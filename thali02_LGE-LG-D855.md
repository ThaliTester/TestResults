#### Test 82914073a7b15c1_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 18:39:47.214  6459  6459 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
08-29 18:39:47.220  6459  6459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-29 18:39:47.248  4643  6597 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 18:39:47.307  1033  1772 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6601 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 18:39:47.316  1033  1923 V SIM_STK : Menu title from STK is T-Mobile
08-29 18:39:47.421  1816  1834 I art     : Explicit concurrent mark sweep GC freed 27467(1749KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.079ms total 39.249ms
08-29 18:39:47.449  4643  6597 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 201 ms] updated apps [took 201 ms] 
08-29 18:39:47.547  6601  6601 D DocsApplication: Installing DEX configuration.
08-29 18:39:47.572  6601  6601 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 18:39:47.578  6601  6601 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{d8110ec com.google.android.apps.docs}
08-29 18:39:47.596  6601  6601 D TAG     : onCreate()
08-29 18:39:47.623  6601  6601 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 18:39:48.123   336   419 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-29 18:39:48.126  3227  6630 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 18:39:48.453  1816  4797 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-29 18:39:48.463  6631  6631 D AndroidRuntime: 
08-29 18:39:48.463  6631  6631 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 18:39:48.465  6631  6631 D AndroidRuntime: CheckJNI is OFF
08-29 18:39:48.556  1816  4797 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-29 18:39:48.578  6631  6631 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 18:39:48.584  1033  1953 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 18:39:48.599  1941  2957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 18:39:48.601  1033  1953 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 18:39:48.601  1033  1953 D ActivityManager: setTaskToReturnTo : TaskRecord{3307fabe #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 18:39:48.601  1033  1953 D ActivityManager: setTaskToReturnTo : TaskRecord{3307fabe #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 18:39:48.602  1033  1953 D WindowStateEx: AppWindowTokenEx init.. 
08-29 18:39:48.603   344   360 E GBMv2   : DFP En is all cleared set to be enabled
08-29 18:39:48.622  1033  1953 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6657 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 18:39:48.623  6631  6631 D AndroidRuntime: Shutting down VM
08-29 18:39:48.675  1816  4797 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-29 18:39:48.683  1941  2957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 18:39:48.683  1941  2957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{24f85628 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 18:39:48.685  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 18:39:48.685  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32ed0f41 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 18:39:48.731  6657  6657 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 18:39:48.783  6657  6657 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-29 18:39:48.789  6657  6657 I LibraryLoader: Loading: webviewchromium
08-29 18:39:48.792  6657  6657 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3656-3658)
08-29 18:39:48.792  6657  6657 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 18:39:48.803  6657  6657 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1038c616}
08-29 18:39:48.804  6657  6657 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 18:39:48.805  6657  6657 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 18:39:48.812  6657  6657 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 18:39:48.813  6657  6657 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 18:39:48.821  6657  6657 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 18:39:48.822  6657  6657 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 18:39:48.822  6657  6657 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 18:39:48.823   325  2163 V AudioPolicyService: registerClient() client 0xb558a500, uid 10118
08-29 18:39:48.826  1033  1095 D BluetoothManagerService: Message: 20
08-29 18:39:48.826  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30609158:true
08-29 18:39:48.839  6657  6657 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 18:39:48.839  6657  6657 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 18:39:48.839  6657  6657 I Adreno-EGL: Build Date: 12/12/14 금
08-29 18:39:48.839  6657  6657 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 18:39:48.839  6657  6657 I Adreno-EGL: Remote Branch: 
08-29 18:39:48.839  6657  6657 I Adreno-EGL: Local Patches: 
08-29 18:39:48.839  6657  6657 I Adreno-EGL: Reconstruct Branch: 
,08-29 18:39:48.897  6657  6692 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-29 18:39:48.897  6657  6657 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-29 18:39:48.908  6657  6657 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 18:39:48.910  6657  6657 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 18:39:48.913  6657  6657 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 18:39:48.915  6657  6657 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 18:39:48.915  6657  6657 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-29 18:39:48.925  6657  6657 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-29 18:39:48.932  6657  6657 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 18:39:48.932  6657  6657 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 18:39:48.950  6657  6704 D OpenGLRenderer: Render dirty regions requested: true
08-29 18:39:48.951  6657  6704 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 18:39:48.967  6657  6704 D OpenGLRenderer: Enabling debug mode 0
,08-29 18:39:48.979  6657  6657 D Atlas   : Validating map...
,08-29 18:39:48.984  1033  1953 D SplitWindow: check instance of lgWin Window{183cd8d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 18:39:49.031  6657  6702 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:39:49.031  6657  6702 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:39:49.121  1033  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +440ms (total +518ms)
08-29 18:39:49.121  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15bfd71f u0 com.test.thalitest/.MainActivity t6} time:103989
08-29 18:39:49.128  6657  6657 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39de7bdd time:103995
08-29 18:39:49.220  6601  6601 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:39:49.220  6601  6601 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:39:49.255  6657  6657 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 18:39:49.255  6657  6657 I chromium: 
,08-29 18:39:49.281  6657  6657 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 18:39:49.327  6657  6702 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 18:39:49.327  6657  6702 I chromium: 
,08-29 18:39:49.375  6161  6161 I LockScreenSettings: New app installed broadcast received ..
,08-29 18:39:49.379  6161  6161 I LockScreenSettings: Number of installed packages  1
08-29 18:39:49.381  6601  6601 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-29 18:39:49.420  1033  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-29 18:39:49.429  6657  6728 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
08-29 18:39:49.439  6657  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 18:39:49.439  6657  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 18:39:49.439  6657  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 18:39:49.439  6657  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 18:39:49.439  6657  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 18:39:49.439  6657  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@982ea11 added. We now have 1 listener(s)
,08-29 18:39:49.463  1033  2764 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6731 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 18:39:49.469  1033  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:39:49.471  6657  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 18:39:49.473  6657  6728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:39:49.475  6657  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 18:39:49.475  6657  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 18:39:49.485  6657  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec521e4 added. We now have 1 listener(s)
08-29 18:39:49.485  6657  6728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:49.489  1033  1402 D WifiService: New client listening to asynchronous messages
08-29 18:39:49.491  6657  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:39:49.492  6657  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 18:39:49.492  6657  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 18:39:49.492  6657  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 18:39:49.492  6657  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 18:39:49.494  6657  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:39:49.495  1033  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:39:49.495  6657  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 18:39:49.501  6657  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:49.502  6657  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:39:49.502  6657  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 18:39:49.502  6657  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:39:49.503  6657  6728 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 18:39:49.504  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:39:49.508  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:39:49.543  6731  6731 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 18:39:49.543  6731  6731 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 18:39:49.549  6657  6657 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-29 18:39:49.580  1033  1976 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6750 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 18:39:49.581  1033  1976 I ActivityManager: Killing 5496:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-29 18:39:49.692  1033  1994 W libprocessgroup: failed to open /acct/uid_10005/pid_5496/cgroup.procs: No such file or directory
08-29 18:39:49.759  6750  6750 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-29 18:39:49.783  6750  6750 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 18:39:49.786  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 18:39:49.845  1033  1648 I ActivityManager: Killing 5913:com.google.android.talk/u0a72 (adj 15): empty #17
,08-29 18:39:49.944  1033  1994 W libprocessgroup: failed to open /acct/uid_10072/pid_5913/cgroup.procs: No such file or directory
,08-29 18:39:50.007   344   362 E GBMv2   : DFP En is all cleared set to be enabled
08-29 18:39:50.008   344   362 E GBMv2   : Set value is all cleared set the max
08-29 18:39:50.008   344   362 I GBMv2   : DFP Enabled. Ignore VFP set
,08-29 18:39:50.448  6657  6749 W jxcore-log: Initializing JXcore engine
,08-29 18:39:50.448  6657  6749 W jxcore-log: JXcore engine is ready
,08-29 18:39:50.472  6749  6749 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9656]" dev="sockfs" ino=9656 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 18:39:50.472  6749  6749 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 18:39:50.472  6749  6749 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7902]" dev="sockfs" ino=7902 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-29 18:39:50.472  6749  6749 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 18:39:50.472  6749  6749 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30409]" dev="sockfs" ino=30409 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 18:39:50.500  6657  6749 W jxcore-log: Starting JXcore engine
,08-29 18:39:50.587  6657  6749 W jxcore-log: Platform android
08-29 18:39:50.587  6657  6749 W jxcore-log: 
08-29 18:39:50.587  6657  6749 W jxcore-log: Process ARCH arm
08-29 18:39:50.587  6657  6749 W jxcore-log: 
,08-29 18:39:50.881  6657  6749 I jxcore-log: JXcore Cordova bridge is ready!
08-29 18:39:50.881  6657  6749 I jxcore-log: 
,08-29 18:39:50.881  6657  6749 W jxcore-log: JXcore engine is started
,08-29 18:39:50.891  6657  6728 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 18:39:50.899  6657  6657 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 18:39:50.948  2800  2800 I MusicWidget: mDelayedStopHandler : unbind
,08-29 18:39:50.951  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 18:39:50.951  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 18:39:50.951  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 18:39:50.953  2168  2168 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 18:39:50.953  2168  2168 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 18:39:50.954  2168  2168 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 18:39:50.955  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 18:39:50.956  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 18:39:50.957  1033  1048 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@51c3887com.lge.music.MediaPlaybackService$5@5a763b4
08-29 18:39:50.958  2168  2168 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 18:39:50.958  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.959  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.959  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.960  2168  2168 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2cf32da2
08-29 18:39:50.960  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-29 18:39:50.961  2168  2168 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 18:39:50.961  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.964  2168  2168 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 18:39:50.964  2168  2168 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 18:39:50.965  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.966  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.966  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.967  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.968  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 18:39:50.969  2168  2168 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 18:39:50.971  2168  2168 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
,08-29 18:39:50.971  2168  2168 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 18:39:50.971  2168  2168 V MediaPlayer[Native]: reset
08-29 18:39:50.985  2168  2168 V MediaPlayer[Native]: setListener
08-29 18:39:50.985  2168  2168 V MediaPlayer[Native]: disconnect
08-29 18:39:50.985  2168  2168 V MediaPlayer[Native]: destructor
08-29 18:39:50.985   325  1400 V AudioFlinger: releasing 16 from 2168 for -1
08-29 18:39:50.985   325  1400 V AudioFlinger:  decremented refcount to 0
08-29 18:39:50.985   325  1400 V AudioFlinger: purging stale effects
08-29 18:39:50.985  2168  2168 V MediaPlayer[Native]: disconnect
08-29 18:39:50.986  2168  2168 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-29 18:39:50.987  2168  2168 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
,08-29 18:39:50.988  2168  2168 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 18:39:50.989  2168  2168 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 18:39:50.989  2168  2168 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
,08-29 18:39:50.990  2168  2168 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 18:39:50.990  2168  2168 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 970882013
08-29 18:39:50.990  2168  2168 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 970882013
,08-29 18:39:51.003  2168  2168 I SmartShareClient: [SmartShareManagerClient] terminate service: 2168/MediaPlaybackService/283398104
08-29 18:39:51.007  2168  2168 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 18:39:51.007  2168  2168 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@17664352
,08-29 18:39:51.014  2168  2168 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 18:39:51.014  2168  2168 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 18:39:51.015  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 18:39:51.015  2168  2168 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 18:39:51.016  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 30000
08-29 18:39:51.019  1033  1904 I ActivityManager: Killing 5671:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-29 18:39:51.037  5645  5645 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 18:39:51.037  5645  5645 W System.err: android.os.DeadObjectException
,08-29 18:39:51.038  5645  5645 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-29 18:39:51.038  5645  5645 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 18:39:51.038  5645  5645 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 18:39:51.038  5645  5645 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 18:39:51.038  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 18:39:51.038  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 18:39:51.038  5645  5645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 18:39:51.038  5645  5645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 18:39:51.039  5645  5645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 18:39:51.040  5645  5645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 18:39:51.040  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:51.040  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:51.040  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 18:39:51.040  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 18:39:51.040  5645  5645 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 18:39:51.041  5645  5645 W System.err: android.os.DeadObjectException
08-29 18:39:51.041  5645  5645 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 18:39:51.041  5645  5645 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 18:39:51.041  5645  5645 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 18:39:51.041  5645  5645 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 18:39:51.041  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 18:39:51.041  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 18:39:51.041  5645  5645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 18:39:51.041  5645  5645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 18:39:51.041  5645  5645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 18:39:51.041  5645  5645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 18:39:51.041  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-29 18:39:51.041  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:51.041  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 18:39:51.041  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 18:39:51.042  5645  5645 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 18:39:51.042  5645  5645 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 18:39:51.308  1033  2042 W libprocessgroup: failed to open /acct/uid_1000/pid_5671/cgroup.procs: No such file or directory
,08-29 18:39:51.309  1033  2042 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 18:39:51.321  5645  5645 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 18:39:51.321  5645  5645 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 18:39:51.366  1033  1772 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6781 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 18:39:51.397  5645  5645 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 18:39:51.433  6781  6781 D UEI.SmartControl: Quickset Services start...
08-29 18:39:51.435  6781  6781 I UEI.SmartControl: Manufacture = LGE
08-29 18:39:51.435  6781  6781 D UEI.SmartControl: Id = LGNevo
,08-29 18:39:51.440  6781  6781 D UEI.SmartControl: File observer start...
08-29 18:39:51.441  6781  6781 E UEI.SmartControl: IR Port is disabled: false
08-29 18:39:51.442  6781  6781 D UEI.SmartControl: Starting file observer...
08-29 18:39:51.442  6781  6781 D UEI.SmartControl: Extracting JNI libs...
08-29 18:39:51.442  6781  6781 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 18:39:51.545  6781  6781 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 18:39:51.545  6781  6781 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 18:39:51.545  6781  6781 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 18:39:51.574  6781  6781 I UEI.SmartControl: --- Selecting new region: 6
,08-29 18:39:51.576  6781  6781 I UEI.SmartControl: Model = LG-D855
,08-29 18:39:51.578  6781  6781 D UEI.SmartControl: QS Service created
08-29 18:39:51.589  6781  6781 I UEI.SmartControl: Service initServices...
,08-29 18:39:51.593  6781  6781 D UEI.SmartControl: QS start get config
,08-29 18:39:51.656  6781  6781 D UEI.SmartControl: Loading JNI Libs...
,08-29 18:39:51.907  6781  6781 I UEI.SmartControl: Supports setup maps: true
08-29 18:39:51.909  6781  6781 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 18:39:51.909  6781  6781 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 18:39:51.909  6781  6781 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 18:39:51.910  6781  6781 I UEI.SmartControl: ### init IR Blaster...
,08-29 18:39:51.914  6781  6781 D serial_port: Configuring serial port
08-29 18:39:51.919  6781  6781 E UEI.SmartControl: UEIBLaster setting for 616
08-29 18:39:51.919  6781  6781 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 18:39:51.920  6781  6781 I UEI.SmartControl: configuring settings for MAXQ616
08-29 18:39:51.920  6781  6781 I UEI.SmartControl: Get version...
08-29 18:39:51.937  6781  6814 D UEI.SmartControl: serial port data available: 21
,08-29 18:39:51.965  6781  6781 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 18:39:51.965  6781  6781 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 18:39:51.965  6781  6781 I UEI.SmartControl: QS saving settings...
08-29 18:39:51.967  6781  6781 D UEI.SmartControl: IR Blaster version: 25672567
08-29 18:39:51.984  6781  6814 D UEI.SmartControl: serial port data available: 4
,08-29 18:39:52.021  6781  6817 I UEI.SmartControl: Device manager: loading config....
,08-29 18:39:52.029  6781  6781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 18:39:52.030  6781  6817 D UEI.SmartControl: ----------- loading internal config...
,08-29 18:39:52.033  6781  6781 E UEI.SmartControl: Services init done
08-29 18:39:52.033  6781  6781 D UEI.SmartControl: QS Service init finished
,08-29 18:39:52.036  6781  6781 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 18:39:52.036  6781  6781 D UEI.SmartControl: QS Service version code: 201091
08-29 18:39:52.037  6781  6781 D UEI.SmartControl: Service requested: Control
08-29 18:39:52.042  6781  6817 E UEI.SmartControl: Loading SETTINGS...
08-29 18:39:52.044  6781  6781 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 18:39:52.045  1033  1648 I ActivityManager: Killing 5645:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 18:39:52.048  6781  6817 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 18:39:52.058  6781  6816 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 18:39:52.058  6781  6816 D UEI.SmartControl: -----service ready thread exits
08-29 18:39:52.165  1033  2013 W libprocessgroup: failed to open /acct/uid_10112/pid_5645/cgroup.procs: No such file or directory
08-29 18:39:52.166  6781  6781 D UEI.SmartControl: Internal service binding...
,08-29 18:39:53.317  6601  6601 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 18:39:53.318  1033  1729 I ActivityManager: Killing 6281:com.android.calendar/u0a13 (adj 15): empty #17
,08-29 18:39:53.393  1033  1994 W libprocessgroup: failed to open /acct/uid_10013/pid_6281/cgroup.procs: No such file or directory
,08-29 18:39:54.304  6601  6715 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 18:39:57.028  6781  6818 D UEI.SmartControl: Internal timer expired: 1
,08-29 18:39:57.028  6781  6818 D UEI.SmartControl: unbind internal service
,08-29 18:39:57.032  6781  6781 D UEI.SmartControl: Service.onUnbind: IControl
,08-29 18:39:57.032  6781  6781 D UEI.SmartControl: Service.onDestroy
,08-29 18:39:57.032  6781  6781 D UEI.SmartControl: Lock is in USE false
08-29 18:39:57.032  6781  6781 D UEI.SmartControl: unbind internal service
,08-29 18:39:57.032  6781  6781 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2cf32da2
,08-29 18:39:57.040  6781  6781 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 18:39:57.040  6781  6781 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 18:39:57.040  6781  6781 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-29 18:39:57.040  6781  6781 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-29 18:39:57.040  6781  6781 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 18:39:57.040  6781  6781 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 18:39:57.040  6781  6781 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 18:39:57.040  6781  6781 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-29 18:39:57.041  6781  6781 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-29 18:39:57.041  6781  6781 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 18:39:57.041  6781  6781 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 18:39:57.041  6781  6781 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-29 18:39:57.041  6781  6781 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:57.041  6781  6781 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 18:39:57.041  6781  6781 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 18:39:57.041  6781  6781 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2cf32da2
08-29 18:39:57.042  6781  6781 D serial_port: close(fd = 25)
08-29 18:39:57.049  6781  6781 I UEI.SmartControl: Serial port is closed.
,08-29 18:39:57.056  6781  6781 I UEI.SmartControl: Serial port is closed.
08-29 18:39:57.056  6781  6781 D UEI.SmartControl: Blaster closed
08-29 18:39:57.056  6781  6781 D UEI.SmartControl: Shut down QS...
08-29 18:39:57.056  6781  6781 D UEI.SmartControl: Stopping QS lib
08-29 18:39:57.056  6781  6781 D UEI.SmartControl: QS lib stop result = true
08-29 18:39:57.056  6781  6781 D UEI.SmartControl: Stopped QS lib
08-29 18:39:57.057  6781  6781 D UEI.SmartControl: Stopped file observer...
08-29 18:39:57.057  6781  6781 D UEI.SmartControl: QS shutdown complete
,08-29 18:40:00.001  1033  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1025899777, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-29 18:40:00.041  2584  2584 D [Concierge]Service: onStartCommand(). Type : 9
,08-29 18:40:00.049  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-29 18:40:00.049  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 18:40:00.049  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 18:40:00.049  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
08-29 18:40:00.050  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 18:40:00.051  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-29 18:40:00.051  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
,08-29 18:40:00.062  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-29 18:40:00.103  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1025899777 [*alarm*], flags=0x0
,08-29 18:40:00.122  4528  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-29 18:40:01.023  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19993
,08-29 18:40:01.622  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 18:40:01.622  6657  6749 I jxcore-log: 
,08-29 18:40:01.625  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 18:40:01.625  6657  6749 I jxcore-log: 
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:01.631  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:01.633  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:01.636  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 18:40:01.636  6657  6749 I jxcore-log: 
08-29 18:40:01.638  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 18:40:01.638  6657  6749 I jxcore-log: 
08-29 18:40:01.676  1033  1091 I ActivityManager: Waited long enough for: ServiceRecord{1de0e59d u0 com.google.android.gms/.wearable.service.WearableService}
,08-29 18:40:02.143  6657  6749 D executeNativeTests: Running unit tests
,08-29 18:40:02.223  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:02.223  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 added. We now have 2 listener(s)
08-29 18:40:02.224  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:02.226  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:02.226  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:02.226  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:02.226  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:02.226  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 added. We now have 2 listener(s)
08-29 18:40:02.226  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:02.228  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:02.231  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:02.235  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:02.237  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.237  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:02.238  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.239  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:02.242  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 18:40:02.244  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:40:02.244  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 18:40:02.246  6657  6749 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 18:40:02.246  6657  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 18:40:02.247  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 18:40:02.247  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:40:02.247  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:40:02.247  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.248  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.248  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.248  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.248  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.249  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:02.249  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 18:40:02.249  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 removed from the list,
08-29 18:40:02.249  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.249  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 removed from the list,
,08-29 18:40:02.249  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.249  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:02.249  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 18:40:02.249  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:02.250  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.250  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 18:40:02.250  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:02.250  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.251  6657  6749 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
08-29 18:40:02.251  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.251  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-29 18:40:02.251  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:02.252  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.252  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:02.252  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.252  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
,08-29 18:40:02.252  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 18:40:02.252  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
,08-29 18:40:02.252  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.252  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:02.252  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:02.252  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.252  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.253  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.253  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:40:02.253  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.253  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 18:40:02.257  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 18:40:02.258  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 18:40:02.258  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 18:40:02.258  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 18:40:02.258  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:02.258  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.258  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.258  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.258  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.259  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.259  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.259  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:02.259  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.259  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.259  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.259  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.259  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.259  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.259  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:02.260  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.260  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.260  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.260  6657  6749 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 18:40:02.264  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:02.266  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:02.267  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:02.267  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:02.268  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.269  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.270  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:02.270  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:02.270  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 18:40:02.270  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.270  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:02.273  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:40:02.273  1033  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:02.277  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 18:40:02.280  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:02.282  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-29 18:40:02.283  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-29 18:40:02.283  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:02.284  6657  6749 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 18:40:02.285  6657  6749 I io.jxcore.node.ConnectionHelper: start: OK,
08-29 18:40:02.287  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.287  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.287  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.287  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.287  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.287  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:02.287  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
,08-29 18:40:02.287  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.287  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.287  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.287  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.288  6657  6749 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 18:40:02.289  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:02.291  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:02.292  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.292  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:02.293  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:02.293  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 18:40:02.293  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:02.293  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.293  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:02.294  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:02.296  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 18:40:02.298  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:02.298  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:02.299  6657  6749 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 18:40:02.299  6657  6749 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 18:40:02.300  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.300  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.300  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.300  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.300  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.300  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:02.300  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.300  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.300  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.300  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.301  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.301  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.301  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:02.301  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.301  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.303  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.303  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.303  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:02.303  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.303  6657  6749 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 18:40:02.305  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:02.306  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:02.308  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:02.308  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:02.309  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.309  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:02.309  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:02.309  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 18:40:02.309  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.309  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:02.310  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.312  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:02.312  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:02.313  6657  6749 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 18:40:02.313  6657  6749 I io.jxcore.node.ConnectionHelper: start: OK
08-29 18:40:02.313  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.313  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.313  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-29 18:40:02.314  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.314  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.314  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.314  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.314  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:02.314  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:02.314  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.314  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.314  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.314  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.314  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.314  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.315  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.315  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:02.315  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.315  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.315  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.315  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:02.315  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.316  6657  6749 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 18:40:02.316  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.316  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.316  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-29 18:40:02.316  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.316  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.316  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.316  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
,08-29 18:40:02.316  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.316  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.316  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.316  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.316  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.316  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.316  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:02.317  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-29 18:40:02.317  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.318  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.318  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.318  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:02.318  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.319  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 18:40:02.319  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.319  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.319  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:02.319  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.319  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.319  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.320  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.320  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:02.320  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.320  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.320  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.320  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.320  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 18:40:02.320  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.320  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.320  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.321  6657  6749 D BluetoothLeScanner: could not find callback wrapper
,08-29 18:40:02.321  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.321  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.321  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.321  6657  6749 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 18:40:02.321  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.321  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.321  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.322  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:02.322  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.322  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.322  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.322  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:02.322  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.322  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.322  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.322  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.322  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.322  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.323  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.323  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 18:40:02.323  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.323  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.323  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.323  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
,08-29 18:40:02.323  6657  6749 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
,08-29 18:40:02.323  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.324  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.324  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.324  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.324  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.324  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.324  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.324  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.324  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.324  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.324  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.324  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.324  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.324  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.325  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.325  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.325  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.325  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.325  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.325  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.325  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 18:40:02.326  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:40:02.326  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 18:40:02.327  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:40:02.327  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 18:40:02.327  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:40:02.327  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.327  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discove,ring: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.327  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.327  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.327  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.327  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.327  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.327  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.327  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.327  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.327  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.327  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.327  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.327  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.328  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.328  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.328  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.328  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.328  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.328  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.329  6657  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:02.329  6657  6749 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 18:40:02.329  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 18:40:02.331  6657  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:02.331  6657  6749 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 18:40:02.331  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 18:40:02.332  6657  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 18:40:02.332  6657  6749 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:40:02.332  6657  6749 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 18:40:02.332  6657  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:02.332  6657  6749 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:40:02.332  6657  6749 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 18:40:02.332  6657  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:02.332  6657  6749 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:40:02.332  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 18:40:02.336  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 18:40:02.337  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 18:40:02.337  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 18:40:02.337  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 18:40:02.337  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 18:40:02.337  6657  6749 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 18:40:02.337  6657  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:02.337  6657  6749 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 18:40:02.338  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.338  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.338  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.339  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.339  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.339  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.339  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 18:40:02.343  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.343  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.343  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.343  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.343  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.343  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.343  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.343  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.344  6657  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-29 18:40:02.347  6657  6875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-29 18:40:02.348  6657  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-29 18:40:02.348  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.349  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.349  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.349  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.349  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.349  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.350  6657  6749 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 18:40:02.350  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.350  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.350  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.350  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.350  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.350  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.351  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.351  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.351  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.351  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.351  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.351  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.351  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.351  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.352  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.352  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.352  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.352  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.352  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.352  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.353  6657  6749 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 18:40:02.353  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.353  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.353  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.353  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.353  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.353  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.353  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.353  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.354  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.354  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.354  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.354  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.354  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.354  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.354  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.354  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.355  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.355  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.355  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.355  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.355  6657  6749 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 18:40:02.355  6657  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 18:40:02.356  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:40:02.356  6657  6749 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 18:40:02.356  6657  6749 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 18:40:02.356  6657  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 18:40:02.356  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:40:02.356  6657  6749 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 18:40:02.356  6657  6749 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 18:40:02.356  6657  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 18:40:02.356  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:40:02.356  6657  6749 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 18:40:02.356  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.356  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.356  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.357  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.357  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.357  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.357  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.357  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.357  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.357  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.357  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.357  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.357  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.357  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.358  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.358  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.358  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.358  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.358  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.358  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.359  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.359  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.359  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.359  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.359  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.359  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.359  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.359  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.359  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.359  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.359  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.359  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.359  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.359  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.359  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.359  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.359  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.359  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.359  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.359  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.359  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.359  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.359  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.359  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.359  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.359  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.359  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.359  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.359  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.361  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.361  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.361  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.361  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.361  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.361  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.362  6657  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 18:40:02.362  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.363  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 18:40:02.363  6657  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 18:40:02.363  6657  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 18:40:02.364  6657  6657 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 18:40:02.364  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 18:40:02.364  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 18:40:02.365  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.365  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 18:40:02.365  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 18:40:02.365  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 18:40:02.365  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.365  6657  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 18:40:02.366  6657  6657 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 18:40:02.366  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.366  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.366  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:40:02.366  6657  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:02.366  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:02.367  6657  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 18:40:02.367  6657  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 18:40:02.368  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:40:02.370  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:02.370  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:02.370  6657  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:02.370  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.370  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.371  6657  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:02.371  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.371  6657  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:02.371  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.371  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.371  6657  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 18:40:02.371  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.371  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.371  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.371  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.371  6657  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:02.371  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.371  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.371  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.371  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.371  6657  6657 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:02.371  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.371  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.371  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.371  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.372  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.372  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.372  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.372  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.373  6657  6749 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 18:40:02.373  6657  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 18:40:02.373  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 18:40:02.374  6657  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:40:02.374  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.374  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.374  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.374  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.374  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.374  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.374  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.374  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.374  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.374  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.374  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.374  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.374  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.374  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.375  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.375  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.375  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.375  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.376  1033  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:02.379  1033  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:02.380  1033  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:02.381  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.381  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.381  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.381  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.381  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.381  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.382  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.382  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.382  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.382  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.382  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.382  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.382  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.382  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.383  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.383  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.383  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.383  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.384  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:02.384  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:02.384  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:02.385  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:02.385  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.385  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.385  6657  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27459aa1 not in the list
08-29 18:40:02.385  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.385  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.385  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:02.385  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.385  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.385  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:02.385  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:02.386  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:02.386  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:02.386  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:02.386  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274614c6 not in the list
08-29 18:40:02.388  6657  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 18:40:02.388  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:40:02.388  6657  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 18:40:02.388  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:40:02.388  6657  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 18:40:02.388  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:40:02.391  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 18:40:02.391  6657  6749 D io.jxco,re.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 18:40:02.392  6657  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 18:40:02.392  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 18:40:02.392  6657  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 18:40:02.392  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 18:40:02.392  6657  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 18:40:02.392  6657  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 18:40:02.394  6657  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 18:40:02.394  6657  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 18:40:02.394  6657  6749 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 18:40:02.394  6657  6749 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 18:40:02.394  6657  6749 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 18:40:02.394  6657  6749 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 18:40:02.395  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:02.395  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c7d557f added. We now have 2 listener(s)
08-29 18:40:02.395  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:02.396  6657  6749 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 18:40:02.398  1033  1923 D WifiServiceImplEx: setWifiEnabled: true pid=6657, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 18:40:02.398  1033  1923 D WifiService: setWifiEnabled: true pid=6657, uid=10118
08-29 18:40:02.398  1033  1923 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 18:40:02.400  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:02.400  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a4494c added. We now have 3 listener(s)
08-29 18:40:02.401  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:02.405  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:02.405  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11108d95 added. We now have 4 listener(s)
08-29 18:40:02.405  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:02.408  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:02.408  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@256ddeaa added. We now have 5 listener(s)
08-29 18:40:02.408  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:02.410  1033  1923 D WifiServiceImplEx: setWifiEnabled: false pid=6657, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 18:40:02.410  1033  1923 D WifiService: setWifiEnabled: false pid=6657, uid=10118
08-29 18:40:02.410  1033  1923 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 18:40:02.430  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:02.431  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:02.431  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 18:40:02.431  1033  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:02.431  1033  1904 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@88fd973 mBinding = false
08-29 18:40:02.432  1033  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:02.432  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:02.432  1033  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:02.433  1033  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:02.433  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:02.434  1033  1390 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 18:40:02.434  1033  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:02.434  1033  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 18:40:02.435  1033  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 18:40:02.435  1033  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 18:40:02.443  1033  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 18:40:02.443  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 18:40:02.443  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.444  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.444  2725  2725 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-29 18:40:02.444  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 18:40:02.444  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 18:40:02.446  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:02.446  1033  2868 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.447  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:02.447  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:02.447  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 18:40:02.448  1033  1095 D BluetoothManagerService: Message: 2
08-29 18:40:02.448   321   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:02.450  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:02.451  1033  1095 D BluetoothManagerService: Sending off request.
08-29 18:40:02.452  3891  4019 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:02.452  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:02.456  3891  3984 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 18:40:02.456  3891  3984 D BluetoothAdapterProperties: Setting state to 13
08-29 18:40:02.456  3891  3984 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 18:40:02.462  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.462  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:02.463  3891  3984 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 18:40:02.463  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:02.463  3891  3984 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 18:40:02.463  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 18:40:02.463  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 18:40:02.466  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:02.466  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:02.468  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.468  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:02.470  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.488  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 18:40:02.488  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-29 18:40:02.548  1033  1409 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 18:40:02.548  1033  1409 D DSQN    : disableDataServiceNotify
08-29 18:40:02.548  1033  1409 D DSQN    : stop dsqn bin
,08-29 18:40:02.561  1033  1409 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 18:40:02.562  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:02.562  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:02.562  1033  1409 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:02.562  1033  1409 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 18:40:02.563  1601  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-29 18:40:02.563  1033  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.563  1033  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.563  1033  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 18:40:02.565  1033  1409 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 18:40:02.565  1033  1409 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 18:40:02.565  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:40:02.586  1033  1377 I art     : Explicit concurrent mark sweep GC freed 27308(1447KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.865ms total 127.802ms
,08-29 18:40:02.589  3891  3989 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:02.589  3891  3984 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 18:40:02.589  1033  1377 V AlarmManager: RTC_WAKEUP set : Alarm{1f6cbf5c type 0 when 1472488802229 com.android.vending} when 1472488802229
08-29 18:40:02.590  1033  1409 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:02.590  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:40:02.590  3891  4207 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:02.590  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 18:40:02.590  3891  4228 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:02.590  3891  4098 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 18:40:02.590  3891  4203 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 18:40:02.591  1033  1409 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:02.591  3891  3984 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 18:40:02.591  1033  1409 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:02.591  1033  1409 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:02.592  3891  4232 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:02.592  3891  4230 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:02.593  3891  4098 W bt-l2cap,: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 18:40:02.593  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 18:40:02.593  3891  4098 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 18:40:02.594  3891  3891 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:02.594  3891  3891 D BluetoothMapService: STATE_TURNING_OFF
08-29 18:40:02.594  1033  1409 D NetworkManagementService: Removing idletimer
08-29 18:40:02.594  3891  3891 V BtOppService: Receiver DISABLED_ACTION 
08-29 18:40:02.594  3891  3891 V BluetoothMapService: Handler(): got msg=4
08-29 18:40:02.594  3891  3891 D BluetoothMapService: MAP Service closeService in
08-29 18:40:02.594  3891  3891 D BluetoothMapMasInstance: MAP Service shutdown
08-29 18:40:02.594  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 18:40:02.594  3891  3891 V BluetoothMapService: MAP Service closeService out
08-29 18:40:02.594  3891  3891 I BtOppRfcommListener: stopping Accept Thread
08-29 18:40:02.594  3891  3891 V BtOppRfcommListener: close mBtServerSocket
08-29 18:40:02.594  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:02.594  3891  3891 V BtOppRfcommListener: waiting for thread to terminate
08-29 18:40:02.594  3891  4228 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 18:40:02.595  3891  3891 V BtOppRfcommListener: done waiting for thread to terminate
08-29 18:40:02.595  1033  1409 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:02.595  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 18:40:02.596  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:02.596  1033  1409 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 18:40:02.598  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 18:40:02.606  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:02.606  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:02.606  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.606  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:02.608  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:02.608  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:02.608  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.608  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:02.647  1033  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6895 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 18:40:02.650  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 18:40:02.651  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:02.651  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:02.651  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 18:40:02.651  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 18:40:02.651  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 18:40:02.651  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 18:40:02.651  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-29 18:40:02.651  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 18:40:02.651  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 18:40:02.651  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 18:40:02.651  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 18:40:02.652  1033  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 18:40:02.652  1033  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 18:40:02.652  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 18:40:02.657  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.658  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.664  1033  2868 D DhcpStateMachine: StoppedState
,08-29 18:40:02.666  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:02.667  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:02.667  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.691  1033  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6913 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 18:40:02.696  1033  2764 V SIM_STK : Menu title from STK is T-Mobile
08-29 18:40:02.699  3891  3891 V BtOppService: onDestroy
08-29 18:40:02.700  3891  3891 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 18:40:02.700  1033  1390 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 18:40:02.701  1033  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.701  1033  1389 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.701  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.701  1033  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@eac20a4
08-29 18:40:02.702  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 18:40:02.702  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 18:40:02.702  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.703  1033  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.703  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.703  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.704  1033  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.704  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:02.704  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:02.704  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 18:40:02.705  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 18:40:02.705  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-29 18:40:02.705  1033  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.705  1033  1389 D LGWifiP2pService: P2pDisablingState
08-29 18:40:02.705  1033  1389 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.705  1033  1389 D LGWifiP2pService: p2p socket connection lost
08-29 18:40:02.705  1033  1389 D LGWifiP2pService: P2pDisabledState
08-29 18:40:02.706  1033  1555 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 18:40:02.706  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.706  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:02.706  1033  1390 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:02.707  1033  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:02.707  1033  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 18:40:02.708  1033  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.708  1033  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.708  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 18:40:02.708  1941  1941 D WfdsService: WifiP2pState is changed : false
08-29 18:40:02.708  1941  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 18:40:02.708  1941  2296 D WfdsService: Set the WFDS Monitor: false
08-29 18:40:02.709  1941  2296 D WfdsMonitor: WFDS Monitor is stopped
08-29 18:40:02.709  1941  2296 D WfdsService: STATE : WfdsDisabledState - enter
08-29 18:40:02.709  1941  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 18:40:02.709  1941  2760 D CtrlSupplicant: Received on exit socket, terminate
08-29 18:40:02.710  1941  2760 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 18:40:02.710  1941  2760 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 18:40:02.710  1941  2760 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 18:40:02.710  1941  2296 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 18:40:02.710  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 18:40:02.710  2725  2725 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 18:40:02.710  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 18:40:02.710  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 18:40:02.711  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:02.711  1033  2868 D DhcpStateMachine: StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:02.712   321   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:02.714  1033  1390 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 18:40:02.714  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 18:40:02.714  1033  1390 D WifiNative-p2p0: TERMINATE: returned true
08-29 18:40:02.714  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:02.714  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:02.714  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 18:40:02.716  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:02.716  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:02.716  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-29 18:40:02.718  1033  1390 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 18:40:02.719  1033  1390 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 18:40:02.721  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 18:40:02.721  6895  6895 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:40:02.721  6895  6895 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 18:40:02.722  6895  6895 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 18:40:02.722  6895  6895 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 18:40:02.723  6895  6895 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 18:40:02.723  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 18:40:02.724  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:02.724  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 18:40:02.724  6895  6895 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 18:40:02.725  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:02.725  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:02.726  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.726  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:02.733  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:02.733  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:02.733  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:02.733  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:02.736  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 18:40:02.736  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.737  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.754  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 18:40:02.755  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.755  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 18:40:02.760  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:02.760  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:02.761  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.774  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 18:40:02.774  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 18:40:02.775  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.776  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.783  2725  2725 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 18:40:02.783  2725  2725 I wpa_supplicant: monitor socket send errors count : 1
,08-29 18:40:02.783  2725  2725 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
08-29 18:40:02.784  1033  2757 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 18:40:02.784  1033  2757 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 18:40:02.793  6913  6913 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 18:40:02.793  6913  6913 W LG Account v2.2: No ProfileInfo entries
08-29 18:40:02.793  6913  6913 I LG Account v2.2: isEnabled: false
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Country: EU
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Operator: OPEN
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Ranking support: false
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Comfort support: false
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Accessory: true
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Health device: true
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Extra Pedometer: false
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Blood glucose device: false
08-29 18:40:02.793  6913  6913 I Feature : [Lifetracker]Device Number: 3
,08-29 18:40:02.800  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 18:40:02.803  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 18:40:02.803  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:02.803  3891  3891 V BluetoothPbapReceiver: ***********state = 13
08-29 18:40:02.804  3891  3891 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 18:40:02.804  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:02.805  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:02.805  3891  3891 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:02.805  3891  3891 V BluetoothPbapService: state: 13
08-29 18:40:02.805  3891  3891 V BluetoothPbapService: Pbap Service closeService in
,08-29 18:40:02.809  1033  1095 D BluetoothManagerService: Message: 20
08-29 18:40:02.809  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b5b03eb:true
08-29 18:40:02.822  2725  2725 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 18:40:02.822  1033  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 18:40:02.822  1033  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 18:40:02.822  1033  2757 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 18:40:02.823  1033  2757 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 18:40:02.824  1033  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-29 18:40:02.824  2725  2725 W wpa_supplicant: USIM:  scard_deinit function
08-29 18:40:02.824  1033  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:02.824  1033  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117679
08-29 18:40:02.824  1033  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117679
08-29 18:40:02.824  1033  1095 D Tethering: InitialState.processMessage what=4
08-29 18:40:02.824  1033  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117679  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 18:40:02.825  1033  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117679  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 18:40:02.848  1033  1953 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6932 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 18:40:02.851  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 18:40:02.851  3891  3891 V BluetoothPbapService: successfully stopped pbap service
08-29 18:40:02.851  3891  3891 V BluetoothPbapService: Pbap Service closeService out
08-29 18:40:02.851  3891  3891 V BluetoothPbapService: Pbap Service onDestroy
08-29 18:40:02.851  3891  3891 V BluetoothPbapService: Pbap Service closeService in
08-29 18:40:02.851  3891  3891 V BluetoothPbapService: Pbap Service closeService out
08-29 18:40:02.851  3891  3891 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 18:40:02.853  1033  1095 D BluetoothManagerService: Message: 30
08-29 18:40:02.855  1033  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:02.855  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 18:40:02.858  1033  1095 D BluetoothManagerService: Message: 30
08-29 18:40:02.860  6895  6895 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 18:40:02.861  6895  6895 D BluetoothMap: Create BluetoothMap proxy object
08-29 18:40:02.862  1033  1095 D BluetoothManagerService: Message: 30
,08-29 18:40:02.865  1033  1095 D BluetoothManagerService: Message: 30
08-29 18:40:02.866  6895  6895 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 18:40:02.867  6895  6895 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 18:40:02.871  6657  6657 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 18:40:02.877  6895  6895 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-29 18:40:02.880  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-29 18:40:02.881  6123  6123 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-29 18:40:02.884  2725  2725 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 18:40:02.886  1033  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 18:40:02.886  1033  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 18:40:02.886  1033  2757 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 18:40:02.886  1033  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-29 18:40:02.887  1033  1573 I ActivityManager: Killing 6244:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 18:40:02.913  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 18:40:02.916  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 18:40:02.917  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:02.924  1033  1908 W libprocessgroup: failed to open /acct/uid_10014/pid_6244/cgroup.procs: No such file or directory
08-29 18:40:02.924  6895  6895 D DockEventReceiver: finishStartingService: stopping service
08-29 18:40:02.927  1033  1573 I ActivityManager: Killing 6346:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-29 18:40:02.933  6895  6895 D BluetoothInputDevice: Proxy object connected
08-29 18:40:02.934  6895  6895 D HidProfile: Bluetooth service connected
08-29 18:40:02.935  6895  6895 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 18:40:02.935  6895  6895 D PanProfile: Bluetooth service connected
08-29 18:40:02.936  6895  6895 D BluetoothMap: Proxy object connected
08-29 18:40:02.936  6895  6895 D MapProfile: Bluetooth service connected
08-29 18:40:02.936  6895  6895 D BluetoothMap: getConnectedDevices()
08-29 18:40:02.937  6895  6895 D BluetoothMap: Bluetooth is Not enabled
08-29 18:40:02.937  6895  6895 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-29 18:40:02.958  1033  1048 W libprocessgroup: failed to open /acct/uid_10004/pid_6346/cgroup.procs: No such file or directory
,08-29 18:40:02.984  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:02.989  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-29 18:40:02.989  1033  1390 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 18:40:02.989  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:02.989  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:02.989  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 18:40:02.990  1941  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-29 18:40:02.990  1941  2296 D WfdsService: Set the WFDS Monitor: false
08-29 18:40:02.990  1941  2296 D WfdsMonitor: WFDS Monitor is stopped
08-29 18:40:02.993  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:02.994  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 18:40:02.995  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 18:40:02.996  1033  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 18:40:02.996  2485  2485 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:02.997  1033  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 18:40:03.000  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:03.003  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:03.051  6895  6895 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:03.051  6895  6895 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:40:03.065  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:03.066  6895  6895 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 18:40:03.070  6895  6895 D BluetoothPermissionRequest: onReceive
08-29 18:40:03.073  6895  6895 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 18:40:03.083  1033  2013 I ActivityManager: Killing 6519:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 18:40:03.086  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:03.116  1033  1953 W libprocessgroup: failed to open /acct/uid_10008/pid_6519/cgroup.procs: No such file or directory
,08-29 18:40:03.116  3891  3891 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 18:40:03.116  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 18:40:03.117  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-29 18:40:03.198  1033  1648 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6964 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-29 18:40:03.204  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:03.205  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 18:40:03.214  3891  3891 V BluetoothFtpService: Ftp Service onStartCommand
08-29 18:40:03.214  3891  3891 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:03.216  3891  3891 V BluetoothFtpService: Ftp Service closeService
08-29 18:40:03.216  3891  3891 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 18:40:03.218  3891  3891 V BluetoothFtpService: successfully stopped ftp service
08-29 18:40:03.218  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:03.218  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:03.218  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 18:40:03.218  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:03.219  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 18:40:03.219  3891  3891 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-29 18:40:03.221  3891  3891 V BluetoothFtpService: Ftp Service onDestroy
08-29 18:40:03.221  3891  3891 V BluetoothFtpService: Ftp Service closeService
08-29 18:40:03.223   348   348 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 23.114ms
08-29 18:40:03.241   348   348 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 17.089ms
,08-29 18:40:03.259   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.077ms
,08-29 18:40:03.319  1033  1953 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6981 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 18:40:03.334  3891  3891 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:03.335  3891  3891 V BluetoothSapService: state: 13
08-29 18:40:03.335  3891  3891 V BluetoothSapService: Stopping SAP server process
,08-29 18:40:03.336  3891  3891 V BluetoothSapService: Sap Service closeSapService in
08-29 18:40:03.336  3891  3891 V BluetoothSapService: Close listen Socket : 
08-29 18:40:03.337  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
08-29 18:40:03.337  3891  3891 V BluetoothSapService: Close sapd  Socket : 
08-29 18:40:03.339  3891  3891 V BluetoothSapService: Sap Service closeSapService out
08-29 18:40:03.339  3891  3891 V BluetoothSapService: Sap Service onDestroy
08-29 18:40:03.339  3891  3891 V BluetoothSapService: Sap Service closeSapService in
08-29 18:40:03.339  3891  3891 V BluetoothSapService: Close listen Socket : 
08-29 18:40:03.339  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
08-29 18:40:03.339  3891  3891 V BluetoothSapService: Close sapd  Socket : 
08-29 18:40:03.339  3891  3891 V BluetoothSapService: Sap Service closeSapService out
08-29 18:40:03.359  6964  6964 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 18:40:03.383  6981  6981 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 18:40:03.393  6964  6964 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 18:40:03.407  1033  1648 I ActivityManager: Killing 6054:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 18:40:03.430  6964  6964 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 18:40:03.431  6964  6964 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 18:40:03.431  6964  6964 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 18:40:03.432  6964  6964 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 18:40:03.432  6964  6964 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-29 18:40:03.434  6964  6964 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 18:40:03.440  6964  6964 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 18:40:03.467  1033  1573 W libprocessgroup: failed to open /acct/uid_10011/pid_6054/cgroup.procs: No such file or directory
,08-29 18:40:03.478  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:03.485  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:03.512  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 18:40:03.515  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:03.517  6964  6964 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 18:40:03.519  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 18:40:03.519  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 18:40:03.519  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:03.521  6964  6964 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 18:40:03.524  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:03.533  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:03.541  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:03.541  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:03.543  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 18:40:03.546  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:03.552  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 18:40:03.552  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 18:40:03.552  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:03.557  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:03.566  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:03.576  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:03.577  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:03.579  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 18:40:03.599  3891  3989 D bt_hci_bdroid: cleanup
,08-29 18:40:03.600  3891  4104 I bt_lpm  : LPM is already off!!!
08-29 18:40:03.600  3891  4193 I bt_userial_mct: exiting userial_read_thread
08-29 18:40:03.600  3891  4193 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 18:40:03.600  3891  4098 W bt-btif : ag scb idx 1 not allocated
08-29 18:40:03.600  3891  4098 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 18:40:03.600  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:03.600  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-29 18:40:03.601  3891  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:03.601  3891  4098 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 18:40:03.601  3891  3989 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-29 18:40:03.601  3891  4104 I bt_vendor: hw_epilog_process
08-29 18:40:03.602  3891  3989 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-29 18:40:03.602  3891  3989 D bt_userial_mct: userial_close
08-29 18:40:03.602  3891  3989 E bt_userial_mct: pthread_join() FAILED result:3
08-29 18:40:03.602  3891  3989 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 18:40:03.645  1033  1994 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7002 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 18:40:03.723  3891  3989 D bt_hci_bdroid: set_power 0
08-29 18:40:03.723  3891  3989 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 18:40:03.723  3891  3989 I bt_vendor: bluetooth satus is on
08-29 18:40:03.723  3891  3989 I bt_vendor: bt-vendor : resetting BT status
08-29 18:40:03.723  3891  3989 I bt_vendor: Starting hciattach daemon
08-29 18:40:03.723  3891  3989 I bt_vendor: try to set false
,08-29 18:40:03.725  3891  3989 I bt_vendor: Starting hciattach daemon
08-29 18:40:03.725  3891  3989 I bt_vendor: try to set false
08-29 18:40:03.725  3891  3989 I bt_vendor: cleanup
08-29 18:40:03.727  3891  4098 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 18:40:03.728  3891  3989 I GKI_LINUX: GKI_exit_task 0 done
08-29 18:40:03.728  3891  3989 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 18:40:03.731  3891  3984 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 18:40:03.734  3891  3891 D HeadsetService: Received stop request...Stopping profile...
08-29 18:40:03.736  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 18:40:03.736  3891  3891 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 18:40:03.736  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8b3b97
,08-29 18:40:03.738  3891  4016 D HeadsetStateMachine: Exit Disconnected: -1
08-29 18:40:03.740  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:03.740  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:03.740  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:03.740  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:03.740  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 18:40:03.744  3891  3891 D A2dpService: Received stop request...Stopping profile...
08-29 18:40:03.745  3891  4073 D A2dpStateMachine: Exit Disconnected: -1
08-29 18:40:03.746  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 18:40:03.749  3891  3984 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 18:40:03.750  3891  3891 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 18:40:03.751  3891  3891 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 18:40:03.751  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8b3b97
08-29 18:40:03.752  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-29 18:40:03.752  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 18:40:03.754  3891  3891 D HeadsetStateMachine: Unbinding service...
08-29 18:40:03.755  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 18:40:03.756  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 18:40:03.756  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 18:40:03.756  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 18:40:03.756  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 18:40:03.756  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 18:40:03.756  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 18:40:03.757  3891  3891 D HidService: Received stop request...Stopping profile...
08-29 18:40:03.757  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8b3b97
08-29 18:40:03.763  6895  6895 D BluetoothInputDevice: Proxy object disconnected
08-29 18:40:03.764  6895  6895 D HidProfile: Bluetooth service disconnected
08-29 18:40:03.764  3891  3891 D HealthService: Received stop request...Stopping profile...
,08-29 18:40:03.764  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8b3b97
08-29 18:40:03.765  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:03.766  3891  3891 D PanService: Received stop request...Stopping profile...
08-29 18:40:03.767  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8b3b97
,08-29 18:40:03.768  3891  3891 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 18:40:03.768  3891  3891 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 18:40:03.768  3891  3891 D BtGatt.GattService: stop()
08-29 18:40:03.768  3891  3891 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 18:40:03.770  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8b3b97
08-29 18:40:03.771  3891  3891 D BluetoothMapService: Received stop request...Stopping profile...
08-29 18:40:03.771  3891  3891 D BluetoothMapService: stop()
08-29 18:40:03.771  6895  6895 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 18:40:03.771  6895  6895 D PanProfile: Bluetooth service disconnected
08-29 18:40:03.775  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 18:40:03.776  3891  3891 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 18:40:03.776  3891  3891 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 18:40:03.777  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8b3b97
,08-29 18:40:03.780  3891  3891 I BluetoothA2dpServiceJni: cleanupNative
08-29 18:40:03.780  3891  4074 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 18:40:03.780  3891  3891 I GKI_LINUX: GKI_exit_task 2 done
08-29 18:40:03.780  3891  3891 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 18:40:03.781  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 18:40:03.781  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 18:40:03.782  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 18:40:03.782  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 18:40:03.782  3891  3891 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 18:40:03.784  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 18:40:03.784  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 18:40:03.785  3891  3891 V BluetoothMapService: Handler(): got msg=4
08-29 18:40:03.785  3891  3891 D BluetoothMapService: MAP Service closeService in
08-29 18:40:03.785  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 18:40:03.785  3891  3891 V BluetoothMapService: MAP Service closeService out
08-29 18:40:03.785  3891  3891 D BluetoothMapService: cleanup()
08-29 18:40:03.785  3891  3891 D BluetoothMapService: MAP Service closeService in
08-29 18:40:03.785  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 18:40:03.785  3891  3891 V BluetoothMapService: MAP Service closeService out
08-29 18:40:03.786  3891  3984 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 18:40:03.786  3891  3984 D BluetoothAdapterProperties: Setting state to 10
08-29 18:40:03.786  3891  3984 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 18:40:03.787  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:03.787  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 18:40:03.787  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 18:40:03.787  3891  3984 I BluetoothAdapterState: Entering OffState
08-29 18:40:03.787  1852  4027 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:03.788  6895  6911 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 18:40:03.789  6895  6910 D BluetoothPan: onBluetoothStateChange on: false
08-29 18:40:03.791  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:03.791  1852  2461 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:03.792  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 18:40:03.793  6895  6911 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 18:40:03.794  1852  2460 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:03.795  6895  6910 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 18:40:03.797  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 18:40:03.797  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-29 18:40:03.804  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:03.805  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 18:40:03.805  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 18:40:03.805  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@88fd973 mBinding = false
08-29 18:40:03.806  1033  1095 D BluetoothManagerService: Sending unbind request.
08-29 18:40:03.810  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 18:40:03.812  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:03.812  1941  2125 D LGBluetoothAPIService: Message: 2
08-29 18:40:03.812  1941  2125 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@36db7ce6 mBinding = false
08-29 18:40:03.812  1941  2125 D LGBluetoothAPIService: Sending unbind request.
08-29 18:40:03.813  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 18:40:03.814  6895  6895 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 18:40:03.815  6895  6895 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 18:40:03.815  6895  6895 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-29 18:40:03.822  3891  3989 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 18:40:03.822  3891  3891 I GKI_LINUX: GKI_exit_task 1 done
08-29 18:40:03.822  3891  3891 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 18:40:03.823  3891  3891 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 18:40:03.823  3891  3891 I art     : --- WEIRD: removing null entry 246
08-29 18:40:03.823  3891  3891 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 18:40:03.823  3891  3891 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 18:40:03.824  3891  3891 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 18:40:03.827  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:03.828  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 18:40:03.828  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:03.834  1601  1601 D BluetoothAdapter: 888945935: getState() :  mService = null. Returning STATE_OFF
08-29 18:40:03.834  1601  1601 D BluetoothAdapter: 888945935: getState() :  mService = null. Returning STATE_OFF
08-29 18:40:03.834  3891  3891 I art     : System.exit called, status: 0
08-29 18:40:03.834  3891  3891 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 18:40:03.841  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 18:40:03.841  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 18:40:03.841  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-29 18:40:03.841  6895  6895 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 18:40:03.842  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 18:40:03.847  7002  7021 W FormManager: Network not available. Please check & try again.
08-29 18:40:03.850  7002  7022 V FormManager: Network unavailable.
08-29 18:40:03.854  7002  7022 V FormManager: Network unavailable.
,08-29 18:40:03.858  6895  6895 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 18:40:03.859   325  2163 V AudioFlinger: 3891 died, releasing its sessions
08-29 18:40:03.859   325  2163 V AudioFlinger:  pid 1852 @ 0
08-29 18:40:03.859   325  2163 V AudioFlinger:  pid 3458 @ 1
08-29 18:40:03.859   325  2163 V AudioFlinger:  pid 3458 @ 2
08-29 18:40:03.860  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 18:40:03.860  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 18:40:03.860  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 18:40:03.860  6895  6895 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-29 18:40:03.861  6895  6895 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 18:40:03.933  1033  2013 I ActivityManager: Process com.android.bluetooth (pid 3891) has died
08-29 18:40:03.934  1033  2013 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-29 18:40:03.951  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 18:40:03.952  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 18:40:03.957  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:03.959  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:03.961  6895  6895 D DockEventReceiver: finishStartingService: stopping service
08-29 18:40:03.963  6895  6895 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 18:40:03.968  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 18:40:03.980  4362  7032 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 18:40:03.988  4362  7033 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 18:40:03.988  4362  7033 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 18:40:03.996  6932  6932 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-29 18:40:03.996  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 18:40:03.996  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:03.998  6895  6895 D BluetoothPermissionRequest: onReceive
08-29 18:40:04.003  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:04.012  7002  7035 W FormManager: Network not available. Please check & try again.
08-29 18:40:04.016  7002  7036 V FormManager: Network unavailable.
,08-29 18:40:04.020  7002  7036 V FormManager: Network unavailable.
08-29 18:40:04.021  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:04.023  6895  6895 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 18:40:04.025  6895  6895 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 18:40:04.027  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:04.094  1033  1049 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7037 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 18:40:04.104  1033  1049 I ActivityManager: Killing 6076:com.android.contacts/u0a19 (adj 15): empty #17
08-29 18:40:04.165  1033  2042 W libprocessgroup: failed to open /acct/uid_10019/pid_6076/cgroup.procs: No such file or directory
,08-29 18:40:04.198  6964  6964 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-29 18:40:04.201  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-29 18:40:04.202  6964  6964 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 18:40:04.204  7037  7037 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 18:40:04.205  7037  7037 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 18:40:04.206  7037  7037 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 18:40:04.208  7037  7037 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 18:40:04.231  7037  7037 D BluetoothAdapterApp: Loading JNI Library
,08-29 18:40:04.251  6964  6964 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:04.252  6964  6964 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:40:04.261  6964  6964 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 18:40:04.263  6964  6964 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 18:40:04.263  6964  6964 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 18:40:04.263  6964  6964 V SoundPool: doLoad: loading sample sampleID=1
08-29 18:40:04.264  6964  6964 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-29 18:40:04.266  6964  7057 V SoundPool: Start decode
08-29 18:40:04.266  6964  7057 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 18:40:04.268   325  1400 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 18:40:04.268   325  1400 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 18:40:04.268   325  1400 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 18:40:04.268   325  1400 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 18:40:04.268   325  1400 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 18:40:04.268   325  1400 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 18:40:04.268   325  1400 V MediaPlayerService: player type = 3
08-29 18:40:04.268   325  1400 V AwesomePlayer: AwesomePlayer create()
08-29 18:40:04.269   325  1400 V AwesomePlayer: reset_l() 
08-29 18:40:04.269   325  1400 V AwesomePlayer: cancelPlayerEvents
08-29 18:40:04.269   325  1400 V AwesomePlayer: setAudioSink() 
08-29 18:40:04.269   325  1400 V AwesomePlayer: reset_l() 
08-29 18:40:04.269  7037  7037 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d8110ec Instance Count = 1
08-29 18:40:04.269   325  1400 V AudioCache: notify(0xb16a6800, 8, 0, 0)
08-29 18:40:04.269   325  1400 V AudioCache: ignored
08-29 18:40:04.269   325  1400 V AwesomePlayer: cancelPlayerEvents
08-29 18:40:04.269   325  1400 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 18:40:04.269   325  1400 V AwesomePlayer: setDataSource_l dataSource
08-29 18:40:04.269   325  1400 V LGParserOSAL: SniffLGParser start
08-29 18:40:04.269   325  1400 V LGParserOSAL: MainType:5, SubType=0
08-29 18:40:04.269   325  1400 V LGParserOSAL: #### check Mime : application/ogg
08-29 18:40:04.269   325  1400 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 18:40:04.269   325  1400 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 18:40:04.275  6781  6781 D UEI.SmartControl: QS Service created
08-29 18:40:04.276  6964  6964 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 18:40:04.276  7037  7037 D BluetoothAdapterApp: onCreate
08-29 18:40:04.279  6964  6964 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 18:40:04.280  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-29 18:40:04.302  7037  7037 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 18:40:04.303  7037  7037 D ProfileConfigQcom: Adding HeadsetService
08-29 18:40:04.303  7037  7037 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 18:40:04.303  7037  7037 D ProfileConfigQcom: Adding A2dpService
08-29 18:40:04.303  7037  7037 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 18:40:04.303  7037  7037 D ProfileConfigQcom: Adding HidService
08-29 18:40:04.304  7037  7037 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 18:40:04.304  7037  7037 D ProfileConfigQcom: Adding HealthService
08-29 18:40:04.304  7037  7037 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 18:40:04.305  7037  7037 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 18:40:04.305  7037  7037 D ProfileConfigQcom: Adding PanService
08-29 18:40:04.306  6781  6781 I UEI.SmartControl: Service initServices...
08-29 18:40:04.306  7037  7037 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 18:40:04.306  6781  6781 D UEI.SmartControl: QS start get config
08-29 18:40:04.306  7037  7037 D ProfileConfigQcom: Adding GattService
08-29 18:40:04.306  7037  7037 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 18:40:04.306  7037  7037 D ProfileConfigQcom: Adding BluetoothMapService
08-29 18:40:04.307  6964  6964 V LGMDMManager: Create singleton instance
08-29 18:40:04.307  7037  7037 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 18:40:04.308  7037  7037 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 18:40:04.313  6895  6895 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-29 18:40:04.315   325  1400 V LGParserOSAL: supported mime: application/ogg
08-29 18:40:04.315   325  1400 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 18:40:04.315   325  1400 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 18:40:04.315   325  1400 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 18:40:04.315   325  1400 V AwesomePlayer: AudioTrack Setting
08-29 18:40:04.315   325  1400 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 18:40:04.315   325  1400 V AwesomePlayer: setAudioSource() 
08-29 18:40:04.315   325  1400 V MediaPlayerService: prepare
08-29 18:40:04.315   325  1400 V AwesomePlayer: prepareAsync_l() 
08-29 18:40:04.315   325  1400 V MediaPlayerService: wait for prepare
08-29 18:40:04.316   325  7059 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 18:40:04.316   325  7059 V AwesomePlayer: initAudioDecoder() 
08-29 18:40:04.316   325  7059 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 18:40:04.316   325  7059 V AudioSystem: isOffloadSupported()
08-29 18:40:04.316   325  7059 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 18:40:04.316   325  7059 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 18:40:04.316   325  7059 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 18:40:04.316   325  7059 V AwesomePlayer: getUseOffload() = 0 
08-29 18:40:04.316   325  7059 V OMXCodec: OMXCodec::Create
08-29 18:40:04.316   325  7059 V OMXCodec: findMatchingCodecs()
08-29 18:40:04.316   325  7059 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 18:40:04.316   325  7059 V OMXCodec: matchingCodecs.size()=1
08-29 18:40:04.316   325  7059 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 18:40:04.318   325  7059 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 18:40:04.318   325  7059 V LGCodecAdapter: LG Codec Adapter start
08-29 18:40:04.318   325  7059 V OMXCodec: OMXCodec Createtor
08-29 18:40:04.318  7037  7037 V LGMDMManagerInternal: Create singleton instance
08-29 18:40:04.318   325  7059 V OMXCodec: setComponentRole
08-29 18:40:04.318   325  7059 V OMXCodec: configureCodec protected=0
08-29 18:40:04.318   325  7059 V LGCodecAdapter: called getLGCodecSpecificData
08-29 18:40:04.318   325  7059 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 18:40:04.318   325  7059 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 18:40:04.318   325  7059 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 18:40:04.318   325  7059 V LGCodecOSAL: Not support LGCodec
08-29 18:40:04.318   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 18:40:04.318   325  7059 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 18:40:04.318   325  7059 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 18:40:04.318   325  7059 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 18:40:04.318   325  7059 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 18:40:04.318   325  7059 V AudioSystem: isOffloadSupported()
08-29 18:40:04.318   325  7059 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 18:40:04.318   325  7059 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 18:40:04.318   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 18:40:04.318   325  7059 V OMXCodec: ,init()
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 18:40:04.319   325  7059 V OMXCodec: allocateBuffers
08-29 18:40:04.319   325  7059 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-29 18:40:04.319   325  7059 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-29 18:40:04.319   325  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff100 on output port
08-29 18:40:04.319   325  7059 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 18:40:04.320   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 18:40:04.320   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 18:40:04.320   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 18:40:04.321   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 18:40:04.321   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 18:40:04.321   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 18:40:04.321   325  7059 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 18:40:04.321   325  7059 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 18:40:04.321   325  7059 V AudioCache: notify(0xb16a6800, 5, 0, 0)
08-29 18:40:04.321   325  7059 V AudioCache: ignored
08-29 18:40:04.321   325  7059 V AudioCache: notify(0xb16a6800, 1, 0, 0)
08-29 18:40:04.321   325  7059 V AudioCache: prepared
08-29 18:40:04.321   325  1400 V AudioCache: wait - success
08-29 18:40:04.321   325  1400 V MediaPlayerService: start
08-29 18:40:04.321   325  1400 V AwesomePlayer: play_l() 
08-29 18:40:04.321   325  1400 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 18:40:04.321   325  1400 V AwesomePlayer: createAudioPlayer_l
08-29 18:40:04.321   325  1400 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 18:40:04.321   325  1400 V AwesomePlayer: startAudioPlayer_l() 
08-29 18:40:04.321   325  1400 D AudioPlayer: start of Playback, useOffload 0
08-29 18:40:04.321   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 18:40:04.321   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 18:40:04.324   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 18:40:04.324   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 18:40:04.324   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 18:40:04.324   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 18:40:04.324   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 18:40:04.324   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 18:40:04.327   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-29 18:40:04.327   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045060864
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 18:40:04.333   325  7061 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 18:40:04.333   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-29 18:40:04.334   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-29 18:40:04.334   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-29 18:40:04.334   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff6a0 on output port
08-29 18:40:04.334   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 18:40:04.334   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,08-29 18:40:04.335   325  1400 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 18:40:04.335   325  1400 V AudioCache: notify(0xb16a6800, 6, 0, 0)
08-29 18:40:04.335   325  1400 V AudioCache: ignored
08-29 18:40:04.335   325  1400 V MediaPlayerService: wait for playback complete
08-29 18:40:04.336   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.336   325  7062 V AudioCache: memcpy(0xae300000, 0xb1786000, 4096)
08-29 18:40:04.337   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.337   325  7062 V AudioCache: memcpy(0xae301000, 0xb1786000, 4096)
08-29 18:40:04.338   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.338   325  7062 V AudioCache: memcpy(0xae302000, 0xb1786000, 4096)
08-29 18:40:04.338   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.338   325  7062 V AudioCache: memcpy(0xae303000, 0xb1786000, 4096)
08-29 18:40:04.339   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.339   325  7062 V AudioCache: memcpy(0xae304000, 0xb1786000, 4096)
08-29 18:40:04.339   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.339   325  7062 V AudioCache: memcpy(0xae305000, 0xb1786000, 4096)
08-29 18:40:04.340   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.340   325  7062 V AudioCache: memcpy(0xae306000, 0xb1786000, 4096)
08-29 18:40:04.340   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.340   325  7062 V AudioCache: memcpy(0xae307000, 0xb1786000, 4096)
08-29 18:40:04.343   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.343   325  7062 V AudioCache: memcpy(0xae308000, 0xb1786000, 4096)
08-29 18:40:04.345   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.345   325  7062 V AudioCache: memcpy(0xae309000, 0xb1786000, 4096)
08-29 18:40:04.345   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.345   325  7062 V AudioCache: memcpy(0xae30a000, 0xb1786000, 4096)
08-29 18:40:04.345   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.346   325  7062 V AudioCache: memcpy(0xae30b000, 0xb1786000, 4096)
08-29 18:40:04.346   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.346   325  7062 V AudioCache: memcpy(0xae30c000, 0xb1786000, 4096)
08-29 18:40:04.347   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.347   325  7062 V AudioCache: memcpy(0xae30d000, 0xb1786000, 4096)
08-29 18:40:04.348   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.348   325  7062 V AudioCache: memcpy(0xae30e000, 0xb1786000, 4096)
08-29 18:40:04.348   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.348   325  7062 V AudioCache: memcpy(0xae30f000, 0xb1786000, 4096)
08-29 18:40:04.349   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.349   325  7062 V AudioCache: memcpy(0xae310000, 0xb1786000, 4096)
08-29 18:40:04.349   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.349   325  7062 V AudioCache: memcpy(0xae311000, 0xb1786000, 4096)
,08-29 18:40:04.353   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.353   325  7062 V AudioCache: memcpy(0xae312000, 0xb1786000, 4096)
08-29 18:40:04.353   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.353   325  7062 V AudioCache: memcpy(0xae313000, 0xb1786000, 4096)
08-29 18:40:04.356   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.356   325  7062 V AudioCache: memcpy(0xae314000, 0xb1786000, 4096)
08-29 18:40:04.357   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.357   325  7062 V AudioCache: memcpy(0xae315000, 0xb1786000, 4096)
08-29 18:40:04.357   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.357   325  7062 V AudioCache: memcpy(0xae316000, 0xb1786000, 4096)
08-29 18:40:04.358   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.358   325  7062 V AudioCache: memcpy(0xae317000, 0xb1786000, 4096)
08-29 18:40:04.359   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.359   325  7062 V AudioCache: memcpy(0xae318000, 0xb1786000, 4096)
08-29 18:40:04.359   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.359   325  7062 V AudioCache: memcpy(0xae319000, 0xb1786000, 4096)
08-29 18:40:04.360   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.360   325  7062 V AudioCache: memcpy(0xae31a000, 0xb1786000, 4096)
08-29 18:40:04.361   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.361   325  7062 V AudioCache: memcpy(0xae31b000, 0xb1786000, 4096)
08-29 18:40:04.361   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.361   325  7062 V AudioCache: memcpy(0xae31c000, 0xb1786000, 4096)
08-29 18:40:04.362   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.362   325  7062 V AudioCache: memcpy(0xae31d000, 0xb1786000, 4096)
08-29 18:40:04.363   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.363   325  7062 V AudioCache: memcpy(0xae31e000, 0xb1786000, 4096)
08-29 18:40:04.364   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.364   325  7062 V AudioCache: memcpy(0xae31f000, 0xb1786000, 4096)
08-29 18:40:04.364   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.364   325  7062 V AudioCache: memcpy(0xae320000, 0xb1786000, 4096)
08-29 18:40:04.365   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.365   325  7062 V AudioCache: memcpy(0xae321000, 0xb1786000, 4096)
,08-29 18:40:04.365   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.365   325  7062 V AudioCache: memcpy(0xae322000, 0xb1786000, 4096)
08-29 18:40:04.366   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.366   325  7062 V AudioCache: memcpy(0xae323000, 0xb1786000, 4096)
08-29 18:40:04.367   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.367   325  7062 V AudioCache: memcpy(0xae324000, 0xb1786000, 4096)
08-29 18:40:04.367   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.367   325  7062 V AudioCache: memcpy(0xae325000, 0xb1786000, 4096)
08-29 18:40:04.368   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.368   325  7062 V AudioCache: memcpy(0xae326000, 0xb1786000, 4096)
08-29 18:40:04.369   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.369   325  7062 V AudioCache: memcpy(0xae327000, 0xb1786000, 4096)
08-29 18:40:04.369   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.369   325  7062 V AudioCache: memcpy(0xae328000, 0xb1786000, 4096)
08-29 18:40:04.370   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.370   325  7062 V AudioCache: memcpy(0xae329000, 0xb1786000, 4096)
08-29 18:40:04.370   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.370   325  7062 V AudioCache: memcpy(0xae32a000, 0xb1786000, 4096)
08-29 18:40:04.371   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.371   325  7062 V AudioCache: memcpy(0xae32b000, 0xb1786000, 4096)
08-29 18:40:04.372   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.372   325  7062 V AudioCache: memcpy(0xae32c000, 0xb1786000, 4096)
08-29 18:40:04.372   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.372   325  7062 V AudioCache: memcpy(0xae32d000, 0xb1786000, 4096)
08-29 18:40:04.373   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.373   325  7062 V AudioCache: memcpy(0xae32e000, 0xb1786000, 4096)
08-29 18:40:04.374   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.374   325  7062 V AudioCache: memcpy(0xae32f000, 0xb1786000, 4096)
08-29 18:40:04.374   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.374   325  7062 V AudioCache: memcpy(0xae330000, 0xb1786000, 4096)
08-29 18:40:04.375   325  7062 V AudioCache: write(0xb1786000, 4096)
08-29 18:40:04.375   325  7062 V AudioCache: memcpy(0xae331000, 0xb1786000, 4096)
08-29 18:40:04.375   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 18:40:04.375   325  7062 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 18:40:04.375   325  7062 V AwesomePlayer: postAudioEOS() 
08-29 18:40:04.375   325  7062 V AudioCache: write(0xb1786000, 280)
08-29 18:40:04.375   325  7062 V AudioCache: memcpy(0xae332000, 0xb1786000, 280)
08-29 18:40:04.380  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 18:40:04.380   325  7059 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 18:40:04.380   325  7059 V AwesomePlayer: onStreamDone
08-29 18:40:04.380   325  7059 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 18:40:04.380   325  7059 V AudioCache: notify(0xb16a6800, 2, 0, 0)
08-29 18:40:04.380   325  7059 V AudioCache: playback complete
08-29 18:40:04.380   325  7059 V AwesomePlayer: pause_l() 
08-29 18:40:04.380   325  7059 V AudioCache: notify(0xb16a6800, 7, 0, 0)
08-29 18:40:04.380   325  7059 V AudioCache: ignored
,08-29 18:40:04.380   325  7059 V AwesomePlayer: cancelPlayerEvents
08-29 18:40:04.380   325  1400 V AudioCache: wait - success
08-29 18:40:04.380   325  1400 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 18:40:04.381   325  7059 D AudioPlayer: Pause Playback at 1068125
08-29 18:40:04.381   325  1400 V AwesomePlayer: reset_l() 
08-29 18:40:04.381   325  1400 V AudioCache: notify(0xb16a6800, 8, 0, 0)
08-29 18:40:04.381   325  1400 V AudioCache: ignored
08-29 18:40:04.381   325  1400 V AwesomePlayer: cancelPlayerEvents
08-29 18:40:04.381   325  1400 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 18:40:04.381   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 18:40:04.381   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 18:40:04.381   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 18:40:04.381  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 18:40:04.381   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-29 18:40:04.381   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 18:40:04.381   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ff6a0 on port 1
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 18:40:04.382   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 18:40:04.382   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 18:40:04.382   325  7061 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 18:40:04.382   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 18:40:04.382   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 18:40:04.383   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 18:40:04.384   325  1400 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 18:40:04.385   325  1400 D AudioPlayer: AudioPlayer releasing audio source
08-29 18:40:04.385   325  1400 D AudioPlayer: AudioPlayer done releasing audio source
08-29 18:40:04.385   325  1400 V AwesomePlayer: reset_l() 
08-29 18:40:04.385   325  1400 V AwesomePlayer: cancelPlayerEvents
08-29 18:40:04.385   325  1400 V AwesomePlayer: ~AwesomePlayer call
,08-29 18:40:04.385   325  1400 V AwesomePlayer: reset_l() 
08-29 18:40:04.385   325  1400 V AwesomePlayer: cancelPlayerEvents
08-29 18:40:04.385  6964  7057 V SoundPool: close(31)
08-29 18:40:04.386  6964  7057 V SoundPool: pointer = 0x9ffd0000, size = 205080, sampleRate = 48000, numChannels = 2
,08-29 18:40:04.390  7037  7037 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:04.390  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5831
08-29 18:40:04.393  7037  7037 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:04.393  7037  7037 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:04.393  7037  7037 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 18:40:04.394  7037  7037 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:04.394  7037  7037 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 18:40:04.400  6981  6981 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 18:40:04.791  6781  6781 I UEI.SmartControl: Supports setup maps: true
,08-29 18:40:04.800  6781  6781 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 18:40:04.800  6781  6781 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 18:40:04.800  6781  6781 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 18:40:04.800  6781  6781 I UEI.SmartControl: ### init IR Blaster...
08-29 18:40:04.803  6781  6781 D serial_port: Configuring serial port
08-29 18:40:04.804  6781  6781 E UEI.SmartControl: UEIBLaster setting for 616
08-29 18:40:04.804  6781  6781 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 18:40:04.804  6781  6781 I UEI.SmartControl: configuring settings for MAXQ616
08-29 18:40:04.804  6781  6781 I UEI.SmartControl: Get version...
08-29 18:40:04.821  6781  7073 D UEI.SmartControl: serial port data available: 21
,08-29 18:40:04.850  6781  6781 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 18:40:04.850  6781  6781 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 18:40:04.851  6781  6781 I UEI.SmartControl: QS saving settings...
,08-29 18:40:04.861  6781  6781 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 18:40:04.878  6781  7073 D UEI.SmartControl: serial port data available: 4
,08-29 18:40:04.914  6781  6781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 18:40:04.925  6781  6781 E UEI.SmartControl: Services init done
08-29 18:40:04.925  6781  6781 D UEI.SmartControl: QS Service init finished
08-29 18:40:04.934  6781  6781 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 18:40:04.934  6781  6781 D UEI.SmartControl: QS Service version code: 201091
,08-29 18:40:04.937  6781  6781 D UEI.SmartControl: Service requested: Control
08-29 18:40:04.938  6781  7076 I UEI.SmartControl: Device manager: loading config....
08-29 18:40:04.938  6781  7076 D UEI.SmartControl: ----------- loading internal config...
08-29 18:40:04.943  6964  6964 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 18:40:04.945  6781  6797 I UEI.SmartControl: ------ IControl API: 11
08-29 18:40:04.945  6781  6797 D UEI.SmartControl: File observer start...
08-29 18:40:04.945  6781  6797 E UEI.SmartControl: IR Port is disabled: false
08-29 18:40:04.945  6781  6797 D UEI.SmartControl: Starting file observer...
08-29 18:40:04.946  6781  6797 I UEI.SmartControl: Registering callback...
08-29 18:40:04.947  6781  6797 I UEI.SmartControl: ------ IControl API: 19
08-29 18:40:04.948  6781  6797 I UEI.SmartControl: Registering Services Ready callback...
,08-29 18:40:04.952  6781  6781 D UEI.SmartControl: Internal service binding...
08-29 18:40:04.955  6781  7076 E UEI.SmartControl: Loading SETTINGS...
08-29 18:40:04.959  6781  7076 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 18:40:04.964  6781  7075 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 18:40:04.967  6964  6979 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 18:40:04.968  6964  7055 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 18:40:04.968  6964  7055 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 18:40:04.969  6964  6964 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 18:40:04.969  6964  6964 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 18:40:04.970  6781  6796 I UEI.SmartControl: ------ IControl API: 8
08-29 18:40:04.970  6781  7075 D UEI.SmartControl: -----service ready thread exits
08-29 18:40:04.972  6964  6964 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 18:40:04.972  6964  6964 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 18:40:04.973  6964  6964 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 18:40:04.973  6964  6964 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 18:40:04.974  6964  6964 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 18:40:04.974  6964  6964 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 18:40:04.978  6964  6964 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-29 18:40:04.984  6964  6964 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 18:40:04.985  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 18:40:04.986  6964  6964 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 18:40:04.986  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 18:40:04.987  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 18:40:04.988  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 18:40:04.988  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 18:40:04.989  6964  6964 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472488804989]
08-29 18:40:04.992  6964  6964 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-29 18:40:04.999  1033  1904 I ActivityManager: Killing 6099:com.android.gallery3d/u0a27 (adj 15): empty #17
08-29 18:40:05.034  6964  7078 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 18:40:05.038  1033  1904 I ActivityManager: Killing 6560:com.lge.email/u0a23 (adj 15): empty #18
08-29 18:40:05.083  1033  2013 W libprocessgroup: failed to open /acct/uid_10027/pid_6099/cgroup.procs: No such file or directory
,08-29 18:40:05.088  1033  1049 W libprocessgroup: failed to open /acct/uid_10023/pid_6560/cgroup.procs: No such file or directory
08-29 18:40:05.117  6964  6964 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-29 18:40:05.120  6964  6964 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 18:40:05.120  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 18:40:05.120  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 18:40:05.121  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 18:40:05.121  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 18:40:05.121  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 18:40:05.130  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 18:40:05.467  1033  2042 D WifiServiceImplEx: setWifiEnabled: true pid=6657, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 18:40:05.469  1033  2042 D WifiService: setWifiEnabled: true pid=6657, uid=10118
,08-29 18:40:05.469  1033  2042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 18:40:05.494  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:05.495  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:05.495  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-29 18:40:05.498  1033  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-29 18:40:05.498  1033  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 18:40:05.501  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 18:40:05.501  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 18:40:05.501  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 18:40:05.501  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 18:40:05.501  1033  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 18:40:05.501  1033  1390 E WifiHW  : unknown target_country: EU , set to default
,08-29 18:40:05.502  1033  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
08-29 18:40:05.502  1033  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
08-29 18:40:05.502  1033  1390 I WifiUtil: gEnableBmps=1,
08-29 18:40:05.593  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-29 18:40:05.627  1033  1095 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:05.639  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:05.644  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:05.647  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:05.650  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-29 18:40:05.664  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:05.668  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:05.668  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:05.670  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 18:40:05.674  5809  5809 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 18:40:05.686  5809  5809 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 18:40:05.687  6459  6500 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 18:40:05.716  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:05.756  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:05.781  1033  1049 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7092 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 18:40:05.792  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:05.792  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 18:40:05.856  7092  7092 I AppUp4:AppBoxCP: onCreate
08-29 18:40:05.856  7092  7092 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-29 18:40:05.867  7092  7092 I AppUp4:DB:  setFingerPrint start
08-29 18:40:05.867  7092  7092 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 18:40:05.876  7092  7092 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 18:40:05.876  7092  7092 I AppUp4:DB:  SDK version = 21
08-29 18:40:05.876  7092  7092 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-29 18:40:05.878  7092  7092 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-29 18:40:05.880  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 18:40:05.880  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:05.883  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 18:40:05.883  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 18:40:05.891  7092  7092 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 18:40:05.930  7092  7092 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 18:40:05.930  7092  7092 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:40:05.940  7092  7092 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1038c616
08-29 18:40:05.940  7092  7092 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-29 18:40:05.940  7092  7092 D AppUp4:CustFacade: isPhone : true
08-29 18:40:05.941  7092  7092 D AppUp4:CustModeStarterReceiver: begin check event
08-29 18:40:05.941  7092  7092 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 18:40:05.942  7092  7092 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-29 18:40:05.942  7092  7113 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-29 18:40:05.943  7092  7113 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 18:40:05.943  7092  7113 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 18:40:05.946  1033  2764 I ActivityManager: Killing 6601:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 18:40:05.976  1033  1648 W libprocessgroup: failed to open /acct/uid_10061/pid_6601/cgroup.procs: No such file or directory
08-29 18:40:05.977  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:05.978  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 18:40:05.983  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:05.989  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:05.998  4362  7117 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 18:40:06.004  4362  7118 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:06.006  4362  7118 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 18:40:06.045  1033  1049 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7125 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 18:40:06.120  7125  7125 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 18:40:06.121  7125  7125 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 18:40:06.122  7125  7125 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 18:40:06.123  7125  7125 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 18:40:06.210   321   900 D SoftapController: Softap fwReload - Ok
,08-29 18:40:06.217  1033  1390 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (710ms)
08-29 18:40:06.224   321   900 D CommandListener: Setting iface cfg
08-29 18:40:06.224  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 18:40:06.224   321   900 D CommandListener: Trying to bring down wlan0
08-29 18:40:06.224  1033  1095 D Tethering: InitialState.processMessage what=4
,08-29 18:40:06.226  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 18:40:06.227   321   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:06.229  1033  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 18:40:06.233  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:06.233  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:06.233  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 18:40:06.236  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 18:40:06.222  7146  7146 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:06.222  7146  7146 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 18:40:06.245  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:06.245  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 18:40:06.250  1033  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 18:40:06.250  1033  1390 D WifiMonitor: connecting to supplicant
08-29 18:40:06.252  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:06.253  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:06.263  7125  7125 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-29 18:40:06.270  7146  7146 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 18:40:06.278  7125  7125 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-29 18:40:06.305  7146  7146 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 18:40:06.305  7146  7146 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 18:40:06.317  7125  7125 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:06.350  7125  7125 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:06.351  7125  7125 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:40:06.386  7146  7146 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 18:40:06.416  7146  7146 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 18:40:06.424  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-29 18:40:06.425  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 18:40:06.425  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 18:40:06.425  1033  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-29 18:40:06.426  7146  7146 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-29 18:40:06.427  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:06.427  7146  7146 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 18:40:06.428  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:06.429  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:06.430  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 18:40:06.431  1033  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 18:40:06.431  1033  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 18:40:06.433  1033  7157 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 18:40:06.433  1033  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 18:40:06.433  1033  7157 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 18:40:06.433  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 18:40:06.433  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 18:40:06.433  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 18:40:06.433  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 18:40:06.433  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 18:40:06.433  1033  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 18:40:06.433  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 18:40:06.433  1033  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 18:40:06.435  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.436  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.436  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:06.436  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:06.436  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 18:40:06.436  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.436  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.436  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 18:40:06.439  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:06.440  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 18:40:06.441  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-29 18:40:06.441  1033  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 18:40:06.441  1033  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 18:40:06.442  1033  1390 D WifiNative-wlan0: SET update_config 1: returned true
08-29 18:40:06.442  1033  1390 D WifiConfigStore: Loading config and enabling all networks 
08-29 18:40:06.442  1033  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 18:40:06.443  1033  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 18:40:06.443  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:06.443  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:06.443  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:06.443  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:06.443  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:06.443  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:06.443  6657  6657 V io.jxcore.node.C,onnectivityMonitor:     - BSSID name: null
08-29 18:40:06.443  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:06.443  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:06.443  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:06.443  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:06.445  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:06.445  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:06.445  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:06.445  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:06.453  1033  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 18:40:06.463  1033  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 18:40:06.464  1033  1390 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 18:40:06.465  1033  1390 D WifiStateMachine: enableVerboseLogging : level 2
08-29 18:40:06.465  1033  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 18:40:06.465  1033  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 18:40:06.465  1033  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 18:40:06.466  1033  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 18:40:06.466  1033  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 18:40:06.467  1033  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 18:40:06.467  1033  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 18:40:06.467  1033  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 18:40:06.467  1033  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 18:40:06.468  1033  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 18:40:06.468  1033  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 18:40:06.468  1033  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 18:40:06.468  1033  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 18:40:06.469  1033  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 18:40:06.470  1033  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 18:40:06.470  1033  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 18:40:06.470  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-29 18:40:06.470  1941  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 18:40:06.471  1941  2296 D WfdsService: Set the WFDS Monitor: true
08-29 18:40:06.471  1941  2296 D WfdsMonitor: WfdsMonitorThread create
08-29 18:40:06.471  1941  2296 D WfdsMonitor: WFDS Monitor is created and started
08-29 18:40:06.471  1941  2296 D WfdsService: WiFi: Supplicant connection re-established
08-29 18:40:06.471  1033  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 18:40:06.471  1033  1390 D WifiNative-HAL: Setting external_sim to 1
08-29 18:40:06.471  1033  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 18:40:06.472  1033  1390 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 18:40:06.472  1033  1390 I WifiNative-HAL: startHal
08-29 18:40:06.472  1033  1390 D wifi    : setting scan oui 0xaf669c60
08-29 18:40:06.472  1033  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 18:40:06.472  1033  1390 I WifiNative-HAL: startHal
08-29 18:40:06.472  1033  1390 D wifi    : setting scan oui 0xaf669c60
08-29 18:40:06.473  1033  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 18:40:06.473  1033  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 18:40:06.473  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 18:40:06.473  1941  7158 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 18:40:06.473  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 18:40:06.474  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 18:40:06.474  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 18:40:06.474  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 18:40:06.474  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 18:40:06.474  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 18:40:06.474  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 18:40:06.474  1941  7158 E CtrlSupplicant: Succeed to open control connection
08-29 18:40:06.475  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 18:40:06.475  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 18:40:06.475  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START,
08-29 18:40:06.475  1941  7158 E CtrlSupplicant: Succeed to open monitor connection
08-29 18:40:06.475  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 18:40:06.475  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 18:40:06.476  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 18:40:06.476  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 18:40:06.476  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 18:40:06.476  7146  7146 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 18:40:06.476  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 18:40:06.476  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 18:40:06.476  1941  7158 D WfdsMonitor: Supplicant connection established
08-29 18:40:06.476  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 18:40:06.477  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 18:40:06.478  1033  1390 E WifiNative: : [121,331,867 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 18:40:06.478  1033  1390 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 18:40:06.478  1033  1390 D WifiNative-wlan0: RECONNECT: returned true
08-29 18:40:06.478  1033  1390 D WifiNative-wlan0: doString: [STATUS]
08-29 18:40:06.479  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 18:40:06.479  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 18:40:06.479  1033  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 18:40:06.479  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 18:40:06.480  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:06.481  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 18:40:06.481  1033  1033 D RttService: SCAN_AVAILABLE : 3
,08-29 18:40:06.481  1033  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.481  1033  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.481  1033  1554 I WifiNative-HAL: startHal
08-29 18:40:06.481  1033  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf669c60
08-29 18:40:06.481  1033  1554 D wifi    : failed to get capabilities : -3
08-29 18:40:06.481  1033  1554 E WifiScanningService: could not get scan capabilities
08-29 18:40:06.481  1033  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.482  1033  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 18:40:06.482  1033  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 18:40:06.483  1033  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 18:40:06.483  1033  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 18:40:06.484  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121339  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 18:40:06.485   321   900 D CommandListener: Setting iface cfg
08-29 18:40:06.485   321   900 D CommandListener: Trying to bring up p2p0
08-29 18:40:06.485  1941  2296 D WfdsService: Connected to the supplicant for wfds
08-29 18:40:06.486  1033  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 18:40:06.486  1033  1389 D LGWifiP2pService: P2pEnablingState
08-29 18:40:06.486  1033  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.486  1033  1389 D LGWifiP2pService: P2p socket connection successful
08-29 18:40:06.486  1033  1389 D LGWifiP2pService: P2pEnabledState
08-29 18:40:06.487  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 18:40:06.487  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:06.488  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:06.488  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.488  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.488  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 18:40:06.489  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:06.490  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121344  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 18:40:06.491  1033  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 18:40:06.491  1033  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 18:40:06.491  1033  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 18:40:06.491  1033  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 18:40:06.492  7146  7146 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 18:40:06.493  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-29 18:40:06.493  1033  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 18:40:06.493  1033  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 18:40:06.494  1941  1941 D WfdsService: WifiP2pState is changed : true
08-29 18:40:06.494  1033  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 18:40:06.494  1941  2296 D WfdsService: Receive the WFDS_ENABLE Method
08-29 18:40:06.494  1941  2296 D WfdsService: Set the WFDS Monitor: true
08-29 18:40:06.494  1033  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 18:40:06.494  1033  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 18:40:06.494  1941  2296 D WfdsService: Connected to the supplicant for wfds
08-29 18:40:06.494  1941  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 18:40:06.494  7146  7146 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 18:40:06.494  7146  7146 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 18:40:06.495  1941  2296 D WfdsService: selectPreferredScanChannel [36]
08-29 18:40:06.495  1941  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 18:40:06.495  1033  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 18:40:06.496  1033  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 18:40:06.496  1033  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 18:40:06.496  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 18:40:06.497  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 18:40:06.497  7146  7146 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.498  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 18:40:06.498  7146  7146 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 18:40:06.498  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.498  7146  7146 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.498  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.498  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.498  1033  7157 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.498  1033  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 18:40:06.498  1033  7157 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.498  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.498  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.499  7146  7146 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.499  1033  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 18:40:06.499  1033  7157 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.499  1033  7157 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.499  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.499  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.499  1033  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 18:40:06.499  1033  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 18:40:06.499  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 18:40:06.500  7146  7146 I wpa_supplicant: wpa_driver_nl80211_e,xt_driver_cmd SETBAND 0 - interface name wlan0
08-29 18:40:06.500  7146  7146 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:06.500  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 18:40:06.500  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:06.500  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:06.500  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:06.501  1033  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 18:40:06.501  1033  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 18:40:06.501  1033  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 18:40:06.502  1033  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 18:40:06.502  1033  1390 D WifiNative-wlan0: doBoolean: SCAN
08-29 18:40:06.502  1033  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 18:40:06.502  1033  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 18:40:06.503  1941  7158 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.503  1033  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-29 18:40:06.503  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 18:40:06.503  1033  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 18:40:06.503  1941  7158 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.503  1033  1389 D LGWifiP2pService: before postfix = G3
08-29 18:40:06.503  1033  1389 D WifiServerServiceExt: postfix byte check : 2
08-29 18:40:06.503  1033  1389 D LGWifiP2pService: after postfix = G3
08-29 18:40:06.503  1033  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 18:40:06.503  1033  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 18:40:06.504  1033  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 18:40:06.504  1033  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 18:40:06.504  1033  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 18:40:06.504  1941  1941 D WfdsService: isConnected: false
08-29 18:40:06.504  1033  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 18:40:06.504  1033  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 18:40:06.505  1033  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 18:40:06.505  1033  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-29 18:40:06.505  1033  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-29 18:40:06.506  1033  1390 D WifiNative-wlan0: SCAN: returned false
08-29 18:40:06.506  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121361  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 18:40:06.509  1033  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 18:40:06.509  1033  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 18:40:06.510  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121364  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 18:40:06.510  1033  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 18:40:06.510  1033  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 18:40:06.511  1033  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 18:40:06.511  1033  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 18:40:06.511  1033  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 18:40:06.511  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 18:40:06.511  1033  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 18:40:06.511  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 18:40:06.511  1941  1941 D WfdsService: Update P2p Interface State: 3
08-29 18:40:06.513  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:06.513  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:06.514  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:06.514  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.514  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:06.515  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 18:40:06.515  1033  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:06.516  1033  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:06.516  1033  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:06.517  1033  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:06.517  1033  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-29 18:40:06.521  1033  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 18:40:06.521  1033  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 18:40:06.521  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:06.521  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 18:40:06.521  1033  1389 D LGWifiP2pService: InactiveState
08-29 18:40:06.521  1033  1389 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.521  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.521  1033  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 18:40:06.522  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 18:40:06.522  7146  7146 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.523  1941  7158 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 18:40:06.523  1033  7157 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 18:40:06.523  7146  7146 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 18:40:06.523  1033  7157 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.523  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.523  7146  7146 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.523  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:06.523  1941  7158 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.523  1033  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 18:40:06.523  1033  1389 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.523  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  7146  7146 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1941  7158 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.524  1033  7157 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.524  1033  7157 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.524  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  7157 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  7157, E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.524  1033  7157 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.524  1033  7157 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:06.524  1033  1033 E WifiServerServiceExt: No p2p device connected
08-29 18:40:06.525  1941  2296 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 18:40:06.535  3458  3458 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 18:40:06.535  3458  3458 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:06.535  3458  3458 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 18:40:06.539  7125  7125 I HubEmail: JNI_OnLoad()
08-29 18:40:06.539  7125  7125 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 18:40:06.539  7125  7125 I HubEmail: registerNatives()
08-29 18:40:06.539  7125  7125 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 18:40:06.539  7125  7125 I HubEmail: registerNativeMethods()
08-29 18:40:06.539  7125  7125 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 18:40:06.539  7125  7125 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 18:40:06.587  1033  1049 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7164 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 18:40:06.592  7002  7160 W FormManager: Network not available. Please check & try again.
08-29 18:40:06.599  7125  7163 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:06.603  7002  7161 V FormManager: Network unavailable.
08-29 18:40:06.606  7002  7161 V FormManager: Network unavailable.
,08-29 18:40:06.620  1033  2012 I ActivityManager: Killing 6161:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-29 18:40:06.663  1033  1648 W libprocessgroup: failed to open /acct/uid_10080/pid_6161/cgroup.procs: No such file or directory
,08-29 18:40:06.674  7164  7164 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:06.674  7164  7164 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 18:40:06.677  7164  7164 D PhoneMonitor: Register our PhoneStateListener
,08-29 18:40:06.693  7164  7164 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-29 18:40:06.697  7164  7164 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 18:40:06.713  7164  7164 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-29 18:40:06.714  7164  7164 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 18:40:06.715  7164  7164 D TelephonyAutoProfiling: [parse] Load xml
08-29 18:40:06.721  7164  7164 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 18:40:06.722  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 18:40:06.723  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 18:40:06.723  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 18:40:06.723  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 18:40:06.723  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 18:40:06.723  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 18:40:06.723  7164  7164 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 18:40:06.723  7164  7164 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-29 18:40:06.737  1033  1923 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7183 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 18:40:06.737  7164  7164 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-29 18:40:06.738  1033  1923 I ActivityManager: Killing 6190:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-29 18:40:06.785  1033  2013 W libprocessgroup: failed to open /acct/uid_10097/pid_6190/cgroup.procs: No such file or directory
,08-29 18:40:07.029  1033  1923 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7201 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 18:40:07.031  1033  1923 I ActivityManager: Killing 6731:com.lge.eula/1000 (adj 15): empty #17
,08-29 18:40:07.095  1033  2013 W libprocessgroup: failed to open /acct/uid_1000/pid_6731/cgroup.procs: No such file or directory
,08-29 18:40:07.135  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 18:40:07.135  1033  7157 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-29 18:40:07.136  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 18:40:07.136  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-29 18:40:07.136  1033  7157 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 18:40:07.136  7146  7146 E wpa_supplicant: USIM:  scard_init function
08-29 18:40:07.136  7146  7146 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 18:40:07.137  1033  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 18:40:07.137  1033  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 18:40:07.137  1033  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 18:40:07.138  1033  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 18:40:07.138  1033  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 18:40:07.138  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 18:40:07.138  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 18:40:07.152  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122006  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 18:40:07.200  1033  2042 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7221 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:40:07.201  1033  2042 I ActivityManager: Killing 6750:com.lge.bnr/1000 (adj 15): empty #17
08-29 18:40:07.248  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122102  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 18:40:07.249  1033  2013 W libprocessgroup: failed to open /acct/uid_1000/pid_6750/cgroup.procs: No such file or directory
,08-29 18:40:07.253  7146  7146 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 18:40:07.254  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 18:40:07.254  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 18:40:07.254  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 18:40:07.254  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 18:40:07.254  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:07.254  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:07.258  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122112  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 18:40:07.258  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.258  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:07.258  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122113  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 18:40:07.259  1033  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122114
08-29 18:40:07.259  1033  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122114
08-29 18:40:07.260  1033  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122114
08-29 18:40:07.260  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122115
08-29 18:40:07.261  1033  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122115
08-29 18:40:07.261  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122116  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 18:40:07.262  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:07.262  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.262  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 18:40:07.263  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.267  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:07.267  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 18:40:07.271  7146  7146 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:40:07.271  7146  7146 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 18:40:07.272  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:07.272  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:07.272  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 18:40:07.272  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:40:07.272  1033  7157 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:40:07.272  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 18:40:07.272  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 18:40:07.272  1033  7157 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 18:40:07.273  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:07.273  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:07.273  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 18:40:07.273  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 18:40:07.275  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=122129  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-29 18:40:07.275  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=122130  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 18:40:07.276  1033  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122130
08-29 18:40:07.276  1033  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122131
08-29 18:40:07.277  1033  1390 D WifiNative-wlan0: doString: [STATUS]
08-29 18:40:07.279  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:07.279  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:07.279  1033  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 18:40:07.281  1033  1390 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 18:40:07.281  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.282  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.282  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 18:40:07.285  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.285  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.285  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 18:40:07.285  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:07.285  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 18:40:07.288  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.288  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:07.289  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.291  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.291  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:07.292  1033  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 18:40:07.292  1033  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 18:40:07.293  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 18:40:07.296  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.296  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.296  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 18:40:07.299  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.299  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.299  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 18:40:07.308  1033  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 18:40:07.309  1033  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:07.309  1033  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 18:40:07.309  1033  1409 D ConnectivityService: Got NetworkAgent Messenger
08-29 18:40:07.309  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 18:40:07.309  1033  1409 D ConnectivityService: NetworkAgent connected
,08-29 18:40:07.309  1033  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 18:40:07.309  1033  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 18:40:07.312  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.312  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:07.313  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.314  1033  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 18:40:07.314  1033  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:07.315  1033  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 18:40:07.315  1033  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 18:40:07.315  1033  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 18:40:07.315  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.315  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:07.317  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.318  1033  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 18:40:07.320   321   900 D CommandListener: Setting iface cfg
,08-29 18:40:07.323  7221  7221 I art     : Almond Protected OAT
08-29 18:40:07.324  1033  1390 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 18:40:07.325  1033  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122179  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:07.326  1033  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122180  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:07.326  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122181  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:07.327  1033  7245 D DhcpStateMachine: StoppedState
08-29 18:40:07.327  1033  7245 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.327  1033  7245 D DhcpStateMachine: WaitBeforeStartState
08-29 18:40:07.327  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:07.327  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 18:40:07.328  1033  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122182  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:07.328  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:07.328  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 18:40:07.328  1033  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122183  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:07.329  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122183  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:07.329  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:07.330  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:07.330  1033  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:07.331  1033  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:07.331  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-29 18:40:07.332  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 18:40:07.333  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:76468] from screen [on:0 period:-684975195] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 18:40:07.334  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-684975194] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 18:40:07.334  1033  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 18:40:07.339  1033  1409 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 18:40:07.340  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.340  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.340  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.341  1033  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.341  1033  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 18:40:07.341  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.342  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.342  1033  1409 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 18:40:07.343  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-29 18:40:07.343  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 18:40:07.343  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
08-29 18:40:07.344  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
08-29 18:40:07.344  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 18:40:07.344  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 18:40:07.344  1033  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 18:40:07.344  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 18:40:07.345  1033  1390 D WifiNative-wlan0: SET ps 0: returned true
08-29 18:40:07.345  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 18:40:07.345  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 18:40:07.345  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 18:40:07.345  1033  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11ebc080 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.346  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11ebc080 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.346  1033  7245 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.346  1033  7245 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 18:40:07.346  1033  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 18:40:07.346  1033  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 18:40:07.346  1033  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 18:40:07.349   321   900 D CommandListener: Setting iface cfg
08-29 18:40:07.349   321   900 D CommandListener: Trying to bring up wlan0
08-29 18:40:07.350  1033  1390 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 18:40:07.350  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:07.350  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 18:40:07.351  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.351  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.352  1033  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.352  1033  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.353  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.353  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:07.353  1033  1409 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 18:40:07.354  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 18:40:07.354  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 18:40:07.354  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 18:40:07.354  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 18:40:07.354  1033  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.355  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.363  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 18:40:07.363  1033  1390 D Wifi,Native-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 18:40:07.363  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 18:40:07.363  1033  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 18:40:07.363  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
,08-29 18:40:07.377  7221  7221 D WeatherApplication: removeAccount,
08-29 18:40:07.378  7221  7221 D WeatherApplication: Account.length = 0
,08-29 18:40:07.378  7221  7221 E WeatherApplication: OPERATOR:OPEN
,08-29 18:40:07.379  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:07.380  1033  1409 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 18:40:07.380  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 18:40:07.381  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 18:40:07.381  1033  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-29 18:40:07.381  1033  1409 D ConnectivityService: ignoring duplicate network state non-change
08-29 18:40:07.383  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:7
08-29 18:40:07.386  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.386  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:07.387  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 18:40:07.387  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-29 18:40:07.389  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.389  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 18:40:07.392  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-29 18:40:07.392  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.392  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.392  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 18:40:07.393  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 18:40:07.394  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 18:40:07.394  1033  1409 D ConnectivityService: Adding iface wlan0 to network 101
08-29 18:40:07.399  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.399  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.399  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 18:40:07.400  1033  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 18:40:07.402  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 18:40:07.404  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 18:40:07.406  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.406  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.406  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 18:40:07.406  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 18:40:07.407  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 18:40:07.407  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 18:40:07.407  7221  7221 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-29 18:40:07.408  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.408  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:07.408  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 18:40:07.413  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.413  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:07.415  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 18:40:07.417  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.417  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 18:40:07.418  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.423  1033  1409 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 18:40:07.423  1033  1409 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 18:40:07.424  1033  1409 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 18:40:07.425  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:07.425  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 18:40:07.425  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.425   321   900 E Netd    : netlink response contains error (File exists)
08-29 18:40:07.425  1033  1409 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 18:40:07.426  1033  1409 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 18:40:07.426  1033  1409 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 18:40:07.426  1033  1409 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 18:40:07.431  1033  1409 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 18:40:07.431  1033  1409 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:07.431  1033  1409 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:07.432  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.432  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 18:40:07.432  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.432  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 18:40:07.432  1033  1409 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 18:40:07.433  1033  1409 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:07.433  1033  1409 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:07.433  1033  1409 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 18:40:07.433  1033  1409 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:07.433  1033  1409 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 18:40:07.433  1033  1409 D ConnectivityService: currentScore = 0, newScore = 20
08-29 18:40:07.433  1033  1409 D ConnectivityService:    accepting network in place of null
08-29 18:40:07.433  1033  1409 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:07.434  1033  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:07.434  1033  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:07.434  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:07.434   321  7250 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 18:40:07.434  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 18:40:07.435  1033  1409 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 18:40:07.435  1033  1409 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIF,I () - 101] isDefaultNetwork=true
08-29 18:40:07.435  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:40:07.435  1033  1409 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:07.435  1033  1409 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 18:40:07.436  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 18:40:07.436  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 18:40:07.436  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 18:40:07.436  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 18:40:07.436  1033  1409 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 18:40:07.437  1033  1409 D ConnectivityService: validation of new default Network = false
08-29 18:40:07.437  1033  1409 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 18:40:07.437  1033  1409 D DSQN    : enableDataServiceNotify 
08-29 18:40:07.437  1033  1409 D DSQN    : start dsqn bin
,08-29 18:40:07.446  1033  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 18:40:07.449  1033  1409 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:07.449  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:07.449  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:07.449  1033  1409 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:07.432  7251  7251 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:07.432  7251  7251 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:07.450  1601  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 18:40:07.461  7251  7251 E DSQN    : DSQN ssw
08-29 18:40:07.465  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 18:40:07.465  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:7
,08-29 18:40:07.504  1033  1729 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7256 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 18:40:07.505  1033  1729 I ActivityManager: Killing 2168:com.lge.music/u0a34 (adj 15): empty #17
,08-29 18:40:07.522   325  2163 V AudioFlinger: 2168 died, releasing its sessions
,08-29 18:40:07.522   325  2163 V AudioFlinger:  pid 1852 @ 0
08-29 18:40:07.522   325  2163 V AudioFlinger:  pid 3458 @ 1
08-29 18:40:07.522   325  2163 V AudioFlinger:  pid 3458 @ 2
,08-29 18:40:07.544  1033  2012 W libprocessgroup: failed to open /acct/uid_10034/pid_2168/cgroup.procs: No such file or directory
,08-29 18:40:07.545  1816  7255 I CheckinService: active receiver: enabled
08-29 18:40:07.548  1033  7245 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 18:40:07.549  1033  7245 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 18:40:07.549  1033  7245 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 18:40:07.532  7273  7273 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:07.532  7273  7273 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:07.560  1816  7255 I CheckinService: Preparing to send checkin request
08-29 18:40:07.560  1816  7255 I EventLogService: Accumulating logs since 1472488742146
,08-29 18:40:07.564  7273  7273 I dhcpcd  : version 5.5.6 starting
08-29 18:40:07.567  7273  7273 E dhcpcd  : get_duid: m
08-29 18:40:07.567  7273  7273 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 18:40:07.567  7273  7273 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 18:40:07.582  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-29 18:40:07.583  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.584  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:07.607  1816  7255 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-29 18:40:07.638  7273  7273 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 18:40:07.638  7273  7273 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 18:40:07.638  7273  7273 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 18:40:07.639  7273  7273 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 18:40:07.639  7273  7273 D dhcpcd  : wlan0: sending REQUEST (xid 0xa8e1003c), next in 4.86 seconds
08-29 18:40:07.679  7273  7273 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 18:40:07.681   281   359 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 18:40:07.681   281   359 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 18:40:07.681   281   359 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 18:40:07.682  7256  7282 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 18:40:07.693  7273  7273 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 18:40:07.693  7273  7273 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 18:40:07.693  7273  7273 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 18:40:07.693  7273  7273 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-29 18:40:07.693  7273  7273 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 18:40:07.693   281   359 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 18:40:07.693   281   359 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 18:40:07.693   281   359 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 18:40:07.693  7273  7273 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 18:40:07.694  7273  7273 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 18:40:07.694  7273  7273 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 18:40:07.694  7256  7282 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 18:40:07.702   281   359 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 18:40:07.702   281   359 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 18:40:07.702   281   359 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 18:40:07.703  7256  7286 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 18:40:07.705   281   359 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 18:40:07.705   281   359 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 18:40:07.705   281   359 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 18:40:07.705  1033  1389 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.705  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.705  1033  1389 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:07.706  7256  7286 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-29 18:40:07.715  1033  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 18:40:07.715  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 18:40:07.716  1033  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 18:40:07.716  1033  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 18:40:07.717  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 18:40:07.717  1033  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 18:40:07.726  1033  2042 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7290 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-29 18:40:07.747   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 22.176ms
,08-29 18:40:07.767   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 19.452ms
,08-29 18:40:07.783  7290  7290 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 18:40:07.783  7290  7290 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-29 18:40:07.785   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 290us total 17.262ms
,08-29 18:40:07.803  7290  7290 I MultiDex: VM with version 2.1.0 has multidex support
08-29 18:40:07.803  7290  7290 I MultiDex: install
08-29 18:40:07.803  7290  7290 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 18:40:07.811  7290  7290 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-29 18:40:07.935  7256  7256 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 18:40:07.943  7256  7256 I LibraryLoader: Loading: webviewchromium
08-29 18:40:07.946  7256  7256 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2810-2813)
,08-29 18:40:07.947  7256  7256 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 18:40:07.951  7256  7256 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2acbf8d9}
,08-29 18:40:07.952  7256  7256 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 18:40:07.952  7256  7256 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 18:40:07.954  1033  7245 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 18:40:07.956  1033  7245 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 18:40:07.957  1033  7245 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 18:40:07.957  1033  7245 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 18:40:07.957  1033  7245 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 18:40:07.957  1033  7245 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 18:40:07.957  1033  7245 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,08-29 18:40:07.958  1033  7245 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-29 18:40:07.961  1033  7245 D DhcpStateMachine: RunningState
08-29 18:40:07.965  7256  7256 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 18:40:07.968  7256  7256 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 18:40:07.991  7256  7256 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 18:40:07.993  7256  7256 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-29 18:40:07.994  7256  7256 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-29 18:40:07.997   325   325 V AudioPolicyService: registerClient() client 0xb101ebe0, uid 10093
08-29 18:40:07.998  7256  7345 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 18:40:08.014  7256  7256 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 18:40:08.014  7256  7256 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 18:40:08.014  7256  7256 I Adreno-EGL: Build Date: 12/12/14 금
08-29 18:40:08.014  7256  7256 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 18:40:08.014  7256  7256 I Adreno-EGL: Remote Branch: 
08-29 18:40:08.014  7256  7256 I Adreno-EGL: Local Patches: 
08-29 18:40:08.014  7256  7256 I Adreno-EGL: Reconstruct Branch: 
,08-29 18:40:08.094  7256  7256 I NSApplication: Starting up...
,08-29 18:40:08.131   321  7250 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 18:40:08.189  1033  1048 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7361 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 18:40:08.190  1033  1048 I ActivityManager: Killing 6123:com.android.vending/u0a44 (adj 15): empty #17
,08-29 18:40:08.235  1033  1772 W libprocessgroup: failed to open /acct/uid_10044/pid_6123/cgroup.procs: No such file or directory
,08-29 18:40:08.330  7378  7378 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 18:40:08.404  7378  7378 I dex2oat : dex2oat took 70.682ms (threads: 4)
,08-29 18:40:08.420  7290  7308 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 18:40:08.420  7290  7308 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 18:40:08.420  7290  7308 I Adreno-EGL: Build Date: 12/12/14 금
08-29 18:40:08.420  7290  7308 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 18:40:08.420  7290  7308 I Adreno-EGL: Remote Branch: 
08-29 18:40:08.420  7290  7308 I Adreno-EGL: Local Patches: 
08-29 18:40:08.420  7290  7308 I Adreno-EGL: Reconstruct Branch: 
,08-29 18:40:08.424  1033  1048 I art     : Explicit concurrent mark sweep GC freed 97803(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.161ms total 174.576ms
,08-29 18:40:08.442  7361  7361 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 18:40:08.450  1033  1409 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-29 18:40:08.496   321  7250 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 18:40:08.502  1033  1772 D WifiServiceImplEx: setWifiEnabled: false pid=6657, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 18:40:08.503  1033  1772 D WifiService: setWifiEnabled: false pid=6657, uid=10118
08-29 18:40:08.503  1033  1772 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 18:40:08.517  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:08.518  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:08.518  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 18:40:08.519  1033  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:08.519  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:08.520  1033  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:08.520  1033  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:08.521  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 18:40:08.521  1033  1390 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 18:40:08.521  1033  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:08.521  1033  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 18:40:08.521  1033  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 18:40:08.521  1033  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 18:40:08.529  1033  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 18:40:08.529  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 18:40:08.529  1033  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.529  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 18:40:08.529  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.530  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 18:40:08.530  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 18:40:08.531  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:08.531  1033  7245 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.531   321   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:08.545  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.ConnectException: failed to connect to clients3.google.com/2a00:1450:4001:81c::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-29 18:40:08.561  1033  1389 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.561  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.561  1033  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@eac20a4
08-29 18:40:08.561  1033  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:08.561  1033  1389 D LGWifiP2pService: P2pDisablingState
08-29 18:40:08.562  1033  1389 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.562  1033  1389 D LGWifiP2pService: p2p socket connection lost
08-29 18:40:08.562  1033  1389 D LGWifiP2pService: P2pDisabledState
08-29 18:40:08.562  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 18:40:08.562  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:08.563  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 18:40:08.563  1033  1409 D ConnectivityService: ignoring duplicate network state non-change
08-29 18:40:08.563  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-29 18:40:08.572  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:08.572  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:08.573  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 18:40:08.574  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 18:40:08.575  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.575  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.575  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 18:40:08.575  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 18:40:08.575  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.576  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.576  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 18:40:08.576  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 18:40:08.576  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-29 18:40:08.576  1033  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.580  1033  1555 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.582  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-29 18:40:08.586  1941  1941 D WfdsService: WifiP2pState is changed : false
08-29 18:40:08.587  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:08.587  1941  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 18:40:08.587  1941  2296 D WfdsService: Set the WFDS Monitor: false
08-29 18:40:08.587  1941  2296 D WfdsMonitor: WFDS Monitor is stopped
08-29 18:40:08.588  1941  2296 D WfdsService: STATE : WfdsDisabledState - enter
08-29 18:40:08.588  1941  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 18:40:08.588  1941  7158 D CtrlSupplicant: Received on exit socket, terminate
08-29 18:40:08.588  1941  7158 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 18:40:08.588  1033  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:08.588  1941  7158 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 18:40:08.588  1941  7158 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 18:40:08.588  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:08.589  1941  2296 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 18:40:08.589  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:08.589  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:08.589  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:08.589  1033  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 18:40:08.590  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:08.596  1033  1389 D LGWifiP2pService: P2pDisabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.597  1033  1389 D LGWifiP2pService: DefaultState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.597  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 18:40:08.597  7146  7146 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 18:40:08.597  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 18:40:08.598  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 18:40:08.598  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:08.600  7290  7308 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 18:40:08.600  7290  7308 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 18:40:08.600  7290  7308 I Adreno-EGL: Build Date: 12/12/14 금
08-29 18:40:08.600  7290  7308 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 18:40:08.600  7290  7308 I Adreno-EGL: Remote Branch: 
08-29 18:40:08.600  7290  7308 I Adreno-EGL: Local Patches: 
08-29 18:40:08.600  7290  7308 I Adreno-EGL: Reconstruct Branch: 
,08-29 18:40:08.629   321   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:08.629  1033  1409 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 18:40:08.629  1033  1409 D DSQN    : disableDataServiceNotify
08-29 18:40:08.629  1033  1409 D DSQN    : stop dsqn bin
,08-29 18:40:08.632  1033  1390 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 18:40:08.632  1033  1390 D WifiNative-p2p0: TERMINATE: returned true
08-29 18:40:08.632  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:08.632  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:08.632  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 18:40:08.632  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 18:40:08.635  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.635  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.635  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 18:40:08.635  1033  1409 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:08.636  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 18:40:08.636  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:08.636  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:08.636  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:08.636  1033  1390 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 18:40:08.636  1033  1409 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:08.636  1033  1409 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 18:40:08.636  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.636  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.636  1033  7244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 18:40:08.636  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:08.637  1033  1409 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 18:40:08.637  1033  1409 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 18:40:08.637  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:40:08.637  1033  1409 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:08.637  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:40:08.637  1601  1826 D ConnectivityManager.Cal,lbackHandler: CM callback handler got msg 524292
08-29 18:40:08.637  1033  1409 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:08.638  1033  1409 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:08.638  1033  1409 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:08.638  1033  1409 D NetworkManagementService: Removing idletimer
08-29 18:40:08.638  1033  1409 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.638  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:08.638  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 18:40:08.639  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 18:40:08.640  1033  1390 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:08.640  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:08.640  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:08.640  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:08.640  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:08.641  1033  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 18:40:08.643  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:08.643  1033  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:08.643  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:08.643  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:08.643  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:08.644  1033  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 18:40:08.646  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 18:40:08.646  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:08.646  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 18:40:08.646  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 18:40:08.647  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 18:40:08.647  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 18:40:08.647  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 18:40:08.647  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 18:40:08.647  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 18:40:08.647  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 18:40:08.647  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-29 18:40:08.657  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 18:40:08.676  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 18:40:08.677  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:08.678  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 18:40:08.691  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 18:40:08.692  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:08.692  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:08.744  7146  7146 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 18:40:08.744  7146  7146 I wpa_supplicant: monitor socket send errors count : 1
08-29 18:40:08.744  7146  7146 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
,08-29 18:40:08.747  1033  7245 D DhcpStateMachine: StoppedState
08-29 18:40:08.747  1033  7245 D DhcpStateMachine: StoppedState{ when=-149ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:08.747  1033  1390 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 18:40:08.748  1033  1390 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 18:40:08.748  1033  7157 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 18:40:08.748  1033  7157 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 18:40:08.750  7290  7308 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 18:40:08.750  7290  7308 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 18:40:08.750  7290  7308 I Adreno-EGL: Build Date: 12/12/14 금
08-29 18:40:08.750  7290  7308 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 18:40:08.750  7290  7308 I Adreno-EGL: Remote Branch: 
08-29 18:40:08.750  7290  7308 I Adreno-EGL: Local Patches: 
08-29 18:40:08.750  7290  7308 I Adreno-EGL: Reconstruct Branch: 
08-29 18:40:08.770  7146  7146 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 18:40:08.770  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 18:40:08.770  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 18:40:08.770  1033  7157 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 18:40:08.771  1033  7157 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 18:40:08.771  7146  7146 W wpa_supplicant: USIM:  scard_deinit function
08-29 18:40:08.771  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:08.771  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:08.771  1033  1095 D Tethering: InitialState.processMessage what=4
08-29 18:40:08.771  1033  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123626
08-29 18:40:08.772  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 18:40:08.772  1033  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123626
08-29 18:40:08.772  1033  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123627  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 18:40:08.773  1033  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123627  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 18:40:08.774  1033  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:08.775  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:08.790  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 18:40:08.793  6459  6500 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 18:40:08.803  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:08.819  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 18:40:08.819  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:08.819  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 18:40:08.819  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 18:40:08.821  7092  7092 I AppUp4:CustModeStarterReceiver: onReceive
08-29 18:40:08.824  7092  7092 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1038c616
08-29 18:40:08.824  7092  7092 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 18:40:08.824  7092  7092 D AppUp4:CustFacade: isPhone : true
08-29 18:40:08.825  7092  7092 D AppUp4:CustModeStarterReceiver: begin check event
08-29 18:40:08.825  7092  7092 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 18:40:08.828  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:08.828  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 18:40:08.830  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:08.832  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 18:40:08.838  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 18:40:08.839  7290  7308 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:08.840  4362  7407 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 18:40:08.840  7290  7308 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 18:40:08.842  4362  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:08.842  4362  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 18:40:08.854  7125  7411 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.866  3458  3458 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-29 18:40:08.866  3458  3458 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:08.867  3458  3458 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 18:40:08.869  7164  7164 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 18:40:08.869  7164  7164 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 18:40:08.874  7146  7146 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 18:40:08.874  1033  7157 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 18:40:08.874  1033  7157 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 18:40:08.874  1033  7157 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 18:40:08.875  1033  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-29 18:40:08.876  7002  7415 W FormManager: Network not available. Please check & try again.
08-29 18:40:08.879  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:8
,08-29 18:40:08.884  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 18:40:08.884  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-29 18:40:08.885  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 18:40:08.885  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-29 18:40:08.885  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@283a9184
08-29 18:40:08.886  7002  7416 V FormManager: Network unavailable.
08-29 18:40:08.887  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 18:40:08.887  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 18:40:08.887  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 18:40:08.887  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 18:40:08.887  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:8
08-29 18:40:08.892  7002  7416 V FormManager: Network unavailable.
,08-29 18:40:08.905  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 18:40:08.905  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 18:40:08.906  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 18:40:08.906  6895  6895 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 18:40:08.906  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 18:40:08.906  6895  6895 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 18:40:08.906  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 18:40:08.906  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 18:40:08.906  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 18:40:08.907  6895  6895 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 18:40:08.907  6895  6895 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 18:40:08.913  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:08.916  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:08.923  7002  7418 W FormManager: Network not available. Please check & try again.
08-29 18:40:08.924  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:08.925  7002  7419 V FormManager: Network unavailable.
08-29 18:40:08.931  7002  7419 V FormManager: Network unavailable.
,08-29 18:40:08.943  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:08.947  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:08.952  7002  7421 W FormManager: Network not available. Please check & try again.
08-29 18:40:08.956  7002  7422 V FormManager: Network unavailable.
08-29 18:40:08.957  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:08.961  7002  7422 V FormManager: Network unavailable.
,08-29 18:40:08.972  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 18:40:08.972  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 18:40:08.974  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:08.976  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:08.978  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-29 18:40:08.978  1941  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 18:40:08.978  1941  2296 D WfdsService: Set the WFDS Monitor: false
08-29 18:40:08.978  1941  2296 D WfdsMonitor: WFDS Monitor is stopped
08-29 18:40:08.981  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:08.982  1033  1390 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 18:40:08.982  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:08.982  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:08.982  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 18:40:08.983  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:08.983  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 18:40:08.984  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 18:40:08.984  1033  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 18:40:08.984  1033  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 18:40:08.985  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:08.985  2485  2485 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:08.987  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:08.992  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 18:40:09.002  4362  7423 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 18:40:09.008  4362  7424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 18:40:09.008  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.008  4362  7424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 18:40:09.015  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.015  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:09.016  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 18:40:09.021   321  7426 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 18:40:09.021  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 18:40:09.021  1816  7255 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-29 18:40:09.068  1033  1573 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7427 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 18:40:09.083  1816  7255 I CheckinService: active receiver: disabled
,08-29 18:40:09.237  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-29 18:40:09.238  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-29 18:40:09.241  7427  7427 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 18:40:09.241  7427  7427 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 18:40:09.246  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
08-29 18:40:09.246  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-29 18:40:09.247  1033  1402 D WifiController: battery changed pluggedType: 2
,08-29 18:40:09.249  1941  2092 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-29 18:40:09.249  1941  2092 D LEDHandler: Battery Level Remaining: 100%
08-29 18:40:09.249  1941  2092 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
08-29 18:40:09.251  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-29 18:40:09.254  7427  7427 V [BNRBootReceiver]: Boot Receiver Return
,08-29 18:40:09.258  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:09.263  7427  7427 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 18:40:09.266  7427  7427 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 18:40:09.267  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.273  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:09.279  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 18:40:09.280  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:09.282  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 18:40:09.285  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 18:40:09.288  6895  6895 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 18:40:09.291  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:09.299  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.305  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.311  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.311  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.313  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:09.317  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:09.328  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.336  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.345  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.346  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:09.346  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:09.350  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:09.359  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.369  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.377  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.378  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.379  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 18:40:09.386  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:09.399  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.408  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.419  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.419  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.420  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 18:40:09.424  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:09.434  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.444  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:09.456  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.456  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.457  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 18:40:09.472  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:09.491  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.500  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:09.511  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.512  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:09.520  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:09.526  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:09.540  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.553  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.565  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 18:40:09.565  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.567  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:09.574  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:09.585  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 18:40:09.599  1033  1402 D WifiService: New client listening to asynchronous messages
,08-29 18:40:09.600  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:09.608  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.619  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:09.632  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.634  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.635  6964  6964 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 18:40:09.637  6964  6964 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 18:40:09.638  6964  6964 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 18:40:09.648  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:09.659  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 18:40:09.662  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 18:40:09.669  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.683  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.695  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.695  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:09.699  6964  6964 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 18:40:09.700  6964  6964 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 18:40:09.701  6964  6964 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 18:40:09.706  1033  1772 I ActivityManager: Killing 6913:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-29 18:40:09.738  1033  1648 W libprocessgroup: failed to open /acct/uid_10037/pid_6913/cgroup.procs: No such file or directory
,08-29 18:40:09.744  2193  2193 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 18:40:09.765  2193  2193 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 18:40:09.768  2193  2193 D c       : Getting all permits...
08-29 18:40:09.768  2193  2193 D a       : Opening database...
08-29 18:40:09.779  2193  2193 D a       : Opening database auth.proximity.permit_store...
,08-29 18:40:09.781  2193  2193 D a       : Closing database...
08-29 18:40:09.796  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:09.801  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 18:40:09.801  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 18:40:09.802  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:09.805  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.813  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.822  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.822  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.824  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 18:40:09.829  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:09.835  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 18:40:09.835  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 18:40:09.836  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:09.843  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.854  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.866  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.867  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 18:40:09.869  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 18:40:09.876  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:09.882  6932  6932 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 18:40:09.882  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 18:40:09.882  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:09.890  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:09.903  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.912  6781  7077 D UEI.SmartControl: Internal timer expired: 2
08-29 18:40:09.912  6781  7077 D UEI.SmartControl: unbind internal service
,08-29 18:40:09.918  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:09.919  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:09.922  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 18:40:09.941  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 18:40:09.947  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 18:40:09.955  7002  7452 W FormManager: Network not available. Please check & try again.
,08-29 18:40:09.962  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:09.980  7002  7453 V FormManager: Network unavailable.
,08-29 18:40:09.985  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 18:40:09.986  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 18:40:09.989  7002  7453 V FormManager: Network unavailable.
08-29 18:40:09.991  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:09.995  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 18:40:10.010  6932  6932 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 18:40:10.010  6932  6932 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 18:40:10.010  6932  6932 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 18:40:10.013  4362  7456 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 18:40:10.014  4362  7456 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 18:40:10.015  4362  7454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 18:40:10.017  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:10.023  7002  7457 W FormManager: Network not available. Please check & try again.
,08-29 18:40:10.026  7002  7458 V FormManager: Network unavailable.
08-29 18:40:10.029  7002  7458 V FormManager: Network unavailable.
08-29 18:40:10.030  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:10.047  2193  2193 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 18:40:10.068  6781  7074 D serial_port: close(fd = 24)
,08-29 18:40:10.071  6781  7074 I UEI.SmartControl: Serial port is closed.
,08-29 18:40:10.343  1033  1390 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-684972185] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 18:40:10.356  1033  1390 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-684972172] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 18:40:10.437  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:10.444  1033  1095 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:10.449  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:10.452  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:10.459  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:10.461  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 18:40:10.463  6459  6500 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 18:40:10.473  5809  5809 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 18:40:10.491  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:10.509  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 18:40:10.509  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:10.509  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 18:40:10.509  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 18:40:10.514  7092  7092 I AppUp4:CustModeStarterReceiver: onReceive
08-29 18:40:10.517  7092  7092 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1038c616
08-29 18:40:10.517  7092  7092 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 18:40:10.517  7092  7092 D AppUp4:CustFacade: isPhone : true
08-29 18:40:10.518  7092  7092 D AppUp4:CustModeStarterReceiver: begin check event
08-29 18:40:10.518  7092  7092 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 18:40:10.523  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:10.523  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 18:40:10.524  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 18:40:10.530  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:10.538  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 18:40:10.568  3458  3458 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 18:40:10.568  3458  3458 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:10.568  3458  3458 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 18:40:10.568  3458  3458 D PhoneState: setPdpRejectCasuse : false
,08-29 18:40:10.574  7164  7164 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-29 18:40:10.574  7164  7164 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 18:40:10.593  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:10
,08-29 18:40:10.595  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:10.598  4362  7467 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 18:40:10.603  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 18:40:10.603  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-29 18:40:10.603  7125  7466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:10.604  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 18:40:10.604  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-29 18:40:10.604  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@283a9184
08-29 18:40:10.605  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 18:40:10.605  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 18:40:10.605  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 18:40:10.605  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 18:40:10.605  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:10
08-29 18:40:10.605  4362  7484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:10.605  4362  7484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 18:40:10.621  7002  7482 W FormManager: Network not available. Please check & try again.
,08-29 18:40:10.625  7002  7483 V FormManager: Network unavailable.
,08-29 18:40:10.628  7002  7483 V FormManager: Network unavailable.
,08-29 18:40:11.521  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 18:40:11.522  1033  1048 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 18:40:11.554  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:11.554  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:11.554  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 18:40:11.555  1033  1095 D BluetoothManagerService: Message: 1
08-29 18:40:11.555  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 18:40:11.584  1033  1095 D BluetoothManagerService: Message: 20
08-29 18:40:11.585  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@101fb479:true
,08-29 18:40:11.588  7037  7037 D BluetoothAdapterState: make
08-29 18:40:11.593  7037  7037 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 18:40:11.594  7037  7037 I bluedroid-qcom: init
08-29 18:40:11.595  7037  7499 I BluetoothAdapterState: Entering OffState
08-29 18:40:11.595  7037  7037 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 18:40:11.596  7037  7037 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 18:40:11.596  7037  7037 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 18:40:11.596  7037  7037 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 18:40:11.596  7037  7037 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 18:40:11.598  7037  7037 I bluedroid-qcom: get_profile_interface socket
08-29 18:40:11.598  7037  7037 I bluedroid-qcom: get_profile_interface map_client
,08-29 18:40:11.602  7037  7503 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 18:40:11.592  7502  7502 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:11.606  7037  7503 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 18:40:11.592  7502  7502 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:11.616  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 18:40:11.616  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 18:40:11.622  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 18:40:11.622  7502  7502 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 18:40:11.622  7502  7502 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 18:40:11.623  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 18:40:11.623  1033  1095 D BluetoothManagerService: Message: 40
08-29 18:40:11.624  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 18:40:11.624  7037  7053 I bluedroid-qcom: config_hci_snoop_log
08-29 18:40:11.626  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 18:40:11.626  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 18:40:11.627  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 18:40:11.632  7502  7502 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 18:40:11.632  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-29 18:40:11.638  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:11.649  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:11.652  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:11.652  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:11.662  7037  7499 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-29 18:40:11.664  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-29 18:40:11.664  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-29 18:40:11.665  7037  7503 D BluetoothAdapterProperties: Name is: G3
08-29 18:40:11.667  7037  7499 D BluetoothAdapterProperties: Setting state to 11
08-29 18:40:11.667  7037  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 18:40:11.668  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:11.668  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 18:40:11.668  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 18:40:11.669  7037  7499 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 18:40:11.689  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:11.689  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:11.693  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:11.696  5809  5809 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 18:40:11.696  7037  7499 D BluetoothBondStateMachine: make
08-29 18:40:11.698  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED,
08-29 18:40:11.699  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 18:40:11.700  6895  6895 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 18:40:11.701  7037  7518 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 18:40:11.701  7037  7499 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:11.701  7037  7499 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 18:40:11.701  7037  7499 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:11.701  7037  7499 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 18:40:11.702  7037  7499 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 18:40:11.702  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:11.704  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:11.704  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 18:40:11.706  6459  6500 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 18:40:11.708  7037  7037 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 18:40:11.709  7037  7037 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:11.709  7037  7037 V BluetoothPbapReceiver: ***********state = 11
08-29 18:40:11.712  7037  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:11.715  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:11.715  5809  5809 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 18:40:11.728  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:11.729  7037  7037 D HeadsetService: Received start request. Starting profile...
08-29 18:40:11.729  7037  7037 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 18:40:11.730  7037  7037 D LGBluetoothHfpAdapter: Version 1.6
08-29 18:40:11.732  7037  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:11.734  7037  7037 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 18:40:11.735  7037  7037 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 18:40:11.735  7037  7037 D HeadsetStateMachine: make
08-29 18:40:11.742  7037  7499 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 18:40:11.776  7037  7037 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:11.776  7037  7037 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:40:11.787  1033  1976 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7523 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 18:40:11.791  7037  7037 D HeadsetStateMachine: max_hf_connections = 1
08-29 18:40:11.791  7037  7037 I bluedroid-qcom: get_profile_interface handsfree
08-29 18:40:11.793  7037  7037 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 18:40:11.795   325  1400 V AudioPolicyService: registerClient() client 0xb101ef60, uid 1002
,08-29 18:40:11.795  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:11.795  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:11.801   325  2163 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 18:40:11.801   325  2163 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 18:40:11.801   325  2163 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 18:40:11.801  7037  7037 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 18:40:11.802  7037  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:11.802   325  2172 V AudioFlinger: registerClient() client 0xb5581808, pid 7037
08-29 18:40:11.803   325  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:11.803   325  1395 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:11.803  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:11.803  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:11.803  7037  7037 V ToneGenerator: Create Track: 0xb4928080
08-29 18:40:11.803  7037  7037 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 18:40:11.803  7037  7037 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 18:40:11.804  1852  4018 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:11.804  1852  4018 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:11.804   325  1401 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 18:40:11.804   325  1401 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 18:40:11.804   325  1401 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 18:40:11.804   325  1401 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 18:40:11.804  7037  7037 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 18:40:11.804  1033  1953 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:11.804  1033  1953 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:11.805   325  2163 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 18:40:11.806   325  2172 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,08-29 18:40:11.806   325  2172 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 18:40:11.806   325  2172 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 18:40:11.806   325  2172 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 18:40:11.806  3458  3474 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:11.806  3458  3474 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:11.811   325  1396 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:11.811   325  1396 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:11.811  7037  7053 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:11.811  7037  7053 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 18:40:11.811  7037  7037 V AudioSystem: getLatency() output 2, latency 50
08-29 18:40:11.812  3458  3474 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:11.812  7037  7037 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 18:40:11.812  3458  3474 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:11.812  7037  7037 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 18:40:11.812  7037  7053 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:11.812  1033  2042 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:11.812  1033  2042 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:11.812  7037  7053 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 18:40:11.812  1601  2103 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:11.812  1601  2103 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:11.812   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 18:40:11.812   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 18:40:11.812   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 18:40:11.812   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 18:40:11.812   325   325 V AudioFlinger: createTrack() lSessionId: 20
08-29 18:40:11.813  7037  7037 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 18:40:11.814   325   325 V AudioFlinger: acquiring 20 from 7037, for 7037
08-29 18:40:11.814   325   325 V AudioFlinger:  added new entry for 20
08-29 18:40:11.814  7037  7037 V ToneGenerator: ToneGenerator INIT OK, time: 126681
08-29 18:40:11.814  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:11.816  7037  7522 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 18:40:11.816  7037  7522 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 18:40:11.816  7037  7522 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 18:40:11.816  7037  7522 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 18:40:11.816   325  1401 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7037
08-29 18:40:11.818  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:11.818  1852  2461 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:11.818  1852  2461 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:11.820  7037  7037 D A2dpService: Received start request. Starting profile...
08-29 18:40:11.821  7037  7037 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 18:40:11.822  7037  7499 E BluetoothAdapterService: File transfer profiles, supported!!
08-29 18:40:11.822  7037  7037 V Avrcp   : make
,08-29 18:40:11.823  7037  7037 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 18:40:11.823  7037  7037 I bluedroid-qcom: get_profile_interface avrcp
08-29 18:40:11.824   325  1401 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 18:40:11.825   325  1401 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 18:40:11.825   325  1401 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 18:40:11.825   325  1401 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 18:40:11.825   325  1401 V voice   : voice_set_parameters: exit with code(0)
08-29 18:40:11.825   325  1401 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 18:40:11.825   325  1401 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 18:40:11.825   325  1401 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 18:40:11.825   325  1401 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 18:40:11.825   325  1401 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 18:40:11.825   325  1401 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 18:40:11.827  7037  7522 V ToneGenerator: ToneGenerator destructor
08-29 18:40:11.827  7037  7522 V ToneGenerator: stopTone
08-29 18:40:11.827  7037  7522 V ToneGenerator: Delete Track: 0xb4928080
08-29 18:40:11.827  7037  7522 V AudioTrack: ~AudioTrack, releasing session id from 7037 on behalf of 7037
08-29 18:40:11.827   325  2163 V AudioFlinger: releasing 20 from 7037 for 7037
08-29 18:40:11.827   325  2163 V AudioFlinger:  decremented refcount to 0
08-29 18:40:11.827   325  2163 V AudioFlinger: purging stale effects
08-29 18:40:11.828   325  2163 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 18:40:11.828   325  2163 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 18:40:11.828   325  1226 V AudioPolicyService: AudioCommandThread() waking up
08-29 18:40:11.829   325  1226 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 18:40:11.829   325  1226 V AudioPolicyManager: releaseOutput() 2
08-29 18:40:11.829   325  1226 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 18:40:11.829   325  2163 V AudioFlinger: PlaybackThread::Track destructor
08-29 18:40:11.829   325  2163 V AudioFlinger: removeClient_l() pid 7037, calling pid 325
08-29 18:40:11.829  7037  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:11.830  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:11.834  7037  7499 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 18:40:11.835  7037  7037 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 18:40:11.837  7037  7037 E AudioManager: No RCC entry present to update
08-29 18:40:11.837  7037  7037 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 18:40:11.841  7037  7037 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 18:40:11.842  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 18:40:11.842  7037  7037 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 18:40:11.848  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 18:40:11.852  7037  7499 V LGMDMManager: Create singleton instance
08-29 18:40:11.854  7037  7499 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 18:40:11.906  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-29 18:40:11.911  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:11.911  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 18:40:11.911  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 18:40:11.917  7092  7092 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 18:40:11.929  7092  7092 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1038c616
08-29 18:40:11.929  7092  7092 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 18:40:11.929  7092  7092 D AppUp4:CustFacade: isPhone : true
08-29 18:40:11.930  7092  7092 D AppUp4:CustModeStarterReceiver: begin check event
08-29 18:40:11.930  7092  7092 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 18:40:11.939  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:11.940  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 18:40:11.947  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:11.950  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:11.967  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 18:40:11.973  4362  7545 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 18:40:11.987  7523  7523 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 18:40:11.987  7523  7523 W LG Account v2.2: No ProfileInfo entries
08-29 18:40:11.987  7523  7523 I LG Account v2.2: isEnabled: false
,08-29 18:40:11.988  7523  7523 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 18:40:11.988  7125  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:11.990  4362  7546 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:11.990  4362  7546 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Country: EU
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Operator: OPEN
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Ranking support: false
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Comfort support: false
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Accessory: true
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Health device: true
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Extra Pedometer: false
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Blood glucose device: false
08-29 18:40:11.991  7523  7523 I Feature : [Lifetracker]Device Number: 3
08-29 18:40:12.001  1033  1904 V SIM_STK : Menu title from STK is T-Mobile
08-29 18:40:12.002  1033  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-29 18:40:12.007  7002  7551 W FormManager: Network not available. Please check & try again.
08-29 18:40:12.016  6895  6895 D BluetoothPermissionRequest: onReceive
,08-29 18:40:12.020  3458  3458 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 18:40:12.020  3458  3458 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:12.020  3458  3458 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 18:40:12.024  7164  7164 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 18:40:12.024  7164  7164 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 18:40:12.025  7002  7552 V FormManager: Network unavailable.
08-29 18:40:12.026  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:12.032  7002  7552 V FormManager: Network unavailable.
,08-29 18:40:12.036  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:12
08-29 18:40:12.039  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 18:40:12.039  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-29 18:40:12.039  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 18:40:12.039  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-29 18:40:12.039  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@283a9184
08-29 18:40:12.040  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 18:40:12.040  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 18:40:12.040  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 18:40:12.040  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 18:40:12.040  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:12
08-29 18:40:12.061  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 18:40:12.063  6459  6500 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 18:40:12.077  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:12.090  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 18:40:12.090  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:12.090  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 18:40:12.090  1033  1923 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 18:40:12.090  7092  7092 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 18:40:12.096  7092  7092 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 18:40:12.100  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 18:40:12.102  7092  7092 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1038c616
08-29 18:40:12.102  7092  7092 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 18:40:12.102  7092  7092 D AppUp4:CustFacade: isPhone : true
08-29 18:40:12.102  7092  7092 D AppUp4:CustModeStarterReceiver: begin check event
08-29 18:40:12.104  7092  7092 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 18:40:12.105  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 18:40:12.106  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 18:40:12.107  7037  7037 I BluetoothA2dpServiceJni: classInitNative
08-29 18:40:12.107  7037  7037 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:12.107  7037  7037 D A2dpStateMachine: make
08-29 18:40:12.108  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:12.108  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 18:40:12.108  7037  7037 I bluedroid-qcom: get_profile_interface a2dp
08-29 18:40:12.109  7037  7556 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 18:40:12.109  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:12.112  7037  7037 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:12.112  7037  7037 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 18:40:12.113  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:12.114  7037  7555 D A2dpStateMachine: Enter Disconnected: -2
08-29 18:40:12.114  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:12.115  7037  7037 D HeadsetStateMachine: Proxy object connected
08-29 18:40:12.116  7037  7037 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 18:40:12.116  7037  7037 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 18:40:12.118  7037  7037 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 18:40:12.119  7037  7037 D HidService: Received start request. Starting profile...
08-29 18:40:12.119  7037  7037 I bluedroid-qcom: get_profile_interface hidhost
08-29 18:40:12.119  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:12.121  7037  7522 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 18:40:12.121  7037  7522 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 18:40:12.121  7037  7522 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 18:40:12.124  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 18:40:12.125  7037  7037 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 18:40:12.126  7037  7037 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 18:40:12.127  4362  7558 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 18:40:12.127  7037  7037 D HealthService: Received start request. Starting profile...
08-29 18:40:12.129  7037  7037 I bluedroid-qcom: get_profile_interface health
08-29 18:40:12.129  4362  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:12.129  7037  7037 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 18:40:12.129  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:12.129  4362  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 18:40:12.130  7037  7037 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 18:40:12.133  7037  7037 D PanService: Received start request. Starting profile...
08-29 18:40:12.133  7037  7037 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 18:40:12.133  7037  7037 I bluedroid-qcom: get_profile_interface pan
08-29 18:40:12.142  7037  7037 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 18:40:12.142  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:12.142  7125  7562 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:12.143  7037  7037 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-29 18:40:12.145  3458  3458 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 18:40:12.145  3458  3458 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:12.146  3458  3458 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 18:40:12.148  7037  7037 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 18:40:12.149  7037  7037 D BtGatt.GattService: Received start request. Starting profile...
08-29 18:40:12.149  7164  7164 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 18:40:12.149  7037  7037 D BtGatt.GattService: start()
08-29 18:40:12.149  7037  7037 I bluedroid-qcom: get_profile_interface gatt
08-29 18:40:12.149  7164  7164 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 18:40:12.149  7037  7037 D BtGatt.AdvertiseManager: advertise manager created
08-29 18:40:12.150  7002  7565 W FormManager: Network not available. Please check & try again.
08-29 18:40:12.156  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:12.156  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:12
,08-29 18:40:12.157  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:12.157  7037  7037 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 18:40:12.158  7037  7037 V BluetoothMapService: BluetoothMapBinder()
08-29 18:40:12.158  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 18:40:12.158  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-29 18:40:12.158  7037  7037 D BluetoothMapService: Received start request. Starting profile...
08-29 18:40:12.158  7037  7037 D BluetoothMapService: start()
08-29 18:40:12.159  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 18:40:12.159  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-29 18:40:12.159  7002  7566 V FormManager: Network unavailable.
08-29 18:40:12.159  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@283a9184
08-29 18:40:12.161  7002  7566 V FormManager: Network unavailable.
08-29 18:40:12.161  7037  7037 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 18:40:12.161  7037  7037 D BluetoothMapEmailAppObserver: createReceiver()
08-29 18:40:12.162  7037  7037 D BluetoothMapEmailAppObserver: initObservers()
08-29 18:40:12.162  7037  7037 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 18:40:12.163  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 18:40:12.163  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 18:40:12.163  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 18:40:12.163  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 18:40:12.163  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:40:12
08-29 18:40:12.172  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
,08-29 18:40:12.179  7037  7037 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 18:40:12.182  7037  7037 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 18:40:12.184  7037  7037 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 18:40:12.184  7037  7037 V PanService: [BTUI] SIM Extra State :ABSENT
,08-29 18:40:12.187  7037  7037 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 18:40:12.189  7037  7037 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 18:40:12.189  7037  7037 V BluetoothMapService: Handler(): got msg=1
08-29 18:40:12.189  7037  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 18:40:12.190  7037  7499 I bluedroid-qcom: enable
08-29 18:40:12.190  7037  7570 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 18:40:12.190  7037  7499 I bt_hci_bdroid: init
08-29 18:40:12.191  7037  7037 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:12.191  7037  7499 I bt_vendor: bt-vendor : init
08-29 18:40:12.191  7037  7499 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 18:40:12.191  7037  7499 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 18:40:12.191  7037  7499 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 18:40:12.191  7037  7499 D bt_userial_mct: userial_init
08-29 18:40:12.191  7037  7570 I bt-btu  : btu_task pending for preload complete event
08-29 18:40:12.191  7037  7499 D bt_hci_bdroid: set_power 1
08-29 18:40:12.191  7037  7499 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 18:40:12.191  7037  7499 I bt_vendor: Starting hciattach daemon
08-29 18:40:12.191  7037  7499 I bt_vendor: try to set true
08-29 18:40:12.182  7573  7573 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:12.193  7037  7037 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:12.193  7037  7037 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:12.193  7037  7037 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 18:40:12.182  7573  7573 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:12.194  7037  7037 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:12.194  7037  7037 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 18:40:12.209  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 18:40:12.313  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 18:40:12.341  7581  7581 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 18:40:12.372  7583  7583 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 18:40:12.396  7584  7584 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 18:40:12.424  7585  7585 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 18:40:12.454  7586  7586 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 18:40:12.496  7591  7591 I libmdmdetect: ESOC framework not supported
,08-29 18:40:12.497  7591  7591 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 18:40:12.505  7591  7591 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 18:40:12.505  7591  7591 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 18:40:12.505  7591  7591 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 18:40:12.505  7591  7591 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 18:40:12.505  7591  7591 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 18:40:12.505  7591  7591 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 18:40:12.505  7591  7591 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 18:40:12.541  7591  7595 E QC-QMI  : qmi_client [7591] 14: failed to locate client data
08-29 18:40:12.542   452   452 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 18:40:12.542   452   452 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-29 18:40:12.594  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 18:40:12.610  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 18:40:12.629  7037  7499 I bt_vendor: bluetooth satus is on
08-29 18:40:12.629  7037  7499 D bt_hci_bdroid: preload
,08-29 18:40:12.632  7037  7572 D bt_userial_mct: userial_open(port:0)
08-29 18:40:12.632  7037  7572 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 18:40:12.636  7037  7572 I bt_vendor: Done intiailizing UART
08-29 18:40:12.637  7037  7572 I bt_vendor: Done intiailizing UART
08-29 18:40:12.637  7037  7572 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 18:40:12.637  7037  7572 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 18:40:12.638  7037  7570 I bt-btu  : btu_task received preload complete event
08-29 18:40:12.638  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 18:40:12.638  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 18:40:12.640  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 18:40:12.643  7037  7602 D bt_userial_mct: Entering userial_read_thread()
,08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 18:40:12.648  7037  7570 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 18:40:12.699  7037  7570 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 18:40:12.699  7037  7570 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01de061 
08-29 18:40:12.699  7037  7570 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01de061 
,08-29 18:40:12.715  7256  7284 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-29 18:40:12.724  7037  7503 E bt-btif : Calling BTA_HhEnable
08-29 18:40:12.724  7037  7503 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 18:40:12.724  7037  7503 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 18:40:12.725  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 18:40:12.725  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 18:40:12.725  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 18:40:12.725  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 18:40:12.725  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 18:40:12.727  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 18:40:12.727  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 18:40:12.727  7037  7503 D BluetoothAdapterProperties: Name is: G3
,08-29 18:40:12.731  7037  7503 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:12.731  7037  7503 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 18:40:12.731  7037  7503 D bt_hci_bdroid: postload
08-29 18:40:12.732  7037  7572 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 18:40:12.733  7037  7503 D bte_conf: Device ID record 1 : primary
08-29 18:40:12.733  7037  7503 D bte_conf:   vendorId            = 00c4
08-29 18:40:12.733  7037  7503 D bte_conf:   vendorIdSource      = 0001
08-29 18:40:12.733  7037  7503 D bte_conf:   product             = 13a1
08-29 18:40:12.733  7037  7503 D bte_conf:   version             = 1000
08-29 18:40:12.733  7037  7503 D bte_conf:   clientExecutableURL = 
08-29 18:40:12.733  7037  7503 D bte_conf:   serviceDescription  = 
08-29 18:40:12.733  7037  7503 D bte_conf:   documentationURL    = 
08-29 18:40:12.734  7037  7503 D bte_conf: bte_load_did_conf no section named DID2.
08-29 18:40:12.734  7037  7570 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 18:40:12.735  7037  7572 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 18:40:12.735  7037  7602 E bt_mct  : hci lib postload completed
08-29 18:40:12.738  7037  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 18:40:12.738  7037  7499 D BluetoothAdapterProperties: ScanMode =  20
08-29 18:40:12.738  7037  7499 D BluetoothAdapterProperties: State =  11
08-29 18:40:12.738  7037  7499 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 18:40:12.738  7037  7499 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 18:40:12.738  7037  7499 D BluetoothAdapterProperties: Setting state to 12
08-29 18:40:12.738  7037  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 18:40:12.739  7037  7503 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 18:40:12.739  7037  7503 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 18:40:12.732  7606  7606 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:12.746  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:12.746  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 18:40:12.746  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 18:40:12.747  7037  7570 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:12.747  7037  7570 W bt-smp  : Plain text(LSB ~ MSB) = 0a c4 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:12.747  7037  7570 W bt-smp  : Encrypted text(LSB ~ MSB) = 13 f7 b6 db 1a 02 7c 91 d0 ff ec 0f d6 46 12 86 
08-29 18:40:12.747  7037  7570 W bt-btm  : Stopping oneshot timer
08-29 18:40:12.732  7606  7606 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:12.761  7037  7499 I BluetoothAdapterState: Entering On State
,08-29 18:40:12.764  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:12.769  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:12.776  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:12.782  7037  7570 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:12.782  7037  7570 W bt-smp  : Plain text(LSB ~ MSB) = 2a 31 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:12.782  7037  7570 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 65 6e 97 4c 3d f1 d6 b2 3d 87 b4 23 d7 63 52 
08-29 18:40:12.785  7037  7570 W bt-btm  : Stopping oneshot timer
08-29 18:40:12.800  7037  7570 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:12.800  7037  7570 W bt-smp  : Plain text(LSB ~ MSB) = 46 18 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:12.800  7037  7570 W bt-smp  : Encrypted text(LSB ~ MSB) = d5 16 3e 78 13 f8 12 29 70 9a db 02 72 07 f8 68 
,08-29 18:40:12.803  7037  7570 W bt-btm  : Stopping oneshot timer
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:12.804  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:12.812  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:12.825  7037  7570 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:12.825  7037  7570 W bt-smp  : Plain text(LSB ~ MSB) = 81 05 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:12.825  7037  7570 W bt-smp  : Encrypted text(LSB ~ MSB) = 74 01 3f cf b1 c2 f5 75 e5 47 2e 68 2d 82 88 ac 
,08-29 18:40:12.827  7037  7570 W bt-btm  : Stopping oneshot timer
08-29 18:40:12.836  7037  7503 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 18:40:12.837  7037  7503 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 18:40:12.854  7037  7570 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:12.854  7037  7570 W bt-smp  : Plain text(LSB ~ MSB) = cc f0 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:12.854  7037  7570 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 1f e8 0e 77 88 43 f4 7c 43 fd cf 26 6d 39 0b 
08-29 18:40:12.854  7037  7570 W bt-btm  : Stopping oneshot timer
,08-29 18:40:12.855  6895  6910 D BluetoothMap: onBluetoothStateChange: up=true
08-29 18:40:12.856  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 18:40:12.859  6895  6911 D BluetoothPan: onBluetoothStateChange on: true
08-29 18:40:12.859  6895  6911 D BluetoothPan: onBluetoothStateChange call bindService
08-29 18:40:12.860  7037  7499 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 18:40:12.860  7037  7499 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 18:40:12.860  7037  7499 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 18:40:12.862  7037  7499 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 18:40:12.863  7037  7499 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 18:40:12.865  6895  6895 D BluetoothMap: Proxy object connected
08-29 18:40:12.865  6895  6895 D MapProfile: Bluetooth service connected
08-29 18:40:12.865  6895  6895 D BluetoothMap: getConnectedDevices()
08-29 18:40:12.866  7037  7053 V BluetoothMapService: getConnectedDevices()
08-29 18:40:12.870  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:12.872  1852  4026 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:12.873  1033  1033 D BluetoothHeadset: Proxy object connected
08-29 18:40:12.882  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 18:40:12.883  6895  7619 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 18:40:12.884  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 18:40:12.886  1033  1033 D BluetoothA2dp: Proxy object connected
08-29 18:40:12.887  1852  2460 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:12.888  6895  6895 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 18:40:12.888  6895  6895 D PanProfile: Bluetooth service connected
08-29 18:40:12.890  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 18:40:12.890  6895  6910 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 18:40:12.890  7623  7623 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 18:40:12.895  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 18:40:12.895  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-29 18:40:12.897  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:12.898  1941  2125 D LGBluetoothAPIService: Message: 1
08-29 18:40:12.898  1941  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 18:40:12.898  6895  6895 D BluetoothInputDevice: Proxy object connected
08-29 18:40:12.898  6895  6895 D HidProfile: Bluetooth service connected
08-29 18:40:12.902  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 18:40:12.903  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 18:40:12.903  1033  1095 D BluetoothManagerService: Message: 40
08-29 18:40:12.903  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 18:40:12.906  1941  2125 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 18:40:12.908  6657  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-29 18:40:12.912  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:12.913  7037  7037 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:12.913  7037  7037 D BluetoothMapService: STATE_ON
08-29 18:40:12.913  6895  6895 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 18:40:12.915  7037  7037 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 18:40:12.915  7037  7037 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 18:40:12.916  1033  1095 D BluetoothManagerService: Message: 30
08-29 18:40:12.917  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:12.918  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 18:40:12.918  1941  2125 D LGBluetoothAPIService: Message: 100
08-29 18:40:12.918  1941  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 18:40:12.921  6895  6895 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 18:40:12.924  1033  1095 D BluetoothManagerService: Message: 30
,08-29 18:40:12.929  6895  6895 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 18:40:12.931  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 18:40:12.933  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:12.934  7037  7037 V BluetoothPbapService: Pbap Service onCreate
08-29 18:40:12.934  7037  7037 V BluetoothPbapService: Starting PBAP service
08-29 18:40:12.934  6895  6895 D BluetoothA2dp: Proxy object connected
08-29 18:40:12.935  7037  7037 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 18:40:12.935  7037  7037 V BluetoothPbapService: Pbap Service onBind
,08-29 18:40:12.936  6895  6895 D A2dpProfile: Bluetooth service connected
08-29 18:40:12.936  7037  7037 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:12.937  7037  7037 V BluetoothPbapService: state: 12
08-29 18:40:12.937  7037  7037 V BluetoothMapService: Handler(): got msg=1
08-29 18:40:12.937  7037  7037 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-29 18:40:12.938  7037  7037 V BluetoothPbapService: Handler(): got msg=1
08-29 18:40:12.938  7037  7037 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 18:40:12.939  7037  7629 D BluetoothMapMasInstance: MAS initSocket()
08-29 18:40:12.939  6895  6895 D BluetoothHeadset: Proxy object connected
08-29 18:40:12.939  7037  7037 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 18:40:12.939  7037  7037 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:12.939  7037  7037 V BluetoothPbapReceiver: ***********state = 12
08-29 18:40:12.939  7037  7629 D BluetoothMapMasInstance:   masId = 00
08-29 18:40:12.939  7037  7629 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 18:40:12.939  7037  7629 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 18:40:12.939  7037  7629 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 18:40:12.940  6895  6895 D HeadsetProfile: Bluetooth service connected
08-29 18:40:12.941  7037  7630 V BluetoothPbapService: Pbap Service initSocket
08-29 18:40:12.944  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:12.944  2193  2193 D c       : Getting all permits...
08-29 18:40:12.944  2193  2193 D a       : Opening database...
08-29 18:40:12.945  1033  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:12.945  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:12.948  2193  2193 D a       : Opening database auth.proximity.permit_store...
08-29 18:40:12.949  7037  7629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:12.949  7037  7630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:12.950  6895  6895 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:12.951  7037  7629 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 18:40:12.951  7037  7629 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 18:40:12.951  7037  7629 D BluetoothMapMasInstance: Accepting socket connection...
08-29 18:40:12.951  7037  7503 D BluetoothAdapterProperties: Scan Mode:21
08-29 18:40:12.952  7037  7503 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 18:40:12.952  2193  2193 D a       : Closing database...
08-29 18:40:12.952  7037  7630 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 18:40:12.953  7037  7630 V BluetoothPbapService: Succeed to create listening socket 
08-29 18:40:12.953  7037  7630 V BluetoothPbapService: Accepting socket connection...
08-29 18:40:12.953  6895  6895 D BluetoothPbap: Proxy object connected
08-29 18:40:12.954  6895  6895 D PbapServerProfile: Bluetooth service connected
08-29 18:40:12.955  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:12.957  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:12.968  6895  6895 D BluetoothPermissionRequest: onReceive
08-29 18:40:12.969  6895  6895 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-29 18:40:12.971  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:12.975  7037  7037 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 18:40:12.976  7037  7037 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 18:40:12.983  7037  7037 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 18:40:13.011  7037  7037 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 18:40:13.012  7037  7037 V BtOppService: onCreate
08-29 18:40:13.018  7037  7037 V BluetoothOppNotification: send message
08-29 18:40:13.022  7037  7037 V BtOppService: Starting RfcommListener
08-29 18:40:13.030  7037  7037 D BluetoothOppPreference: Dumping Names:  
08-29 18:40:13.030  7037  7037 D BluetoothOppPreference: {}
,08-29 18:40:13.030  7037  7037 D BluetoothOppPreference: Dumping Channels:  
08-29 18:40:13.030  7037  7037 D BluetoothOppPreference: {}
,08-29 18:40:13.033  7037  7037 V BtOppService: onStartCommand
08-29 18:40:13.037  7037  7637 V BtOppService: Deleted complete outbound shares, number =  0
08-29 18:40:13.038  7037  7037 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:13.039  7037  7037 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 18:40:13.039  7037  7640 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 18:40:13.041  7037  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 18:40:13.044  7037  7037 V BluetoothOppNotification: new notify threadi!
,08-29 18:40:13.044  7037  7037 V BluetoothOppNotification: send delay message
08-29 18:40:13.045  7037  7037 V BtOppService: start RfcommListener
08-29 18:40:13.045  7037  7637 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 18:40:13.046  7037  7637 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 18:40:13.049  7037  7637 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e62d7b9 on behalf of 
08-29 18:40:13.049  7037  7037 V BtOppService: RfcommListener started
08-29 18:40:13.049  7037  7037 V BtOppService: ContentObserver received notification
08-29 18:40:13.051  7037  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 18:40:13.052  7037  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fe667fe on behalf of 
08-29 18:40:13.053  7037  7642 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 18:40:13.056  7037  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@53ddb5f on behalf of 
08-29 18:40:13.057  1033  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:13.057  7037  7640 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 18:40:13.057  7037  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-29 18:40:13.059  7037  7641 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 18:40:13.061  7037  7642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:13.062  7037  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ea789ac on behalf of 
08-29 18:40:13.062  7037  7642 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 18:40:13.063  7037  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:13.063  7037  7642 V BtOppRfcommListener: Started RFCOMM listener....
08-29 18:40:13.063  7037  7642 I BtOppRfcommListener: Accept thread started.
08-29 18:40:13.063  7037  7642 V BtOppRfcommListener: Accepting connection...
08-29 18:40:13.065  7037  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@503675 on behalf of 
08-29 18:40:13.065  7037  7640 V BluetoothOppNotification: update too frequent, put in queue
08-29 18:40:13.066  7037  7641 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 18:40:13.067  7037  7640 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 18:40:13.068  7037  7641 V BluetoothOppNotification: outbound notification was removed.
08-29 18:40:13.068  7037  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:13.072  7037  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@263d060a on behalf of 
08-29 18:40:13.073  7037  7641 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 18:40:13.076  7037  7641 V BluetoothOppNotification: inbound notification was removed.
,08-29 18:40:13.077  7037  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-29 18:40:13.079  7037  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@158ece7b on behalf of 
08-29 18:40:13.079  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:13.079  7037  7037 V BluetoothFtpService: Ftp Service onCreate
08-29 18:40:13.079  7037  7037 I BluetoothFtpService: Ftp Service onCreate
08-29 18:40:13.080  7037  7037 V BluetoothFtpService: Ftp Service onStartCommand
08-29 18:40:13.080  7037  7037 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:13.080  7037  7037 V BluetoothFtpService: Starting Listening on sockets
08-29 18:40:13.080  7037  7037 V BtOppService: ContentObserver received notification
08-29 18:40:13.081  7037  7037 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:13.081  7037  7037 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:13.081  7037  7037 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 18:40:13.081  7037  7037 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:13.081  7037  7037 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 18:40:13.081  7037  7037 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 18:40:13.083  7037  7037 V BluetoothFtpService: Handler(): got msg=1
08-29 18:40:13.084  7037  7037 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 18:40:13.084  7037  7643 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 18:40:13.084  7037  7037 V BluetoothFtpService: Ftp Service initSocket
08-29 18:40:13.084  7037  7643 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 18:40:13.087  7037  7643 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@337ac4f1 on behalf of 
08-29 18:40:13.088  1033  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:13.089  7037  7643 V BluetoothOppNotification: update too frequent, put in queue
08-29 18:40:13.089  7037  7037 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:13.091  7037  7643 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-29 18:40:13.096  7037  7037 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-29 18:40:13.097  7037  7037 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 18:40:13.099  7037  7644 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 18:40:13.120  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
,08-29 18:40:13.121  7037  7037 V BluetoothSapService: Sap Service onCreate
08-29 18:40:13.123  7037  7037 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:13.123  7037  7037 V BluetoothSapService: state: 12
,08-29 18:40:13.124  7037  7037 V BluetoothSapService: Starting SAP server process
08-29 18:40:13.126  7037  7037 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 18:40:13.112  7645  7645 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:13.112  7645  7645 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:13.128  7037  7646 V BluetoothSapService: Sap Service initRfcommSocket
08-29 18:40:13.129  1033  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:13.130  7037  7646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:13.131  7037  7646 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 18:40:13.131  7037  7646 V BluetoothSapService: Succeed to create listening socket 
08-29 18:40:13.131  7037  7646 V BluetoothSapService: Accepting socket connection...
08-29 18:40:13.155  7645  7645 V BT_SAP  : Event pipe created
08-29 18:40:13.155  7645  7645 V BT_SAP  : create_server_socket qcom.sap.server
08-29 18:40:13.155  7645  7645 V BT_SAP  : created socket fd 6
,08-29 18:40:13.563  1033  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 18:40:13.563  1033  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 18:40:13.635  1033  1390 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 18:40:13.636  1033  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 18:40:13.768  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{9a5d5 type 2 when 128611 com.google.android.gms} when 128611
,08-29 18:40:13.782  6964  6964 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-29 18:40:13.782  6964  6964 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5831
08-29 18:40:13.786   321  7657 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 18:40:13.791  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 18:40:13.809  1033  1049 I ActivityManager: Killing 7427:com.lge.bnr/1000 (adj 15): empty #17
,08-29 18:40:13.841  1033  2013 W libprocessgroup: failed to open /acct/uid_1000/pid_7427/cgroup.procs: No such file or directory
,08-29 18:40:14.028  1033  2764 I ActivityManager: Killing 6932:com.lge.sync/1000 (adj 15): empty #17
,08-29 18:40:14.046  7037  7037 V BluetoothOppNotification: new notify threadi!
08-29 18:40:14.046  7037  7037 V BluetoothOppNotification: send delay message
,08-29 18:40:14.057  7037  7658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 18:40:14.059  1033  1402 D WifiService: Client connection lost with reason: 4
,08-29 18:40:14.062  7037  7658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14e5bf2d on behalf of 
08-29 18:40:14.065  7037  7658 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 18:40:14.066  7037  7658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:14.067  7037  7658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fe04c62 on behalf of 
08-29 18:40:14.067  7037  7658 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 18:40:14.069  7037  7658 V BluetoothOppNotification: outbound notification was removed.
08-29 18:40:14.069  7037  7658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:14.104  1033  1729 W libprocessgroup: failed to open /acct/uid_1000/pid_6932/cgroup.procs: No such file or directory
,08-29 18:40:14.238  1033  1923 I art     : Explicit concurrent mark sweep GC freed 92623(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.404ms total 157.079ms
,08-29 18:40:14.240  7037  7658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f9291f3 on behalf of 
,08-29 18:40:14.241  7037  7658 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 18:40:14.243  7037  7658 V BluetoothOppNotification: inbound notification was removed.
,08-29 18:40:14.243  7037  7658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-29 18:40:14.244  7037  7658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ed25eb0 on behalf of 
,08-29 18:40:14.576  1033  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:14.576  1033  1994 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@c60b1ea mBinding = false
,08-29 18:40:14.606  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:14.607  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:14.607  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-29 18:40:14.610  1033  1095 D BluetoothManagerService: Message: 2
08-29 18:40:14.611  1033  1095 D BluetoothManagerService: Sending off request.
08-29 18:40:14.611  7037  7053 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 18:40:14.612  7037  7499 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 18:40:14.612  7037  7499 D BluetoothAdapterProperties: Setting state to 13
08-29 18:40:14.612  7037  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 18:40:14.613  7037  7499 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 18:40:14.613  7037  7499 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 18:40:14.615  7037  7503 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:14.616  7037  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 18:40:14.617  7037  7499 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 18:40:14.619  7037  7629 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-29 18:40:14.624  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 18:40:14.625  7037  7570 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 18:40:14.626  7037  7630 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:14.627  7037  7644 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:14.627  7037  7642 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 18:40:14.631  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 18:40:14.631  7037  7570 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 18:40:14.641  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:14.641  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:14.646  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:14.646  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:14.650  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:14.650  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:14.651  6657  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:14.651  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:14.652  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:14.653  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 18:40:14.653  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-29 18:40:14.658  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 18:40:14.660  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:14.664  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:14.665  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:14.669  7037  7037 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:14.670  7037  7037 D BluetoothMapService: STATE_TURNING_OFF
08-29 18:40:14.670  7037  7037 V BluetoothMapService: Handler(): got msg=4
08-29 18:40:14.670  7037  7037 D BluetoothMapService: MAP Service closeService in
08-29 18:40:14.670  7037  7037 D BluetoothMapMasInstance: MAP Service shutdown
08-29 18:40:14.670  7037  7037 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 18:40:14.670  7037  7037 V BluetoothMapService: MAP Service closeService out
08-29 18:40:14.672  7037  7037 V BtOppService: Receiver DISABLED_ACTION 
08-29 18:40:14.672  7037  7037 I BtOppRfcommListener: stopping Accept Thread
08-29 18:40:14.673  7037  7037 V BtOppRfcommListener: close mBtServerSocket
08-29 18:40:14.673  7037  7642 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 18:40:14.673  7037  7037 V BtOppRfcommListener: waiting for thread to terminate
08-29 18:40:14.673  7037  7037 V BtOppRfcommListener: done waiting for thread to terminate
08-29 18:40:14.676  6895  6895 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 18:40:14.682  7037  7646 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 18:40:14.689  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 18:40:14.690  7037  7037 V BtOppService: onDestroy
08-29 18:40:14.692  7037  7037 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 18:40:14.697  7037  7037 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 18:40:14.697  7037  7037 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:14.697  7037  7037 V BluetoothPbapReceiver: ***********state = 13
,08-29 18:40:14.701  7037  7037 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 18:40:14.703  7037  7037 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:14.703  7037  7037 V BluetoothPbapService: state: 13
08-29 18:40:14.703  7037  7037 V BluetoothPbapService: Pbap Service closeService in
08-29 18:40:14.706  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:14.707  7037  7037 V BluetoothPbapService: successfully stopped pbap service
08-29 18:40:14.707  7037  7037 V BluetoothPbapService: Pbap Service closeService out
08-29 18:40:14.708  7037  7037 V BluetoothPbapService: Pbap Service onDestroy
08-29 18:40:14.708  7037  7037 V BluetoothPbapService: Pbap Service closeService in
08-29 18:40:14.708  7037  7037 V BluetoothPbapService: Pbap Service closeService out
08-29 18:40:14.708  7037  7037 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 18:40:14.723  6895  6895 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:14.729  6895  6895 D BluetoothPbap: Proxy object disconnected
,08-29 18:40:14.729  6895  6895 D PbapServerProfile: Bluetooth service disconnected
,08-29 18:40:14.755  6895  6895 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 18:40:14.761  6895  6895 D BluetoothPermissionRequest: onReceive
08-29 18:40:14.762  6895  6895 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 18:40:14.768  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:14.773  7037  7037 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 18:40:14.773  7037  7037 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-29 18:40:14.774  7037  7037 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-29 18:40:14.780  7037  7037 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:14.780  7037  7037 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 18:40:14.781  7037  7037 V BluetoothFtpService: Ftp Service onStartCommand
08-29 18:40:14.781  7037  7037 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:14.782  7037  7037 V BluetoothFtpService: Ftp Service closeService
08-29 18:40:14.782  7037  7037 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 18:40:14.785  7037  7037 V BluetoothFtpService: successfully stopped ftp service
08-29 18:40:14.785  7037  7037 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:14.786  7037  7037 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:14.786  7037  7037 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 18:40:14.786  7037  7037 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:14.786  7037  7037 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 18:40:14.786  7037  7037 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 18:40:14.787  7037  7037 V BluetoothFtpService: Ftp Service onDestroy
08-29 18:40:14.787  7037  7037 V BluetoothFtpService: Ftp Service closeService
,08-29 18:40:14.788  7037  7037 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:14.788  7037  7037 V BluetoothSapService: state: 13
,08-29 18:40:14.789  7037  7037 V BluetoothSapService: Stopping SAP server process
,08-29 18:40:14.790  7037  7037 V BluetoothSapService: Sap Service closeSapService in
,08-29 18:40:14.790  7037  7037 V BluetoothSapService: Close listen Socket : ,
,08-29 18:40:14.790  7037  7037 V BluetoothSapService: Close rfcomm Socket : 
08-29 18:40:14.790  7037  7037 V BluetoothSapService: Close sapd  Socket : 
,08-29 18:40:14.793  7037  7037 V BluetoothSapService: Sap Service closeSapService out
08-29 18:40:14.794  7037  7037 V BluetoothSapService: Sap Service onDestroy
08-29 18:40:14.794  7037  7037 V BluetoothSapService: Sap Service closeSapService in
08-29 18:40:14.794  7037  7037 V BluetoothSapService: Close listen Socket : 
,08-29 18:40:14.794  7037  7037 V BluetoothSapService: Close rfcomm Socket : 
08-29 18:40:14.794  7037  7037 V BluetoothSapService: Close sapd  Socket : 
08-29 18:40:14.798  7037  7037 V BluetoothSapService: Sap Service closeSapService out
08-29 18:40:15.531  7037  7503 D bt_hci_bdroid: cleanup
,08-29 18:40:15.546  7037  7602 I bt_userial_mct: exiting userial_read_thread
08-29 18:40:15.546  7037  7602 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 18:40:15.546  7037  7572 I bt_lpm  : LPM is already off!!!
08-29 18:40:15.547  7037  7570 W bt-btif : ag scb idx 1 not allocated
08-29 18:40:15.547  7037  7570 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 18:40:15.547  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:15.547  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:15.547  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:15.547  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 18:40:15.548  7037  7570 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:15.548  7037  7570 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 18:40:15.549  7037  7503 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 18:40:15.549  7037  7572 I bt_vendor: hw_epilog_process
08-29 18:40:15.549  7037  7503 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 18:40:15.549  7037  7503 D bt_userial_mct: userial_close
08-29 18:40:15.549  7037  7503 E bt_userial_mct: pthread_join() FAILED result:3
08-29 18:40:15.549  7037  7503 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 18:40:15.553  7037  7503 D bt_hci_bdroid: set_power 0
08-29 18:40:15.553  7037  7503 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 18:40:15.553  7037  7503 I bt_vendor: bluetooth satus is on
08-29 18:40:15.553  7037  7503 I bt_vendor: bt-vendor : resetting BT status
08-29 18:40:15.553  7037  7503 I bt_vendor: Starting hciattach daemon
08-29 18:40:15.553  7037  7503 I bt_vendor: try to set false
08-29 18:40:15.555  7037  7503 I bt_vendor: Starting hciattach daemon
08-29 18:40:15.555  7037  7503 I bt_vendor: try to set false
,08-29 18:40:15.559  7037  7503 I bt_vendor: cleanup
08-29 18:40:15.561  7037  7570 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 18:40:15.562  7037  7503 I GKI_LINUX: GKI_exit_task 0 done
08-29 18:40:15.562  7037  7503 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 18:40:15.563  7037  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 18:40:15.566  7037  7037 D HeadsetService: Received stop request...Stopping profile...
08-29 18:40:15.567  7037  7037 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 18:40:15.567  7037  7037 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 18:40:15.567  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
,08-29 18:40:15.571  7037  7522 D HeadsetStateMachine: Exit Disconnected: -1
08-29 18:40:15.573  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:15.573  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:15.574  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:15.575  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:15.575  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 18:40:15.576  7037  7037 D HeadsetStateMachine: Unbinding service...
08-29 18:40:15.577  7037  7037 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 18:40:15.577  7037  7037 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 18:40:15.578  7037  7037 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 18:40:15.578  7037  7037 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 18:40:15.578  7037  7037 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 18:40:15.578  7037  7037 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 18:40:15.578  7037  7037 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 18:40:15.584  7037  7037 D A2dpService: Received stop request...Stopping profile...
,08-29 18:40:15.587  7037  7555 D A2dpStateMachine: Exit Disconnected: -1
08-29 18:40:15.590  7037  7037 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 18:40:15.591  7037  7499 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 18:40:15.593  7037  7037 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 18:40:15.593  7037  7037 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 18:40:15.593  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:15.594  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-29 18:40:15.594  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 18:40:15.596  7037  7037 D HidService: Received stop request...Stopping profile...
08-29 18:40:15.597  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
,08-29 18:40:15.601  7037  7037 D HealthService: Received stop request...Stopping profile...
08-29 18:40:15.601  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:15.604  7037  7037 D PanService: Received stop request...Stopping profile...
08-29 18:40:15.605  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:15.605  7037  7037 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 18:40:15.606  7037  7037 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 18:40:15.606  7037  7037 D BtGatt.GattService: stop()
08-29 18:40:15.606  7037  7037 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 18:40:15.608  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:15.610  7037  7037 D BluetoothMapService: Received stop request...Stopping profile...
08-29 18:40:15.610  7037  7037 D BluetoothMapService: stop()
,08-29 18:40:15.613  7037  7037 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 18:40:15.613  7037  7037 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 18:40:15.614  7037  7037 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@283a9184
08-29 18:40:15.616  7037  7037 I BluetoothA2dpServiceJni: cleanupNative
08-29 18:40:15.616  7037  7556 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 18:40:15.616  7037  7037 I GKI_LINUX: GKI_exit_task 2 done
08-29 18:40:15.616  7037  7037 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 18:40:15.617  7037  7037 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 18:40:15.617  7037  7037 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 18:40:15.617  7037  7037 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 18:40:15.617  7037  7037 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 18:40:15.617  7037  7037 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 18:40:15.618  7037  7037 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 18:40:15.618  7037  7037 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 18:40:15.620  7037  7037 V BluetoothMapService: Handler(): got msg=4
08-29 18:40:15.620  7037  7037 D BluetoothMapService: MAP Service closeService in
08-29 18:40:15.620  7037  7037 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 18:40:15.620  7037  7037 V BluetoothMapService: MAP Service closeService out
08-29 18:40:15.621  7037  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 18:40:15.621  7037  7499 D BluetoothAdapterProperties: Setting state to 10
08-29 18:40:15.621  7037  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 18:40:15.622  7037  7037 D BluetoothMapService: cleanup()
08-29 18:40:15.622  7037  7037 D BluetoothMapService: MAP Service closeService in
08-29 18:40:15.622  7037  7037 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 18:40:15.622  7037  7037 V BluetoothMapService: MAP Service closeService out
,08-29 18:40:15.626  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:15.626  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 18:40:15.626  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 18:40:15.627  7037  7499 I BluetoothAdapterState: Entering OffState
08-29 18:40:15.627  1852  4026 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:15.630  6895  6911 D BluetoothMap: onBluetoothStateChange: up=false
08-29 18:40:15.631  6895  6911 D BluetoothPan: onBluetoothStateChange on: false
08-29 18:40:15.632  6895  6911 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:15.632  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:15.633  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:15.633  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:40:15.635  6895  6911 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 18:40:15.636  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:15.637  6895  6911 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 18:40:15.638  6895  6911 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 18:40:15.639  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 18:40:15.639  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 18:40:15.642  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 18:40:15.642  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 18:40:15.642  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@c60b1ea mBinding = false
08-29 18:40:15.642  1033  1095 D BluetoothManagerService: Sending unbind request.
08-29 18:40:15.647  7037  7503 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 18:40:15.649  7037  7037 I GKI_LINUX: GKI_exit_task 1 done
08-29 18:40:15.649  7037  7037 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 18:40:15.651  7037  7037 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 18:40:15.651  7037  7037 I art     : --- WEIRD: removing null entry 248
08-29 18:40:15.651  7037  7037 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 18:40:15.651  7037  7037 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 18:40:15.652  7037  7037 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 18:40:15.653  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 18:40:15.655  7037  7037 I art     : System.exit called, status: 0
08-29 18:40:15.655  7037  7037 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 18:40:15.675   325  1401 V AudioFlinger: 7037 died, releasing its sessions
08-29 18:40:15.675   325  1401 V AudioFlinger:  pid 1852 @ 0
08-29 18:40:15.675   325  1401 V AudioFlinger:  pid 3458 @ 1
08-29 18:40:15.675   325  1401 V AudioFlinger:  pid 3458 @ 2
,08-29 18:40:15.679  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-29 18:40:15.679  1941  2125 D LGBluetoothAPIService: Message: 101
,08-29 18:40:15.679  1941  2125 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 18:40:15.680  1941  2125 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-29 18:40:15.680  1941  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 18:40:15.681  6895  6895 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 18:40:15.733  1033  1923 I ActivityManager: Process com.android.bluetooth (pid 7037) has died
08-29 18:40:15.733  1033  1923 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-29 18:40:15.733  1033  1923 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-29 18:40:15.743  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:15.743  1941  2125 D LGBluetoothAPIService: Message: 2
08-29 18:40:15.743  1941  2125 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-29 18:40:15.744  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 18:40:15.745  6895  6895 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 18:40:15.745  6895  6895 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 18:40:15.746  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:15.747  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:15.754  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 18:40:15.762  1601  1601 D BluetoothAdapter: 888945935: getState() :  mService = null. Returning STATE_OFF
08-29 18:40:15.762  1601  1601 D BluetoothAdapter: 888945935: getState() :  mService = null. Returning STATE_OFF
08-29 18:40:15.815  1033  1729 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7705 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 18:40:15.817  6895  6895 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:15.893  7705  7705 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 18:40:15.893  7705  7705 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 18:40:15.894  7705  7705 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 18:40:15.895  7705  7705 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 18:40:15.924  7705  7705 D BluetoothAdapterApp: Loading JNI Library
,08-29 18:40:15.962  7705  7705 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d8110ec Instance Count = 1
,08-29 18:40:15.970  7705  7705 D BluetoothAdapterApp: onCreate
08-29 18:40:15.996  7705  7705 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 18:40:15.996  7705  7705 D ProfileConfigQcom: Adding HeadsetService
08-29 18:40:15.996  7705  7705 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-29 18:40:15.997  7705  7705 D ProfileConfigQcom: Adding A2dpService
,08-29 18:40:15.997  7705  7705 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 18:40:15.997  7705  7705 D ProfileConfigQcom: Adding HidService
08-29 18:40:15.997  7705  7705 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 18:40:15.998  7705  7705 D ProfileConfigQcom: Adding HealthService
08-29 18:40:15.998  7705  7705 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 18:40:15.999  7705  7705 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 18:40:15.999  7705  7705 D ProfileConfigQcom: Adding PanService
08-29 18:40:16.000  7705  7705 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 18:40:16.000  7705  7705 D ProfileConfigQcom: Adding GattService
08-29 18:40:16.000  7705  7705 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 18:40:16.000  7705  7705 D ProfileConfigQcom: Adding BluetoothMapService
08-29 18:40:16.001  7705  7705 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 18:40:16.002  7705  7705 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 18:40:16.003  7705  7705 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:16.004  7705  7705 V BluetoothPbapReceiver: ***********state = 10
08-29 18:40:16.005  7705  7705 V LGMDMManagerInternal: Create singleton instance
,08-29 18:40:16.104  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:16.121  7705  7705 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-29 18:40:16.121  7705  7705 D LGBluetoothAPIServer: [BTUI] onBind()
,08-29 18:40:16.122  6895  6895 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 18:40:16.128  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 18:40:16.128  1941  2125 D LGBluetoothAPIService: Message: 100
08-29 18:40:16.128  1941  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 18:40:16.139  6895  6895 D BluetoothPermissionRequest: onReceive
,08-29 18:40:16.142  6895  6895 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 18:40:16.142  6895  6895 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 18:40:16.145  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:16.150  7705  7705 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 18:40:16.156  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:16.160  7705  7705 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:16.160  7705  7705 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:16.160  7705  7705 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 18:40:16.162  7705  7705 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:16.162  7705  7705 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-29 18:40:16.165  6981  6981 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 18:40:17.134  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{94bca51 type 2 when 131973 com.google.android.gms} when 131973
,08-29 18:40:17.142   321  7735 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 18:40:17.146  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 18:40:17.643  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 18:40:17.668  1033  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 18:40:17.693  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:17.693  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:17.703  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-29 18:40:17.753  1033  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7736 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 18:40:17.759  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-29 18:40:17.760  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-29 18:40:17.795  1033  1033 D administrator: Handling package changes for user 0
,08-29 18:40:17.814  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 18:40:17.850  7736  7736 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 18:40:17.914  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-29 18:40:17.914  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 18:40:17.947  7736  7736 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:17.947  7736  7736 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:40:17.962  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 18:40:17.968  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 18:40:17.977  2485  2485 V GmsNetworkLocationProvi: DISABLE
08-29 18:40:17.977  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-29 18:40:18.009  1033  1090 D LocationProviderProxy: applying state to connected service
,08-29 18:40:18.015  2485  2485 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-29 18:40:18.090  7736  7781 I Babel   : MmsConfig: mnc/mcc: 0/0
08-29 18:40:18.090  7736  7781 I Babel   : MmsConfig.loadMmsSettings
,08-29 18:40:18.095  7736  7781 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-29 18:40:18.096  7736  7781 I Babel   : MmsConfig.loadFromDatabase
,08-29 18:40:18.113  7736  7781 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-29 18:40:18.113  7736  7781 I Babel   : MmsConfig.loadFromResources
08-29 18:40:18.123  7736  7781 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 18:40:18.124  7736  7781 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-29 18:40:18.134  7736  7779 W AudioCapabilities: Unsupported mime audio/evrc
08-29 18:40:18.135  7736  7779 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 18:40:18.137  7736  7779 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 18:40:18.144  7736  7736 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:18.149  7736  7779 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-29 18:40:18.151  7736  7779 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 18:40:18.152  7736  7779 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 18:40:18.163  7736  7779 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 18:40:18.166  7736  7779 W VideoCapabilities: Unsupported mime video/divx
,08-29 18:40:18.168  7736  7779 W VideoCapabilities: Unsupported mime video/divx311
08-29 18:40:18.171  7736  7779 W VideoCapabilities: Unsupported mime video/divx4
08-29 18:40:18.180  7736  7779 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 18:40:18.191  1816  7784 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-29 18:40:18.191  1816  7784 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-29 18:40:18.200  7092  7092 I AppUp4:CustModeStarterReceiver: onReceive
08-29 18:40:18.207  1816  4797 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-29 18:40:18.208  7092  7092 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1038c616
,08-29 18:40:18.208  7092  7092 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 18:40:18.208  7092  7092 D AppUp4:CustFacade: isPhone : true
08-29 18:40:18.208  7092  7092 D AppUp4:CustModeStarterReceiver: begin check event
08-29 18:40:18.209  7092  7092 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-29 18:40:18.215  7736  7779 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-29 18:40:18.218  7736  7779 W AudioCapabilities: Unsupported mime audio/eac3
08-29 18:40:18.219  7736  7779 W AudioCapabilities: Unsupported mime audio/ac3
08-29 18:40:18.220  7736  7779 W AudioCapabilities: Unsupported mime audio/g726
08-29 18:40:18.222  7736  7779 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-29 18:40:18.224  7736  7779 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-29 18:40:18.225  7736  7779 W AudioCapabilities: Unsupported mime audio/adpcm
,08-29 18:40:18.226  7736  7779 W VideoCapabilities: Unsupported mime video/theora
08-29 18:40:18.228  7736  7779 W VideoCapabilities: Unsupported mime video/mjpg
08-29 18:40:18.247  1033  1904 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7787 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-29 18:40:18.289  1033  1953 I ActivityManager: Killing 7125:com.lge.email/u0a23 (adj 15): empty #17
08-29 18:40:18.304  7787  7787 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 18:40:18.304  7787  7787 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 18:40:18.305  7787  7787 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-29 18:40:18.306  7787  7787 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 18:40:18.306  7787  7787 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 18:40:18.410  1033  2042 W libprocessgroup: failed to open /acct/uid_10023/pid_7125/cgroup.procs: No such file or directory
,08-29 18:40:18.437  7787  7787 I SystemConfig: BUILD Country: EU
,08-29 18:40:18.437  7787  7787 I SystemConfig: BUILD Operator: OPEN
08-29 18:40:18.474  1033  1976 I ActivityManager: Killing 7002:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-29 18:40:18.574  1033  1048 W libprocessgroup: failed to open /acct/uid_10026/pid_7002/cgroup.procs: No such file or directory
,08-29 18:40:18.582  7787  7805 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 18:40:18.582  7787  7805 I SystemConfig: existFile = false
08-29 18:40:18.582  7787  7805 I SystemConfig: canReadFile = false
08-29 18:40:18.582  7787  7805 I SystemConfig: systemFeature RCS result false
08-29 18:40:18.582  7787  7805 D SystemConfig: refreshRcsSupport() :false
08-29 18:40:18.633  1033  1976 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7813 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-29 18:40:18.643  1033  1409 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-29 18:40:18.696  7813  7813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:40:18.696  7813  7813 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 18:40:18.696  7813  7813 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 18:40:18.696  7813  7813 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 18:40:18.783  7813  7813 I AppConfig: Total System Memory = 2995761152
,08-29 18:40:18.792  7813  7813 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-29 18:40:18.847  1033  2012 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7842 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:40:18.850  1033  2012 I ActivityManager: Killing 6459:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-29 18:40:18.955  1033  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_6459/cgroup.procs: No such file or directory
,08-29 18:40:19.201  7842  7842 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-29 18:40:19.271  7842  7842 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 18:40:19.271  7842  7842 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 18:40:19.316  7842  7842 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 18:40:19.334  7842  7842 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 18:40:19.335  7842  7842 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 18:40:19.350  7842  7842 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 18:40:19.350  7842  7842 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-29 18:40:19.366  1033  1573 I ActivityManager: Killing 7164:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-29 18:40:19.462  1033  1908 W libprocessgroup: failed to open /acct/uid_10046/pid_7164/cgroup.procs: No such file or directory
,08-29 18:40:19.476  3524  6274 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 18:40:19.481  3524  6274 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3bbb525a on behalf of 7842
,08-29 18:40:19.484  4643  7885 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-29 18:40:19.552  1033  2012 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7886 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 18:40:19.617  7842  7842 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 18:40:19.644  7842  7842 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-29 18:40:19.656  7886  7886 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 18:40:19.680  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-29 18:40:19.680  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-29 18:40:19.680  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-29 18:40:19.680  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-29 18:40:19.680  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-29 18:40:19.680  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-29 18:40:19.702  1033  1994 I ActivityManager: Killing 7183:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 18:40:19.796  1033  1573 W libprocessgroup: failed to open /acct/uid_10057/pid_7183/cgroup.procs: No such file or directory
,08-29 18:40:20.059  1033  2764 V SIM_STK : Menu title from STK is T-Mobile
,08-29 18:40:20.083  4643  7885 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 599 ms] updated apps [took 599 ms] 
,08-29 18:40:20.761  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:20.762  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@172ae38 added. We now have 6 listener(s)
,08-29 18:40:20.762  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:20.775  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:20.775  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6396e11 added. We now have 7 listener(s)
08-29 18:40:20.775  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:20.776  6657  6749 I System.out: IsBluetoothEnabled
08-29 18:40:20.777  1033  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:20.777  1033  2013 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 18:40:20.778  1033  1095 D BluetoothManagerService: Message: 2
08-29 18:40:20.781  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:20.783  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:20.783  1033  1049 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 18:40:20.804  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:20.805  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:20.805  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-29 18:40:20.808  1033  1095 D BluetoothManagerService: Message: 1
08-29 18:40:20.808  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 18:40:20.834  1033  1095 D BluetoothManagerService: Message: 20
08-29 18:40:20.834  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67d7955:true
,08-29 18:40:20.838  7705  7705 D BluetoothAdapterState: make
08-29 18:40:20.843  7705  7705 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create,
08-29 18:40:20.843  7705  7705 I bluedroid-qcom: init
08-29 18:40:20.844  7705  7930 I BluetoothAdapterState: Entering OffState
08-29 18:40:20.844  7705  7705 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 18:40:20.845  7705  7705 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 18:40:20.845  7705  7705 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 18:40:20.845  7705  7705 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 18:40:20.845  7705  7705 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 18:40:20.847  7705  7705 I bluedroid-qcom: get_profile_interface socket
08-29 18:40:20.847  7705  7705 I bluedroid-qcom: get_profile_interface map_client
,08-29 18:40:20.852  7705  7934 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 18:40:20.842  7933  7933 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:20.857  7705  7934 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 18:40:20.842  7933  7933 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:20.867  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-29 18:40:20.872  1033  1095 D BluetoothManagerService: Message: 40
08-29 18:40:20.872  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 18:40:20.873  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 18:40:20.874  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 18:40:20.874  7705  7721 I bluedroid-qcom: config_hci_snoop_log
08-29 18:40:20.876  7933  7933 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 18:40:20.876  7933  7933 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 18:40:20.876  7933  7933 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 18:40:20.876  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 18:40:20.877  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 18:40:20.879  7933  7933 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-29 18:40:20.883  7705  7934 D BluetoothAdapterProperties: Name is: G3
08-29 18:40:20.886  7933  7933 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 18:40:20.886  7933  7933 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 18:40:20.890  7705  7930 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 18:40:20.890  7705  7930 D BluetoothAdapterProperties: Setting state to 11
08-29 18:40:20.890  7705  7930 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 18:40:20.891  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:20.891  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 18:40:20.891  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-29 18:40:20.898  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:20.899  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 18:40:20.903  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:20.905  6895  6895 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-29 18:40:20.920  7705  7705 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 18:40:20.921  7705  7705 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:20.921  7705  7705 V BluetoothPbapReceiver: ***********state = 11
,08-29 18:40:20.922  7705  7930 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 18:40:20.928  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:20.939  7705  7930 D BluetoothBondStateMachine: make
,08-29 18:40:20.943  6895  6895 D BluetoothPermissionRequest: onReceive
08-29 18:40:20.944  7705  7949 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 18:40:20.946  7705  7930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:20.946  7705  7930 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 18:40:20.946  7705  7930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:20.946  7705  7930 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 18:40:20.947  7705  7930 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 18:40:20.948  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:20.951  7705  7930 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:20.958  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:20.961  7705  7705 D HeadsetService: Received start request. Starting profile...
08-29 18:40:20.962  7705  7930 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:20.962  7705  7705 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 18:40:20.962  7705  7705 D LGBluetoothHfpAdapter: Version 1.6
08-29 18:40:20.966  7705  7705 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 18:40:20.967  7705  7705 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 18:40:20.968  7705  7705 D HeadsetStateMachine: make
08-29 18:40:20.968  7705  7930 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:20.975  7705  7930 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 18:40:20.980  7705  7930 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:20.986  7705  7930 E BluetoothAdapterService: File transfer profiles supported!!
08-29 18:40:20.991  7705  7930 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 18:40:21.006  7705  7930 V LGMDMManager: Create singleton instance
,08-29 18:40:21.007  7705  7705 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 18:40:21.007  7705  7705 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 18:40:21.008  7705  7930 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 18:40:21.012  7705  7705 D HeadsetStateMachine: max_hf_connections = 1
08-29 18:40:21.013  7705  7705 I bluedroid-qcom: get_profile_interface handsfree
08-29 18:40:21.015  7705  7705 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 18:40:21.016   325  1401 V AudioPolicyService: registerClient() client 0xb101ef40, uid 1002
08-29 18:40:21.016   325  1400 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 18:40:21.016   325  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 18:40:21.016   325  1400 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 18:40:21.016  7705  7705 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 18:40:21.016   325  2172 V AudioFlinger: registerClient() client 0xb1433880, pid 7705
08-29 18:40:21.017   325  1396 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:21.017   325  1396 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:21.017  1852  2460 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:21.017  1852  2460 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-29 18:40:21.017   325  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:21.017   325  1395 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:21.017  1601  2103 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:21.017  1601  2103 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:21.017  1601  2103 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:21.017  1601  2103 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:21.017  1852  2460 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:21.017  1852  2460 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:21.017  3458  3473 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:21.017  3458  3473 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:21.017  3458  3473 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:21.017  3458  3473 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:21.017  7705  7721 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:21.017  7705  7721 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 18:40:21.017  7705  7721 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:21.017  7705  7721 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 18:40:21.017  7705  7705 V ToneGenerator: Create Track: 0xb4928080
08-29 18:40:21.017  7705  7705 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 18:40:21.017  7705  7705 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 18:40:21.017   325  2163 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 18:40:21.017   325  2163 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 18:40:21.018   325  2163 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 18:40:21.018   325  2163 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 18:40:21.018  1033  1573 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 18:40:21.018  1033  1573 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 18:40:21.018  1033  1573 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 18:40:21.018  1033  1573 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 18:40:21.018   325  1401 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 18:40:21.018   325  1400 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 18:40:21.018   325  1400 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
,08-29 18:40:21.018   325  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 18:40:21.018   325  1400 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 18:40:21.018  7705  7705 V AudioSystem: getLatency() output 2, latency 50
08-29 18:40:21.018  7705  7705 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 18:40:21.018  7705  7705 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 18:40:21.018   325  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 18:40:21.018   325  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 18:40:21.018   325  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 18:40:21.018   325  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 18:40:21.018   325  2172 V AudioFlinger: createTrack() lSessionId: 21
08-29 18:40:21.019  7705  7705 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 18:40:21.019   325  2172 V AudioFlinger: acquiring 21 from 7705, for 7705
08-29 18:40:21.019   325  2172 V AudioFlinger:  added new entry for 21
08-29 18:40:21.019  7705  7705 V ToneGenerator: ToneGenerator INIT OK, time: 135887
08-29 18:40:21.020  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.020  7705  7952 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 18:40:21.020  7705  7952 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 18:40:21.021  7705  7952 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 18:40:21.021  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.021  7705  7952 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 18:40:21.021  7705  7705 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:21.021  7705  7705 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:21.021  7705  7705 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 18:40:21.021  7705  7705 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:21.021  7705  7705 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 18:40:21.024   325   325 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7705
08-29 18:40:21.025  7705  7705 D A2dpService: Received start request. Starting profile...
08-29 18:40:21.026  7705  7705 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 18:40:21.026   325   325 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 18:40:21.026   325   325 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 18:40:21.026   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 18:40:21.026   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 18:40:21.026   325   325 V voice   : voice_set_parameters: exit with code(0)
08-29 18:40:21.026   325   325 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 18:40:21.026   325   325 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 18:40:21.026   325   325 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 18:40:21.027   325   325 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 18:40:21.027   325   325 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 18:40:21.027   325   325 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 18:40:21.027  7705  7952 V ToneGenerator: ToneGenerator destructor
08-29 18:40:21.027  7705  7952 V ToneGenerator: stopTone
08-29 18:40:21.027  7705  7952 V ToneGenerator: Delete Track: 0xb4928080
08-29 18:40:21.027  7705  7705 V Avrcp   ,: make
08-29 18:40:21.027  7705  7952 V AudioTrack: ~AudioTrack, releasing session id from 7705 on behalf of 7705
08-29 18:40:21.027   325  2172 V AudioFlinger: releasing 21 from 7705 for 7705
08-29 18:40:21.027   325  2172 V AudioFlinger:  decremented refcount to 0
08-29 18:40:21.027   325  2172 V AudioFlinger: purging stale effects
08-29 18:40:21.027   325  2172 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 18:40:21.027   325  2172 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 18:40:21.027   325  2172 V AudioFlinger: PlaybackThread::Track destructor
08-29 18:40:21.027   325  1226 V AudioPolicyService: AudioCommandThread() waking up
08-29 18:40:21.027   325  2172 V AudioFlinger: removeClient_l() pid 7705, calling pid 325
08-29 18:40:21.027   325  1226 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 18:40:21.027   325  1226 V AudioPolicyManager: releaseOutput() 2
08-29 18:40:21.027   325  1226 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 18:40:21.027  7705  7705 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 18:40:21.028  7705  7705 I bluedroid-qcom: get_profile_interface avrcp
08-29 18:40:21.036  7705  7705 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 18:40:21.038  7705  7705 E AudioManager: No RCC entry present to update
,08-29 18:40:21.038  7705  7705 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 18:40:21.042  7705  7705 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 18:40:21.043  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 18:40:21.043  7705  7705 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 18:40:21.046  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 18:40:21.142  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
08-29 18:40:21.142  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-29 18:40:21.214  1033  1953 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 18:40:21.224  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 18:40:21.228  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 18:40:21.228  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 18:40:21.228  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 18:40:21.228  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 18:40:21.229  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 18:40:21.229  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 18:40:21.229  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 18:40:21.229  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 18:40:21.229  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 18:40:21.229  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 18:40:21.229  7705  7705 I BluetoothA2dpServiceJni: classInitNative
08-29 18:40:21.229  7705  7705 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:21.229  7705  7705 D A2dpStateMachine: make
,08-29 18:40:21.234  7705  7705 I bluedroid-qcom: get_profile_interface a2dp
,08-29 18:40:21.234  7705  7959 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 18:40:21.237  7705  7705 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:21.237  7705  7705 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 18:40:21.238  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.238  7705  7958 D A2dpStateMachine: Enter Disconnected: -2
08-29 18:40:21.238  7705  7705 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 18:40:21.240  7705  7705 D HidService: Received start request. Starting profile...
08-29 18:40:21.240  7705  7705 I bluedroid-qcom: get_profile_interface hidhost
08-29 18:40:21.240  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.240  7705  7705 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 18:40:21.242  7705  7705 D HealthService: Received start request. Starting profile...
,08-29 18:40:21.246  7705  7705 I bluedroid-qcom: get_profile_interface health
08-29 18:40:21.247  7705  7705 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,08-29 18:40:21.247  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.247  7705  7705 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 18:40:21.249  7705  7705 D PanService: Received start request. Starting profile...
08-29 18:40:21.249  7705  7705 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 18:40:21.249  7705  7705 I bluedroid-qcom: get_profile_interface pan
08-29 18:40:21.256  7705  7705 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 18:40:21.256  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.257  7705  7705 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-29 18:40:21.261  7705  7705 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 18:40:21.262  7705  7705 D BtGatt.GattService: Received start request. Starting profile...
08-29 18:40:21.262  7705  7705 D BtGatt.GattService: start()
08-29 18:40:21.262  7705  7705 I bluedroid-qcom: get_profile_interface gatt
08-29 18:40:21.262  7705  7705 D BtGatt.AdvertiseManager: advertise manager created
08-29 18:40:21.273  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
,08-29 18:40:21.274  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
,08-29 18:40:21.274  7705  7705 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 18:40:21.275  7705  7705 V BluetoothMapService: BluetoothMapBinder()
08-29 18:40:21.275  7705  7705 D BluetoothMapService: Received start request. Starting profile...
08-29 18:40:21.275  7705  7705 D BluetoothMapService: start()
08-29 18:40:21.279  7705  7705 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 18:40:21.280  7705  7705 D BluetoothMapEmailAppObserver: createReceiver()
08-29 18:40:21.281  7705  7705 D BluetoothMapEmailAppObserver: initObservers()
08-29 18:40:21.281  7705  7705 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 18:40:21.286  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.286  7705  7705 D HeadsetStateMachine: Proxy object connected
,08-29 18:40:21.287  7705  7705 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 18:40:21.287  7705  7705 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 18:40:21.290  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 18:40:21.290  7705  7952 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 18:40:21.290  7705  7952 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 18:40:21.290  7705  7952 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 18:40:21.293  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 18:40:21.298  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 18:40:21.300  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 18:40:21.303  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 18:40:21.303  7705  7705 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 18:40:21.305  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 18:40:21.306  7705  7705 V BluetoothMapService: Handler(): got msg=1
08-29 18:40:21.307  7705  7930 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 18:40:21.307  7705  7930 I bluedroid-qcom: enable
08-29 18:40:21.307  7705  7969 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 18:40:21.308  7705  7969 I bt-btu  : btu_task pending for preload complete event
08-29 18:40:21.308  7705  7930 I bt_hci_bdroid: init
08-29 18:40:21.311  7705  7930 I bt_vendor: bt-vendor : init
08-29 18:40:21.311  7705  7930 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 18:40:21.311  7705  7930 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 18:40:21.311  7705  7930 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 18:40:21.311  7705  7930 D bt_userial_mct: userial_init
08-29 18:40:21.312  7705  7930 D bt_hci_bdroid: set_power 1
08-29 18:40:21.312  7705  7930 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 18:40:21.312  7705  7930 I bt_vendor: Starting hciattach daemon
08-29 18:40:21.312  7705  7930 I bt_vendor: try to set true
,08-29 18:40:21.302  7972  7972 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 18:40:21.302  7972  7972 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:21.330  7975  7975 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 18:40:21.365  7982  7982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 18:40:21.371  7983  7983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-29 18:40:21.387  7985  7985 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 18:40:21.395  7986  7986 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 18:40:21.402  7987  7987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 18:40:21.410  7988  7988 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-29 18:40:21.425  7990  7990 I libmdmdetect: ESOC framework not supported
08-29 18:40:21.425  7990  7990 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 18:40:21.435  7990  7990 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 18:40:21.435  7990  7990 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 18:40:21.435  7990  7990 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 18:40:21.435  7990  7990 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 18:40:21.435  7990  7990 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 18:40:21.435  7990  7990 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 18:40:21.435  7990  7990 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 18:40:21.476  7990  7991 E QC-QMI  : qmi_client [7990] 15: failed to locate client data
08-29 18:40:21.476   452   452 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 18:40:21.476   452   452 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-29 18:40:21.512  7992  7992 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 18:40:21.528  7993  7993 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-29 18:40:21.568  7705  7930 I bt_vendor: bluetooth satus is on
08-29 18:40:21.568  7705  7930 D bt_hci_bdroid: preload
08-29 18:40:21.569  7705  7971 D bt_userial_mct: userial_open(port:0)
,08-29 18:40:21.569  7705  7971 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 18:40:21.573  7705  7971 I bt_vendor: Done intiailizing UART
08-29 18:40:21.578  7705  7971 I bt_vendor: Done intiailizing UART
08-29 18:40:21.578  7705  7971 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 18:40:21.578  7705  7971 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 18:40:21.578  7705  7969 I bt-btu  : btu_task received preload complete event
08-29 18:40:21.579  7705  7995 D bt_userial_mct: Entering userial_read_thread()
08-29 18:40:21.580  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 18:40:21.581  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 18:40:21.588  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-29 18:40:21.597  7705  7969 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 18:40:21.598  7705  7969 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 18:40:21.704  7705  7969 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-29 18:40:21.704  7705  7969 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01de061 
08-29 18:40:21.704  7705  7969 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01de061 
,08-29 18:40:21.732  7705  7934 E bt-btif : Calling BTA_HhEnable
08-29 18:40:21.732  7705  7934 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 18:40:21.732  7705  7934 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 18:40:21.736  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-29 18:40:21.736  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 18:40:21.737  7705  7934 D BluetoothAdapterProperties: Name is: G3
,08-29 18:40:21.738  7705  7934 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:21.739  7705  7934 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 18:40:21.739  7705  7934 D bt_hci_bdroid: postload
08-29 18:40:21.739  7705  7934 D bte_conf: Device ID record 1 : primary
08-29 18:40:21.739  7705  7934 D bte_conf:   vendorId            = 00c4
08-29 18:40:21.740  7705  7934 D bte_conf:   vendorIdSource      = 0001
08-29 18:40:21.740  7705  7934 D bte_conf:   product             = 13a1
08-29 18:40:21.740  7705  7934 D bte_conf:   version             = 1000
08-29 18:40:21.740  7705  7934 D bte_conf:   clientExecutableURL = 
08-29 18:40:21.740  7705  7934 D bte_conf:   serviceDescription  = 
08-29 18:40:21.740  7705  7934 D bte_conf:   documentationURL    = 
08-29 18:40:21.740  7705  7934 D bte_conf: bte_load_did_conf no section named DID2.
08-29 18:40:21.742  7705  7971 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 18:40:21.742  7705  7971 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 18:40:21.746  7705  7930 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 18:40:21.747  7705  7930 D BluetoothAdapterProperties: ScanMode =  20
08-29 18:40:21.747  7705  7930 D BluetoothAdapterProperties: State =  11
08-29 18:40:21.747  7705  7930 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 18:40:21.747  7705  7930 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 18:40:21.747  7705  7930 D BluetoothAdapterProperties: Setting state to 12
08-29 18:40:21.747  7705  7930 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 18:40:21.754  7705  7934 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 18:40:21.742  8000  8000 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:21.757  1033  1095 D BluetoothManagerService: Message: 60
08-29 18:40:21.757  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 18:40:21.757  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-29 18:40:21.758  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:21.742  8000  8000 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:21.776  1852  2461 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:21.782  7705  7930 I BluetoothAdapterState: Entering On State
08-29 18:40:21.784  7705  7995 E bt_mct  : hci lib postload completed
08-29 18:40:21.788  7705  7934 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 18:40:21.788  7705  7934 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 18:40:21.801  7705  7930 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 18:40:21.801  7705  7930 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 18:40:21.801  7705  7930 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 18:40:21.805  7705  7930 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 18:40:21.812  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 18:40:21.816  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 18:40:21.816  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 18:40:21.816  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-29 18:40:21.819  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-29 18:40:21.819  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 18:40:21.819  7705  7969 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 18:40:21.819  7705  7934 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 18:40:21.835  7705  7930 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 18:40:21.846  6895  6911 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:21.854  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:21.858  7705  7969 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:21.858  7705  7969 W bt-smp  : Plain text(LSB ~ MSB) = e0 5f 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:21.858  7705  7969 W bt-smp  : Encrypted text(LSB ~ MSB) = db 83 4c 22 26 d3 9a 62 07 53 c4 e6 03 e2 d7 f5 
08-29 18:40:21.858  7705  7969 W bt-btm  : Stopping oneshot timer
08-29 18:40:21.862  6895  7619 D BluetoothPan: onBluetoothStateChange on: true
08-29 18:40:21.863  6895  7619 D BluetoothPan: onBluetoothStateChange call bindService
08-29 18:40:21.868  8016  8016 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 18:40:21.868  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:21.869  6895  6911 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:21.872  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:21.872  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18233b76 added. We now have 8 listener(s)
08-29 18:40:21.872  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:21.873  6895  6895 D BluetoothMap: Proxy object connected
08-29 18:40:21.873  6895  6895 D MapProfile: Bluetooth service connected
08-29 18:40:21.873  6895  6895 D BluetoothMap: getConnectedDevices()
08-29 18:40:21.875  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:21.876  7705  7722 V BluetoothMapService: getConnectedDevices()
08-29 18:40:21.877  1033  1033 D BluetoothHeadset: Proxy object connected
08-29 18:40:21.878  1033  2013 D WifiServiceImplEx: setWifiEnabled: false pid=6657, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 18:40:21.878  1033  2013 D WifiService: setWifiEnabled: false pid=6657, uid=10118
08-29 18:40:21.878  1033  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 18:40:21.879  1852  4026 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:21.880  7705  7969 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:21.880  7705  7969 W bt-smp  : Plain text(LSB ~ MSB) = b8 76 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:21.880  7705  7969 W bt-smp  : Encrypted text(LSB ~ MSB) = 0c 1e 40 1c c5 8e 60 b0 b9 aa e3 9d ec e4 0f da 
08-29 18:40:21.880  7705  7969 W bt-btm  : Stopping oneshot timer
08-29 18:40:21.882  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 18:40:21.882  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 18:40:21.885  6895  6895 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 18:40:21.886  6895  6895 D PanProfile: Bluetooth service connected
08-29 18:40:21.888  6895  7619 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 18:40:21.889  1033  1033 D BluetoothA2dp: Proxy object connected
08-29 18:40:21.891  6895  6895 D BluetoothHeadset: Proxy object connected
08-29 18:40:21.892  6895  6895 D HeadsetProfile: Bluetooth service connected
08-29 18:40:21.892  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:21.893  1033  1729 D WifiServiceImplEx: setWifiEnabled: true pid=6657, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 18:40:21.893  1033  1729 D WifiService: setWifiEnabled: true pid=6657, uid=10118
08-29 18:40:21.893  1033  1729 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 18:40:21.894  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:21.897  7705  7969 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:21.897  7705  7969 W bt-smp  : Plain text(LSB ~ MSB) = f2 4f 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:21.897  7705  7969 W bt-smp  : Encrypted text(LSB ~ MSB) = 23 09 ed 5c 14 b8 0d 44 c9 e6 db 9e 80 ba be 03 
08-29 18:40:21.897  7705  7969 W bt-btm  : Stopping oneshot timer
08-29 18:40:21.899  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 18:40:21.899  6895  6911 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 18:40:21.902  6895  6910 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 18:40:21.902  6895  6895 D BluetoothA2dp: Proxy object connected
08-29 18:40:21.902  6895  6895 D A2dpProfile: Bluetooth service connected
08-29 18:40:21.906  1033  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 18:40:21.906  1033  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 18:40:21.907  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 18:40:21.907  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 18:40:21.907  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 18:40:21.907  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 18:40:21.907  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 18:40:21.907  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-29 18:40:21.907  1033  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 18:40:21.908  1033  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 18:40:21.908  1033  1390 E WifiHW  : unknown target_country: EU , set to default
08-29 18:40:21.908  1033  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 18:40:21.908  1033  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 18:40:21.908  1033  1390 I WifiUtil: gEnableBmps=1
08-29 18:40:21.911  6895  6895 D BluetoothInputDevice: Proxy object connected
08-29 18:40:21.911  6895  6895 D HidProfile: Bluetooth service connected
08-29 18:40:21.912  7705  7969 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:21.912  7705  7969 W bt-smp  : Plain text(LSB ~ MSB) = 06 35 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:21.912  7705  7969 W bt-smp  : Encrypted text(LSB ~ MSB) = 02 26 b9 8c 01 d7 f0 eb f0 48 58 2f 21 0e db ca 
08-29 18:40:21.912  7705  7969 W bt-btm  : Stopping oneshot timer
08-29 18:40:21.914  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 18:40:21.915  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 18:40:21.916  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 18:40:21.916  1033  1095 D BluetoothManagerService: Message: 40
08-29 18:40:21.916  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 18:40:21.917  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:21.917  1941  2125 D LGBluetoothAPIService: Message: 1
08-29 18:40:21.917  1941  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 18:40:21.917  1941  2125 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 18:40:21.917  1941  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 18:40:21.918  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:21.926  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:21.928  7705  7969 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 18:40:21.928  7705  7969 W bt-smp  : Plain text(LSB ~ MSB) = c2 8f 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 18:40:21.929  7705  7969 W bt-smp  : Encrypted text(LSB ~ MSB) = a1 58 71 2a 16 8c 85 b9 c7 66 39 3c 58 3e f7 54 
08-29 18:40:21.929  7705  7969 W bt-btm  : Stopping oneshot timer
08-29 18:40:21.929  7705  7705 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:21.930  7705  7705 D BluetoothMapService: STATE_ON
08-29 18:40:21.932  6895  6895 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 18:40:21.933  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:21.935  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 18:40:21.941  6895  6895 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:21.950  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:21.950  7705  7705 V BluetoothPbapService: Pbap Service onCreate
08-29 18:40:21.950  7705  7705 V BluetoothPbapService: Starting PBAP service
08-29 18:40:21.951  7705  7705 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 18:40:21.951  7705  7705 V BluetoothPbapService: Pbap Service onBind
08-29 18:40:21.952  7705  7705 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:21.952  6895  6895 D BluetoothPbap: Proxy object connected
08-29 18:40:21.952  6895  6895 D PbapServerProfile: Bluetooth service connected
08-29 18:40:21.952  7705  7705 V BluetoothPbapService: state: 12
08-29 18:40:21.953  7705  7705 V BluetoothMapService: Handler(): got msg=1
08-29 18:40:21.953  7705  7705 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 18:40:21.954  7705  7705 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 18:40:21.954  7705  7705 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:21.954  7705  7705 V BluetoothPbapReceiver: ***********state = 12
08-29 18:40:21.955  7705  8029 D BluetoothMapMasInstance: MAS initSocket()
08-29 18:40:21.956  7705  7705 V BluetoothPbapService: Handler(): got msg=1
08-29 18:40:21.956  7705  7705 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 18:40:21.956  7705  8029 D BluetoothMapMasInstance:   masId = 00
08-29 18:40:21.956  7705  8029 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 18:40:21.956  7705  8029 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 18:40:21.956  7705  8029 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 18:40:21.957  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:21.958  2193  2193 D c       : Getting all permits...
08-29 18:40:21.958  2193  2193 D a       : Opening database...
08-29 18:40:21.958  7705  8030 V BluetoothPbapService: Pbap Service initSocket
08-29 18:40:21.959  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:21.959  1033  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:21.960  7705  8029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:21.961  7705  8030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:21.962  7705  8029 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 18:40:21.962  7705  8029 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 18:40:21.962  7705  8029 D BluetoothMapMasInstance: Accepting socket connection...
08-29 18:40:21.962  7705  7934 D BluetoothAdapterProperties: Scan Mode:21
08-29 18:40:21.962  7705  7934 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 18:40:21.964  7705  8030 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 18:40:21.964  7705  8030 V BluetoothPbapService: Succeed to create listening socket 
08-29 18:40:21.964  7705  8030 V BluetoothPbapService: Accepting socket connection...
08-29 18:40:21.965  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:21.965  2193  2193 D a       : Opening database auth.proximity.permit_store...
08-29 18:40:21.966  2193  2193 D a       : Closing database...
,08-29 18:40:21.979  6895  6895 D BluetoothPermissionRequest: onReceive
,08-29 18:40:21.981  6895  6895 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 18:40:21.983  6895  6895 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 18:40:21.986  7705  7705 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 18:40:21.987  7705  7705 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 18:40:21.994  7705  7705 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 18:40:22.026  7705  7705 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 18:40:22.026  7705  7705 V BtOppService: onCreate
,08-29 18:40:22.031  7705  7705 V BluetoothOppNotification: send message
,08-29 18:40:22.035  7705  7705 V BtOppService: Starting RfcommListener
08-29 18:40:22.044  7705  7705 D BluetoothOppPreference: Dumping Names:  
08-29 18:40:22.044  7705  7705 D BluetoothOppPreference: {}
08-29 18:40:22.044  7705  7705 D BluetoothOppPreference: Dumping Channels:  
08-29 18:40:22.044  7705  7705 D BluetoothOppPreference: {}
,08-29 18:40:22.048  7705  7705 V BtOppService: onStartCommand
08-29 18:40:22.051  7705  8036 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 18:40:22.052  7705  8033 V BtOppService: Deleted complete outbound shares, number =  0
08-29 18:40:22.052  7705  8036 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 18:40:22.055  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:22.056  7705  8033 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 18:40:22.056  7705  8036 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e62d7b9 on behalf of 
08-29 18:40:22.056  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 18:40:22.056  7705  8033 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 18:40:22.057  7705  8036 V BluetoothOppNotification: update too frequent, put in queue
,08-29 18:40:22.076  7705  7705 V BluetoothOppNotification: new notify threadi!
,08-29 18:40:22.077  7705  7705 V BluetoothOppNotification: send delay message
,08-29 18:40:22.078  7705  7705 V BtOppService: start RfcommListener
08-29 18:40:22.082  7705  8037 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 18:40:22.083  7705  7705 V BtOppService: RfcommListener started
08-29 18:40:22.084  7705  7705 V BtOppService: ContentObserver received notification
08-29 18:40:22.084  7705  7705 V BtOppService: ContentObserver received notification
08-29 18:40:22.087  7705  8038 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 18:40:22.088  1033  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:22.089  7705  8038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:22.091  7705  8038 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 18:40:22.091  7705  8038 V BtOppRfcommListener: Started RFCOMM listener....
08-29 18:40:22.092  7705  8038 I BtOppRfcommListener: Accept thread started.
08-29 18:40:22.092  7705  8038 V BtOppRfcommListener: Accepting connection...
,08-29 18:40:22.113  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
,08-29 18:40:22.113  7705  7705 V BluetoothFtpService: Ftp Service onCreate
08-29 18:40:22.113  7705  7705 I BluetoothFtpService: Ftp Service onCreate
08-29 18:40:22.114  7705  7705 V BluetoothFtpService: Ftp Service onStartCommand
08-29 18:40:22.114  7705  7705 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:22.114  7705  7705 V BluetoothFtpService: Starting Listening on sockets
08-29 18:40:22.114  7705  7705 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 18:40:22.114  7705  7705 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 18:40:22.114  7705  7705 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 18:40:22.114  7705  7705 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:22.115  7705  7705 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 18:40:22.115  7705  7705 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 18:40:22.118  7705  7705 V BluetoothFtpService: Handler(): got msg=1
08-29 18:40:22.121  7705  7705 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 18:40:22.121  7705  7705 V BluetoothFtpService: Ftp Service initSocket
08-29 18:40:22.127  1033  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:22.128  7705  7705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:22.129  7705  7705 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-29 18:40:22.129  7705  7705 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 18:40:22.140  7705  8039 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-29 18:40:22.146  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95e5d6d
08-29 18:40:22.147  7705  7705 V BluetoothSapService: Sap Service onCreate
08-29 18:40:22.149  7705  7705 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:22.149  7705  7705 V BluetoothSapService: state: 12
08-29 18:40:22.149  7705  7705 V BluetoothSapService: Starting SAP server process
08-29 18:40:22.132  8040  8040 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:22.152  7705  7705 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 18:40:22.142  8040  8040 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 18:40:22.164  7705  8041 V BluetoothSapService: Sap Service initRfcommSocket
08-29 18:40:22.164  1033  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:22.165  7705  8041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:22.166  8040  8040 V BT_SAP  : Event pipe created
08-29 18:40:22.166  8040  8040 V BT_SAP  : create_server_socket qcom.sap.server
08-29 18:40:22.166  8040  8040 V BT_SAP  : created socket fd 6
08-29 18:40:22.166  7705  8041 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
08-29 18:40:22.166  7705  8041 V BluetoothSapService: Succeed to create listening socket 
08-29 18:40:22.166  7705  8041 V BluetoothSapService: Accepting socket connection...
08-29 18:40:22.218  1033  2013 I art     : Explicit concurrent mark sweep GC freed 27615(1346KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.724ms total 158.468ms
,08-29 18:40:22.219  7705  8037 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@263d060a on behalf of 
,08-29 18:40:22.219  7705  8036 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 18:40:22.219  7705  8036 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 18:40:22.220  7705  8037 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 18:40:22.220  7705  8033 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@158ece7b on behalf of 
08-29 18:40:22.221  7705  8036 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ed99498 on behalf of 
08-29 18:40:22.225  7705  8037 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:22.226  7705  8036 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 18:40:22.229  7705  8037 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@337ac4f1 on behalf of 
08-29 18:40:22.232  7705  8037 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 18:40:22.234  7705  8037 V BluetoothOppNotification: outbound notification was removed.
08-29 18:40:22.235  7705  8037 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:22.238  7705  8037 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16ad78d6 on behalf of 
08-29 18:40:22.240  7705  8037 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 18:40:22.242  7705  8037 V BluetoothOppNotification: inbound notification was removed.
08-29 18:40:22.242  7705  8037 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 18:40:22.245  7705  8037 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e31d757 on behalf of 
,08-29 18:40:22.736   321   900 D SoftapController: Softap fwReload - Ok
,08-29 18:40:22.743  1033  1390 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (830ms)
08-29 18:40:22.773  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 18:40:22.789   321   900 D CommandListener: Setting iface cfg
08-29 18:40:22.789   321   900 D CommandListener: Trying to bring down wlan0
,08-29 18:40:22.795   321   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:22.814  1033  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 18:40:22.802  8058  8058 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 18:40:22.822  8058  8058 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 18:40:22.859  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:22.859  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:22.859  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 18:40:22.873  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 18:40:22.873  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 18:40:22.873  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 18:40:22.873  6895  6895 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-29 18:40:22.878  8058  8058 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 18:40:22.905  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 18:40:22.906  1033  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 18:40:22.906  1033  1390 D WifiMonitor: connecting to supplicant
08-29 18:40:22.908  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 18:40:22.910  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 18:40:22.911  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:22.912  6895  6895 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 18:40:22.912  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 18:40:22.912  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 18:40:22.913  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 18:40:22.913  6895  6895 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 18:40:22.913  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 18:40:22.914  8058  8058 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 18:40:22.914  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:22.914  6895  6895 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 18:40:22.914  8058  8058 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-29 18:40:22.916  1033  1095 D Tethering: InitialState.processMessage what=4
08-29 18:40:22.917  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 18:40:22.967  1033  1772 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8076 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 18:40:23.010  8058  8058 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 18:40:23.035  8058  8058 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 18:40:23.042  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 18:40:23.042  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 18:40:23.043  8058  8058 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 18:40:23.043  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 18:40:23.043  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 18:40:23.043  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 18:40:23.043  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 18:40:23.043  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 18:40:23.043  1033  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 18:40:23.043  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.044  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.044  1033  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.045  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.045  1033  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 18:40:23.045  1033  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 18:40:23.046  1033  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 18:40:23.046  1033  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 18:40:23.046  1033  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 18:40:23.046  1033  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 18:40:23.046  1033  1390 E WifiStateMachine: useWiFiOffloading() : false
08-29 18:40:23.046  1033  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 18:40:23.047  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.047  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.047  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.047  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.047  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-29 18:40:23.049  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-29 18:40:23.050  1033  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 18:40:23.050  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 18:40:23.051  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.051  1033  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 18:40:23.051  1033  1390 D WifiNative-wlan0: SET update_config 1: returned true
08-29 18:40:23.053  1033  1390 D WifiConfigStore: Loading config and enabling all networks 
08-29 18:40:23.053  1033  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:23.054  6657  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:23.055  1033  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 18:40:23.058  6657  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:23.063  1033  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-29 18:40:23.073  1033  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 18:40:23.074  1033  1390 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 18:40:23.079  7705  7705 V BluetoothOppNotification: new notify threadi!
08-29 18:40:23.079  7705  7705 V BluetoothOppNotification: send delay message
,08-29 18:40:23.080  7705  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 18:40:23.082  7705  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f1f6244 on behalf of 
08-29 18:40:23.082  7705  8097 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 18:40:23.084  7705  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:23.084  7705  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14e5bf2d on behalf of 
08-29 18:40:23.085  7705  8097 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 18:40:23.086  7705  8097 V BluetoothOppNotification: outbound notification was removed.
08-29 18:40:23.087  7705  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 18:40:23.087  7705  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fe04c62 on behalf of 
08-29 18:40:23.088  7705  8097 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 18:40:23.089  7705  8097 V BluetoothOppNotification: inbound notification was removed.
08-29 18:40:23.089  7705  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 18:40:23.090  7705  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f9291f3 on behalf of 
,08-29 18:40:23.106  1033  2012 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8099 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 18:40:23.108  1033  1390 D WifiStateMachine: enableVerboseLogging : level 2
08-29 18:40:23.108  1033  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-29 18:40:23.110  8076  8096 W FormManager: Network not available. Please check & try again.
08-29 18:40:23.111  1033  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 18:40:23.111  1033  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 18:40:23.112  1033  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 18:40:23.112  1033  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 18:40:23.112  1033  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 18:40:23.112  1033  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 18:40:23.113  1033  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 18:40:23.113  1033  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 18:40:23.113  1033  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 18:40:23.113  1033  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 18:40:23.113  1033  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 18:40:23.113  1033  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 18:40:23.114  1033  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 18:40:23.114  1033  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 18:40:23.114  1033  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 18:40:23.115  1033  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 18:40:23.115  1033  1390 D WifiNative-HAL: Setting external_sim to 1
08-29 18:40:23.115  1033  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 18:40:23.115  1033  1390 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 18:40:23.115  1033  1390 I WifiNative-HAL: startHal
08-29 18:40:23.115  1033  1390 D wifi    : setting scan oui 0xaf669c60
08-29 18:40:23.115  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-29 18:40:23.115  1941  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 18:40:23.115  1941  2296 D WfdsService: Set the WFDS Monitor: true
08-29 18:40:23.115  1941  2296 D WfdsMonitor: WfdsMonitorThread create
08-29 18:40:23.116  1941  2296 D WfdsMonitor: WFDS Monitor is created and started
08-29 18:40:23.116  1941  2296 D WfdsService: WiFi: Supplicant connection re-established
08-29 18:40:23.116  1033  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 18:40:23.116  1033  1390 I WifiNative-HAL: startHal
08-29 18:40:23.116  1033  1390 D wifi    : setting scan oui 0xaf669c60
08-29 18:40:23.116  7736  7736 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.116  1033  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 18:40:23.116  1033  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 18:40:23.116  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 18:40:23.116  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 18:40:23.117  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 18:40:23.117  1941  8108 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 18:40:23.117  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 18:40:23.117  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 18:40:23.117  1941  8108 E CtrlSupplicant: Succeed to open control connection
,08-29 18:40:23.118  1941  8108 E CtrlSupplicant: Succeed to open monitor connection
08-29 18:40:23.118  1941  8108 D WfdsMonitor: Supplicant connection established
08-29 18:40:23.118  1941  2296 D WfdsService: Connected to the supplicant for wfds
08-29 18:40:23.119  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 18:40:23.119  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 18:40:23.119  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 18:40:23.119  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 18:40:23.119  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 18:40:23.119  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-29 18:40:23.120  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 18:40:23.120  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 18:40:23.120  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-29 18:40:23.126  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 18:40:23.126  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 18:40:23.127  8058  8058 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 18:40:23.127  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 18:40:23.127  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 18:40:23.127  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 18:40:23.127  1033  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 18:40:23.127   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 21.569ms
08-29 18:40:23.128  1033  1390 E WifiNative: : [137,982,366 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 18:40:23.128  1033  1390 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 18:40:23.129  1033  1390 D WifiNative-wlan0: RECONNECT: returned true
08-29 18:40:23.129  1033  1390 D WifiNative-wlan0: doString: [STATUS]
08-29 18:40:23.129  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 18:40:23.129  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 18:40:23.130  1033  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 18:40:23.130  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 18:40:23.130  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:23.130  1033  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.132   321   900 D CommandListener: Setting iface cfg
08-29 18:40:23.132   321   900 D CommandListener: Trying to bring up p2p0
08-29 18:40:23.132  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 18:40:23.132  1033  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 18:40:23.132  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-29 18:40:23.132  1033  1389 D LGWifiP2pService: P2pEnablingState
08-29 18:40:23.132  1033  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.132  1033  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.132  1033  1389 D LGWifiP2pService: P2p socket connection successful
08-29 18:40:23.132  1033  1389 D LGWifiP2pService: P2pEnabledState
08-29 18:40:23.133  1033  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.133  1033  1554 I WifiNative-HAL: startHal
08-29 18:40:23.133  1033  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf669c60
08-29 18:40:23.133  1033  1554 D wifi    : failed to get capabilities : -3
08-29 18:40:23.133  1033  1554 E WifiScanningService: could not get scan capabilities
08-29 18:40:23.134  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 18:40:23.134  1941  1941 D WfdsService: WifiP2pState is changed : true
08-29 18:40:23.134  1941  2296 D WfdsService: Receive the WFDS_ENABLE Method
08-29 18:40:23.134  1941  2296 D WfdsService: Set the WFDS Monitor: true
08-29 18:40:23.134  1941  2296 D WfdsService: Connected to the supplicant for wfds
08-29 18:40:23.134  1941  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
,08-29 18:40:23.135  8058  8058 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 18:40:23.135  1941  2296 D WfdsService: selectPreferredScanChannel [36]
08-29 18:40:23.135  1941  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 18:40:23.137  1033  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 18:40:23.138  1033  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 18:40:23.139  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 18:40:23.139  1033  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 18:40:23.139  1033  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 18:40:23.140  1033  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 18:40:23.140  1941  1941 D WfdsService: isConnected: false
08-29 18:40:23.140  1033  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-29 18:40:23.140  1033  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 18:40:23.140  1033  1389 D LGWifiP2pService: before postfix = G3
08-29 18:40:23.140  1033  1389 D WifiServerServiceExt: postfix byte check : 2
08-29 18:40:23.140  1033  1389 D LGWifiP2pService: after postfix = G3
08-29 18:40:23.140  1033  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 18:40:23.140  1033  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 18:40:23.140  1033  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 18:40:23.140  1033  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 18:40:23.141  1033  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 18:40:23.141  1033  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 18:40:23.141  1033  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 18:40:23.141  1033  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 18:40:23.141  1033  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 18:40:23.141  1033  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-29 18:40:23.141  1033  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 18:40:23.142  1033  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 18:40:23.142  1033  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 18:40:23.142  1033  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 18:40:23.142  1033  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 18:40:23.143  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 18:40:23.143  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 18:40:23.143  1941  1941 D WfdsService: Update P2p Interface State: 3
08-29 18:40:23.143  1033  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 18:40:23.143  1033  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 18:40:23.144  1033  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 18:40:23.144  1033  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 18:40:23.144  1033  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 18:40:23.145  1033  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 18:40:23.145  1033  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 18:40:23.146  1033  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 18:40:23.146  1033  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 18:40:23.146  1033  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-29 18:40:23.148   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 19.318ms
08-29 18:40:23.149  8076  8098 V FormManager: Network unavailable.
08-29 18:40:23.154  8076  8098 V FormManager: Network unavailable.
08-29 18:40:23.154  8058  8058 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 18:40:23.154  1033  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 18:40:23.154  1033  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 18:40:23.154  1033  1389 D LGWifiP2pService: InactiveState
08-29 18:40:23.154  1033  1389 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.154  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.154  1033  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 18:40:23.155  1033  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 18:40:23.155  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.155  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 18:40:23.155  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.155  1033  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.155  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.155  8058  8058 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.156  8058  8058 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 18:40:23.156  8058  8058 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.156  8058  8058 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.157  1941  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 18:40:23.157  1941  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:23.157  1941  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-29 18:40:23.157  1033  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 18:40:23.157  1033  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.157  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.157  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.157  1033  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:23.157  1033  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.157  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.157  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.157  1033  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:23.157  1033  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.158  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.158  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.158  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.158  1033  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.158  1033  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 18:40:23.158  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.158  1033  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.158  1941  2296 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 18:40:23.159  1033  1389 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.159  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.159  1033  1389 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.159  1033  1033 E WifiServerServiceExt: No p2p device connected
08-29 18:40:23.160  1033  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 18:40:23.160  1033  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 18:40:23.160  1033  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 18:40:23.160  1033  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 18:40:23.160  8058  8058 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 18:40:23.161  1033  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 18:40:23.161  1033  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 18:40:23.161  1033  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 18:40:23.161  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 18:40:23.162  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 18:40:23.162  8058  8058 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.162  8058  8058 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 18:40:23.162  8058  8058 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.163  8058  8058 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.164  1941  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-29 18:40:23.164  1941  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:23.164  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 18:40:23.164  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.164  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.164  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 18:40:23.164  1033  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:23.164  1033  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.164  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.164  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.164  1033  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 18:40:23.164  1033  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.164  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.164  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 18:40:23.165  1033  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 18:40:23.165  1033  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 18:40:23.165  1033  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 18:40:23.166  1033  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 18:40:23.166  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 18:40:23.166  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 18:40:23.166  8058  8058 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:23.166   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 359us total 18ms
08-29 18:40:23.167  1033  1389 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.167  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 18:40:23.167  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:23.167  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.167  1033  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:23.167  1033  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 18:40:23.167  1033  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 18:40:23.167  1033  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 18:40:23.168  1033  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 18:40:23.168  1033  1390 D WifiNative-wlan0: doBoolean: SCAN
08-29 18:40:23.168  1033  1390 D WifiNative-wlan0: SCAN: returned false
08-29 18:40:23.168  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=138023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 18:40:23.169  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=138024  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 18:40:23.169  1033  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:23.,169  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:23.170  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:23.170  1033  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:23.170  1033  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:23.170  1033  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:23.171  1033  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 18:40:23.171  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.171  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.171  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 18:40:23.171  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.171  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:23.172  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-29 18:40:23.177  1033  1953 I ActivityManager: Killing 7201:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-29 18:40:23.196  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 18:40:23.225  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 18:40:23.225  1033  1923 W libprocessgroup: failed to open /acct/uid_10062/pid_7201/cgroup.procs: No such file or directory
,08-29 18:40:23.230  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:23.231  1033  2042 I ActivityManager: Killing 7221:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 18:40:23.338  1033  1048 W libprocessgroup: failed to open /acct/uid_10085/pid_7221/cgroup.procs: No such file or directory
,08-29 18:40:23.365  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 18:40:23.366  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 18:40:23.366  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 18:40:23.366  6895  6895 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 18:40:23.366  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 18:40:23.368  6895  6895 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 18:40:23.368  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 18:40:23.368  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 18:40:23.368  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 18:40:23.368  6895  6895 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 18:40:23.368  6895  6895 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-29 18:40:23.383  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 18:40:23.390  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:23.402  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:23.419  8076  8122 W FormManager: Network not available. Please check & try again.
,08-29 18:40:23.426  8076  8123 V FormManager: Network unavailable.
08-29 18:40:23.433  8076  8123 V FormManager: Network unavailable.
,08-29 18:40:23.446  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 18:40:23.447  4362  4362 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 18:40:23.452  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 18:40:23.456  4362  4362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 18:40:23.462  4362  8124 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 18:40:23.471  4362  8125 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 18:40:23.471  4362  8125 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 18:40:23.528  1033  1953 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8126 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 18:40:23.664  8126  8126 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 18:40:23.664  8126  8126 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 18:40:23.672  8126  8126 V [BNRBootReceiver]: Boot Receiver Return
08-29 18:40:23.680  8126  8126 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 18:40:23.728  1033  2764 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8147 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 18:40:23.728  1033  2764 I ActivityManager: Killing 7256:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-29 18:40:23.766  8058  8058 E wpa_supplicant: USIM:  scard_init function
08-29 18:40:23.766  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 18:40:23.766  1033  8093 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 18:40:23.766  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 18:40:23.766  8058  8058 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 18:40:23.766  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-29 18:40:23.766  1033  8093 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 18:40:23.766  1033  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-29 18:40:23.767  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-29 18:40:23.767  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 18:40:23.767  1033  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 18:40:23.768  1033  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 18:40:23.768  1033  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 18:40:23.768  1033  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 18:40:23.846  1033  1049 W libprocessgroup: failed to open /acct/uid_10093/pid_7256/cgroup.procs: No such file or directory
,08-29 18:40:23.867  1033  1377 V AlarmManager: RTC_WAKEUP set : Alarm{167d6b7e type 0 when 1472488823338 android} when 1472488823338
08-29 18:40:23.868  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2b9b58df type 2 when 138647 com.google.android.gms} when 138647
,08-29 18:40:23.869  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138723  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 18:40:23.872  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138727  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 18:40:23.878  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.878  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.878  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 18:40:23.878  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.878  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.878  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 18:40:23.880  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:23.881  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:23.881  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:23.881  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 18:40:23.882  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.885  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:23.885  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:23.886  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.888  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 18:40:23.890  8058  8058 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 18:40:23.893  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 18:40:23.894  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 18:40:23.894  1033  1390 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.894  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 18:40:23.894  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 18:40:23.894  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:23.894  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:23.894  1033  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.895  1033  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.895  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.895  1033  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 18:40:23.896  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138750  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 18:40:23.896  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138751  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 18:40:23.897  1033  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138752
08-29 18:40:23.897  1033  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138752
08-29 18:40:23.898  1033  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138752
08-29 18:40:23.898  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138753
08-29 18:40:23.899  1033  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138753
08-29 18:40:23.901  8058  8058 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:40:23.901  8058  8058 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 18:40:23.902  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138756  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 18:40:23.903  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:23.903  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:23.903  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-29 18:40:23.903  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:40:23.903  1033  8093 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:40:23.903  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 18:40:23.903  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 18:40:23.904  1033  8093 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 18:40:23.904  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 18:40:23.904  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:23.909  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:23.909  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:23.910  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.912  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.912  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.912  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 18:40:23.913  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.913  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.913  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 18:40:23.914  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 18:40:23.915  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:23.915  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 18:40:23.916  1033  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138770  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 18:40:23.917  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138771  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 18:40:23.917  1033  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138772
08-29 18:40:23.918  1033  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138772
08-29 18:40:23.918  1033  1390 D WifiNative-wlan0: doString: [STATUS]
08-29 18:40:23.919  1033  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-29 18:40:23.919  1033  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 18:40:23.920  1033  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:23.921  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:23.922  1033  1390 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 18:40:23.923  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:23.929  1033  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 18:40:23.929  1033  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-29 18:40:23.933  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.933  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.933  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 18:40:23.937  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.937  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:23.937  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 18:40:23.939  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:23.939  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:23.941  6657  6749 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 18:40:23.941  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.942  6657  6749 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 18:40:23.943  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:23.943  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 18:40:23.944  1033  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 18:40:23.944  1033  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:23.944  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.944  1033  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 18:40:23.945  1033  1409 D ConnectivityService: Got NetworkAgent Messenger
08-29 18:40:23.945  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 18:40:23.945  1033  1409 D ConnectivityService: NetworkAgent connected
08-29 18:40:23.945  1033  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 18:40:23.945  1033  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 18:40:23.946  6657  6749 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@35775f08 Bundle[{}]
08-29 18:40:23.947  6657  6749 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 18:40:23.948  6657  6749 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 18:40:23.948  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:23.948  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:23.949  6657  6749 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 18:40:23.950  1033  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 18:40:23.950  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.950  1033  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:23.950  1033  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 18:40:23.950  6657  6749 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 18:40:23.950  1033  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 18:40:23.950  1033  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 18:40:23.951  6657  6749 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 18:40:23.952  8147  8147 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 18:40:23.952  6657  6749 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 18:40:23.955  1033  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 18:40:23.956   321   900 D CommandListener: Setting iface cfg
,08-29 18:40:23.961  6657  6749 I System.out: Running OutgoingSocketThread
08-29 18:40:23.964  1033  1390 E WifiStateMachine: Start Dhcp Watchdog 3
08-29 18:40:23.964  1033  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138819  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:23.964  6657  8166 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
08-29 18:40:23.965  1033  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138819  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:23.965  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138820  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:23.966  6657  8166 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58181
08-29 18:40:23.966  6657  8166 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 18:40:23.967  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:23.967  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 18:40:23.968  1033  8165 D DhcpStateMachine: StoppedState
08-29 18:40:23.968  1033  8165 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.968  1033  8165 D DhcpStateMachine: WaitBeforeStartState
08-29 18:40:23.968  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:23.968  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 18:40:23.969  1033  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138824  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:23.970  1033  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138824  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:23.970  1033  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138824  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 18:40:23.972  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13615] from screen [on:0 period:-684958556] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 18:40:23.973  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-684958555] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 18:40:23.973  1033  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 18:40:23.976  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:23.979  1033  1409 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-29 18:40:23.979  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:23.980  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:23.980  1033  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:23.980  1033  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:23.981  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:23.981  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 18:40:23.982  1033  1409 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 18:40:23.983  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:23.983  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-29 18:40:23.985  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
08-29 18:40:23.985  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
08-29 18:40:23.985  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 18:40:23.985  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-29 18:40:23.986  1033  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 18:40:23.986  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 18:40:23.986  1033  1390 D WifiNative-wlan0: SET ps 0: returned true
08-29 18:40:23.986  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,08-29 18:40:23.987  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 18:40:23.987  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 18:40:23.987  1033  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d700b60 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.987  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d700b60 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.988  1033  8165 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.988  1033  8165 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 18:40:23.988  1033  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 18:40:23.988  1033  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 18:40:23.988  1033  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 18:40:23.989   321   900 D CommandListener: Setting iface cfg
08-29 18:40:23.989   321   900 D CommandListener: Trying to bring up wlan0
08-29 18:40:23.990  1033  1390 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 18:40:23.992  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 18:40:23.992  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 18:40:23.992  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 18:40:23.992  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 18:40:23.993  1033  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.993  1033  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:23.993  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 18:40:23.993  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 18:40:23.994  1033  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 18:40:23.994  1033  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 18:40:23.994  8058  8058 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 18:40:23.994  1033  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 18:40:23.995  1033  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 18:40:23.997  8147  8147 D PluginManager: init()
,08-29 18:40:24.013  1033  1390 D WifiNative-wlan0: SET ps 1: returned true
08-29 18:40:24.014  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 18:40:24.014  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:24.015  1033  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:24.015  1033  1409 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 18:40:24.015  1033  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:24.015  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:24.016  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:24.016  1033  1409 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 18:40:24.017  1033  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 18:40:24.017  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 18:40:24.017  1033  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 18:40:24.017  1033  1409 D ConnectivityService: ignoring duplicate network state non-change
08-29 18:40:24.020  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:24.020  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:24.022  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.022  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.022  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 18:40:24.024  1033  1409 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 18:40:24.025  1033  1409 D ConnectivityService: Adding iface wlan0 to network 102
08-29 18:40:24.025  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 18:40:24.028  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 18:40:24.028  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 18:40:24.029  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.029  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.029  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 18:40:24.030  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:24.031  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 18:40:24.034  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 18:40:24.034  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.034  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.034  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 18:40:24.036  1033  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 18:40:24.037  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 18:40:24.047  1033  1409 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 18:40:24.047  1033  1409 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 18:40:24.048  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:24.048  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 18:40:24.048  1033  1409 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-29 18:40:24.048  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:24.049   321   900 E Netd    : netlink response contains error (File exists)
08-29 18:40:24.049  1033  1409 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 18:40:24.050  1033  1409 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 18:40:24.050  1033  1409 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-29 18:40:24.050  1033  1409 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-29 18:40:24.050  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.050  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 18:40:24.050  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 18:40:24.051  1033  1409 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 18:40:24.051  1033  1409 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:24.051  1033  1409 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:24.051  1033  1409 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 18:40:24.051  1033  1409 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:24.051  1033  1409 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:24.052  1033  1409 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 18:40:24.052  1033  1409 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.052  1033  1409 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 18:40:24.052  1033  1409 D ConnectivityService: currentScore = 0, newScore = 20
08-29 18:40:24.052  1033  1409 D ConnectivityService:    accepting network in place of null
08-29 18:40:24.052  1033  1409 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.053  1033  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:24.053  1033  1409 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,209715,2,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 18:40:24.053  1033  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 18:40:24.053  1033  1409 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 18:40:24.053  1033  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:24.054  1033  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 18:40:24.054  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:40:24.054  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.054  1033  1409 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:24.054  1033  1409 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 18:40:24.054  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 18:40:24.054  1033  1409 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 18:40:24.055  1033  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.055  1033  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:24.056  1033  1409 D ConnectivityService: validation of new default Network = false
08-29 18:40:24.056  1033  1409 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 18:40:24.056  1033  1409 D DSQN    : enableDataServiceNotify 
08-29 18:40:24.056  1033  1409 D DSQN    : start dsqn bin
08-29 18:40:24.057  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 18:40:24.057  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 18:40:24.057  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 18:40:24.057  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 18:40:24.058   321  8176 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 18:40:24.058   321  8176 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 18:40:24.042  8177  8177 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40,:24.042  8177  8177 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:24.063  1033  1409 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:24.063  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.063  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:24.063  1033  1409 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:24.071  1601  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 18:40:24.072  1033  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 18:40:24.073  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:24.073  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 18:40:24.073  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:24.074  8177  8177 E DSQN    : DSQN ssw
,08-29 18:40:24.089  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 18:40:24.090  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:24.090  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:24.114   321  8176 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 18:40:24.145   321   899 D LGDataListener: argv[0]=dsqncommand
08-29 18:40:24.145   321   899 D LGDataListener: argv[1]=wlan0
08-29 18:40:24.146   321   899 D LGDataListener: argv[2]=1
08-29 18:40:24.146   321   899 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 18:40:24.147  1033  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 18:40:24.147  1033  1093 D DSQN    : start to monitor internet connection
,08-29 18:40:24.177  1033  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 16:40:24 GMT], X-Android-Received-Millis=[1472488824177], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472488824144]}
08-29 18:40:24.178  1033  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 18:40:24.178  1033  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 18:40:24.178  1033  1409 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-29 18:40:24.178  1033  1409 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 18:40:24.178  1033  1409 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:24.178  1033  1409 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:24.178  1033  1409 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 18:40:24.178  1033  1409 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-29 18:40:24.178  1033  1409 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:24.178  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.178  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:24.179  1033  1409 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:24.179  1033  1409 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.179  1601  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 18:40:24.179  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 18:40:24.180  1033  1390 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.180  1033  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 18:40:24.183  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:24.184  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 18:40:24.190  1033  8165 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 18:40:24.192  1033  8165 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 18:40:24.192  1033  8165 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 18:40:24.182  8183  8183 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:24.182  8183  8183 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 18:40:24.202  8183  8183 I dhcpcd  : version 5.5.6 starting
08-29 18:40:24.203  8183  8183 E dhcpcd  : get_duid: m
08-29 18:40:24.203  8183  8183 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 18:40:24.203  8183  8183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 18:40:24.210  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-29 18:40:24.211  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:24.212  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:24.302  8183  8183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 18:40:24.303  8183  8183 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 18:40:24.303  8183  8183 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 18:40:24.303  8183  8183 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 18:40:24.304  8183  8183 D dhcpcd  : wlan0: sending REQUEST (xid 0x5ff9d6ca), next in 3.63 seconds
,08-29 18:40:24.343  8183  8183 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 18:40:24.356  8147  8147 W ExternalStrings: load override strings
08-29 18:40:24.356  8147  8147 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 18:40:24.356  8147  8147 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 18:40:24.358  8147  8147 D StatusProvider: onCreate
,08-29 18:40:24.363  8183  8183 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 18:40:24.363  8183  8183 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 18:40:24.363  8183  8183 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 18:40:24.364  8183  8183 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 18:40:24.365  8183  8183 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 18:40:24.365  8183  8183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 18:40:24.366  8183  8183 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 18:40:24.366  8183  8183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 18:40:24.396  8147  8147 V Signer  : override build config not found
08-29 18:40:24.396  8147  8147 D Signer  : value of property debug is false
,08-29 18:40:24.419  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-29 18:40:24.419  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-29 18:40:24.419  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-29 18:40:24.419  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-29 18:40:24.420  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-29 18:40:24.420  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-29 18:40:24.420  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-29 18:40:24.420  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-29 18:40:24.420  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-29 18:40:24.420  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,08-29 18:40:24.421  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-29 18:40:24.421  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-29 18:40:24.421  8147  8147 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-29 18:40:24.428  8147  8147 V LGMDMManager: Create singleton instance
08-29 18:40:24.464  8147  8147 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-29 18:40:24.550  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:24.559  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 18:40:24.559  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.566  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:24.577  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.578  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.579  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 18:40:24.584  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 18:40:24.587  6895  6895 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 18:40:24.590  1033  1908 I ActivityManager: Killing 7290:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-29 18:40:24.591  1033  1390 E WifiStateMachine:  ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-44 f=2437 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=88.0 fiv=20000 [on:0 tx:0 rx:0 period:613] from screen [on:0 period:-684957937]
,08-29 18:40:24.592  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-44 f=2437 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=88.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-684957936]
08-29 18:40:24.593  1033  1390 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=82.50 rxSuccessRate=88.00 targetRoamBSSID=any RSSI=-44
08-29 18:40:24.695  1033  1648 W libprocessgroup: failed to open /acct/uid_10005/pid_7290/cgroup.procs: No such file or directory
,08-29 18:40:24.697  8147  8207 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 18:40:24.712   321  8224 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 18:40:24.713   321  8224 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-29 18:40:24.714  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.715  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.729  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.737  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.744   321  8224 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-29 18:40:24.748  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 18:40:24.749  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.751  6964  6964 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 18:40:24.759  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.759  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 18:40:24.772  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.778  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:24.787  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.788  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.789  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:24.793  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 18:40:24.793  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 18:40:24.793  6895  6895 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-29 18:40:24.793  6895  6895 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 18:40:24.793  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 18:40:24.794  6895  6895 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 18:40:24.794  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 18:40:24.794  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 18:40:24.794  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 18:40:24.794  6895  6895 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 18:40:24.794  6895  6895 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 18:40:24.794  6895  6895 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 18:40:24.797  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.797  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.798  1033  8165 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 18:40:24.801  1033  8165 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 18:40:24.801  1033  8165 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 18:40:24.802  1033  8165 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 18:40:24.802  1033  8165 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 18:40:24.802  1033  8165 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 18:40:24.802  1033  8165 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 18:40:24.802  1033  8165 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 18:40:24.802  1033  8165 D DhcpStateMachine: RunningState
08-29 18:40:24.803  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.812  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.820  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 18:40:24.821  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.821  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:24.827  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.827  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.837  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.842  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.850  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.850  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.851  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 18:40:24.855  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.855  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.861  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.866  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.873  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.873  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.874  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 18:40:24.877  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.878  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.883  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.888  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 18:40:24.893  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.893  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.894  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:24.901  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.901  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 18:40:24.911  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.915  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.921  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.921  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.922  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:24.926  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 18:40:24.926  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.931  8147  8207 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:24.932  8147  8207 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 18:40:24.933  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 18:40:24.939  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.945  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.945  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.946  6964  6964 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 18:40:24.949  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.949  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 18:40:24.952  8099  8099 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 18:40:24.954  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:24.956  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 18:40:24.960  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.963  6657  6749 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
08-29 18:40:24.963  6657  6749 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
08-29 18:40:24.966  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:24.967  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:24.967  6657  6749 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
08-29 18:40:24.967  6964  6964 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 18:40:24.968  6964  6964 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 18:40:24.968  6657  6749 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 18:40:24.968  6657  6749 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
08-29 18:40:24.968  6964  6964 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 18:40:24.973  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 18:40:24.973  8147  8209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 18:40:24.974  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:24.974  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36627577 added. We now have 2 listener(s)
,08-29 18:40:24.977  8099  8099 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 18:40:24.977  1033  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:24.978  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 18:40:24.979  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:24.980  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:24.980  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:24.980  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:24.980  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c075e4 added. We now have 9 listener(s)
08-29 18:40:24.980  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:24.980  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:24.982  6895  6895 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 18:40:24.982  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:24.985  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:24.986  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:24.986  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:24.986  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:24.986  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ff9902 added. We now have 3 listener(s)
08-29 18:40:24.986  1033  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:24.988  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:24.988  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:24.988  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:24.988  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:24.989  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfef213 added. We now have 10 listener(s)
08-29 18:40:24.989  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:24.989  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:24.989  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:24.989  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:24.989  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:24.989  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:24.989  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:24.989  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:24.989  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36627577 removed from the list
08-29 18:40:24.989  6657  6749 I org.thaliproject.p2p.btconnectorlib.Disco,veryManager: dispose
08-29 18:40:24.989  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c075e4 removed from the list
08-29 18:40:24.990  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:24.990  6895  6895 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 18:40:24.990  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:24.990  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:24.992  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:24.992  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:24.994  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:24.994  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:24.994  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:24.994  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:24.994  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c075e4 not in the list
08-29 18:40:24.994  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:24.994  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:24.995  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:24.995  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:24.995  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:24.995  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfef213 removed from the list
08-29 18:40:24.995  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:24.995  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:24.995  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:24.995  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:24.995  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ff9902 removed from the list
08-29 18:40:24.996  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:24.996  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11010c50 added. We now have 2 listener(s)
08-29 18:40:25.000  6964  6964 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 18:40:25.000  1033  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.001  6964  6964 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 18:40:25.003  6964  6964 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 18:40:25.004  6964  6964 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 18:40:25.004  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.004  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.004  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.004  6964  6964 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 18:40:25.004  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.004  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2512ce49 added. We now have 9 listener(s)
08-29 18:40:25.004  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.006  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:25.008  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.008  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:25.011  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:25.011  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.012  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.012  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:25.013  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:25.013  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34dc9c6f added. We now have 3 listener(s)
08-29 18:40:25.014  1033  2042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.014  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.016  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.016  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.016  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.016  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.016  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26729d7c added. We now have 10 listener(s)
08-29 18:40:25.016  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.016  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:25.016  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:25.016  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:25.016  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:25.016  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:25.017  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.017  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.019  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:40:25.020  1033  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.023  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 18:40:25.023  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.024  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:25.026  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:25.026  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:25.027  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.028  6657  6749 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 18:40:25.029  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:25.029  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:25.029  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.031  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-29 18:40:25.033  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:25.033  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.033  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:25.033  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:25.033  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.033  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.033  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:25.033  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.033  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11010c50 removed from the list
08-29 18:40:25.033  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.033  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2512ce49 removed from the list
08-29 18:40:25.033  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:25.034  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.036  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.037  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.037  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.038  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.038  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.038  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.038  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2512ce49 not in the list
08-29 18:40:25.038  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.038  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.038  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.039  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:25.039  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:25.039  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.039  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.039  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26729d7c removed from the list
08-29 18:40:25.039  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.039  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.039  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.039  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.039  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34dc9c6f removed from the list
08-29 18:40:25.039  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.040  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:25.040  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2740908b added. We now have 2 listener(s)
08-29 18:40:25.041  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 18:40:25.042  1033  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.044  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.044  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.044  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.044  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.044  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390a1568 added. We now have 9 listener(s)
08-29 18:40:25.044  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.044  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:25.048  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:25.051  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:25.053  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.053  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:25.053  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:25.053  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25af6e26 added. We now have 3 listener(s)
08-29 18:40:25.054  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.055  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.056  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.056  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.056  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.056  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.056  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.057  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a5aa67 added. We now have 10 listener(s)
08-29 18:40:25.057  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.057  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:25.057  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:25.057  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:25.057  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:25.057  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:25.057  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:25.060  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:40:25.060  1033  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.061  8147  8207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-29 18:40:25.063  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 18:40:25.064  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:25.065  2193  8234 D GCM     : Connected
08-29 18:40:25.066  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:25.068  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:25.069  6657  6749 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 18:40:25.070  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:25.070  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:25.070  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:25.070  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.070  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.070  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:25.070  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.070  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2740908b removed from the list
08-29 18:40:25.070  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.070  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390a1568 removed from the list
08-29 18:40:25.070  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:25.070  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:25.073  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.073  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.073  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.073  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.073  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.074  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390a1568 not in the list
08-29 18:40:25.074  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.074  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.074  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.074  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:25.075  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:25.075  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.075  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.075  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a5aa67 removed from the list
08-29 18:40:25.075  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.075  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.075  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.075  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.075  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25af6e26 removed from the list
08-29 18:40:25.075  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:25.076  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79446b2 added. We now have 2 listener(s)
08-29 18:40:25.076  1033  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.077  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.077  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.077  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.077  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.077  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7588603 added. We now have 9 listener(s)
08-29 18:40:25.077  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.078  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:25.079  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:25.081  2193  8234 D GCM     : Message class com.google.e.a.a.q
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:25.082  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:25.083  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.083  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:25.084  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:25.084  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2baedbb9 added. We now have 3 listener(s)
08-29 18:40:25.084  1033  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.085  8147  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-29 18:40:25.090  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.091  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.092  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.092  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.092  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.092  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.092  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7c1bfe added. We now have 10 listener(s)
08-29 18:40:25.092  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.092  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:25.093  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:25.093  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:25.093  8147  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-29 18:40:25.093  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:25.093  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:25.093  8147  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 18:40:25.094  8147  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 18:40:25.097  8147  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-29 18:40:25.098  8147  8207 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-29 18:40:25.098  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:40:25.098  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.100  8147  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-29 18:40:25.102  8147  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-29 18:40:25.103  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 18:40:25.104  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:25.105  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:25.105  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:25.107  6657  6749 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 18:40:25.108  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:25.108  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:25.108  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:25.108  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.108  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.108  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:25.108  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.109  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79446b2 removed from the list
08-29 18:40:25.109  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.109  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7588603 removed from the list
08-29 18:40:25.109  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:25.109  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:25.113  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.113  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.113  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.113  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.113  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.113  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7588603 not in the list
08-29 18:40:25.113  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.114  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.114  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.115  6657  6749 D BluetoothLeScanner: could not find callback wrapper
08-29 18:40:25.115  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:25.115  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.115  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.115  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7c1bfe removed from the list
08-29 18:40:25.115  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.115  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.115  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.115  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.115  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2baedbb9 removed from the list
08-29 18:40:25.116  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:25.116  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20587a75 added. We now have 2 listener(s)
08-29 18:40:25.116  1033  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.118  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.118  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.118  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.118  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.118  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2679fa0a added. We now have 9 listener(s)
08-29 18:40:25.118  6657  6749 D org.thaliproject.p2p.btconnectorlib.uti,ls.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.119  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:25.120  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:25.122  6657  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:25.124  6657  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:25.124  6657  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:25.124  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:25.124  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa1a898 added. We now have 3 listener(s)
08-29 18:40:25.125  1033  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 18:40:25.128  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 18:40:25.128  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:25.128  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:25.128  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.128  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.128  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c348f1 added. We now have 10 listener(s)
08-29 18:40:25.128  6657  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:25.129  6657  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:25.129  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:25.129  6657  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:25.129  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.129  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.129  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:25.129  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.129  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20587a75 removed from the list
08-29 18:40:25.129  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.129  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2679fa0a removed from the list
08-29 18:40:25.130  6657  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:25.130  6657  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:25.130  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.130  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.130  6657  6749 D org.thal,iproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.131  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.131  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.131  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.131  6657  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2679fa0a not in the list
08-29 18:40:25.131  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.131  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.132  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:25.132  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:25.132  6657  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:25.132  6657  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c348f1 removed from the list
08-29 18:40:25.132  6657  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:25.132  6657  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:25.132  6657  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:25.132  6657  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:25.132  6657  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa1a898 removed from the list
08-29 18:40:25.134  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 18:40:25.134  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 18:40:25.134  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 18:40:25.134  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 18:40:25.134  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 18:40:25.134  6657  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:25.145  6657  8238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
08-29 18:40:25.146  6657  8238 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
08-29 18:40:25.146  6657  8238 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 18:40:25.150  6657  8239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
08-29 18:40:25.150  6657  8239 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-29 18:40:25.150  6657  8239 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 18:40:25.152  6657  6749 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 18:40:25.152  6657  6749 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 18:40:25.152  6657  6749 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 18:40:25.152  6657  6749 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 18:40:25.152  6657  6749 D com.test.thalitest.ThaliTestRunner: Total duration: 22932 ms
08-29 18:40:25.155  6657  6749 I jxcore-log: *Native tests were executed*
08-29 18:40:25.155  6657  6749 I jxcore-log: 
08-29 18:40:25.155  6657  6749 I jxcore-log: Total number of executed tests:  80
08-29 18:40:25.155  6657  6749 I jxcore-log: 
08-29 18:40:25.155  6657  6749 I jxcore-log: Number of passed tests:  80
08-29 18:40:25.155  6657  6749 I jxcore-log: 
08-29 18:40:25.156  6657  6749 I jxcore-log: Number of failed tests:  0
08-29 18:40:25.156  6657  6749 I jxcore-log: 
08-29 18:40:25.156  6657  6749 I jxcore-log: Number of ignored tests:  0
08-29 18:40:25.156  6657  6749 I jxcore-log: 
08-29 18:40:25.156  6657  6749 I jxcore-log: Total duration:  22932
08-29 18:40:25.156  6657  6749 I jxcore-log: 
08-29 18:40:25.156  6657  6749 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 18:40:25.156  6657  6749 I jxcore-log: 
08-29 18:40:25.159  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.159  6657  6749 I jxcore-log: 
08-29 18:40:25.163  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.163  6657  6749 I jxcore-log: 
,08-29 18:40:25.164  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.164  6657  6749 I jxcore-log: 
08-29 18:40:25.165  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.165  6657  6749 I jxcore-log: 
08-29 18:40:25.166  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.166  6657  6749 I jxcore-log: 
08-29 18:40:25.168  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.168  6657  6749 I jxcore-log: 
08-29 18:40:25.171  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.171  6657  6749 I jxcore-log: 
08-29 18:40:25.173  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:25.173  6657  6749 I jxcore-log: 
08-29 18:40:25.174  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:25.174  6657  6749 I jxcore-log: 
08-29 18:40:25.175  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.175  6657  6749 I jxcore-log: 
08-29 18:40:25.176  6657  6657 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 18:40:25.176  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.176  6657  6749 I jxcore-log: 
,08-29 18:40:25.178  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:25.178  6657  6749 I jxcore-log: 
08-29 18:40:25.179  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:25.179  6657  6749 I jxcore-log: 
08-29 18:40:25.179  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:25.179  6657  6749 I jxcore-log: 
08-29 18:40:25.180  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.180  6657  6749 I jxcore-log: 
08-29 18:40:25.181  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.181  6657  6749 I jxcore-log: 
08-29 18:40:25.182  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.182  6657  6749 I jxcore-log: 
08-29 18:40:25.183  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.183  6657  6749 I jxcore-log: 
08-29 18:40:25.184  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.184  6657  6749 I jxcore-log: 
08-29 18:40:25.185  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.185  6657  6749 I jxcore-log: 
08-29 18:40:25.186  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.186  6657  6749 I jxcore-log: 
08-29 18:40:25.186  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:25.186  6657  6749 I jxcore-log: 
08-29 18:40:25.187  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:25.187  6657  6749 I jxcore-log: 
08-29 18:40:25.188  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:25.188  6657  6749 I jxcore-log: 
,08-29 18:40:25.189  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.189  6657  6749 I jxcore-log: 
08-29 18:40:25.189  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.189  6657  6749 I jxcore-log: 
08-29 18:40:25.190  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.190  6657  6749 I jxcore-log: 
08-29 18:40:25.191  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.191  6657  6749 I jxcore-log: 
08-29 18:40:25.192  6657  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:25.192  6657  6749 I jxcore-log: 
08-29 18:40:25.247  1033  1390 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:25.249  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 18:40:25.250  1033  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:25.252  1033  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:25.254  1033  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:25.256  1033  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 18:40:25.258  1033  1409 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-29 18:40:25.258  1033  1409 D ConnectivityService: identical MTU - not setting
08-29 18:40:25.258  1033  1409 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 18:40:25.258  1033  1409 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:25.259  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:25.259  1033  1409 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:25.260  1033  1409 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 18:40:25.262  1601  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 18:40:25.502  8242  8242 D AndroidRuntime: 
08-29 18:40:25.502  8242  8242 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 18:40:25.507  8242  8242 D AndroidRuntime: CheckJNI is OFF
08-29 18:40:25.737  8242  8242 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 18:40:25.766  1033  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-29 18:40:25.767  1033  1091 I ActivityManager: Killing 6657:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-29 18:40:25.837  1033  2013 I WindowState: WIN DEATH: Window{183cd8d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 18:40:25.837  1033  1402 D WifiService: Client connection lost with reason: 4
,08-29 18:40:25.848  1033  2013 D InputDispatcher: Window went away: Window{183cd8d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 18:40:25.989  1033  1091 I ActivityManager:   Force finishing activity ActivityRecord{15bfd71f u0 com.test.thalitest/.MainActivity t6}
,08-29 18:40:26.056   344   360 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 18:40:26.057  1033  1048 W ActivityManager: Spurious death for ProcessRecord{3a98084a 6657:com.test.thalitest/u0a118}, curProc for 6657: null
08-29 18:40:26.057  1033  1107 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 18:40:26.061  1033  1107 I ActivityManager:   Force finishing activity ActivityRecord{15bfd71f u0 com.test.thalitest/.MainActivity t6 f}
08-29 18:40:26.061  1033  1107 W ActivityManager: Duplicate finish request for ActivityRecord{15bfd71f u0 com.test.thalitest/.MainActivity t6 f}
,08-29 18:40:26.090  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 18:40:26.090  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1c3a5e7d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 18:40:26.090  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 18:40:26.092  1941  2957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 18:40:26.092  1941  2957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f528172 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-29 18:40:26.097  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-29 18:40:26.104  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-29 18:40:26.111  1033  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 18:40:26.127  2485  2678 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 18:40:26.133  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-29 18:40:26.139  3831  3831 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 18:40:26.150  7705  7705 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 18:40:26.150  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 18:40:26.161  4528  4528 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 18:40:26.162  4528  4528 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 18:40:26.162  4528  4528 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 18:40:26.162  4528  4528 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 18:40:26.162  4528  4528 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 18:40:26.163  4528  4528 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 18:40:26.163  4528  4528 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 18:40:26.163  4528  4528 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 18:40:26.163  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:26.163  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:26.163  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 18:40:26.163  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 18:40:26.172  1033  2764 V SIM_STK : Menu title from STK is T-Mobile
,08-29 18:40:26.198  4643  4643 I art     : Explicit concurrent mark sweep GC freed 8224(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 571us total 117.325ms
,08-29 18:40:26.203  1033  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 18:40:26.215  8147  8147 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 18:40:26.221  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 18:40:26.222  2032  2105 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-29 18:40:26.228  1033  1033 D administrator: Handling package changes for user 0
08-29 18:40:26.243  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 18:40:26.244  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 18:40:26.245  1903  1903 D ActionManagerService: notifyUserLog: 1000003
,08-29 18:40:26.245  3831  4522 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-29 18:40:26.245  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 18:40:26.255  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-29 18:40:26.272  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-29 18:40:26.277  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 18:40:26.282  2193  2193 I ConfigService: onCreate
08-29 18:40:26.283  2193  2193 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 18:40:26.283  1869  1869 D SplitUIManager: split_name #11 / not available #0
,08-29 18:40:26.284  1869  1869 D SplitUIService: removed split : 
08-29 18:40:26.284  1601  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 18:40:26.284  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.286  1033  1772 V SIM_STK : Menu title from STK is T-Mobile
08-29 18:40:26.286  1033  1772 V SIM_STK : Menu title from STK is T-Mobile
08-29 18:40:26.288  1601  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 18:40:26.288  1601  1651 D KeyguardModel: createShortcutInfo...
,08-29 18:40:26.291  2193  2193 I ConfigService: onBind returning update interface
,08-29 18:40:26.295  2193  2193 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 18:40:26.295  2193  2193 I ConfigService: onBind returning config service
08-29 18:40:26.295  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 18:40:26.296  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 18:40:26.296  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-29 18:40:26.297  3831  4522 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 18:40:26.299  1601  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 18:40:26.300  1601  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:40:26.300  1601  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 18:40:26.301  1601  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 18:40:26.303  1601  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:26.316  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , display: false
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , animation: false }
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , display: false
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , animation: false }
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , display: false
08-29 18:40:26.318  2032  2032 I GBoardWebViewUtils: , animation: false }
08-29 18:40:26.319  1816  1816 I ConfigFetchService: service connected
08-29 18:40:26.319  1816  1816 I ConfigClient: service connected
,08-29 18:40:26.327  2032  8276 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 18:40:26.327  2193  2193 I ConfigService: onDestroy
08-29 18:40:26.327  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 18:40:26.328  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 18:40:26.332  1601  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 18:40:26.335  1601  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 18:40:26.335  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.338  1816  8277 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 18:40:26.341  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-29 18:40:26.341  1869  1869 I SplitUIService: split app #11
08-29 18:40:26.345  1601  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 18:40:26.345  1601  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 18:40:26.347  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 18:40:26.348  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-29 18:40:26.352  1601  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:26.353  1601  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 18:40:26.354  1601  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 18:40:26.354  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.358  1601  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:40:26.358  1601  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 18:40:26.358  1601  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 18:40:26.358  1601  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 18:40:26.359  1601  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:26.359  1601  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-29 18:40:26.360  1601  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 18:40:26.360  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.364  1033  1729 V SIM_STK : Menu title from STK is T-Mobile
08-29 18:40:26.371  1033  1908 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 18:40:26.372  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-29 18:40:26.373  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-29 18:40:26.373  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 18:40:26.380  1601  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 18:40:26.380  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.383  1601  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 18:40:26.383  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.390  1601  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:26.390  1601  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 18:40:26.395  1601  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 18:40:26.395  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.396  1601  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:26.396  1601  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 18:40:26.398  1601  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 18:40:26.398  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.399  1601  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:26.399  1601  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 18:40:26.400  1601  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 18:40:26.400  1601  1651 D KeyguardModel: createShortcutInfo...
08-29 18:40:26.406  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 18:40:26.406  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 18:40:26.407  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 18:40:26.419  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-29 18:40:26.419  1816  8285 I PeopleContactsSync: CP2 sync disabled
08-29 18:40:26.428  1816  4797 I Icing   : doRemovePackageData com.test.thalitest
08-29 18:40:26.428  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-29 18:40:26.428  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 18:40:26.429  1033  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-29 18:40:26.430  5987  8283 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-29 18:40:26.455  1816  8284 W GmsApplication: Using Auth Proxy for data requests.
,08-29 18:40:26.467  1816  8284 W GmsApplication: Using Auth Proxy for data requests.
,08-29 18:40:26.469  7092  7092 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-29 18:40:26.492  2379  8289 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 18:40:26.496  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-29 18:40:26.499  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 18:40:26.501  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 18:40:26.502  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 18:40:26.505  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 18:40:26.509   336   419 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 18:40:26.509  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-29 18:40:26.510  3227  8290 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 18:40:26.527  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 18:40:26.527  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 18:40:26.528  2032  2203 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 18:40:26.528  2032  2203 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-29 18:40:26.530  1033  1923 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8292 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-29 18:40:26.535  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f66315d u0 com.lge.launcher2/.Launcher t5} time:141402
08-29 18:40:26.543  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 18:40:26.544  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 18:40:26.544  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 18:40:26.552  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 18:40:26.553  2584  2584 D [Concierge]Service: onStartCommand(). Type : 8
08-29 18:40:26.553  2584  2584 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 18:40:26.554  2584  2584 D [Concierge]Service: Update widget ID : 11
08-29 18:40:26.556  2032  2032 D [Concierge]WidgetView: change position of spinner
,08-29 18:40:26.557  2584  2584 D [Concierge]Service: onStartCommand(). Type : 0
08-29 18:40:26.558  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1472488826558
08-29 18:40:26.569  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 680686517
08-29 18:40:26.569  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 18:40:26.570  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 18:40:26.572  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@33c80735
08-29 18:40:26.572  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 18:40:26.574  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 18:40:26.574  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 18:40:26.578  2193  2224 I art     : Explicit concurrent mark sweep GC freed 7999(487KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 1.050ms total 41.355ms
08-29 18:40:26.579  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 18:40:26.580  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 18:40:26.580  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 18:40:26.581  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472488713766, New one : 1472488826558
08-29 18:40:26.581  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-29 18:40:26.582  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 18:40:26.583  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 18:40:26.584  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 18:40:26.585  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 18:40:26.586  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 18:40:26.587  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 18:40:26.588  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 18:40:26.590  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 18:40:26.591  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 18:40:26.591  8292  8292 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:40:26.591  8292  8292 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 18:40:26.592  8292  8292 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 18:40:26.592  8292  8292 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 18:40:26.629  1033  1107 I art     : Explicit concurrent mark sweep GC freed 85965(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 6.844ms total 349.004ms
,08-29 18:40:26.635  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 18:40:26.645  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 18:40:26.645  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 18:40:26.647  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 18:40:26.666  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2973c386 time:141533
,08-29 18:40:26.675  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:40:26.680  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-29 18:40:26.684  8292  8292 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-29 18:40:26.686  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 18:40:26.694  8292  8292 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 18:40:26.713  8242  8242 D AndroidRuntime: Shutting down VM
,08-29 18:40:26.717  8292  8292 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 18:40:26.744  1033  1107 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8313 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 18:40:26.765  8292  8292 D LgDataFeature: LgDataFeature() Constructor: none
08-29 18:40:26.765  8292  8292 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 18:40:26.782  1033  1729 I ActivityManager: Killing 7736:com.google.android.talk/u0a72 (adj 15): empty #17
,08-29 18:40:26.793  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-29 18:40:26.828  2032  2954 I GBoardtInterface: onReloaded()
,08-29 18:40:26.830  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 18:40:26.894  1033  2012 W libprocessgroup: failed to open /acct/uid_10072/pid_7736/cgroup.procs: No such file or directory
,08-29 18:40:26.896  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 18:40:26.900  3831  3847 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 18:40:26.905  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-29 18:40:26.906  3831  4522 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 18:40:26.906  3831  4522 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 18:40:26.908  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-29 18:40:26.909  3831  4522 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-29 18:40:26.910  3831  4522 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 18:40:26.910  3831  4522 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 18:40:26.910  3831  4522 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 18:40:26.910  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 18:40:26.912  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 18:40:26.912  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 18:40:26.914  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-29 18:40:26.914  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 18:40:26.916  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 18:40:26.916  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-29 18:40:26.933  8292  8292 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-29 18:40:26.944  1033  1648 I ActivityManager: Killing 7842:com.android.vending/u0a44 (adj 15): empty #17
08-29 18:40:26.981  1033  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=88.0 bcn=0 [on:0 tx:0 rx:0 period:2388] from screen [on:0 period:-684955547] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 18:40:26.981  1033  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=88.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-684955547] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 18:40:26.981  1033  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-29 18:40:26.984  1033  1772 W libprocessgroup: failed to open /acct/uid_10044/pid_7842/cgroup.procs: No such file or directory
08-29 18:40:26.984  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 18:40:26.984  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-29 18:40:26.986  1995  1995 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-29 18:40:26.991  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 18:40:26.999  8147  8147 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 18:40:27.001  8147  8147 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-29 18:40:27.005  7523  7523 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-29 18:40:27.007  6895  6895 D PackageIntentReceiver: Not supported Hotkey customization function 
08-29 18:40:27.012  6895  6895 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-29 18:40:27.012  6895  6895 D HideNavigationAppsReceiver: replacing : false
08-29 18:40:27.014  6895  6895 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
,08-29 18:40:27.016  6895  6895 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-29 18:40:27.016  6895  6895 D ButtonCombinationReceiver: replacing : false
08-29 18:40:27.032  1033  1391 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-29 18:40:27.045  1033  2764 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8337 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 18:40:27.054  1033  1409 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:27.056  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:27.056  1033  1095 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:27.058  5809  5809 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-29 18:40:27.063  2485  2546 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml.bak

```
