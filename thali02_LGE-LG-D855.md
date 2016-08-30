#### Test 828946826174a68_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 17:08:00.385  1802  1819 I art     : Explicit concurrent mark sweep GC freed 25057(1736KB) AllocSpace objects, 18(288KB) LOS objects, 51% free, 29MB/61MB, paused 2.611ms total 55.856ms
08-30 17:08:00.429  4607  6544 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 258 ms] updated apps [took 258 ms] 
08-30 17:08:00.499  6547  6547 D DocsApplication: Installing DEX configuration.
08-30 17:08:00.518  6547  6547 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-30 17:08:00.523  6547  6547 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2a0cfbc5 com.google.android.apps.docs}
08-30 17:08:00.540  6547  6547 D TAG     : onCreate()
08-30 17:08:00.574  6547  6547 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 17:08:00.928   338   414 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-30 17:08:00.934  3206  6571 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 17:08:01.397  6572  6572 D AndroidRuntime: 
08-30 17:08:01.397  6572  6572 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:08:01.401  6572  6572 D AndroidRuntime: CheckJNI is OFF
08-30 17:08:01.435  1802  4794 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-30 17:08:01.485  1802  4794 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 17:08:01.541  1802  4794 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-30 17:08:01.580  6572  6572 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 17:08:01.584  1070  1969 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 17:08:01.599  1924  2830 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 17:08:01.602  1070  1969 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 17:08:01.603  1070  1969 D ActivityManager: setTaskToReturnTo : TaskRecord{25d4a832 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:08:01.603  1070  1969 D ActivityManager: setTaskToReturnTo : TaskRecord{25d4a832 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:08:01.605  1070  1969 D WindowStateEx: AppWindowTokenEx init.. 
08-30 17:08:01.606   344   357 E GBMv2   : DFP En is all cleared set to be enabled
08-30 17:08:01.643  1070  1969 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6593 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:08:01.645  6572  6572 D AndroidRuntime: Shutting down VM
08-30 17:08:01.689  1924  2830 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 17:08:01.689  1924  2830 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32539b51 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 17:08:01.690  1924  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 17:08:01.690  1924  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1891ffb6 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 17:08:01.753  6593  6593 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 17:08:01.837  6593  6593 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 17:08:01.844  6593  6593 I LibraryLoader: Loading: webviewchromium
,08-30 17:08:01.847  6593  6593 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3278-3282)
08-30 17:08:01.847  6593  6593 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:08:01.864  6593  6593 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e9bf227}
,08-30 17:08:01.866  6593  6593 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:08:01.866  6593  6593 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:08:01.874  6593  6593 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 17:08:01.875  6593  6593 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:08:01.883   312  2115 V AudioPolicyService: registerClient() client 0xb558ac80, uid 10118
08-30 17:08:01.884  6593  6593 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 17:08:01.884  6593  6593 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 17:08:01.885  6593  6593 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 17:08:01.890  1070  1248 D BluetoothManagerService: Message: 20
08-30 17:08:01.890  1070  1248 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1417b32c:true
,08-30 17:08:01.903  6593  6593 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:08:01.903  6593  6593 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:08:01.903  6593  6593 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:08:01.903  6593  6593 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:08:01.903  6593  6593 I Adreno-EGL: Remote Branch: 
08-30 17:08:01.903  6593  6593 I Adreno-EGL: Local Patches: 
08-30 17:08:01.903  6593  6593 I Adreno-EGL: Reconstruct Branch: 
08-30 17:08:01.987  6593  6622 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 17:08:01.995  6593  6593 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 17:08:02.003  6547  6547 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:02.003  6547  6547 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:02.011  6593  6593 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:08:02.015  6593  6593 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 17:08:02.017  6593  6593 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 17:08:02.020  6593  6593 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 17:08:02.020  6593  6593 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 17:08:02.032  6593  6593 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 17:08:02.040  6593  6593 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:08:02.040  6593  6593 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:08:02.076  6593  6640 D OpenGLRenderer: Render dirty regions requested: true
08-30 17:08:02.076  6593  6640 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:08:02.083  6593  6640 D OpenGLRenderer: Enabling debug mode 0
08-30 17:08:02.089  6593  6593 D Atlas   : Validating map...
,08-30 17:08:02.092  1070  1978 D SplitWindow: check instance of lgWin Window{2ad90106 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:08:02.121  6129  6129 I LockScreenSettings: New app installed broadcast received ..
,08-30 17:08:02.123  6129  6129 I LockScreenSettings: Number of installed packages  1
08-30 17:08:02.127  6593  6634 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:02.127  6593  6634 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:08:02.131  6547  6547 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-30 17:08:02.181  1070  1739 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:08:02.205  6593  6593 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2f1dab22 time:103640
,08-30 17:08:02.219  1070  2015 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6654 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 17:08:02.222  1070  1249 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +534ms (total +615ms)
08-30 17:08:02.222  1070  1249 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f770983 u0 com.test.thalitest/.MainActivity t6} time:103656
,08-30 17:08:02.272  6654  6654 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 17:08:02.272  6654  6654 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-30 17:08:02.304  1070  2015 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6673 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-30 17:08:02.304  1070  2015 I ActivityManager: Killing 5515:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-30 17:08:02.311  6593  6593 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 17:08:02.338  6593  6593 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 17:08:02.338  6593  6593 I chromium: 
,08-30 17:08:02.354  6593  6634 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 17:08:02.354  6593  6634 I chromium: 
,08-30 17:08:02.366  1070  1942 W libprocessgroup: failed to open /acct/uid_10005/pid_5515/cgroup.procs: No such file or directory
,08-30 17:08:02.433  6673  6673 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-30 17:08:02.436  6593  6690 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
08-30 17:08:02.447  6673  6673 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 17:08:02.447  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-30 17:08:02.447  6593  6690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:08:02.447  6593  6690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:08:02.447  6593  6690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:08:02.447  6593  6690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:08:02.447  6593  6690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:08:02.447  6593  6690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2636e646 added. We now have 1 listener(s)
08-30 17:08:02.452  1070  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:02.454  6593  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 17:08:02.456  6593  6690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:02.457  6593  6690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:02.457  6593  6690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:02.464  1070  1908 I ActivityManager: Killing 5866:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 17:08:02.465  6593  6690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d1e5f5d added. We now have 1 listener(s)
08-30 17:08:02.466  6593  6690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:02.469  1070  1525 D WifiService: New client listening to asynchronous messages
08-30 17:08:02.472  6593  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:08:02.472  6593  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:08:02.472  6593  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:08:02.472  6593  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:08:02.472  6593  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 17:08:02.534  1070  1745 W libprocessgroup: failed to open /acct/uid_10072/pid_5866/cgroup.procs: No such file or directory
08-30 17:08:02.538  6593  6690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:02.544  1070  1759 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:02.547  6593  6690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-30 17:08:02.558  6593  6690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:02.559  6593  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:02.559  6593  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 17:08:02.559  6593  6690 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:02.561  6593  6690 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:08:02.563  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:02.566  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:02.616  6593  6593 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:08:03.356  6593  6694 W jxcore-log: Initializing JXcore engine
08-30 17:08:03.356  6593  6694 W jxcore-log: JXcore engine is ready
,08-30 17:08:03.386  6694  6694 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[6124]" dev="sockfs" ino=6124 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 17:08:03.386  6694  6694 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 17:08:03.386  6694  6694 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7627]" dev="sockfs" ino=7627 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 17:08:03.386  6694  6694 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 17:08:03.386  6694  6694 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32866]" dev="sockfs" ino=32866 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 17:08:03.411  6593  6694 W jxcore-log: Starting JXcore engine
,08-30 17:08:03.436   344   359 E GBMv2   : DFP En is all cleared set to be enabled
08-30 17:08:03.436   344   359 E GBMv2   : Set value is all cleared set the max
08-30 17:08:03.436   344   359 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 17:08:03.490  6593  6694 W jxcore-log: Platform android
08-30 17:08:03.490  6593  6694 W jxcore-log: 
08-30 17:08:03.490  6593  6694 W jxcore-log: Process ARCH arm
08-30 17:08:03.490  6593  6694 W jxcore-log: 
,08-30 17:08:03.691  6593  6694 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:08:03.691  6593  6694 I jxcore-log: 
,08-30 17:08:03.691  6593  6694 W jxcore-log: JXcore engine is started
,08-30 17:08:03.698  6593  6690 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:08:03.700  6593  6593 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 17:08:04.976  2779  2779 I MusicWidget: mDelayedStopHandler : unbind
08-30 17:08:04.979  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,08-30 17:08:04.979  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,08-30 17:08:04.981  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 17:08:04.984  2110  2110 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 17:08:04.985  2110  2110 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 17:08:04.986  2110  2110 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-30 17:08:04.989  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-30 17:08:04.989  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 17:08:04.990  1070  1597 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@16d660edcom.lge.music.MediaPlaybackService$5@2f1dab22
08-30 17:08:04.991  2110  2110 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 17:08:04.992  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:04.993  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:04.994  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:04.995  2110  2110 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1acb89c3
08-30 17:08:04.996  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 17:08:05.000  2110  2110 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 17:08:05.001  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:05.001  2110  2110 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 17:08:05.002  2110  2110 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 17:08:05.002  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:05.005  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:05.015  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 17:08:05.017  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:05.018  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 17:08:05.019  2110  2110 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-30 17:08:05.020  2110  2110 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 17:08:05.020  2110  2110 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 17:08:05.021  2110  2110 V MediaPlayer[Native]: reset
08-30 17:08:05.027  2110  2110 V MediaPlayer[Native]: setListener
08-30 17:08:05.027  2110  2110 V MediaPlayer[Native]: disconnect
08-30 17:08:05.027  2110  2110 V MediaPlayer[Native]: destructor
08-30 17:08:05.027   312  2119 V AudioFlinger: releasing 18 from 2110 for -1
08-30 17:08:05.027   312  2119 V AudioFlinger:  decremented refcount to 0
08-30 17:08:05.027   312  2119 V AudioFlinger: purging stale effects
08-30 17:08:05.027  2110  2110 V MediaPlayer[Native]: disconnect
,08-30 17:08:05.030  2110  2110 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-30 17:08:05.032  2110  2110 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 17:08:05.032  2110  2110 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-30 17:08:05.033  2110  2110 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-30 17:08:05.033  2110  2110 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 17:08:05.034  2110  2110 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 17:08:05.034  2110  2110 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 403859891
08-30 17:08:05.034  2110  2110 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 403859891
08-30 17:08:05.041  2110  2110 I SmartShareClient: [SmartShareManagerClient] terminate service: 2110/MediaPlaybackService/516329281
08-30 17:08:05.044  2110  2110 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 17:08:05.044  2110  2110 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@f7dbb70
,08-30 17:08:05.048  2110  2110 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 17:08:05.049  2110  2110 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-30 17:08:05.050  2110  2110 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 17:08:05.050  2110  2110 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-30 17:08:05.053  1070  1942 I ActivityManager: Killing 5715:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-30 17:08:05.065  2110  2110 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
,08-30 17:08:05.068  5691  5691 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-30 17:08:05.068  5691  5691 W System.err: android.os.DeadObjectException
,08-30 17:08:05.069  5691  5691 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:08:05.069  5691  5691 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 17:08:05.069  5691  5691 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 17:08:05.069  5691  5691 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 17:08:05.069  5691  5691 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 17:08:05.069  5691  5691 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 17:08:05.069  5691  5691 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:08:05.069  5691  5691 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:08:05.069  5691  5691 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:08:05.069  5691  5691 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:08:05.069  5691  5691 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:05.069  5691  5691 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:05.069  5691  5691 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:08:05.069  5691  5691 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:08:05.069  5691  5691 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 17:08:05.069  5691  5691 W System.err: android.os.DeadObjectException
08-30 17:08:05.070  5691  5691 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:08:05.070  5691  5691 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 17:08:05.070  5691  5691 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,08-30 17:08:05.070  5691  5691 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 17:08:05.070  5691  5691 W System.err: ,	,at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 17:08:05.070  5691  5691 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 17:08:05.070  5691  5691 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:08:05.070  5691  5691 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95),
08-30 17:08:05.070  5691  5691 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:08:05.070  5691  5691 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:08:05.070  5691  5691 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-30 17:08:05.070  5691  5691 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:05.070  5691  5691 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:08:05.070  5691  5691 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 17:08:05.070  5691  5691 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 17:08:05.071  5691  5691 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 17:08:05.277  1070  1739 W libprocessgroup: failed to open /acct/uid_1000/pid_5715/cgroup.procs: No such file or directory
,08-30 17:08:05.286  1070  1739 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 17:08:05.290  5691  5691 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 17:08:05.291  1070  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=367520804, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1070
08-30 17:08:05.293  5691  5691 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 17:08:05.337  1070  1908 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6701 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 17:08:05.346  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
08-30 17:08:05.370  1070  1070 D PowerManagerServiceEx: releaseWakeLockInternal: lock=367520804 [*alarm*], flags=0x0
08-30 17:08:05.371  4486  6698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-30 17:08:05.397  5691  5691 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 17:08:05.449  6701  6701 D UEI.SmartControl: Quickset Services start...
08-30 17:08:05.451  6701  6701 I UEI.SmartControl: Manufacture = LGE
08-30 17:08:05.451  6701  6701 D UEI.SmartControl: Id = LGNevo
08-30 17:08:05.452  6701  6701 D UEI.SmartControl: File observer start...
,08-30 17:08:05.457  6701  6701 E UEI.SmartControl: IR Port is disabled: false
08-30 17:08:05.457  6701  6701 D UEI.SmartControl: Starting file observer...
08-30 17:08:05.457  6701  6701 D UEI.SmartControl: Extracting JNI libs...
08-30 17:08:05.457  6701  6701 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 17:08:05.531  6701  6701 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 17:08:05.531  6701  6701 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 17:08:05.531  6701  6701 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 17:08:05.555  6701  6701 I UEI.SmartControl: --- Selecting new region: 6
,08-30 17:08:05.557  6701  6701 I UEI.SmartControl: Model = LG-D855
08-30 17:08:05.558  6701  6701 D UEI.SmartControl: QS Service created
08-30 17:08:05.568  6701  6701 I UEI.SmartControl: Service initServices...
08-30 17:08:05.571  6701  6701 D UEI.SmartControl: QS start get config
,08-30 17:08:05.604  6701  6701 D UEI.SmartControl: Loading JNI Libs...
,08-30 17:08:05.842  6701  6701 I UEI.SmartControl: Supports setup maps: true
08-30 17:08:05.846  6701  6701 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 17:08:05.846  6701  6701 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 17:08:05.846  6701  6701 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 17:08:05.846  6701  6701 I UEI.SmartControl: ### init IR Blaster...
,08-30 17:08:05.851  6701  6701 D serial_port: Configuring serial port
,08-30 17:08:05.854  6701  6701 E UEI.SmartControl: UEIBLaster setting for 616
08-30 17:08:05.854  6701  6701 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 17:08:05.855  6701  6701 I UEI.SmartControl: configuring settings for MAXQ616
08-30 17:08:05.855  6701  6701 I UEI.SmartControl: Get version...
08-30 17:08:05.871  6701  6738 D UEI.SmartControl: serial port data available: 21
,08-30 17:08:05.900  6701  6701 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 17:08:05.900  6701  6701 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 17:08:05.901  6701  6701 I UEI.SmartControl: QS saving settings...
,08-30 17:08:05.902  6701  6701 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 17:08:05.919  6701  6738 D UEI.SmartControl: serial port data available: 4
,08-30 17:08:05.953  6701  6741 I UEI.SmartControl: Device manager: loading config....
08-30 17:08:05.953  6701  6741 D UEI.SmartControl: ----------- loading internal config...
08-30 17:08:05.956  6701  6701 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 17:08:05.959  6701  6701 E UEI.SmartControl: Services init done
08-30 17:08:05.959  6701  6701 D UEI.SmartControl: QS Service init finished
08-30 17:08:05.961  6701  6701 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 17:08:05.961  6701  6701 D UEI.SmartControl: QS Service version code: 201091
08-30 17:08:05.962  6701  6701 D UEI.SmartControl: Service requested: Control
08-30 17:08:05.967  6701  6741 E UEI.SmartControl: Loading SETTINGS...
08-30 17:08:05.967  6701  6701 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 17:08:05.970  1070  1739 I ActivityManager: Killing 5691:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 17:08:05.977  6701  6741 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 17:08:05.992  6701  6740 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 17:08:05.992  6701  6740 D UEI.SmartControl: -----service ready thread exits
08-30 17:08:06.058  1070  1969 W libprocessgroup: failed to open /acct/uid_10112/pid_5691/cgroup.procs: No such file or directory
08-30 17:08:06.060  6701  6701 D UEI.SmartControl: Internal service binding...
,08-30 17:08:06.084  6547  6547 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 17:08:06.089  1070  2000 I ActivityManager: Killing 6257:com.android.calendar/u0a13 (adj 15): empty #17
,08-30 17:08:06.216  1070  1937 W libprocessgroup: failed to open /acct/uid_10013/pid_6257/cgroup.procs: No such file or directory
,08-30 17:08:07.067  6547  6630 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 17:08:09.458  1802  6455 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 17:08:09.466   308  6766 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 17:08:09.466   308  6766 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-30 17:08:09.467   308  6766 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-30 17:08:10.953  6701  6742 D UEI.SmartControl: Internal timer expired: 1
,08-30 17:08:10.954  6701  6742 D UEI.SmartControl: unbind internal service
,08-30 17:08:10.956  6701  6701 D UEI.SmartControl: Service.onUnbind: IControl
08-30 17:08:10.959  6701  6701 D UEI.SmartControl: Service.onDestroy
08-30 17:08:10.959  6701  6701 D UEI.SmartControl: Lock is in USE false
08-30 17:08:10.959  6701  6701 D UEI.SmartControl: unbind internal service
08-30 17:08:10.960  6701  6701 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1acb89c3
08-30 17:08:10.960  6701  6701 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 17:08:10.961  6701  6701 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 17:08:10.961  6701  6701 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 17:08:10.961  6701  6701 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 17:08:10.961  6701  6701 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 17:08:10.961  6701  6701 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 17:08:10.961  6701  6701 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 17:08:10.961  6701  6701 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 17:08:10.961  6701  6701 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.962  6701  6701 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:08:10.962  6701  6701 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:08:10.962  6701  6701 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.962  6701  6701 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.962  6701  6701 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:08:10.962  6701  6701 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:08:10.962  6701  6701 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1acb89c3
08-30 17:08:10.966  6701  6701 D serial_port: close(fd = 25)
,08-30 17:08:10.973  6701  6701 I UEI.SmartControl: Serial port is closed.
08-30 17:08:10.973  6701  6701 I UEI.SmartControl: Serial port is closed.
08-30 17:08:10.973  6701  6701 D UEI.SmartControl: Blaster closed
08-30 17:08:10.973  6701  6701 D UEI.SmartControl: Shut down QS...
08-30 17:08:10.973  6701  6701 D UEI.SmartControl: Stopping QS lib
08-30 17:08:10.973  6701  6701 D UEI.SmartControl: QS lib stop result = true
08-30 17:08:10.973  6701  6701 D UEI.SmartControl: Stopped QS lib
08-30 17:08:10.974  6701  6701 D UEI.SmartControl: Stopped file observer...
08-30 17:08:10.974  6701  6701 D UEI.SmartControl: QS shutdown complete
,08-30 17:08:13.512  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
,08-30 17:08:13.513  1802  1802 I ConfigFetchService: stopping self
,08-30 17:08:13.521  2160  2160 I ConfigService: onDestroy
,08-30 17:08:13.828  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:08:13.828  6593  6694 I jxcore-log: 
08-30 17:08:13.830  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:08:13.830  6593  6694 I jxcore-log: 
,08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:13.836  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:13.838  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:13.841  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:08:13.841  6593  6694 I jxcore-log: 
08-30 17:08:13.843  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:08:13.843  6593  6694 I jxcore-log: 
,08-30 17:08:14.346  6593  6694 D executeNativeTests: Running unit tests
,08-30 17:08:14.430  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:08:14.430  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 added. We now have 2 listener(s)
,08-30 17:08:14.431  1070  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:14.433  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 17:08:14.433  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:08:14.433  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-30 17:08:14.433  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:14.433  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 added. We now have 2 listener(s)
08-30 17:08:14.433  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-30 17:08:14.433  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:14.436  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
,08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-30 17:08:14.438  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:14.439  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-30 17:08:14.439  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:14.440  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 17:08:14.441  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.444  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:08:14.444  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:14.444  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-30 17:08:14.446  6593  6694 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 17:08:14.447  6593  6694 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-30 17:08:14.447  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-30 17:08:14.447  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:14.447  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:14.447  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.448  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.448  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-30 17:08:14.448  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.449  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:14.449  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 17:08:14.449  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:14.449  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 removed from the list,
08-30 17:08:14.449  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.449  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 removed from the list
08-30 17:08:14.449  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.449  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.450  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.450  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.451  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.451  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.451  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:08:14.451  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list,
08-30 17:08:14.452  6593  6694 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 17:08:14.453  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.453  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:14.453  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.453  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.453  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.453  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:14.453  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.453  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.453  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list,
08-30 17:08:14.453  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.453  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:14.453  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.453  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:14.453  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.454  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:14.454  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.454  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:08:14.454  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list,
08-30 17:08:14.458  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:08:14.458  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010],
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-30 17:08:14.459  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:08:14.459  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.459  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.459  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.459  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-30 17:08:14.460  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.460  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.460  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.460  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:08:14.460  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.460  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.460  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.460  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 17:08:14.460  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.460  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.461  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.461  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:08:14.461  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.461  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.462  6593  6694 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:08:14.464  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:14.466  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:14.467  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:14.467  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:14.468  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.469  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.469  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-30 17:08:14.469  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:14.469  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:14.469  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:14.469  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:14.472  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:08:14.472  1070  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:14.477  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:14.483  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-30 17:08:14.484  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 17:08:14.485  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:14.486  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 17:08:14.487  6593  6694 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:08:14.487  6593  6694 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:08:14.490  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:14.490  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.490  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.490  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:08:14.490  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.490  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:14.490  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.490  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:08:14.490  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.490  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.490  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:14.491  6593  6694 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:08:14.492  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:14.494  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:14.495  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:14.495  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:14.496  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.496  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:14.496  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:14.497  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:14.497  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:14.497  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:14.498  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.499  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:08:14.500  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:14.501  6593  6694 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:08:14.501  6593  6694 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:08:14.502  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.502  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.502  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.502  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.502  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.502  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:14.502  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.502  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.502  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.502  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.502  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.502  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.502  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.504  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.504  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.506  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.506  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.506  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.506  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.507  6593  6694 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:08:14.508  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:14.511  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:14.512  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:14.512  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:14.512  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:14.512  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:14.513  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:14.513  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:14.513  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:14.515  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.517  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.518  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:14.518  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:14.519  6593  6694 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:08:14.520  6593  6694 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:08:14.520  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.520  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.520  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.521  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.522  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.522  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.522  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.522  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.522  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:14.522  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.522  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.522  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.522  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.522  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.522  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.522  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.523  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.523  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.523  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.523  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.523  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.523  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.524  6593  6694 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 17:08:14.524  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.524  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.524  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.524  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.524  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.524  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.524  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.524  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.524  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.524  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.524  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.524  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.524  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.524  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.525  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.525  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.536  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.536  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.536  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.536  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
,08-30 17:08:14.539  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:08:14.540  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.540  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.540  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.540  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.540  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.541  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.541  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.541  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.541  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.541  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.541  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.541  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.541  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.541  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.543  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.543  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.543  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.543  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.543  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.544  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.546  6593  6694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 17:08:14.546  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.546  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.546  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.546  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.546  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.546  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.546  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.546  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.546  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.546  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.546  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.547  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.547  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.547  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.548  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.548  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.548  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.548  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.548  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.548  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.549  6593  6694 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 17:08:14.549  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.549  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.549  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.550  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.550  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.550  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.550  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.550  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.550  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.550  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.550  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.550  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.550  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.550  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.552  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.552  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.552  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.552  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.552  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.552  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.553  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:08:14.553  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:14.553  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:14.553  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:14.554  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:08:14.554  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:14.554  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.554  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.554  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.554  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.555  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.555  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.555  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.555  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.555  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.555  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.555  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.555  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.555  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.555  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.556  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.556  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.556  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.556  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.556  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.556  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.557  6593  6694 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:14.557  6593  6694 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:08:14.558  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:08:14.561  6593  6694 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:14.561  6593  6694 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:08:14.561  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:08:14.562  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:08:14.562  6593  6694 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 17:08:14.562  6593  6694 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:14.562  6593  6694 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 17:08:14.563  6593  6694 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:14.563  6593  6694 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:14.563  6593  6694 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 17:08:14.563  6593  6694 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:14.563  6593  6694 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:14.563  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 17:08:14.564  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 17:08:14.566  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 17:08:14.566  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 17:08:14.566  1070  1173 I ActivityManager: Waited long enough for: ServiceRecord{3e568088 u0 com.google.android.gms/.wearable.service.WearableService}
08-30 17:08:14.566  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 17:08:14.567  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 17:08:14.567  6593  6694 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 17:08:14.567  6593  6694 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:14.567  6593  6694 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 17:08:14.567  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.567  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.567  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.568  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.568  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.568  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.568  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 17:08:14.568  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.568  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.568  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.568  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.569  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.569  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.569  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.569  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.570  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.570  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.570  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.570  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.570  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.570  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.571  6593  6694 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 17:08:14.571  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.572  6593  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-30 17:08:14.572  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.572  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.574  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.574  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.574  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.574  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.574  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.574  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.574  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.574  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.574  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.574  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.574  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.575  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:14.575  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.576  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.576  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.577  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.577  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.577  6593  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-30 17:08:14.578  6593  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-30 17:08:14.579  6593  6694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 17:08:14.580  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.580  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.580  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.581  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.581  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.581  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.581  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.581  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.581  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.581  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.581  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.581  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.582  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.582  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.583  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.583  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.584  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.584  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.584  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.584  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.585  6593  6694 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 17:08:14.585  6593  6694 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 17:08:14.585  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:14.585  6593  6694 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 17:08:14.585  6593  6694 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:08:14.585  6593  6694 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 17:08:14.586  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:08:14.586  6593  6694 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 17:08:14.586  6593  6694 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:08:14.586  6593  6694 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:08:14.586  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:08:14.586  6593  6694 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 17:08:14.586  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.586  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.586  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.586  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.586  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.586  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.586  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.586  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.587  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.587  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.587  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.587  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.587  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.587  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.587  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.587  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.588  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.588  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.588  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.588  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.588  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.588  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.588  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.589  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.589  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.589  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.589  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.589  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.589  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.589  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.589  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.589  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.589  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.589  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.589  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.589  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.589  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.589  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.589  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.589  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.589  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.589  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.589  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.589  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.589  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.589  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.589  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.589  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.589  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.594  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.594  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.595  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.595  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.595  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.595  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.597  6593  6694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 17:08:14.597  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:14.598  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 17:08:14.599  6593  6694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 17:08:14.599  6593  6694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 17:08:14.599  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 17:08:14.599  6593  6593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 17:08:14.599  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:14.600  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.600  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 17:08:14.601  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 17:08:14.601  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 17:08:14.601  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.601  6593  6694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 17:08:14.601  6593  6593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 17:08:14.601  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.601  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.601  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:14.601  6593  6694 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:14.601  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:14.602  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:14.602  1070  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:14.602  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:14.602  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:14.602  6593  6694 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:14.602  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.602  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.604  6593  6694 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:14.605  6593  6593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:14.605  6593  6593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:14.605  6593  6593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:14.605  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.605  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.605  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.605  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.606  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.606  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.606  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.606  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.606  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.606  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.606  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.606  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.606  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.606  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.606  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.607  6593  6775 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:14.607  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.607  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.607  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.607  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.608  6593  6694 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 17:08:14.608  3896  4018 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-30 17:08:14.608  6593  6694 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:08:14.608  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:14.608  6593  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:14.608  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.609  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.609  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.609  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.609  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.609  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.609  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.609  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.609  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.609  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.609  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.609  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.609  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.609  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.610  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.610  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.610  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.610  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.611  6593  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: c,loseBluetoothServerSocket: Bluetooth server socket closed
08-30 17:08:14.611  6593  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 17:08:14.611  6593  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 17:08:14.611  6593  6593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 17:08:14.612  1070  1759 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:14.613  1070  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:14.613  1070  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:14.614  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.614  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.615  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.615  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.615  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.615  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.615  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.616  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.616  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.616  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.616  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.616  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.617  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.617  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.618  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.618  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.618  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.618  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.620  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:14.620  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:14.620  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:14.620  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:14.620  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.620  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.620  6593  6694 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375a9f96 not in the list
08-30 17:08:14.620  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.620  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryMana,ger@3239d717 not in the list
08-30 17:08:14.620  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:14.620  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.620  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.620  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:14.620  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:14.621  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:14.621  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:14.621  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:14.621  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3239d717 not in the list
08-30 17:08:14.623  6593  6694 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 17:08:14.623  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:14.624  6593  6694 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 17:08:14.624  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:14.624  6593  6694 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 17:08:14.624  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:08:14.627  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 17:08:14.627  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 17:08:14.628  6593  6694 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 17:08:14.628  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:08:14.628  6593  6694 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 17:08:14.628  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 17:08:14.628  6593  6694 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 17:08:14.629  6593  6694 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 17:08:14.629  6593  6694 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 17:08:14.630  6593  6694 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 17:08:14.631  6593  6694 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 17:08:14.631  6593  6694 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 17:08:14.631  6593  6694 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 17:08:14.631  6593  6694 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 17:08:14.632  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:14.632  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@55af29c added. We now have 2 listener(s)
08-30 17:08:14.632  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:14.635  6593  6694 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 17:08:14.636  1070  1888 D WifiServiceImplEx: setWifiEnabled: true pid=6593, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:08:14.636  1070  1888 D WifiService: setWifiEnabled: true pid=6593, uid=10118
08-30 17:08:14.636  1070  1888 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:08:14.638  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:14.638  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e4d04a5 added. We now have 3 listener(s)
08-30 17:08:14.638  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:14.643  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:14.643  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ad3707a added. We now have 4 listener(s)
08-30 17:08:14.643  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:14.645  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:14.645  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30a8402b added. We now have 5 listener(s)
08-30 17:08:14.645  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:14.648  1070  1888 D WifiServiceImplEx: setWifiEnabled: false pid=6593, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:08:14.648  1070  1888 D WifiService: setWifiEnabled: false pid=6593, uid=10118
08-30 17:08:14.648  1070  1888 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:08:14.660  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:14.661  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:14.661  1070  1070 D Ulp_jni : JNI:system_update. Event-4
08-30 17:08:14.661  1070  1437 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:14.662  1070  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:14.662  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:14.662  1070  1942 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1abacf0 mBinding = false
08-30 17:08:14.662  1070  1437 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:14.663  1070  1437 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:14.663  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:14.663  1070  1437 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 17:08:14.664  1070  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:14.664  1070  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:08:14.664  1070  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:08:14.665  1070  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:08:14.671  1070  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 17:08:14.672  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:08:14.672  2642  2642 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:08:14.672  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.672  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.672  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:08:14.672  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:14.674  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:08:14.674  1070  2850 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.674   308   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:08:14.682  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:14.683  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:14.683  1070  1070 D Ulp_jni : JNI:system_update. Event-4
08-30 17:08:14.683  1070  1248 D BluetoothManagerService: Message: 2
08-30 17:08:14.684  1070  1248 D BluetoothManagerService: Sending off request.
08-30 17:08:14.684  3896  3915 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 17:08:14.685  3896  3991 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 17:08:14.685  3896  3991 D BluetoothAdapterProperties: Setting state to 13
08-30 17:08:14.685  3896  3991 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:08:14.686  3896  3991 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 17:08:14.686  3896  3991 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 17:08:14.692  3896  3999 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:08:14.693  3896  3991 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:08:14.694  3896  3991 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 17:08:14.695  3896  4245 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 17:08:14.696  3896  4247 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:14.697  3896  4322 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:14.697  3896  4323 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:14.698  3896  4328 V BluetoothSapService: Accept thread ex,ception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:14.700  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 17:08:14.700  3896  4081 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 17:08:14.702  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:14.702  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 17:08:14.705  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:08:14.705  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 17:08:14.706  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 17:08:14.707  3896  4081 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 17:08:14.724  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:14.724  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 17:08:14.724  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-30 17:08:14.735  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:14.736  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:14.737  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.737  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:14.757  1070  1888 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-30 17:08:14.757  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.757  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.759  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 17:08:14.759  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.759  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-30 17:08:14.765  1070  1173 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6781 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 17:08:14.770  1070  1070 D WifiHS20: hidePasspointNotification off =false
08-30 17:08:14.770  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.770  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.770  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:14.772  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-30 17:08:14.773  1070  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 17:08:14.773  1070  1527 D DSQN    : disableDataServiceNotify
08-30 17:08:14.774  1070  1527 D DSQN    : stop dsqn bin
08-30 17:08:14.774  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:14.774  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:14.776  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:14.780  3896  3896 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:14.781  3896  3896 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:08:14.781  3896  3896 V BtOppService: Receiver DISABLED_ACTION 
08-30 17:08:14.781  3896  3896 V BluetoothMapService: Handler(): got msg=4
08-30 17:08:14.781  3896  3896 D BluetoothMapService: MAP Service closeService in
08-30 17:08:14.781  3896  3896 D BluetoothMapMasInstance: MAP Service shutdown
08-30 17:08:14.781  3896  3896 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:08:14.781  3896  3896 V BluetoothMapService: MAP Service closeService out
08-30 17:08:14.782   308  6795 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 17:08:14.782  3896  3896 I BtOppRfcommListener: stopping Accept Thread
08-30 17:08:14.782  3896  3896 V BtOppRfcommListener: close mBtServerSocket
08-30 17:08:14.782  3896  3896 V BtOppRfcommListener: waiting for thread to terminate
08-30 17:08:14.783  3896  4322 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 17:08:14.783  3896  3896 V BtOppRfcommListener: done waiting for thread to terminate
08-30 17:08:14.785  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:14.785  1070  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 17:08:14.786  1070  1246 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 17:08:14.787  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:14.787  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:14.788  1070  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:14.788  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.788  1070  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,08-30 17:08:14.790  1070  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 17:08:14.790  1070  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 17:08:14.791  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:14.791  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 17:08:14.795  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 17:08:14.796  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.796  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.796  1070  2825 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 17:08:14.797  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 17:08:14.833  1070  1173 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 17:08:14.836  1070  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:14.836  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:14.836  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.836  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.836  1070  1383 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@761671d
08-30 17:08:14.836  1070  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:14.836  1070  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.837  1070  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:14.837  3896  3896 V BtOppService: onDestroy
08-30 17:08:14.837  1070  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:14.837  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.837  1070  1527 D NetworkManagementService: Removing idletimer
08-30 17:08:14.837  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.837  1070  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.837  1070  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.837  1070  1383 D LGWifiP2pService: P2pDisablingState
08-30 17:08:14.838  1070  1383 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.838  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.838  1070  1383 D LGWifiP2pService: p2p socket connection lost
08-30 17:08:14.838  1070  1383 D LGWifiP2pService: P2pDisabledState
08-30 17:08:14.838  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.838  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:14.838  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:08:14.839  1070  1437 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:08:14.839  1070  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 17:08:14.839  1070  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.839  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.840  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:14.840  1070  1437 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:14.840  1070  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:14.841  1070  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 17:08:14.841  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:08:14.841  2642  2642 I wpa_suppli,cant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:08:14.842  1070  1070 D WifiHS20: hidePasspointNotification off =false
08-30 17:08:14.842  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:08:14.842  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.842  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:14.842  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.842  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:14.842  1070  1070 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:08:14.842  1070  1070 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:08:14.842  1070  1070 D RttService: SCAN_AVAILABLE : 1
08-30 17:08:14.842  1070  1070 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:08:14.842  1070  1070 D LocSvc_java: getAGpsConnectionInfo connType - 4
,08-30 17:08:14.843  1070  1070 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:08:14.843  1070  1070 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:08:14.843  1070  1070 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:08:14.843  1070  1070 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:08:14.843  1070  1070 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:08:14.843  1070  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 17:08:14.843  1070  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 17:08:14.844  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:08:14.844   308   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:08:14.848  1070  1070 D WifiHS20: hidePasspointNotification off =false
08-30 17:08:14.848  1070  1383 D LGWifiP2pService: P2pDisabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.848  1070  1383 D LGWifiP2pService: DefaultState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.848  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.848  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.848  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:14.848  1070  1541 D WifiScanningService: DefaultState got{ when=-6ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.849  1070  1542 D RttService: EnabledState got{ when=-6ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.849  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 17:08:14.849  1924  1924 D WfdsService: WifiP2pState is changed : false
08-30 17:08:14.849  1924  2344 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 17:08:14.850  1924  2344 D WfdsService: Set the WFDS Monitor: false
08-30 17:08:14.852  1924  2344 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:08:14.852  1924  2344 D WfdsService: STATE : WfdsDisabledState - enter
08-30 17:08:14.852  1924  2746 D CtrlSupplicant: Received on exit socket, terminate
08-30 17:08:14.852  1924  2746 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 17:08:14.853  1924  2746 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 17:08:14.853  1924  2746 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 17:08:14.853  1924  2345 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 17:08:14.853  1924  2344 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 17:08:14.853  1070  1437 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 17:08:14.855  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:14.855  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:14.856  1070  1437 D WifiNative-p2p0: TERMINATE: returned true
08-30 17:08:14.856  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:14.,856  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:14.856  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:08:14.856  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:14.858  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-30 17:08:14.868  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 17:08:14.869  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:14.869  1070  1070 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 17:08:14.870  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:14.870  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:14.870  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.870  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:14.896  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:08:14.897  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:14.898  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:14.911  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:08:14.912  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:14.912  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:14.912  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:08:14.912  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:14.913  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:14.917  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:14.918  1070  1739 I art     : Explicit concurrent mark sweep GC freed 46381(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.446ms total 206.168ms
08-30 17:08:14.919  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:14.926  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:14.926  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:14.927  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.927  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:14.927  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:14.928  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.928  3896  3896 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 17:08:14.930  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:14.937  2642  2642 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 17:08:14.937  2642  2642 I wpa_supplicant: monitor socket send errors count : 1
08-30 17:08:14.937  2642  2642 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1924-2\x00 that cannot receive messages
08-30 17:08:14.937  1070  2850 D DhcpStateMachine: StoppedState
08-30 17:08:14.937  1070  2850 D DhcpStateMachine: StoppedState{ when=-94ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.937  1070  2702 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 17:08:14.937  1070  2702 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 17:08:14.938  1070  1437 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 17:08:14.938  1070  1437 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 17:08:14.939  6805  6805 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:14.939  6805  6805 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 17:08:14.940  6805  6805 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:08:14.940  6805  6805 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 17:08:14.941  6805  6805 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:08:14.941  6805  6805 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:14.978  6781  6781 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 17:08:14.979  6781  6781 W LG Account v2.2: No ProfileInfo entries
08-30 17:08:14.979  6781  6781 I LG Account v2.2: isEnabled: false
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Country: EU
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Operator: OPEN
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Ranking support: false
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Comfort support: false
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Accessory: true
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Health device: true
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Extra Pedometer: false
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Blood glucose device: false
08-30 17:08:14.979  6781  6781 I Feature : [Lifetracker]Device Number: 3
,08-30 17:08:14.986  2642  2642 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:08:14.987  2642  2642 W wpa_supplicant: USIM:  scard_deinit function
08-30 17:08:14.987  1070  2702 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 17:08:14.987  1070  2702 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:08:14.987  1070  2702 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:08:14.987  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:14.987  1070  2702 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 17:08:14.987  1070  2702 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:14.987  1070  2702 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:14.987  1070  1248 D Tethering: InitialState.processMessage what=4
08-30 17:08:14.988  1070  1437 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116410
08-30 17:08:14.989  1070  1437 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116411
08-30 17:08:14.989  1070  1437 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:08:14.989  1070  1437 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:08:15.032  1070  1560 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6827 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:08:15.032  1070  1560 I ActivityManager: Killing 6204:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-30 17:08:15.035  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:08:15.055  2110  2110 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19995
,08-30 17:08:15.076  2642  2642 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 17:08:15.076  1070  1248 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 17:08:15.076  1070  1888 W libprocessgroup: failed to open /acct/uid_10014/pid_6204/cgroup.procs: No such file or directory
08-30 17:08:15.076  1070  2702 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 17:08:15.077  1070  2702 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 17:08:15.077  1070  2702 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 17:08:15.077  1070  1437 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 17:08:15.087  3896  3896 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:08:15.087  3896  3896 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:15.087  3896  3896 V BluetoothPbapReceiver: ***********state = 13
08-30 17:08:15.089  3896  3896 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-30 17:08:15.089  3896  3896 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:15.089  3896  3896 V BluetoothPbapService: state: 13
08-30 17:08:15.089  3896  3896 V BluetoothPbapService: Pbap Service closeService in
,08-30 17:08:15.091  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:15.092  1070  1248 D BluetoothManagerService: Message: 20
08-30 17:08:15.092  3896  3896 V BluetoothPbapService: successfully stopped pbap service
08-30 17:08:15.092  3896  3896 V BluetoothPbapService: Pbap Service closeService out
08-30 17:08:15.092  1070  1248 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@281fe1fa:true
08-30 17:08:15.092  3896  3896 V BluetoothPbapService: Pbap Service onDestroy
08-30 17:08:15.092  3896  3896 V BluetoothPbapService: Pbap Service closeService in
08-30 17:08:15.092  3896  3896 V BluetoothPbapService: Pbap Service closeService out
08-30 17:08:15.093  3896  3896 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 17:08:15.105  6593  6593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 17:08:15.107  1070  1248 D BluetoothManagerService: Message: 30
,08-30 17:08:15.113  1070  1248 D BluetoothManagerService: Message: 30
,08-30 17:08:15.115  6805  6805 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 17:08:15.116  6805  6805 D BluetoothMap: Create BluetoothMap proxy object
08-30 17:08:15.116  1070  1248 D BluetoothManagerService: Message: 30
08-30 17:08:15.119  1070  1248 D BluetoothManagerService: Message: 30
,08-30 17:08:15.121  6805  6805 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 17:08:15.122  6805  6805 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 17:08:15.132  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:08:15.134  6805  6805 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 17:08:15.136  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 17:08:15.138  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 17:08:15.139  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:15.140  1070  1888 I ActivityManager: Killing 6325:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 17:08:15.157  1070  1908 W libprocessgroup: failed to open /acct/uid_10004/pid_6325/cgroup.procs: No such file or directory
,08-30 17:08:15.160  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:15.175  6805  6805 D BluetoothInputDevice: Proxy object connected
,08-30 17:08:15.176  6805  6805 D HidProfile: Bluetooth service connected
08-30 17:08:15.178  1070  1437 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 17:08:15.178  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:15.178  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:15.178  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:08:15.179  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:15.180  6805  6805 D PanProfile: Bluetooth service connected
08-30 17:08:15.181  1924  1924 D WfdsService: Supplicant Connection state is changed : false
08-30 17:08:15.181  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 17:08:15.182  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:15.182  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 17:08:15.182  2496  2496 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:15.183  1070  1481 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 17:08:15.183  1070  1481 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 17:08:15.183  1924  2344 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 17:08:15.183  1924  2344 D WfdsService: Set the WFDS Monitor: false
08-30 17:08:15.183  1924  2344 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:08:15.185  6805  6805 D BluetoothMap: Proxy object connected
08-30 17:08:15.185  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:15.187  6805  6805 D MapProfile: Bluetooth service connected
,08-30 17:08:15.187  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:15.187  6805  6805 D BluetoothMap: getConnectedDevices()
08-30 17:08:15.188  6805  6805 D BluetoothMap: Bluetooth is Not enabled
08-30 17:08:15.189  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 17:08:15.208  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:15.242  6805  6805 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:15.243  6805  6805 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:15.251  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:15.252  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 17:08:15.256  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 17:08:15.259  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 17:08:15.270  1070  1759 I ActivityManager: Killing 6460:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-30 17:08:15.274  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:08:15.370  3896  3896 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 17:08:15.371  3896  3896 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-30 17:08:15.374  1070  1888 W libprocessgroup: failed to open /acct/uid_10008/pid_6460/cgroup.procs: No such file or directory
08-30 17:08:15.376  3896  3896 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 17:08:15.383  1070  1437 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:15.384  1070  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 17:08:15.406  3896  3896 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:15.406  3896  3896 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 17:08:15.484  1070  1759 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6855 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 17:08:15.487  3896  3896 V BluetoothFtpService: Ftp Service onStartCommand
,08-30 17:08:15.487  3896  3896 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:15.487  3896  3896 V BluetoothFtpService: Ftp Service closeService
08-30 17:08:15.487  3896  3896 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 17:08:15.491  3896  3896 V BluetoothFtpService: successfully stopped ftp service
08-30 17:08:15.491  3896  3896 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:15.491  3896  3896 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:15.491  3896  3896 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:15.491  3896  3896 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:15.492  3896  3896 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 17:08:15.492  3896  3896 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 17:08:15.493  3896  3896 V BluetoothFtpService: Ftp Service onDestroy
08-30 17:08:15.493  3896  3896 V BluetoothFtpService: Ftp Service closeService
08-30 17:08:15.493  3896  3896 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:15.493  3896  3896 V BluetoothSapService: state: 13
08-30 17:08:15.493  3896  3896 V BluetoothSapService: Stopping SAP server process
08-30 17:08:15.495  3896  3896 V BluetoothSapService: Sap Service closeSapService in
08-30 17:08:15.495  3896  3896 V BluetoothSapService: Close listen Socket : 
08-30 17:08:15.495  3896  3896 V BluetoothSapService: Close rfcomm Socket : 
08-30 17:08:15.495  3896  3896 V BluetoothSapService: Close sapd  Socket : 
08-30 17:08:15.528   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 480us total 40.283ms
,08-30 17:08:15.549   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 20.153ms
,08-30 17:08:15.569   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 18.180ms
,08-30 17:08:15.605  1070  1969 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6872 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 17:08:15.608  3896  3896 V BluetoothSapService: Sap Service closeSapService out
08-30 17:08:15.609  3896  3896 V BluetoothSapService: Sap Service onDestroy
08-30 17:08:15.609  3896  3896 V BluetoothSapService: Sap Service closeSapService in
08-30 17:08:15.609  3896  3896 V BluetoothSapService: Close listen Socket : 
08-30 17:08:15.609  3896  3896 V BluetoothSapService: Close rfcomm Socket : 
08-30 17:08:15.609  3896  3896 V BluetoothSapService: Close sapd  Socket : 
08-30 17:08:15.619  3896  3896 V BluetoothSapService: Sap Service closeSapService out
,08-30 17:08:15.641  6855  6855 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:08:15.667  6855  6855 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 17:08:15.686  6872  6872 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:08:15.704  3896  3999 D bt_hci_bdroid: cleanup
,08-30 17:08:15.704  3896  4086 I bt_lpm  : LPM is already off!!!
08-30 17:08:15.705  3896  4235 I bt_userial_mct: exiting userial_read_thread
08-30 17:08:15.705  3896  4235 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:08:15.705  3896  4081 W bt-btif : ag scb idx 1 not allocated
08-30 17:08:15.705  3896  4081 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:15.705  3896  3999 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:15.705  3896  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:15.705  3896  4081 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 17:08:15.705  3896  4086 I bt_vendor: hw_epilog_process
08-30 17:08:15.706  3896  3999 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 17:08:15.706  3896  3999 D bt_userial_mct: userial_close
08-30 17:08:15.706  3896  3999 E bt_userial_mct: pthread_join() FAILED result:3
08-30 17:08:15.706  3896  3999 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 17:08:15.707  6855  6855 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 17:08:15.707  6855  6855 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 17:08:15.707  6855  6855 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 17:08:15.708  6855  6855 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 17:08:15.708  6855  6855 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 17:08:15.710  6855  6855 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 17:08:15.715  1070  1888 I ActivityManager: Killing 6022:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-30 17:08:15.717  6855  6855 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-30 17:08:15.755  3896  3999 D bt_hci_bdroid: set_power 0
08-30 17:08:15.755  3896  3999 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:08:15.755  3896  3999 I bt_vendor: bluetooth satus is on
08-30 17:08:15.755  3896  3999 I bt_vendor: bt-vendor : resetting BT status
08-30 17:08:15.755  3896  3999 I bt_vendor: Starting hciattach daemon
08-30 17:08:15.755  3896  3999 I bt_vendor: try to set false
,08-30 17:08:15.759  3896  3999 I bt_vendor: Starting hciattach daemon
08-30 17:08:15.759  3896  3999 I bt_vendor: try to set false
08-30 17:08:15.761  3896  3999 I bt_vendor: cleanup
08-30 17:08:15.762  3896  4081 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:08:15.763  3896  3999 I GKI_LINUX: GKI_exit_task 0 done
08-30 17:08:15.763  3896  3999 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 17:08:15.766  3896  3991 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 17:08:15.802  1070  2033 W libprocessgroup: failed to open /acct/uid_10011/pid_6022/cgroup.procs: No such file or directory
,08-30 17:08:15.816  3896  3896 D HeadsetService: Received stop request...Stopping profile...
,08-30 17:08:15.819  3896  3896 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:08:15.819  3896  3896 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:08:15.820  3896  3896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d582cd4
08-30 17:08:15.820  3896  4014 D HeadsetStateMachine: Exit Disconnected: -1
08-30 17:08:15.822  1070  1070 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:15.822  1070  1070 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 17:08:15.824  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:15.824  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:15.824  3896  3896 D A2dpService: Received stop request...Stopping profile...
08-30 17:08:15.824  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:15.824  3896  4070 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:08:15.825  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:15.826  3896  3896 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 17:08:15.828  3896  3896 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 17:08:15.828  3896  3896 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:08:15.828  3896  3896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d582cd4
08-30 17:08:15.828  3896  3991 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:08:15.829  1070  1070 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:15.829  1070  1070 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 17:08:15.830  3896  3896 D HidService: Received stop request...Stopping profile...
08-30 17:08:15.830  3896  3896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d582cd4
08-30 17:08:15.830  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:15.832  6805  6805 D BluetoothInputDevice: Proxy object disconnected
08-30 17:08:15.832  6805  6805 D HidProfile: Bluetooth service disconnected
,08-30 17:08:15.832  3896  3896 D HealthService: Received stop request...Stopping profile...
08-30 17:08:15.833  3896  3896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d582cd4
08-30 17:08:15.834  3896  3896 D HeadsetStateMachine: Unbinding service...
08-30 17:08:15.835  3896  3896 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:08:15.836  3896  3896 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:08:15.836  3896  3896 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:08:15.836  3896  3896 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:08:15.836  3896  3896 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:08:15.836  3896  3896 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:08:15.836  3896  3896 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:08:15.837  3896  3896 D PanService: Received stop request...Stopping profile...
08-30 17:08:15.837  3896  3896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d582cd4
08-30 17:08:15.838  3896  3896 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:08:15.839  3896  3896 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:08:15.839  3896  3896 D BtGatt.GattService: stop()
08-30 17:08:15.839  3896  3896 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 17:08:15.839  6805  6805 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:08:15.839  6805  6805 D PanProfile: Bluetooth service disconnected
08-30 17:08:15.840  3896  3896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d582cd4
08-30 17:08:15.841  3896  3896 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:08:15.841  3896  3896 D BluetoothMapService: stop()
08-30 17:08:15.842  3896  3896 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 17:08:15.842  3896  3896 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 17:08:15.844  3896  3896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d582cd4
,08-30 17:08:15.846  3896  3896 I BluetoothA2dpServiceJni: cleanupNative
08-30 17:08:15.846  3896  4071 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 17:08:15.846  3896  3896 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:08:15.846  3896  3896 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 17:08:15.847  3896  3896 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:08:15.847  3896  3896 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:08:15.847  3896  3896 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:08:15.848  3896  3896 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:08:15.848  3896  3896 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:08:15.848  6805  6805 D BluetoothMap: Proxy object disconnected
08-30 17:08:15.848  6805  6805 D MapProfile: Bluetooth service disconnected
08-30 17:08:15.848  3896  3896 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:08:15.848  3896  3896 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:08:15.850  3896  3896 V BluetoothMapService: Handler(): got msg=4
08-30 17:08:15.850  3896  3896 D BluetoothMapService: MAP Service closeService in
08-30 17:08:15.850  3896  3896 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:08:15.850  3896  3896 V BluetoothMapService: MAP Service closeService out
08-30 17:08:15.850  3896  3896 D BluetoothMapService: cleanup()
08-30 17:08:15.850  3896  3896 D BluetoothMapService: MAP Service closeService in
08-30 17:08:15.850  3896  3896 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:08:15.850  3896  3896 V BluetoothMapService: MAP Service closeService out
08-30 17:08:15.850  3896  3991 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:08:15.850  3896  3991 D BluetoothAdapterProperties: Setting state to 10
08-30 17:08:15.850  3896  3991 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:08:15.851  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:15.851  3896  3991 I BluetoothAdapterState: Entering OffState
08-30 17:08:15.851  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 17:08:15.851  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 17:08:15.851  1070  1248 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:15.851  6805  6821 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:08:15.852  1070  1248 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:15.852  6805  6820 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:08:15.853  6805  6821 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:08:15.854  1837  2409 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:15.854  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:08:15.854  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:15.855  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:15.858  6805  6820 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:08:15.858  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:15.859  1070  1248 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 17:08:15.859  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-30 17:08:15.863  1070  1248 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 17:08:15.863  1070  1248 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 17:08:15.863  1070  1248 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1abacf0 mBinding = false
08-30 17:08:15.864  6855  6855 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 17:08:15.864  1070  1248 D BluetoothManagerService: Sending unbind request.
08-30 17:08:15.864  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:08:15.864  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:08:15.864  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:15.866  6855  6855 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 17:08:15.867  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 17:08:15.871  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:08:15.872  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:15.872  1924  2134 D LGBluetoothAPIService: Message: 2
08-30 17:08:15.873  1924  2134 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2ed784b7 mBinding = false
08-30 17:08:15.873  1924  2134 D LGBluetoothAPIService: Sending unbind request.
08-30 17:08:15.877  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 17:08:15.879  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:15.881  1587  1587 D BluetoothAdapter: 513643935: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:15.881  1587  1587 D BluetoothAdapter: 513643935: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:15.882  3896  3999 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 17:08:15.882  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:15.882  3896  3896 I GKI_LINUX: GKI_exit_task 1 done
08-30 17:08:15.882  3896  3896 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 17:08:15.883  3896  3896 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 17:08:15.883  3896  3896 I art     : --- WEIRD: removing null entry 246
08-30 17:08:15.883  3896  3896 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 17:08:15.883  3896  3896 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 17:08:15.883  3896  3896 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 17:08:15.886  3896  3896 I art     : System.exit called, status: 0
08-30 17:08:15.886  3896  3896 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 17:08:15.887  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:15.889  6805  6805 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 17:08:15.890  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 17:08:15.891  6805  6805 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 17:08:15.892  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 17:08:15.902  6805  6805 D DockEventReceiver: finishStartingService: stopping service
08-30 17:08:15.907   312  2115 V AudioFlinger: 3896 died, releasing its sessions
,08-30 17:08:15.907   312  2115 V AudioFlinger:  pid 1837 @ 0
08-30 17:08:15.907   312  2115 V AudioFlinger:  pid 3386 @ 1
08-30 17:08:15.907   312  2115 V AudioFlinger:  pid 3386 @ 2
08-30 17:08:15.908  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 17:08:15.908  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:15.909  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:15.925  1070  1888 I ActivityManager: Process com.android.bluetooth (pid 3896) has died
,08-30 17:08:15.925  1070  1888 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-30 17:08:15.930  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:15.931  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:08:15.935  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:15.941  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:08:15.941  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:08:15.941  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:08:15.946  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:08:15.952  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:15.952  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 17:08:15.955  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 17:08:15.956  6805  6805 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 17:08:15.960  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:08:16.022  1070  1937 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6895 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 17:08:16.037  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:08:16.038  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:16.041  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:08:16.101  1070  2015 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6912 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 17:08:16.121  6895  6895 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 17:08:16.121  6895  6895 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:08:16.122  6895  6895 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 17:08:16.122  6895  6895 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:16.143  6895  6895 D BluetoothAdapterApp: Loading JNI Library
08-30 17:08:16.174  6895  6895 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2a0cfbc5 Instance Count = 1
,08-30 17:08:16.178  6895  6895 D BluetoothAdapterApp: onCreate
08-30 17:08:16.189  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:08:16.191  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:16.197  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:16.198  6895  6895 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 17:08:16.198  6895  6895 D ProfileConfigQcom: Adding HeadsetService
08-30 17:08:16.199  6895  6895 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 17:08:16.199  6895  6895 D ProfileConfigQcom: Adding A2dpService
08-30 17:08:16.199  6895  6895 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 17:08:16.199  6895  6895 D ProfileConfigQcom: Adding HidService
08-30 17:08:16.199  6895  6895 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 17:08:16.199  6895  6895 D ProfileConfigQcom: Adding HealthService
08-30 17:08:16.200  6895  6895 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 17:08:16.200  6895  6895 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 17:08:16.200  6895  6895 D ProfileConfigQcom: Adding PanService
08-30 17:08:16.200  6895  6895 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 17:08:16.200  6895  6895 D ProfileConfigQcom: Adding GattService
08-30 17:08:16.201  6895  6895 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 17:08:16.201  6895  6895 D ProfileConfigQcom: Adding BluetoothMapService
08-30 17:08:16.201  6895  6895 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 17:08:16.202  6895  6895 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-30 17:08:16.215  6895  6895 V LGMDMManagerInternal: Create singleton instance
08-30 17:08:16.215  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 17:08:16.221  6912  6932 W FormManager: Network not available. Please check & try again.
08-30 17:08:16.225  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:16.225  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:08:16.225  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:08:16.225  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:08:16.226  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:08:16.232  6912  6933 V FormManager: Network unavailable.
,08-30 17:08:16.234  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:08:16.235  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 17:08:16.235  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:08:16.235  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:08:16.235  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:08:16.235  6912  6933 V FormManager: Network unavailable.
08-30 17:08:16.235  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:08:16.238  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:08:16.238  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:08:16.239  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:16.241  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:16.246  6827  6827 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 17:08:16.246  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:08:16.246  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:16.248  4331  6937 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:08:16.248  4331  6937 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:08:16.248  4331  6936 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:08:16.250  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:16.256  6912  6938 W FormManager: Network not available. Please check & try again.
08-30 17:08:16.257  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:16.262  6912  6939 V FormManager: Network unavailable.
,08-30 17:08:16.268  6912  6939 V FormManager: Network unavailable.
08-30 17:08:16.272  1070  1759 I ActivityManager: Killing 6043:com.android.contacts/u0a19 (adj 15): empty #17
08-30 17:08:16.272  6855  6855 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 17:08:16.273  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 17:08:16.273  6855  6855 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 17:08:16.303  6855  6855 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:16.303  6855  6855 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:16.310  6855  6855 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 17:08:16.310  6855  6855 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 17:08:16.310  6855  6855 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 17:08:16.310  6855  6855 V SoundPool: doLoad: loading sample sampleID=1
08-30 17:08:16.311  6855  6942 V SoundPool: Start decode
08-30 17:08:16.311  6855  6942 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 17:08:16.312   312  2119 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 17:08:16.312   312  2119 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 17:08:16.312   312  2119 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 17:08:16.312   312  2119 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 17:08:16.312   312  2119 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 17:08:16.312   312  2119 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 17:08:16.312   312  2119 V MediaPlayerService: player type = 3
08-30 17:08:16.312   312  2119 V AwesomePlayer: AwesomePlayer create()
08-30 17:08:16.312   312  2119 V AwesomePlayer: reset_l() 
08-30 17:08:16.312   312  2119 V AwesomePlayer: cancelPlayerEvents
08-30 17:08:16.312   312  2119 V AwesomePlayer: setAudioSink() 
08-30 17:08:16.312   312  2119 V AwesomePlayer: reset_l() 
08-30 17:08:16.312   312  2119 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
08-30 17:08:16.312   312  2119 V AudioCache: ignored
08-30 17:08:16.312   312  2119 V AwesomePlayer: cancelPlayerEvents
08-30 17:08:16.312   312  2119 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 17:08:16.312   312  2119 V AwesomePlayer: setDataSource_l dataSource
08-30 17:08:16.312   312  2119 V LGParserOSAL: SniffLGParser start
08-30 17:08:16.312   312  2119 V LGParserOSAL: MainType:5, SubType=0
08-30 17:08:16.312   312  2119 V LGParserOSAL: #### check Mime : application/ogg
08-30 17:08:16.312   312  2119 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 17:08:16.313   312  2119 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 17:08:16.315  6855  6855 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 17:08:16.316  1070  1942 W libprocessgroup: failed to open /acct/uid_10019/pid_6043/cgroup.procs: No such file or directory
,08-30 17:08:16.321  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:16.323  6701  6701 D UEI.SmartControl: QS Service created
08-30 17:08:16.323  6855  6855 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 17:08:16.324  6895  6895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:16.324  6895  6895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:16.324  6895  6895 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:16.325  6895  6895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:16.325  6895  6895 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 17:08:16.327  6855  6855 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 17:08:16.328  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 17:08:16.331  6872  6872 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 17:08:16.338  6701  6701 I UEI.SmartControl: Service initServices...
08-30 17:08:16.338  6701  6701 D UEI.SmartControl: QS start get config
08-30 17:08:16.348   312  2119 V LGParserOSAL: supported mime: application/ogg
08-30 17:08:16.348   312  2119 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 17:08:16.348   312  2119 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 17:08:16.348   312  2119 V AwesomePlayer: mBitrate = -1 bits/sec
,08-30 17:08:16.348   312  2119 V AwesomePlayer: AudioTrack Setting
08-30 17:08:16.348   312  2119 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 17:08:16.348   312  2119 V AwesomePlayer: setAudioSource() 
08-30 17:08:16.348   312  2119 V MediaPlayerService: prepare
08-30 17:08:16.348   312  2119 V AwesomePlayer: prepareAsync_l() 
08-30 17:08:16.349   312  2119 V MediaPlayerService: wait for prepare
08-30 17:08:16.349   312  6944 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 17:08:16.349   312  6944 V AwesomePlayer: initAudioDecoder() 
08-30 17:08:16.349   312  6944 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 17:08:16.349   312  6944 V AudioSystem: isOffloadSupported()
08-30 17:08:16.349   312  6944 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 17:08:16.349   312  6944 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 17:08:16.349   312  6944 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 17:08:16.349   312  6944 V AwesomePlayer: getUseOffload() = 0 
08-30 17:08:16.349   312  6944 V OMXCodec: OMXCodec::Create
08-30 17:08:16.349   312  6944 V OMXCodec: findMatchingCodecs()
08-30 17:08:16.349   312  6944 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 17:08:16.349   312  6944 V OMXCodec: matchingCodecs.size()=1
08-30 17:08:16.349   312  6944 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 17:08:16.350   312  6944 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 17:08:16.350   312  6944 V LGCodecAdapter: LG Codec Adapter start
08-30 17:08:16.350   312  6944 V OMXCodec: OMXCodec Createtor
08-30 17:08:16.350   312  6944 V OMXCodec: setComponentRole
08-30 17:08:16.350   312  6944 V OMXCodec: configureCodec protected=0
08-30 17:08:16.350   312  6944 V LGCodecAdapter: called getLGCodecSpecificData
08-30 17:08:16.350   312  6944 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 17:08:16.350   312  6944 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 17:08:16.350   312  6944 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 17:08:16.350   312  6944 V LGCodecOSAL: Not support LGCodec
08-30 17:08:16.350   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 17:08:16.350   312  6944 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 17:08:16.350   312  6944 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 17:08:16.350   312  6944 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 17:08:16.351   312  6944 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 17:08:16.351   312  6944 V AudioSystem: isOffloadSupported()
08-30 17:08:16.351   312  6944 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 17:08:16.351   312  6944 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 17:08:16.351   312  6944 V OMXCodec: init()
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 17:08:16.351   312  6944 V OMXCodec: allocateBuffers
08-30 17:08:16.351   312  6944 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorb,is.decoder] allocated buffer 0xb54f7970 on input port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-30 17:08:16.351   312  6944 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-30 17:08:16.351   312  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-30 17:08:16.351   312  6944 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 17:08:16.351   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 17:08:16.351   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 17:08:16.351   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 17:08:16.351   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 17:08:16.351   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 17:08:16.351   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 17:08:16.353  6855  6855 V LGMDMManager: Create singleton instance
08-30 17:08:16.355   312  6944 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 17:08:16.355   312  6944 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 17:08:16.355   312  6944 V AudioCache: notify(0xb16a67c0, 5, 0, 0)
08-30 17:08:16.355   312  6944 V AudioCache: ignored
08-30 17:08:16.355   312  6944 V AudioCache: notify(0xb16a67c0, 1, 0, 0)
08-30 17:08:16.355   312  6944 V AudioCache: prepared
08-30 17:08:16.355   312  2119 V AudioCache: wait - success
08-30 17:08:16.355   312  2119 V MediaPlayerService: start
08-30 17:08:16.355   312  2119 V AwesomePlayer: play_l() 
08-30 17:08:16.355   312  2119 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 17:08:16.355   312  2119 V AwesomePlayer: createAudioPlayer_l
08-30 17:08:16.355   312  2119 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 17:08:16.355   312  2119 V AwesomePlayer: startAudioPlayer_l() 
08-30 17:08:16.355   312  2119 D AudioPlayer: start of Playback, useOffload 0
08-30 17:08:16.355   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-30 17:08:16.355   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 17:08:16.357   312  6946 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 17:08:16.357   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 17:08:16.358   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-30 17:08:16.358   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 17:08:16.358   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 17:08:16.358   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
,08-30 17:08:16.358   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 17:08:16.358   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 17:08:16.359   312  2119 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 17:08:16.359   312  2119 V AudioCache: notify(0xb16a67c0, 6, 0, 0)
08-30 17:08:16.359   312  2119 V AudioCache: ignored
08-30 17:08:16.360   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.360   312  6947 V AudioCache: memcpy(0xaf006000, 0xb1721000, 4096)
,08-30 17:08:16.361   312  2119 V MediaPlayerService: wait for playback complete
,08-30 17:08:16.363   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.363   312  6947 V AudioCache: memcpy(0xaf007000, 0xb1721000, 4096)
08-30 17:08:16.364   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.364   312  6947 V AudioCache: memcpy(0xaf008000, 0xb1721000, 4096)
08-30 17:08:16.364   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.364   312  6947 V AudioCache: memcpy(0xaf009000, 0xb1721000, 4096)
08-30 17:08:16.365   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.365   312  6947 V AudioCache: memcpy(0xaf00a000, 0xb1721000, 4096)
08-30 17:08:16.365   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.365   312  6947 V AudioCache: memcpy(0xaf00b000, 0xb1721000, 4096)
,08-30 17:08:16.366   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.366   312  6947 V AudioCache: memcpy(0xaf00c000, 0xb1721000, 4096)
08-30 17:08:16.366   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.366   312  6947 V AudioCache: memcpy(0xaf00d000, 0xb1721000, 4096)
08-30 17:08:16.367   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.367   312  6947 V AudioCache: memcpy(0xaf00e000, 0xb1721000, 4096)
08-30 17:08:16.367   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.367   312  6947 V AudioCache: memcpy(0xaf00f000, 0xb1721000, 4096)
,08-30 17:08:16.368   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.368   312  6947 V AudioCache: memcpy(0xaf010000, 0xb1721000, 4096)
08-30 17:08:16.368   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.368   312  6947 V AudioCache: memcpy(0xaf011000, 0xb1721000, 4096)
08-30 17:08:16.368   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.368   312  6947 V AudioCache: memcpy(0xaf012000, 0xb1721000, 4096)
08-30 17:08:16.369   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.369   312  6947 V AudioCache: memcpy(0xaf013000, 0xb1721000, 4096)
,08-30 17:08:16.369   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.369   312  6947 V AudioCache: memcpy(0xaf014000, 0xb1721000, 4096)
08-30 17:08:16.370   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.370   312  6947 V AudioCache: memcpy(0xaf015000, 0xb1721000, 4096)
08-30 17:08:16.370   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.370   312  6947 V AudioCache: memcpy(0xaf016000, 0xb1721000, 4096)
08-30 17:08:16.371   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.371   312  6947 V AudioCache: memcpy(0xaf017000, 0xb1721000, 4096)
08-30 17:08:16.371   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.371   312  6947 V AudioCache: memcpy(0xaf018000, 0xb1721000, 4096)
08-30 17:08:16.372   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.372   312  6947 V AudioCache: memcpy(0xaf019000, 0xb1721000, 4096)
08-30 17:08:16.372   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.372   312  6947 V AudioCache: memcpy(0xaf01a000, 0xb1721000, 4096)
08-30 17:08:16.373   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.373   312  6947 V AudioCache: memcpy(0xaf01b000, 0xb1721000, 4096)
08-30 17:08:16.374   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.374   312  6947 V AudioCache: memcpy(0xaf01c000, 0xb1721000, 4096)
08-30 17:08:16.374   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.374   312  6947 V AudioCache: memcpy(0xaf01d000, 0xb1721000, 4096)
08-30 17:08:16.375   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.375   312  6947 V AudioCache: memcpy(0xaf01e000, 0xb1721000, 4096)
08-30 17:08:16.375   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.375   312  6947 V AudioCache: memcpy(0xaf01f000, 0xb1721000, 4096)
08-30 17:08:16.376   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.376   312  6947 V AudioCache: memcpy(0xaf020000, 0xb1721000, 4096)
08-30 17:08:16.376   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.376   312  6947 V AudioCache: memcpy(0xaf021000, 0xb1721000, 4096)
08-30 17:08:16.377   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.377   312  6947 V AudioCache: memcpy(0xaf022000, 0xb1721000, 4096)
08-30 17:08:16.377   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.378   312  6947 V AudioCache: memcpy(0xaf023000, 0xb1721000, 4096)
08-30 17:08:16.378   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.378   312  6947 V AudioCache: memcpy(0xaf024000, 0xb1721000, 4096)
08-30 17:08:16.379   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.379   312  6947 V AudioCache: memcpy(0xaf025000, 0xb1721000, 4096)
08-30 17:08:16.379   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.379   312  6947 V AudioCache: memcpy(0xaf026000, 0xb1721000, 4096)
08-30 17:08:16.380   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.380   312  6947 V AudioCache: memcpy(0xaf027000, 0xb1721000, 4096)
08-30 17:08:16.380   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.380   312  6947 V AudioCache: memcpy(0xaf028000, 0xb1721000, 4096)
08-30 17:08:16.381   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.381   312  6947 V AudioCache: memcpy(0xaf029000, 0xb1721000, 4096)
08-30 17:08:16.381   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.381   312  6947 V AudioCache: memcpy(0xaf02a000, 0xb1721000, 4096)
08-30 17:08:16.382   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.382   312  6947 V AudioCache: memcpy(0xaf02b000, 0xb1721000, 4096)
08-30 17:08:16.382   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.382   312  6947 V AudioCache: memcpy(0xaf02c000, 0xb1721000, 4096)
08-30 17:08:16.383   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.383   312  6947 V AudioCache: memcpy(0xaf02d000, 0xb1721000, 4096)
08-30 17:08:16.383   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.383   312  6947 V AudioCache: memcpy(0xaf02e000, 0xb1721000, 4096)
08-30 17:08:16.384   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.384   312  6947 V AudioCache: memcpy(0xaf02f000, 0xb1721000, 4096)
08-30 17:08:16.384   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.384   312  6947 V AudioCache: memcpy(0xaf030000, 0xb1721000, 4096)
08-30 17:08:16.385   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.385   312  6947 V AudioCache: memcpy(0xaf031000, 0xb1721000, 4096)
08-30 17:08:16.386   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.386   312  6947 V AudioCache: memcpy(0xaf032000, 0xb1721000, 4096)
08-30 17:08:16.388   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.388   312  6947 V AudioCache: memcpy(0xaf033000, 0xb1721000, 4096)
08-30 17:08:16.388   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.388   312  6947 V AudioCache: memcpy(0xaf034000, 0xb1721000, 4096)
08-30 17:08:16.389   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.389   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 17:08:16.389   312  6947 V AudioCache: memcpy(0xaf035000, 0xb1721000, 4096)
08-30 17:08:16.389   312  6947 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 17:08:16.389   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.389   312  6947 V AudioCache: memcpy(0xaf036000, 0xb1721000, 4096)
08-30 17:08:16.389   312  6947 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 17:08:16.389   312  6947 V AudioCache: write(0xb1721000, 4096)
08-30 17:08:16.389   312  6947 V AudioCache: memcpy(0xaf037000, 0xb1721000, 4096)
08-30 17:08:16.389   312  6947 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 17:08:16.389   312  6947 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 17:08:16.389   312  6947 V AwesomePlayer: postAudioEOS() 
08-30 17:08:16.389   312  6947 V AudioCache: write(0xb1721000, 280)
08-30 17:08:16.389   312  6947 V AudioCache: memcpy(0xaf038000, 0xb1721000, 280)
08-30 17:08:16.390   312  6944 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 17:08:16.390   312  6944 V AwesomePlayer: onStreamDone
08-30 17:08:16.390   312  6944 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 17:08:16.390   312  6944 V AudioCache: notify(0xb16a67c0, 2, 0, 0)
08-30 17:08:16.390   312  6944 V AudioCache: playback complete
08-30 17:08:16.390   312  6944 V AwesomePlayer: pause_l() 
08-30 17:08:16.390   312  6944 V AudioCache: notify(0xb16a67c0, 7, 0, 0)
08-30 17:08:16.390   312  6944 V AudioCache: ignored
08-30 17:08:16.390   312  2119 V AudioCache: wait - success
08-30 17:08:16.390   312  6944 V AwesomePlayer: cancelPlayerEvents
08-30 17:08:16.390   312  2119 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 17:08:16.390   312  6944 D AudioPlayer: Pause Playback at 1068125
08-30 17:08:16.391   312  2119 V AwesomePlayer: reset_l() 
08-30 17:08:16.391   312  2119 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
08-30 17:08:16.391   312  2119 V AudioCache: ignored
08-30 17:08:16.391   312  2119 V AwesomePlayer: cancelPlayerEvents
08-30 17:08:16.391   312  2119 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 17:08:16.391   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 17:08:16.391   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 17:08:16.391   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 17:08:16.391   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:08:16.391   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 17:08:16.392   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 17:08:16.392   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 17:08:16.392   312  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 17:08:16.392   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 17:08:16.392   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 17:08:16.392   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 17:08:16.392   312  2119 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 17:08:16.393   312  2119 D AudioPlayer: AudioPlayer releasing audio source
08-30 17:08:16.393   312  2119 D AudioPlayer: AudioPlayer done releasing audio source
08-30 17:08:16.393   312  2119 V AwesomePlayer: reset_l() 
08-30 17:08:16.393   312  2119 V AwesomePlayer: cancelPlayerEvents
08-30 17:08:16.393   312  2119 V AwesomePlayer: ~AwesomePlayer call
08-30 17:08:16.393   312  2119 V AwesomePlayer: reset_l() 
08-30 17:08:16.393   312  2119 V AwesomePlayer: cancelPlayerEvents
08-30 17:08:16.393  6855  6942 V SoundPool: close(31)
08-30 17:08:16.393  6855  6942 V SoundPool: pointer = 0xa0010000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 17:08:16.403  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 17:08:16.404  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 17:08:16.407  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9539
,08-30 17:08:16.632  6701  6701 I UEI.SmartControl: Supports setup maps: true
,08-30 17:08:16.635  6701  6701 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 17:08:16.635  6701  6701 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 17:08:16.635  6701  6701 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 17:08:16.635  6701  6701 I UEI.SmartControl: ### init IR Blaster...
08-30 17:08:16.639  6701  6701 D serial_port: Configuring serial port
08-30 17:08:16.639  6701  6701 E UEI.SmartControl: UEIBLaster setting for 616
08-30 17:08:16.639  6701  6701 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 17:08:16.639  6701  6701 I UEI.SmartControl: configuring settings for MAXQ616
08-30 17:08:16.639  6701  6701 I UEI.SmartControl: Get version...
08-30 17:08:16.655  6701  6951 D UEI.SmartControl: serial port data available: 21
,08-30 17:08:16.682  6701  6701 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 17:08:16.682  6701  6701 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 17:08:16.682  6701  6701 I UEI.SmartControl: QS saving settings...
08-30 17:08:16.684  6701  6701 D UEI.SmartControl: IR Blaster version: 25672567
08-30 17:08:16.701  6701  6951 D UEI.SmartControl: serial port data available: 4
,08-30 17:08:16.737  6701  6957 I UEI.SmartControl: Device manager: loading config....
,08-30 17:08:16.743  6701  6701 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 17:08:16.747  6701  6701 E UEI.SmartControl: Services init done
08-30 17:08:16.747  6701  6701 D UEI.SmartControl: QS Service init finished
08-30 17:08:16.748  6701  6957 D UEI.SmartControl: ----------- loading internal config...
,08-30 17:08:16.750  6701  6701 D UEI.SmartControl: QS Service version name: 2.1.91
,08-30 17:08:16.750  6701  6701 D UEI.SmartControl: QS Service version code: 201091
08-30 17:08:16.751  6701  6701 D UEI.SmartControl: Service requested: Control
,08-30 17:08:16.777  1070  1364 V AlarmManager: RTC_WAKEUP set : Alarm{3765c5b2 type 0 when 1472569695149 com.android.vending} when 1472569695149
08-30 17:08:16.797  6701  6957 E UEI.SmartControl: Loading SETTINGS...
,08-30 17:08:16.800  6701  6701 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 17:08:16.802  6701  6701 D UEI.SmartControl: Internal service binding...
08-30 17:08:16.803  6855  6855 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 17:08:16.805  6701  6723 I UEI.SmartControl: ------ IControl API: 11
08-30 17:08:16.805  6701  6723 D UEI.SmartControl: File observer start...
08-30 17:08:16.805  6701  6723 E UEI.SmartControl: IR Port is disabled: false
08-30 17:08:16.805  6701  6723 D UEI.SmartControl: Starting file observer...
08-30 17:08:16.806  6701  6723 I UEI.SmartControl: Registering callback...
08-30 17:08:16.810  6701  6957 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 17:08:16.817  6701  6720 I UEI.SmartControl: ------ IControl API: 19
08-30 17:08:16.818  6701  6720 I UEI.SmartControl: Registering Services Ready callback...
08-30 17:08:16.818  6701  6720 I UEI.SmartControl: Notify client services are ready...
08-30 17:08:16.819  6855  6870 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 17:08:16.820  6855  6940 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 17:08:16.820  6855  6940 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 17:08:16.820  6701  6956 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 17:08:16.821  6855  6871 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 17:08:16.821  6701  6956 D UEI.SmartControl: -----service ready thread exits
08-30 17:08:16.821  6855  6940 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 17:08:16.822  6855  6940 D QRemote : [RemoteControlManager.java:391:handleMessage()] oooooo 140510:Retrieve msg remove
08-30 17:08:16.822  6855  6940 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 17:08:16.822  6855  6855 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 17:08:16.823  6855  6855 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 17:08:16.823  6701  6723 I UEI.SmartControl: ------ IControl API: 8
08-30 17:08:16.824  6855  6855 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 17:08:16.825  6855  6855 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 17:08:16.825  6855  6855 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 17:08:16.826  6855  6855 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-30 17:08:16.829  6855  6855 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 17:08:16.829  6855  6855 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 17:08:16.833  6855  6855 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 17:08:16.836  6855  6855 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 17:08:16.837  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 17:08:16.837  6855  6855 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 17:08:16.838  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-30 17:08:16.840  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 17:08:16.842  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 17:08:16.842  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 17:08:16.843  6855  6855 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472569696843]
08-30 17:08:16.848  6855  6855 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 17:08:16.851  1070  1560 I ActivityManager: Killing 6513:com.lge.email/u0a23 (adj 15): empty #17
,08-30 17:08:16.916  1070  1086 W libprocessgroup: failed to open /acct/uid_10023/pid_6513/cgroup.procs: No such file or directory
,08-30 17:08:16.930  6855  6962 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 17:08:16.938  6855  6855 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 17:08:16.938  6855  6855 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 17:08:16.939  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 17:08:16.939  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 17:08:16.939  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 17:08:16.940  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 17:08:16.940  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 17:08:16.948  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 17:08:16.960  1070  2033 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:08:17.059  6090  6090 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 17:08:17.065  1070  1759 I ActivityManager: Killing 6068:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 17:08:17.096  1070  1888 W libprocessgroup: failed to open /acct/uid_10027/pid_6068/cgroup.procs: No such file or directory
,08-30 17:08:17.839  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:17.853  1070  1248 D Tethering: MasterInitialState.processMessage what=3
08-30 17:08:17.868  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:17.873  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:17.874  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:17.878  1070  1248 D Tethering: MasterInitialState.processMessage what=3
08-30 17:08:17.886  1070  1172 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:17.891  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:17.892  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:17.893  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:08:17.901  6421  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 17:08:17.906  5308  5308 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 17:08:17.920  5308  5308 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 17:08:17.929  1070  2000 D WifiServiceImplEx: setWifiEnabled: true pid=6593, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:08:17.929  1070  2000 D WifiService: setWifiEnabled: true pid=6593, uid=10118
08-30 17:08:17.929  1070  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:08:17.941  1070  1437 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 17:08:17.941  1070  1437 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 17:08:17.943  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:17.943  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:17.943  1070  1070 D Ulp_jni : JNI:system_update. Event-4
,08-30 17:08:17.946  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1070] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 17:08:17.946  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 17:08:17.946  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1070] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 17:08:17.946  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 17:08:17.946  1070  1437 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 17:08:17.946  1070  1437 E WifiHW  : unknown target_country: EU , set to default
08-30 17:08:17.946  1070  1437 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 17:08:17.946  1070  1437 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 17:08:17.946  1070  1437 I WifiUtil: gEnableBmps=1
08-30 17:08:17.956  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:17.988  1070  1172 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:18.040  1070  1942 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6987 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 17:08:18.043  1070  1172 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:18.045  1070  1172 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 17:08:18.130  6987  6987 I AppUp4:AppBoxCP: onCreate
,08-30 17:08:18.131  6987  6987 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 17:08:18.141  6987  6987 I AppUp4:DB:  setFingerPrint start
,08-30 17:08:18.141  6987  6987 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-30 17:08:18.150  6987  6987 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-30 17:08:18.150  6987  6987 I AppUp4:DB:  SDK version = 21
,08-30 17:08:18.150  6987  6987 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 17:08:18.153  6987  6987 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 17:08:18.154  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 17:08:18.154  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:18.157  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:08:18.157  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 17:08:18.164  6987  6987 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 17:08:18.218  6987  6987 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:18.219  6987  6987 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:18.228  6987  6987 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e9bf227
,08-30 17:08:18.228  6987  6987 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:08:18.229  6987  6987 D AppUp4:CustFacade: isPhone : true
08-30 17:08:18.229  6987  6987 D AppUp4:CustModeStarterReceiver: begin check event
,08-30 17:08:18.230  6987  6987 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 17:08:18.230  6987  6987 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 17:08:18.231  6987  7006 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 17:08:18.231  6987  7006 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 17:08:18.232  6987  7006 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 17:08:18.236  1070  2000 I ActivityManager: Killing 6129:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-30 17:08:18.291  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:18.291  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 17:08:18.294  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:18.297  1070  1937 W libprocessgroup: failed to open /acct/uid_10080/pid_6129/cgroup.procs: No such file or directory
08-30 17:08:18.311  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:08:18.326  4331  7013 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:08:18.334  4331  7014 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:18.334  4331  7014 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:08:18.365  1070  1745 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7015 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 17:08:18.466  7015  7015 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:08:18.467  7015  7015 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:08:18.469  7015  7015 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:08:18.469  7015  7015 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:08:18.573  7015  7015 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 17:08:18.588  7015  7015 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 17:08:18.630  7015  7015 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 17:08:18.669  7015  7015 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:18.670  7015  7015 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:18.712  1070  1248 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:08:18.719  1070  1248 D Tethering: InitialState.processMessage what=4
08-30 17:08:18.723   308   917 D SoftapController: Softap fwReload - Ok
08-30 17:08:18.724  1070  1437 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (771ms)
,08-30 17:08:18.727   308   917 D CommandListener: Setting iface cfg
08-30 17:08:18.727   308   917 D CommandListener: Trying to bring down wlan0
08-30 17:08:18.729  1070  1248 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:18.730   308   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:08:18.732  1070  1437 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 17:08:18.734  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:18.734  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:18.734  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 17:08:18.726  7041  7041 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:18.726  7041  7041 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:18.744  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 17:08:18.745  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:18.755  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 17:08:18.755  1070  1437 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 17:08:18.755  1070  1437 D WifiMonitor: connecting to supplicant
,08-30 17:08:18.761  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:18.761  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:18.765  7041  7041 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 17:08:18.798  7041  7041 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:08:18.798  7041  7041 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 17:08:18.838  7015  7015 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 17:08:18.866  7041  7041 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:08:18.876  7015  7015 I HubEmail: JNI_OnLoad()
,08-30 17:08:18.876  7015  7015 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 17:08:18.876  7015  7015 I HubEmail: registerNatives()
08-30 17:08:18.876  7015  7015 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 17:08:18.876  7015  7015 I HubEmail: registerNativeMethods()
08-30 17:08:18.876  7015  7015 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 17:08:18.876  7015  7015 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 17:08:18.878  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:08:18.878  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:18.878  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 17:08:18.888  7041  7041 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 17:08:18.893  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 17:08:18.893  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 17:08:18.893  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:08:18.894  1070  1437 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:08:18.894  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:18.894  1070  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:18.895  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:18.895  1070  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:18.895  1070  1437 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 17:08:18.895  1070  1437 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 17:08:18.896  1070  1437 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 17:08:18.896  1070  1437 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 17:08:18.896  1070  1437 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 17:08:18.921  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-30 17:08:18.922  1070  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 17:08:18.922  1070  7053 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-30 17:08:18.926  1070  1969 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7054 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-30 17:08:18.927  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 17:08:18.927  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:08:18.927  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 17:08:18.927  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 17:08:18.927  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 17:08:18.927  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:08:18.927  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:08:18.929  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:18.929  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:18.929  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:08:18.929  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:18.929  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:18.929  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:18.929  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:18.929  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:18.930  1070  1437 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 17:08:18.931  1070  1437 D WifiNative-wlan0: SET update_config 1: returned true
08-30 17:08:18.931  1070  1437 D WifiConfigStore: Loading config and enabling all networks 
08-30 17:08:18.931  1070  1437 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 17:08:18.932  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:18.932  1924  1924 D WfdService: Waiting for WifiP2p enabling
08-30 17:08:18.933  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 17:08:18.934  1070  1481 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 17:08:18.934  1070  1437 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-30 17:08:18.939  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:18.939  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:18.939  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:18.939  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:18.939  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:18.939  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:18.939  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:18.940  7015  7049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:18.943  1070  1437 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 17:08:18.944  6912  7051 W FormManager: Network not available. Please check & try again.
08-30 17:08:18.946  6912  7052 V FormManager: Network unavailable.
08-30 17:08:18.948  6912  7052 V FormManager: Network unavailable.
,08-30 17:08:18.954  1070  1085 I ActivityManager: Killing 6547:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 17:08:18.956  1070  1437 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 17:08:18.956  1070  1437 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 17:08:18.996  1070  1437 D WifiStateMachine: enableVerboseLogging : level 2
08-30 17:08:18.996  1070  1437 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 17:08:18.996  1070  1745 W libprocessgroup: failed to open /acct/uid_10061/pid_6547/cgroup.procs: No such file or directory
,08-30 17:08:18.997  1070  1437 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 17:08:18.997  1070  1437 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 17:08:18.997  1070  1437 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 17:08:18.997  1070  1437 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 17:08:18.998  1070  1437 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 17:08:18.998  1070  1437 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 17:08:18.998  1070  1437 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 17:08:18.998  1070  1437 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-30 17:08:18.998  1070  1437 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 17:08:18.999  1070  1437 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 17:08:18.999  1070  1437 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 17:08:18.999  1070  1437 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 17:08:18.999  1070  1437 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 17:08:19.004  1070  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:08:19.005  1070  1437 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 17:08:19.005  1924  1924 D WfdsService: Supplicant Connection state is changed : true
08-30 17:08:19.005  1070  1437 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 17:08:19.005  1070  1437 D WifiNative-HAL: Setting external_sim to 1
08-30 17:08:19.005  1924  2344 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 17:08:19.005  1924  2344 D WfdsService: Set the WFDS Monitor: true
08-30 17:08:19.005  1070  1437 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 17:08:19.005  1924  2344 D WfdsMonitor: WfdsMonitorThread create
08-30 17:08:19.005  1924  2344 D WfdsMonitor: WFDS Monitor is created and started
08-30 17:08:19.005  1924  2344 D WfdsService: WiFi: Supplicant connection re-established
08-30 17:08:19.006  1070  1437 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 17:08:19.006  1070  1437 I WifiNative-HAL: startHal
08-30 17:08:19.006  1070  1437 D wifi    : setting scan oui 0x9579c180
08-30 17:08:19.007  1070  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:08:19.007  1070  1437 I WifiNative-HAL: startHal
,08-30 17:08:19.007  1070  1437 D wifi    : setting scan oui 0x9579c180
08-30 17:08:19.007  1924  7073 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 17:08:19.007  1070  1437 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 17:08:19.007  1924  7073 E CtrlSupplicant: Succeed to open control connection
08-30 17:08:19.007  1924  7073 E CtrlSupplicant: Succeed to open monitor connection
08-30 17:08:19.008  1924  7073 D WfdsMonitor: Supplicant connection established
08-30 17:08:19.008  1924  2344 D WfdsService: Connected to the supplicant for wfds
08-30 17:08:19.008  1070  1437 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 17:08:19.008  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 17:08:19.009  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 17:08:19.009  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 17:08:19.010  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:08:19.010  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 17:08:19.011  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 17:08:19.011  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 17:08:19.011  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 17:08:19.012  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 17:08:19.012  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 17:08:19.012  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 17:08:19.013  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:08:19.013  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:08:19.013  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-30 17:08:19.014  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-30 17:08:19.014  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 17:08:19.014  7041  7041 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 17:08:19.015  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 17:08:19.016  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 17:08:19.016  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-30 17:08:19.017  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:08:19.019  1070  1437 E WifiNative: : [120,439,179 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 17:08:19.019  1070  1437 D WifiNative-wlan0: doBoolean: RECONNECT
,08-30 17:08:19.019  1070  1437 D WifiNative-wlan0: RECONNECT: returned true
08-30 17:08:19.019  1070  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 17:08:19.020  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:08:19.020  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 17:08:19.021  1070  1437 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 17:08:19.021  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:19.022  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:08:19.022  1070  1383 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.025   308   917 D CommandListener: Setting iface cfg
08-30 17:08:19.025   308   917 D CommandListener: Trying to bring up p2p0
08-30 17:08:19.025  1070  1383 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 17:08:19.025  1070  1383 D LGWifiP2pService: P2pEnablingState
08-30 17:08:19.025  1070  1383 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.025  1070  1383 D LGWifiP2pService: P2p socket connection successful
08-30 17:08:19.025  1070  1383 D LGWifiP2pService: P2pEnabledState
,08-30 17:08:19.029  1070  1383 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 17:08:19.030  1070  1070 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:08:19.030  1070  1070 D RttService: SCAN_AVAILABLE : 3
08-30 17:08:19.030  1070  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.030  1070  1541 I WifiNative-HAL: startHal
08-30 17:08:19.030  1070  1541 D wifi    : getting scan capabilities on interface[1] = 0x9579c180
08-30 17:08:19.030  1070  1541 D wifi    : failed to get capabilities : -3
08-30 17:08:19.030  1070  1541 E WifiScanningService: could not get scan capabilities
08-30 17:08:19.030  1070  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.030  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 17:08:19.030  1924  1924 D WfdsService: WifiP2pState is changed : true
08-30 17:08:19.031  1924  2344 D WfdsService: Receive the WFDS_ENABLE Method
08-30 17:08:19.031  1070  1383 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 17:08:19.031  1924  2344 D WfdsService: Set the WFDS Monitor: true
08-30 17:08:19.031  1924  2344 D WfdsService: Connected to the supplicant for wfds
08-30 17:08:19.031  1924  2344 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 17:08:19.031  7041  7041 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 17:08:19.032  1070  1383 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 17:08:19.032  1924  2344 D WfdsService: selectPreferredScanChannel [36]
08-30 17:08:19.032  1924  2344 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 17:08:19.032  1070  1383 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 17:08:19.033  1070  1383 D WifiNative-p2p0: SET device_name G3: returned true
08-30 17:08:19.033  1070  1383 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 17:08:19.033  1070  1383 D LGWifiP2pService: before postfix = G3
08-30 17:08:19.033  1070  1383 D WifiServerServiceExt: postfix byte check : 2
08-30 17:08:19.033  1070  1383 D LGWifiP2pService: after postfix = G3
08-30 17:08:19.033  1070  1383 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 17:08:19.033  1924  1924 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 17:08:19.034  1070  1383 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 17:08:19.034  1070  1383 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 17:08:19.034  1070  1437 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 17:08:19.034  1070  1383 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 17:08:19.034  1070  1383 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 17:08:19.034  1924  1924 D WfdsService: isConnected: false
08-30 17:08:19.035  1070  1437 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 17:08:19.035  1070  1383 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 17:08:19.035  1070  1383 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 17:08:19.035  1070  1437 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 17:08:19.036  1070  1383 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 17:08:19.036  1070  1383 D WifiNative-HAL: p2pGetDeviceAddress
08-30 17:08:19.036  1070  1383 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 17:08:19.036  1070  1437 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 17:08:19.036  1070  1383 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 17:08:19.036  1070  1383 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 17:08:19.037  1070  1383 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 17:08:19.037  1070  1383 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 17,:08:19.037  1070  1383 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 17:08:19.037  1070  1383 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 17:08:19.038  1070  1383 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 17:08:19.038  1070  1383 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 17:08:19.038  1924  1924 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 17:08:19.038  1924  1924 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 17:08:19.038  1924  1924 D WfdsService: Update P2p Interface State: 3
,08-30 17:08:19.039  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120461  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:08:19.040  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120462  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:08:19.041  1070  1437 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 17:08:19.041  1070  1437 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 17:08:19.042  1070  1437 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 17:08:19.042  1070  1437 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 17:08:19.043  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.043  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.043  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.043  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.043  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:08:19.045  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.047  7041  7041 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 17:08:19.048  1070  1437 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 17:08:19.048  1070  1437 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 17:08:19.048  1070  1437 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 17:08:19.049  1070  1437 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 17:08:19.049  7041  7041 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 17:08:19.049  1070  1383 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 17:08:19.049  1070  1383 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 17:08:19.049  1070  1383 D LGWifiP2pService: InactiveState
08-30 17:08:19.049  1070  1383 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.049  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.049  1070  1383 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 17:08:19.050  1070  1383 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 17:08:19.050  1070  1383 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.050  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.050  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 17:08:19.050  1070  1383 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.050  1070  1383 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.050  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.050  1070  1383 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.050  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:19.051  1070  7053 D WifiMonitor: Event [IFNAME=p2p0 CT,RL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:08:19.051  1070  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:19.051  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:19.051  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 17:08:19.051  7041  7041 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:08:19.051  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.052  1070  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.052  1070  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.052  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.052  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.052  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.052  1070  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.052  1070  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.052  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.052  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.053  1070  1070 E WifiServerServiceExt: No p2p device connected
08-30 17:08:19.053  1924  7073 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:08:19.053  1924  7073 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.053  1924  7073 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.054  1070  1437 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 17:08:19.054  1070  1437 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 17:08:19.054  1070  1437 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 17:08:19.055  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 17:08:19.050  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.055  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 17:08:19.055  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.055  1070  1383 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.056  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:19.056  7041  7041 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:08:19.056  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.057  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.058  1924  7073 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.058  1924  7073 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.058  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:08:19.058  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:19.058  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:19.058  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:19.058  1070  1383 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.058  1070  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.058  1070  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-C,HANGE init=DRIVER type=WORLD
08-30 17:08:19.058  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.058  1070  1383 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.058  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.058  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.058  1070  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:19.058  1070  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.058  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.058  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:19.059  1924  2344 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 17:08:19.059  1070  1437 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 17:08:19.059  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.059  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.059  1070  1437 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:08:19.059  1070  1437 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:08:19.060  1070  1437 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:08:19.060  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 17:08:19.060  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 17:08:19.060  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:08:19.061  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 17:08:19.061  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:08:19.061  1070  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:08:19.061  1070  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:08:19.061  1070  1437 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 17:08:19.061  1070  1437 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 17:08:19.062  1070  1437 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 17:08:19.062  1070  1437 D WifiNative-wlan0: doBoolean: SCAN
,08-30 17:08:19.062  1070  1437 D WifiNative-wlan0: SCAN: returned false
08-30 17:08:19.062  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120484  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:08:19.063  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120485  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:08:19.064  1070  1437 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:08:19.064  1070  1437 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:08:19.064  1070  1437 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-30 17:08:19.065  1070  1437 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:08:19.065  1070  1437 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-30 17:08:19.070  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 17:08:19.070  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.071  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.071  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.071  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:08:19.072  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:19.072  1070  1070 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 17:08:19.072  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.103  7054  7054 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:19.103  7054  7054 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:19.107  7054  7054 D PhoneMonitor: Register our PhoneStateListener
08-30 17:08:19.122  7054  7054 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 17:08:19.123  7054  7054 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 17:08:19.134  7054  7054 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 17:08:19.134  7054  7054 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 17:08:19.135  7054  7054 D TelephonyAutoProfiling: [parse] Load xml
08-30 17:08:19.139  7054  7054 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 17:08:19.139  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 17:08:19.140  7054  7054 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 17:08:19.140  7054  7054 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 17:08:19.147  7054  7054 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 17:08:19.177  1070  2000 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7076 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:19.182  1070  2000 I ActivityManager: Killing 6158:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-30 17:08:19.240  1070  1597 W libprocessgroup: failed to open /acct/uid_10097/pid_6158/cgroup.procs: No such file or directory
,08-30 17:08:19.456  1070  2000 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7100 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 17:08:19.464  1070  2000 I ActivityManager: Killing 6654:com.lge.eula/1000 (adj 15): empty #17
08-30 17:08:19.497  7041  7041 E wpa_supplicant: USIM:  scard_init function
08-30 17:08:19.498  7041  7041 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 17:08:19.502  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 17:08:19.502  1070  7053 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 17:08:19.502  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 17:08:19.502  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-30 17:08:19.503  1070  7053 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 17:08:19.503  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:08:19.503  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 17:08:19.504  1070  1437 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:19.504  1070  1437 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:19.505  1070  1437 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:19.506  1070  1437 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:19.506  1070  1437 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-30 17:08:19.535  1070  1597 W libprocessgroup: failed to open /acct/uid_1000/pid_6654/cgroup.procs: No such file or directory
08-30 17:08:19.549  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120971  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 17:08:19.553  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.553  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.555  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.558  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.558  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.558  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 17:08:19.559  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120981  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 17:08:19.561  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:19.561  1070  1070 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 17:08:19.616  7041  7041 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 17:08:19.616  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 17:08:19.616  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 17:08:19.617  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 17:08:19.617  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 17:08:19.617  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:19.617  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:19.618  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=121040  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-30 17:08:19.621  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=121043  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 17:08:19.625  1070  1437 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121047
08-30 17:08:19.625  1070  1437 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121047
08-30 17:08:19.626  1070  1437 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121048
08-30 17:08:19.626  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121048
08-30 17:08:19.626  1070  1437 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121048,
08-30 17:08:19.627  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121049  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 17:08:19.633  7041  7041 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:19.633  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 17:08:19.636  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:19.636  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:19.636  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 17:08:19.636  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:19.637  1070  7053 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:19.637  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 17:08:19.637  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:08:19.637  1070  7053 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:08:19.637  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:19.637  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:19.651  1070  1085 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7122 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:19.653  1070  1085 I ActivityManager: Killing 6673:com.lge.bnr/1000 (adj 15): empty #17
08-30 17:08:19.697  1070  1248 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:08:19.702  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.702  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.704  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.709  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.709  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.709  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 17:08:19.711  1070  1888 W libprocessgroup: failed to open /acct/uid_1000/pid_6673/cgroup.procs: No such file or directory
,08-30 17:08:19.724  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121146  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 17:08:19.725  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=121147  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:08:19.726  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=121148  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:08:19.728  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.729  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.729  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 17:08:19.729  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.729  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.729  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:19.729  1070  1070 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 17:08:19.729  1070  1437 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121151
08-30 17:08:19.731  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.732  1070  1437 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121154
08-30 17:08:19.734  1070  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 17:08:19.734  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:19.734  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:19.735  1070  1437 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 17:08:19.737  1070  1437 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 17:08:19.754  1070  1437 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 17:08:19.754  1070  1437 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 17:08:19.759  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.759  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.760  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.760  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.760  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 17:08:19.761  7122  7122 I art     : Almond Protected OAT
08-30 17:08:19.761  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.766  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.766  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.766  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 17:08:19.771  1070  1437 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 17:08:19.771  1070  1527 D ConnectivityService: Got NetworkAgent Messenger
08-30 17:08:19.771  1070  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:19.771  1070  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:08:19.771  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 17:08:19.771  1070  1527 D ConnectivityService: NetworkAgent connected
08-30 17:08:19.771  1070  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:08:19.771  1070  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:08:19.777  1070  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:08:19.777  1070  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:19.777  1070  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:08:19.778  1070  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:08:19.778  1070  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 17:08:19.782  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.782  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.782  1070  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:08:19.784  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.784   308   917 D CommandListener: Setting iface cfg
08-30 17:08:19.787  1070  1437 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 17:08:19.787  1070  7147 D DhcpStateMachine: StoppedState
08-30 17:08:19.787  1070  7147 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.787  1070  7147 D DhcpStateMachine: WaitBeforeStartState
08-30 17:08:19.787  1070  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:19.788  1070  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121210  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:19.789  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121210  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:19.789  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:19.790  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-30 17:08:19.790  1070  1437 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:19.790  1070  1437 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:19.791  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:19.792  1070  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:19.792  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:19.792  1070  1070 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 17:08:19.793  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:19.793  1070  1070 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 17:08:19.794  1070  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=121216  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:19.795  1070  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=121216  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:19.795  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=121217  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:19.797  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:74585] from screen [on:0 period:-604082731] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:08:19.798  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-604082730] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:08:19.798  1070  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 17:08:19.803  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.803  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.803  1070  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.804  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.804  1070  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.804  1070  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 17:08:19.804  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.805  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.805  1070  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-30 17:08:19.806  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-30 17:08:19.806  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-30 17:08:19.806  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 17:08:19.807  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 17:08:19.807  1070  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 17:08:19.807  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 17:08:19.807  1070  1437 D WifiNative-wlan0: SET ps 0: returned true
08-30 17:08:19.807  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 17:08:19.808  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 17:08:19.808  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 17:08:19.808  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ad56d40 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.808  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ad56d40 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.808  1070  7147 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.808  1070  7147 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 17:08:19.809  1070  1437 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 17:08:19.809  1070  1437 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:08:19.809  1070  1437 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:08:19.810   308   917 D CommandListener: Setting iface cfg
08-30 17:08:19.810   308   917 D CommandListener: Trying to bring up wlan0
08-30 17:08:19.811  1070  1437 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 17:08:19.812  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:19.812  1070  1070 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 17:08:19.812  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:19.812  1070  1070 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 17:08:19.813  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.814  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.814  1070  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.814  1070  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.815  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.815  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:19.816  1070  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 17:08:19.816  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 17:08:19.817  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-30 17:08:19.817  1070  1383 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.817  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.817  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:08:19.817  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:08:19.818  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:08:19.818  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 17:08:19.818  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 17:08:19.819  1070  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 17:08:19.819  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:19.826  7122  7122 D WeatherApplication: removeAccount
08-30 17:08:19.827  7122  7122 D WeatherApplication: Account.length = 0
08-30 17:08:19.828  7122  7122 E WeatherApplication: OPERATOR:OPEN
,08-30 17:08:19.832  7122  7122 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:19
08-30 17:08:19.834  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:08:19.835  7122  7122 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:08:19.835  1070  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 17:08:19.835  7122  7122 D Weather.Utils: 2 : All the weather widget is gone.
08-30 17:08:19.836  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 17:08:19.836  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-30 17:08:19.836  1070  1437 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 17:08:19.837  1070  1527 D ConnectivityService: ignoring duplicate network state non-change
08-30 17:08:19.837  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.837  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.837  1070  1383 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.838  7122  7122 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-30 17:08:19.841  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.841  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.841  7122  7122 D WeatherAncestor: connectivity changed - connection : true
08-30 17:08:19.841  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:08:19.843  7122  7122 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 17:08:19.843  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.843  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.844  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.850  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.850  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.850  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:08:19.851  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 17:08:19.851  1070  1527 D ConnectivityService: Adding iface wlan0 to network 101
08-30 17:08:19.855  1070  1070 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 17:08:19.857  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-30 17:08:19.861  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:19.861  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.861  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:08:19.862  7122  7122 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:08:19.862  7122  7122 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:08:19.862  7122  7122 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 17:08:19.863  1070  1437 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 17:08:19.864  1070  1070 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 17:08:19.868  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.868  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:19.869  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.870  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:19.870  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:08:19.870  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.874  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.875  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:08:19.875  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:19.881  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:19.881  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:08:19.881  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:19.882  7122  7122 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:08:19.882  1070  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:08:19.883  7122  7122 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:19
08-30 17:08:19.883  1070  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 17:08:19.884  1070  1437 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:08:19.884  1070  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 17:08:19.884  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:08:19.884   308   917 E Netd    : netlink response contains error (File exists)
08-30 17:08:19.884  1070  1437 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:08:19.885  1070  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 17:08:19.885  1070  1437 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:08:19.885  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:08:19.885  1070  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 17:08:19.886  1070  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 17:08:19.886  1070  1437 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:08:19.886  1070  1527 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 17:08:19.922  1070  1969 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7151 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:19.923  1070  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 17:08:19.923  1070  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 17:08:19.923  1070  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 17:08:19.923  1070  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 17:08:19.923  1070  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:19.923  1070  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:19.923  1070  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-30 17:08:19.925  1070  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:19.925  1070  1969 I ActivityManager: Killing 2110:com.lge.music/u0a34 (adj 15): empty #17
08-30 17:08:19.925  1070  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 17:08:19.925  1070  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-30 17:08:19.925  1070  1527 D ConnectivityService:    accepting network in place of null
08-30 17:08:19.925  1070  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:19.926  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.926  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 17:08:19.926  1070  1437 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:19.926  1070  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:19.926  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:19.927  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:19.927  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:08:19.929  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 17:08:19.929  1070  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 17:08:19.929  1070  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 17:08:19.929  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:19.934   308  7168 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-30 17:08:19.942   312   312 V AudioFlinger: 2110 died, releasing its sessions
08-30 17:08:19.943   312   312 V AudioFlinger:  pid 1837 @ 0
08-30 17:08:19.943   312   312 V AudioFlinger:  pid 3386 @ 1
08-30 17:08:19.943   312   312 V AudioFlinger:  pid 3386 @ 2
08-30 17:08:20.011  1070  7147 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 17:08:20.012  1070  7147 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-30 17:08:20.012  1070  7147 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 17:08:20.006  7171  7171 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:20.006  7171  7171 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:08:20.028  1070  1173 W ActivityManager: Failed to clear dns cache for: com.lge.music
08-30 17:08:20.037  1070  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:20.037  1070  2015 W libprocessgroup: failed to open /acct/uid_10034/pid_2110/cgroup.procs: No such file or directory
08-30 17:08:20.037  1070  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 17:08:20.039  1070  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-30 17:08:20.041  7171  7171 I dhcpcd  : version 5.5.6 starting
08-30 17:08:20.041  1070  1527 D ConnectivityService: validation of new default Network = false
08-30 17:08:20.041  1070  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 17:08:20.041  1070  1527 D DSQN    : enableDataServiceNotify 
08-30 17:08:20.042  1070  1527 D DSQN    : start dsqn bin
08-30 17:08:20.043  7171  7171 E dhcpcd  : get_duid: m
08-30 17:08:20.043  7171  7171 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 17:08:20.043  7171  7171 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 17:08:20.036  7173  7173 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:20.036  7173  7173 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:08:20.052  1070  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 17:08:20.059  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:20.059  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:20.059  1070  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:20.060  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:08:20.061  1070  1070 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 17:08:20.061  1070  1070 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:08:20.061  1070  1070 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:08:20.061  1070  1070 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:08:20.069  7173  7173 E DSQN    : DSQN ssw
,08-30 17:08:20.088  1070  1376 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 17:08:20.117  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:08:20.118  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:20.119  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:20.125  1802  7180 I CheckinService: active receiver: enabled
08-30 17:08:20.134  7171  7171 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:08:20.134  7171  7171 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 17:08:20.134  7171  7171 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:08:20.134  7171  7171 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-30 17:08:20.134  7171  7171 D dhcpcd  : wlan0: sending REQUEST (xid 0x794a0aa0), next in 3.14 seconds
08-30 17:08:20.145  1802  7180 I CheckinService: Preparing to send checkin request
08-30 17:08:20.145  1802  7180 I EventLogService: Accumulating logs since 1472569636550
,08-30 17:08:20.173   279   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 17:08:20.173   279   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 17:08:20.173   279   449 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:08:20.173  7151  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 17:08:20.174   279   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 17:08:20.174   279   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 17:08:20.174   279   449 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:20.175  7151  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 17:08:20.177  1802  7180 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 17:08:20.185  7171  7171 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 17:08:20.190   279   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 17:08:20.190   279   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 17:08:20.190   279   449 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:08:20.191  7151  7187 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 17:08:20.193   279   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 17:08:20.193   279   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 17:08:20.193   279   449 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:08:20.193  7151  7187 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 17:08:20.208  7171  7171 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 17:08:20.208  7171  7171 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 17:08:20.209  7171  7171 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 17:08:20.209  7171  7171 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 17:08:20.209  7171  7171 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:08:20.209  7171  7171 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:08:20.209  7171  7171 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 17:08:20.209  7171  7171 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-30 17:08:20.268  1070  1597 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7196 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 17:08:20.284   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 15.043ms
,08-30 17:08:20.297   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.277ms
,08-30 17:08:20.309   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 11.975ms
,08-30 17:08:20.325  7196  7196 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 17:08:20.326  7196  7196 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:08:20.347  7196  7196 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:08:20.347  7196  7196 I MultiDex: install
08-30 17:08:20.347  7196  7196 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 17:08:20.355  7196  7196 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 17:08:20.402  7151  7151 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 17:08:20.410  7151  7151 I LibraryLoader: Loading: webviewchromium
08-30 17:08:20.413  7151  7151 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1844-1848)
08-30 17:08:20.413  7151  7151 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:08:20.417  7151  7151 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e0f576e}
08-30 17:08:20.418  7151  7151 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:08:20.419  7151  7151 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:08:20.420  1070  7147 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 17:08:20.421  1070  7147 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 17:08:20.421  1070  7147 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:08:20.421  1070  7147 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 17:08:20.421  1070  7147 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 17:08:20.421  1070  7147 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:08:20.421  1070  7147 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 17:08:20.421  1070  7147 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-30 17:08:20.422  1070  7147 D DhcpStateMachine: RunningState
,08-30 17:08:20.427  7151  7151 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 17:08:20.427  7151  7151 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:08:20.435  7151  7151 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 17:08:20.435   312  1381 V AudioPolicyService: registerClient() client 0xb558a800, uid 10093
08-30 17:08:20.436  7151  7151 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 17:08:20.436  7151  7151 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 17:08:20.437  7151  7247 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 17:08:20.443  7151  7151 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:08:20.443  7151  7151 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:08:20.443  7151  7151 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:08:20.443  7151  7151 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:08:20.443  7151  7151 I Adreno-EGL: Remote Branch: 
08-30 17:08:20.443  7151  7151 I Adreno-EGL: Local Patches: 
08-30 17:08:20.443  7151  7151 I Adreno-EGL: Reconstruct Branch: 
08-30 17:08:20.514  7151  7151 I NSApplication: Starting up...
,08-30 17:08:20.595  1070  1759 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7260 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:20.597  1070  1739 I ActivityManager: Killing 6781:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 17:08:20.692  7196  7215 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:20.692  7196  7215 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:20.701  1070  1560 W libprocessgroup: failed to open /acct/uid_10037/pid_6781/cgroup.procs: No such file or directory
08-30 17:08:20.702   308  7168 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 17:08:20.732  7260  7260 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:08:20.924  7279  7279 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 17:08:20.940  1070  1597 I art     : Explicit concurrent mark sweep GC freed 78737(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.446ms total 109.566ms
,08-30 17:08:20.951  1070  1942 D WifiServiceImplEx: setWifiEnabled: false pid=6593, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:08:20.951  1070  1942 D WifiService: setWifiEnabled: false pid=6593, uid=10118
08-30 17:08:20.951  1070  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:08:20.968  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:20.968  1070  1437 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:20.968  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:20.968  1070  1070 D Ulp_jni : JNI:system_update. Event-4
,08-30 17:08:20.969  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:20.969  1070  1437 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:20.969  1070  1437 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:20.970  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:08:20.970  1070  1437 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 17:08:20.970  1070  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:20.970  1070  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:08:20.971  1070  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:08:20.971  1070  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:08:20.979  1070  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:08:20.979  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:08:20.979  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:08:20.979  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:20.979  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:20.980  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:08:20.980  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:20.981  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
,08-30 17:08:20.982   308   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:08:20.983  1070  7147 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:20.989  7279  7279 I dex2oat : dex2oat took 64.456ms (threads: 4)
08-30 17:08:20.998  1070  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:20.998  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:20.998  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:20.998  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:08:20.998  1070  1527 D ConnectivityService: ignoring duplicate network state non-change
08-30 17:08:20.998  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 17:08:21.005  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:21.005  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 17:08:21.006  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:21.007  1070  1383 D LGWifiP2pService: InactiveState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.007  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.007  1070  1383 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@761671d
08-30 17:08:21.008  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 17:08:21.008  1070  1070 D WifiHS20: hidePasspointNotification off =false
08-30 17:08:21.009  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:21.010  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:21.010  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:21.010  1070  1070 D WifiHS20: hidePasspointNotification off =false
08-30 17:08:21.011  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:21.011  1070  1383 D LGWifiP2pService: P2pDisablingState
08-30 17:08:21.011  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:21.011  1070  1383 D LGWifiP2pService: P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.011  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:21.011  1070  1383 D LGWifiP2pService: p2p socket connection lost
08-30 17:08:21.011  1070  1383 D LGWifiP2pService: P2pDisabledState
08-30 17:08:21.011  1070  1070 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:08:21.011  1070  1070 D RttService: SCAN_AVAILABLE : 1
08-30 17:08:21.012  1070  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.012  1070  1437 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:08:21.012  1070  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 17:08:21.012  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:08:21.012  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:08:21.013  1070  1383 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.013  1070  1383 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.014  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:08:21.015  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:21.015  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:08:21.016  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 17:08:21.017  1924  1924 D WfdsService: WifiP2pState is changed : false
08-30 17:08:21.017  1924  2344 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 17:08:21.017  1924  2344 D WfdsService: Set the WFDS Monitor: false
08-30 17:08:21.018  1924  2344 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:08:21.018  1924  2344 D WfdsService: STATE : WfdsDisabledState - enter
,08-30 17:08:21.019  7196  7215 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:08:21.019  7196  7215 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:08:21.019  7196  7215 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:08:21.019  7196  7215 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:08:21.019  7196  7215 I Adreno-EGL: Remote Branch: 
08-30 17:08:21.019  7196  7215 I Adreno-EGL: Local Patches: 
08-30 17:08:21.019  7196  7215 I Adreno-EGL: Reconstruct Branch: 
08-30 17:08:21.019  1070  1542 D RttService: EnabledState got{ when=-8ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.020  1924  7073 D CtrlSupplicant: Received on exit socket, terminate
08-30 17:08:21.020  1924  7073 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 17:08:21.020  1924  7073 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 17:08:21.021  1924  7073 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 17:08:21.021  1924  2345 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 17:08:21.021  1924  2344 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 17:08:21.029  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:21.029  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:21.030  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:21.044   308   917 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:21.046  1070  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 17:08:21.046  1070  1527 D DSQN    : disableDataServiceNotify
08-30 17:08:21.046  1070  1527 D DSQN    : stop dsqn bin
08-30 17:08:21.047  1070  1437 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 17:08:21.048  1070  1070 D WifiHS20: hidePasspointNotification off =false
08-30 17:08:21.049  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:21.049  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:21.049  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:21.049  1070  1437 D WifiNative-p2p0: TERMINATE: returned true
08-30 17:08:21.049  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:21.049  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:21.049  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:08:21.051  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 17:08:21.052  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:21.052  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:21.052  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.052  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:21.052  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 17:08:21.053  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:21.053  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:21.053  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth,.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.053  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:21.053  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:21.053  1070  1070 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 17:08:21.055  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:08:21.055  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:21.056  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:21.058  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:21.058  1070  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 17:08:21.058  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:21.058  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:21.058  1070  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 17:08:21.059  1070  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 17:08:21.059  1070  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 17:08:21.059  1070  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 17:08:21.059  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:21.059  1070  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:21.060  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:21.060  1070  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:21.060  1070  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:21.060  1070  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:21.060  1070  1527 D NetworkManagementService: Removing idletimer
08-30 17:08:21.060  1070  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:21.060  1070  1527 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-30 17:08:21.061  1070  1437 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:21.061  1070  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:21.061  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:21.062  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:08:21.062  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 17:08:21.063  1070  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 17:08:21.063  1070  1070 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:08:21.063  1070  1070 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:08:21.063  1070  1070 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:08:21.063  1070  1070 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:08:21.065  1070  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConne,cted  type  :1
08-30 17:08:21.065  1070  1070 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:08:21.065  1070  1070 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:08:21.066  1070  1070 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:08:21.066  1070  1070 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 17:08:21.091  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:08:21.092  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:21.092  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:21.111  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:08:21.112  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:21.112  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:21.136  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 17:08:21.136  7041  7041 I wpa_supplicant: monitor socket send errors count : 1
08-30 17:08:21.136  7041  7041 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1924-4\x00 that cannot receive messages
,08-30 17:08:21.137  1070  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 17:08:21.137  1070  7053 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 17:08:21.138  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:08:21.139  6421  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 17:08:21.151  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:21.158  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 17:08:21.158  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:21.158  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:08:21.158  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:08:21.159  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:08:21.160  7041  7041 W wpa_supplicant: USIM:  scard_deinit function
08-30 17:08:21.160  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 17:08:21.160  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:08:21.160  1070  7053 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:08:21.160  1070  7053 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 17:08:21.161  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:21.161  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:21.161  1070  1437 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122583
08-30 17:08:21.161  1070  1248 D Tethering: InitialState.processMessage what=4
08-30 17:08:21.162  6987  6987 I AppUp4:CustModeStarterReceiver: onReceive
08-30 17:08:21.162  1070  1437 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122583
,08-30 17:08:21.162  1070  1437 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122584  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:08:21.162  1070  1248 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 17:08:21.164  1070  1437 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122586  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:08:21.165  1070  1437 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:21.165  1070  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:21.166  6987  6987 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e9bf227
08-30 17:08:21.166  6987  6987 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:08:21.166  6987  6987 D AppUp4:CustFacade: isPhone : true
08-30 17:08:21.167  6987  6987 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:08:21.167  6987  6987 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 17:08:21.169  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:21.169  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:08:21.170  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:21.172  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:21.174  4331  7304 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:08:21.177  7196  7215 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:08:21.177  7196  7215 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:08:21.177  7196  7215 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:08:21.177  7196  7215 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:08:21.177  7196  7215 I Adreno-EGL: Remote Branch: 
08-30 17:08:21.177  7196  7215 I Adreno-EGL: Local Patches: 
08-30 17:08:21.177  7196  7215 I Adreno-EGL: Reconstruct Branch: 
08-30 17:08:21.186  4331  7305 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:21.186  4331  7305 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 17:08:21.187  7015  7015 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:08:21.190  1070  7147 D DhcpStateMachine: StoppedState
08-30 17:08:21.190  1070  7147 D DhcpStateMachine: StoppedState{ when=-174ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:21.191  1070  1437 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 17:08:21.191  1070  1437 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 17:08:21.201  7015  7308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:21.203  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:08:21.203  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:21.203  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 17:08:21.205  7054  7054 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 17:08:21.205  7054  7054 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 17:08:21.212  6912  7311 W FormManager: Network not available. Please check & try again.
08-30 17:08:21.214  7122  7122 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:21
,08-30 17:08:21.217  6912  7312 V FormManager: Network unavailable.
08-30 17:08:21.218  6912  7312 V FormManager: Network unavailable.
08-30 17:08:21.221  7122  7122 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:08:21.221  7122  7122 D Weather.Utils: 2 : All the weather widget is gone.
08-30 17:08:21.221  7122  7122 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 17:08:21.222  7122  7122 D WeatherAncestor: connectivity changed - connection : true
08-30 17:08:21.222  7122  7122 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c2bde7d
08-30 17:08:21.223  7122  7122 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:08:21.223  7122  7122 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:08:21.223  7122  7122 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:08:21.223  7122  7122 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:08:21.223  7122  7122 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:21
08-30 17:08:21.241  7196  7215 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:08:21.241  7196  7215 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:08:21.241  7196  7215 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:08:21.241  7196  7215 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:08:21.241  7196  7215 I Adreno-EGL: Remote Branch: 
08-30 17:08:21.241  7196  7215 I Adreno-EGL: Local Patches: 
08-30 17:08:21.241  7196  7215 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:08:21.243  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:21.243  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:08:21.243  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:08:21.244  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:08:21.244  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:08:21.244  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:08:21.244  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 17:08:21.244  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:08:21.244  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:08:21.245  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:08:21.245  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:08:21.250  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:21.253  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:21.255  6912  7317 W FormManager: Network not available. Please check & try again.
08-30 17:08:21.258  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.262  6912  7318 V FormManager: Network unavailable.
08-30 17:08:21.265  6912  7318 V FormManager: Network unavailable.
,08-30 17:08:21.269  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:21.272  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:21.275  6912  7319 W FormManager: Network not available. Please check & try again.
,08-30 17:08:21.277  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:08:21.281  6912  7320 V FormManager: Network unavailable.
08-30 17:08:21.283  6912  7320 V FormManager: Network unavailable.
08-30 17:08:21.287  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:08:21.287  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 17:08:21.289  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:21.291  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:21.295  4331  7321 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:08:21.295  4331  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:08:21.296  4331  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:08:21.316  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 17:08:21.317  1070  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 17:08:21.317  1070  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 17:08:21.317  1070  7053 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 17:08:21.318  1070  1437 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-30 17:08:21.327  1070  1759 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7323 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 17:08:21.413  7323  7323 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:08:21.413  7323  7323 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 17:08:21.418  7323  7323 V [BNRBootReceiver]: Boot Receiver Return
08-30 17:08:21.419  7323  7323 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 17:08:21.421  1070  1437 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 17:08:21.421  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:21.421  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:21.421  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:08:21.421  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:21.424  1924  1924 D WfdsService: Supplicant Connection state is changed : false
08-30 17:08:21.424  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 17:08:21.424  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:21.424  2496  2496 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:21.424  1924  2344 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 17:08:21.424  1924  2344 D WfdsService: Set the WFDS Monitor: false
08-30 17:08:21.424  1924  2344 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:08:21.426  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:21.426  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:21.427  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 17:08:21.427  1070  1481 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 17:08:21.427  1070  1481 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 17:08:21.428  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:21.428  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:21.430  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:08:21.435  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.440   308  7343 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 17:08:21.440  1070  1246 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 17:08:21.440  1802  7180 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 17:08:21.448  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.448  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:21.450  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:08:21.452  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:08:21.458  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.459  1802  7180 I CheckinService: active receiver: disabled
,08-30 17:08:21.465  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:08:21.481  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:08:21.481  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:21.482  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:08:21.486  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 17:08:21.489  6805  6805 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-30 17:08:21.494  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:21.503  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.509  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.515  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.516  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:21.516  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:08:21.522  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:08:21.535  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.543  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.556  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.557  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:21.558  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:21.564  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:21.577  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.585  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:08:21.596  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.597  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:21.599  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:21.604  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:21.613  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.621  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.629  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:08:21.630  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:21.631  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:08:21.638  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:21.654  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.664  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.676  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.677  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:21.679  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:08:21.696  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:08:21.717  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.729  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.738  6701  6958 D UEI.SmartControl: Internal timer expired: 2
08-30 17:08:21.739  6701  6958 D UEI.SmartControl: unbind internal service
08-30 17:08:21.742  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.742  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:21.750  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:21.759  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:08:21.777  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.790  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:08:21.802  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.802  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:21.804  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:21.811  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:21.822  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 17:08:21.837  1070  1525 D WifiService: New client listening to asynchronous messages
,08-30 17:08:21.837  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:08:21.845  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.860  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.873  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.874  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:21.876  6855  6855 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 17:08:21.879  6855  6855 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 17:08:21.880  6855  6855 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 17:08:21.886  6701  6952 D serial_port: close(fd = 24)
08-30 17:08:21.890  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:08:21.894  6701  6952 I UEI.SmartControl: Serial port is closed.
08-30 17:08:21.901  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 17:08:21.904  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:21.910  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:21.921  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:21.931  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:21.932  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:21.934  6855  6855 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 17:08:21.935  6855  6855 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 17:08:21.936  6855  6855 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 17:08:21.942  1070  1888 I ActivityManager: Killing 6872:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 17:08:21.977  1070  1086 W libprocessgroup: failed to open /acct/uid_1000/pid_6872/cgroup.procs: No such file or directory
,08-30 17:08:21.985  2160  2160 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 17:08:22.001  2160  2160 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 17:08:22.002  2160  2160 D c       : Getting all permits...
08-30 17:08:22.002  2160  2160 D a       : Opening database...
,08-30 17:08:22.009  2160  2160 D a       : Opening database auth.proximity.permit_store...
08-30 17:08:22.010  2160  2160 D a       : Closing database...
08-30 17:08:22.033  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:08:22.041  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:08:22.042  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 17:08:22.042  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:22.050  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:22.062  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:22.072  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:22.073  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:22.076  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 17:08:22.082  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:22.089  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:08:22.089  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:08:22.089  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:08:22.098  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:22.112  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:22.123  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:22.124  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:22.127  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 17:08:22.135  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:22.145  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:08:22.145  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:08:22.145  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:08:22.155  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:22.164  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:22.174  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:22.175  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:22.178  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:08:22.191  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:08:22.197  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:22.201  6912  7351 W FormManager: Network not available. Please check & try again.
08-30 17:08:22.204  6912  7352 V FormManager: Network unavailable.
,08-30 17:08:22.209  6912  7352 V FormManager: Network unavailable.
,08-30 17:08:22.217  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:22.241  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:08:22.242  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 17:08:22.246  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:22.252  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:22.259  4331  7353 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:08:22.265  4331  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 17:08:22.266  4331  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:08:22.272  6827  6827 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 17:08:22.272  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:08:22.272  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:22.281  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:22.285  6912  7356 W FormManager: Network not available. Please check & try again.
,08-30 17:08:22.290  6912  7357 V FormManager: Network unavailable.
08-30 17:08:22.292  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:22.297  6912  7357 V FormManager: Network unavailable.
,08-30 17:08:22.310  2160  2160 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 17:08:22.806  1070  1437 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-604079722] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 17:08:22.808  1070  1437 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-604079720] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 17:08:23.040  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:23.053  1070  1248 D Tethering: MasterInitialState.processMessage what=3
08-30 17:08:23.063  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:23.067  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:23.071  1070  1172 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:23.073  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:08:23.075  6421  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 17:08:23.084  5308  5308 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 17:08:23.109  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:23.151  1070  1172 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 17:08:23.155  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 17:08:23.155  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:23.156  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:08:23.156  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:08:23.158  6987  6987 I AppUp4:CustModeStarterReceiver: onReceive
08-30 17:08:23.161  6987  6987 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e9bf227
08-30 17:08:23.161  6987  6987 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:08:23.162  6987  6987 D AppUp4:CustFacade: isPhone : true
08-30 17:08:23.163  6987  6987 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:08:23.163  6987  6987 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 17:08:23.170  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:23.171  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:08:23.172  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:23.175  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:08:23.185  7015  7015 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:08:23.218  4331  7379 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:08:23.224  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:08:23.224  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:23.225  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 17:08:23.225  3386  3386 D PhoneState: setPdpRejectCasuse : false
08-30 17:08:23.226  7015  7380 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:23.227  6912  7370 W FormManager: Network not available. Please check & try again.
08-30 17:08:23.230  7054  7054 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 17:08:23.231  7054  7054 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 17:08:23.236  6912  7371 V FormManager: Network unavailable.
08-30 17:08:23.235  4331  7383 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:23.237  4331  7383 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 17:08:23.243  7122  7122 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:23
,08-30 17:08:23.244  6912  7371 V FormManager: Network unavailable.
,08-30 17:08:23.246  7122  7122 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 17:08:23.246  7122  7122 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 17:08:23.247  7122  7122 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-30 17:08:23.247  7122  7122 D WeatherAncestor: connectivity changed - connection : true,
08-30 17:08:23.247  7122  7122 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c2bde7d
08-30 17:08:23.248  7122  7122 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:08:23.248  7122  7122 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4,
08-30 17:08:23.248  7122  7122 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:08:23.248  7122  7122 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:08:23.248  7122  7122 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:23
08-30 17:08:23.974  1070  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:23.975  1070  2000 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 17:08:24.022  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:24.023  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:24.023  1070  1070 D Ulp_jni : JNI:system_update. Event-4
,08-30 17:08:24.027  1070  1248 D BluetoothManagerService: Message: 1
08-30 17:08:24.027  1070  1248 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 17:08:24.059  1070  1248 D BluetoothManagerService: Message: 20
08-30 17:08:24.059  1070  1248 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dda5a00:true
,08-30 17:08:24.061  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.069  1070  1248 D Tethering: MasterInitialState.processMessage what=3
08-30 17:08:24.071  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:24.075  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:24.075  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.080  1070  1248 D Tethering: MasterInitialState.processMessage what=3
08-30 17:08:24.082  6895  6895 D BluetoothAdapterState: make
08-30 17:08:24.089  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:24.093  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:24.098  6895  6895 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 17:08:24.099  6895  7396 I BluetoothAdapterState: Entering OffState
08-30 17:08:24.099  6895  6895 I bluedroid-qcom: init
08-30 17:08:24.100  6895  6895 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 17:08:24.100  6895  6895 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 17:08:24.100  6895  6895 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:08:24.101  6895  6895 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 17:08:24.101  6895  6895 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 17:08:24.104  6895  6895 I bluedroid-qcom: get_profile_interface socket
08-30 17:08:24.104  6895  6895 I bluedroid-qcom: get_profile_interface map_client
,08-30 17:08:24.108  6895  7400 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 17:08:24.110  6895  7400 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 17:08:24.096  7399  7399 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:24.096  7399  7399 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:24.121  7399  7399 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 17:08:24.121  7399  7399 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 17:08:24.121  7399  7399 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 17:08:24.125  1070  1070 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-30 17:08:24.127  7399  7399 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 17:08:24.131  1070  1070 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 17:08:24.137  7399  7399 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 17:08:24.137  7399  7399 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 17:08:24.148  1070  1070 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 17:08:24.149  1070  1248 D BluetoothManagerService: Message: 40
08-30 17:08:24.149  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 17:08:24.150  6895  7400 D BluetoothAdapterProperties: Name is: G3
08-30 17:08:24.151  6895  6910 I bluedroid-qcom: config_hci_snoop_log
08-30 17:08:24.151  1070  1172 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.152  1070  1248 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 17:08:24.152  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 17:08:24.152  5308  5308 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 17:08:24.157  5308  5308 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 17:08:24.157  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:08:24.159  6421  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 17:08:24.166  6895  7396 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 17:08:24.166  6895  7396 D BluetoothAdapterProperties: Setting state to 11
08-30 17:08:24.166  6895  7396 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 17:08:24.167  6895  7396 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 17:08:24.169  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:24.169  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,08-30 17:08:24.173  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 17:08:24.178  6895  7396 D BluetoothBondStateMachine: make
08-30 17:08:24.180  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 17:08:24.181  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:24.182  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-30 17:08:24.186  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.188  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:24.188  6895  6895 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:08:24.189  1070  1172 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.189  6895  6895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:24.189  6895  6895 V BluetoothPbapReceiver: ***********state = 11
08-30 17:08:24.191  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:24.194  6895  7396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.194  6895  7396 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 17:08:24.194  6895  7396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.194  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:24.194  6895  7396 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-30 17:08:24.195  6895  7396 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 17:08:24.197  6895  7416 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 17:08:24.200  6895  7396 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:24.233  1070  1969 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7419 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:24.240  6895  7396 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:24.242  6895  6895 D HeadsetService: Received start request. Starting profile...
08-30 17:08:24.242  6895  6895 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:08:24.242  6895  6895 D LGBluetoothHfpAdapter: Version 1.6
08-30 17:08:24.244  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 17:08:24.244  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.244  6895  6895 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 17:08:24.244  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:08:24.244  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:08:24.245  6895  6895 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:08:24.245  6895  6895 D HeadsetStateMachine: make
,08-30 17:08:24.248  6895  7396 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:08:24.250  1070  1172 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:24.250  1070  1172 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:24.252  6987  6987 I AppUp4:CustModeStarterReceiver: onReceive
08-30 17:08:24.255  6895  7396 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:24.261  6895  7396 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:08:24.264  6987  6987 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e9bf227
08-30 17:08:24.264  6987  6987 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:08:24.264  6987  6987 D AppUp4:CustFacade: isPhone : true
08-30 17:08:24.265  6987  6987 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:08:24.265  6987  6987 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 17:08:24.271  6895  7396 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:24.272  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.272  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:08:24.274  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:24.276  6895  7396 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:24.276  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:08:24.282  4331  7439 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:08:24.282  6895  6895 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:24.282  6895  6895 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:08:24.287  6895  6895 D HeadsetStateMachine: max_hf_connections = 1
08-30 17:08:24.287  6895  6895 I bluedroid-qcom: get_profile_interface handsfree
08-30 17:08:24.289  6895  6895 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 17:08:24.290   312  2119 V AudioPolicyService: registerClient() client 0xb558a380, uid 1002
08-30 17:08:24.290   312   312 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-30 17:08:24.290   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:08:24.290   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:08:24.290  6895  6895 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 17:08:24.291   312  1381 V AudioFlinger: registerClient() client 0xb14331d8, pid 6895
08-30 17:08:24.292   312  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:24.292   312  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:24.292  1070  1597 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-30 17:08:24.292  1070  1597 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:24.292  1587  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:24.292  1587  1606 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:24.292  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:24.292  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-30 17:08:24.292  6895  6910 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:24.292  6895  6910 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 17:08:24.292  3386  3401 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:24.292  3386  3401 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:24.292   312  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:24.292   312  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:24.293  1070  1759 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:24.293  1070  1759 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:24.293  1837  2409 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:24.293  1837  2409 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:24.293  3386  3402 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:24.293  1587  2086 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:24.293  3386  3402 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:24.293  1587  2086 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:24.293  6895  6911 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:24.293  6895  6911 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 17:08:24.293  6895  6895 V ToneGenerator: Create Track: 0xb4928080
08-30 17:08:24.293  6895  7396 V LGMDMManager: Create singleton instance
08-30 17:08:24.293  6895  6895 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 17:08:24.293  6895  6895 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 17:08:24.293   312  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:08:24.293   312  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 17:08:24.293   312  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:08:24.293   312  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:08:24.294  4331  7440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.294   312  2119 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 17:08:24.294   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:08:24.294   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 17:08:24.294   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:08:24.294   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:08:24.294  6895  6895 V AudioSystem: getLatency() output 2, latency 50
08-30 17:08:24.294  6895  6895 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 17:08:24.294  6895  6895 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 17:08:24.295   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:08:24.295   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 17:08:24.295   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:08:24.295   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 17:08:24.295   312  1381 V AudioFlinger: createTrack() lSessionId: 22
08-30 17:08:24.295  7015  7015 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:08:24.296  4331  7440 D LGDMClient: [GCMRegisterService.java] [o,nHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:08:24.296  6895  6895 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 17:08:24.297  6895  7396 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 17:08:24.297   312  1382 V AudioFlinger: acquiring 22 from 6895, for 6895
08-30 17:08:24.297   312  1382 V AudioFlinger:  added new entry for 22
08-30 17:08:24.297  6895  6895 V ToneGenerator: ToneGenerator INIT OK, time: 125732
08-30 17:08:24.297  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.298  6895  7434 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 17:08:24.298  6895  7434 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:08:24.298  6895  7434 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:08:24.298  6895  7434 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 17:08:24.298   312  2119 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6895
08-30 17:08:24.298   312  2119 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 17:08:24.298   312  2119 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 17:08:24.298   312  2119 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 17:08:24.298   312  2119 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 17:08:24.298   312  2119 V voice   : voice_set_parameters: exit with code(0)
08-30 17:08:24.298   312  2119 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 17:08:24.298   312  2119 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 17:08:24.298  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.299   312  2119 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 17:08:24.299   312  2119 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 17:08:24.299   312  2119 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 17:08:24.299   312  2119 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 17:08:24.299  6895  7434 V ToneGenerator: ToneGenerator destructor
08-30 17:08:24.299  6895  7434 V ToneGenerator: stopTone
08-30 17:08:24.299  6895  7434 V ToneGenerator: Delete Track: 0xb4928080
08-30 17:08:24.299  6895  7434 V AudioTrack: ~AudioTrack, releasing session id from 6895 on behalf of 6895
08-30 17:08:24.299   312  2115 V AudioFlinger: releasing 22 from 6895 for 6895
08-30 17:08:24.299   312  2115 V AudioFlinger:  decremented refcount to 0
08-30 17:08:24.299   312  2115 V AudioFlinger: purging stale effects
08-30 17:08:24.299   312  2115 V AudioPolicyService: AudioCommandThread() adding release output 2,
08-30 17:08:24.299   312  2115 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 17:08:24.299   312  2115 V AudioFlinger: PlaybackThread::Track destructor
08-30 17:08:24.299   312  2115 V AudioFlinger: removeClient_l() pid 6895, calling pid 312
08-30 17:08:24.299   312  1272 V AudioPolicyService: AudioCommandThread() waking up
08-30 17:08:24.299   312  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 17:08:24.299   312  1272 V AudioPolicyManager: releaseOutput() 2
08-30 17:08:24.300   312  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 17:08:24.300  6895  6895 D A2dpService: Received start request. Starting profile...
08-30 17:08:24.301  6895  6895 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 17:08:24.302  6895  6895 V Avrcp   : make,
08-30 17:08:24.302  6895  6895 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 17:08:24.302  6895  6895 I bluedroid-qcom: get_profile_interface avrcp
08-30 17:08:24.303  1070  1888 W Process : Unable to open /proc/7441/status
,08-30 17:08:24.312  6895  6895 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 17:08:24.313  6895  6895 E AudioManager: No RCC entry present to update
08-30 17:08:24.313  6895  6895 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:08:24.316  6895  6895 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 17:08:24.317  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 17:08:24.317  6895  6895 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 17:08:24.321  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:08:24.321  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:24.322  6912  7445 W FormManager: Network not available. Please check & try again.
08-30 17:08:24.322  7015  7442 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:24.323  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 17:08:24.321  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 17:08:24.362  7054  7054 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 17:08:24.362  7054  7054 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 17:08:24.364  6912  7446 V FormManager: Network unavailable.
,08-30 17:08:24.366  7419  7419 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-30 17:08:24.367  7419  7419 W LG Account v2.2: No ProfileInfo entries
08-30 17:08:24.367  7419  7419 I LG Account v2.2: isEnabled: false
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Country: EU
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Operator: OPEN
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Ranking support: false
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Comfort support: false
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Accessory: true
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Health device: true
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Extra Pedometer: false
08-30 17:08:24.367  7419  7419 I Feature : [Lifetracker]Blood glucose device: false
08-30 17:08:24.368  7419  7419 I Feature : [Lifetracker]Device Number: 3
08-30 17:08:24.378  7122  7122 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:24
,08-30 17:08:24.382  6912  7446 V FormManager: Network unavailable.
08-30 17:08:24.382  7122  7122 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:08:24.382  7122  7122 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 17:08:24.383  7122  7122 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 17:08:24.383  7122  7122 D WeatherAncestor: connectivity changed - connection : true
08-30 17:08:24.383  7122  7122 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c2bde7d
08-30 17:08:24.383  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 17:08:24.386  7122  7122 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:08:24.386  7122  7122 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:08:24.386  7122  7122 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:08:24.386  7122  7122 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:08:24.386  7122  7122 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:24
08-30 17:08:24.388  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:08:24.410  1070  1745 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:08:24.410  1070  1745 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:08:24.429  6421  6421 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:08:24.430  6421  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 17:08:24.451  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:24.466  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 17:08:24.466  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.466  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:08:24.466  6987  6987 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:08:24.468  6987  6987 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 17:08:24.472  6987  6987 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e9bf227
08-30 17:08:24.472  6987  6987 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:08:24.472  6987  6987 D AppUp4:CustFacade: isPhone : true
08-30 17:08:24.472  6987  6987 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:08:24.473  6987  6987 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 17:08:24.477  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.478  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 17:08:24.482  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:08:24.484  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:24.491  4331  7451 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:08:24.496  4331  7452 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.496  4331  7452 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:08:24.496  7015  7015 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:08:24.503  1070  2000 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 17:08:24.510  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 17:08:24.514  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:08:24.515  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 17:08:24.516  6895  6895 I BluetoothA2dpServiceJni: classInitNative
08-30 17:08:24.516  6895  6895 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:08:24.516  6895  6895 D A2dpStateMachine: make
08-30 17:08:24.520  6912  7456 W FormManager: Network not available. Please check & try again.
08-30 17:08:24.521  6895  6895 I bluedroid-qcom: get_profile_interface a2dp
08-30 17:08:24.521  6895  7458 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 17:08:24.522  7015  7453 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:24.523  6895  6895 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:08:24.523  6895  6895 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 17:08:24.524  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.524  6895  7455 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:08:24.525  6895  6895 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 17:08:24.526  6895  6895 D HidService: Received start request. Starting profile...
08-30 17:08:24.526  6895  6895 I bluedroid-qcom: get_profile_interface hidhost
08-30 17:08:24.526  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.527  6895  6895 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:08:24.527  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:08:24.527  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:24.527  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 17:08:24.528  6895  6895 D HealthService: Received start request. Starting profile...
08-30 17:08:24.530  7054  7054 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 17:08:24.530  7054  7054 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 17:08:24.531  6895  6895 I bluedroid-qcom: get_profile_interface health
08-30 17:08:24.532  6895  6895 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:08:24.532  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.533  6895  6895 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:08:24.537  6895  6895 D PanService: Received start request. Starting profile...
08-30 17:08:24.537  6895  6895 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:08:24.537  6895  6895 I bluedroid-qcom: get_profile_interface pan
08-30 17:08:24.545  6895  6895 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 17:08:24.545  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.546  6895  6895 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 17:08:24.547  6912  7457 V FormManager: Network unavailable.
08-30 17:08:24.547  7122  7122 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:24
08-30 17:08:24.549  6912  7457 V FormManager: Network unavailable.
08-30 17:08:24.550  7122  7122 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:08:24.550  7122  7122 D Weather.Utils: 2 : All the weather widget is gone.
08-30 17:08:24.550  7122  7122 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 17:08:24.550  7122  7122 D WeatherAncestor: connectivity changed - connection : true
08-30 17:08:24.550  7122  7122 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c2bde7d
08-30 17:08:24.552  6895  6895 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:08:24.552  7122  7122 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:08:24.552  7122  7122 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:08:24.552  6895  6895 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:08:24.552  6895  6895 D BtGatt.GattService: start()
08-30 17:08:24.552  6895  6895 I bluedroid-qcom: get_profile_interface gatt
08-30 17:08:24.553  7122  7122 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:08:24.553  7122  7122 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:08:24.553  6895  6895 D BtGatt.AdvertiseManager: advertise manager created
08-30 17:08:24.553  7122  7122 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:8:24
08-30 17:08:24.561  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.562  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.562  6895  6895 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 17:08:24.563  6895  6895 V BluetoothMapService: BluetoothMapBinder()
08-30 17:08:24.564  6895  6895 D BluetoothMapService: Received start request. Starting profile...
08-30 17:08:24.564  6895  6895 D BluetoothMapService: start()
08-30 17:08:24.568  6895  6895 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 17:08:24.568  6895  6895 D BluetoothMapEmailAppObserver: createReceiver()
08-30 17:08:24.569  6895  6895 D BluetoothMapEmailAppObserver: initObservers()
08-30 17:08:24.569  6895  6895 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 17:08:24.577  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:24.577  6895  6895 D HeadsetStateMachine: Proxy object connected
,08-30 17:08:24.578  6895  6895 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 17:08:24.578  6895  6895 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 17:08:24.579  6895  7434 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 17:08:24.580  6895  7434 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:08:24.580  6895  7434 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 17:08:24.582  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:08:24.585  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:08:24.588  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 17:08:24.592  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:08:24.592  6895  6895 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 17:08:24.596  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:08:24.598  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 17:08:24.599  6895  6895 V BluetoothMapService: Handler(): got msg=1
08-30 17:08:24.600  6895  7396 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-30 17:08:24.600  6895  7396 I bluedroid-qcom: enable
08-30 17:08:24.600  6895  7466 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 17:08:24.600  6895  7396 I bt_hci_bdroid: init
08-30 17:08:24.601  6895  7466 I bt-btu  : btu_task pending for preload complete event
08-30 17:08:24.601  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:24.602  6895  7396 I bt_vendor: bt-vendor : init
08-30 17:08:24.602  6895  7396 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:08:24.603  6895  7396 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 17:08:24.603  6895  7396 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 17:08:24.603  6895  7396 D bt_userial_mct: userial_init
08-30 17:08:24.603  6895  7396 D bt_hci_bdroid: set_power 1
08-30 17:08:24.603  6895  7396 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 17:08:24.603  6895  7396 I bt_vendor: Starting hciattach daemon
08-30 17:08:24.603  6895  7396 I bt_vendor: try to set true
08-30 17:08:24.603  6895  6895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:24.603  6895  6895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:24.603  6895  6895 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:24.603  6895  6895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:24.603  6895  6895 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 17:08:24.596  7469  7469 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:24.596  7469  7469 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:24.640  7470  7470 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 17:08:24.658  1070  2015 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7472 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 17:08:24.729  7472  7472 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:08:24.730  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 17:08:24.742  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 17:08:24.753  1070  1759 I ActivityManager: Killing 6090:com.android.vending/u0a44 (adj 15): empty #17
,08-30 17:08:24.769  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:08:24.780  7497  7497 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 17:08:24.792  7498  7498 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:08:24.802  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 17:08:24.807  1070  1942 W libprocessgroup: failed to open /acct/uid_10044/pid_6090/cgroup.procs: No such file or directory
,08-30 17:08:24.818  7501  7501 I libmdmdetect: ESOC framework not supported
,08-30 17:08:24.819  7501  7501 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 17:08:24.826  7501  7501 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 17:08:24.826  7501  7501 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-30 17:08:24.826  7501  7501 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 17:08:24.826  7501  7501 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-30 17:08:24.826  7501  7501 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 17:08:24.826  7501  7501 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-30 17:08:24.826  7501  7501 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 17:08:24.860  7501  7502 E QC-QMI  : qmi_client [7501] 14: failed to locate client data
08-30 17:08:24.860   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 17:08:24.860   475   475 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 17:08:24.913  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 17:08:24.938  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:08:24.955  6895  7396 I bt_vendor: bluetooth satus is on
08-30 17:08:24.955  6895  7396 D bt_hci_bdroid: preload
08-30 17:08:24.955  6895  7468 D bt_userial_mct: userial_open(port:0)
,08-30 17:08:24.955  6895  7468 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 17:08:24.959  6895  7468 I bt_vendor: Done intiailizing UART
08-30 17:08:24.962  6895  7468 I bt_vendor: Done intiailizing UART
08-30 17:08:24.962  6895  7468 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 17:08:24.963  6895  7468 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 17:08:24.963  6895  7506 D bt_userial_mct: Entering userial_read_thread()
08-30 17:08:24.963  6895  7466 I bt-btu  : btu_task received preload complete event
08-30 17:08:24.964  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 17:08:24.964  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 17:08:24.969  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-30 17:08:24.975  6895  7466 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 17:08:24.975  6895  7466 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:08:24.976  6895  7466 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 17:08:25.074  6895  7466 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 17:08:25.074  6895  7466 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021e061 
08-30 17:08:25.074  6895  7466 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021e061 
,08-30 17:08:25.110  6895  7400 E bt-btif : Calling BTA_HhEnable
,08-30 17:08:25.110  6895  7400 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-30 17:08:25.110  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 17:08:25.110  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 17:08:25.110  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 17:08:25.111  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 17:08:25.111  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 17:08:25.111  6895  7400 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 17:08:25.116  6895  7400 D BluetoothAdapterProperties: Name is: G3
08-30 17:08:25.116  1070  1070 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 17:08:25.117  6895  7400 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:08:25.118  1070  1070 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 17:08:25.118  6895  7400 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:08:25.118  6895  7400 D bt_hci_bdroid: postload
08-30 17:08:25.118  6895  7400 D bte_conf: Device ID record 1 : primary
08-30 17:08:25.119  6895  7400 D bte_conf:   vendorId            = 00c4
08-30 17:08:25.119  6895  7400 D bte_conf:   vendorIdSource      = 0001
08-30 17:08:25.119  6895  7400 D bte_conf:   product             = 13a1
08-30 17:08:25.119  6895  7400 D bte_conf:   version             = 1000
08-30 17:08:25.119  6895  7400 D bte_conf:   clientExecutableURL = 
08-30 17:08:25.119  6895  7400 D bte_conf:   serviceDescription  = 
08-30 17:08:25.119  6895  7400 D bte_conf:   documentationURL    = 
08-30 17:08:25.119  6895  7400 D bte_conf: bte_load_did_conf no section named DID2.
08-30 17:08:25.120  6895  7466 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 17:08:25.120  6895  7468 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:08:25.120  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:25.122  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:25.122  6895  7396 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 17:08:25.122  6895  7396 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:08:25.122  6895  7396 D BluetoothAdapterProperties: State =  11
08-30 17:08:25.123  6895  7396 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 17:08:25.123  6895  7396 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 17:08:25.123  6895  7396 D BluetoothAdapterProperties: Setting state to 12
08-30 17:08:25.123  6895  7396 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 17:08:25.124  6895  7468 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:08:25.124  6895  7468 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:08:25.124  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:25.124  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 17:08:25.124  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 17:08:25.124  1070  1248 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:08:25.125  6895  7400 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 17:08:25.126  6895  7400 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:08:25.116  7514  7514 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:25.116  7514  7514 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:25.128  6895  7468 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:08:25.128  6895  7468 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 17:08:25.132  6895  7506 E bt_mct  : hci lib postload completed
08-30 17:08:25.133  6895  7396 I BluetoothAdapterState: Entering On State
08-30 17:08:25.146  6895  7466 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:25.146  6895  7466 W bt-smp  : Plain text(LSB ~ MSB) = a7 1c 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:25.146  6895  7466 W bt-smp  : Encrypted text(LSB ~ MSB) = 52 26 32 b5 67 d9 07 f6 bd 98 3d da 22 fe 0e dc 
08-30 17:08:25.146  6895  7466 W bt-btm  : Stopping oneshot timer
,08-30 17:08:25.156  6895  7396 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 17:08:25.156  6895  7396 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
,08-30 17:08:25.156  6895  7396 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 17:08:25.157  6895  7396 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 17:08:25.158  1070  1070 D BluetoothHeadset: Proxy object connected
08-30 17:08:25.161  6805  6821 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:08:25.176  6895  7400 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:08:25.176  6895  7400 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-30 17:08:25.178  6895  7466 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:25.178  6895  7466 W bt-smp  : Plain text(LSB ~ MSB) = 66 f1 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:25.178  6895  7466 W bt-smp  : Encrypted text(LSB ~ MSB) = 7f f7 c2 fb 8f ce 41 ed cd a8 53 77 75 ae be af 
08-30 17:08:25.178  6895  7466 W bt-btm  : Stopping oneshot timer
08-30 17:08:25.179  1070  1248 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:08:25.182  1070  1070 D BluetoothA2dp: Proxy object connected
08-30 17:08:25.182  6895  7396 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 17:08:25.184  6805  6820 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 17:08:25.187  6805  6805 D BluetoothInputDevice: Proxy object connected
08-30 17:08:25.187  6805  6805 D HidProfile: Bluetooth service connected
08-30 17:08:25.189  6805  6821 D BluetoothMap: onBluetoothStateChange: up=true
08-30 17:08:25.191  6895  7466 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:25.191  6895  7466 W bt-smp  : Plain text(LSB ~ MSB) = 03 56 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:25.191  6895  7466 W bt-smp  : Encrypted text(LSB ~ MSB) = 25 5e 00 40 e5 cf d2 c3 e1 46 b4 d1 13 ef 5a f6 
08-30 17:08:25.191  6895  7466 W bt-btm  : Stopping oneshot timer
,08-30 17:08:25.201  6895  7466 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:25.201  6895  7466 W bt-smp  : Plain text(LSB ~ MSB) = c9 31 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:25.201  7520  7520 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 17:08:25.201  6895  7466 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 94 f8 f2 97 5e e2 a4 9e b5 a2 4b ad 47 21 41 
08-30 17:08:25.201  6895  7466 W bt-btm  : Stopping oneshot timer
08-30 17:08:25.207  1837  2409 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:08:25.210  6805  6805 D BluetoothMap: Proxy object connected
08-30 17:08:25.210  6805  6805 D MapProfile: Bluetooth service connected
08-30 17:08:25.210  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 17:08:25.210  6805  6805 D BluetoothMap: getConnectedDevices()
08-30 17:08:25.211  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:08:25.211  6895  6911 V BluetoothMapService: getConnectedDevices()
08-30 17:08:25.213  7151  7188 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 17:08:25.213  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 17:08:25.214  1837  2409 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:08:25.215  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 17:08:25.216  6805  6820 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:08:25.216  6805  6820 D BluetoothPan: onBluetoothStateChange call bindService
08-30 17:08:25.216  6895  7466 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:25.216  6895  7466 W bt-smp  : Plain text(LSB ~ MSB) = 8f 27 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:25.216  6895  7466 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 01 46 d0 65 9f b1 cf d8 95 7a 9c 2f ad 41 36 
08-30 17:08:25.217  6895  7466 W bt-btm  : Stopping oneshot timer
08-30 17:08:25.220  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:25.220  6805  6805 D PanProfile: Bluetooth service connected
,08-30 17:08:25.221  1070  1248 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 17:08:25.221  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 17:08:25.223  1070  1070 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 17:08:25.224  1070  1248 D BluetoothManagerService: Message: 40
08-30 17:08:25.225  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.225  1924  2134 D LGBluetoothAPIService: Message: 1
08-30 17:08:25.225  1924  2134 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 17:08:25.226  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:08:25.233  6593  6593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 17:08:25.237  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 17:08:25.240  1924  2134 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:25.240  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:25.242  6895  6895 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.242  6895  6895 D BluetoothMapService: STATE_ON
08-30 17:08:25.243  6805  6805 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 17:08:25.243  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:25.244  6895  6895 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 17:08:25.244  6895  6895 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 17:08:25.247  1070  1248 D BluetoothManagerService: Message: 30
08-30 17:08:25.251  1924  1924 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 17:08:25.251  1924  2134 D LGBluetoothAPIService: Message: 100
08-30 17:08:25.251  1924  2134 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:25.254  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:25.254  6805  6805 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 17:08:25.256  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:25.257  1070  1248 D BluetoothManagerService: Message: 30
,08-30 17:08:25.262  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 17:08:25.264  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:25.264  6895  6895 V BluetoothPbapService: Pbap Service onCreate
08-30 17:08:25.264  6895  6895 V BluetoothPbapService: Starting PBAP service
08-30 17:08:25.266  6895  6895 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 17:08:25.266  6895  6895 V BluetoothMapService: Handler(): got msg=1
08-30 17:08:25.266  6895  6895 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 17:08:25.267  6895  6895 V BluetoothPbapService: Pbap Service onBind
08-30 17:08:25.268  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:08:25.268  6895  6895 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.268  6895  6895 V BluetoothPbapService: state: 12
08-30 17:08:25.268  6895  6895 V BluetoothPbapService: Handler(): got msg=1
,08-30 17:08:25.271  6895  6895 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 17:08:25.271  6895  7536 D BluetoothMapMasInstance: MAS initSocket()
08-30 17:08:25.271  6805  6805 D BluetoothA2dp: Proxy object connected
08-30 17:08:25.272  6805  6805 D A2dpProfile: Bluetooth service connected
08-30 17:08:25.272  6895  6895 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:08:25.272  6895  6895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.273  6895  6895 V BluetoothPbapReceiver: ***********state = 12
08-30 17:08:25.273  6895  7536 D BluetoothMapMasInstance:   masId = 00
08-30 17:08:25.273  6895  7536 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 17:08:25.273  6895  7536 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 17:08:25.273  6895  7536 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 17:08:25.273  6895  7537 V BluetoothPbapService: Pbap Service initSocket
08-30 17:08:25.277  1070  1086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:25.277  1070  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:25.277  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:25.277  2160  2160 D c       : Getting all permits...
08-30 17:08:25.277  2160  2160 D a       : Opening database...
08-30 17:08:25.278  6895  7536 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:25.278  6895  7537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:25.280  6895  7536 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-30 17:08:25.280  6895  7537 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 17:08:25.280  6895  7536 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-30 17:08:25.280  6895  7537 V BluetoothPbapService: Succeed to create listening socket 
08-30 17:08:25.280  6805  6805 D BluetoothHeadset: Proxy object connected
08-30 17:08:25.280  6895  7536 D BluetoothMapMasInstance: Accepting socket connection...
08-30 17:08:25.280  6895  7537 V BluetoothPbapService: Accepting socket connection...
08-30 17:08:25.281  6805  6805 D HeadsetProfile: Bluetooth service connected
08-30 17:08:25.281  6895  7400 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:08:25.281  2160  2160 D a       : Opening database auth.proximity.permit_store...
08-30 17:08:25.281  6895  7400 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 17:08:25.283  2160  2160 D a       : Closing database...
08-30 17:08:25.284  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:25.285  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:25.286  6805  6805 D BluetoothPbap: Proxy object connected
08-30 17:08:25.287  6805  6805 D PbapServerProfile: Bluetooth service connected
08-30 17:08:25.291  6805  6805 D DockEventReceiver: finishStartingService: stopping service
08-30 17:08:25.295  6805  6805 D BluetoothPermissionRequest: onReceive
,08-30 17:08:25.297  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 17:08:25.298  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:08:25.301  6895  6895 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 17:08:25.302  6895  6895 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 17:08:25.307  6895  6895 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 17:08:25.326  6895  6895 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 17:08:25.327  6895  6895 V BtOppService: onCreate
,08-30 17:08:25.331  6895  6895 V BluetoothOppNotification: send message
08-30 17:08:25.334  6895  6895 V BtOppService: Starting RfcommListener
08-30 17:08:25.341  6895  6895 D BluetoothOppPreference: Dumping Names:  
08-30 17:08:25.341  6895  6895 D BluetoothOppPreference: {}
,08-30 17:08:25.341  6895  6895 D BluetoothOppPreference: Dumping Channels:  
08-30 17:08:25.341  6895  6895 D BluetoothOppPreference: {}
08-30 17:08:25.342  6895  6895 V BtOppService: onStartCommand
08-30 17:08:25.342  6895  7542 V BtOppService: Deleted complete outbound shares, number =  0
,08-30 17:08:25.345  6895  7542 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-30 17:08:25.346  6895  7542 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 17:08:25.347  6895  7542 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c7f24ce on behalf of 
08-30 17:08:25.347  6895  7545 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:08:25.348  6895  7545 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:08:25.350  6895  7545 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24ad9fef on behalf of 
08-30 17:08:25.351  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.351  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 17:08:25.352  6895  7545 V BluetoothOppNotification: update too frequent, put in queue
08-30 17:08:25.353  6895  7545 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 17:08:25.355  6895  6895 V BluetoothOppNotification: new notify threadi!
,08-30 17:08:25.357  6895  6895 V BluetoothOppNotification: send delay message
08-30 17:08:25.358  6895  6895 V BtOppService: start RfcommListener
08-30 17:08:25.359  6895  7546 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 17:08:25.360  6895  7546 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26821afc on behalf of 
08-30 17:08:25.361  6895  7546 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 17:08:25.361  6895  6895 V BtOppService: RfcommListener started
08-30 17:08:25.362  6895  6895 V BtOppService: ContentObserver received notification
08-30 17:08:25.362  6895  7546 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 17:08:25.363  6895  7546 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24867585 on behalf of 
08-30 17:08:25.364  6895  6895 V BtOppService: ContentObserver received notification
08-30 17:08:25.364  6895  7546 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 17:08:25.365  6895  7547 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 17:08:25.366  6895  7546 V BluetoothOppNotification: outbound notification was removed.
08-30 17:08:25.366  1070  1937 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:25.366  6895  7546 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 17:08:25.367  6895  7547 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:25.368  6895  7546 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2eecbfda on behalf of 
08-30 17:08:25.368  6895  7548 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:08:25.369  6895  7547 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=73
08-30 17:08:25.370  6895  7547 V BtOppRfcommListener: Started RFCOMM listener....
08-30 17:08:25.370  6895  7547 I BtOppRfcommListener: Accept thread started.
08-30 17:08:25.370  6895  7547 V BtOppRfcommListener: Accepting connection...
08-30 17:08:25.371  6895  7546 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 17:08:25.372  6895  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:08:25.372  6895  7546 V BluetoothOppNotification: inbound notification was removed.
08-30 17:08:25.373  6895  7546 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 17:08:25.373  6895  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19de4c0b on behalf of 
08-30 17:08:25.374  6895  7546 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a53eae8 on behalf of 
08-30 17:08:25.376  6895  7548 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 17:08:25.390  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:25.390  6895  6895 V BluetoothFtpService: Ftp Service onCreate
08-30 17:08:25.390  6895  6895 I BluetoothFtpService: Ftp Service onCreate
08-30 17:08:25.391  6895  6895 V BluetoothFtpService: Ftp Service onStartCommand
08-30 17:08:25.391  6895  6895 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.391  6895  6895 V BluetoothFtpService: Starting Listening on sockets
08-30 17:08:25.391  6895  6895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:25.391  6895  6895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:25.391  6895  6895 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:25.391  6895  6895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.391  6895  6895 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 17:08:25.392  6895  6895 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 17:08:25.394  6895  6895 V BluetoothFtpService: Handler(): got msg=1
,08-30 17:08:25.394  6895  6895 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 17:08:25.395  6895  6895 V BluetoothFtpService: Ftp Service initSocket
08-30 17:08:25.400  1070  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:25.401  6895  6895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:25.402  6895  6895 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-30 17:08:25.402  6895  6895 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 17:08:25.405  6895  7549 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-30 17:08:25.419  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
,08-30 17:08:25.419  6895  6895 V BluetoothSapService: Sap Service onCreate
,08-30 17:08:25.422  6895  6895 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.422  6895  6895 V BluetoothSapService: state: 12
08-30 17:08:25.422  6895  6895 V BluetoothSapService: Starting SAP server process
08-30 17:08:25.424  6895  6895 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 17:08:25.416  7551  7551 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:25.416  7551  7551 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:25.427  6895  7550 V BluetoothSapService: Sap Service initRfcommSocket
08-30 17:08:25.428  1070  1086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:25.430  6895  7550 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:25.433  6895  7550 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 17:08:25.433  6895  7550 V BluetoothSapService: Succeed to create listening socket 
08-30 17:08:25.433  6895  7550 V BluetoothSapService: Accepting socket connection...
,08-30 17:08:25.445  7551  7551 V BT_SAP  : Event pipe created
08-30 17:08:25.445  7551  7551 V BT_SAP  : create_server_socket qcom.sap.server
08-30 17:08:25.445  7551  7551 V BT_SAP  : created socket fd 6
,08-30 17:08:25.707   308  7168 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 17:08:25.712  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
,08-30 17:08:25.712  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s654ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:25.712  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s654ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:25.712  1070  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-30 17:08:26.015  1070  1383 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:26.016  1070  1383 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,08-30 17:08:26.051  1070  1437 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 17:08:26.053  1070  1437 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 17:08:26.096  1070  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{20fe334c type 2 when 127502 com.google.android.gms} when 127502
,08-30 17:08:26.111  6855  6855 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 17:08:26.111  6855  6855 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9539
08-30 17:08:26.115   308  7563 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 17:08:26.119  1070  1246 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 17:08:26.139  1070  1745 I ActivityManager: Killing 7323:com.lge.bnr/1000 (adj 15): empty #17
,08-30 17:08:26.169  1070  1085 W libprocessgroup: failed to open /acct/uid_1000/pid_7323/cgroup.procs: No such file or directory
,08-30 17:08:26.359  6895  6895 V BluetoothOppNotification: new notify threadi!
,08-30 17:08:26.359  6895  6895 V BluetoothOppNotification: send delay message
,08-30 17:08:26.372  6895  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 17:08:26.376  6895  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21a2d03d on behalf of 
08-30 17:08:26.381  6895  7564 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 17:08:26.388  6895  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 17:08:26.389  6895  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39f37032 on behalf of 
08-30 17:08:26.390  6895  7564 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 17:08:26.393  6895  7564 V BluetoothOppNotification: outbound notification was removed.
08-30 17:08:26.393  6895  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 17:08:26.394  6895  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11823183 on behalf of 
08-30 17:08:26.395  6895  7564 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 17:08:26.398  6895  7564 V BluetoothOppNotification: inbound notification was removed.
08-30 17:08:26.398  6895  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 17:08:26.400  6895  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dd72f00 on behalf of 
08-30 17:08:26.421  1070  1969 I ActivityManager: Killing 6827:com.lge.sync/1000 (adj 15): empty #17
,08-30 17:08:26.442  1070  1525 D WifiService: Client connection lost with reason: 4
,08-30 17:08:26.456  1070  1745 W libprocessgroup: failed to open /acct/uid_1000/pid_6827/cgroup.procs: No such file or directory
,08-30 17:08:27.038  1070  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:27.038  1070  1908 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@38a52f95 mBinding = false
,08-30 17:08:27.077  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:27.077  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:27.077  1070  1070 D Ulp_jni : JNI:system_update. Event-4
08-30 17:08:27.078  1070  1248 D BluetoothManagerService: Message: 2
08-30 17:08:27.079  1070  1248 D BluetoothManagerService: Sending off request.
08-30 17:08:27.080  6895  7532 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 17:08:27.081  6895  7396 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 17:08:27.081  6895  7396 D BluetoothAdapterProperties: Setting state to 13
08-30 17:08:27.081  6895  7396 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:08:27.081  6895  7396 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 17:08:27.082  6895  7396 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 17:08:27.083  6895  7400 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:08:27.085  6895  7396 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-30 17:08:27.089  6895  7396 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:08:27.092  6895  7537 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 17:08:27.093  6895  7536 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 17:08:27.093  6895  7547 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:27.094  6895  7549 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:27.094  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 17:08:27.094  6895  7466 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 17:08:27.100  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 17:08:27.100  6895  7466 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-30 17:08:27.107  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:27.107  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:27.109  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:27.110  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:27.119  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:27.119  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:27.125  6593  6593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:27.125  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:27.127  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:27.127  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 17:08:27.127  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 17:08:27.130  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:27.137  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:08:27.141  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:27.142  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:27.144  6895  6895 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:27.144  6895  6895 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:08:27.144  6895  6895 V BluetoothMapService: Handler(): got msg=4
08-30 17:08:27.144  6895  6895 D BluetoothMapService: MAP Service closeService in
08-30 17:08:27.144  6895  6895 D BluetoothMapMasInstance: MAP Service shutdown
08-30 17:08:27.145  6895  6895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:08:27.145  6895  6895 V BluetoothMapService: MAP Service closeService out
,08-30 17:08:27.149  6895  6895 V BtOppService: Receiver DISABLED_ACTION 
08-30 17:08:27.149  6895  6895 I BtOppRfcommListener: stopping Accept Thread
08-30 17:08:27.149  6895  6895 V BtOppRfcommListener: close mBtServerSocket
08-30 17:08:27.150  6895  7547 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 17:08:27.151  6895  6895 V BtOppRfcommListener: waiting for thread to terminate
08-30 17:08:27.151  6895  6895 V BtOppRfcommListener: done waiting for thread to terminate
08-30 17:08:27.153  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 17:08:27.154  6895  7550 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:27.160  6895  6895 V BtOppService: onDestroy
,08-30 17:08:27.164  6895  6895 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 17:08:27.167  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:08:27.172  6895  6895 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:08:27.172  6895  6895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:27.172  6895  6895 V BluetoothPbapReceiver: ***********state = 13
,08-30 17:08:27.176  6895  6895 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 17:08:27.178  6895  6895 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:27.178  6895  6895 V BluetoothPbapService: state: 13
08-30 17:08:27.178  6895  6895 V BluetoothPbapService: Pbap Service closeService in
08-30 17:08:27.181  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:27.182  6895  6895 V BluetoothPbapService: successfully stopped pbap service
08-30 17:08:27.183  6895  6895 V BluetoothPbapService: Pbap Service closeService out
08-30 17:08:27.184  6895  6895 V BluetoothPbapService: Pbap Service onDestroy
08-30 17:08:27.184  6895  6895 V BluetoothPbapService: Pbap Service closeService in
08-30 17:08:27.184  6895  6895 V BluetoothPbapService: Pbap Service closeService out
08-30 17:08:27.184  6895  6895 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 17:08:27.218  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:27.223  6805  6805 D BluetoothPbap: Proxy object disconnected
08-30 17:08:27.223  6805  6805 D PbapServerProfile: Bluetooth service disconnected
08-30 17:08:27.228  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 17:08:27.233  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 17:08:27.233  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 17:08:27.240  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:08:27.243  6895  6895 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 17:08:27.243  6895  6895 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 17:08:27.244  6895  6895 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-30 17:08:27.249  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:27.249  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 17:08:27.250  6895  6895 V BluetoothFtpService: Ftp Service onStartCommand
08-30 17:08:27.251  6895  6895 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:27.251  6895  6895 V BluetoothFtpService: Ftp Service closeService
08-30 17:08:27.251  6895  6895 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 17:08:27.253  6895  6895 V BluetoothFtpService: successfully stopped ftp service
08-30 17:08:27.253  6895  6895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:27.253  6895  6895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:27.253  6895  6895 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:27.253  6895  6895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:27.253  6895  6895 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 17:08:27.253  6895  6895 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 17:08:27.254  6895  6895 V BluetoothFtpService: Ftp Service onDestroy
08-30 17:08:27.254  6895  6895 V BluetoothFtpService: Ftp Service closeService
08-30 17:08:27.258  6895  6895 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:27.259  6895  6895 V BluetoothSapService: state: 13
,08-30 17:08:27.259  6895  6895 V BluetoothSapService: Stopping SAP server process
,08-30 17:08:27.260  6895  6895 V BluetoothSapService: Sap Service closeSapService in
,08-30 17:08:27.260  6895  6895 V BluetoothSapService: Close listen Socket : 
,08-30 17:08:27.260  6895  6895 V BluetoothSapService: Close rfcomm Socket : 
,08-30 17:08:27.260  6895  6895 V BluetoothSapService: Close sapd  Socket : 
08-30 17:08:27.262  6895  6895 V BluetoothSapService: Sap Service closeSapService out
08-30 17:08:27.263  6895  6895 V BluetoothSapService: Sap Service onDestroy
08-30 17:08:27.263  6895  6895 V BluetoothSapService: Sap Service closeSapService in
08-30 17:08:27.263  6895  6895 V BluetoothSapService: Close listen Socket : 
08-30 17:08:27.263  6895  6895 V BluetoothSapService: Close rfcomm Socket : 
,08-30 17:08:27.263  6895  6895 V BluetoothSapService: Close sapd  Socket : 
08-30 17:08:27.263  6895  6895 V BluetoothSapService: Sap Service closeSapService out
08-30 17:08:28.001  6895  7400 D bt_hci_bdroid: cleanup
,08-30 17:08:28.017  6895  7468 I bt_lpm  : LPM is already off!!!
08-30 17:08:28.017  6895  7506 I bt_userial_mct: exiting userial_read_thread
08-30 17:08:28.017  6895  7506 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:08:28.018  6895  7466 W bt-btif : ag scb idx 1 not allocated
08-30 17:08:28.018  6895  7466 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:28.018  6895  7466 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:08:28.019  6895  7466 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:28.019  6895  7466 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 17:08:28.021  6895  7400 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:08:28.021  6895  7468 I bt_vendor: hw_epilog_process
08-30 17:08:28.021  6895  7400 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 17:08:28.021  6895  7400 D bt_userial_mct: userial_close
08-30 17:08:28.021  6895  7400 E bt_userial_mct: pthread_join() FAILED result:3
08-30 17:08:28.021  6895  7400 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 17:08:28.025  6895  7400 D bt_hci_bdroid: set_power 0
08-30 17:08:28.026  6895  7400 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:08:28.026  6895  7400 I bt_vendor: bluetooth satus is on
08-30 17:08:28.026  6895  7400 I bt_vendor: bt-vendor : resetting BT status
08-30 17:08:28.026  6895  7400 I bt_vendor: Starting hciattach daemon
08-30 17:08:28.026  6895  7400 I bt_vendor: try to set false
08-30 17:08:28.027  6895  7400 I bt_vendor: Starting hciattach daemon
08-30 17:08:28.027  6895  7400 I bt_vendor: try to set false
,08-30 17:08:28.033  6895  7400 I bt_vendor: cleanup
08-30 17:08:28.035  6895  7466 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:08:28.035  6895  7400 I GKI_LINUX: GKI_exit_task 0 done
08-30 17:08:28.035  6895  7400 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 17:08:28.037  6895  7396 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 17:08:28.045  6895  6895 D HeadsetService: Received stop request...Stopping profile...
,08-30 17:08:28.050  6895  6895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:08:28.050  6895  6895 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:08:28.050  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:28.051  6895  7434 D HeadsetStateMachine: Exit Disconnected: -1
08-30 17:08:28.053  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:28.053  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:28.053  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:28.054  1070  1070 D BluetoothHeadset: Proxy object disconnected
08-30 17:08:28.054  1070  1070 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 17:08:28.055  6895  6895 D A2dpService: Received stop request...Stopping profile...
08-30 17:08:28.055  6895  7396 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:08:28.056  6895  7455 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:08:28.057  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-30 17:08:28.062  6895  6895 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 17:08:28.062  6895  6895 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:08:28.062  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:28.065  1070  1070 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:28.065  1070  1070 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 17:08:28.065  6895  6895 D HidService: Received stop request...Stopping profile...
08-30 17:08:28.066  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:28.068  6895  6895 D HealthService: Received stop request...Stopping profile...
08-30 17:08:28.068  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:28.070  6895  6895 D PanService: Received stop request...Stopping profile...
,08-30 17:08:28.075  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:28.077  6895  6895 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:08:28.077  6895  6895 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:08:28.077  6895  6895 D BtGatt.GattService: stop()
08-30 17:08:28.078  6895  6895 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 17:08:28.079  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:28.080  6895  6895 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:08:28.080  6895  6895 D BluetoothMapService: stop()
08-30 17:08:28.080  6895  6895 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 17:08:28.081  6895  6895 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 17:08:28.081  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c2bde7d
08-30 17:08:28.083  6895  6895 D HeadsetStateMachine: Unbinding service...
08-30 17:08:28.084  6895  6895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:08:28.084  6895  6895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:08:28.084  6895  6895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:08:28.084  6895  6895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:08:28.084  6895  6895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:08:28.084  6895  6895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:08:28.084  6895  6895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:08:28.084  6895  6895 I BluetoothA2dpServiceJni: cleanupNative
,08-30 17:08:28.088  6895  7458 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 17:08:28.089  6895  6895 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:08:28.089  6895  6895 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 17:08:28.089  6895  6895 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:08:28.089  6895  6895 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:08:28.089  6895  6895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:08:28.090  6895  6895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:08:28.090  6895  6895 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:08:28.090  6895  6895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:08:28.090  6895  6895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:08:28.093  6895  6895 V BluetoothMapService: Handler(): got msg=4
08-30 17:08:28.093  6895  6895 D BluetoothMapService: MAP Service closeService in
08-30 17:08:28.093  6895  6895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:08:28.093  6895  6895 V BluetoothMapService: MAP Service closeService out
08-30 17:08:28.093  6895  7396 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:08:28.094  6895  7396 D BluetoothAdapterProperties: Setting state to 10
08-30 17:08:28.094  6895  7396 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:08:28.094  6895  6895 D BluetoothMapService: cleanup()
08-30 17:08:28.094  6895  6895 D BluetoothMapService: MAP Service closeService in
08-30 17:08:28.094  6895  6895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:08:28.094  6895  6895 V BluetoothMapService: MAP Service closeService out
08-30 17:08:28.096  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:28.096  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 17:08:28.096  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 17:08:28.096  1070  1248 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:28.097  6895  7396 I BluetoothAdapterState: Entering OffState
,08-30 17:08:28.102  6805  7518 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:08:28.103  1070  1248 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:08:28.104  6805  7518 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:08:28.104  6805  7518 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:08:28.105  6805  7518 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:08:28.106  1837  2409 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:28.106  6805  7518 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:28.107  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:28.108  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:08:28.108  6805  7518 D BluetoothPan: onBluetoothStateChange on: false
,08-30 17:08:28.111  1070  1248 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 17:08:28.111  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 17:08:28.113  1070  1248 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 17:08:28.113  1070  1248 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 17:08:28.114  1070  1248 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@38a52f95 mBinding = false
08-30 17:08:28.115  1070  1248 D BluetoothManagerService: Sending unbind request.
08-30 17:08:28.120  6895  7400 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 17:08:28.122  6895  6895 I GKI_LINUX: GKI_exit_task 1 done
08-30 17:08:28.122  6895  6895 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 17:08:28.122  6895  6895 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 17:08:28.122  6895  6895 I art     : --- WEIRD: removing null entry 248
08-30 17:08:28.123  6895  6895 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 17:08:28.123  6895  6895 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 17:08:28.124  6895  6895 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 17:08:28.125  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 17:08:28.128  6895  6895 I art     : System.exit called, status: 0
08-30 17:08:28.128  6895  6895 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 17:08:28.148   312  2119 V AudioFlinger: 6895 died, releasing its sessions
08-30 17:08:28.148   312  2119 V AudioFlinger:  pid 1837 @ 0
08-30 17:08:28.148   312  2119 V AudioFlinger:  pid 3386 @ 1
08-30 17:08:28.148   312  2119 V AudioFlinger:  pid 3386 @ 2
,08-30 17:08:28.152  1924  1924 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-30 17:08:28.152  1924  2134 D LGBluetoothAPIService: Message: 101
08-30 17:08:28.152  1924  2134 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 17:08:28.152  1924  2134 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 17:08:28.153  1924  2134 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 17:08:28.157  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 17:08:28.185  1070  1560 I ActivityManager: Process com.android.bluetooth (pid 6895) has died
08-30 17:08:28.185  1070  1560 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-30 17:08:28.185  1070  1560 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-30 17:08:28.192  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:28.193  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:08:28.195  1924  2134 D LGBluetoothAPIService: Message: 2
08-30 17:08:28.195  1924  2134 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 17:08:28.196  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:28.197  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:28.203  1587  1587 D BluetoothAdapter: 513643935: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:28.203  1587  1587 D BluetoothAdapter: 513643935: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:28.205  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 17:08:28.205  6805  6805 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 17:08:28.208  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:08:28.332  1070  2033 I art     : Explicit concurrent mark sweep GC freed 92755(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.790ms total 121.617ms
,08-30 17:08:28.386  1070  2000 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7611 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-30 17:08:28.388  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:28.474  7611  7611 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 17:08:28.474  7611  7611 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:08:28.475  7611  7611 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 17:08:28.476  7611  7611 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:28.496  7611  7611 D BluetoothAdapterApp: Loading JNI Library
,08-30 17:08:28.533  7611  7611 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2a0cfbc5 Instance Count = 1
,08-30 17:08:28.539  7611  7611 D BluetoothAdapterApp: onCreate
08-30 17:08:28.567  7611  7611 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 17:08:28.567  7611  7611 D ProfileConfigQcom: Adding HeadsetService
08-30 17:08:28.568  7611  7611 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 17:08:28.568  7611  7611 D ProfileConfigQcom: Adding A2dpService
08-30 17:08:28.569  7611  7611 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 17:08:28.569  7611  7611 D ProfileConfigQcom: Adding HidService
08-30 17:08:28.570  7611  7611 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 17:08:28.571  7611  7611 D ProfileConfigQcom: Adding HealthService
08-30 17:08:28.571  7611  7611 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 17:08:28.574  7611  7611 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 17:08:28.574  7611  7611 D ProfileConfigQcom: Adding PanService
08-30 17:08:28.575  7611  7611 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 17:08:28.575  7611  7611 D ProfileConfigQcom: Adding GattService
,08-30 17:08:28.576  7611  7611 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 17:08:28.576  7611  7611 D ProfileConfigQcom: Adding BluetoothMapService
08-30 17:08:28.578  7611  7611 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 17:08:28.581  7611  7611 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 17:08:28.583  7611  7611 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:28.584  7611  7611 V BluetoothPbapReceiver: ***********state = 10
08-30 17:08:28.587  7611  7611 V LGMDMManagerInternal: Create singleton instance
08-30 17:08:28.700  7611  7611 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 17:08:28.700  7611  7611 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 17:08:28.705  1924  1924 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 17:08:28.705  1924  2134 D LGBluetoothAPIService: Message: 100
08-30 17:08:28.705  1924  2134 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 17:08:28.706  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:28.715  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 17:08:28.719  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 17:08:28.721  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 17:08:28.721  6805  6805 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 17:08:28.723  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:08:28.728  7611  7611 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-30 17:08:28.734  7611  7611 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:28.738  7611  7611 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:28.739  7611  7611 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:28.739  7611  7611 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:28.740  7611  7611 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:28.740  7611  7611 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-30 17:08:28.749  7472  7472 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 17:08:29.379  1070  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e813838 type 2 when 130785 com.google.android.gms} when 130785
,08-30 17:08:29.385   308  7641 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 17:08:29.389  1070  1246 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 17:08:30.158  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:08:30.158  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.199  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 17:08:30.292  1070  1173 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7642 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 17:08:30.298  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 17:08:30.326  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 17:08:30.329  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 17:08:30.331  1070  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:08:30.343  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:30.362  1070  1070 D administrator: Handling package changes for user 0
,08-30 17:08:30.365  7642  7642 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:08:30.458  7642  7642 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 17:08:30.458  7642  7642 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:30.468  1070  1070 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 17:08:30.468  1070  1070 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 17:08:30.500  1070  1172 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:08:30.507  1070  1172 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 17:08:30.515  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 17:08:30.517  2496  2496 V GmsNetworkLocationProvi: DISABLE
,08-30 17:08:30.550  7642  7686 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 17:08:30.551  7642  7686 I Babel   : MmsConfig.loadMmsSettings
,08-30 17:08:30.556  7642  7686 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 17:08:30.556  7642  7686 I Babel   : MmsConfig.loadFromDatabase
08-30 17:08:30.562  1070  1172 D LocationProviderProxy: applying state to connected service
08-30 17:08:30.565  2496  2496 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 17:08:30.582  7642  7686 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 17:08:30.582  7642  7686 I Babel   : MmsConfig.loadFromResources
08-30 17:08:30.582  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:30.584  7642  7686 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 17:08:30.584  7642  7686 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 17:08:30.600  7642  7684 W AudioCapabilities: Unsupported mime audio/evrc
08-30 17:08:30.605  7642  7684 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 17:08:30.608  1802  7689 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 17:08:30.608  1802  7689 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 17:08:30.609  7642  7684 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 17:08:30.612  6987  6987 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 17:08:30.618  6987  6987 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e9bf227
08-30 17:08:30.618  6987  6987 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:08:30.618  6987  6987 D AppUp4:CustFacade: isPhone : true
08-30 17:08:30.618  6987  6987 D AppUp4:CustModeStarterReceiver: begin check event
,08-30 17:08:30.618  6987  6987 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 17:08:30.625  1802  4794 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 17:08:30.636  7642  7684 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 17:08:30.639  7642  7684 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 17:08:30.642  7642  7684 W AudioCapabilities: Unsupported mime audio/evrc
08-30 17:08:30.648  1070  2033 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7692 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 17:08:30.654  1070  1942 I ActivityManager: Killing 7015:com.lge.email/u0a23 (adj 15): empty #17
,08-30 17:08:30.666  7642  7684 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 17:08:30.668  7642  7684 W VideoCapabilities: Unsupported mime video/divx
08-30 17:08:30.670  7642  7684 W VideoCapabilities: Unsupported mime video/divx311
,08-30 17:08:30.671  7642  7684 W VideoCapabilities: Unsupported mime video/divx4
08-30 17:08:30.675  7642  7684 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 17:08:30.688  7642  7684 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 17:08:30.691  7642  7684 W AudioCapabilities: Unsupported mime audio/eac3
08-30 17:08:30.691  7642  7684 W AudioCapabilities: Unsupported mime audio/ac3
08-30 17:08:30.692  7642  7684 W AudioCapabilities: Unsupported mime audio/g726
08-30 17:08:30.693  7642  7684 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 17:08:30.694  7642  7684 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 17:08:30.694  7642  7684 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 17:08:30.696  7642  7684 W VideoCapabilities: Unsupported mime video/theora
08-30 17:08:30.698  7642  7684 W VideoCapabilities: Unsupported mime video/mjpg
08-30 17:08:30.736  1070  1085 W libprocessgroup: failed to open /acct/uid_10023/pid_7015/cgroup.procs: No such file or directory
,08-30 17:08:30.775  7692  7692 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:08:30.776  7692  7692 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:08:30.776  7692  7692 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 17:08:30.777  7692  7692 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 17:08:30.778  7692  7692 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:08:30.852  7692  7692 I SystemConfig: BUILD Country: EU
08-30 17:08:30.852  7692  7692 I SystemConfig: BUILD Operator: OPEN
,08-30 17:08:30.897  1070  1759 I ActivityManager: Killing 6912:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 17:08:31.038  1070  1908 W libprocessgroup: failed to open /acct/uid_10026/pid_6912/cgroup.procs: No such file or directory
,08-30 17:08:31.068  7692  7711 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 17:08:31.068  7692  7711 I SystemConfig: existFile = false
08-30 17:08:31.069  7692  7711 I SystemConfig: canReadFile = false
08-30 17:08:31.069  7692  7711 I SystemConfig: systemFeature RCS result false
08-30 17:08:31.069  7692  7711 D SystemConfig: refreshRcsSupport() :false
,08-30 17:08:31.107  1070  1086 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7719 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 17:08:31.166  7719  7719 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:31.166  7719  7719 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:08:31.166  7719  7719 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 17:08:31.167  7719  7719 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 17:08:31.232  7719  7719 I AppConfig: Total System Memory = 2995761152
,08-30 17:08:31.240  7719  7719 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-30 17:08:31.352  1070  1937 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7749 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:08:31.354  1070  1937 I ActivityManager: Killing 6421:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 17:08:31.480  1070  1978 W libprocessgroup: failed to open /acct/uid_1000/pid_6421/cgroup.procs: No such file or directory
08-30 17:08:31.587  7749  7749 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 17:08:31.689  7749  7749 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:31.689  7749  7749 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:08:31.744  7749  7749 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 17:08:31.785  7749  7749 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 17:08:31.788  7749  7749 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 17:08:31.811  7749  7749 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:08:31.812  7749  7749 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-30 17:08:31.851  1070  1969 I ActivityManager: Killing 7054:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 17:08:31.931  1070  2000 W libprocessgroup: failed to open /acct/uid_10046/pid_7054/cgroup.procs: No such file or directory
,08-30 17:08:31.943  4607  7790 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 17:08:31.945  3434  4477 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 17:08:31.954  3434  4477 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e4ba61b on behalf of 7749
08-30 17:08:32.007  1070  1739 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7791 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:32.044  7749  7749 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 17:08:32.068  7749  7749 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 17:08:32.082  7791  7791 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 17:08:32.105  7791  7791 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 17:08:32.105  7791  7791 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 17:08:32.105  7791  7791 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 17:08:32.105  7791  7791 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 17:08:32.105  7791  7791 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 17:08:32.105  7791  7791 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 17:08:32.125  1070  1908 I ActivityManager: Killing 7076:com.android.chrome/u0a57 (adj 15): empty #17
,08-30 17:08:32.204  1070  1978 W libprocessgroup: failed to open /acct/uid_10057/pid_7076/cgroup.procs: No such file or directory
,08-30 17:08:32.467  1070  1597 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:08:32.492  4607  7790 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 548 ms] updated apps [took 548 ms] 
,08-30 17:08:33.173  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:33.173  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30ae4621 added. We now have 6 listener(s)
,08-30 17:08:33.173  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:33.181  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:33.181  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32181a46 added. We now have 7 listener(s)
08-30 17:08:33.181  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.182  6593  6694 I System.out: IsBluetoothEnabled
08-30 17:08:33.184  1070  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:33.184  1070  1888 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 17:08:33.185  1070  1248 D BluetoothManagerService: Message: 2
08-30 17:08:33.190  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.196  1070  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:33.196  1070  1969 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-30 17:08:33.219  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:33.220  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:33.220  1070  1070 D Ulp_jni : JNI:system_update. Event-4
,08-30 17:08:33.223  1070  1248 D BluetoothManagerService: Message: 1
,08-30 17:08:33.223  1070  1248 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 17:08:33.249  1070  1248 D BluetoothManagerService: Message: 20
08-30 17:08:33.249  1070  1248 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bd88315:true
,08-30 17:08:33.254  7611  7611 D BluetoothAdapterState: make
08-30 17:08:33.259  7611  7611 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 17:08:33.259  7611  7611 I bluedroid-qcom: init
08-30 17:08:33.260  7611  7821 I BluetoothAdapterState: Entering OffState
08-30 17:08:33.261  7611  7611 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 17:08:33.261  7611  7611 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 17:08:33.261  7611  7611 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:08:33.261  7611  7611 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 17:08:33.261  7611  7611 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 17:08:33.263  7611  7611 I bluedroid-qcom: get_profile_interface socket
08-30 17:08:33.263  7611  7611 I bluedroid-qcom: get_profile_interface map_client
,08-30 17:08:33.268  7611  7825 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 17:08:33.256  7824  7824 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:33.274  7611  7825 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 17:08:33.256  7824  7824 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:33.285  1070  1070 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-30 17:08:33.287  1070  1248 D BluetoothManagerService: Message: 40
08-30 17:08:33.287  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 17:08:33.290  1070  1070 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 17:08:33.290  1070  1070 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 17:08:33.291  7824  7824 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 17:08:33.291  7824  7824 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 17:08:33.291  7824  7824 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 17:08:33.292  7611  7628 I bluedroid-qcom: config_hci_snoop_log
08-30 17:08:33.293  1070  1248 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 17:08:33.293  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 17:08:33.293  7824  7824 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 17:08:33.296  7611  7825 D BluetoothAdapterProperties: Name is: G3
,08-30 17:08:33.301  7824  7824 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 17:08:33.301  7824  7824 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 17:08:33.306  7611  7821 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 17:08:33.307  7611  7821 D BluetoothAdapterProperties: Setting state to 11
08-30 17:08:33.307  7611  7821 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 17:08:33.308  7611  7821 I LGBluetoothServiceJni: classInitNative: succeeds
,08-30 17:08:33.314  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:33.314  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 17:08:33.314  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 17:08:33.319  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:33.319  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:08:33.323  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.334  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 17:08:33.342  7611  7821 D BluetoothBondStateMachine: make
,08-30 17:08:33.350  7611  7834 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 17:08:33.350  7611  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.351  7611  7821 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 17:08:33.351  7611  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.351  7611  7821 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 17:08:33.352  7611  7821 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 17:08:33.355  7611  7611 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:08:33.355  7611  7611 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:33.355  7611  7611 V BluetoothPbapReceiver: ***********state = 11
08-30 17:08:33.358  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:33.360  7611  7821 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:33.369  7611  7611 D HeadsetService: Received start request. Starting profile...
,08-30 17:08:33.370  7611  7611 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:08:33.370  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 17:08:33.370  7611  7611 D LGBluetoothHfpAdapter: Version 1.6
08-30 17:08:33.373  7611  7611 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 17:08:33.374  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:08:33.374  7611  7611 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:08:33.377  7611  7611 D HeadsetStateMachine: make
,08-30 17:08:33.381  7611  7821 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:33.386  7611  7821 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:33.390  7611  7821 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:08:33.395  7611  7821 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:33.400  7611  7821 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:08:33.404  7611  7821 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:08:33.415  7611  7611 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 17:08:33.416  7611  7611 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:08:33.419  7611  7821 V LGMDMManager: Create singleton instance
08-30 17:08:33.421  7611  7611 D HeadsetStateMachine: max_hf_connections = 1
08-30 17:08:33.421  7611  7611 I bluedroid-qcom: get_profile_interface handsfree
08-30 17:08:33.421  7611  7821 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 17:08:33.423  7611  7611 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 17:08:33.423   312   312 V AudioPolicyService: registerClient() client 0xb558a840, uid 1002
,08-30 17:08:33.423   312  1382 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 17:08:33.423   312  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:08:33.423   312  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:08:33.423  7611  7611 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 17:08:33.424   312  2119 V AudioFlinger: registerClient() client 0xb5581628, pid 7611
08-30 17:08:33.424   312  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:33.424   312  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:33.424  7611  7611 V ToneGenerator: Create Track: 0xb4928a80
08-30 17:08:33.424  7611  7611 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 17:08:33.424  7611  7611 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 17:08:33.425   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:08:33.425   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 17:08:33.425   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:08:33.425   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:08:33.425  7611  7611 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 17:08:33.425  1587  2085 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:33.425   312  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:33.425   312  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:33.425  1587  2085 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:33.425  1070  1086 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:33.425  1070  1086 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:33.426   312  1381 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 17:08:33.426  7611  7627 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:33.426  7611  7627 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 17:08:33.426   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:08:33.426   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 17:08:33.426  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:33.426   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:08:33.426  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:33.426   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:08:33.426  3386  3401 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:08:33.426  3386  3401 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:08:33.426  1070  1739 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:33.426  1070  1739 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:33.427  3386  3402 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:33.427  3386  3402 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:33.427  1587  2085 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:33.427  7611  7627 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:33.427  1587  2085 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:33.427  7611  7627 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 17,:08:33.427  7611  7611 V AudioSystem: getLatency() output 2, latency 50
08-30 17:08:33.427  7611  7611 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 17:08:33.427  7611  7611 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 17:08:33.427  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:08:33.427  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:08:33.427   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:08:33.427   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 17:08:33.427   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:08:33.427   312  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 17:08:33.427   312  1381 V AudioFlinger: createTrack() lSessionId: 23
08-30 17:08:33.428  7611  7611 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 17:08:33.428   312  1381 V AudioFlinger: acquiring 23 from 7611, for 7611
08-30 17:08:33.428   312  1381 V AudioFlinger:  added new entry for 23
08-30 17:08:33.428  7611  7611 V ToneGenerator: ToneGenerator INIT OK, time: 134863
08-30 17:08:33.428  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.429  7611  7842 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 17:08:33.430  7611  7842 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:08:33.430  7611  7842 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:08:33.430  7611  7842 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 17:08:33.431   312  2115 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7611
08-30 17:08:33.433   312  2115 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 17:08:33.433   312  2115 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 17:08:33.433   312  2115 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 17:08:33.433   312  2115 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 17:08:33.433   312  2115 V voice   : voice_set_parameters: exit with code(0)
08-30 17:08:33.433   312  2115 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 17:08:33.433   312  2115 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 17:08:33.434   312  2115 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 17:08:33.434   312  2115 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 17:08:33.434   312  2115 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 17:08:33.434   312  2115 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 17:08:33.434  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.435  7611  7842 V ToneGenerator: ToneGenerator destructor
08-30 17:08:33.435  7611  7842 V ToneGenerator: stopTone
08-30 17:08:33.435  7611  7842 V ToneGenerator: Delete Track: 0xb4928a80
08-30 17:08:33.436  7611  7842 V AudioTrack: ~AudioTrack, releasing session id from 7611 on behalf of 7611
08-30 17:08:33.436   312  1381 V AudioFlinger: releasing 23 from 7611 for 7611
08-30 17:08:33.436   312  1381 V AudioFlinger:  decremented refcount to 0
08-30 17:08:33.436   312  1381 V AudioFlinger: purging stale effects
08-30 17:08:33.436   312  1381 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 17:08:33.436   312  1381 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 17:08:33.436   312  1272 V AudioPolicyService: AudioCommandThread() waking up
08-30 17:08:33.436   312  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 17:08:33.436   312  1272 V AudioPolicyManager: releaseOutput() 2
08-30 17:08:33.436   312  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 17:08:33.436   312  1381 V AudioFlinger: PlaybackThread::Track destructor
08-30 17:08:33.436   312  1381 V AudioFlinger: removeClient_l() pid 7611, calling pid 312
08-30 17:08:33.437  7611  7611 D A2dpService: Received start request. Starting profile...
08-30 17:08:33.438  7611  7611 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 17:08:33.439  7611  7611 V Avrcp   : make
08-30 17:08:33.440  7611  7611 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 17:08:33.440  7611  7611 I bluedroid-qcom: get_profile_interface avrcp
08-30 17:08:33.450  7611  7611 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 17:08:33.451  7611  7611 E AudioManager: No RCC entry present to update
08-30 17:08:33.452  7611  7611 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 17:08:33.455  7611  7611 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 17:08:33.457  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 17:08:33.457  7611  7611 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 17:08:33.461  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 17:08:33.574  1070  1908 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:08:33.574  1070  1908 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:08:33.697  1070  1888 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 17:08:33.720  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 17:08:33.727  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 17:08:33.727  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:08:33.728  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 17:08:33.729  7611  7611 I BluetoothA2dpServiceJni: classInitNative
08-30 17:08:33.729  7611  7611 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:08:33.729  7611  7611 D A2dpStateMachine: make
08-30 17:08:33.732  7611  7611 I bluedroid-qcom: get_profile_interface a2dp
08-30 17:08:33.733  7611  7852 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 17:08:33.736  7611  7611 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 17:08:33.736  7611  7611 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 17:08:33.737  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.738  7611  7851 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:08:33.739  7611  7611 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 17:08:33.742  7611  7611 D HidService: Received start request. Starting profile...
08-30 17:08:33.742  7611  7611 I bluedroid-qcom: get_profile_interface hidhost
08-30 17:08:33.742  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.743  7611  7611 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:08:33.745  7611  7611 D HealthService: Received start request. Starting profile...
08-30 17:08:33.748  7611  7611 I bluedroid-qcom: get_profile_interface health
08-30 17:08:33.749  7611  7611 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:08:33.749  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.750  7611  7611 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:08:33.752  7611  7611 D PanService: Received start request. Starting profile...
,08-30 17:08:33.752  7611  7611 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:08:33.752  7611  7611 I bluedroid-qcom: get_profile_interface pan
08-30 17:08:33.762  7611  7611 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 17:08:33.762  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.764  7611  7611 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 17:08:33.770  7611  7611 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:08:33.771  7611  7611 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:08:33.771  7611  7611 D BtGatt.GattService: start()
08-30 17:08:33.771  7611  7611 I bluedroid-qcom: get_profile_interface gatt
08-30 17:08:33.772  7611  7611 D BtGatt.AdvertiseManager: advertise manager created
08-30 17:08:33.783  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
,08-30 17:08:33.785  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:33.786  7611  7611 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 17:08:33.787  7611  7611 V BluetoothMapService: BluetoothMapBinder()
08-30 17:08:33.788  7611  7611 D BluetoothMapService: Received start request. Starting profile...
08-30 17:08:33.788  7611  7611 D BluetoothMapService: start()
08-30 17:08:33.794  7611  7611 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 17:08:33.794  7611  7611 D BluetoothMapEmailAppObserver: createReceiver()
08-30 17:08:33.795  7611  7611 D BluetoothMapEmailAppObserver: initObservers()
08-30 17:08:33.796  7611  7611 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 17:08:33.808  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
,08-30 17:08:33.808  7611  7611 D HeadsetStateMachine: Proxy object connected
08-30 17:08:33.809  7611  7611 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 17:08:33.810  7611  7611 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 17:08:33.812  7611  7842 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 17:08:33.813  7611  7842 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:08:33.813  7611  7842 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 17:08:33.818  7611  7611 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:08:33.820  7611  7611 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:33.828  7611  7611 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 17:08:33.831  7611  7611 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:08:33.835  7611  7611 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:08:33.836  7611  7611 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 17:08:33.840  7611  7611 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 17:08:33.843  7611  7611 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 17:08:33.843  7611  7611 V BluetoothMapService: Handler(): got msg=1
,08-30 17:08:33.844  7611  7611 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:33.844  7611  7611 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:33.844  7611  7611 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:33.844  7611  7611 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:33.845  7611  7821 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 17:08:33.845  7611  7611 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 17:08:33.845  7611  7821 I bluedroid-qcom: enable
08-30 17:08:33.846  7611  7821 I bt_hci_bdroid: init
08-30 17:08:33.849  7611  7821 I bt_vendor: bt-vendor : init
08-30 17:08:33.849  7611  7821 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:08:33.849  7611  7821 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 17:08:33.849  7611  7821 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 17:08:33.849  7611  7821 D bt_userial_mct: userial_init
08-30 17:08:33.850  7611  7821 D bt_hci_bdroid: set_power 1
08-30 17:08:33.850  7611  7821 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 17:08:33.850  7611  7821 I bt_vendor: Starting hciattach daemon
08-30 17:08:33.850  7611  7821 I bt_vendor: try to set true
08-30 17:08:33.850  7611  7859 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 17:08:33.850  7611  7859 I bt-btu  : btu_task pending for preload complete event
08-30 17:08:33.836  7862  7862 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:33.836  7862  7862 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:33.878  7863  7863 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 17:08:33.992  7869  7869 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 17:08:34.006  7870  7870 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:08:34.046  7872  7872 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:08:34.059  7873  7873 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 17:08:34.073  7874  7874 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:08:34.086  7875  7875 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 17:08:34.113  7877  7877 I libmdmdetect: ESOC framework not supported
08-30 17:08:34.115  7877  7877 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 17:08:34.125  7877  7877 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 17:08:34.125  7877  7877 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 17:08:34.125  7877  7877 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 17:08:34.125  7877  7877 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 17:08:34.125  7877  7877 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 17:08:34.125  7877  7877 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 17:08:34.125  7877  7877 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 17:08:34.173  7877  7878 E QC-QMI  : qmi_client [7877] 15: failed to locate client data
08-30 17:08:34.176   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 17:08:34.176   475   475 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 17:08:34.224  7882  7882 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 17:08:34.240  7886  7886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:08:34.306  7611  7821 I bt_vendor: bluetooth satus is on
,08-30 17:08:34.307  7611  7821 D bt_hci_bdroid: preload
,08-30 17:08:34.315  7611  7861 D bt_userial_mct: userial_open(port:0)
,08-30 17:08:34.315  7611  7861 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 17:08:34.320  7611  7861 I bt_vendor: Done intiailizing UART
,08-30 17:08:34.323  7611  7861 I bt_vendor: Done intiailizing UART
,08-30 17:08:34.323  7611  7861 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-30 17:08:34.324  7611  7861 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 17:08:34.327  7611  7859 I bt-btu  : btu_task received preload complete event,
08-30 17:08:34.328  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001,
08-30 17:08:34.329  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f,
,08-30 17:08:34.335  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-30 17:08:34.353  7611  7888 D bt_userial_mct: Entering userial_read_thread()
08-30 17:08:34.360  7611  7859 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 17:08:34.360  7611  7859 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:08:34.360  7611  7859 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 17:08:34.360  7611  7859 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:08:34.361  7611  7859 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 17:08:34.418  7611  7859 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-30 17:08:34.418  7611  7859 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021e061 
08-30 17:08:34.418  7611  7859 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021e061 
,08-30 17:08:34.436  7611  7825 E bt-btif : Calling BTA_HhEnable
08-30 17:08:34.436  7611  7825 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 17:08:34.436  7611  7825 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 17:08:34.441  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 17:08:34.441  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 17:08:34.441  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 17:08:34.441  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 17:08:34.441  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 17:08:34.442  7611  7825 D BluetoothAdapterProperties: Name is: G3
08-30 17:08:34.443  7611  7825 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:08:34.443  7611  7825 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:08:34.443  7611  7825 D bt_hci_bdroid: postload
08-30 17:08:34.443  7611  7861 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:08:34.444  7611  7825 D bte_conf: Device ID record 1 : primary
08-30 17:08:34.444  7611  7825 D bte_conf:   vendorId            = 00c4
08-30 17:08:34.444  7611  7825 D bte_conf:   vendorIdSource      = 0001
08-30 17:08:34.444  7611  7825 D bte_conf:   product             = 13a1
08-30 17:08:34.444  7611  7825 D bte_conf:   version             = 1000
08-30 17:08:34.444  7611  7825 D bte_conf:   clientExecutableURL = 
08-30 17:08:34.444  7611  7825 D bte_conf:   serviceDescription  = 
08-30 17:08:34.444  7611  7825 D bte_conf:   documentationURL    = 
08-30 17:08:34.444  7611  7825 D bte_conf: bte_load_did_conf no section named DID2.
08-30 17:08:34.446  7611  7859 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 17:08:34.446  7611  7861 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:08:34.449  7611  7821 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 17:08:34.449  7611  7821 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:08:34.449  7611  7821 D BluetoothAdapterProperties: State =  11
08-30 17:08:34.449  7611  7821 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 17:08:34.449  7611  7821 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 17:08:34.449  7611  7821 D BluetoothAdapterProperties: Setting state to 12
08-30 17:08:34.449  7611  7821 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 17:08:34.450  7611  7825 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 17:08:34.451  7611  7825 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 17:08:34.446  7890  7890 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:34.460  1070  1248 D BluetoothManagerService: Message: 60
08-30 17:08:34.446  7890  7890 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:34.465  7611  7821 I BluetoothAdapterState: Entering On State
08-30 17:08:34.468  7611  7861 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 17:08:34.471  7611  7861 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:08:34.472  7611  7888 E bt_mct  : hci lib postload completed
08-30 17:08:34.478  7611  7859 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:34.479  7611  7859 W bt-smp  : Plain text(LSB ~ MSB) = 96 73 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:34.479  7611  7859 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a 7a 76 46 25 7d 51 b2 34 69 82 7f 54 a7 d1 8f 
08-30 17:08:34.479  7611  7859 W bt-btm  : Stopping oneshot timer
,08-30 17:08:34.483  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 17:08:34.483  1070  1248 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 17:08:34.483  1070  1248 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:08:34.487  7611  7821 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 17:08:34.487  7611  7821 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 17:08:34.487  7611  7821 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 17:08:34.488  7611  7821 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 17:08:34.521  7611  7821 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-30 17:08:34.525  1070  1070 D BluetoothHeadset: Proxy object connected
08-30 17:08:34.530  6805  6821 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:08:34.532  1070  1248 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:08:34.540  7611  7825 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:08:34.540  7611  7825 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-30 17:08:34.549  1070  1070 D BluetoothA2dp: Proxy object connected
08-30 17:08:34.550  7611  7859 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:34.551  7611  7859 W bt-smp  : Plain text(LSB ~ MSB) = 56 06 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:34.551  7611  7859 W bt-smp  : Encrypted text(LSB ~ MSB) = ce 45 23 b2 2b 25 a4 b2 ef a5 8f 16 1d 50 43 d7 
08-30 17:08:34.551  7611  7859 W bt-btm  : Stopping oneshot timer
08-30 17:08:34.552  6805  6805 D BluetoothInputDevice: Proxy object connected
,08-30 17:08:34.553  6805  6805 D HidProfile: Bluetooth service connected
08-30 17:08:34.555  1070  1070 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 17:08:34.556  1070  1070 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 17:08:34.560  6805  6820 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:34.571  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:34.574  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:34.576  7611  7859 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:34.576  7611  7859 W bt-smp  : Plain text(LSB ~ MSB) = 27 8f 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:34.576  7611  7859 W bt-smp  : Encrypted text(LSB ~ MSB) = 56 88 95 5d 13 47 83 24 aa a0 9d 2c 1c 4a 85 f0 
08-30 17:08:34.576  7611  7859 W bt-btm  : Stopping oneshot timer
08-30 17:08:34.577  6805  6821 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:08:34.580  7912  7912 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 17:08:34.581  6805  7518 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:08:34.585  1837  2409 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:08:34.585  6805  6805 D BluetoothMap: Proxy object connected
08-30 17:08:34.585  6805  6805 D MapProfile: Bluetooth service connected
08-30 17:08:34.585  6805  6805 D BluetoothMap: getConnectedDevices()
08-30 17:08:34.587  7611  7627 V BluetoothMapService: getConnectedDevices()
08-30 17:08:34.587  7611  7859 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:34.587  7611  7859 W bt-smp  : Plain text(LSB ~ MSB) = b2 76 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:34.587  7611  7859 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 cd a6 ec fc c1 12 1f 68 fe 0f 87 58 7a 29 f9 
08-30 17:08:34.587  7611  7859 W bt-btm  : Stopping oneshot timer
08-30 17:08:34.588  6805  6805 D BluetoothA2dp: Proxy object connected
08-30 17:08:34.588  6805  6805 D A2dpProfile: Bluetooth service connected
08-30 17:08:34.588  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 17:08:34.589  6805  7518 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:08:34.590  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:08:34.591  6805  6805 D BluetoothHeadset: Proxy object connected
08-30 17:08:34.591  6805  6805 D HeadsetProfile: Bluetooth service connected
08-30 17:08:34.593  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 17:08:34.593  1837  2409 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:08:34.595  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 17:08:34.595  6805  6821 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:08:34.595  6805  6821 D BluetoothPan: onBluetoothStateChange call bindService
08-30 17:08:34.596  7611  7859 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:08:34.596  7611  7859 W bt-smp  : Plain text(LSB ~ MSB) = f8 9d 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:08:34.596  7611  7859 W bt-smp  : Encrypted text(LSB ~ MSB) = 72 5d df f2 98 05 30 04 a7 03 74 90 12 51 a9 40 
08-30 17:08:34.596  7611  7859 W bt-btm  : Stopping oneshot timer
08-30 17:08:34.598  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:34.598  6805  6805 D PanProfile: Bluetooth service connected
08-30 17:08:34.598  1070  1248 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 17:08:34.598  1070  1248 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 17:08:34.600  1070  1070 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 17:08:34.600  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:34.600  1924  2134 D LGBluetoothAPIService: Message: 1
08-30 17:08:34.600  1924  2134 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 17:08:34.600  1924  2134 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 17:08:34.601  1924  2134 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 17:08:34.601  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:08:34.603  1070  1248 D BluetoothManagerService: Message: 40
08-30 17:08:34.604  1070  1248 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 17:08:34.606  7611  7611 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:34.606  7611  7611 D BluetoothMapService: STATE_ON
08-30 17:08:34.607  7611  7611 V BluetoothMapService: Handler(): got msg=1
08-30 17:08:34.607  7611  7611 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 17:08:34.609  7611  7913 D BluetoothMapMasInstance: MAS initSocket()
08-30 17:08:34.609  7611  7913 D BluetoothMapMasInstance:   masId = 00
08-30 17:08:34.609  7611  7913 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 17:08:34.609  7611  7913 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 17:08:34.609  7611  7913 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 17:08:34.610  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:34.611  1070  1759 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:34.614  7611  7913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:34.615  7611  7913 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 17:08:34.615  7611  7913 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 17:08:34.615  7611  7913 D BluetoothMapMasInstance: Accepting socket connection...
08-30 17:08:34.616  7611  7825 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:08:34.616  7611  7825 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 17:08:34.619  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:34.620  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-30 17:08:34.621  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:08:34.623  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:34.623  7611  7611 V BluetoothPbapService: Pbap Service onCreate
08-30 17:08:34.623  7611  7611 V BluetoothPbapService: Starting PBAP service
,08-30 17:08:34.625  7611  7611 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 17:08:34.625  7611  7611 V BluetoothPbapService: Pbap Service onBind
08-30 17:08:34.626  7611  7611 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:34.626  7611  7611 V BluetoothPbapService: state: 12
08-30 17:08:34.627  7611  7611 V BluetoothPbapService: Handler(): got msg=1
08-30 17:08:34.627  7611  7611 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 17:08:34.627  7611  7611 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:08:34.628  7611  7611 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:34.628  7611  7611 V BluetoothPbapReceiver: ***********state = 12
08-30 17:08:34.628  7611  7915 V BluetoothPbapService: Pbap Service initSocket
08-30 17:08:34.629  6805  6805 D DockEventReceiver: finishStartingService: stopping service
08-30 17:08:34.630  6805  6805 D BluetoothPbap: Proxy object connected
08-30 17:08:34.630  6805  6805 D PbapServerProfile: Bluetooth service connected
08-30 17:08:34.631  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:34.631  2160  2160 D c       : Getting all permits...
08-30 17:08:34.631  2160  2160 D a       : Opening database...
08-30 17:08:34.632  1070  1745 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:34.633  7611  7915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:34.634  7611  7915 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 17:08:34.634  7611  7915 V BluetoothPbapService: Succeed to create listening socket 
08-30 17:08:34.634  7611  7915 V BluetoothPbapService: Accepting socket connection...
08-30 17:08:34.635  2160  2160 D a       : Opening database auth.proximity.permit_store...
08-30 17:08:34.636  2160  2160 D a       : Closing database...
,08-30 17:08:34.644  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 17:08:34.646  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 17:08:34.647  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 17:08:34.649  7611  7611 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 17:08:34.651  7611  7611 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 17:08:34.656  7611  7611 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 17:08:34.673  7611  7611 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 17:08:34.674  7611  7611 V BtOppService: onCreate
,08-30 17:08:34.677  7611  7611 V BluetoothOppNotification: send message
,08-30 17:08:34.679  7611  7611 V BtOppService: Starting RfcommListener
08-30 17:08:34.682  7611  7611 D BluetoothOppPreference: Dumping Names:  
08-30 17:08:34.682  7611  7611 D BluetoothOppPreference: {}
08-30 17:08:34.682  7611  7611 D BluetoothOppPreference: Dumping Channels:  
08-30 17:08:34.683  7611  7611 D BluetoothOppPreference: {}
08-30 17:08:34.683  7611  7611 V BtOppService: onStartCommand
08-30 17:08:34.684  7611  7923 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:08:34.686  7611  7611 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:34.686  7611  7611 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 17:08:34.686  7611  7920 V BtOppService: Deleted complete outbound shares, number =  0
08-30 17:08:34.687  7611  7923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 17:08:34.690  7611  7920 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 17:08:34.690  7611  7611 V BluetoothOppNotification: new notify threadi!
08-30 17:08:34.691  7611  7611 V BluetoothOppNotification: send delay message
08-30 17:08:34.691  7611  7920 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 17:08:34.691  7611  7611 V BtOppService: start RfcommListener
08-30 17:08:34.693  7611  7611 V BtOppService: RfcommListener started
08-30 17:08:34.693  7611  7611 V BtOppService: ContentObserver received notification
08-30 17:08:34.693  7611  7920 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c7f24ce on behalf of 
08-30 17:08:34.695  7611  7923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24ad9fef on behalf of 
08-30 17:08:34.701  7611  7925 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 17:08:34.701  1070  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:34.702  7611  7925 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:34.704  7611  7925 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-30 17:08:34.704  7611  7925 V BtOppRfcommListener: Started RFCOMM listener....
08-30 17:08:34.704  7611  7925 I BtOppRfcommListener: Accept thread started.
08-30 17:08:34.704  7611  7925 V BtOppRfcommListener: Accepting connection...
08-30 17:08:34.704  7611  7923 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:08:34.704  7611  7923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:08:34.705  7611  7923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26821afc on behalf of 
08-30 17:08:34.706  7611  7923 V BluetoothOppNotification: update too frequent, put in queue
08-30 17:08:34.710  7611  7923 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 17:08:34.712  7611  7924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 17:08:34.715  7611  7924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24867585 on behalf of 
,08-30 17:08:34.718  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
,08-30 17:08:34.718  7611  7611 V BluetoothFtpService: Ftp Service onCreate
08-30 17:08:34.719  7611  7611 I BluetoothFtpService: Ftp Service onCreate
08-30 17:08:34.719  7611  7611 V BluetoothFtpService: Ftp Service onStartCommand
08-30 17:08:34.719  7611  7611 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:34.720  7611  7611 V BluetoothFtpService: Starting Listening on sockets
08-30 17:08:34.720  7611  7611 V BtOppService: ContentObserver received notification
08-30 17:08:34.721  7611  7611 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:08:34.721  7611  7611 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:08:34.721  7611  7611 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:08:34.721  7611  7611 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:34.721  7611  7926 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:08:34.721  7611  7611 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 17:08:34.722  7611  7926 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:08:34.722  7611  7611 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 17:08:34.723  7611  7926 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19de4c0b on behalf of 
08-30 17:08:34.724  7611  7611 V BluetoothFtpService: Handler(): got msg=1
08-30 17:08:34.724  7611  7926 V BluetoothOppNotification: update too frequent, put in queue
08-30 17:08:34.725  7611  7611 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 17:08:34.725  7611  7611 V BluetoothFtpService: Ftp Service initSocket
08-30 17:08:34.726  7611  7926 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 17:08:34.725  7611  7924 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 17:08:34.729  1070  1937 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:34.730  7611  7611 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:34.731  7611  7611 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 17:08:34.732  7611  7924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 17:08:34.733  7611  7927 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 17:08:34.744  7611  7611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e260172
08-30 17:08:34.744  7611  7611 V BluetoothSapService: Sap Service onCreate
08-30 17:08:34.747  7611  7611 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:34.747  7611  7611 V BluetoothSapService: state: 12
08-30 17:08:34.747  7611  7611 V BluetoothSapService: Starting SAP server process
,08-30 17:08:34.749  7611  7611 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 17:08:34.736  7928  7928 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:34.751  7611  7929 V BluetoothSapService: Sap Service initRfcommSocket
08-30 17:08:34.751  1070  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:34.752  7611  7929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:34.753  7611  7929 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 17:08:34.753  7611  7929 V BluetoothSapService: Succeed to create listening socket 
08-30 17:08:34.754  7611  7929 V BluetoothSapService: Accepting socket connection...
08-30 17:08:34.736  7928  7928 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:34.761  7928  7928 V BT_SAP  : Event pipe created
08-30 17:08:34.761  7928  7928 V BT_SAP  : create_server_socket qcom.sap.server
08-30 17:08:34.761  7928  7928 V BT_SAP  : created socket fd 6
,08-30 17:08:34.863  1070  2000 I art     : Explicit concurrent mark sweep GC freed 25136(1253KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.938ms total 129.156ms
08-30 17:08:34.864  7611  7924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18239de7 on behalf of 
,08-30 17:08:34.867  7611  7924 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 17:08:34.870  7611  7924 V BluetoothOppNotification: outbound notification was removed.
,08-30 17:08:34.870  7611  7924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-30 17:08:34.872  7611  7924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28f0cd94 on behalf of 
,08-30 17:08:34.872  7611  7924 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 17:08:34.873  7611  7924 V BluetoothOppNotification: inbound notification was removed.
,08-30 17:08:34.873  7611  7924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.,
,08-30 17:08:34.874  7611  7924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21a2d03d on behalf of 
,08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:35.257  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:35.280  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:35.283  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:35.283  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@468b407 added. We now have 8 listener(s)
08-30 17:08:35.283  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:35.289  1070  1560 D WifiServiceImplEx: setWifiEnabled: false pid=6593, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:08:35.289  1070  1560 D WifiService: setWifiEnabled: false pid=6593, uid=10118
08-30 17:08:35.289  1070  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:08:35.293  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:35.296  1070  2033 D WifiServiceImplEx: setWifiEnabled: true pid=6593, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:08:35.297  1070  2033 D WifiService: setWifiEnabled: true pid=6593, uid=10118
08-30 17:08:35.297  1070  2033 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:08:35.326  1070  1070 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:08:35.326  1070  1070 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:08:35.326  1070  1070 D Ulp_jni : JNI:system_update. Event-4
08-30 17:08:35.328  1070  1437 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 17:08:35.328  1070  1437 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 17:08:35.337  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1070] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 17:08:35.337  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 17:08:35.337  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1070] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 17:08:35.337  1070  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 17:08:35.338  1070  1437 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 17:08:35.338  1070  1437 E WifiHW  : unknown target_country: EU , set to default
08-30 17:08:35.338  1070  1437 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 17:08:35.338  1070  1437 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 17:08:35.338  1070  1437 I WifiUtil: gEnableBmps=1
,08-30 17:08:35.692  7611  7611 V BluetoothOppNotification: new notify threadi!
,08-30 17:08:35.693  7611  7611 V BluetoothOppNotification: send delay message
,08-30 17:08:35.706  7611  7942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 17:08:35.710  7611  7942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39f37032 on behalf of 
,08-30 17:08:35.713  7611  7942 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 17:08:35.720  7611  7942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 17:08:35.721  7611  7942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11823183 on behalf of 
,08-30 17:08:35.722  7611  7942 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 17:08:35.723  7611  7942 V BluetoothOppNotification: outbound notification was removed.
08-30 17:08:35.723  7611  7942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 17:08:35.724  7611  7942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dd72f00 on behalf of 
08-30 17:08:35.725  7611  7942 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 17:08:35.769  7611  7942 V BluetoothOppNotification: inbound notification was removed.
08-30 17:08:35.770  7611  7942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 17:08:35.776  7611  7942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ef13339 on behalf of 
,08-30 17:08:35.874  1070  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29505d8e type 2 when 137289 com.google.android.gms} when 137289
,08-30 17:08:35.898   308  7950 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 17:08:35.917  1070  1246 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 17:08:35.941   308   917 D SoftapController: Softap fwReload - Ok
,08-30 17:08:35.946  1070  1437 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (599ms)
08-30 17:08:35.953  1070  1248 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:35.953  1070  1248 D Tethering: InitialState.processMessage what=4
08-30 17:08:35.954  1070  1248 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 17:08:35.971   308   917 D CommandListener: Setting iface cfg
08-30 17:08:35.971   308   917 D CommandListener: Trying to bring down wlan0
08-30 17:08:35.973   308   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:08:35.977  1070  1437 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 17:08:35.976  7952  7952 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:08:35.986  7952  7952 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:36.003  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:36.003  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:36.003  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 17:08:36.017  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 17:08:36.028  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:36.036  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:36.036  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:08:36.036  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:08:36.036  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:08:36.037  1070  1437 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 17:08:36.038  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 17:08:36.038  1070  1437 D WifiMonitor: connecting to supplicant
08-30 17:08:36.042  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:08:36.044  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:36.047  7952  7952 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 17:08:36.048  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:08:36.049  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 17:08:36.049  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:08:36.049  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:08:36.049  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:08:36.049  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:08:36.052  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:36.052  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:08:36.052  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:08:36.052  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:08:36.052  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:08:36.053  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:08:36.053  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 17:08:36.053  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:08:36.053  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:08:36.053  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:08:36.053  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:08:36.078  7952  7952 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 17:08:36.078  7952  7952 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 17:08:36.094  1070  1908 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7969 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 17:08:36.112   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 18.983ms
,08-30 17:08:36.131   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 348us total 18.264ms
,08-30 17:08:36.147   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 15.787ms
,08-30 17:08:36.169  7952  7952 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:08:36.182  1070  1908 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7990 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:08:36.185  7969  7988 W FormManager: Network not available. Please check & try again.
,08-30 17:08:36.193  7969  8002 V FormManager: Network unavailable.
08-30 17:08:36.194  7969  8002 V FormManager: Network unavailable.
,08-30 17:08:36.205  1070  2033 I ActivityManager: Killing 7100:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 17:08:36.208  7952  7952 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 17:08:36.215  7952  7952 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 17:08:36.215  7952  7952 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-30 17:08:36.216  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-30 17:08:36.216  1070  8010 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 17:08:36.216  1070  8010 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 17:08:36.216  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 17:08:36.216  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 17:08:36.216  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:08:36.216  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:08:36.216  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 17:08:36.217  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:08:36.217  1070  1437 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:08:36.218  1070  1437 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:36.218  1070  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:36.219  1070  1437 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 17:08:36.219  1070  1437 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 17:08:36.219  1070  1437 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 17:08:36.219  1070  1437 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 17:08:36.219  1070  1437 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 17:08:36.225  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:36.257  1070  1759 W libprocessgroup: failed to open /acct/uid_10062/pid_7100/cgroup.procs: No such file or directory
08-30 17:08:36.259  1070  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:08:36.259  1070  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:08:36.259  1070  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 17:08:36.259  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.259  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.260  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.260  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.260  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:08:36.260  1070  1437 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 17:08:36.261  1070  1437 D WifiNative-wlan0: SET update_config 1: returned true
08-30 17:08:36.261  1070  1437 D WifiConfigStore: Loading config and enabling all networks 
08-30 17:08:36.261  1070  1437 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 17:08:36.261  1070  1437 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 17:08:36.262  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:36.262  1924  1924 D WfdService: Waiting for WifiP2p enabling
08-30 17:08:36.268  1070  1437 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:36.271  6593  6593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:36.273  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:36.275  1070  1070 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 17:08:36.275  1070  1481 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 17:08:36.276  6593  6593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:36.278  1070  1437 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 17:08:36.278  1070  1437 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 17:08:36.279  1070  1437 D WifiStateMachine: enableVerboseLogging : level 2
08-30 17:08:36.279  1070  1437 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 17:08:36.280  1070  1437 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 17:08:36.280  1070  1437 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 17:08:36.280  1070  1437 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 17:08:36.280  1070  1437 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 17:08:36.281  1070  1437 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 17:08:36.281  1070  1437 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 17:08:36.281  1070  1437 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 17:08:36.282  1070  1437 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 17:08:36.282  1070  1437 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
,08-30 17:08:36.282  1070  1437 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 17:08:36.283  1070  1437 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 17:08:36.283  1070  1437 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 17:08:36.283  1070  1437 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 17:08:36.284  1070  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:08:36.284  1070  1437 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 17:08:36.284  1070  1437 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 17:08:36.285  1070  1437 D WifiNative-HAL: Setting external_sim to 1
08-30 17:08:36.285  1070  1437 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 17:08:36.285  1924  1924 D WfdsService: Supplicant Connection state is changed : true
08-30 17:08:36.286  1924  2344 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 17:08:36.286  1924  2344 D WfdsService: Set the WFDS Monitor: true
08-30 17:08:36.286  1924  2344 D WfdsMonitor: WfdsMonitorThread create
08-30 17:08:36.287  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:36.287  1924  2344 D WfdsMonitor: WFDS Monitor is created and started
08-30 17:08:36.287  1924  2344 D WfdsService: WiFi: Supplicant connection re-established
08-30 17:08:36.287  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.287  1070  1437 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 17:08:36.287  1070  1437 I WifiNative-HAL: startHal
08-30 17:08:36.288  1070  1437 D wifi    : setting scan oui 0x9579c180
08-30 17:08:36.289  1070  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:08:36.289  1070  1437 I WifiNative-HAL: startHal
08-30 17:08:36.289  1070  1437 D wifi    : setting scan oui 0x9579c180
08-30 17:08:36.289  1070  1978 I ActivityManager: Killing 7122:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 17:08:36.289  1070  1437 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 17:08:36.290  1070  1437 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 17:08:36.290  1924  8013 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 17:08:36.290  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 17:08:36.290  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 17:08:36.290  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 17:08:36.290  1924  8013 E CtrlSupplicant: Succeed to open control connection
08-30 17:08:36.291  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:08:36.291  1924  8013 E CtrlSupplicant: Succeed to open monitor connection
08-30 17:08:36.291  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 17:08:36.291  1924  8013 D WfdsMonitor: Supplicant connection established
08-30 17:08:36.291  1924  2344 D WfdsService: Connected to the supplicant for wfds
08-30 17:08:36.291  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 17:08:36.291  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 17:08:36.291  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 17:08:36.292  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 17:08:36.292  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 17:08:36.292  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 17:08:36.292  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:08:36.292  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:08:36.292  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 17:08:36.293  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-,30 17:08:36.293  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 17:08:36.293  7952  7952 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 17:08:36.293  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 17:08:36.293  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 17:08:36.293  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 17:08:36.293  1070  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:08:36.294  1070  1437 E WifiNative: : [137,715,872 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 17:08:36.294  1070  1437 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 17:08:36.295  1070  1437 D WifiNative-wlan0: RECONNECT: returned true
08-30 17:08:36.295  1070  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 17:08:36.296  1070  1437 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 17:08:36.296  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:36.296  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:08:36.296  1070  1383 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.298   308   917 D CommandListener: Setting iface cfg
08-30 17:08:36.298   308   917 D CommandListener: Trying to bring up p2p0
,08-30 17:08:36.298  1070  1383 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 17:08:36.298  1070  1383 D LGWifiP2pService: P2pEnablingState
08-30 17:08:36.298  1070  1383 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.298  1070  1383 D LGWifiP2pService: P2p socket connection successful
08-30 17:08:36.298  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:08:36.298  1070  1383 D LGWifiP2pService: P2pEnabledState
08-30 17:08:36.299  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 17:08:36.319  1070  1383 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 17:08:36.320  1070  1437 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 17:08:36.320  1070  1383 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 17:08:36.320  1070  1070 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:08:36.321  1070  1437 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 17:08:36.321  1070  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.321  1070  1541 I WifiNative-HAL: startHal
08-30 17:08:36.321  1070  1070 D RttService: SCAN_AVAILABLE : 3
08-30 17:08:36.321  1070  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.321  1070  1437 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 17:08:36.321  1070  1437 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 17:08:36.322  1070  1437 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 17:08:36.322  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 17:08:36.322  1924  1924 D WfdsService: WifiP2pState is changed : true
08-30 17:08:36.322  1070  1437 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 17:08:36.322  1924  2344 D WfdsService: Receive the WFDS_ENABLE Method
08-30 17:08:36.323  1924  2344 D WfdsService: Set the WFDS Monitor: true
08-30 17:08:36.323  1924  2344 D WfdsService: Connected to the supplicant for wfds
08-30 17:08:36.323  1924  2344 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 17:08:36.323  1070  1437 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 17:08:36.323  1070  1437 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 17:08:36.323  7952  7952 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 17:08:36.323  7952  7952 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 17:08:36.323  1924  2344 D WfdsService: selectPreferredScanChannel [36]
08-30 17:08:36.323  1924  2344 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 17:08:36.324  1070  1437 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 17:08:36.324  1070  1437 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 17:08:36.324  1070  1383 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 17:08:36.324  1924  1924 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 17:08:36.324  1070  1383 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 17:08:36.325  1070  1383 D WifiNative-p2p0: SET device_name G3: returned true
08-30 17:08:36.325  1070  1383 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 17:08:36.325  1070  1383 D LGWifiP2pService: before postfix = G3
08-30 17:08:36.325  1924  1924 D WfdsService: isConnected: false
08-30 17:08:36.325  1070  1383 D WifiServerServiceExt: postfix byte check : 2
08-30 17:08:36.325  1070  1383 D LGWifiP2pService: after postfix = G3
08-30 17:08:36.325  1070  1383 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 17:08:36.326  1070  2000 W libprocessgroup: failed to open /acct/uid_10085/pid_7122/cgrou,p.procs: No such file or directory
08-30 17:08:36.326  1070  1383 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 17:08:36.326  1070  1383 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 17:08:36.327  1070  1383 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 17:08:36.327  1070  1383 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-30 17:08:36.327  1070  1383 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 17:08:36.327  1070  1383 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 17:08:36.328  1070  1383 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 17:08:36.328  1070  1383 D WifiNative-HAL: p2pGetDeviceAddress
08-30 17:08:36.329  1070  1383 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 17:08:36.329  1070  1541 D wifi    : getting scan capabilities on interface[1] = 0x9579c180
08-30 17:08:36.329  1070  1541 D wifi    : failed to get capabilities : -3
08-30 17:08:36.329  1070  1541 E WifiScanningService: could not get scan capabilities
08-30 17:08:36.329  1070  1437 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 17:08:36.329  1070  1437 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 17:08:36.330  7952  7952 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 17:08:36.331  1070  1383 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 17:08:36.331  1070  1383 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 17:08:36.331  1070  1437 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 17:08:36.331  1070  1383 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 17:08:36.331  1070  1383 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 17:08:36.331  1070  1437 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 17:08:36.332  1070  1383 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 17:08:36.332  1070  1383 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 17:08:36.332  1070  1383 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 17:08:36.332  1070  1383 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 17:08:36.336  1070  1437 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 17:08:36.337  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:36.337  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:36.340  1924  1924 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 17:08:36.340  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:36.340  1924  1924 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 17:08:36.340  1924  1924 D WfdsService: Update P2p Interface State: 3
,08-30 17:08:36.348  6593  6694 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 17:08:36.349  6593  6694 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 17:08:36.351  1070  1383 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 17:08:36.351  1070  1383 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 17:08:36.351  6593  6694 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@12b0cab1 Bundle[{}]
08-30 17:08:36.352  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 17:08:36.352  7952  7952 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.353  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:08:36.353  1070  1383 D LGWifiP2pService: InactiveState
08-30 17:08:36.353  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.353  1070  1383 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.353  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:36.353  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.353  1070  1383 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 17:08:36.353  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.353  7952  7952 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:08:36.353  7952  7952 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.353  1924  8013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.353  6593  6694 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:08:36.354  1070  8010 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.354  6593  6694 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 17:08:36.354  1070  8010 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-30 17:08:36.354  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.354  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.354  7952  7952 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.355  1070  1437 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 17:08:36.355  1070  1437 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:08:36.356  6593  6694 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 17:08:36.356  1070  1437 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:08:36.356  1924  8013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.356  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 17:08:36.356  1070  8010 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.356  1070  8010 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.356  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.357  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.357  1070  1437 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:08:36.357  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 17:08:36.357  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:36.358  7952  7952 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.359  6593  6694 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 17:08:36.359  7952  7952 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:08:36.359  7952  7952 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.359  1924  8013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:08:36.359  1924  8013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.359  7952  7952 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.360  6593  6694 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 17:08:36.360  1924  8013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.360  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:36.360  6593  6694 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 17:08:36.361  1070  8010 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:08:36.361  1070  8010 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.361  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.361  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:08:36.361  1070  8010 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.361  1070  8010 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.361  1070  1383 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 17:08:36.361  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.361  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.361  1070  8010 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:08:36.361  1070  8010 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANG,E init=DRIVER type=WORLD
08-30 17:08:36.361  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.361  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:08:36.361  1070  1383 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.362  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.362  1070  1383 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.362  1070  1383 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.362  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.362  1070  1383 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.363  1070  1383 D LGWifiP2pService: InactiveState{ when=-7ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.363  1924  2344 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 17:08:36.363  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.363  1070  1383 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.363  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.363  1070  1383 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.364  1070  1383 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.364  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.364  1070  1383 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.364  1070  1070 E WifiServerServiceExt: No p2p device connected
08-30 17:08:36.365  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 17:08:36.365  7952  7952 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:08:36.366  7969  8015 W FormManager: Network not available. Please check & try again.
08-30 17:08:36.366  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 17:08:36.366  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:08:36.366  1070  8010 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:08:36.367  1070  8010 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
08-30 17:08:36.367  6593  6694 I System.out: Running OutgoingSocketThread
08-30 17:08:36.367  1070  1437 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 17:08:36.368  1070  1437 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 17:08:36.368  1070  1437 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 17:08:36.369  1070  1437 D WifiNative-wlan0: doBoolean: SCAN
,08-30 17:08:36.369  1070  1437 D WifiNative-wlan0: SCAN: returned false
08-30 17:08:36.370  6593  8017 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 852)
08-30 17:08:36.371  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137793  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:08:36.371  6593  8017 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50175
08-30 17:08:36.371  6593  8017 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 17:08:36.373  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:36.375  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137797  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:08:36.376  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:36.376  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:36.376  1070  1437 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:08:36.377  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.377  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.377  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:08:36.377  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:36.378  1070  1437 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:08:36.379  1070  1437 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:08:36.381  1070  1437 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-30 17:08:36.382  1070  1437 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:08:36.385  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:36.385  1070  1070 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 17:08:36.385  7969  8016 V FormManager: Network unavailable.
08-30 17:08:36.388  7969  8016 V FormManager: Network unavailable.
08-30 17:08:36.391  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:08:36.391  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:08:36.393  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:08:36.395  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:08:36.398  4331  8018 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:08:36.400  4331  8019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:08:36.400  4331  8019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 17:08:36.446  1070  1942 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8020 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 17:08:36.576  8020  8020 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:08:36.576  8020  8020 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 17:08:36.590  8020  8020 V [BNRBootReceiver]: Boot Receiver Return
,08-30 17:08:36.592  8020  8020 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 17:08:36.675  1070  1086 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8041 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:08:36.678  1070  1086 I ActivityManager: Killing 7151:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-30 17:08:36.769  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-30 17:08:36.769  1070  8010 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 17:08:36.769  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 17:08:36.769  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-30 17:08:36.769  1070  8010 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 17:08:36.770  7952  7952 E wpa_supplicant: USIM:  scard_init function
,08-30 17:08:36.771  7952  7952 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 17:08:36.776  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:08:36.776  1070  1437 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:36.776  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 17:08:36.777  1070  1437 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:36.780  1070  1437 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:36.781  1070  1437 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:08:36.781  1070  1437 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-30 17:08:36.822  1070  1969 W libprocessgroup: failed to open /acct/uid_10093/pid_7151/cgroup.procs: No such file or directory
,08-30 17:08:36.841  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138263  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 17:08:36.853  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:36.853  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 17:08:36.859  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:36.860  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.860  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.860  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:08:36.863  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138285  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 17:08:36.865  8041  8041 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:08:36.870  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.870  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.870  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 17:08:36.870  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:36.870  1070  1070 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 17:08:36.880  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:36.880  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:36.881  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:36.894  7952  7952 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 17:08:36.894  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 17:08:36.894  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 17:08:36.895  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 17:08:36.895  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-30 17:08:36.896  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138318  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 17:08:36.897  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-30 17:08:36.897  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:36.898  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138320  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 17:08:36.898  1070  1248 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:08:36.899  1070  1437 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138321
08-30 17:08:36.900  1070  1437 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138322
08-30 17:08:36.900  1070  1437 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138322
08-30 17:08:36.901  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138323
08-30 17:08:36.902  1070  1437 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138324
08-30 17:08:36.902  1070  1437 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:36.903  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:36.903  1070  1070 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 17:08:36.903  1070  1437 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:36.903  1070  1437 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:36.904  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:36.904  1070  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:08:36.905  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138327  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 17:08:36.908  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:36.908  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:36.909  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:36.909  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.909  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.909  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 17:08:36.914  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138336  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 17:08:36.917  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.917  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.918  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 17:08:36.918  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:36.919  1070  1070 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 17:08:36.919  7952  7952 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 17:08:36.919  7952  7952 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:08:36.919  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:36.919  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:36.919  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 17:08:36.919  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:36.919  1070  8010 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:36.919  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 17:08:36.919  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:08:36.919  1070  8010 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:08:36.920  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:36.920  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:36.921  1070  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138342  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:08:36.922  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138344  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:08:36.922  1070  1437 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138344
08-30 17:08:36.923  1070  1437 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138345
08-30 17:08:36.923  1070  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 17:08:36.924  8041  8041 D PluginManager: init()
08-30 17:08:36.924  1070  8010 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:08:36.924  1070  8010 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:08:36.925  1070  1437 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-30 17:08:36.927  1070  1437 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 17:08:36.932  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:36.932  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:36.933  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:36.935  1070  1437 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 17:08:36.935  1070  1437 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 17:08:36.938  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.938  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.938  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 17:08:36.941  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.942  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:36.942  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 17:08:36.949  1070  1437 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-30 17:08:36.950  1070  1527 D ConnectivityService: Got NetworkAgent Messenger
08-30 17:08:36.950  1070  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:36.950  1070  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:08:36.950  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 17:08:36.950  1070  1527 D ConnectivityService: NetworkAgent connected
08-30 17:08:36.950  1070  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:08:36.950  1070  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:08:36.954  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:36.955  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:36.956  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:36.958  1070  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:08:36.958  1070  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:36.958  1070  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:08:36.958  1070  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:08:36.958  1070  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:08:36.958  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:36.958  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:36.960  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:36.965  1070  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 17:08:36.968   308   917 D CommandListener: Setting iface cfg
08-30 17:08:36.971  1070  1437 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 17:08:36.971  1070  8074 D DhcpStateMachine: StoppedState
08-30 17:08:36.971  1070  8074 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.971  1070  8074 D DhcpStateMachine: WaitBeforeStartState
08-30 17:08:36.971  1070  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138393  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:36.972  1070  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138393  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:36.972  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:36.973  1070  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138395  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:36.973  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:36.973  1070  1070 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 17:08:36.973  1070  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138395  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:36.974  1070  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:08:36.975  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14166] from screen [on:0 period:-604065553] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:08:36.976  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-604065552] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:08:36.976  1070  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 17:08:36.980  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:08:36.983  1070  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-30 17:08:36.983  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 17:08:36.984  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.984  1070  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.985  1070  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.986  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.986  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.987  1070  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 17:08:36.987  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
08-30 17:08:36.987  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
08-30 17:08:36.987  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 17:08:36.988  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 17:08:36.988  1070  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 17:08:36.988  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 17:08:36.989  1070  1437 D WifiNative-wlan0: SET ps 0: returned true
08-30 17:08:36.989  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 17:08:36.989  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 17:08:36.989  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 17:08:36.989  1070  1437 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 17:08:36.989  1070  1437 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:08:36.989  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d240b23 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.990  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d240b23 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.990  1070  8074 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.990  1070  8074 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 17:08:36.990  1070  1437 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:08:36.991   308   917 D CommandListener: Setting iface cfg
08-30 17:08:36.991   308   917 D CommandListener: Trying to bring up wlan0
08-30 17:08:36.992  1070  1437 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-30 17:08:36.994  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:36.994  1070  1070 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 17:08:36.995  1070  1070 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:08:36.995  1070  1070 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 17:08:36.996  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.997  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.997  1070  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.997  1070  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.998  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.998  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:08:36.999  1070  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 17:08:36.999  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 17:08:36.999  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 17:08:36.999  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:08:36.999  1070  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:36.999  1070  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:37.000  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:08:37.000  1070  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:08:37.000  1070  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 17:08:37.000  7952  7952 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 17:08:37.001  1070  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 17:08:37.001  1070  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:08:37.020  1070  1437 D WifiNative-wlan0: SET ps 1: returned true
,08-30 17:08:37.021  1070  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 17:08:37.021  1070  1437 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 17:08:37.022  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 17:08:37.022  1070  1437 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 17:08:37.022  1070  1527 D ConnectivityService: ignoring duplicate network state non-change
08-30 17:08:37.026  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 17:08:37.026  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:08:37.027  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:37.027  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:37.027  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:08:37.029  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.031  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:37.031  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:37.031  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:08:37.032  1070  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 17:08:37.033  1070  1527 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 17:08:37.041  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 17:08:37.042  1070  1070 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 17:08:37.050  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:37.050  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 17:08:37.056  1070  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:08:37.056  1070  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 17:08:37.057  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.057  1070  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 17:08:37.058   308   917 E Netd    : netlink response contains error (File exists)
08-30 17:08:37.059  1070  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 17:08:37.059  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:37.059  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:08:37.060  1070  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 17:08:37.060  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.060  1070  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 17:08:37.060  1070  1527 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 17:08:37.061  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:37.061  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:37.061  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:08:37.062  1070  1437 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 17:08:37.075  1070  1070 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 17:08:37.077  1070  1070 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:37.077  1070  1070 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:37.077  1070  1070 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:08:37.078  1070  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-30 17:08:37.078  1070  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 17:08:37.078  1070  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 17:08:37.078  1070  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 17:08:37.078  1070  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:37.078  1070  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:37.078  1070  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 17:08:37.078  1070  8072 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:37.078  1070  8072 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 17:08:37.078  1070  8072 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:37.078  1070  8072 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 17:08:37.079  1070  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.079  1070  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 17:08:37.079  1070  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-30 17:08:37.079  1070  1527 D ConnectivityService:    accepting network in place of null
08-30 17:08:37.079  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:37.080  1070  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.080  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:08:37.080  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.080  1070  1437 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.080  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.080  1070  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:37.080  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:08:37.081  1070  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDn,Bandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 17:08:37.081  1070  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 17:08:37.081  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:37.081   308  8078 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 17:08:37.083  1070  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:37.083  1070  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 17:08:37.083  1070  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 17:08:37.084  1070  1527 D ConnectivityService: validation of new default Network = false
08-30 17:08:37.084  1070  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 17:08:37.084  1070  1527 D DSQN    : enableDataServiceNotify 
08-30 17:08:37.084  1070  1527 D DSQN    : start dsqn bin
08-30 17:08:37.085  1070  1070 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 17:08:37.085  1070  1070 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:08:37.085  1070  1070 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:08:37.085  1070  1070 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 17:08:37.092  1070  1376 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 17:08:37.092  1070  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 17:08:37.092  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.092  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:37.092  1070  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:37.093  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:08:37.086  8079  8079 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:37.086  8079  8079 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:37.107  8079  8079 E DSQN    : DSQN ssw
,08-30 17:08:37.112  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:08:37.112  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.113  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.192  1070  8074 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 17:08:37.193  1070  8074 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-30 17:08:37.193  1070  8074 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 17:08:37.186  8083  8083 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:37.186  8083  8083 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:08:37.213  8083  8083 I dhcpcd  : version 5.5.6 starting
08-30 17:08:37.215  8083  8083 E dhcpcd  : get_duid: m
08-30 17:08:37.215  8083  8083 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 17:08:37.215  8083  8083 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 17:08:37.290  8041  8041 W ExternalStrings: load override strings
08-30 17:08:37.290  8041  8041 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:08:37.290  8041  8041 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 17:08:37.293  8041  8041 D StatusProvider: onCreate
,08-30 17:08:37.305  8083  8083 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:08:37.305  8083  8083 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 17:08:37.305  8083  8083 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:08:37.306  8083  8083 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 17:08:37.306  8083  8083 D dhcpcd  : wlan0: sending REQUEST (xid 0x105677ce), next in 4.61 seconds
,08-30 17:08:37.331  8041  8041 V Signer  : override build config not found
,08-30 17:08:37.331  8041  8041 D Signer  : value of property debug is false
,08-30 17:08:37.367  8083  8083 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 17:08:37.371  6593  6694 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 853)
,08-30 17:08:37.372  6593  6694 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 853)
08-30 17:08:37.384  6593  6694 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
,08-30 17:08:37.386  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 17:08:37.387  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 17:08:37.388  6593  6694 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 17:08:37.388  6593  6694 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 859)
08-30 17:08:37.388  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 17:08:37.389  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 17:08:37.390  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 17:08:37.390  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 17:08:37.391  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 17:08:37.392  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 17:08:37.392  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 17:08:37.393  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 17:08:37.393  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 17:08:37.394  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 17:08:37.395  8041  8041 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 17:08:37.396  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.396  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd8f934 added. We now have 2 listener(s)
08-30 17:08:37.397  1070  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.399  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.400  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.400  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.400  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.400  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1988235d added. We now have 9 listener(s)
08-30 17:08:37.400  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.400  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:37.404  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:37.410  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:37.410   308  8078 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 17:08:37.412  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.412  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:37.412  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.412  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd289a3 added. We now have 3 listener(s)
08-30 17:08:37.413  1070  1086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.415  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:37.415  8083  8083 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 17:08:37.415  8083  8083 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 17:08:37.415  8083  8083 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 17:08:37.415  8083  8083 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 17:08:37.416  8083  8083 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:08:37.416  8083  8083 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:08:37.416  8083  8083 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 17:08:37.416  8083  8083 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 17:08:37.419  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:37.419  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.419  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.419  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.419  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.420  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32a674a0 added. We now have 10 listener(s)
08-30 17:08:37.420  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.420  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:37.420  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:37.420  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:37.420  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.420  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.420  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:37.420  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.420  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd8f934 removed from the list
08-30 17:08:37.420  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.420  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1988235d removed from the list
08-30 17:08:37.420  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:37.420  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.424  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.424  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release:, 1 listener(s) left
08-30 17:08:37.425  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.425  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.425  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.425  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1988235d not in the list
08-30 17:08:37.425  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.425  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.427  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.427  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.427  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.427  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32a674a0 removed from the list
08-30 17:08:37.427  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.427  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.427  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.427  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.427  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd289a3 removed from the list
08-30 17:08:37.428  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.428  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c289859 added. We now have 2 listener(s)
08-30 17:08:37.429  1070  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.432  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 17:08:37.432  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.432  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.432  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.432  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98a2c1e added. We now have 9 listener(s)
08-30 17:08:37.432  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.432  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-30 17:08:37.435  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:37.441  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:37.443  8041  8041 V LGMDMManager: Create singleton instance
08-30 17:08:37.443  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.444  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:37.444  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.444  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e3acc added. We now have 3 listener(s)
08-30 17:08:37.444  1070  1739 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.446  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:37.448  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:37.449  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.449  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.449  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.449  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.449  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c16115 added. We now have 10 listener(s)
08-30 17:08:37.449  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.449  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:37.449  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:37.449  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:37.449  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:37.449  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:37.455  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:08:37.455  1070  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:08:37.462  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:08:37.463  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:08:37.465  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:37.466  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:37.468  6593  6694 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:08:37.468  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:37.468  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:37.470  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:37.470  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:37.470  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:37.470  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.470  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.470  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:37.470  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:08:37.470  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c289859 removed from the list
08-30 17:08:37.470  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.470  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98a2c1e removed from the list
08-30 17:08:37.470  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:37.471  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.471  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.471  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.472  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.472  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.472  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.472  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98a2c1e not in the list
08-30 17:08:37.472  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.472  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.473  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.474  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:37.474  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:37.474  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.474  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.474  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c16115 removed from the list
08-30 17:08:37.474  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.474  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.474  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.474  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.474  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e3acc removed from the list
08-30 17:08:37.475  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.475  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224a37b8 added. We now have 2 listener(s)
08-30 17:08:37.475  1070  1745 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.478  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.478  6593  6694 D o,rg.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.478  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.478  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.478  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e3f991 added. We now have 9 listener(s)
08-30 17:08:37.478  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.479  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:08:37.481  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:37.486  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:37.487  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.487  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:37.489  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:37.491  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:37.491  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.492  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b40acf7 added. We now have 3 listener(s)
08-30 17:08:37.492  1070  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.494  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.495  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.495  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.495  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.495  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d471764 added. We now have 10 listener(s)
08-30 17:08:37.495  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.495  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:37.496  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:37.496  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:08:37.496  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 17:08:37.496  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:37.496  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:37.499  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:08:37.499  1070  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.503  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:08:37.504  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:08:37.506  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:37.506  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:37.508  6593  6694 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:08:37.508  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:37.508  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:37.508  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:37.509  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.509  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.509  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:37.509  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.509  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224a37b8 removed from the list
08-30 17:08:37.509  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.509  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e3f991 removed from the list
08-30 17:08:37.509  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:37.509  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.510  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.510  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.511  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.511  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.511  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.511  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e3f991 not in the list
08-30 17:08:37.511  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManage,r: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.511  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.512  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.512  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:37.512  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:37.513  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.513  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.513  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d471764 removed from the list
08-30 17:08:37.513  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.513  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.513  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.513  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.513  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b40acf7 removed from the list
08-30 17:08:37.513  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.514  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b492193 added. We now have 2 listener(s)
08-30 17:08:37.514  1070  1739 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.516  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.516  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.516  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.516  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.516  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11045d0 added. We now have 9 listener(s)
08-30 17:08:37.516  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:37.525  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:08:37.528  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:37.530  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:37.532  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.532  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:37.534  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:37.536  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:37.536  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.536  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b27d8ce added. We now have 3 listener(s)
08-30 17:08:37.536  1070  1086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.538  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 17:08:37.538  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.539  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.539  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.539  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@315a43ef added. We now have 10 listener(s)
08-30 17:08:37.539  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.539  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:37.539  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:37.539  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:37.539  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:37.539  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:37.542  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:08:37.542  1070  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.546  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:08:37.546  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:08:37.548  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:37.548  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:37.549  8041  8041 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-30 17:08:37.549  6593  6694 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:08:37.551  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:37.551  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:37.551  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:37.551  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.551  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.551  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:37.551  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.551  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b492193 removed from the list
08-30 17:08:37.551  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.552  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11045d0 removed from the list
08-30 17:08:37.552  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:37.552  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.552  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.552  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.553  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.553  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.553  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.553  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11045d0 not in the list
08-30 17:08:37.553  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.553  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.553  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.554  6593  6694 D BluetoothLeScanner: could not find callback wrapper
08-30 17:08:37.554  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:37.554  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.554  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.554  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@315a43ef removed from the list
08-30 17:08:37.554  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.554  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.554  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.554  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.554  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b27d8ce removed from the list
08-30 17:08:37.554  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.554  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16cb3da added. We now have 2 listener(s)
08-30 17:08:37.555  1070  1937 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.556  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.556  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.556  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.556  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.556  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb1300b added. We now have 9 listener(s)
08-30 17:08:37.556  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.557  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:37.559  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:37.561  6593  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:37.563  6593  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:37.563  6593  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:37.564  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:37.565  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:37.565  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e656901 added. We now have 3 listener(s)
08-30 17:08:37.565  1070  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:08:37.566  6593  6593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:37.568  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:08:37.568  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:37.568  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:37.568  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:37.568  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef233a6 added. We now have 10 listener(s)
08-30 17:08:37.569  6593  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:37.569  6593  6694 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:37.569  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:37.569  6593  6694 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:37.569  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.570  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.570  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:37.570  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.570  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16cb3da removed from the list
08-30 17:08:37.570  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.570  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb1300b removed from the list
08-30 17:08:37.570  6593  6694 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:37.570  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.570  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.570  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.571  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.571  6593  6694 I org.thaliproject.p2p.btconnecto,rlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.571  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.571  6593  6694 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb1300b not in the list
08-30 17:08:37.571  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.571  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:37.572   308  8078 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 17:08:37.575  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:37.575  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:37.575  6593  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:37.575  6593  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef233a6 removed from the list
08-30 17:08:37.575  6593  6694 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:37.575  6593  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:37.575  6593  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:37.575  6593  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:37.575  6593  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e656901 removed from the list
08-30 17:08:37.577  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 17:08:37.577  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 17:08:37.577  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 17:08:37.577  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:37.578  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 17:08:37.578  6593  6694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:37.587  6593  8114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: My test thread name)
,08-30 17:08:37.587  6593  8114 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 866, thread name: My test thread name)
08-30 17:08:37.588  6593  8114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 17:08:37.590  6593  8118 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: My test thread name)
08-30 17:08:37.590  6593  8118 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: My test thread name)
08-30 17:08:37.590  6593  8118 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 17:08:37.593  6593  6694 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 17:08:37.593  6593  6694 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 17:08:37.593  6593  6694 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 17:08:37.593  6593  6694 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 17:08:37.593  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.593  6593  6694 D com.test.thalitest.ThaliTestRunner: Total duration: 23166 ms
08-30 17:08:37.596  6593  6694 I jxcore-log: *Native tests were executed*
08-30 17:08:37.596  6593  6694 I jxcore-log: 
08-30 17:08:37.596  6593  6694 I jxcore-log: Total number of executed tests:  80
08-30 17:08:37.596  6593  6694 I jxcore-log: 
08-30 17:08:37.596  6593  6694 I jxcore-log: Number of passed tests:  80
08-30 17:08:37.596  6593  6694 I jxcore-log: 
08-30 17:08:37.597  6593  6694 I jxcore-log: Number of failed tests:  0
08-30 17:08:37.597  6593  6694 I jxcore-log: 
08-30 17:08:37.597  6593  6694 I jxcore-log: Number of ignored tests:  0
08-30 17:08:37.597  6593  6694 I jxcore-log: 
08-30 17:08:37.598  6593  6694 I jxcore-log: Total duration:  23166
08-30 17:08:37.598  6593  6694 I jxcore-log: 
08-30 17:08:37.598  6593  6694 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 17:08:37.598  6593  6694 I jxcore-log: 
08-30 17:08:37.601  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.601  6593  6694 I jxcore-log: 
08-30 17:08:37.601  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 17:08:37.605  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:08:37.607  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.607  6593  6694 I jxcore-log: 
08-30 17:08:37.608  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.608  6593  6694 I jxcore-log: 
08-30 17:08:37.609  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.609  6593  6694 I jxcore-log: 
08-30 17:08:37.612  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.613  6593  6593 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:08:37.615  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.615  6593  6694 I jxcore-log: 
08-30 17:08:37.616  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:08:37.616  6593  6694 I jxcore-log: 
08-30 17:08:37.618  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:37.618  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.618  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.618  6593  6694 I jxcore-log: 
08-30 17:08:37.619  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 17:08:37.621  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.621  6593  6694 I jxcore-log: 
08-30 17:08:37.622  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:37.622  6593  6694 I jxcore-log: 
08-30 17:08:37.622  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 17:08:37.623  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:08:37.623  6593  6694 I jxcore-log: 
,08-30 17:08:37.623  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:08:37.623  6593  6694 I jxcore-log: 
08-30 17:08:37.624  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.624  6593  6694 I jxcore-log: 
08-30 17:08:37.624  6805  6805 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 17:08:37.625  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.625  6593  6694 I jxcore-log: 
08-30 17:08:37.626  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.626  6593  6694 I jxcore-log: 
08-30 17:08:37.626  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.626  6593  6694 I jxcore-log: 
08-30 17:08:37.627  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.627  6593  6694 I jxcore-log: 
08-30 17:08:37.627  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.627  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.627  6593  6694 I jxcore-log: 
08-30 17:08:37.627  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.628  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.628  6593  6694 I jxcore-log: 
08-30 17:08:37.630  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:37.630  6593  6694 I jxcore-log: 
08-30 17:08:37.631  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:37.631  6593  6694 I jxcore-log: 
08-30 17:08:37.631  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:37.631  6593  6694 I jxcore-log: 
08-30 17:08:37.632  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.632  6593  6694 I jxcore-log: 
08-30 17:08:37.632  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:08:37.633  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.633  6593  6694 I jxcore-log: 
,08-30 17:08:37.634  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.634  6593  6694 I jxcore-log: 
08-30 17:08:37.636  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.636  6593  6694 I jxcore-log: 
08-30 17:08:37.636  6593  6694 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:37.636  6593  6694 I jxcore-log: 
08-30 17:08:37.639  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.643  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:08:37.644  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.644  6855  6855 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:08:37.647  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.647  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.651  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:37.657  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.661  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:37.662  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.662  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:37.664  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:37.664  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:08:37.664  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:08:37.664  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:08:37.664  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:08:37.665  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:08:37.665  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 17:08:37.665  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:08:37.665  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:08:37.665  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:08:37.666  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 17:08:37.666  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:08:37.712   308   916 D LGDataListener: argv[0]=dsqncommand
08-30 17:08:37.712   308   916 D LGDataListener: argv[1]=wlan0
08-30 17:08:37.712   308   916 D LGDataListener: argv[2]=1
08-30 17:08:37.712   308   916 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-30 17:08:37.715  1070  1246 D DSQN    : DSQM DsqnNotification wlan0  1
,08-30 17:08:37.715  1070  1246 D DSQN    : start to monitor internet connection
08-30 17:08:37.737  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.738  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.739  8041  8115 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 17:08:37.744  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:37.753  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.762  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:08:37.762  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.763  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:37.767  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.768  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.772  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:37.777  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.782  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:37.782  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.783  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:37.784  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.784  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 17:08:37.789  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:08:37.793  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.795  1070  8074 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 17:08:37.796  1070  8074 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 17:08:37.796  1070  8074 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:08:37.796  1070  8074 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 17:08:37.796  1070  8074 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 17:08:37.796  1070  8074 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:08:37.796  1070  8074 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 17:08:37.796  1070  8074 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-30 17:08:37.797  1070  8074 D DhcpStateMachine: RunningState
08-30 17:08:37.798  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:37.798  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.798  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:37.802  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.803  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.807  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:37.812  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.818  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:37.818  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.819  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:37.825  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.826  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:08:37.837  8126  8126 D AndroidRuntime: 
08-30 17:08:37.837  8126  8126 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:08:37.837  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:37.839  8126  8126 D AndroidRuntime: CheckJNI is OFF
08-30 17:08:37.844  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.850  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:08:37.851  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.854  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:08:37.862  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.863  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 17:08:37.868  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:08:37.874  1070  8072 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:08:37 GMT], X-Android-Received-Millis=[1472569717874], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472569717710]}
08-30 17:08:37.874  1070  8072 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 17:08:37.874  1070  8072 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 17:08:37.874  1070  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 17:08:37.874  1070  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 17:08:37.874  1070  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:37.874  1070  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:37.874  1070  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 17:08:37.874  1070  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 17:08:37.874  1070  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,08-30 17:08:37.874  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.874  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:37.875  1070  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:37.875  1070  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.875  1070  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 17:08:37.875  1070  1437 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.875  1070  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:37.876  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:08:37.876  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:37.876  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:08:37.879  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.885  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:37.886  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.886  6855  6855 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:08:37.891  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.891  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.894  7990  7990 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 17:08:37.898  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:37.899  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:37.906  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:08:37.907  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.908  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:08:37.910  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.915  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:08:37.915  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.916  6855  6855 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 17:08:37.916  6855  6855 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 17:08:37.917  6855  6855 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 17:08:37.922  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:08:37.922  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:37.925  7990  7990 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 17:08:37.926  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:08:37.927  8041  8115 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:37.927  8041  8115 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:08:37.928  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:08:37.932  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:08:37.938  6855  6855 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:08:37.939  6855  6855 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:08:37.939  6855  6855 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 17:08:37.940  6855  6855 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 17:08:37.940  6855  6855 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 17:08:37.941  8126  8126 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:08:37.943  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:37.944  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:37.947  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:37.947  1070  1173 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 17:08:37.948  1070  1173 I ActivityManager: Killing 6593:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 17:08:37.991  1070  1978 I WindowState: WIN DEATH: Window{2ad90106 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:08:37.992  1070  1525 D WifiService: Client connection lost with reason: 4
,08-30 17:08:37.999  1070  1978 D InputDispatcher: Window went away: Window{2ad90106 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:08:38.131  8041  8115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-30 17:08:38.166  1070  1173 I ActivityManager:   Force finishing activity ActivityRecord{2f770983 u0 com.test.thalitest/.MainActivity t6}
,08-30 17:08:38.218   344   357 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 17:08:38.232  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:38.239  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:38.239  1070  1560 W ActivityManager: Spurious death for ProcessRecord{57dd703 6593:com.test.thalitest/u0a118}, curProc for 6593: null
,08-30 17:08:38.240  1070  1259 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 17:08:38.242  1070  1259 I ActivityManager:   Force finishing activity ActivityRecord{2f770983 u0 com.test.thalitest/.MainActivity t6 f}
08-30 17:08:38.242  1070  1259 W ActivityManager: Duplicate finish request for ActivityRecord{2f770983 u0 com.test.thalitest/.MainActivity t6 f}
08-30 17:08:38.263  2016  2016 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 17:08:38.264  1924  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 17:08:38.264  1924  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18366142 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-30 17:08:38.265  2016  2016 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-30 17:08:38.268  1924  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 17:08:38.268  1924  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1bd5b553 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 17:08:38.270  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 17:08:38.288  1070  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 17:08:38.296  2496  2662 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 17:08:38.297  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 17:08:38.302  3806  3806 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 17:08:38.305  4486  4486 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 17:08:38.306  4486  4486 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 17:08:38.306  4486  4486 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 17:08:38.306  4486  4486 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 17:08:38.306  4486  4486 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:08:38.306  4486  4486 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:08:38.307  4486  4486 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:08:38.307  4486  4486 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:08:38.307  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:38.307  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:38.307  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:08:38.307  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:08:38.310  7611  7611 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 17:08:38.310  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 17:08:38.313  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 17:08:38.334  1070  1172 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 17:08:38.351  4607  4607 I art     : Explicit concurrent mark sweep GC freed 8232(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 894us total 81.450ms
,08-30 17:08:38.351  1070  1888 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:08:38.373  1070  1070 D administrator: Handling package changes for user 0
,08-30 17:08:38.376  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:38.377  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 17:08:38.377  2016  2123 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 17:08:38.387  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 17:08:38.391  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:38.397  1070  1173 I ActivityManager: Killing 7196:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 17:08:38.397  8041  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-30 17:08:38.425  8041  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-30 17:08:38.435  8041  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 17:08:38.436  8041  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 17:08:38.438  8041  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 17:08:38.438  8041  8115 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-30 17:08:38.447  8041  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 17:08:38.455  8041  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 17:08:38.459  1070  1597 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:08:38.459  1070  1597 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:08:38.469  1889  1889 D ActionManagerService: notifyUserLog: 1000003
08-30 17:08:38.469  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 17:08:38.469  3806  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 17:08:38.470  1070  2000 W libprocessgroup: failed to open /acct/uid_10005/pid_7196/cgroup.procs: No such file or directory
08-30 17:08:38.471  2016  2016 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 17:08:38.471  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:38.471  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 17:08:38.474  2016  2016 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 17:08:38.476  2016  2016 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-30 17:08:38.479  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-30 17:08:38.480  1889  1889 D ActionManagerService: notifyUserLog: 1000004
08-30 17:08:38.480  3806  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 17:08:38.482  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 17:08:38.484  1070  1070 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 17:08:38.484  1070  1070 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:08:38.484  1070  1070 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 17:08:38.484  3806  3821 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-30 17:08:38.485  1587  1629 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:08:38.485  1587  1629 D KeyguardModel: createShortcutInfo...
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , display: false
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , animation: false }
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , display: false
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , animation: false }
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , expire_time: 0
,08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , display: false
08-30 17:08:38.488  2016  2016 I GBoardWebViewUtils: , animation: false }
08-30 17:08:38.492  8041  8041 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-30 17:08:38.497  8041  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:08:38.501  2016  8161 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 17:08:38.505  1587  1629 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:08:38.505  1587  1629 D KeyguardModel: createShortcutInfo...
,08-30 17:08:38.508  1070  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 17:08:38.510  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 17:08:38.514  1070  1937 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:08:38.518  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 17:08:38.518  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-30 17:08:38.521  1587  1629 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 17:08:38.522  1587  1629 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:38.522  1587  1629 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 17:08:38.523  1587  1629 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:08:38.524  1587  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:38.524  1587  1629 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:08:38.524  1070  1560 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 17:08:38.525  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 17:08:38.525  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 17:08:38.525  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 17:08:38.525  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 17:08:38.525  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 17:08:38.525  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:08:38.525  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 17:08:38.526  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 17:08:38.526  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 17:08:38.526  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:08:38.526  7611  7611 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 17:08:38.528  1587  1629 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:08:38.528  1587  1629 D KeyguardModel: createShortcutInfo...
08-30 17:08:38.530  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 17:08:38.530  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 17:08:38.536  2160  2160 I ConfigService: onCreate
08-30 17:08:38.536  2160  2160 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 17:08:38.537  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 17:08:38.538  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-30 17:08:38.538  1854  1854 D SplitUIService: removed split : 
08-30 17:08:38.541  1587  1629 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 17:08:38.541  1587  1629 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:08:38.542  1587  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:38.543  1587  1629 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:08:38.544  1587  1629 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:08:38.544  1587  1629 D KeyguardModel: createShortcutInfo...
,08-30 17:08:38.546  2160  2160 I ConfigService: onBind returning update interface
08-30 17:08:38.548  2160  2160 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 17:08:38.548  2160  2160 I ConfigService: onBind returning config service
,08-30 17:08:38.554  1587  1629 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:38.554  1587  1629 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:08:38.554  1587  1629 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 17:08:38.554  1587  1629 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:08:38.557  1587  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:38.557  1587  1629 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 17:08:38.558  1587  1629 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:08:38.559  1587  1629 D KeyguardModel: createShortcutInfo...
08-30 17:08:38.565  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-30 17:08:38.565  1854  1854 I SplitUIService: split app #11
08-30 17:08:38.567  2160  2160 I ConfigService: onDestroy
08-30 17:08:38.569  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-30 17:08:38.569  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 17:08:38.571  1802  8165 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 17:08:38.587  1587  1629 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:08:38.587  1587  1629 D KeyguardModel: createShortcutInfo...
,08-30 17:08:38.589  1587  1629 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:08:38.589  1587  1629 D KeyguardModel: createShortcutInfo...
08-30 17:08:38.590  1587  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:38.590  1587  1629 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:08:38.591  1587  1629 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:08:38.591  1587  1629 D KeyguardModel: createShortcutInfo...
08-30 17:08:38.594  1587  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 17:08:38.594  1587  1629 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:08:38.596  1587  1629 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:08:38.596  1587  1629 D KeyguardModel: createShortcutInfo...
08-30 17:08:38.597  1587  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:38.597  1587  1629 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 17:08:38.601  5945  8170 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 17:08:38.603  2016  2016 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-30 17:08:38.603  1587  1629 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:08:38.603  1587  1629 D KeyguardModel: createShortcutInfo...
08-30 17:08:38.618  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-30 17:08:38.618  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 17:08:38.625  1802  8172 I PeopleContactsSync: CP2 sync disabled
08-30 17:08:38.625   338   414 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 17:08:38.626  3206  8173 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 17:08:38.634  1802  4794 I Icing   : doRemovePackageData com.test.thalitest
,08-30 17:08:38.646  1802  8171 W GmsApplication: Using Auth Proxy for data requests.
,08-30 17:08:38.651  1802  8171 W GmsApplication: Using Auth Proxy for data requests.
,08-30 17:08:38.669  6987  6987 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 17:08:38.683  2160  2758 I art     : Explicit concurrent mark sweep GC freed 7197(412KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 591us total 18.152ms
08-30 17:08:38.691  2315  8178 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 17:08:38.697  1070  1259 I art     : Explicit concurrent mark sweep GC freed 82600(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.884ms total 209.181ms
08-30 17:08:38.731  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 17:08:38.732  1070  2033 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8180 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 17:08:38.734  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:38.736  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 17:08:38.737  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 17:08:38.738  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 17:08:38.739  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 17:08:38.759  1070  1249 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6d885b5 u0 com.lge.launcher2/.Launcher t5} time:140194
08-30 17:08:38.760  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 17:08:38.761  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 17:08:38.768  2016  2219 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 17:08:38.768  2016  2219 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 17:08:38.776  8180  8180 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:38.776  8180  8180 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:08:38.776  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-30 17:08:38.777  8180  8180 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:08:38.777  8180  8180 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:08:38.777  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 17:08:38.777  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:38.786  2016  2016 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 17:08:38.787  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
08-30 17:08:38.787  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 17:08:38.788  2583  2583 D [Concierge]Service: Update widget ID : 11
08-30 17:08:38.789  2016  2016 D [Concierge]WidgetView: change position of spinner
,08-30 17:08:38.791  2016  2016 I [Concierge]WidgetView: initWebView(). Time : 1472569718791
08-30 17:08:38.791  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
08-30 17:08:38.801  2016  2016 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 526205978
08-30 17:08:38.801  2016  2016 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-30 17:08:38.802  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 17:08:38.804  2016  2016 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@333ab19a
08-30 17:08:38.804  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 17:08:38.806  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 17:08:38.806  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:38.811  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 17:08:38.811  2016  2016 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 17:08:38.812  2016  2016 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 17:08:38.812  2016  2016 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472569607817, New one : 1472569718791
08-30 17:08:38.812  2016  2016 D [Concierge]WidgetView: Unregister all receivers
08-30 17:08:38.812  2016  2016 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 17:08:38.813  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:38.816  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 17:08:38.817  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 17:08:38.818  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 17:08:38.819  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,08-30 17:08:38.820  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 17:08:38.823  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:38.824  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:38.825  8180  8180 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 17:08:38.828  8126  8126 D AndroidRuntime: Shutting down VM
08-30 17:08:38.841  8180  8180 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 17:08:38.851  1070  1172 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:38.855  1070  1172 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 17:08:38.861  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 17:08:38.863  8180  8180 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:38.869  2016  2016 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 17:08:38.870  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 17:08:38.873  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:08:38.876  1070  1437 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:08:38.876  1070  1259 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8201 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 17:08:38.876  1070  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:08:38.876  1070  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:08:38.876  1070  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:08:38.876  1070  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:08:38.877  1070  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:08:38.877  1070  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 17:08:38.877  1070  1527 D ConnectivityService: identical MTU - not setting
08-30 17:08:38.877  1070  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 17:08:38.877  1070  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 17:08:38.877  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:08:38.877  1070  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:08:38.877  1070  1527 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 17:08:38.880  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 17:08:38.892  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 17:08:38.896  2016  2016 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21f9ced7 time:140331
,08-30 17:08:38.907  8180  8180 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:08:38.908  8180  8180 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:08:38.924  1070  1739 I ActivityManager: Killing 7642:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 17:08:39.006  1070  1937 W libprocessgroup: failed to open /acct/uid_10072/pid_7642/cgroup.procs: No such file or directory
,08-30 17:08:39.018  2016  2016 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 17:08:39.031  8180  8180 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 17:08:39.042  1070  1969 I ActivityManager: Killing 7749:com.android.vending/u0a44 (adj 15): empty #17
08-30 17:08:39.058  2016  2923 I GBoardtInterface: onReloaded()
,08-30 17:08:39.060  2016  2016 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 17:08:39.076  1979  1979 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 17:08:39.076  1979  1979 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 17:08:39.076  1070  2000 W libprocessgroup: failed to open /acct/uid_10044/pid_7749/cgroup.procs: No such file or directory
08-30 17:08:39.078  1979  1979 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 17:08:39.078  3806  3821 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:08:39.080  3806  3822 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:08:39.085  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-30 17:08:39.087  3806  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 17:08:39.087  3806  4513 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-30 17:08:39.089  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-30 17:08:39.090  3806  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 17:08:39.090  3806  4513 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 17:08:39.090  3806  4513 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 17:08:39.090  3806  4513 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 17:08:39.091  3806  3821 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:08:39.092  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 17:08:39.092  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 17:08:39.094  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 17:08:39.094  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 17:08:39.096  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 17:08:39.096  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 17:08:39.104  8041  8041 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-30 17:08:39.111  7419  7419 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 17:08:39.113  6805  6805 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-30 17:08:39.119  6805  6805 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-30 17:08:39.120  6805  6805 D HideNavigationAppsReceiver: replacing : false
,08-30 17:08:39.122  6805  6805 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-30 17:08:39.124  6805  6805 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-30 17:08:39.124  6805  6805 D ButtonCombinationReceiver: replacing : false
08-30 17:08:39.144  1070  1759 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8225 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a

```
