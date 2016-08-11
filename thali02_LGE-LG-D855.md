#### Test 797510156960f45_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-11 07:24:27.220  6575  6575 D DocsApplication: Installing DEX configuration.
08-11 07:24:27.236  6575  6575 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-11 07:24:27.238  6575  6575 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{20f622e9 com.google.android.apps.docs}
08-11 07:24:27.253  6575  6575 D TAG     : onCreate()
08-11 07:24:27.268  6575  6575 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-11 07:24:28.096  1803  5218 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-11 07:24:28.150  1803  5218 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-11 07:24:28.180  1803  5218 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-11 07:24:28.341  6575  6575 D LgDataFeature: LgDataFeature() Constructor: none
08-11 07:24:28.342  6575  6575 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 07:24:28.421  6598  6598 D AndroidRuntime: 
08-11 07:24:28.421  6598  6598 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 07:24:28.424  6598  6598 D AndroidRuntime: CheckJNI is OFF
--------- beginning of system
08-11 07:24:28.562  1043  2000 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6621 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-11 07:24:28.563  1043  2000 I ActivityManager: Killing 6202:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-11 07:24:28.603  6598  6598 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 07:24:28.634  1043  1946 W libprocessgroup: failed to open /acct/uid_10097/pid_6202/cgroup.procs: No such file or directory
08-11 07:24:28.636  1043  1964 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 07:24:28.645  6575  6575 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-11 07:24:28.662  1927  1944 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 07:24:28.668  1043  1964 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 07:24:28.671  1043  1964 D ActivityManager: setTaskToReturnTo : TaskRecord{29c9bc77 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 07:24:28.671  1043  1964 D ActivityManager: setTaskToReturnTo : TaskRecord{29c9bc77 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 07:24:28.672  1043  1964 D WindowStateEx: AppWindowTokenEx init.. 
08-11 07:24:28.673   342   366 E GBMv2   : DFP En is all cleared set to be enabled
08-11 07:24:28.679  6621  6621 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-11 07:24:28.714  1043  1964 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6646 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 07:24:28.715  6598  6598 D AndroidRuntime: Shutting down VM
08-11 07:24:28.718  6621  6621 I LockScreenSettings: New app installed broadcast received ..
08-11 07:24:28.726  6621  6621 I LockScreenSettings: Number of installed packages  1
08-11 07:24:28.751  1043  1059 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6663 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-11 07:24:28.766   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 266us total 12.963ms
08-11 07:24:28.780   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 12.568ms
08-11 07:24:28.781  1927  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 07:24:28.781  1927  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{152037b5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 07:24:28.785  1927  4424 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 07:24:28.785  1927  4424 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1aaf0e4a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 07:24:28.792   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 231us total 11.547ms
08-11 07:24:28.820  6663  6663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 07:24:28.839  6646  6646 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 07:24:28.904  6646  6646 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-11 07:24:28.911  6646  6646 I LibraryLoader: Loading: webviewchromium
08-11 07:24:28.913  6646  6646 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9234-9236)
08-11 07:24:28.913  6646  6646 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 07:24:28.923  6646  6646 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a0402b}
08-11 07:24:28.923  6646  6646 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 07:24:28.924  6646  6646 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 07:24:28.931  6646  6646 I BrowserStartupController: Initializing chromium process, renderers=0
08-11 07:24:28.932  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 07:24:28.940  6646  6646 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-11 07:24:28.941  6646  6646 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
,08-11 07:24:28.941  6646  6646 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
08-11 07:24:28.947   320  1367 V AudioPolicyService: registerClient() client 0xb0410700, uid 10118
08-11 07:24:28.951  1043  1118 D BluetoothManagerService: Message: 20
08-11 07:24:28.951  1043  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a7dd49:true
08-11 07:24:28.955  6646  6646 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 07:24:28.955  6646  6646 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 07:24:28.955  6646  6646 I Adreno-EGL: Build Date: 12/12/14 금
08-11 07:24:28.955  6646  6646 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 07:24:28.955  6646  6646 I Adreno-EGL: Remote Branch: 
08-11 07:24:28.955  6646  6646 I Adreno-EGL: Local Patches: 
08-11 07:24:28.955  6646  6646 I Adreno-EGL: Reconstruct Branch: 
,08-11 07:24:29.020  6646  6700 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-11 07:24:29.022  6646  6646 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 07:24:29.034  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 07:24:29.037  6646  6646 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 07:24:29.039  6646  6646 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 07:24:29.041  6646  6646 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 07:24:29.041  6646  6646 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 07:24:29.052  6646  6646 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 07:24:29.061  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 07:24:29.061  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 07:24:29.092  6646  6719 D OpenGLRenderer: Render dirty regions requested: true
08-11 07:24:29.092  6646  6719 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 07:24:29.100  6646  6719 D OpenGLRenderer: Enabling debug mode 0
,08-11 07:24:29.107  6646  6646 D Atlas   : Validating map...
08-11 07:24:29.109  1043  1879 V SIM_STK : Menu title from STK is T-Mobile
08-11 07:24:29.111  1043  2020 D SplitWindow: check instance of lgWin Window{2564f7f1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 07:24:29.150  1043  1928 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6728 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 07:24:29.165  6646  6716 D LgDataFeature: LgDataFeature() Constructor: none
08-11 07:24:29.165  6646  6716 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 07:24:29.201  6728  6728 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-11 07:24:29.202  6728  6728 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-11 07:24:29.204  5640  5640 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-11 07:24:29.215  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-11 07:24:29.241  1043  2020 I ActivityManager: Killing 6022:com.google.android.talk/u0a72 (adj 15): empty #17
,08-11 07:24:29.246  1043  1855 I art     : Explicit concurrent mark sweep GC freed 16236(836KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.452ms total 116.502ms
08-11 07:24:29.298  1043  1945 W libprocessgroup: failed to open /acct/uid_10072/pid_6022/cgroup.procs: No such file or directory
,08-11 07:24:29.373  1043  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +593ms (total +699ms)
,08-11 07:24:29.374  6646  6646 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1699a0f6 time:109697
08-11 07:24:29.374  1043  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d5bb0e4 u0 com.test.thalitest/.MainActivity t6} time:109698
08-11 07:24:29.502  6646  6646 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 07:24:29.502  6646  6646 I chromium: 
,08-11 07:24:29.573  6646  6646 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 07:24:29.764  6646  6758 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,08-11 07:24:29.785  6646  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 07:24:29.785  6646  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 07:24:29.785  6646  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 07:24:29.785  6646  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 07:24:29.785  6646  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 07:24:29.786  6646  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44b3da added. We now have 1 listener(s)
08-11 07:24:29.799  1043  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 07:24:29.804  6646  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 07:24:29.808  6646  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 07:24:29.811  6646  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 07:24:29.812  6646  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 07:24:29.828  6646  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@191d6901 added. We now have 1 listener(s)
,08-11 07:24:29.829  6646  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 07:24:29.833  1043  1529 D WifiService: New client listening to asynchronous messages
08-11 07:24:29.838  6646  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 07:24:29.838  6646  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 07:24:29.839  6646  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 07:24:29.839  6646  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 07:24:29.839  6646  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 07:24:29.843  6646  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:24:29.844  1043  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 07:24:29.845  6646  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-11 07:24:29.857  6646  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:24:29.857  6646  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 07:24:29.858  6646  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 07:24:29.858  6646  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 07:24:29.861  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 07:24:29.863  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 07:24:29.864  6646  6758 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 07:24:29.903  6646  6716 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 07:24:29.903  6646  6716 I chromium: 
,08-11 07:24:29.981  6646  6646 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 07:24:30.484   342   368 E GBMv2   : DFP En is all cleared set to be enabled
08-11 07:24:30.484   342   368 E GBMv2   : Set value is all cleared set the max
08-11 07:24:30.484   342   368 I GBMv2   : DFP Enabled. Ignore VFP set
,08-11 07:24:31.056  6646  6761 W jxcore-log: Initializing JXcore engine
,08-11 07:24:31.056  6646  6761 W jxcore-log: JXcore engine is ready
,08-11 07:24:31.092  6761  6761 W Thread-787: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8507]" dev="sockfs" ino=8507 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 07:24:31.092  6761  6761 W Thread-787: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-11 07:24:31.092  6761  6761 W Thread-787: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10469]" dev="sockfs" ino=10469 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 07:24:31.092  6761  6761 W Thread-787: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-11 07:24:31.092  6761  6761 W Thread-787: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30260]" dev="sockfs" ino=30260 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-11 07:24:31.111  6646  6761 W jxcore-log: Starting JXcore engine
,08-11 07:24:31.187  6646  6761 W jxcore-log: Platform android
08-11 07:24:31.187  6646  6761 W jxcore-log: 
08-11 07:24:31.187  6646  6761 W jxcore-log: Process ARCH arm
08-11 07:24:31.187  6646  6761 W jxcore-log: 
,08-11 07:24:31.308  2782  2782 I MusicWidget: mDelayedStopHandler : unbind
,08-11 07:24:31.316  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-11 07:24:31.316  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-11 07:24:31.316  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-11 07:24:31.333  2165  2165 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-11 07:24:31.333  2165  2165 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-11 07:24:31.334  2165  2165 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-11 07:24:31.343  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-11 07:24:31.344  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-11 07:24:31.346  1043  1059 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@339bf991com.lge.music.MediaPlaybackService$5@1699a0f6
08-11 07:24:31.349  2165  2165 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-11 07:24:31.349  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-11 07:24:31.350  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.351  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.356  2165  2165 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3de0b407
08-11 07:24:31.357  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.357  2165  2165 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-11 07:24:31.357  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.366  2165  2165 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-11 07:24:31.366  2165  2165 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-11 07:24:31.367  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-11 07:24:31.371  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.371  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.372  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.372  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 07:24:31.374  2165  2165 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-11 07:24:31.375  2165  2165 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-11 07:24:31.375  2165  2165 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-11 07:24:31.375  2165  2165 V MediaPlayer[Native]: reset
08-11 07:24:31.388  2165  2165 V MediaPlayer[Native]: setListener
08-11 07:24:31.388  2165  2165 V MediaPlayer[Native]: disconnect
08-11 07:24:31.388  2165  2165 V MediaPlayer[Native]: destructor
08-11 07:24:31.388   320  1367 V AudioFlinger: releasing 18 from 2165 for -1
08-11 07:24:31.388   320  1367 V AudioFlinger:  decremented refcount to 0
08-11 07:24:31.388   320  1367 V AudioFlinger: purging stale effects
,08-11 07:24:31.390  2165  2165 V MediaPlayer[Native]: disconnect
08-11 07:24:31.394  2165  2165 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-11 07:24:31.401  2165  2165 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
,08-11 07:24:31.403  2165  2165 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-11 07:24:31.404  2165  2165 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-11 07:24:31.404  2165  2165 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-11 07:24:31.404  2165  2165 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-11 07:24:31.404  2165  2165 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 582528247
08-11 07:24:31.405  2165  2165 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 582528247
08-11 07:24:31.409  2165  2165 I SmartShareClient: [SmartShareManagerClient] terminate service: 2165/MediaPlaybackService/293930149
08-11 07:24:31.415  2165  2165 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-11 07:24:31.415  2165  2165 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@b5f1764
,08-11 07:24:31.418  6646  6761 I jxcore-log: JXcore Cordova bridge is ready!
08-11 07:24:31.418  6646  6761 I jxcore-log: 
08-11 07:24:31.418  6646  6761 W jxcore-log: JXcore engine is started
08-11 07:24:31.423  6646  6758 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 07:24:31.423  2165  2165 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-11 07:24:31.423  2165  2165 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-11 07:24:31.424  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-11 07:24:31.424  2165  2165 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-11 07:24:31.425  1043  1058 I ActivityManager: Killing 5771:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-11 07:24:31.427  6646  6646 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 07:24:31.431  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
08-11 07:24:31.438  5750  5750 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-11 07:24:31.438  5750  5750 W System.err: android.os.DeadObjectException
08-11 07:24:31.438  5750  5750 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 07:24:31.438  5750  5750 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 07:24:31.438  5750  5750 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-11 07:24:31.438  5750  5750 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-11 07:24:31.438  5750  5750 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 07:24:31.438  5750  5750 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 07:24:31.438  5750  5750 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 07:24:31.438  5750  5750 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 07:24:31.438  5750  5750 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:24:31.438  5750  5750 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 07:24:31.438  5750  5750 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:24:31.439  5750  5750 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 07:24:31.439  5750  5750 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 07:24:31.439  5750  5750 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 07:24:31.439  5750  5750 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-11 07:24:31.439  5750  5750 W System.err: android.os.DeadObjectException
08-11 07:24:31.439  5750  5750 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 07:24:31.439  5750  5750 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 07:24:31.439  5750  5750 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-11 07:24:31.439  5750  5750 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-11 07:24:31.439  5750  5750 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 07:24:31.439  5750  5750 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 07:24:31.439  5750  5750 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 07:24:31.439  5750  5750 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 07:24:31.439  5750  5750 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:24:31.439  5750  5750 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 07:24:31.439  5750  5750 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:24:31.439  5750  5750 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 07:24:31.439  5750  5750 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 07:24:31.439  5750  5750 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 07:24:31.439  5750  5750 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-11 07:24:31.439  5750  5750 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-11 07:24:31.676  1043  1919 W libprocessgroup: failed to open /acct/uid_1000/pid_5771/cgroup.procs: No such file or directory
,08-11 07:24:31.677  1043  1919 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-11 07:24:31.686  5750  5750 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-11 07:24:31.687  5750  5750 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-11 07:24:31.737  1043  1879 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6771 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 07:24:31.742  5750  5750 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-11 07:24:31.834  6771  6771 D UEI.SmartControl: Quickset Services start...
08-11 07:24:31.836  6771  6771 I UEI.SmartControl: Manufacture = LGE
,08-11 07:24:31.836  6771  6771 D UEI.SmartControl: Id = LGNevo
08-11 07:24:31.837  6771  6771 D UEI.SmartControl: File observer start...
08-11 07:24:31.839  6771  6771 E UEI.SmartControl: IR Port is disabled: false
08-11 07:24:31.839  6771  6771 D UEI.SmartControl: Starting file observer...
08-11 07:24:31.839  6771  6771 D UEI.SmartControl: Extracting JNI libs...
08-11 07:24:31.839  6771  6771 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-11 07:24:31.918  6771  6771 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-11 07:24:31.918  6771  6771 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-11 07:24:31.918  6771  6771 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-11 07:24:31.967  6771  6771 I UEI.SmartControl: --- Selecting new region: 6
08-11 07:24:31.970  6771  6771 I UEI.SmartControl: Model = LG-D855
08-11 07:24:31.971  6771  6771 D UEI.SmartControl: QS Service created
,08-11 07:24:31.990  6771  6771 I UEI.SmartControl: Service initServices...
,08-11 07:24:31.996  6771  6771 D UEI.SmartControl: QS start get config
08-11 07:24:32.045  6771  6771 D UEI.SmartControl: Loading JNI Libs...
,08-11 07:24:32.275  6771  6771 I UEI.SmartControl: Supports setup maps: true
,08-11 07:24:32.278  6771  6771 D UEI.SmartControl: QS start statue = true Error code = 0
08-11 07:24:32.278  6771  6771 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-11 07:24:32.278  6771  6771 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 07:24:32.279  6771  6771 I UEI.SmartControl: ### init IR Blaster...
08-11 07:24:32.284  6771  6771 D serial_port: Configuring serial port
08-11 07:24:32.288  6771  6771 E UEI.SmartControl: UEIBLaster setting for 616
,08-11 07:24:32.288  6771  6771 I UEI.SmartControl: Setting serial record hearder size = 2
,08-11 07:24:32.289  6771  6771 I UEI.SmartControl: configuring settings for MAXQ616
08-11 07:24:32.290  6771  6771 I UEI.SmartControl: Get version...
08-11 07:24:32.308  6771  6800 D UEI.SmartControl: serial port data available: 21
,08-11 07:24:32.337  6771  6771 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-11 07:24:32.337  6771  6771 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-11 07:24:32.338  6771  6771 I UEI.SmartControl: QS saving settings...
,08-11 07:24:32.342  6771  6771 D UEI.SmartControl: IR Blaster version: 25672567
08-11 07:24:32.360  6771  6800 D UEI.SmartControl: serial port data available: 4
,08-11 07:24:32.399  6771  6806 I UEI.SmartControl: Device manager: loading config....
,08-11 07:24:32.403  6771  6771 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-11 07:24:32.405  6771  6806 D UEI.SmartControl: ----------- loading internal config...
08-11 07:24:32.409  6771  6771 E UEI.SmartControl: Services init done
08-11 07:24:32.409  6771  6771 D UEI.SmartControl: QS Service init finished
08-11 07:24:32.411  6771  6771 D UEI.SmartControl: QS Service version name: 2.1.91
08-11 07:24:32.411  6771  6771 D UEI.SmartControl: QS Service version code: 201091
08-11 07:24:32.413  6771  6771 D UEI.SmartControl: Service requested: Control
,08-11 07:24:32.419  6771  6806 E UEI.SmartControl: Loading SETTINGS...
08-11 07:24:32.424  6771  6771 D UEI.SmartControl: Request IControl service: devices are loaded...
08-11 07:24:32.425  6771  6806 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 07:24:32.427  5750  5750 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-11 07:24:32.429  1043  1058 I ActivityManager: Killing 5750:com.lge.qremote/u0a112 (adj 15): empty #17
,08-11 07:24:32.433  6771  6786 I UEI.SmartControl: ------ IControl API: 11
,08-11 07:24:32.435  6771  6786 I UEI.SmartControl: Registering callback...
08-11 07:24:32.435  6771  6805 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 07:24:32.435  6771  6805 D UEI.SmartControl: -----service ready thread exits
08-11 07:24:32.598  1043  1964 W libprocessgroup: failed to open /acct/uid_10112/pid_5750/cgroup.procs: No such file or directory
08-11 07:24:32.599  6771  6771 D UEI.SmartControl: Internal service binding...
,08-11 07:24:32.615  6575  6575 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-11 07:24:32.618  1043  1561 I ActivityManager: Killing 6235:com.google.android.gm/u0a64 (adj 15): empty #17
08-11 07:24:32.748  1043  1919 W libprocessgroup: failed to open /acct/uid_10064/pid_6235/cgroup.procs: No such file or directory
,08-11 07:24:33.452  6575  6600 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-11 07:24:34.120  1043  1058 I ActivityManager: Killing 5681:com.android.calendar/u0a13 (adj 15): empty #17
,08-11 07:24:34.188  1043  1855 W libprocessgroup: failed to open /acct/uid_10013/pid_5681/cgroup.procs: No such file or directory
,08-11 07:24:36.266  1803  6481 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-11 07:24:36.269   315  6830 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 07:24:36.269   315  6830 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-11 07:24:36.269   315  6830 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-11 07:24:36.469  1803  1803 I ConfigFetchService: fetch service done; releasing wakelock
,08-11 07:24:36.475  1803  1803 I ConfigFetchService: stopping self
,08-11 07:24:36.481  2125  2125 I ConfigService: onDestroy
,08-11 07:24:37.398  6771  6807 D UEI.SmartControl: Internal timer expired: 1
,08-11 07:24:37.408  6771  6807 D UEI.SmartControl: unbind internal service
,08-11 07:24:37.419  6771  6771 D UEI.SmartControl: Service.onUnbind: IControl
08-11 07:24:37.420  6771  6771 D UEI.SmartControl: Service.onDestroy
08-11 07:24:37.420  6771  6771 D UEI.SmartControl: Lock is in USE false
08-11 07:24:37.420  6771  6771 D UEI.SmartControl: unbind internal service
08-11 07:24:37.420  6771  6771 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3de0b407
08-11 07:24:37.420  6771  6771 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-11 07:24:37.421  6771  6771 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-11 07:24:37.421  6771  6771 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:24:37.421  6771  6771 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 07:24:37.421  6771  6771 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:24:37.421  6771  6771 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 07:24:37.421  6771  6771 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 07:24:37.421  6771  6771 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 07:24:37.422  6771  6771 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3de0b407
08-11 07:24:37.422  6771  6771 D serial_port: close(fd = 25)
08-11 07:24:37.426  6771  6771 I UEI.SmartControl: Serial port is closed.
08-11 07:24:37.426  6771  6771 I UEI.SmartControl: Serial port is closed.
08-11 07:24:37.426  6771  6771 D UEI.SmartControl: Blaster closed
08-11 07:24:37.426  6771  6771 D UEI.SmartControl: Shut down QS...
08-11 07:24:37.426  6771  6771 D UEI.SmartControl: Stopping QS lib
08-11 07:24:37.427  6771  6771 D UEI.SmartControl: QS lib stop result = true
08-11 07:24:37.427  6771  6771 D UEI.SmartControl: Stopped QS lib
08-11 07:24:37.428  6771  6771 D UEI.SmartControl: Stopped file observer...
08-11 07:24:37.428  6771  6771 D UEI.SmartControl: QS shutdown complete
,08-11 07:24:41.393  1043  1110 I ActivityManager: Waited long enough for: ServiceRecord{1c4ddcf9 u0 com.google.android.gms/.wearable.service.WearableService}
,08-11 07:24:41.442  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19982
,08-11 07:24:42.182  1043  1370 V AlarmManager: RTC_WAKEUP set : Alarm{2a84803f type 0 when 1470893081868 com.android.vending} when 1470893081868
,08-11 07:24:42.260  1043  1919 V SIM_STK : Menu title from STK is T-Mobile
,08-11 07:24:42.297  4936  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-11 07:24:42.418  6134  6134 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-11 07:24:48.061  6646  6761 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 07:24:48.061  6646  6761 I jxcore-log: 
,08-11 07:24:48.065  6646  6761 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 07:24:48.065  6646  6761 I jxcore-log: 
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:24:48.071  6646  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 07:24:48.075  6646  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 07:24:48.083  6646  6761 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 07:24:48.083  6646  6761 I jxcore-log: 
08-11 07:24:48.089  6646  6761 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 07:24:48.089  6646  6761 I jxcore-log: 
,08-11 07:24:48.562  6646  6761 I jxcore-log: Unit Test app is loaded
08-11 07:24:48.562  6646  6761 I jxcore-log: 
,08-11 07:24:48.573  6646  6761 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 07:24:48.573  6646  6761 I jxcore-log: 
08-11 07:24:48.575  6646  6646 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-11 07:24:48.583  6646  6761 I jxcore-log: My device name is: LGE-LG-D855
08-11 07:24:48.583  6646  6761 I jxcore-log: 
,08-11 07:24:48.593  6646  6761 I jxcore-log: WARN testUtils: myNameCallback not set!
08-11 07:24:48.593  6646  6761 I jxcore-log: 
,08-11 07:24:50.996  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-11 07:24:50.996  6646  6761 I jxcore-log: 
,08-11 07:24:51.641  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-11 07:24:51.641  6646  6761 I jxcore-log: 
,08-11 07:24:51.666  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-11 07:24:51.666  6646  6761 I jxcore-log: 
,08-11 07:24:53.019  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-11 07:24:53.019  6646  6761 I jxcore-log: 
,08-11 07:24:53.251  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-11 07:24:53.251  6646  6761 I jxcore-log: 
,08-11 07:24:53.259  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-11 07:24:53.259  6646  6761 I jxcore-log: 
08-11 07:24:53.264  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-11 07:24:53.264  6646  6761 I jxcore-log: 
,08-11 07:24:53.282  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-11 07:24:53.282  6646  6761 I jxcore-log: 
,08-11 07:24:53.287  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-11 07:24:53.287  6646  6761 I jxcore-log: 
,08-11 07:24:53.798  1043  1370 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2937fd0c type 2 when 134106 com.google.android.gms} when 134106
,08-11 07:24:53.825  2125  2125 I ConfigService: onCreate
,08-11 07:24:53.827  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 07:24:53.827  1803  1803 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-11 07:24:53.837  1803  6857 I ConfigFetchService: running network task: configservice_periodic
08-11 07:24:53.839  1803  6857 I ConfigFetchService: launchTask
08-11 07:24:53.839  2125  2125 I ConfigService: onBind returning update interface
08-11 07:24:53.840  1803  1803 I ConfigFetchService: service connected
08-11 07:24:53.840  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 07:24:53.840  2125  2125 I ConfigService: onBind returning config service
08-11 07:24:53.841  1803  1803 I ConfigClient: service connected
,08-11 07:24:53.944  1043  2020 V SIM_STK : Menu title from STK is T-Mobile
,08-11 07:24:53.952  1803  2336 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-11 07:24:53.954   315  6862 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 07:24:53.954   315  6862 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-11 07:24:53.954   315  6862 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-11 07:24:53.990  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-11 07:24:53.990  6646  6761 I jxcore-log: 
,08-11 07:24:54.003  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-11 07:24:54.003  6646  6761 I jxcore-log: 
,08-11 07:24:54.014  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-11 07:24:54.014  6646  6761 I jxcore-log: 
08-11 07:24:54.021  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-11 07:24:54.021  6646  6761 I jxcore-log: 
,08-11 07:24:54.070  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-11 07:24:54.070  6646  6761 I jxcore-log: 
,08-11 07:24:54.124  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-11 07:24:54.124  6646  6761 I jxcore-log: 
,08-11 07:24:54.132  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-11 07:24:54.132  6646  6761 I jxcore-log: 
08-11 07:24:54.146  1803  2336 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-11 07:24:54.149  1803  1803 I ConfigFetchService: fetch service done; releasing wakelock
08-11 07:24:54.151  1803  1803 I ConfigFetchService: stopping self
08-11 07:24:54.176  2125  2125 I ConfigService: onDestroy
,08-11 07:24:54.407  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-11 07:24:54.407  6646  6761 I jxcore-log: 
,08-11 07:24:54.479  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-11 07:24:54.479  6646  6761 I jxcore-log: 
,08-11 07:24:54.489  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-11 07:24:54.489  6646  6761 I jxcore-log: 
08-11 07:24:54.501  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-11 07:24:54.501  6646  6761 I jxcore-log: 
,08-11 07:24:54.538  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-11 07:24:54.538  6646  6761 I jxcore-log: 
,08-11 07:24:54.668  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-11 07:24:54.668  6646  6761 I jxcore-log: 
,08-11 07:24:54.685  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-11 07:24:54.685  6646  6761 I jxcore-log: 
,08-11 07:24:54.719  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-11 07:24:54.719  6646  6761 I jxcore-log: 
,08-11 07:24:54.734  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-11 07:24:54.734  6646  6761 I jxcore-log: 
,08-11 07:24:54.756  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-11 07:24:54.756  6646  6761 I jxcore-log: 
,08-11 07:24:54.794  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-11 07:24:54.794  6646  6761 I jxcore-log: 
,08-11 07:24:54.800  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-11 07:24:54.800  6646  6761 I jxcore-log: 
08-11 07:24:55.006  6646  6761 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-11 07:24:55.006  6646  6761 I jxcore-log: 
,08-11 07:24:55.014  6646  6761 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-11 07:24:55.015  6646  6761 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-11 07:24:55.015  6646  6761 I jxcore-log: 
08-11 07:25:00.043  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 07:25:00.044  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 07:25:00.044  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-11 07:25:00.044  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:25:00.058  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,08-11 07:25:00.059  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:25:00.061  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:25:00.063  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 07:25:01.427  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-11 07:25:01.437  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-11 07:25:54.160  1043  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1070653095, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1043
,08-11 07:25:54.184  1043  1370 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3763f72f type 2 when 194466 com.google.android.gms} when 194466
,08-11 07:25:54.225  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 07:25:54.282  1803  1803 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-11 07:25:54.288  1043  1043 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1070653095 [*alarm*], flags=0x0
08-11 07:25:54.289  2125  2125 I ConfigService: onCreate
08-11 07:25:54.290  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 07:25:54.295  1803  6880 I ConfigFetchService: running network task: configservice_periodic
,08-11 07:25:54.298  1803  6880 I ConfigFetchService: launchTask
08-11 07:25:54.304  2125  2125 I ConfigService: onBind returning update interface
08-11 07:25:54.305  1803  1803 I ConfigFetchService: service connected
08-11 07:25:54.305  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 07:25:54.305  2125  2125 I ConfigService: onBind returning config service
,08-11 07:25:54.309  1803  1803 I ConfigClient: service connected
08-11 07:25:54.411  1043  1891 V SIM_STK : Menu title from STK is T-Mobile
,08-11 07:25:54.422  1803  2356 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-11 07:25:54.425   315  6898 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 07:25:54.426   315  6898 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-11 07:25:54.426   315  6898 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-11 07:25:54.604  1803  2356 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-11 07:25:54.607  1803  1803 I ConfigFetchService: fetch service done; releasing wakelock
08-11 07:25:54.610  1803  1803 I ConfigFetchService: stopping self
08-11 07:25:54.673  2125  2125 I ConfigService: onDestroy
,08-11 07:26:00.053  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-11 07:26:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-11 07:26:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-11 07:26:00.054  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:26:00.067  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 07:26:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:26:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:26:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 07:26:48.199  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 07:26:48.200  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-11 07:26:48.216  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:26:48.217  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 07:26:48.220  1043  1529 D WifiController: battery changed pluggedType: 2
08-11 07:26:48.221  4304  4443 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 07:26:48.223  1927  2064 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 07:26:48.223  1927  2064 D LEDHandler: Battery Level Remaining: 100%
08-11 07:26:48.224  1927  2064 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
08-11 07:26:48.225  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
08-11 07:26:48.225  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:26:48.227  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:26:48.231  5640  5640 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 07:26:48.934  1043  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1070653095, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1043
,08-11 07:26:48.943  1043  1370 V AlarmManager: ELAPSED_WAKEUP set : Alarm{283019be type 2 when 228398 android} when 228398
08-11 07:26:48.985  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 07:26:49.017  1043  1043 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1070653095 [*alarm*], flags=0x0
,08-11 07:27:00.052  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-11 07:27:00.052  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 07:27:00.052  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-11 07:27:00.053  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:27:00.064  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,08-11 07:27:00.065  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:27:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:27:00.069  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 07:27:54.628  1043  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1070653095, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1043
,08-11 07:27:54.650  1043  1370 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2b470a1f type 2 when 314934 com.google.android.gms} when 314934
,08-11 07:27:54.693  1803  1803 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-11 07:27:54.709  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 07:27:54.722  2125  2125 I ConfigService: onCreate
,08-11 07:27:54.724  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 07:27:54.726  1803  6918 I ConfigFetchService: running network task: configservice_periodic
08-11 07:27:54.736  2125  2125 I ConfigService: onBind returning update interface
,08-11 07:27:54.740  1803  6918 I ConfigFetchService: launchTask
08-11 07:27:54.743  1803  1803 I ConfigFetchService: service connected
08-11 07:27:54.743  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 07:27:54.743  2125  2125 I ConfigService: onBind returning config service
08-11 07:27:54.744  1803  1803 I ConfigClient: service connected
08-11 07:27:54.756  1043  1043 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1070653095 [*alarm*], flags=0x0
,08-11 07:27:54.827  1043  1990 V SIM_STK : Menu title from STK is T-Mobile
,08-11 07:27:54.840  1803  4524 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-11 07:27:54.844   315  6936 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-11 07:27:54.844   315  6936 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-11 07:27:54.844   315  6936 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-11 07:27:55.014  1803  4524 W ConfigFetchTask: bad response from server: 401 Unauthorized
08-11 07:27:55.017  1803  1803 I ConfigFetchService: fetch service done; releasing wakelock
,08-11 07:27:55.020  1803  1803 I ConfigFetchService: stopping self
08-11 07:27:55.066  2125  2125 I ConfigService: onDestroy
,08-11 07:28:00.051  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-11 07:28:00.051  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 07:28:00.051  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-11 07:28:00.052  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:28:00.064  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 07:28:00.064  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:28:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:28:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 07:28:13.894  1043  3438 I LocationManagerService: remove 3d31e0d2
,08-11 07:28:13.901  1043  3438 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-11 07:28:13.901  1043  3438 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 07:28:13.903  1043  3438 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-11 07:28:13.905  1043  3438 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-11 07:28:13.908  1043  3438 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-11 07:28:31.937  1043  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1070653095, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1043
,08-11 07:28:31.990  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 07:28:32.020  1043  1043 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1070653095 [*alarm*], flags=0x0
,08-11 07:28:35.383  6646  6761 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-11 07:28:35.383  6646  6761 I jxcore-log: 
,08-11 07:28:35.744  6953  6953 D AndroidRuntime: 
08-11 07:28:35.744  6953  6953 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 07:28:35.749  6953  6953 D AndroidRuntime: CheckJNI is OFF
,08-11 07:28:35.920  6953  6953 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 07:28:35.940  1043  1110 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-11 07:28:35.941  1043  1110 I ActivityManager: Killing 6646:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-11 07:28:35.989  1043  2000 I WindowState: WIN DEATH: Window{2564f7f1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 07:28:35.992  1043  1529 D WifiService: Client connection lost with reason: 4
08-11 07:28:36.001  1043  2000 D InputDispatcher: Window went away: Window{2564f7f1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 07:28:36.166  1043  1110 I ActivityManager:   Force finishing activity ActivityRecord{3d5bb0e4 u0 com.test.thalitest/.MainActivity t6}
,08-11 07:28:36.202   342   366 E GBMv2   : DFP En is all cleared set to be enabled
08-11 07:28:36.206  1043  1891 W ActivityManager: Spurious death for ProcessRecord{32746e6e 6646:com.test.thalitest/u0a118}, curProc for 6646: null
,08-11 07:28:36.218  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-11 07:28:36.218  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a1fd1bb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 07:28:36.219  1043  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-11 07:28:36.219  1927  4424 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-11 07:28:36.219  1927  4424 D SplitWindowPolicy: topRunningActivity=ActivityInfo{331576d8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 07:28:36.224  1043  1124 I ActivityManager:   Force finishing activity ActivityRecord{3d5bb0e4 u0 com.test.thalitest/.MainActivity t6 f}
08-11 07:28:36.224  1043  1124 W ActivityManager: Duplicate finish request for ActivityRecord{3d5bb0e4 u0 com.test.thalitest/.MainActivity t6 f}
,08-11 07:28:36.272  5043  5043 I art     : Explicit concurrent mark sweep GC freed 490(33KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 530us total 34.771ms
,08-11 07:28:36.278  2021  2021 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-11 07:28:36.280  2021  2021 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-11 07:28:36.287  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-11 07:28:36.294  1043  1429 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 07:28:36.299  4304  4304 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-11 07:28:36.299  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-11 07:28:36.318  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 07:28:36.318  3789  3789 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-11 07:28:36.332  1043  1879 V SIM_STK : Menu title from STK is T-Mobile
08-11 07:28:36.343  1043  1108 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-11 07:28:36.358  2479  2589 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 07:28:36.363  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 07:28:36.364  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-11 07:28:36.365  2021  2113 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-11 07:28:36.369  4936  4936 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 07:28:36.369  4936  4936 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 07:28:36.369  4936  4936 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 07:28:36.369  4936  4936 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-11 07:28:36.369  4936  4936 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 07:28:36.369  4936  4936 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 07:28:36.369  4936  4936 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:28:36.369  4936  4936 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 07:28:36.369  4936  4936 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:36.369  4936  4936 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 07:28:36.369  4936  4936 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 07:28:36.370  4936  4936 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 07:28:36.379  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-11 07:28:36.381  1892  1892 D ActionManagerService: notifyUserLog: 1000003
08-11 07:28:36.381  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-11 07:28:36.382  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-11 07:28:36.382  2021  2021 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 07:28:36.382  1588  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 07:28:36.382  1588  1650 D KeyguardModel: createShortcutInfo...
,08-11 07:28:36.383  2021  2021 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-11 07:28:36.384  2021  2021 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-11 07:28:36.389  3789  4928 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-11 07:28:36.394  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-11 07:28:36.394  1892  1892 D ActionManagerService: notifyUserLog: 1000004
,08-11 07:28:36.395  3789  4928 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-11 07:28:36.396  3789  3804 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 07:28:36.401  2125  2125 I ConfigService: onCreate
08-11 07:28:36.408  1588  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 07:28:36.408  1588  1650 D KeyguardModel: createShortcutInfo...
,08-11 07:28:36.409  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 07:28:36.409  2125  2125 I ConfigService: onBind returning update interface
08-11 07:28:36.410  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 07:28:36.410  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262123
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , display: false
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , animation: false }
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262287
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , display: false
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , animation: false }
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , create_time: 1470393743569
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , display: false
08-11 07:28:36.415  2021  2021 I GBoardWebViewUtils: , animation: false }
08-11 07:28:36.418  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-11 07:28:36.419  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 07:28:36.419  2125  2125 I ConfigService: onBind returning config service
,08-11 07:28:36.424  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 07:28:36.424  1588  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 07:28:36.425  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 07:28:36.426  1803  1803 I ConfigFetchService: service connected
08-11 07:28:36.427  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-11 07:28:36.428  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.428  1588  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 07:28:36.434  2021  6987 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-11 07:28:36.440  2125  2125 I ConfigService: onDestroy
08-11 07:28:36.448  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-11 07:28:36.452  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 07:28:36.452  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-11 07:28:36.457  1856  1856 D SplitUIService: removed split : 
08-11 07:28:36.461  1588  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 07:28:36.461  1588  1650 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.468  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 07:28:36.468  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 07:28:36.470  1803  6989 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-11 07:28:36.470  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.470  1588  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 07:28:36.479  1043  1990 V SIM_STK : Menu title from STK is T-Mobile
08-11 07:28:36.479  1043  1990 V SIM_STK : Menu title from STK is T-Mobile
08-11 07:28:36.480  1588  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 07:28:36.480  1588  1650 D KeyguardModel: createShortcutInfo...
,08-11 07:28:36.490  1588  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 07:28:36.490  1588  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 07:28:36.490  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 07:28:36.490  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 07:28:36.494  1043  1043 I art     : Explicit concurrent mark sweep GC freed 25720(1737KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.495ms total 234.792ms
08-11 07:28:36.496  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.496  1588  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 07:28:36.498  1043  1124 I art     : WaitForGcToComplete blocked for 131.020ms for cause Explicit
08-11 07:28:36.506  1588  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 07:28:36.506  1588  1650 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.517  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-11 07:28:36.517  1856  1856 I SplitUIService: split app #11
,08-11 07:28:36.531  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-11 07:28:36.531  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 07:28:36.540  1043  1919 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-11 07:28:36.540  5880  6996 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 07:28:36.541  4304  4304 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 07:28:36.542  2021  2021 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-11 07:28:36.542  2021  2035 I art     : Background sticky concurrent mark sweep GC freed 2961(152KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 11.548ms total 26.990ms
08-11 07:28:36.542  1588  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 07:28:36.542  1588  1650 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.543  1803  6997 I PeopleContactsSync: CP2 sync disabled
08-11 07:28:36.544   331   409 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-11 07:28:36.544  3222  6998 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-11 07:28:36.553  6066  6066 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-11 07:28:36.557  1043  1059 V SIM_STK : Menu title from STK is T-Mobile
,08-11 07:28:36.572  1588  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 07:28:36.572  1588  1650 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.573  1803  6995 W GmsApplication: Using Auth Proxy for data requests.
08-11 07:28:36.573  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.573  1588  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-11 07:28:36.576  1803  5218 I Icing   : doRemovePackageData com.test.thalitest
08-11 07:28:36.577  1588  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 07:28:36.577  1588  1650 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.577  1043  1043 D administrator: Handling package changes for user 0
08-11 07:28:36.579  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.579  1588  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 07:28:36.580  1588  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 07:28:36.580  1588  1650 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.581  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.581  1588  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 07:28:36.584  1588  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 07:28:36.584  1588  1650 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.585  1803  6995 W GmsApplication: Using Auth Proxy for data requests.
08-11 07:28:36.588  2360  7000 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 07:28:36.592  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-11 07:28:36.592  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 07:28:36.609  6537  6537 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 07:28:36.629  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-11 07:28:36.632  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 07:28:36.633  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-11 07:28:36.634  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-11 07:28:36.635  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-11 07:28:36.636  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-11 07:28:36.650  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 07:28:36.650  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-11 07:28:36.651  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-11 07:28:36.653  6438  6438 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 07:28:36.658  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-11 07:28:36.659  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 07:28:36.674  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-11 07:28:36.674  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 07:28:36.674  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 07:28:36.680  1043  1636 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7004 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-11 07:28:36.681  1043  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e00d87 u0 com.lge.launcher2/.Launcher t5} time:357005
08-11 07:28:36.686  2021  2235 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-11 07:28:36.686  2021  2235 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-11 07:28:36.694  2021  2021 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-11 07:28:36.695  2628  2628 D [Concierge]Service: onStartCommand(). Type : 8
08-11 07:28:36.695  2628  2628 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-11 07:28:36.696  2628  2628 D [Concierge]Service: Update widget ID : 11
08-11 07:28:36.699  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 07:28:36.699  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 07:28:36.699  1043  1043 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 07:28:36.700  1043  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-11 07:28:36.701  2021  2021 D [Concierge]WidgetView: change position of spinner
08-11 07:28:36.702  2021  2021 I [Concierge]WidgetView: initWebView(). Time : 1470893316702
08-11 07:28:36.702  2628  2628 D [Concierge]Service: onStartCommand(). Type : 0
,08-11 07:28:36.722  2021  2021 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 405706526
08-11 07:28:36.723  2021  2021 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-11 07:28:36.723  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-11 07:28:36.725  2021  2021 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2609d569
08-11 07:28:36.726  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-11 07:28:36.726  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 07:28:36.727  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 07:28:36.731  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-11 07:28:36.732  2021  2021 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-11 07:28:36.732  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 07:28:36.732  2021  2021 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470892987062, New one : 1470893316702
08-11 07:28:36.732  2021  2021 D [Concierge]WidgetView: Unregister all receivers
08-11 07:28:36.732  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 07:28:36.733  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 07:28:36.734  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-11 07:28:36.736  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-11 07:28:36.737  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-11 07:28:36.738  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-11 07:28:36.739  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-11 07:28:36.743  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 07:28:36.744  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 07:28:36.752  1043  1124 I art     : Explicit concurrent mark sweep GC freed 9805(599KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.595ms total 254.083ms
,08-11 07:28:36.765  7004  7004 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-11 07:28:36.766  7004  7004 W LG Account v2.2: No ProfileInfo entries
08-11 07:28:36.766  7004  7004 I LG Account v2.2: isEnabled: false
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Country: EU
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Operator: OPEN
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Ranking support: false
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Comfort support: false
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Accessory: true
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Health device: true
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Extra Pedometer: false
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Blood glucose device: false
08-11 07:28:36.766  7004  7004 I Feature : [Lifetracker]Device Number: 3
,08-11 07:28:36.767  7004  7004 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-11 07:28:36.795  1043  1919 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7025 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 07:28:36.796  1043  1919 I ActivityManager: Killing 6293:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-11 07:28:36.801  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 07:28:36.810  2021  2021 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-11 07:28:36.810  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-11 07:28:36.827  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 07:28:36.845  2021  2021 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@19b049db time:357169
,08-11 07:28:36.864  6953  6953 D AndroidRuntime: Shutting down VM
,08-11 07:28:36.897  1043  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 07:28:36.901  1043  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 07:28:36.907  1043  1561 W libprocessgroup: failed to open /acct/uid_10014/pid_6293/cgroup.procs: No such file or directory
08-11 07:28:36.911  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 07:28:36.920  7025  7025 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 07:28:36.920  7025  7025 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-11 07:28:36.920  7025  7025 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 07:28:36.920  7025  7025 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-11 07:28:36.921  7025  7025 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 07:28:36.922  7025  7025 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-11 07:28:36.930  2021  2021 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-11 07:28:36.965  2021  2884 I GBoardtInterface: onReloaded()
,08-11 07:28:36.967  2021  2021 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-11 07:28:36.968  3789  3804 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 07:28:36.970  3789  4926 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 07:28:36.974  1892  1892 D ActionManagerService: notifyUserLog: 1000001
08-11 07:28:36.975  3789  4928 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 07:28:36.975  3789  4928 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 07:28:36.978  1892  1892 D ActionManagerService: notifyUserLog: 1000001
,08-11 07:28:36.978  3789  4928 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 07:28:36.979  3789  4928 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 07:28:36.979  3789  4928 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-11 07:28:36.979  3789  4928 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-11 07:28:36.979  3789  3804 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 07:28:36.981  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-11 07:28:36.981  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-11 07:28:36.983  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-11 07:28:36.983  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 07:28:36.984  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-11 07:28:36.984  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 07:28:36.999  7025  7025 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-11 07:28:37.005  7025  7025 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-11 07:28:37.005  7025  7025 D HideNavigationAppsReceiver: replacing : false
08-11 07:28:37.007  7025  7025 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-11 07:28:37.009  7025  7025 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-11 07:28:37.009  7025  7025 D ButtonCombinationReceiver: replacing : false
,08-11 07:28:37.014  1043  2020 I ActivityManager: Killing 6379:com.android.defcontainer/u0a4 (adj 15): empty #17
08-11 07:28:37.061  1043  1945 W libprocessgroup: failed to open /acct/uid_10004/pid_6379/cgroup.procs: No such file or directory
,08-11 07:28:37.065  5043  7042 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-11 07:28:37.085  1043  1891 V SIM_STK : Menu title from STK is T-Mobile
,08-11 07:28:37.093  1043  1561 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7043 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 07:28:37.126  1043  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7060 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-11 07:28:37.169  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-11 07:28:37.170  2125  2125 I art     : Explicit concurrent mark sweep GC freed 7555(406KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 541us total 21.278ms
08-11 07:28:37.173  2125  2317 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-11 07:28:37.174  2125  2317 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.b(SourceFile:56)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.a(SourceFile:48)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at com.google.android.gms.common.internal.be.a(SourceFile:45)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at com.google.android.gms.icing.service.n.b(SourceFile:118)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at com.google.android.gms.common.internal.bd.b(SourceFile:218)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at com.google.android.gms.common.internal.ao.onTransact(SourceFile:460)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at android.os.Binder.execTransact(Binder.java:446)
08-11 07:28:37.174  2125  2317 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 07:28:37.174  2125  2317 W ServiceConnection: 	... 10 more
08-11 07:28:37.184  6621  6621 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-11 07:28:37.184  6621  6621 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-11 07:28:37.184  6621  6621 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-11 07:28:37.184  6621  6621 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-11 07:28:37.184  6621  6621 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-11 07:28:37.184  6621  6621 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-11 07:28:37.186  5043  7042 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 120 ms] updated apps [took 119 ms] 
08-11 07:28:37.193  5640  5640 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:28:37.194  7043  7081 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
08-11 07:28:37.195  7043  7081 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-11 07:28:37.195  7043  7081 E AndroidRuntime: Process: com.android.keychain, PID: 7043
08-11 07:28:37.195  7043  7081 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQ,LiteConnectionPool.java:177)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:28:37.195  7043  7081 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 07:28:37.198  7025  7025 D PackageIntentReceiver: Not supported Hotkey customization function 
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: Can't write: system_app_crash
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 07:28:37.201  1043  7084 E DropBoxManagerService: 	... 5 more
08-11 07:28:37.226  1043  1990 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7085 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a

```
