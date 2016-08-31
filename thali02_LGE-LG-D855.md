#### Test 829140733a8c9ab_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 15:25:06.463  1804  1804 I art     : Explicit concurrent mark sweep GC freed 23396(1507KB) AllocSpace objects, 14(224KB) LOS objects, 51% free, 29MB/61MB, paused 1.518ms total 57.339ms
08-31 15:25:06.479  4621  6618 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 221 ms] updated apps [took 221 ms] 
08-31 15:25:06.567  6628  6628 D DocsApplication: Installing DEX configuration.
08-31 15:25:06.583  6628  6628 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-31 15:25:06.587  6628  6628 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{78bfa98 com.google.android.apps.docs}
08-31 15:25:06.601  6628  6628 D TAG     : onCreate()
08-31 15:25:06.618  6628  6628 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-31 15:25:07.489  1804  4790 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-31 15:25:07.572  1804  4790 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-31 15:25:07.601  1804  4790 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-31 15:25:07.637  6663  6663 D AndroidRuntime: 
08-31 15:25:07.637  6663  6663 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 15:25:07.640  6663  6663 D AndroidRuntime: CheckJNI is OFF
08-31 15:25:07.872  6663  6663 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 15:25:07.879  1044  1963 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 15:25:07.888  1928  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 15:25:07.891  1044  1963 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 15:25:07.892  1044  1963 D ActivityManager: setTaskToReturnTo : TaskRecord{36d3eb01 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 15:25:07.892  1044  1963 D ActivityManager: setTaskToReturnTo : TaskRecord{36d3eb01 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 15:25:07.892  1044  1963 D WindowStateEx: AppWindowTokenEx init.. 
08-31 15:25:07.893   340   346 E GBMv2   : DFP En is all cleared set to be enabled
08-31 15:25:07.922  1044  1963 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6699 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 15:25:07.925  6663  6663 D AndroidRuntime: Shutting down VM
08-31 15:25:07.970  1928  2845 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 15:25:07.971  1928  2845 D SplitWindowPolicy: topRunningActivity=ActivityInfo{21aa9394 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 15:25:07.971  1928  3964 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 15:25:07.972  1928  3964 D SplitWindowPolicy: topRunningActivity=ActivityInfo{7101e3d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 15:25:08.031  6699  6699 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 15:25:08.126  6699  6699 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 15:25:08.135  6699  6699 I LibraryLoader: Loading: webviewchromium
08-31 15:25:08.138  6699  6699 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5298-5301)
08-31 15:25:08.139  6699  6699 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 15:25:08.154  6699  6699 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e0f8262}
,08-31 15:25:08.155  6699  6699 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:25:08.156  6699  6699 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 15:25:08.165  6699  6699 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 15:25:08.167  6699  6699 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 15:25:08.176  6699  6699 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 15:25:08.177  6699  6699 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 15:25:08.177  6699  6699 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-31 15:25:08.182   312  1381 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-31 15:25:08.186  1044  1119 D BluetoothManagerService: Message: 20
08-31 15:25:08.187  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22f80783:true
08-31 15:25:08.203  6699  6699 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:25:08.203  6699  6699 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:25:08.203  6699  6699 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:25:08.203  6699  6699 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:25:08.203  6699  6699 I Adreno-EGL: Remote Branch: 
08-31 15:25:08.203  6699  6699 I Adreno-EGL: Local Patches: 
08-31 15:25:08.203  6699  6699 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:25:08.281  6699  6728 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 15:25:08.290  6699  6699 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 15:25:08.300  6628  6628 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:25:08.300  6628  6628 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:25:08.312  6699  6699 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:25:08.319  6699  6699 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 15:25:08.323  6699  6699 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 15:25:08.326  6699  6699 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 15:25:08.326  6699  6699 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 15:25:08.342  6699  6699 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 15:25:08.357  6699  6699 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 15:25:08.357  6699  6699 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:25:08.406  6699  6742 D OpenGLRenderer: Render dirty regions requested: true
08-31 15:25:08.407  6699  6742 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 15:25:08.414  6699  6742 D OpenGLRenderer: Enabling debug mode 0
08-31 15:25:08.423  6699  6699 D Atlas   : Validating map...
,08-31 15:25:08.427  1044  2018 D SplitWindow: check instance of lgWin Window{206dc065 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 15:25:08.450  6168  6168 I LockScreenSettings: New app installed broadcast received ..
,08-31 15:25:08.455  6168  6168 I LockScreenSettings: Number of installed packages  1
08-31 15:25:08.459  6628  6628 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-31 15:25:08.465  6699  6740 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:25:08.465  6699  6740 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:25:08.529  1044  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:25:08.557  6699  6699 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17c35499 time:105721
,08-31 15:25:08.588  1044  1982 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6764 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 15:25:08.592  1044  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +622ms (total +698ms)
08-31 15:25:08.592  1044  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d9b8da6 u0 com.test.thalitest/.MainActivity t6} time:105756
,08-31 15:25:08.646  6764  6764 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-31 15:25:08.646  6764  6764 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-31 15:25:08.681  6699  6699 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 15:25:08.704  1044  1561 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6785 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 15:25:08.706  1044  1561 I ActivityManager: Killing 5507:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 15:25:08.740  6699  6740 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 15:25:08.740  6699  6740 I chromium: 
,08-31 15:25:08.778  1044  1982 W libprocessgroup: failed to open /acct/uid_10005/pid_5507/cgroup.procs: No such file or directory
,08-31 15:25:08.845  6785  6785 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-31 15:25:08.869  6699  6802 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
08-31 15:25:08.871  6785  6785 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 15:25:08.882  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 15:25:08.882  6699  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 15:25:08.882  6699  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 15:25:08.882  6699  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 15:25:08.882  6699  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 15:25:08.882  6699  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 15:25:08.882  6699  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3867a60d added. We now have 1 listener(s)
08-31 15:25:08.888  1044  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:25:08.891  6699  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 15:25:08.891  6699  6699 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 15:25:08.891  6699  6699 I chromium: 
08-31 15:25:08.893  6699  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-31 15:25:08.897  6699  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:08.898  6699  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 15:25:08.913  6699  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a971b10 added. We now have 1 listener(s)
08-31 15:25:08.913  6699  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:08.916  6487  6487 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 15:25:08.918  1044  1947 I ActivityManager: Killing 5902:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 15:25:08.920  1044  1474 D WifiService: New client listening to asynchronous messages
08-31 15:25:08.929  6699  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:25:08.929  6699  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 15:25:08.934  6699  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 15:25:08.935  6699  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 15:25:08.935  6699  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 15:25:08.959  1044  1764 W libprocessgroup: failed to open /acct/uid_10072/pid_5902/cgroup.procs: No such file or directory
,08-31 15:25:08.963  6699  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:08.964  1044  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:08.967  6699  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 15:25:08.982  6699  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:08.983  6699  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:08.984  6699  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 15:25:08.984  6699  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:08.987  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:08.987  6699  6802 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 15:25:08.988  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:09.044  6699  6699 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 15:25:09.613   340   348 E GBMv2   : DFP En is all cleared set to be enabled
08-31 15:25:09.613   340   348 E GBMv2   : Set value is all cleared set the max
,08-31 15:25:09.613   340   348 I GBMv2   : DFP Enabled. Ignore VFP set
08-31 15:25:09.819  6699  6809 W jxcore-log: Initializing JXcore engine
08-31 15:25:09.819  6699  6809 W jxcore-log: JXcore engine is ready
,08-31 15:25:09.888  6809  6809 W Thread-767: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10241]" dev="sockfs" ino=10241 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-31 15:25:09.888  6809  6809 W Thread-767: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 15:25:09.888  6809  6809 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10423]" dev="sockfs" ino=10423 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 15:25:09.888  6809  6809 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 15:25:09.888  6809  6809 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30177]" dev="sockfs" ino=30177 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 15:25:09.922  6699  6809 W jxcore-log: Starting JXcore engine
,08-31 15:25:09.987   334   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 15:25:09.988  3188  6813 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-31 15:25:10.118  6699  6809 W jxcore-log: Platform android
08-31 15:25:10.118  6699  6809 W jxcore-log: 
,08-31 15:25:10.119  6699  6809 W jxcore-log: Process ARCH arm
08-31 15:25:10.119  6699  6809 W jxcore-log: 
08-31 15:25:10.511  6699  6809 I jxcore-log: JXcore Cordova bridge is ready!
08-31 15:25:10.511  6699  6809 I jxcore-log: 
08-31 15:25:10.512  6699  6809 W jxcore-log: JXcore engine is started
,08-31 15:25:10.518  6699  6802 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 15:25:10.524  6699  6699 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-31 15:25:10.597  2778  2778 I MusicWidget: mDelayedStopHandler : unbind
,08-31 15:25:10.599  2112  2112 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-31 15:25:10.599  2112  2112 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-31 15:25:10.600  2112  2112 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-31 15:25:10.602  2112  2112 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-31 15:25:10.603  2112  2112 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-31 15:25:10.603  2112  2112 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-31 15:25:10.605  2112  2112 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-31 15:25:10.605  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-31 15:25:10.606  1044  1060 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@d8d5be3com.lge.music.MediaPlaybackService$5@bc179e0
08-31 15:25:10.607  2112  2112 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-31 15:25:10.608  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.609  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.610  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.612  2112  2112 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@216762ae
08-31 15:25:10.612  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-31 15:25:10.614  2112  2112 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-31 15:25:10.614  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.618  2112  2112 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-31 15:25:10.619  2112  2112 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-31 15:25:10.619  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-31 15:25:10.621  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.628  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.629  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.630  2112  2112 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 15:25:10.631  2112  2112 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-31 15:25:10.638  2112  2112 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-31 15:25:10.638  2112  2112 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-31 15:25:10.638  2112  2112 V MediaPlayer[Native]: reset
08-31 15:25:10.645  2112  2112 V MediaPlayer[Native]: setListener
08-31 15:25:10.645  2112  2112 V MediaPlayer[Native]: disconnect
08-31 15:25:10.645  2112  2112 V MediaPlayer[Native]: destructor
08-31 15:25:10.646   312  2136 V AudioFlinger: releasing 18 from 2112 for -1
08-31 15:25:10.646   312  2136 V AudioFlinger:  decremented refcount to 0
08-31 15:25:10.646   312  2136 V AudioFlinger: purging stale effects
,08-31 15:25:10.655  2112  2112 V MediaPlayer[Native]: disconnect
08-31 15:25:10.656  2112  2112 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-31 15:25:10.658  2112  2112 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-31 15:25:10.659  2112  2112 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-31 15:25:10.660  2112  2112 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-31 15:25:10.660  2112  2112 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-31 15:25:10.660  2112  2112 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-31 15:25:10.661  2112  2112 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 398677145
08-31 15:25:10.661  2112  2112 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 398677145
08-31 15:25:10.669  2112  2112 I SmartShareClient: [SmartShareManagerClient] terminate service: 2112/MediaPlaybackService/932325444
08-31 15:25:10.673  2112  2112 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-31 15:25:10.673  2112  2112 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@2947d35e
,08-31 15:25:10.677  2112  2112 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-31 15:25:10.678  2112  2112 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-31 15:25:10.679  2112  2112 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-31 15:25:10.679  2112  2112 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-31 15:25:10.681  1044  1713 I ActivityManager: Killing 5709:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 15:25:10.682  2112  2112 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
08-31 15:25:10.698  5678  5678 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 15:25:10.698  5678  5678 W System.err: android.os.DeadObjectException
08-31 15:25:10.698  5678  5678 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 15:25:10.698  5678  5678 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 15:25:10.698  5678  5678 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 15:25:10.698  5678  5678 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 15:25:10.698  5678  5678 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 15:25:10.699  5678  5678 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 15:25:10.699  5678  5678 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:25:10.699  5678  5678 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:25:10.699  5678  5678 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:25:10.699  5678  5678 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 15:25:10.699  5678  5678 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:10.699  5678  5678 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:10.699  5678  5678 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 15:25:10.699  5678  5678 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 15:25:10.699  5678  5678 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 15:25:10.699  5678  5678 W System.err: android.os.DeadObjectException
08-31 15:25:10.700  5678  5678 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 15:25:10.700  5678  5678 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 15:25:10.700  5678  5678 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 15:25:10.700  5678  5678 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 15:25:10.700  5678  5678 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 15:25:10.700  5678  5678 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 15:25:10.700  5678  5678 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:25:10.700  5678  5678 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:25:10.700  5678  5678 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:25:10.700  5678  5678 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 15:25:10.700  5678  5678 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:10.700  5678  5678 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:10.700  5678  5678 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.r,un(ZygoteInit.java:909)
08-31 15:25:10.700  5678  5678 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 15:25:10.700  5678  5678 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 15:25:10.701  5678  5678 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-31 15:25:10.979  1044  1982 W libprocessgroup: failed to open /acct/uid_1000/pid_5709/cgroup.procs: No such file or directory
,08-31 15:25:10.980  1044  1982 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-31 15:25:10.985  1044  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=960494555, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
08-31 15:25:10.985  5678  5678 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 15:25:10.985  5678  5678 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 15:25:11.063  1044  1908 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6832 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 15:25:11.075  5678  5678 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 15:25:11.102  2577  2577 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 15:25:11.128  4507  6842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-31 15:25:11.131  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=960494555 [*alarm*], flags=0x0
,08-31 15:25:11.178  6832  6832 D UEI.SmartControl: Quickset Services start...
08-31 15:25:11.180  6832  6832 I UEI.SmartControl: Manufacture = LGE
08-31 15:25:11.180  6832  6832 D UEI.SmartControl: Id = LGNevo
08-31 15:25:11.181  6832  6832 D UEI.SmartControl: File observer start...
08-31 15:25:11.182  6832  6832 E UEI.SmartControl: IR Port is disabled: false
08-31 15:25:11.182  6832  6832 D UEI.SmartControl: Starting file observer...
08-31 15:25:11.182  6832  6832 D UEI.SmartControl: Extracting JNI libs...
08-31 15:25:11.182  6832  6832 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-31 15:25:11.266  6832  6832 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 15:25:11.266  6832  6832 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-31 15:25:11.266  6832  6832 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 15:25:11.300  6832  6832 I UEI.SmartControl: --- Selecting new region: 6
,08-31 15:25:11.303  6832  6832 I UEI.SmartControl: Model = LG-D855
08-31 15:25:11.304  6832  6832 D UEI.SmartControl: QS Service created
08-31 15:25:11.320  6832  6832 I UEI.SmartControl: Service initServices...
,08-31 15:25:11.325  6832  6832 D UEI.SmartControl: QS start get config
08-31 15:25:11.398  6832  6832 D UEI.SmartControl: Loading JNI Libs...
,08-31 15:25:11.777  6832  6832 I UEI.SmartControl: Supports setup maps: true
08-31 15:25:11.781  6832  6832 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 15:25:11.781  6832  6832 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 15:25:11.782  6832  6832 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 15:25:11.782  6832  6832 I UEI.SmartControl: ### init IR Blaster...
,08-31 15:25:11.788  6832  6832 D serial_port: Configuring serial port
08-31 15:25:11.792  6832  6832 E UEI.SmartControl: UEIBLaster setting for 616
08-31 15:25:11.792  6832  6832 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 15:25:11.792  6832  6832 I UEI.SmartControl: configuring settings for MAXQ616
08-31 15:25:11.792  6832  6832 I UEI.SmartControl: Get version...
08-31 15:25:11.811  6832  6874 D UEI.SmartControl: serial port data available: 21
,08-31 15:25:11.839  6832  6832 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 15:25:11.839  6832  6832 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 15:25:11.840  6832  6832 I UEI.SmartControl: QS saving settings...
08-31 15:25:11.840  6832  6832 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 15:25:11.858  6832  6874 D UEI.SmartControl: serial port data available: 4
,08-31 15:25:11.891  6832  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 15:25:11.894  6832  6832 E UEI.SmartControl: Services init done
08-31 15:25:11.894  6832  6832 D UEI.SmartControl: QS Service init finished
,08-31 15:25:11.898  6832  6832 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 15:25:11.898  6832  6832 D UEI.SmartControl: QS Service version code: 201091
08-31 15:25:11.899  6832  6877 I UEI.SmartControl: Device manager: loading config....
08-31 15:25:11.899  6832  6877 D UEI.SmartControl: ----------- loading internal config...
08-31 15:25:11.903  6832  6832 D UEI.SmartControl: Service requested: Control
,08-31 15:25:11.913  6832  6877 E UEI.SmartControl: Loading SETTINGS...
08-31 15:25:11.914  6832  6832 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 15:25:11.918  1044  1890 I ActivityManager: Killing 5678:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 15:25:11.924  6832  6877 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 15:25:11.943  6832  6876 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 15:25:11.943  6832  6876 D UEI.SmartControl: -----service ready thread exits
,08-31 15:25:12.003  1044  1764 W libprocessgroup: failed to open /acct/uid_10112/pid_5678/cgroup.procs: No such file or directory
08-31 15:25:12.006  6832  6832 D UEI.SmartControl: Internal service binding...
,08-31 15:25:12.392  6628  6628 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-31 15:25:12.398  1044  1909 I ActivityManager: Killing 6357:com.android.calendar/u0a13 (adj 15): empty #17
08-31 15:25:12.533  1044  1561 W libprocessgroup: failed to open /acct/uid_10013/pid_6357/cgroup.procs: No such file or directory
,08-31 15:25:13.371  6628  6736 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 15:25:15.531  1804  6525 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 15:25:15.536   308  6891 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 15:25:15.536   308  6891 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-31 15:25:15.536   308  6891 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-31 15:25:15.788  1804  1804 I ConfigFetchService: fetch service done; releasing wakelock
,08-31 15:25:15.794  1804  1804 I ConfigFetchService: stopping self
08-31 15:25:15.804  2168  2168 I ConfigService: onDestroy
,08-31 15:25:16.897  6832  6878 D UEI.SmartControl: Internal timer expired: 1
08-31 15:25:16.897  6832  6878 D UEI.SmartControl: unbind internal service
,08-31 15:25:16.921  6832  6832 D UEI.SmartControl: Service.onUnbind: IControl
,08-31 15:25:16.937  6832  6832 D UEI.SmartControl: Service.onDestroy
08-31 15:25:16.937  6832  6832 D UEI.SmartControl: Lock is in USE false
08-31 15:25:16.937  6832  6832 D UEI.SmartControl: unbind internal service
08-31 15:25:16.938  6832  6832 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@216762ae
08-31 15:25:16.938  6832  6832 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 15:25:16.938  6832  6832 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 15:25:16.938  6832  6832 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 15:25:16.938  6832  6832 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 15:25:16.938  6832  6832 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 15:25:16.938  6832  6832 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 15:25:16.938  6832  6832 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 15:25:16.938  6832  6832 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 15:25:16.938  6832  6832 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:16.938  6832  6832 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:25:16.939  6832  6832 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 15:25:16.939  6832  6832 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:16.939  6832  6832 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:16.939  6832  6832 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 15:25:16.939  6832  6832 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 15:25:16.939  6832  6832 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@216762ae
,08-31 15:25:16.995  6832  6832 D serial_port: close(fd = 25)
,08-31 15:25:17.001  6832  6832 I UEI.SmartControl: Serial port is closed.
08-31 15:25:17.002  6832  6832 I UEI.SmartControl: Serial port is closed.
08-31 15:25:17.002  6832  6832 D UEI.SmartControl: Blaster closed
08-31 15:25:17.002  6832  6832 D UEI.SmartControl: Shut down QS...
08-31 15:25:17.003  6832  6832 D UEI.SmartControl: Stopping QS lib
08-31 15:25:17.003  6832  6832 D UEI.SmartControl: QS lib stop result = true
08-31 15:25:17.003  6832  6832 D UEI.SmartControl: Stopped QS lib
08-31 15:25:17.003  6832  6832 D UEI.SmartControl: Stopped file observer...
08-31 15:25:17.003  6832  6832 D UEI.SmartControl: QS shutdown complete
,08-31 15:25:20.675  1044  1115 I ActivityManager: Waited long enough for: ServiceRecord{a50a40f u0 com.google.android.gms/.wearable.service.WearableService}
,08-31 15:25:20.687  2112  2112 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19992
,08-31 15:25:25.185  1044  1364 V AlarmManager: RTC_WAKEUP set : Alarm{107391cb type 0 when 1472649921245 com.android.vending} when 1472649921245
,08-31 15:25:25.197  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 15:25:25.197  6699  6809 I jxcore-log: 
08-31 15:25:25.201  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 15:25:25.201  6699  6809 I jxcore-log: 
,08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:25.208  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:25.219  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:25:25.224  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 15:25:25.224  6699  6809 I jxcore-log: 
08-31 15:25:25.239  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 15:25:25.239  6699  6809 I jxcore-log: 
,08-31 15:25:25.337  1044  1982 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:25:25.448  6117  6117 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 15:25:25.836  6699  6809 D executeNativeTests: Running unit tests
,08-31 15:25:25.917  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:25.917  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d added. We now have 2 listener(s)
,08-31 15:25:25.918  1044  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:25.920  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:25.920  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:25.920  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:25.920  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:25.920  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 added. We now have 2 listener(s)
08-31 15:25:25.920  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:25.920  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:25:25.922  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:25.927  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:25.929  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:25.929  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:25.931  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:25.932  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:25.934  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:25:25.936  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:25:25.936  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:25:25.938  6699  6809 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 15:25:25.938  6699  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:25:25.938  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:25:25.939  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:25:25.939  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:25:25.939  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:25.940  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:25.940  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:25.940  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:25.940  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.940  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:25.940  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:25.941  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d removed from the list
08-31 15:25:25.941  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.941  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 removed from the list
08-31 15:25:25.941  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:25.941  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.941  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.941  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.943  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:25.943  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:25:25.943  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.943  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.944  6699  6809 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 15:25:25.945  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:25.945  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:25.945  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:25.945  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:25.945  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.945  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.945  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:25.945  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.945  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.945  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:25.945  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.945  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.945  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.945  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.946  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:25.946  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:25.946  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.946  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgo,ingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:25:25.950  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:25:25.951  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:25.951  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:25.951  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:25:25.951  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:25.951  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.951  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.951  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:25.951  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:25.951  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.951  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:25.951  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:25.951  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.951  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.951  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.952  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:25.952  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:25.952  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.952  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.953  6699  6809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:25:25.954  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:25.958  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:25.959  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:25:25.959  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:25.960  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:25.961  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:25.961  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:25.961  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 15:25:25.962  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:25.962  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:25.962  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:25:25.965  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:25:25.965  1044  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:25:25.970  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:25:25.974  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:25:25.975  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 15:25:25.977  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:25:25.977  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:25.978  6699  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:25:25.978  6699  6809 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:25:25.981  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:25.981  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:25.981  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:25.981  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:25.981  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.981  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:25.981  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:25.981  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.981  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.981  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:25.981  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:25.981  6699  6809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:25:25.983  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:25.985  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:25.986  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:25.986  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:25.987  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:25.988  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:25.989  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:25.989  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:25.989  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:25.989  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:25.989  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:25:25.992  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:25:25.992  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:25.994  6699  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:25:25.994  6699  6809 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:25:25.995  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:25.995  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:25.995  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:25.995  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:25.995  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.995  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:25.995  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:25.995  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.995  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.995  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:25.995  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.995  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:25.995  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:25.996  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:25.996  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:25.997  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:25.997  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:25.997  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:25.997  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:25.997  6699  6809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:25:25.999  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:26.001  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:26.002  6699  6,809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.002  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:26.002  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:26.002  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:26.002  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:26.002  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:26.002  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:25:26.006  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:26.008  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:26.010  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:25:26.010  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:26.011  6699  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:25:26.011  6699  6809 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:25:26.011  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.011  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.011  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.012  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.012  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.012  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.012  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.012  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.012  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:26.012  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.012  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.012  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.012  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.012  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.013  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.013  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.014  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.014  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.014  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.014  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.014  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.014  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.015  6699  6809 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 15:25:26.015  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.015  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.015  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.017  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.017  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.017  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.017  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.017  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.017  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.017  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.017  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.018  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.018  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.018  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.018  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.018  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.019  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.019  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.019  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.019  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.019  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:25:26.020  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.020  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.020  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.020  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.020  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.020  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.020  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.020  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.020  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.020  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.020  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.020  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.020  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.020  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.020  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.020  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.021  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.021  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.021  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.021  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.021  6699  6809 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 15:25:26.021  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.021  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.021  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.022  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.022  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.022  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.022  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.022  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.022  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.022  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.022  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.022  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.022  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.022  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.022  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.022  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.022  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.022  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.022  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.023  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.023  6699  6809 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 15:25:26.023  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.023  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.023  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.023  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.023  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.023  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.023  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.023  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.023  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.023  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.023  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.023  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.023  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.023  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.024  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.024  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.024  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.024  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.024  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.024  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.025  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:25:26.025  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:25:26.025  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:25:26.026  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:25:26.026  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:25:26.026  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:25:26.026  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.026  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.026  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.027  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.027  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.027  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.027  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.027  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.027  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.027  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.027  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.027  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.027  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.027  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:26.032  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.032  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.032  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.032  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.032  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.032  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.033  6699  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:26.033  6699  6809 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:25:26.033  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:25:26.034  6699  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:26.035  6699  6809 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:25:26.035  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:25:26.035  6699  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 15:25:26.035  6699  6809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:25:26.036  6699  6809 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 15:25:26.036  6699  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:26.036  6699  6809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:25:26.036  6699  6809 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 15:25:26.036  6699  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:26.036  6699  6809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:25:26.036  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 15:25:26.040  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 15:25:26.041  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 15:25:26.041  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 15:25:26.042  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 15:25:26.042  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 15:25:26.042  6699  6809 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 15:25:26.042  6699  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:26.042  6699  6809 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 15:25:26.043  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.043  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.043  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.043  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.043  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.043  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.043  6699  6939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
08-31 15:25:26.043  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 15:25:26.043  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.043  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.043  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.044  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.044  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.044  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.044  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.044  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.044  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.044  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.045  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.045  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.045  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.045  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.046  6699  6809 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 15:25:26.046  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.046  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.046  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.047  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.047  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.047  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.047  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.047  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.047  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.047  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.047  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.047  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.047  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.047  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.047  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.047  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.048  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.048  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.048  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.048  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.049  6699  6809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 15:25:26.050  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.051  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.051  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.053  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.053  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.053  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.053  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.053  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.053  6699  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
08-31 15:25:26.054  6699  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 831)
08-31 15:25:26.054  6699  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 831)
08-31 15:25:26.054  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.054  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.054  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.054  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.054  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.054  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.055  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.055  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.055  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.055  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.055  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.055  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.056  6699  6809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 15:25:26.056  6699  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 15:25:26.056  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:25:26.056  6699  6809 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 15:25:26.056  6699  6809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:25:26.056  6699  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 15:25:26.056  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:25:26.056  6699  6809 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 15:25:26.056  6699  6809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:25:26.056  6699  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:25:26.056  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:25:26.056  6699  6809 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 15:25:26.056  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.056  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.056  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.056  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.056  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.056  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.056  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.056  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.056  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.056  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.056  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.056  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.056  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.056  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.057  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.057  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.057  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.057  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.057  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.057  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.058  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.058  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.058  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.058  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.058  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.058  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.058  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.058  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.058  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.058  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.058  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.058  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.058  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.058  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.058  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.058  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.058  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.058  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.058  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.058  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.058  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.058  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.058  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.058  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.058  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.058  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.058  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.058  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.058  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.060  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.060  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.060  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.060  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.060  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.060  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.061  6699  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 15:25:26.062  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:26.062  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 15:25:26.063  6699  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 15:25:26.063  6699  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 15:25:26.063  6699  6699 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 15:25:26.064  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:26.064  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 15:25:26.064  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:25:26.064  6699  6941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:26.065  3845  4000 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=83
08-31 15:25:26.065  6699  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-31 15:25:26.066  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.066  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 15:25:26.067  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 15:25:26.068  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 15:25:26.068  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.068  6699  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 15:25:26.068  6699  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 15:25:26.068  6699  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 15:25:26.069  6699  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 15:25:26.069  6699  6699 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 15:25:26.069  6699  6699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 15:25:26.069  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.070  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.070  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:25:26.070  6699  6809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:25:26.070  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:25:26.071  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:25:26.071  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:26.071  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:26.071  6699  6809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:25:26.071  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.071  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.072  6699  6809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:25:26.072  6699  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:26.072  6699  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:26.072  6699  6699 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:25:26.073  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.073  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.073  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.073  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.073  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.073  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.073  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.073  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.073  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.073  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.073  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.073  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.073  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.074  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.074  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.074  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.074  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.074  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.074  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.075  6699  6809 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 15:25:26.075  6699  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:25:26.075  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:25:26.075  6699  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:25:26.075  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.075  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.075  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.075  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.075  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.075  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.075  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.075  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.075  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.075  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.075  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.075  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.075  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.075  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.076  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.076  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.076  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.076  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.077  1044  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:26.077  1044  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:26.078  1044  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:26.078  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.078  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.078  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.078  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.078  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.078  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.078  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.078  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.078  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.078  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.078  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.078  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.078  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.078  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.079  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.079  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.079  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.079  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.080  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:26.080  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:26.080  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:26.080  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:26.080  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.080  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.080  6699  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25695f9d not in the list
08-31 15:25:26.080  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.080  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.080  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:26.080  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.080  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.080  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:26.080  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:26.080  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:26.080  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:26.080  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:26.080  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196dbc12 not in the list
08-31 15:25:26.081  6699  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 15:25:26.081  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:25:26.082  6699  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 15:25:26.082  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:25:26.082  6699  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 15:25:26.082  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:25:26.083  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:25:26.083  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 15:25:26.083  6699  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 15:25:26.083  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:25:26.084  6699  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 15:25:26.084  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:25:26.084  6699  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 15:25:26.084  6699  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 15:25:26.084  6699  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 15:25:26.084  6699  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 15:25:26.085  6699  6809 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 15:25:26.085  6699  6809 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 15:25:26.085  6699  6809 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 15:25:26.085  6699  6809 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 15:25:26.085  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:26.085  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f86485b added. We now have 2 listener(s)
08-31 15:25:26.085  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:26.086  6699  6809 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 15:25:26.087  1044  2036 D WifiServiceImplEx: setWifiEnabled: true pid=6699, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:25:26.087  1044  2036 D WifiService: setWifiEnabled: true pid=6699, uid=10118
08-31 15:25:26.087  1044  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:25:26.090  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:26.090  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@279ab8f8 added. We now have 3 listener(s)
08-31 15:25:26.090  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:26.093  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:26.093  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90c81d1 added. We now have 4 listener(s)
08-31 15:25:26.093  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:26.094  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:26.094  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22872436 added. We now have 5 listener(s)
08-31 15:25:26.094  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:26.095  1044  2036 D WifiServiceImplEx: setWifiEnabled: false pid=6699, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:25:26.095  1044  2036 D WifiService: setWifiEnabled: false pid=6699, uid=10118
08-31 15:25:26.095  1044  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:25:26.116  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 15:25:26.116  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:25:26.117  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-31 15:25:26.118  1044  1425 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:26.119  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:26.119  1044  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:26.119  1044  1999 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3107ca6d mBinding = false
08-31 15:25:26.119  1044  1425 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:26.120  1044  1425 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:26.120  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:26.120  1044  1425 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 15:25:26.120  1044  1425 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:25:26.120  1044  1425 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:25:26.121  1044  1425 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:25:26.121  1044  1425 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:25:26.169  6699  6939 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-31 15:25:26.171  6699  6939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
08-31 15:25:26.190  1044  1425 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:25:26.190  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:25:26.191  2743  2743 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:25:26.191  1044  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.191  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.191  1044  1425 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:25:26.191  1044  1425 D WifiNative-wlan0: doBoolean: SET ps 1
,08-31 15:25:26.192  1044  1425 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:25:26.192   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:25:26.193  1044  2847 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.196  1044  1119 D BluetoothManagerService: Message: 2
08-31 15:25:26.198  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:25:26.199  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:25:26.199  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-31 15:25:26.199  1044  1119 D BluetoothManagerService: Sending off request.
08-31 15:25:26.200  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:26.202  3845  3861 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 15:25:26.203  3845  3929 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 15:25:26.203  3845  3929 D BluetoothAdapterProperties: Setting state to 13
08-31 15:25:26.203  3845  3929 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 15:25:26.204  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:26.204  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 15:25:26.204  3845  3929 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:25:26.204  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 15:25:26.204  3845  3929 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 15:25:26.207  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:26.209  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:26.212  3845  3845 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:26.212  3845  3845 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:25:26.212  3845  3845 V BluetoothMapService: Handler(): got msg=4
08-31 15:25:26.212  3845  3845 D BluetoothMapService: MAP Service closeService in
08-31 15:25:26.212  3845  3845 D BluetoothMapMasInstance: MAP Service shutdown
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 15:25:26.213  3845  4152 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 15:25:26.214  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:25:26.214  3845  3845 V BluetoothMapService: MAP Service closeService out
08-31 15:25:26.215  3845  3845 V BtOppService: Receiver DISABLED_ACTION 
08-31 15:25:26.215  3845  3845 I BtOppRfcommListener: stopping Accept Thread
08-31 15:25:26.215  3845  3845 V BtOppRfcommListener: close mBtServerSocket
08-31 15:25:26.216  3845  3845 V BtOppRfcommListener: waiting for thread to terminate
08-31 15:25:26.216  3845  4214 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:26.216  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:26.216  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:26.216  3845  4214 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 15:25:26.217  3845  3845 V BtOppRfcommListener: done waiting for thread to terminate
08-31 15:25:26.218  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.218  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.218  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08,-31 15:25:26.223  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:26.223  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:26.227  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.227  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.230  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:26.239  1044  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 15:25:26.239  1044  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-31 15:25:26.241  1044  1982 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-31 15:25:26.242  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.242  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.242  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 15:25:26.242  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.242  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-31 15:25:26.242  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:26.242  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:26.243  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.243  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:26.245  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:26.245  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:26.245  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.245  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE,, BSSID name: null
08-31 15:25:26.268  1044  1115 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6955 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 15:25:26.269  3845  3936 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:25:26.269  3845  3929 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 15:25:26.269  3845  3929 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 15:25:26.270  3845  4221 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:26.271  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 15:25:26.271  3845  4030 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 15:25:26.272  3845  4223 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:26.272  3845  4153 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 15:25:26.274  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 15:25:26.274  3845  4030 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:25:26.275  1044  1425 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 15:25:26.275  1044  1425 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.275  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.276  1044  1425 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.276  1044  1425 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.277  1044  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.277  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.278  1044  1375 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@13de05d0
08-31 15:25:26.278  1044  1375 D LGWifiP2pService: P2pDisablingState
08-31 15:25:26.278  1044  1375 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.278  1044  1375 D LGWifiP2pService: p2p socket connection lost
08-31 15:25:26.278  1044  1375 D LGWifiP2pService: P2pDisabledState
08-31 15:25:26.278  3845  3845 V BtOppService: onDestroy
08-31 15:25:26.279  3845  3845 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-31 15:25:26.281  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.281  1044  1425 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.282  1044  1425 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.282  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.283  1044  1425 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:26.283  1044  1425 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 15:25:26.283  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:25:26.284  2743  2743 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:25:26.286  1044  1484 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 15:25:26.286   308  6966 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 15:25:26.286  1044  1484 D DSQN    : disableDataServiceNotify
08-31 15:25:26.286  1044  1375 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.286  1044  1375 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.286  1044  1484 D DSQN    : stop dsqn bin
08-31 15:25:26.286  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 15:25:26.287  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-31 15:25:26.287  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 15:25:26.287  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:26.287  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:26.288  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.288  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:26.288  1044  1425 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:25:26.288  1044  1425 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:25:26.289  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:26.289  1044  1425 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:25:26.289  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 15:25:26.289   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:25:26.290  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.290  1044  1044 W Settings: Se,tting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.290  1044  1484 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 15:25:26.290  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:25:26.290  1044  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:26.290  1044  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:25:26.291  1044  1484 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:25:26.291  1044  1484 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 15:25:26.291  1589  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 15:25:26.291  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.291  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.291  1044  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-31 15:25:26.293  1044  1484 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 15:25:26.293  1044  1484 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 15:25:26.293  1044  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:25:26.294  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:25:26.294  1928  1928 D WfdsService: WifiP2pState is changed : false
08-31 15:25:26.294  1928  2299 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 15:25:26.294  1928  2299 D WfdsService: Set the WFDS Monitor: false
08-31 15:25:26.295  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-31 15:25:26.295  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.295  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.295  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:25:26.295  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 15:25:26.295  1044  1044 D RttService: SCAN_AVAILABLE : 1
08-31 15:25:26.295  1044  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.295  1928  2299 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:25:26.295  1928  2299 D WfdsService: STATE : WfdsDisabledState - enter
08-31 15:25:26.295  1044  1543 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:26.296  1928  2766 D CtrlSupplicant: Received on exit socket, terminate
08-31 15:25:26.296  1928  2766 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 15:25:26.296  1928  2766 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 15:25:26.296  1928  2766 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 15:25:26.296  1928  2299 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 15:25:26.297  1928  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 15:25:26.306  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 15:25:26.306  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:26.307  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:26.309  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:26.309  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:26.310  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:26.330  1044  1115 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6975 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 15:25:26.331  1044  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:26.331  1044  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 15:25:26.331  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 15:25:26.331  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:25:26.331  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:25:26.331  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 15:25:26.332  1044  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 15:25:26.332  1044  1425 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 15:25:26.337  1044  1425 D WifiNative-p2p0: TERMINATE: returned true
08-31 15:25:26.337  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:26.337  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:26.337  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:25:26.351   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 20.288ms
,08-31 15:25:26.370   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 395us total 18.552ms
,08-31 15:25:26.389   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 17.854ms
,08-31 15:25:26.415  1044  2847 D DhcpStateMachine: StoppedState
,08-31 15:25:26.415  1044  2847 D DhcpStateMachine: StoppedState{ when=-126ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:26.429  1044  1908 I art     : Explicit concurrent mark sweep GC freed 34041(1714KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.953ms total 96.308ms
,08-31 15:25:26.431  1044  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:26.434  1044  1484 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:26.435  1044  1484 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:26.436  1044  1484 D NetworkManagementService: Removing idletimer
08-31 15:25:26.436  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:26.437  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:25:26.437  1044  1484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.438  1044  1484 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 15:25:26.439  1044  1425 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:26.439  1044  1425 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:26.457  6955  6955 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:26.457  6955  6955 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 15:25:26.457  6955  6955 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:25:26.457  6955  6955 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-31 15:25:26.458  6955  6955 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 15:25:26.459  6955  6955 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 15:25:26.461  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-31 15:25:26.465  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.465  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.465  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:25:26.466  1044  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 15:25:26.467  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 15:25:26.468  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:25:26.468  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:25:26.468  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 15:25:26.471  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 15:25:26.474  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 15:25:26.474  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:26.474  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:26.474  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:26.474  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 15:25:26.475  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.476  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:26.477  1044  1425 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 15:25:26.478  1044  1425 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 15:25:26.480  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:26.480  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:26.481  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:26.481  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:26.505  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:25:26.506  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:26.507  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:26.508  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 15:25:26.508  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:26.509  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:26.509  2743  2743 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 15:25:26.509  2743  2743 I wpa_supplicant: monitor socket send errors count : 1
08-31 15:25:26.509  2743  2743 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
08-31 15:25:26.511  1044  2762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 15:25:26.511  1044  2762 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 15:25:26.542  6975  6975 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 15:25:26.543  6975  6975 W LG Account v2.2: No ProfileInfo entries
08-31 15:25:26.543  6975  6975 I LG Account v2.2: isEnabled: false
08-31 15:25:26.543  6975  6975 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 15:25:26.543  6975  6975 I Feature : [Lifetracker]Country: EU
08-31 15:25:26.543  6975  6975 I Feature : [Lifetracker]Operator: OPEN
08-31 15:25:26.543  6975  6975 I Feature : [Lifetracker]Ranking support: false
08-31 15:25:26.543  6975  6975 I Feature : [Lifetracker]Comfort support: false
08-31 15:25:26.544  6975  6975 I Feature : [Lifetracker]Accessory: true
08-31 15:25:26.544  6975  6975 I Feature : [Lifetracker]Health device: true
08-31 15:25:26.544  6975  6975 I Feature : [Lifetracker]Extra Pedometer: false
08-31 15:25:26.544  6975  6975 I Feature : [Lifetracker]Blood glucose device: false
08-31 15:25:26.544  6975  6975 I Feature : [Lifetracker]Device Number: 3
,08-31 15:25:26.550  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:25:26.551  2743  2743 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:25:26.551  1044  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 15:25:26.551  1044  1119 D Tethering: InitialState.processMessage what=4
08-31 15:25:26.551  1044  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:25:26.551  1044  2762 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:25:26.552  1044  2762 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 15:25:26.552  2743  2743 W wpa_supplicant: USIM:  scard_deinit function
08-31 15:25:26.552  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:26.552  1044  1425 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123699
08-31 15:25:26.553  1044  1425 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123699
08-31 15:25:26.553  1044  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:25:26.553  1044  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:25:26.554  1044  1425 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:26.554  1044  1425 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:26.554  1044  1425 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=123700  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:25:26.554  1044  1425 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=123701  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:25:26.552  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:26.555  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:26.556  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:26.562  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:26.573  6699  6699 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:25:26.585  1044  1927 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6994 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 15:25:26.585  1044  1927 I ActivityManager: Killing 6269:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-31 15:25:26.597  6955  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 15:25:26.619  2743  2743 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 15:25:26.620  1044  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-31 15:25:26.620  1044  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 15:25:26.620  1044  2762 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 15:25:26.620  1044  1425 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-31 15:25:26.629  1044  1764 W libprocessgroup: failed to open /acct/uid_10014/pid_6269/cgroup.procs: No such file or directory
,08-31 15:25:26.637  1044  1119 D BluetoothManagerService: Message: 20
08-31 15:25:26.637  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@252a0b8f:true
08-31 15:25:26.643  3845  3845 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:25:26.643  3845  3845 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:26.644  3845  3845 V BluetoothPbapReceiver: ***********state = 13
08-31 15:25:26.646  3845  3845 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-31 15:25:26.647  3845  3845 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:26.647  3845  3845 V BluetoothPbapService: state: 13
08-31 15:25:26.648  3845  3845 V BluetoothPbapService: Pbap Service closeService in
08-31 15:25:26.649  3845  3845 V BluetoothPbapService: successfully stopped pbap service
08-31 15:25:26.649  3845  3845 V BluetoothPbapService: Pbap Service closeService out
08-31 15:25:26.649  3845  3845 V BluetoothPbapService: Pbap Service onDestroy
08-31 15:25:26.649  3845  3845 V BluetoothPbapService: Pbap Service closeService in
08-31 15:25:26.649  3845  3845 V BluetoothPbapService: Pbap Service closeService out
08-31 15:25:26.649  3845  3845 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 15:25:26.650  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:26.655  1044  1119 D BluetoothManagerService: Message: 30
08-31 15:25:26.660  1044  1119 D BluetoothManagerService: Message: 30
,08-31 15:25:26.663  6955  6955 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 15:25:26.664  6955  6955 D BluetoothMap: Create BluetoothMap proxy object
08-31 15:25:26.665  1044  1119 D BluetoothManagerService: Message: 30
08-31 15:25:26.669  1044  1119 D BluetoothManagerService: Message: 30
08-31 15:25:26.672  6955  6955 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 15:25:26.673  6955  6955 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 15:25:26.692  6955  6955 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-31 15:25:26.696  6955  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-31 15:25:26.706  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 15:25:26.711  6955  6955 D DockEventReceiver: finishStartingService: stopping service
08-31 15:25:26.716  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:25:26.716  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:26.721  1044  1561 I ActivityManager: Killing 6327:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-31 15:25:26.727  6955  6955 D BluetoothInputDevice: Proxy object connected
08-31 15:25:26.728  6955  6955 D HidProfile: Bluetooth service connected
08-31 15:25:26.729  6955  6955 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:25:26.730  6955  6955 D PanProfile: Bluetooth service connected
08-31 15:25:26.731  6955  6955 D BluetoothMap: Proxy object connected
08-31 15:25:26.732  6955  6955 D MapProfile: Bluetooth service connected
08-31 15:25:26.732  6955  6955 D BluetoothMap: getConnectedDevices()
08-31 15:25:26.733  6955  6955 D BluetoothMap: Bluetooth is Not enabled
08-31 15:25:26.733  6955  6955 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 15:25:26.765  1044  1982 W libprocessgroup: failed to open /acct/uid_10004/pid_6327/cgroup.procs: No such file or directory
,08-31 15:25:26.767  1044  1425 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 15:25:26.767  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:26.767  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:26.767  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:25:26.768  1928  1928 D WfdsService: Supplicant Connection state is changed : false
08-31 15:25:26.768  1928  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 15:25:26.768  1928  2299 D WfdsService: Set the WFDS Monitor: false
08-31 15:25:26.768  1928  2299 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:25:26.770  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:25:26.772  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:26.773  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:26.774  2456  2456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:26.775  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:26.778  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 15:25:26.778  1044  1455 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 15:25:26.779  1044  1455 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-31 15:25:26.789  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:26.834  6955  6955 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:25:26.834  6955  6955 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:25:26.848  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:26.849  6955  6955 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 15:25:26.854  6955  6955 D BluetoothPermissionRequest: onReceive
08-31 15:25:26.858  6955  6955 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 15:25:26.868  1044  1908 I ActivityManager: Killing 6528:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 15:25:26.871  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:25:26.921  3845  3845 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 15:25:26.922  3845  3845 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-31 15:25:26.923  3845  3845 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-31 15:25:26.934  1044  2036 W libprocessgroup: failed to open /acct/uid_10008/pid_6528/cgroup.procs: No such file or directory
,08-31 15:25:27.032  1044  1908 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7022 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-31 15:25:27.032  3845  3845 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:27.033  3845  3845 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 15:25:27.035  3845  3845 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:25:27.035  3845  3845 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:27.035  3845  3845 V BluetoothFtpService: Ftp Service closeService
08-31 15:25:27.035  3845  3845 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 15:25:27.038  3845  3845 V BluetoothFtpService: successfully stopped ftp service
08-31 15:25:27.039  3845  3845 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:25:27.039  3845  3845 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:25:27.039  3845  3845 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:25:27.039  3845  3845 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:27.039  3845  3845 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 15:25:27.039  3845  3845 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 15:25:27.041  3845  3845 V BluetoothFtpService: Ftp Service onDestroy
08-31 15:25:27.041  3845  3845 V BluetoothFtpService: Ftp Service closeService
,08-31 15:25:27.098  1044  1060 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7042 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 15:25:27.102  3845  3845 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:27.102  3845  3845 V BluetoothSapService: state: 13
,08-31 15:25:27.102  3845  3845 V BluetoothSapService: Stopping SAP server process
08-31 15:25:27.103  3845  3845 V BluetoothSapService: Sap Service closeSapService in
08-31 15:25:27.103  3845  3845 V BluetoothSapService: Close listen Socket : 
08-31 15:25:27.103  3845  3845 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:25:27.103  3845  3845 V BluetoothSapService: Close sapd  Socket : 
08-31 15:25:27.109  3845  3845 V BluetoothSapService: Sap Service closeSapService out
08-31 15:25:27.112  3845  3845 V BluetoothSapService: Sap Service onDestroy
08-31 15:25:27.112  3845  3845 V BluetoothSapService: Sap Service closeSapService in
08-31 15:25:27.112  3845  3845 V BluetoothSapService: Close listen Socket : 
08-31 15:25:27.112  3845  3845 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:25:27.112  3845  3845 V BluetoothSapService: Close sapd  Socket : 
08-31 15:25:27.112  3845  3845 V BluetoothSapService: Sap Service closeSapService out
,08-31 15:25:27.140  7022  7022 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:25:27.159  7042  7042 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:25:27.169  7022  7022 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 15:25:27.179  1044  2036 I ActivityManager: Killing 6046:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-31 15:25:27.208  7022  7022 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 15:25:27.208  7022  7022 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 15:25:27.209  7022  7022 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-31 15:25:27.209  7022  7022 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 15:25:27.210  7022  7022 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 15:25:27.212  7022  7022 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 15:25:27.217  7022  7022 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 15:25:27.242  1044  1982 W libprocessgroup: failed to open /acct/uid_10011/pid_6046/cgroup.procs: No such file or directory
,08-31 15:25:27.266  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:25:27.274  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:27.279  3845  4030 W bt-btif : ag scb idx 1 not allocated
08-31 15:25:27.279  3845  3936 D bt_hci_bdroid: cleanup
,08-31 15:25:27.279  3845  4030 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:27.279  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:27.280  3845  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:27.280  3845  4030 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:25:27.280  3845  4033 I bt_lpm  : LPM is already off!!!
08-31 15:25:27.281  3845  4137 I bt_userial_mct: exiting userial_read_thread
08-31 15:25:27.281  3845  4137 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 15:25:27.281  3845  3936 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 15:25:27.281  3845  4033 I bt_vendor: hw_epilog_process
08-31 15:25:27.282  3845  3936 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 15:25:27.282  3845  3936 D bt_userial_mct: userial_close
08-31 15:25:27.282  3845  3936 E bt_userial_mct: pthread_join() FAILED result:3
08-31 15:25:27.283  3845  3936 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 15:25:27.319  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 15:25:27.324  7022  7022 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 15:25:27.328  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:27.335  7022  7022 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-31 15:25:27.338  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:25:27.338  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:25:27.338  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:27.343  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:27.347  3845  3936 D bt_hci_bdroid: set_power 0
08-31 15:25:27.347  3845  3936 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 15:25:27.347  3845  3936 I bt_vendor: bluetooth satus is on
08-31 15:25:27.347  3845  3936 I bt_vendor: bt-vendor : resetting BT status
08-31 15:25:27.347  3845  3936 I bt_vendor: Starting hciattach daemon
,08-31 15:25:27.347  3845  3936 I bt_vendor: try to set false
08-31 15:25:27.349  3845  3936 I bt_vendor: Starting hciattach daemon
08-31 15:25:27.349  3845  3936 I bt_vendor: try to set false
08-31 15:25:27.350  3845  3936 I bt_vendor: cleanup
08-31 15:25:27.351  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:27.351  3845  4030 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 15:25:27.351  3845  3936 I GKI_LINUX: GKI_exit_task 0 done
,08-31 15:25:27.351  3845  3936 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 15:25:27.353  3845  3929 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 15:25:27.357  3845  3845 D HeadsetService: Received stop request...Stopping profile...
08-31 15:25:27.362  3845  3845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:25:27.362  3845  3845 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:25:27.362  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30208ff3
08-31 15:25:27.362  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:27.362  3845  3967 D HeadsetStateMachine: Exit Disconnected: -1
08-31 15:25:27.364  1839  1839 D BluetoothHeadset: Proxy object disconnected
,08-31 15:25:27.364  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:27.366  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-31 15:25:27.367  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-31 15:25:27.367  1044  1044 D BluetoothHeadset: Proxy object disconnected
08-31 15:25:27.367  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 15:25:27.369  3845  3845 D A2dpService: Received stop request...Stopping profile...
08-31 15:25:27.369  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:25:27.370  3845  4017 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:25:27.370  3845  3845 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 15:25:27.373  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:27.378  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:25:27.378  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:25:27.378  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:25:27.383  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:27.384  3845  3929 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 15:25:27.385  3845  3845 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 15:25:27.385  3845  3845 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:25:27.385  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30208ff3
08-31 15:25:27.387  1044  1044 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:27.387  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 15:25:27.387  3845  3845 D HeadsetStateMachine: Unbinding service...
08-31 15:25:27.388  3845  3845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:25:27.388  3845  3845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:25:27.388  3845  3845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:25:27.388  3845  3845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:25:27.388  3845  3845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 15:25:27.388  3845  3845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:25:27.388  3845  3845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:25:27.389  3845  3845 D HidService: Received stop request...Stopping profile...
08-31 15:25:27.389  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30208ff3
08-31 15:25:27.390  3845  3845 D HealthService: Received stop request...Stopping profile...
,08-31 15:25:27.390  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30208ff3
08-31 15:25:27.393  3845  3845 D PanService: Received stop request...Stopping profile...
08-31 15:25:27.394  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30208ff3
08-31 15:25:27.394  3845  3845 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:25:27.394  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:27.395  3845  3845 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 15:25:27.395  3845  3845 D BtGatt.GattService: stop()
08-31 15:25:27.395  3845  3845 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 15:25:27.397  6955  6955 D BluetoothInputDevice: Proxy object disconnected
08-31 15:25:27.397  6955  6955 D HidProfile: Bluetooth service disconnected
08-31 15:25:27.397  6955  6955 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:25:27.397  6955  6955 D PanProfile: Bluetooth service disconnected
08-31 15:25:27.397  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30208ff3
08-31 15:25:27.398  3845  3845 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:25:27.398  3845  3845 D BluetoothMapService: stop()
08-31 15:25:27.399  3845  3845 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 15:25:27.399  3845  3845 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 15:25:27.403  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:25:27.403  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:27.403  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30208ff3
08-31 15:25:27.405  6955  6955 D BluetoothMap: Proxy object disconnected
08-31 15:25:27.405  6955  6955 D MapProfile: Bluetooth service disconnected
08-31 15:25:27.406  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:25:27.406  3845  3845 I BluetoothA2dpServiceJni: cleanupNative
08-31 15:25:27.406  3845  4018 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 15:25:27.407  3845  3845 I GKI_LINUX: GKI_exit_task 2 done
08-31 15:25:27.407  3845  3845 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 15:25:27.407  3845  3845 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:25:27.407  3845  3845 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:25:27.407  3845  3845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:25:27.407  3845  3845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:25:27.407  3845  3845 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:25:27.408  3845  3845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:25:27.408  3845  3845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 15:25:27.410  3845  3845 V BluetoothMapService: Handler(): got msg=4
08-31 15:25:27.410  3845  3845 D BluetoothMapService: MAP Service closeService in
08-31 15:25:27.410  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:25:27.410  3845  3845 V BluetoothMapService: MAP Service closeService out
08-31 15:25:27.410  3845  3929 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 15:25:27.410  3845  3929 D BluetoothAdapterProperties: Setting state to 10
08-31 15:25:27.410  3845  3929 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 15:25:27.411  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:27.411  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 15:25:27.411  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-31 15:25:27.411  3845  3845 D BluetoothMapService: cleanup()
08-31 15:25:27.411  3845  3845 D BluetoothMapService: MAP Service closeService in
08-31 15:25:27.411  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:25:27.411  3845  3845 V BluetoothMapService: MAP Service closeService out
08-31 15:25:27.412  3845  3929 I BluetoothAdapterState: Entering OffState
08-31 15:25:27.412  1839  2575 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:25:27.461  1044  1561 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7064 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-31 15:25:27.463  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:25:27.467  6955  6974 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:25:27.468  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:25:27.469  6955  6973 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:25:27.470  1839  2754 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:25:27.471  6955  7063 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:25:27.472  6955  6974 D BluetoothMap: onBluetoothStateChange: up=false
08-31 15:25:27.473  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:25:27.474  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 15:25:27.475  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 15:25:27.479  1044  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 15:25:27.479  1044  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 15:25:27.479  1044  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3107ca6d mBinding = false
08-31 15:25:27.480  1044  1119 D BluetoothManagerService: Sending unbind request.
,08-31 15:25:27.493  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-31 15:25:27.496  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:27.497  1928  2121 D LGBluetoothAPIService: Message: 2
08-31 15:25:27.497  1928  2121 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@b41a632 mBinding = false
08-31 15:25:27.497  1928  2121 D LGBluetoothAPIService: Sending unbind request.
08-31 15:25:27.498  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:27.500  3845  3936 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 15:25:27.500  3845  3845 I GKI_LINUX: GKI_exit_task 1 done
08-31 15:25:27.500  3845  3845 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 15:25:27.501  3845  3845 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 15:25:27.501  3845  3845 I art     : --- WEIRD: removing null entry 246
08-31 15:25:27.501  3845  3845 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 15:25:27.501  3845  3845 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 15:25:27.502  3845  3845 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 15:25:27.503  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:27.503  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:27.505  1589  1589 D BluetoothAdapter: 29862123: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:27.505  1589  1589 D BluetoothAdapter: 29862123: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:27.505  6955  6955 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 15:25:27.506  6955  6955 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-31 15:25:27.506  6955  6955 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 15:25:27.509  3845  3845 I art     : System.exit called, status: 0
08-31 15:25:27.509  3845  3845 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 15:25:27.512  6955  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:25:27.519  6955  6955 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:27.546   312  1381 V AudioFlinger: 3845 died, releasing its sessions
08-31 15:25:27.546   312  1381 V AudioFlinger:  pid 1839 @ 0
,08-31 15:25:27.546   312  1381 V AudioFlinger:  pid 3427 @ 1
08-31 15:25:27.546   312  1381 V AudioFlinger:  pid 3427 @ 2
08-31 15:25:27.547  6955  6955 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-31 15:25:27.587  1044  1561 I ActivityManager: Process com.android.bluetooth (pid 3845) has died
08-31 15:25:27.587  1044  1561 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-31 15:25:27.601  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:27.608  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:25:27.620  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:27.629  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:27.631  6955  6955 D BluetoothPermissionRequest: onReceive
08-31 15:25:27.633  6955  6955 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 15:25:27.633  6955  6955 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 15:25:27.635  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 15:25:27.688  1044  1999 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7093 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 15:25:27.715  7064  7090 W FormManager: Network not available. Please check & try again.
08-31 15:25:27.716  7064  7092 V FormManager: Network unavailable.
,08-31 15:25:27.718  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:27.718  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:25:27.718  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:25:27.719  6955  6955 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:25:27.720  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:25:27.720  7064  7092 V FormManager: Network unavailable.
08-31 15:25:27.730  6955  6955 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:25:27.730  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:25:27.730  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:25:27.730  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:25:27.731  6955  6955 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-31 15:25:27.733  6955  6955 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 15:25:27.739  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:27.740  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:25:27.741  1044  1982 I ActivityManager: Killing 6069:com.android.contacts/u0a19 (adj 15): empty #17
08-31 15:25:27.743  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 15:25:27.772  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 15:25:27.775  1044  1963 W libprocessgroup: failed to open /acct/uid_10019/pid_6069/cgroup.procs: No such file or directory
08-31 15:25:27.789  4328  7112 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:25:27.792  6994  6994 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 15:25:27.792  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:25:27.792  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:27.793  7093  7093 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 15:25:27.794  7093  7093 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:25:27.794  7093  7093 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 15:25:27.795  7093  7093 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 15:25:27.797  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:27.800  7064  7114 W FormManager: Network not available. Please check & try again.
,08-31 15:25:27.806  4328  7116 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:27.806  4328  7116 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:25:27.810  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:27.814  7064  7115 V FormManager: Network unavailable.
,08-31 15:25:27.820  7093  7093 D BluetoothAdapterApp: Loading JNI Library
08-31 15:25:27.827  7064  7115 V FormManager: Network unavailable.
08-31 15:25:27.829  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 15:25:27.830  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 15:25:27.831  7022  7022 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-31 15:25:27.857  7093  7093 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@78bfa98 Instance Count = 1
,08-31 15:25:27.862  7093  7093 D BluetoothAdapterApp: onCreate
08-31 15:25:27.870  7022  7022 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:25:27.870  7022  7022 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:25:27.878  7022  7022 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 15:25:27.879  7022  7022 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 15:25:27.879  7022  7022 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 15:25:27.879  7022  7022 V SoundPool: doLoad: loading sample sampleID=1
08-31 15:25:27.880  7022  7022 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 15:25:27.884  7022  7119 V SoundPool: Start decode
08-31 15:25:27.884  7022  7119 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-31 15:25:27.886  7093  7093 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 15:25:27.886  7093  7093 D ProfileConfigQcom: Adding HeadsetService
08-31 15:25:27.886  7093  7093 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 15:25:27.886  7093  7093 D ProfileConfigQcom: Adding A2dpService
08-31 15:25:27.886  7093  7093 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 15:25:27.887  7093  7093 D ProfileConfigQcom: Adding HidService
08-31 15:25:27.887  7093  7093 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 15:25:27.887  7093  7093 D ProfileConfigQcom: Adding HealthService
08-31 15:25:27.887  7093  7093 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 15:25:27.889  7093  7093 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 15:25:27.889  7093  7093 D ProfileConfigQcom: Adding PanService
08-31 15:25:27.889  6832  6832 D UEI.SmartControl: QS Service created
08-31 15:25:27.889  7093  7093 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 15:25:27.889  7093  7093 D ProfileConfigQcom: Adding GattService
08-31 15:25:27.890  7093  7093 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 15:25:27.890  7093  7093 D ProfileConfigQcom: Adding BluetoothMapService
08-31 15:25:27.890  7093  7093 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 15:25:27.892  7093  7093 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 15:25:27.896   312  2136 V MediaPlayerService: decode(23, 10857164, 17813)
,08-31 15:25:27.896   312  2136 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 15:25:27.897   312  2136 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 15:25:27.897   312  2136 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 15:25:27.897   312  2136 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 15:25:27.897   312  2136 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 15:25:27.897   312  2136 V MediaPlayerService: player type = 3
08-31 15:25:27.897   312  2136 V AwesomePlayer: AwesomePlayer create()
08-31 15:25:27.898   312  2136 V AwesomePlayer: reset_l() 
08-31 15:25:27.898   312  2136 V AwesomePlayer: cancelPlayerEvents
08-31 15:25:27.898   312  2136 V AwesomePlayer: setAudioSink() 
08-31 15:25:27.898   312  2136 V AwesomePlayer: reset_l() 
08-31 15:25:27.898   312  2136 V AudioCache: notify(0xb14322c0, 8, 0, 0)
08-31 15:25:27.898   312  2136 V AudioCache: ignored
08-31 15:25:27.898   312  2136 V AwesomePlayer: cancelPlayerEvents
08-31 15:25:27.898   312  2136 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 15:25:27.898   312  2136 V AwesomePlayer: setDataSource_l dataSource
08-31 15:25:27.898   312  2136 V LGParserOSAL: SniffLGParser start
08-31 15:25:27.898   312  2136 V LGParserOSAL: MainType:5, SubType=0
08-31 15:25:27.899   312  2136 V LGParserOSAL: #### check Mime : application/ogg
08-31 15:25:27.899   312  2136 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 15:25:27.899   312  2136 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 15:25:27.899  7022  7022 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 15:25:27.901  7022  7022 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:25:27.902  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 15:25:27.911  6955  6955 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 15:25:27.913  7093  7093 V LGMDMManagerInternal: Create singleton instance
08-31 15:25:27.917  7022  7022 V LGMDMManager: Create singleton instance
08-31 15:25:27.930  6832  6832 I UEI.SmartControl: Service initServices...
,08-31 15:25:27.930  6832  6832 D UEI.SmartControl: QS start get config
08-31 15:25:27.958   312  2136 V LGParserOSAL: supported mime: application/ogg
08-31 15:25:27.958   312  2136 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 15:25:27.958   312  2136 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 15:25:27.958   312  2136 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 15:25:27.958   312  2136 V AwesomePlayer: AudioTrack Setting
08-31 15:25:27.958   312  2136 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 15:25:27.958   312  2136 V AwesomePlayer: setAudioSource() 
08-31 15:25:27.958   312  2136 V MediaPlayerService: prepare
08-31 15:25:27.958   312  2136 V AwesomePlayer: prepareAsync_l() 
08-31 15:25:27.959   312  2136 V MediaPlayerService: wait for prepare
08-31 15:25:27.960   312  7121 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 15:25:27.960   312  7121 V AwesomePlayer: initAudioDecoder() 
08-31 15:25:27.960   312  7121 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 15:25:27.960   312  7121 V AudioSystem: isOffloadSupported()
08-31 15:25:27.960   312  7121 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 15:25:27.960   312  7121 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 15:25:27.960   312  7121 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 15:25:27.960   312  7121 V AwesomePlayer: getUseOffload() = 0 
08-31 15:25:27.960   312  7121 V OMXCodec: OMXCodec::Create
08-31 15:25:27.960   312  7121 V OMXCodec: findMatchingCodecs()
08-31 15:25:27.960   312  7121 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 15:25:27.960   312  7121 V OMXCodec: matchingCodecs.size()=1
08-31 15:25:27.960   312  7121 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-31 15:25:27.966   312  7121 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 15:25:27.966   312  7121 V LGCodecAdapter: LG Codec Adapter start
08-31 15:25:27.967   312  7121 V OMXCodec: OMXCodec Createtor
08-31 15:25:27.967   312  7121 V OMXCodec: setComponentRole
08-31 15:25:27.967   312  7121 V OMXCodec: configureCodec protected=0
08-31 15:25:27.967   312  7121 V LGCodecAdapter: called getLGCodecSpecificData
08-31 15:25:27.967   312  7121 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 15:25:27.967   312  7121 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 15:25:27.967   312  7121 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 15:25:27.967   312  7121 V LGCodecOSAL: Not support LGCodec
08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 15:25:27.967   312  7121 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 15:25:27.967   312  7121 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 15:25:27.967   312  7121 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 15:25:27.967   312  7121 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 15:25:27.967   312  7121 V AudioSystem: isOffloadSupported()
08-31 15:25:27.967   312  7121 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 15:25:27.967   312  7121 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 15:25:27.967   312  7121 V OMXCodec: init()
,08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 15:25:27.967   312  7121 V OMXCodec: allocateBuffers
08-31 15:25:27.967   312  7121 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-31 15:25:27.967   312  7121 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 15:25:27.967   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 15:25:27.968   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-31 15:25:27.968   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-31 15:25:27.968   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-31 15:25:27.968   312  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-31 15:25:27.968   312  7121 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 15:25:27.968   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 15:25:27.968   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 15:25:27.968   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 15:25:27.968   312  7121 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 15:25:27.968   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 15:25:27.968   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 15:25:27.968   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 15:25:27.968   312  7121 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 15:25:27.968   312  7121 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 15:25:27.968   312  7121 V AudioCache: notify(0xb14322c0, 5, 0, 0)
08-31 15:25:27.968   312  7121 V AudioCache: ignored
08-31 15:25:27.968   312  7121 V AudioCache: notify(0xb14322c0, 1, 0, 0)
08-31 15:25:27.968   312  7121 V AudioCache: prepared
08-31 15:25:27.968   312  2136 V AudioCache: wait - success
08-31 15:25:27.968   312  2136 V MediaPlayerService: start
08-31 15:25:27.968   312  2136 V AwesomePlayer: play_l() 
08-31 15:25:27.968   312  2136 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 15:25:27.968   312  2136 V AwesomePlayer: createAudioPlayer_l
08-31 15:25:27.968   312  2136 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 15:25:27.968   312  2136 V AwesomePlayer: startAudioPlayer_l() 
08-31 15:25:27.968   312  2136 D AudioPlayer: start of Playback, useOffload 0
08-31 15:25:27.968   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 15:25:27.968   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 15:25:27.970   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 15:25:27.970   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 15:25:27.970   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 15:25:27.970   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 15:25:27.970   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 15:25:27.970   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bu,fIndex=0
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 15:25:27.971   312  7123 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-31 15:25:27.971   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-31 15:25:27.972   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 15:25:27.972   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 15:25:27.974   312  2136 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-31 15:25:27.975   312  2136 V AudioCache: notify(0xb14322c0, 6, 0, 0)
08-31 15:25:27.975   312  2136 V AudioCache: ignored
08-31 15:25:27.976   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.976   312  2136 V MediaPlayerService: wait for playback complete
08-31 15:25:27.976   312  7124 V AudioCache: memcpy(0xaf004000, 0xb1789000, 4096)
08-31 15:25:27.977   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.977   312  7124 V AudioCache: memcpy(0xaf005000, 0xb1789000, 4096)
08-31 15:25:27.977   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.977   312  7124 V AudioCache: memcpy(0xaf006000, 0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: memcpy(0xaf007000, 0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: memcpy(0xaf008000, 0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: memcpy(0xaf009000, 0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.979   312  7124 V AudioCache: memcpy(0xaf00a000, 0xb1789000, 4096)
08-31 15:25:27.980   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.980   312  7124 V AudioCache: memcpy(0xaf00b000, 0xb1789000, 4096)
08-31 15:25:27.980   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.980   312  7124 V AudioCache: memcpy(0xaf00c000, 0xb1789000, 4096)
08-31 15:25:27.981   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.981   312  7124 V AudioCache: memcpy(0xaf00d000, 0xb1789000, 4096)
08-31 15:25:27.981   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.981   312  7124 V AudioCache: memcpy(0xaf00e000, 0xb1789000, 4096)
08-31 15:25:27.982   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.982   312  7124 V AudioCache: memcpy(0xaf00f000, 0xb1789000, 4096)
08-31 15:25:27.983   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.983   312  7124 V AudioCache: memcpy(0xaf010000, 0xb1789000, 4096)
08-31 15:25:27.983   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.983   312  7124 V AudioCache: memcpy(0xaf011000, 0xb1789000, 4096)
08-31 15:25:27.984   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.984   312  7124 V AudioCache: memcpy(0xaf012000, 0xb1789000, 4096)
08-31 15:25:27.984   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.984   312  7124 V AudioCache: memcpy(0xaf013000, 0xb1789000, 4096)
08-31 15:25:27.984   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.985   312  7124 V AudioCache: memcpy(0xaf014000, 0xb1789000, 4096)
08-31 15:25:27.985   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.985   312  7124 V AudioCache: memcpy(0xaf015000, 0xb1789000, 4096)
08-31 15:25:27.986   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.986   312  7124 V AudioCache: memcpy(0xaf016000, 0xb1789000, 4096)
08-31 15:25:27.986   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.986   312  7124 V AudioCache: memcpy(0xaf017000, 0xb1789000, 4096)
08-31 15:25:27.987   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.987   312  7124 V AudioCache: memcpy(0xaf018000, 0xb1789000, 4096)
08-31 15:25:27.987   312  7124 V AudioCache: write(0xb1789000, 4096)
,08-31 15:25:27.987   312  7124 V AudioCache: memcpy(0xaf019000, 0xb1789000, 4096)
08-31 15:25:27.988   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.988   312  7124 V AudioCache: memcpy(0xaf01a000, 0xb1789000, 4096)
08-31 15:25:27.988   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.988   312  7124 V AudioCache: memcpy(0xaf01b000, 0xb1789000, 4096)
08-31 15:25:27.989   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.989   312  7124 V AudioCache: memcpy(0xaf01c000, 0xb1789000, 4096)
08-31 15:25:27.989   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.989   312  7124 V AudioCache: memcpy(0xaf01d000, 0xb1789000, 4096)
08-31 15:25:27.989   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.989   312  7124 V AudioCache: memcpy(0xaf01e000, 0xb1789000, 4096)
08-31 15:25:27.990   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.990   312  7124 V AudioCache: memcpy(0xaf01f000, 0xb1789000, 4096)
08-31 15:25:27.990   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.990   312  7124 V AudioCache: memcpy(0xaf020000, 0xb1789000, 4096)
08-31 15:25:27.991   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.991   312  7124 V AudioCache: memcpy(0xaf021000, 0xb1789000, 4096)
08-31 15:25:27.991   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.991   312  7124 V AudioCache: memcpy(0xaf022000, 0xb1789000, 4096)
08-31 15:25:27.992   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.992   312  7124 V AudioCache: memcpy(0xaf023000, 0xb1789000, 4096)
08-31 15:25:27.992   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.992   312  7124 V AudioCache: memcpy(0xaf024000, 0xb1789000, 4096)
08-31 15:25:27.993   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.993   312  7124 V AudioCache: memcpy(0xaf025000, 0xb1789000, 4096)
08-31 15:25:27.993   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.993   312  7124 V AudioCache: memcpy(0xaf026000, 0xb1789000, 4096)
08-31 15:25:27.993   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.994   312  7124 V AudioCache: memcpy(0xaf027000, 0xb1789000, 4096)
08-31 15:25:27.994   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.994   312  7124 V AudioCache: memcpy(0xaf028000, 0xb1789000, 4096)
08-31 15:25:27.994   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.994   312  7124 V AudioCache: memcpy(0xaf029000, 0xb1789000, 4096)
08-31 15:25:27.995   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.995   312  7124 V AudioCache: memcpy(0xaf02a000, 0xb1789000, 4096)
08-31 15:25:27.995   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.995   312  7124 V AudioCache: memcpy(0xaf02b000, 0xb1789000, 4096)
08-31 15:25:27.996   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.996   312  7124 V AudioCache: memcpy(0xaf02c000, 0xb1789000, 4096)
08-31 15:25:27.997   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.997   312  7124 V AudioCache: memcpy(0xaf02d000, 0xb1789000, 4096)
08-31 15:25:27.998   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.998   312  7124 V AudioCache: memcpy(0xaf02e000, 0xb1789000, 4096)
08-31 15:25:27.998   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.998   312  7124 V AudioCache: memcpy(0xaf02f000, 0xb1789000, 4096)
08-31 15:25:27.999   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.999   312  7124 V AudioCache: memcpy(0xaf030000, 0xb1789000, 4096)
08-31 15:25:27.999   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:27.999   312  7124 V AudioCache: memcpy(0xaf031000, 0xb1789000, 4096)
08-31 15:25:28.000  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 15:25:28.000   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:28.000   312  7124 V AudioCache: memcpy(0xaf032000, 0xb1789000, 4096)
08-31 15:25:28.000   312  7124 V AudioCache: write(0xb17890,00, 4096)
08-31 15:25:28.000   312  7124 V AudioCache: memcpy(0xaf033000, 0xb1789000, 4096)
08-31 15:25:28.001  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 15:25:28.001   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:28.001   312  7124 V AudioCache: memcpy(0xaf034000, 0xb1789000, 4096)
08-31 15:25:28.003  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4424
08-31 15:25:28.004   312  7124 V AudioCache: write(0xb1789000, 4096)
08-31 15:25:28.004   312  7124 V AudioCache: memcpy(0xaf035000, 0xb1789000, 4096)
08-31 15:25:28.004   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 15:25:28.004   312  7124 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 15:25:28.004   312  7124 V AwesomePlayer: postAudioEOS() 
08-31 15:25:28.004   312  7124 V AudioCache: write(0xb1789000, 280)
08-31 15:25:28.004   312  7124 V AudioCache: memcpy(0xaf036000, 0xb1789000, 280)
08-31 15:25:28.006   312  7121 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 15:25:28.006   312  7121 V AwesomePlayer: onStreamDone
08-31 15:25:28.006   312  7121 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 15:25:28.006   312  7121 V AudioCache: notify(0xb14322c0, 2, 0, 0)
08-31 15:25:28.006   312  7121 V AudioCache: playback complete
08-31 15:25:28.006   312  2136 V AudioCache: wait - success
08-31 15:25:28.006   312  7121 V AwesomePlayer: pause_l() 
08-31 15:25:28.006   312  2136 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 15:25:28.006   312  7121 V AudioCache: notify(0xb14322c0, 7, 0, 0)
08-31 15:25:28.006   312  7121 V AudioCache: ignored
08-31 15:25:28.006   312  7121 V AwesomePlayer: cancelPlayerEvents
08-31 15:25:28.006   312  7121 D AudioPlayer: Pause Playback at 1068125
08-31 15:25:28.008   312  2136 V AwesomePlayer: reset_l() 
08-31 15:25:28.008   312  2136 V AudioCache: notify(0xb14322c0, 8, 0, 0)
08-31 15:25:28.008   312  2136 V AudioCache: ignored
08-31 15:25:28.008   312  2136 V AwesomePlayer: cancelPlayerEvents
08-31 15:25:28.008   312  2136 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 15:25:28.008   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 15:25:28.008   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 15:25:28.008   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 15:25:28.008   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 15:25:28.009  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:25:28.009   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 15:25:28.009   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 15:25:28.009   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 15:25:28.010   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 15:25:28.010   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 15:25:28.010   312  7123 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 15:25:28.010   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-31 15:25:28.010   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,08-31 15:25:28.010   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 15:25:28.011   312  2136 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-31 15:25:28.011   312  2136 D AudioPlayer: AudioPlayer releasing audio source
08-31 15:25:28.011   312  2136 D AudioPlayer: AudioPlayer done releasing audio source
08-31 15:25:28.011   312  2136 V AwesomePlayer: reset_l() 
08-31 15:25:28.011   312  2136 V AwesomePlayer: cancelPlayerEvents
08-31 15:25:28.011   312  2136 V AwesomePlayer: ~AwesomePlayer call
08-31 15:25:28.011   312  2136 V AwesomePlayer: reset_l() 
,08-31 15:25:28.011   312  2136 V AwesomePlayer: cancelPlayerEvents
08-31 15:25:28.012  7022  7119 V SoundPool: close(31)
08-31 15:25:28.012  7022  7119 V SoundPool: pointer = 0x9fe6d000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 15:25:28.012  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:25:28.013  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:25:28.013  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:25:28.014  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:28.014  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 15:25:28.020  7042  7042 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-31 15:25:28.206  6832  6832 I UEI.SmartControl: Supports setup maps: true
,08-31 15:25:28.209  6832  6832 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 15:25:28.209  6832  6832 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 15:25:28.209  6832  6832 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 15:25:28.209  6832  6832 I UEI.SmartControl: ### init IR Blaster...
08-31 15:25:28.213  6832  6832 D serial_port: Configuring serial port
08-31 15:25:28.213  6832  6832 E UEI.SmartControl: UEIBLaster setting for 616
08-31 15:25:28.213  6832  6832 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 15:25:28.213  6832  6832 I UEI.SmartControl: configuring settings for MAXQ616
08-31 15:25:28.213  6832  6832 I UEI.SmartControl: Get version...
08-31 15:25:28.231  6832  7126 D UEI.SmartControl: serial port data available: 21
,08-31 15:25:28.258  6832  6832 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 15:25:28.258  6832  6832 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 15:25:28.258  6832  6832 I UEI.SmartControl: QS saving settings...
08-31 15:25:28.260  6832  6832 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 15:25:28.276  6832  7126 D UEI.SmartControl: serial port data available: 4
,08-31 15:25:28.309  6832  7132 I UEI.SmartControl: Device manager: loading config....
08-31 15:25:28.311  6832  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 15:25:28.313  6832  7132 D UEI.SmartControl: ----------- loading internal config...
,08-31 15:25:28.316  6832  6832 E UEI.SmartControl: Services init done
08-31 15:25:28.317  6832  6832 D UEI.SmartControl: QS Service init finished
08-31 15:25:28.319  6832  6832 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 15:25:28.319  6832  6832 D UEI.SmartControl: QS Service version code: 201091
08-31 15:25:28.320  6832  6832 D UEI.SmartControl: Service requested: Control
08-31 15:25:28.326  6832  6832 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 15:25:28.327  6832  7132 E UEI.SmartControl: Loading SETTINGS...
,08-31 15:25:28.333  7022  7022 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 15:25:28.334  6832  6832 D UEI.SmartControl: Internal service binding...
08-31 15:25:28.337  6832  6856 I UEI.SmartControl: ------ IControl API: 11
08-31 15:25:28.337  6832  6856 D UEI.SmartControl: File observer start...
08-31 15:25:28.339  6832  7132 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 15:25:28.341  6832  6856 E UEI.SmartControl: IR Port is disabled: false
08-31 15:25:28.341  6832  6856 D UEI.SmartControl: Starting file observer...
,08-31 15:25:28.354  6832  6856 I UEI.SmartControl: Registering callback...
08-31 15:25:28.358  6832  6850 I UEI.SmartControl: ------ IControl API: 19
08-31 15:25:28.359  6832  6850 I UEI.SmartControl: Registering Services Ready callback...
08-31 15:25:28.359  6832  6850 I UEI.SmartControl: Notify client services are ready...
08-31 15:25:28.359  7022  7041 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 15:25:28.360  7022  7117 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 15:25:28.360  7022  7117 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 15:25:28.361  7022  7022 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 15:25:28.361  7022  7022 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-31 15:25:28.361  6832  6856 I UEI.SmartControl: ------ IControl API: 8
08-31 15:25:28.363  7022  7022 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 15:25:28.364  7022  7022 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 15:25:28.364  7022  7022 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 15:25:28.364  7022  7022 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 15:25:28.365  7022  7022 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 15:25:28.366  7022  7022 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 15:25:28.368  7022  7022 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 15:25:28.370  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 15:25:28.371  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 15:25:28.371  6832  7131 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 15:25:28.371  7022  7022 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:25:28.372  7022  7041 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 15:25:28.372  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-31 15:25:28.372  7022  7117 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 15:25:28.372  7022  7117 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 15:25:28.373  6832  7131 D UEI.SmartControl: -----service ready thread exits
08-31 15:25:28.374  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 15:25:28.375  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 15:25:28.375  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 15:25:28.377  7022  7022 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472649928376]
08-31 15:25:28.379  7022  7022 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 15:25:28.380  7022  7022 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-31 15:25:28.383  1044  1927 I ActivityManager: Killing 6096:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-31 15:25:28.400  7022  7137 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 15:25:28.413  1044  1927 I ActivityManager: Killing 6580:com.lge.email/u0a23 (adj 15): empty #18
,08-31 15:25:28.458  1044  1999 W libprocessgroup: failed to open /acct/uid_10023/pid_6580/cgroup.procs: No such file or directory
,08-31 15:25:28.463  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-31 15:25:28.464  1044  2036 W libprocessgroup: failed to open /acct/uid_10027/pid_6096/cgroup.procs: No such file or directory
08-31 15:25:28.467  7022  7022 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:25:28.468  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 15:25:28.469  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 15:25:28.470  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 15:25:28.471  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-31 15:25:28.472  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 15:25:28.492  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 15:25:29.223  1044  1561 D WifiServiceImplEx: setWifiEnabled: true pid=6699, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 15:25:29.225  1044  1561 D WifiService: setWifiEnabled: true pid=6699, uid=10118
,08-31 15:25:29.225  1044  1561 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:25:29.256  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 15:25:29.258  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 15:25:29.258  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,08-31 15:25:29.260  1044  1425 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-31 15:25:29.260  1044  1425 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 15:25:29.262  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 15:25:29.262  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 15:25:29.263  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 15:25:29.263  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-31 15:25:29.263  1044  1425 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
08-31 15:25:29.263  1044  1425 E WifiHW  : unknown target_country: EU , set to default,
,08-31 15:25:29.263  1044  1425 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-31 15:25:29.263  1044  1425 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
,08-31 15:25:29.263  1044  1425 I WifiUtil: gEnableBmps=1
,08-31 15:25:29.333  1044  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:29.362  1044  1119 D Tethering: MasterInitialState.processMessage what=3
,08-31 15:25:29.385  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:29.389  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:29.391  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:29.393  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 15:25:29.396  6487  6518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 15:25:29.412  5810  5810 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 15:25:29.432  1044  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:29.447  1044  1119 D Tethering: MasterInitialState.processMessage what=3
,08-31 15:25:29.451  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:29.452  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:29.453  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:29.519  1044  1059 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7142 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-31 15:25:29.539  5810  5810 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 15:25:29.540  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:29.549  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:29.549  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 15:25:29.618  7142  7142 I AppUp4:AppBoxCP: onCreate
,08-31 15:25:29.618  7142  7142 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-31 15:25:29.629  7142  7142 I AppUp4:DB:  setFingerPrint start
,08-31 15:25:29.629  7142  7142 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 15:25:29.638  7142  7142 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 15:25:29.638  7142  7142 I AppUp4:DB:  SDK version = 21
08-31 15:25:29.638  7142  7142 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-31 15:25:29.641  7142  7142 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-31 15:25:29.642  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 15:25:29.642  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:29.645  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 15:25:29.645  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 15:25:29.656  7142  7142 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 15:25:29.719  7142  7142 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:25:29.719  7142  7142 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:25:29.731  7142  7142 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e0f8262
08-31 15:25:29.732  7142  7142 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:25:29.732  7142  7142 D AppUp4:CustFacade: isPhone : true
,08-31 15:25:29.733  7142  7142 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:25:29.734  7142  7142 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 15:25:29.735  7142  7142 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 15:25:29.737  7142  7176 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 15:25:29.738  7142  7176 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 15:25:29.738  7142  7176 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 15:25:29.742  1044  1764 I ActivityManager: Killing 6168:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-31 15:25:29.800  1044  1713 W libprocessgroup: failed to open /acct/uid_10080/pid_6168/cgroup.procs: No such file or directory
,08-31 15:25:29.800  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:29.801  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:25:29.809  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:29.815  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 15:25:29.833  4328  7186 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:25:29.835  4328  7190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:29.836  4328  7190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:25:29.879  1044  1059 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7191 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 15:25:29.928  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:29.929  1044  1119 D Tethering: InitialState.processMessage what=4
08-31 15:25:29.929  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:29.934   308   894 D SoftapController: Softap fwReload - Ok
08-31 15:25:29.936  1044  1425 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (667ms)
,08-31 15:25:29.939   308   894 D CommandListener: Setting iface cfg
08-31 15:25:29.939   308   894 D CommandListener: Trying to bring down wlan0
08-31 15:25:29.941   308   894 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:25:29.946  1044  1425 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 15:25:29.938  7209  7209 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:29.938  7209  7209 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:29.948  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:29.948  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:29.948  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-31 15:25:29.949  1044  1425 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 15:25:29.949  1044  1425 D WifiMonitor: connecting to supplicant
08-31 15:25:29.950  1044  1425 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
08-31 15:25:29.951  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:29.952  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 15:25:29.955  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:29.956  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 15:25:29.956  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:29.965  7191  7191 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:29.965  7191  7191 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:25:29.971  7191  7191 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 15:25:29.971  7191  7191 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 15:25:29.973  7209  7209 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 15:25:30.019  7209  7209 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 15:25:30.019  7209  7209 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-31 15:25:30.055  7191  7191 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 15:25:30.067  7191  7191 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 15:25:30.093  7209  7209 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 15:25:30.094  7191  7191 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 15:25:30.117  7191  7191 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:25:30.117  7191  7191 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:25:30.172  7209  7209 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 15:25:30.181  7209  7209 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 15:25:30.181  7209  7209 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-31 15:25:30.222  7191  7191 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 15:25:30.250  7191  7191 I HubEmail: JNI_OnLoad()
08-31 15:25:30.250  7191  7191 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 15:25:30.250  7191  7191 I HubEmail: registerNatives()
08-31 15:25:30.250  7191  7191 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 15:25:30.250  7191  7191 I HubEmail: registerNativeMethods()
08-31 15:25:30.250  7191  7191 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 15:25:30.250  7191  7191 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-31 15:25:30.252  3427  3427 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 15:25:30.252  3427  3427 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:30.252  3427  3427 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 15:25:30.311  1044  1713 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7228 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 15:25:30.325  7064  7222 W FormManager: Network not available. Please check & try again.
,08-31 15:25:30.326  7191  7224 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:30.327  7064  7223 V FormManager: Network unavailable.
08-31 15:25:30.337  7064  7223 V FormManager: Network unavailable.
,08-31 15:25:30.346  1044  1927 I ActivityManager: Killing 6628:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-31 15:25:30.396  1044  2018 W libprocessgroup: failed to open /acct/uid_10061/pid_6628/cgroup.procs: No such file or directory
08-31 15:25:30.498  7228  7228 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:25:30.498  7228  7228 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:25:30.502  7228  7228 D PhoneMonitor: Register our PhoneStateListener
,08-31 15:25:30.521  7228  7228 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 15:25:30.524  7228  7228 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 15:25:30.552  7228  7228 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-31 15:25:30.557  7228  7228 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-31 15:25:30.558  7228  7228 D TelephonyAutoProfiling: [parse] Load xml
08-31 15:25:30.562  7228  7228 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 15:25:30.562  7228  7228 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 15:25:30.563  7228  7228 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 15:25:30.572  7228  7228 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-31 15:25:30.587  1044  1059 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7247 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:25:30.588  1044  1059 I ActivityManager: Killing 6188:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-31 15:25:30.638  1044  1765 W libprocessgroup: failed to open /acct/uid_10097/pid_6188/cgroup.procs: No such file or directory
,08-31 15:25:30.753  7209  7209 E wpa_supplicant: USIM:  scard_init function
08-31 15:25:30.754  7209  7209 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 15:25:30.878  7209  7209 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 15:25:30.897  7209  7209 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:25:30.897  7209  7209 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:25:30.898  1044  1713 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7265 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-31 15:25:30.902  1044  1713 I ActivityManager: Killing 6764:com.lge.eula/1000 (adj 15): empty #17
08-31 15:25:30.953  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-31 15:25:30.953  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 15:25:30.954  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 15:25:30.954  1044  1425 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 15:25:30.955  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:30.955  1044  1425 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:30.956  1044  1425 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 15:25:30.956  1044  1425 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 15:25:30.957  1044  1425 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 15:25:30.957  1044  1425 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 15:25:30.957  1044  1425 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 15:25:30.961  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 15:25:30.961  1044  1764 W libprocessgroup: failed to open /acct/uid_1000/pid_6764/cgroup.procs: No such file or directory
08-31 15:25:30.964  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:30.964  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:30.964  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:25:30.969  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:30.969  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:30.970  1044  1425 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 15:25:30.970  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:30.970  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:30.970  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-31 15:25:30.972  1044  1425 D WifiNative-wlan0: SET update_config 1: returned true
08-31 15:25:30.972  1044  1425 D WifiConfigStore: Loading config and enabling all networks 
08-31 15:25:30.972  1044  1425 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 15:25:30.972  1044  1425 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-31 15:25:30.978  1928  1928 D WfdService: Waiting for WifiP2p enabling
08-31 15:25:30.978  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:30.980  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 15:25:30.981  1044  1455 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-31 15:25:30.983  1044  1425 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 15:25:30.983  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:30.983  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:30.983  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:30.983  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:30.985  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:30.985  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:30.985  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:30.985  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:30.995  1044  1425 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 15:25:30.995  1044  1425 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:25:30.996  1044  1425 D WifiStateMachine: enableVerboseLogging : level 2
08-31 15:25:30.996  1044  1425 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 15:25:30.996  1044  1425 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 15:25:30.996  1044  1425 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-31 15:25:30.997  1044  1425 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 15:25:30.997  1044  1425 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 15:25:30.997  1044  1425 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 15:25:30.997  1044  1425 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 15:25:30.998  1044  1425 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 15:25:30.998  1044  1425 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 15:25:30.998  1044  1425 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 15:25:30.998  1044  1425 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 15:25:30.999  1044  1425 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 15:25:30.999  1044  1425 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 15:25:31.000  1044  1425 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 15:25:31.000  1044  1425 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:25:31.000  1044  1425 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 15:25:31.001  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-31 15:25:31.001  1928  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 15:25:31.001  1928  2299 D WfdsService: Set the WFDS Monitor: true
08-31 15:25:31.001  1928  2299 D WfdsMonitor: WfdsMonitorThread create
08-31 15:25:31.001  1928  2299 D WfdsMonitor: WFDS Monitor is created and started
08-31 15:25:31.001  1928  2299 D WfdsService: WiFi: Supplicant connection re-established
08-31 15:25:31.001  1044  1425 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 15:25:31.001  1044  1425 D WifiNative-HAL: Setting external_sim to 1
08-31 15:25:31.001  1044  1425 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 15:25:31.002  1044  1425 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 15:25:31.002  1044  1425 I WifiNative-HAL: startHal
08-31 15:25:31.002  1044  1425 D wifi    : setting scan oui 0xaf664220
08-31 15:25:31.002  1044  1425 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:25:31.002  1044  1425 I WifiNative-HAL: startHal
08-31 15:25:31.002  1044  1425 D wifi    : setting scan oui 0xaf664220
08-31 15:25:31.003  1928  7283 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 15:25:31.003  1044  1425 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 15:25:31.004  1044  1425 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 15:25:31.004  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 15:25:31.004  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 15:25:31.004  1044  1425 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 15:25:31.005  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:25:31.005  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 15:25:31.005  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:25:31.005  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 15:25:31.005  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 15:25:31.006  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 15:25:31.006  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:25:31.006  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:25:31.007  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:25:31.007  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:25:31.007  1928  7283 E CtrlSupplicant: Succeed to open control connection
08-31 15:25:31.007  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 15:25:31.007  1928  7283 E CtrlSupplicant: Succeed to open monitor connection
,08-31 15:25:31.007  1928  7283 D WfdsMonitor: Supplicant connection established
08-31 15:25:31.007  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:25:31.007  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 15:25:31.007  1928  2299 D WfdsService: Connected to the supplicant for wfds
,08-31 15:25:31.008  7209  7209 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 15:25:31.008  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 15:25:31.008  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:25:31.008  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:25:31.009  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:25:31.010  1044  1425 E WifiNative: : [128,155,462 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 15:25:31.010  1044  1425 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 15:25:31.010  1044  1425 D WifiNative-wlan0: RECONNECT: returned true
08-31 15:25:31.010  1044  1425 D WifiNative-wlan0: doString: [STATUS]
08-31 15:25:31.011  1044  7282 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:25:31.011  1044  7282 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:25:31.011  1044  1425 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 15:25:31.011  1044  1425 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:25:31.011  1044  1425 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:25:31.012  1044  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.014   308   894 D CommandListener: Setting iface cfg
08-31 15:25:31.014   308   894 D CommandListener: Trying to bring up p2p0
08-31 15:25:31.014  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 15:25:31.014  1044  1375 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 15:25:31.014  1044  1044 D RttService: SCAN_AVAILABLE : 3
08-31 15:25:31.014  1044  1375 D LGWifiP2pService: P2pEnablingState
08-31 15:25:31.015  1044  1375 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.015  1044  1375 D LGWifiP2pService: P2p socket connection successful
08-31 15:25:31.015  1044  1375 D LGWifiP2pService: P2pEnabledState
08-31 15:25:31.015  1044  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.015  1044  1542 I WifiNative-HAL: startHal
08-31 15:25:31.015  1044  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf664220
08-31 15:25:31.015  1044  1542 D wifi    : failed to get capabilities : -3
08-31 15:25:31.015  1044  1425 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 15:25:31.015  1044  1542 E WifiScanningService: could not get scan capabilities
08-31 15:25:31.015  1044  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.015  1044  1425 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 15:25:31.016  1044  1425 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 15:25:31.016  1044  1425 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 15:25:31.017  1044  1425 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:31.017  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 15:25:31.017  1928  1928 D WfdsService: WifiP2pState is changed : true
08-31 15:25:31.017  1044  1425 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:31.017  1928  2299 D WfdsService: Receive the WFDS_ENABLE Method
08-31 15:25:31.017  1928  2299 D WfdsService: Set the WFDS Monitor: true
08-31 15:25:31.017  1928  2299 D WfdsService: Connected to the supplicant for wfds
08-31 15:25:,31.017  1928  2299 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 15:25:31.018  7209  7209 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 15:25:31.018  1928  2299 D WfdsService: selectPreferredScanChannel [36]
08-31 15:25:31.018  1928  2299 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 15:25:31.018  1044  1425 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:31.019  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:31.019  1044  1425 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:31.020  1044  1425 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 15:25:31.020  1044  1425 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 15:25:31.020  1044  1425 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 15:25:31.020  1044  1425 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 15:25:31.021  7209  7209 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 15:25:31.021  1044  1375 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 15:25:31.021  1044  1425 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 15:25:31.021  1044  1375 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 15:25:31.022  1044  1375 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 15:25:31.022  1044  1375 D WifiNative-p2p0: doBoolean: SET device_name G3
,08-31 15:25:31.022  1044  1375 D WifiNative-p2p0: SET device_name G3: returned true
08-31 15:25:31.022  1044  1375 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 15:25:31.022  1044  1375 D LGWifiP2pService: before postfix = G3
08-31 15:25:31.022  1044  1375 D WifiServerServiceExt: postfix byte check : 2
08-31 15:25:31.023  1044  1375 D LGWifiP2pService: after postfix = G3
,08-31 15:25:31.023  1044  1375 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 15:25:31.023  1044  1375 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 15:25:31.023  1044  1375 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 15:25:31.023  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,08-31 15:25:31.023  1044  1375 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 15:25:31.023  1044  1375 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-31 15:25:31.024  1044  1375 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 15:25:31.024  1044  1375 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 15:25:31.024  1928  1928 D WfdsService: isConnected: false
08-31 15:25:31.024  1044  1375 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-31 15:25:31.024  1044  1375 D WifiNative-HAL: p2pGetDeviceAddress
08-31 15:25:31.024  1044  1375 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 15:25:31.025  1044  1375 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 15:25:31.025  1044  1375 D WifiNative-p2p0: doBoolean: P2P_FLUSH,
08-31 15:25:31.025  1044  1425 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 15:25:31.026  1044  1425 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 15:25:31.026  1044  1425 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 15:25:31.026  7209  7209 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-31 15:25:31.026  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 15:25:31.027  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 15:25:31.027  1044  1375 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 15:25:31.027  1044  1375 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-31 15:25:31.027  1044  1375 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 15:25:31.027  1044  1375 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 15:25:31.028  1044  1425 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 15:25:31.028  1928  1928 D WfdsService: Update P2p Interface State: 3
08-31 15:25:31.028  1044  1425 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz,
08-31 15:25:31.029  1044  1425 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 15:25:31.029  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 15:25:31.029  1044  1375 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 15:25:31.029  1044  1375 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-31 15:25:31.052  1044  1375 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 15:25:31.052  1044  1375 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-31 15:25:31.056  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:25:31.056  7209  7209 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:31.056  1044  7282 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:25:31.056  1044  7282 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:31.057  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:31.057  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-31 15:25:31.057  7209  7209 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:25:31.057  7209  7209 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.058  1044  7282 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.058  7209  7209 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.058  1044  7282 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.058  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.058  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.058  1044  7282 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.058  1044  7282 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.058  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.059  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.059  1044  1425 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 15:25:31.059  1044  1425 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:25:31.060  1044  1425 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:25:31.060  1044  1425 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:25:31.060  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 15:25:31.060  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 15:25:31.060  1928  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.060  7209  7209 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:31.060  1928  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.061  1044  7282 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 15:25:31.061  1044  7282 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:31.061  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:31.061  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:31.061  1044  1425 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 15:25:31.061  1044  1425 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 15:25:31.062  1044  1425 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 15:25:31.062  1044  1425 D WifiNative-wlan0: doBoolean: SCAN
08-31 15:25:31.063  7209  7209 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 15:25:31.063  1044  7282 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 15:25:31.063  1044  7282 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 15:25:31.063  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 15:25:31.063  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 15:25:31.063  1044  1425 D WifiNative-wlan0: SCAN: returned true
08-31 15:25:31.065  1044  1425 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=128211  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-31 15:25:31.082  1044  1060 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7288 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:25:31.083  1044  1060 I ActivityManager: Killing 6785:com.lge.bnr/1000 (adj 15): empty #17
,08-31 15:25:31.101   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 19.803ms
,08-31 15:25:31.120   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 17.863ms
,08-31 15:25:31.138   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 340us total 17.162ms
,08-31 15:25:31.149  1044  1375 D LGWifiP2pService: InactiveState
08-31 15:25:31.150  1044  1375 D LGWifiP2pService: InactiveState{ when=-123ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.150  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-123ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.150  1044  1375 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 15:25:31.150  7209  7209 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:25:31.151  7209  7209 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:31.151  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=128297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:25:31.151  1044  7282 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:25:31.151  1044  7282 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:31.151  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:31.151  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:31.151  1928  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:25:31.151  7209  7209 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:25:31.151  7209  7209 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.151  1928  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.151  1044  7282 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.152  1044  7282 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.152  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.152  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.152  7209  7209 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.152  1044  1425 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:31.153  1044  1375 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: InactiveState{ when=-94ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-94ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.153  1044  1425 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:31.153  1044  1375 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.154 , 1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.154  1044  1375 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.154  1044  1375 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.154  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.154  1044  1375 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.154  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:31.154  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:31.154  1044  1425 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:31.155  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:31.155  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:31.155  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 15:25:31.155  1044  1044 E WifiServerServiceExt: No p2p device connected
08-31 15:25:31.155  1928  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.155  1928  2299 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 15:25:31.155  1044  7282 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:31.155  1044  7282 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.155  1044  7282 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.155  1044  7282 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:31.156  1044  1425 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:31.158  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:31.157  1044  1425 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-31 15:25:31.163  1044  1999 W libprocessgroup: failed to open /acct/uid_1000/pid_6785/cgroup.procs: No such file or directory
,08-31 15:25:31.168  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:31.168  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 15:25:31.187  7288  7288 I art     : Almond Protected OAT
,08-31 15:25:31.236  7288  7288 D WeatherApplication: removeAccount
,08-31 15:25:31.239  7288  7288 D WeatherApplication: Account.length = 0
,08-31 15:25:31.239  7288  7288 E WeatherApplication: OPERATOR:OPEN
08-31 15:25:31.244  7288  7288 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:25:31
08-31 15:25:31.249  7288  7288 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 15:25:31.249  7288  7288 D Weather.Utils: 2 : All the weather widget is gone.
,08-31 15:25:31.254  7288  7288 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 15:25:31.258  7288  7288 D WeatherAncestor: connectivity changed - connection : true
08-31 15:25:31.259  7288  7288 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-31 15:25:31.272  7288  7288 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 15:25:31.273  7288  7288 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 15:25:31.273  7288  7288 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-31 15:25:31.278  1044  1375 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.278  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.279  1044  1375 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:31.302  7288  7288 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 15:25:31.302  7288  7288 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:25:31
,08-31 15:25:31.338  1044  1425 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 15:25:31.338  1044  1425 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:25:31.338  1044  1425 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:25:31.339  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:25:31.339  1044  1425 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 15:25:31.369  1044  1963 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7312 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 15:25:31.371  1044  1963 I ActivityManager: Killing 2112:com.lge.music/u0a34 (adj 15): empty #17
08-31 15:25:31.400   312  1381 V AudioFlinger: 2112 died, releasing its sessions
08-31 15:25:31.400   312  1381 V AudioFlinger:  pid 1839 @ 0
08-31 15:25:31.400   312  1381 V AudioFlinger:  pid 3427 @ 1
08-31 15:25:31.400   312  1381 V AudioFlinger:  pid 3427 @ 2
,08-31 15:25:31.428  1044  1713 W libprocessgroup: failed to open /acct/uid_10034/pid_2112/cgroup.procs: No such file or directory
,08-31 15:25:31.538   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 15:25:31.538   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 15:25:31.538   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:31.541  7312  7330 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 15:25:31.544   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 15:25:31.544   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 15:25:31.544   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 15:25:31.544  7312  7330 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 15:25:31.565   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 15:25:31.565   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 15:25:31.565   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 15:25:31.567  7312  7332 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-31 15:25:31.574   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 15:25:31.574   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 15:25:31.574   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 15:25:31.575  7312  7332 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 15:25:31.825  7312  7312 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 15:25:31.857  7312  7312 I LibraryLoader: Loading: webviewchromium
,08-31 15:25:31.862  7312  7312 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 9017-9025)
,08-31 15:25:31.862  7312  7312 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:25:31.872  7312  7312 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eafd33f}
,08-31 15:25:31.878  7312  7312 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:25:31.880  7312  7312 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 15:25:31.897  7312  7312 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 15:25:31.898  7312  7312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 15:25:31.911  7312  7312 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-31 15:25:31.912  7312  7312 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-31 15:25:31.916  7312  7312 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-31 15:25:31.919   312  2137 V AudioPolicyService: registerClient() client 0xb100b580, uid 10093
08-31 15:25:31.920  7312  7357 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 15:25:31.934  7312  7312 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:25:31.934  7312  7312 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:25:31.934  7312  7312 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:25:31.934  7312  7312 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:25:31.934  7312  7312 I Adreno-EGL: Remote Branch: 
08-31 15:25:31.934  7312  7312 I Adreno-EGL: Local Patches: 
08-31 15:25:31.934  7312  7312 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:25:32.028  7312  7312 I NSApplication: Starting up...
,08-31 15:25:32.119  1044  1963 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7370 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 15:25:32.124  1044  1963 I ActivityManager: Killing 6117:com.android.vending/u0a44 (adj 15): empty #17
08-31 15:25:32.188  1044  1927 W libprocessgroup: failed to open /acct/uid_10044/pid_6117/cgroup.procs: No such file or directory
,08-31 15:25:32.218  7370  7370 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 15:25:32.262  1044  1947 D WifiServiceImplEx: setWifiEnabled: false pid=6699, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:25:32.262  1044  1947 D WifiService: setWifiEnabled: false pid=6699, uid=10118
08-31 15:25:32.262  1044  1947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:25:32.280  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:25:32.281  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:25:32.281  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-31 15:25:32.282  1044  1425 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:32.282  1044  1425 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:32.283  1044  1425 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:32.283  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:25:32.290  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 15:25:32.290  1044  1044 D RttService: SCAN_AVAILABLE : 1
,08-31 15:25:32.293  1044  1542 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:32.293  1044  1543 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:32.294  1044  1375 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:32.294  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:32.294  1044  1375 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@13de05d0
08-31 15:25:32.295  1044  1375 D LGWifiP2pService: P2pDisablingState
08-31 15:25:32.295  1044  1375 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:32.295  1044  1375 D LGWifiP2pService: p2p socket connection lost
08-31 15:25:32.295  1044  1375 D LGWifiP2pService: P2pDisabledState
08-31 15:25:32.297  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:25:32.297  1928  1928 D WfdsService: WifiP2pState is changed : false
08-31 15:25:32.298  1928  2299 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 15:25:32.298  1928  2299 D WfdsService: Set the WFDS Monitor: false
08-31 15:25:32.299  1928  2299 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:25:32.299  1928  2299 D WfdsService: STATE : WfdsDisabledState - enter
08-31 15:25:32.299  1928  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 15:25:32.300  1928  7283 D CtrlSupplicant: Received on exit socket, terminate
08-31 15:25:32.300  1928  7283 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 15:25:32.300  1928  7283 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 15:25:32.300  1928  7283 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 15:25:32.300  1928  2299 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 15:25:32.303  1044  1425 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 15:25:32.303   308   894 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:25:32.310  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-31 15:25:32.310  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:32.310  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:32.310  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:25:32.311  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 15:25:32.311  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:32.313  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:32.318  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-31 15:25:32.318  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:32.318  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:32.318  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:25:32.319  1044  1425 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 15:25:32.319  1044  1425 D WifiNative-p2p0: TERMINATE: returned true
08-31 15:25:32.320  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:32.320  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:32.320  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:25:32.322  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 15:25:32.328  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 15:25:32.329  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:32.329  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:32.329  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:32.329  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:32.329  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:32.330  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:32.333  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 15:25:32.333  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:32.337  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:32.337  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:32.337  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:32.337  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:32.338  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:32.340  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:32.389  7209  7209 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 15:25:32.389  7209  7209 I wpa_supplicant: monitor socket send errors count : 1
08-31 15:25:32.389  7209  7209 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-4\x00 that cannot receive messages
,08-31 15:25:32.392  1044  7282 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 15:25:32.392  1044  7282 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 15:25:32.418  7209  7209 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 15:25:32.419  1044  7282 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-31 15:25:32.419  1044  7282 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:25:32.419  1044  7282 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:25:32.419  1044  7282 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 15:25:32.420  1044  1425 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=129566
08-31 15:25:32.420  1044  1425 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=129566
08-31 15:25:32.422  7209  7209 W wpa_supplicant: USIM:  scard_deinit function
08-31 15:25:32.422  1044  7282 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:25:32.422  1044  7282 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:25:32.423  1044  1425 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=129569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:25:32.423  1044  1425 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=129569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:25:32.423  1044  1119 D Tethering: InitialState.processMessage what=4
08-31 15:25:32.426  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:32.426  1044  1425 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:32.427  1044  1425 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 15:25:32.489  7209  7209 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 15:25:32.492  1044  7282 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 15:25:32.492  1044  7282 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 15:25:32.492  1044  7282 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 15:25:32.493  1044  1425 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
,08-31 15:25:32.514  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 15:25:32.518  6487  6518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 15:25:32.542  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:32.552  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 15:25:32.552  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:32.552  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 15:25:32.552  7142  7142 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 15:25:32.554  7142  7142 I AppUp4:CustModeStarterReceiver: onReceive
08-31 15:25:32.558  7142  7142 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e0f8262
08-31 15:25:32.558  7142  7142 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:25:32.558  7142  7142 D AppUp4:CustFacade: isPhone : true
08-31 15:25:32.558  7142  7142 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:25:32.559  7142  7142 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 15:25:32.563  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:32.564  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:25:32.567  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:32.571  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:32.575  4328  7412 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:25:32.577  4328  7413 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:32.577  4328  7413 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:25:32.585  7191  7191 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 15:25:32.596  1044  1425 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 15:25:32.596  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:32.596  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:32.596  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:25:32.596  1928  1928 D WfdsService: Supplicant Connection state is changed : false
,08-31 15:25:32.596  1928  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-31 15:25:32.596  1928  2299 D WfdsService: Set the WFDS Monitor: false
08-31 15:25:32.596  1928  2299 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:25:32.598  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:25:32.599  2456  2456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:32.600  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:32.602  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:32.603  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:32.604  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 15:25:32.605  1044  1455 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 15:25:32.605  1044  1455 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 15:25:32.605  7191  7414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:32.614  3427  3427 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-31 15:25:32.614  3427  3427 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:32.614  3427  3427 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 15:25:32.617  7228  7228 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 15:25:32.617  7228  7228 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 15:25:32.629  7064  7417 V FormManager: Network unavailable.
,08-31 15:25:32.632  7288  7288 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:25:32
08-31 15:25:32.633  7064  7417 V FormManager: Network unavailable.
08-31 15:25:32.635  7064  7416 W FormManager: Network not available. Please check & try again.
08-31 15:25:32.636  7288  7288 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 15:25:32.636  7288  7288 D Weather.Utils: 2 : All the weather widget is gone.
08-31 15:25:32.638  7288  7288 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 15:25:32.639  7288  7288 D WeatherAncestor: connectivity changed - connection : true
08-31 15:25:32.639  7288  7288 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@32ab84b0
,08-31 15:25:32.640  7288  7288 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 15:25:32.640  7288  7288 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 15:25:32.640  7288  7288 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 15:25:32.640  7288  7288 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 15:25:32.640  7288  7288 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:25:32
08-31 15:25:32.663  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:32.663  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:25:32.663  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:25:32.663  6955  6955 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:25:32.663  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:25:32.664  6955  6955 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:25:32.664  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:25:32.664  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:25:32.664  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:25:32.664  6955  6955 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:25:32.664  6955  6955 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 15:25:32.671  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:32.674  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:32.680  7064  7420 W FormManager: Network not available. Please check & try again.
08-31 15:25:32.681  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:32.687  7064  7421 V FormManager: Network unavailable.
08-31 15:25:32.696  7064  7421 V FormManager: Network unavailable.
,08-31 15:25:32.699  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:32.703  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:32.707  7064  7422 W FormManager: Network not available. Please check & try again.
,08-31 15:25:32.710  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:32.718  7064  7423 V FormManager: Network unavailable.
08-31 15:25:32.723  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:32.723  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 15:25:32.725  7064  7423 V FormManager: Network unavailable.
08-31 15:25:32.725  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:32.726  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:32.732  4328  7424 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 15:25:32.735  4328  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:32.736  4328  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 15:25:32.737  1044  1060 I art     : Explicit concurrent mark sweep GC freed 84619(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 3.139ms total 166.981ms
08-31 15:25:32.773  1044  1765 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7427 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 15:25:32.916  7427  7427 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 15:25:32.916  7427  7427 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 15:25:32.926  7427  7427 V [BNRBootReceiver]: Boot Receiver Return
08-31 15:25:32.930  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:25:32.934  7427  7427 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 15:25:32.941  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:32.949  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:32.967  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:32.968  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:32.969  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:25:32.977  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:32.986  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:25:32.986  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-31 15:25:32.986  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:25:32.998  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:33.009  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:33.024  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:33.025  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:25:33.029  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:25:33.039  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:25:33.051  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 15:25:33.051  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:25:33.051  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:33.059  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:33.072  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:33.087  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:33.088  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:25:33.095  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:25:33.119  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:25:33.124  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:33.134  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:33.141  7064  7450 W FormManager: Network not available. Please check & try again.
08-31 15:25:33.143  7064  7451 V FormManager: Network unavailable.
08-31 15:25:33.146  7064  7451 V FormManager: Network unavailable.
,08-31 15:25:33.154  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:33.154  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:25:33.155  1044  1561 I ActivityManager: Killing 6975:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-31 15:25:33.158  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:33.190  1044  2036 W libprocessgroup: failed to open /acct/uid_10037/pid_6975/cgroup.procs: No such file or directory
,08-31 15:25:33.192  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:33.201  4328  7452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 15:25:33.208  4328  7453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:33.209  4328  7453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:25:33.209  6994  6994 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 15:25:33.209  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:25:33.209  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:25:33.218  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:33.228  7064  7455 W FormManager: Network not available. Please check & try again.
08-31 15:25:33.230  7064  7456 V FormManager: Network unavailable.
08-31 15:25:33.231  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:33.237  7064  7456 V FormManager: Network unavailable.
,08-31 15:25:33.310  6832  7133 D UEI.SmartControl: Internal timer expired: 2
08-31 15:25:33.310  6832  7133 D UEI.SmartControl: unbind internal service
,08-31 15:25:33.408  6832  7127 D serial_port: close(fd = 24)
,08-31 15:25:33.415  6832  7127 I UEI.SmartControl: Serial port is closed.
,08-31 15:25:35.294  1044  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:25:35.294  1044  1713 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 15:25:35.324  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:25:35.324  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:25:35.324  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-31 15:25:35.325  1044  1119 D BluetoothManagerService: Message: 1
08-31 15:25:35.325  1044  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 15:25:35.352  1044  1119 D BluetoothManagerService: Message: 20
08-31 15:25:35.352  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c3a4da5:true
,08-31 15:25:35.356  7093  7093 D BluetoothAdapterState: make
08-31 15:25:35.361  7093  7093 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 15:25:35.361  7093  7093 I bluedroid-qcom: init
08-31 15:25:35.363  7093  7464 I BluetoothAdapterState: Entering OffState
08-31 15:25:35.363  7093  7093 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 15:25:35.363  7093  7093 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 15:25:35.364  7093  7093 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:25:35.364  7093  7093 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 15:25:35.364  7093  7093 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 15:25:35.366  7093  7093 I bluedroid-qcom: get_profile_interface socket
08-31 15:25:35.366  7093  7093 I bluedroid-qcom: get_profile_interface map_client
,08-31 15:25:35.370  7093  7468 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 15:25:35.372  7093  7468 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 15:25:35.358  7467  7467 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:35.358  7467  7467 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:35.383  7467  7467 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 15:25:35.383  7467  7467 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 15:25:35.383  7467  7467 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 15:25:35.387  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 15:25:35.388  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 15:25:35.390  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 15:25:35.390  1044  1119 D BluetoothManagerService: Message: 40
08-31 15:25:35.390  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 15:25:35.391  7093  7110 I bluedroid-qcom: config_hci_snoop_log
08-31 15:25:35.392  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 15:25:35.392  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 15:25:35.394  7467  7467 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 15:25:35.400  7093  7464 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-31 15:25:35.404  7467  7467 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 15:25:35.404  7467  7467 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 15:25:35.405  7093  7468 D BluetoothAdapterProperties: Name is: G3
08-31 15:25:35.406  7093  7464 D BluetoothAdapterProperties: Setting state to 11
08-31 15:25:35.406  7093  7464 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 15:25:35.407  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:35.407  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 15:25:35.407  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 15:25:35.409  7093  7464 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 15:25:35.420  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:35.423  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:35.425  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:35.426  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:35.429  6955  6955 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 15:25:35.438  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:25:35.438  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:35.439  7093  7093 V BluetoothPbapReceiver: ***********state = 11
,08-31 15:25:35.445  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:35.461  7093  7464 D BluetoothBondStateMachine: make
,08-31 15:25:35.478  7093  7464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.478  7093  7464 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,08-31 15:25:35.479  7093  7464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.479  7093  7464 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-31 15:25:35.480  7093  7464 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 15:25:35.482  7093  7469 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 15:25:35.495  7093  7464 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:25:35.505  1044  1908 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7485 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 15:25:35.511  7093  7464 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:25:35.513  7093  7093 D HeadsetService: Received start request. Starting profile...
08-31 15:25:35.514  7093  7093 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:25:35.514  7093  7093 D LGBluetoothHfpAdapter: Version 1.6
08-31 15:25:35.516  7093  7464 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:35.518  7093  7093 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 15:25:35.519  7093  7093 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:25:35.520  7093  7093 D HeadsetStateMachine: make
08-31 15:25:35.522  7093  7464 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:35.530  7093  7464 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:25:35.535  7093  7464 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:25:35.554  7093  7464 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:35.564  7093  7093 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:25:35.564  7093  7093 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:25:35.570  7093  7093 D HeadsetStateMachine: max_hf_connections = 1
08-31 15:25:35.570  7093  7093 I bluedroid-qcom: get_profile_interface handsfree
08-31 15:25:35.571  7093  7464 V LGMDMManager: Create singleton instance
08-31 15:25:35.572  7093  7093 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 15:25:35.572   312  2136 V AudioPolicyService: registerClient() client 0xb100b420, uid 1002
08-31 15:25:35.573   312  1381 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-31 15:25:35.573   312  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:25:35.573   312  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:25:35.573  7093  7093 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 15:25:35.573   312  2137 V AudioFlinger: registerClient() client 0xb55815f8, pid 7093
08-31 15:25:35.573  7093  7464 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 15:25:35.573   312  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:35.573   312  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:35.574  1589  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:35.574  1589  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:35.574  7093  7093 V ToneGenerator: Create Track: 0xb4928080
08-31 15:25:35.574  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:35.574  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:35.574  7093  7110 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:35.574  7093  7093 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 15:25:35.574  7093  7110 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 15:25:35.574  7093  7093 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 15:25:35.574  3427  3444 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:35.574  3427  3444 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:35.574   312  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:35.574   312  2136 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:25:35.574   312  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:35.574   312  2136 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 15:25:35.574   312  2136 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:25:35.574   312  2136 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:25:35.574  3427  4900 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:35.574  3427  4900 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:35.574  1589  4474 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:35.574  1589  4474 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:35.574  7093  7109 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:35.574  1839  2575 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:35.574  1839  2575 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:35.574  7093  7109 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 15:25:35.574  1044  1713 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:35.574  1044  1713 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:35.574  1044  1713 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:35.574  1044  1713 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:35.574   312  1381 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 15:25:35.575   312  2137 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:25:35.575   312  2137 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 15:25:35.575   312  2137 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:25:35.575   312  ,2137 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:25:35.575  7093  7093 V AudioSystem: getLatency() output 2, latency 50
08-31 15:25:35.575  7093  7093 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 15:25:35.575  7093  7093 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 15:25:35.575   312  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:25:35.575   312  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:25:35.575   312  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:25:35.575   312  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:25:35.575   312  1382 V AudioFlinger: createTrack() lSessionId: 22
08-31 15:25:35.576  7093  7093 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 15:25:35.577   312  1382 V AudioFlinger: acquiring 22 from 7093, for 7093
08-31 15:25:35.577   312  1382 V AudioFlinger:  added new entry for 22
08-31 15:25:35.577  7093  7093 V ToneGenerator: ToneGenerator INIT OK, time: 132740
08-31 15:25:35.577  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.578  7093  7500 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 15:25:35.578  7093  7500 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:25:35.578  7093  7500 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:25:35.578  7093  7500 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 15:25:35.578  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.579   312   312 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7093
08-31 15:25:35.579   312   312 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 15:25:35.579   312   312 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 15:25:35.579   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 15:25:35.579   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 15:25:35.579   312   312 V voice   : voice_set_parameters: exit with code(0)
08-31 15:25:35.579   312   312 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 15:25:35.579   312   312 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 15:25:35.579   312   312 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 15:25:35.579   312   312 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 15:25:35.579   312   312 V audio_hw_primary: adev_set_parameters: exit with code(0)
,08-31 15:25:35.579   312   312 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 15:25:35.579  7093  7500 V ToneGenerator: ToneGenerator destructor
08-31 15:25:35.580  7093  7500 V ToneGenerator: stopTone
08-31 15:25:35.580  7093  7500 V ToneGenerator: Delete Track: 0xb4928080
08-31 15:25:35.580  7093  7500 V AudioTrack: ~AudioTrack, releasing session id from 7093 on behalf of 7093
08-31 15:25:35.580  7093  7093 D A2dpService: Received start request. Starting profile...
08-31 15:25:35.581   312  2136 V AudioFlinger: releasing 22 from 7093 for 7093
08-31 15:25:35.581   312  2136 V AudioFlinger:  decremented refcount to 0
08-31 15:25:35.581   312  2136 V AudioFlinger: purging stale effects
,08-31 15:25:35.581   312  2136 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 15:25:35.581   312  2136 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 15:25:35.581   312  2136 V AudioFlinger: PlaybackThread::Track destructor
08-31 15:25:35.581   312  1272 V AudioPolicyService: AudioCommandThread() waking up
08-31 15:25:35.581   312  2136 V AudioFlinger: removeClient_l() pid 7093, calling pid 312
08-31 15:25:35.581   312  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 15:25:35.581   312  1272 V AudioPolicyManager: releaseOutput() 2
,08-31 15:25:35.581   312  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 15:25:35.581  7093  7093 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 15:25:35.582  7093  7093 V Avrcp   : make
08-31 15:25:35.583  7093  7093 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 15:25:35.583  7093  7093 I bluedroid-qcom: get_profile_interface avrcp
,08-31 15:25:35.584  1044  1713 W Process : Unable to open /proc/7505/status
08-31 15:25:35.591  7093  7093 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 15:25:35.592  7093  7093 E AudioManager: No RCC entry present to update
,08-31 15:25:35.593  7093  7093 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 15:25:35.596  7093  7093 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 15:25:35.597  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 15:25:35.597  7093  7093 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 15:25:35.600  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 15:25:35.647  7485  7485 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-31 15:25:35.647  7485  7485 W LG Account v2.2: No ProfileInfo entries
08-31 15:25:35.648  7485  7485 I LG Account v2.2: isEnabled: false
08-31 15:25:35.648  7485  7485 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 15:25:35.648  7485  7485 I Feature : [Lifetracker]Country: EU
08-31 15:25:35.649  7485  7485 I Feature : [Lifetracker]Operator: OPEN
08-31 15:25:35.649  7485  7485 I Feature : [Lifetracker]Ranking support: false
08-31 15:25:35.649  7485  7485 I Feature : [Lifetracker]Comfort support: false
08-31 15:25:35.649  7485  7485 I Feature : [Lifetracker]Accessory: true
08-31 15:25:35.649  7485  7485 I Feature : [Lifetracker]Health device: true
08-31 15:25:35.650  7485  7485 I Feature : [Lifetracker]Extra Pedometer: false
08-31 15:25:35.650  7485  7485 I Feature : [Lifetracker]Blood glucose device: false
08-31 15:25:35.650  7485  7485 I Feature : [Lifetracker]Device Number: 3
08-31 15:25:35.675  6955  6955 D BluetoothPermissionRequest: onReceive
,08-31 15:25:35.684  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:25:35.749  1044  2018 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:25:35.749  1044  2018 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:25:35.876  1044  1927 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 15:25:35.893  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-31 15:25:35.899  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 15:25:35.900  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:25:35.901  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-31 15:25:35.901  7093  7093 I BluetoothA2dpServiceJni: classInitNative
08-31 15:25:35.901  7093  7093 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:25:35.901  7093  7093 D A2dpStateMachine: make
08-31 15:25:35.903  7093  7093 I bluedroid-qcom: get_profile_interface a2dp
08-31 15:25:35.903  7093  7516 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 15:25:35.905  7093  7093 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:25:35.905  7093  7093 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 15:25:35.907  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.908  7093  7093 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 15:25:35.910  7093  7515 D A2dpStateMachine: Enter Disconnected: -2
,08-31 15:25:35.910  7093  7093 D HidService: Received start request. Starting profile...
,08-31 15:25:35.910  7093  7093 I bluedroid-qcom: get_profile_interface hidhost
08-31 15:25:35.911  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.912  7093  7093 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:25:35.914  7093  7093 D HealthService: Received start request. Starting profile...
08-31 15:25:35.916  7093  7093 I bluedroid-qcom: get_profile_interface health
08-31 15:25:35.916  7093  7093 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:25:35.917  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.918  7093  7093 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 15:25:35.920  7093  7093 D PanService: Received start request. Starting profile...
08-31 15:25:35.920  7093  7093 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:25:35.920  7093  7093 I bluedroid-qcom: get_profile_interface pan
,08-31 15:25:35.928  7093  7093 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-31 15:25:35.928  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.929  7093  7093 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 15:25:35.935  7093  7093 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:25:35.936  7093  7093 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:25:35.936  7093  7093 D BtGatt.GattService: start()
08-31 15:25:35.936  7093  7093 I bluedroid-qcom: get_profile_interface gatt
08-31 15:25:35.937  7093  7093 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:25:35.944  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.946  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.946  7093  7093 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 15:25:35.947  7093  7093 V BluetoothMapService: BluetoothMapBinder()
08-31 15:25:35.948  7093  7093 D BluetoothMapService: Received start request. Starting profile...
08-31 15:25:35.948  7093  7093 D BluetoothMapService: start()
08-31 15:25:35.952  7093  7093 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 15:25:35.952  7093  7093 D BluetoothMapEmailAppObserver: createReceiver()
,08-31 15:25:35.953  7093  7093 D BluetoothMapEmailAppObserver: initObservers()
08-31 15:25:35.953  7093  7093 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 15:25:35.963  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:35.963  7093  7093 D HeadsetStateMachine: Proxy object connected
08-31 15:25:35.964  7093  7093 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 15:25:35.964  7093  7093 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-31 15:25:35.979  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 15:25:35.980  7093  7500 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 15:25:35.981  7093  7500 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 15:25:35.982  7093  7500 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 15:25:35.985  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:25:35.989  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:25:35.994  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 15:25:35.997  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:25:35.998  7093  7093 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 15:25:36.001  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 15:25:36.002  7093  7093 V BluetoothMapService: Handler(): got msg=1
08-31 15:25:36.003  7093  7464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 15:25:36.003  7093  7464 I bluedroid-qcom: enable
08-31 15:25:36.003  7093  7464 I bt_hci_bdroid: init
08-31 15:25:36.005  7093  7464 I bt_vendor: bt-vendor : init
08-31 15:25:36.005  7093  7464 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 15:25:36.005  7093  7464 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 15:25:36.005  7093  7464 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 15:25:36.005  7093  7464 D bt_userial_mct: userial_init
08-31 15:25:36.005  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.006  7093  7464 D bt_hci_bdroid: set_power 1
08-31 15:25:36.006  7093  7464 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 15:25:36.006  7093  7464 I bt_vendor: Starting hciattach daemon
08-31 15:25:36.006  7093  7464 I bt_vendor: try to set true
08-31 15:25:35.998  7526  7526 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:35.998  7526  7526 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:25:36.017  7093  7523 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 15:25:36.017  7093  7523 I bt-btu  : btu_task pending for preload complete event
08-31 15:25:36.023  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:25:36.023  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:25:36.023  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:25:36.023  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.023  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 15:25:36.032  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 15:25:36.138  7533  7533 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 15:25:36.161  7534  7534 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 15:25:36.195  7536  7536 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 15:25:36.206  7537  7537 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-31 15:25:36.217  7538  7538 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 15:25:36.233  7539  7539 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 15:25:36.257  7541  7541 I libmdmdetect: ESOC framework not supported
,08-31 15:25:36.258  7541  7541 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 15:25:36.267  7541  7541 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 15:25:36.267  7541  7541 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-31 15:25:36.267  7541  7541 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 15:25:36.267  7541  7541 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 15:25:36.267  7541  7541 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-31 15:25:36.267  7541  7541 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 15:25:36.268  7541  7541 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 15:25:36.306  7541  7542 E QC-QMI  : qmi_client [7541] 14: failed to locate client data
08-31 15:25:36.308   480   480 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 15:25:36.308   480   480 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-31 15:25:36.359  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 15:25:36.374  7544  7544 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 15:25:36.408  7093  7464 I bt_vendor: bluetooth satus is on
08-31 15:25:36.408  7093  7464 D bt_hci_bdroid: preload
,08-31 15:25:36.408  7093  7525 D bt_userial_mct: userial_open(port:0)
08-31 15:25:36.408  7093  7525 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 15:25:36.411  7093  7525 I bt_vendor: Done intiailizing UART
08-31 15:25:36.414  7093  7525 I bt_vendor: Done intiailizing UART
08-31 15:25:36.415  7093  7525 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 15:25:36.415  7093  7525 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 15:25:36.415  7093  7546 D bt_userial_mct: Entering userial_read_thread()
08-31 15:25:36.415  7093  7523 I bt-btu  : btu_task received preload complete event
08-31 15:25:36.416  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 15:25:36.416  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 15:25:36.421  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:25:36.428  7093  7523 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:25:36.429  7093  7523 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 15:25:36.429  7093  7523 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:25:36.429  7093  7523 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 15:25:36.446  1044  1484 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-31 15:25:36.525  7093  7523 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 15:25:36.526  7093  7523 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0179061 
08-31 15:25:36.526  7093  7523 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0179061 
,08-31 15:25:36.560  7093  7468 E bt-btif : Calling BTA_HhEnable
,08-31 15:25:36.561  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 15:25:36.561  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 15:25:36.561  7093  7523 W bt-l2cap: btif_storage_get_adapter_propertyr PSM: 0x001b
08-31 15:25:36.561  7093  7468 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 15:25:36.561  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 15:25:36.561  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 15:25:36.561  7093  7468 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 15:25:36.569  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-31 15:25:36.570  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 15:25:36.571  7093  7468 D BluetoothAdapterProperties: Name is: G3
08-31 15:25:36.575  7093  7468 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:25:36.576  7093  7468 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:25:36.578  7093  7468 D bt_hci_bdroid: postload
08-31 15:25:36.578  7093  7525 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:36.580  7093  7523 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-31 15:25:36.585  7093  7525 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:36.585  7312  7333 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-31 15:25:36.587  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:36.586  7093  7468 D bte_conf: Device ID record 1 : primary
08-31 15:25:36.587  7093  7468 D bte_conf:   vendorId            = 00c4
08-31 15:25:36.587  7093  7468 D bte_conf:   vendorIdSource      = 0001
08-31 15:25:36.587  7093  7468 D bte_conf:   product             = 13a1
08-31 15:25:36.587  7093  7468 D bte_conf:   version             = 1000
08-31 15:25:36.587  7093  7468 D bte_conf:   clientExecutableURL = 
08-31 15:25:36.587  7093  7468 D bte_conf:   serviceDescription  = 
08-31 15:25:36.587  7093  7468 D bte_conf:   documentationURL    = 
08-31 15:25:36.587  7093  7468 D bte_conf: bte_load_did_conf no section named DID2.
08-31 15:25:36.589  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:36.589  7093  7525 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:36.578  7552  7552 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:36.592  7093  7464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 15:25:36.592  7093  7464 D BluetoothAdapterProperties: ScanMode =  20
08-31 15:25:36.592  7093  7464 D BluetoothAdapterProperties: State =  11
08-31 15:25:36.592  7093  7464 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 15:25:36.593  7093  7464 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 15:25:36.593  7093  7464 D BluetoothAdapterProperties: Setting state to 12
08-31 15:25:36.593  7093  7464 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 15:25:36.594  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:36.594  7093  7464 I BluetoothAdapterState: Entering On State
08-31 15:25:36.595  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 15:25:36.595  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-31 15:25:36.595  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:25:36.596  7093  7523 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:36.596  7093  7523 W bt-smp  : Plain text(LSB ~ MSB) = 22 13 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:36.596  7093  7523 W bt-smp  : Encrypted text(LSB ~ MSB) = 8f 6a 4c 58 3c a4 be a1 ef 53 ee 71 61 4b bc 42 
08-31 15:25:36.597  7093  7525 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:36.597  7093  7523 W bt-btm  : Stopping oneshot timer
08-31 15:25:36.597  7093  7468 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 15:25:36.597  7093  7468 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 15:25:36.578  7552  7552 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:36.600  7093  7546 E bt_mct  : hci lib postload completed
,08-31 15:25:36.619  7093  7464 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 15:25:36.619  7093  7464 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 15:25:36.619  7093  7464 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-31 15:25:36.622  7093  7464 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 15:25:36.625  1839  1839 D BluetoothHeadset: Proxy object connected
08-31 15:25:36.626  1839  2575 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:25:36.628  7093  7523 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:36.628  7093  7523 W bt-smp  : Plain text(LSB ~ MSB) = 01 8f 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:36.628  7093  7523 W bt-smp  : Encrypted text(LSB ~ MSB) = bf 3b 68 2a 69 d3 09 fc 92 95 22 6b 45 81 15 b6 
08-31 15:25:36.628  7093  7523 W bt-btm  : Stopping oneshot timer
08-31 15:25:36.631  7093  7468 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:25:36.632  7093  7468 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 15:25:36.635  1839  1839 D BluetoothHeadset: Proxy object connected
,08-31 15:25:36.638  6955  6974 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:25:36.638  6955  6974 D BluetoothPan: onBluetoothStateChange call bindService
08-31 15:25:36.644  7093  7523 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:36.644  7093  7523 W bt-smp  : Plain text(LSB ~ MSB) = 58 94 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:36.644  7093  7523 W bt-smp  : Encrypted text(LSB ~ MSB) = 34 27 20 52 df e2 19 e2 01 bd 6b 39 ed 8b 2f e2 
08-31 15:25:36.644  7093  7523 W bt-btm  : Stopping oneshot timer
08-31 15:25:36.645  6955  6955 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:25:36.645  6955  6955 D PanProfile: Bluetooth service connected
08-31 15:25:36.646  7093  7464 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 15:25:36.646  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:25:36.648  6955  7063 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 15:25:36.652  1044  1044 D BluetoothA2dp: Proxy object connected
08-31 15:25:36.656  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:25:36.657  6955  6955 D BluetoothInputDevice: Proxy object connected
08-31 15:25:36.658  6955  6955 D HidProfile: Bluetooth service connected
08-31 15:25:36.659  1839  1839 D BluetoothHeadset: Proxy object connected
08-31 15:25:36.659  6955  6974 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 15:25:36.661  6955  6973 D BluetoothMap: onBluetoothStateChange: up=true
08-31 15:25:36.662  7567  7567 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-31 15:25:36.665  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:25:36.666  1044  1044 D BluetoothHeadset: Proxy object connected
08-31 15:25:36.666  6955  6955 D BluetoothMap: Proxy object connected
08-31 15:25:36.666  6955  6955 D MapProfile: Bluetooth service connected
08-31 15:25:36.666  6955  6955 D BluetoothMap: getConnectedDevices()
08-31 15:25:36.667  7093  7566 V BluetoothMapService: getConnectedDevices()
08-31 15:25:36.668  7093  7523 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:36.668  7093  7523 W bt-smp  : Plain text(LSB ~ MSB) = c2 e4 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:36.668  7093  7523 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 0e 87 f2 70 df 94 80 88 65 89 0a 02 a3 fd 46 
08-31 15:25:36.668  7093  7523 W bt-btm  : Stopping oneshot timer
08-31 15:25:36.668  1044  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 15:25:36.669  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 15:25:36.669  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 15:25:36.672  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:36.673  1044  1119 D BluetoothManagerService: Message: 40
08-31 15:25:36.673  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 15:25:36.675  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.675  1928  2121 D LGBluetoothAPIService: Message: 1
08-31 15:25:36.675  1928  2121 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-31 15:25:36.679  7093  7093 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.679  7093  7093 D BluetoothMapService: STATE_ON
08-31 15:25:36.679  7093  7093 V BluetoothMapService: Handler(): got msg=1
08-31 15:25:36.679  6699  6699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 15:25:36.680  7093  7523 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:36.680  7093  7523 W bt-smp  : Plain text(LSB ~ MSB) = bd 9c 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:36.680  7093  7523 W bt-smp  : Encrypted text(LSB ~ MSB) = 63 48 9e dd 0e 6e 29 46 2a 07 33 15 14 cc 16 92 
08-31 15:25:36.680  7093  7093 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 15:25:36.681  7093  7523 W bt-btm  : Stopping oneshot timer
08-31 15:25:36.683  7093  7571 D BluetoothMapMasInstance: MAS initSocket()
08-31 15:25:36.684  7093  7571 D BluetoothMapMasInstance:   masId = 00
08-31 15:25:36.684  7093  7571 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 15:25:36.684  7093  7571 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 15:25:36.684  7093  7571 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 15:25:36.684  6955  6955 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 15:25:36.685  1044  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:36.686  1044  1119 D BluetoothManagerService: Message: 30
08-31 15:25:36.687  1928  2121 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 15:25:36.688  7093  7571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:36.690  7093  7571 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 15:25:36.691  7093  7571 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-31 15:25:36.691  7093  7571 D BluetoothMapMasInstance: Accepting socket connection...
08-31 15:25:36.693  6955  6955 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 15:25:36.695  7093  7468 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:25:36.695  7093  7468 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 15:25:36.697  1044  1119 D BluetoothManagerService: Message: 30
08-31 15:25:36.700  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:36.701  7093  7093 V BluetoothPbapService: Pbap Service onCreate
08-31 15:25:36.701  7093  7093 V BluetoothPbapService: Starting PBAP service
08-31 15:25:36.702  7093  7093 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 15:25:36.702  7093  7093 V BluetoothPbapService: Pbap Service onBind
,08-31 15:25:36.706  7093  7093 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.706  7093  7093 V BluetoothPbapService: state: 12
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:36.707  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:36.708  7093  7093 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 15:25:36.708  7093  7093 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 15:25:36.709  6955  6955 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 15:25:36.709  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 15:25:36.710  7093  7093 V BluetoothPbapService: Handler(): got msg=1
08-31 15:25:36.710  7093  7093 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 15:25:36.710  1928  2121 D LGBluetoothAPIService: Message: 100
08-31 15:25:36.710  1928  2121 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 15:25:36.711  6955  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:25:36.712  7093  7573 V BluetoothPbapService: Pbap Service initSocket
08-31 15:25:36.713  1044  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:36.713  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:36.713  6955  6955 D BluetoothA2dp: Proxy object connected
08-31 15:25:36.714  6955  6955 D A2dpProfile: Bluetooth service connected
08-31 15:25:36.714  7093  7573 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:36.715  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-31 15:25:36.715  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:36.715  7093  7093 V BluetoothPbapReceiver: ***********state = 12
08-31 15:25:36.715  7093  7573 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 15:25:36.715  7093  7573 V BluetoothPbapService: Succeed to create listening socket 
08-31 15:25:36.715  7093  7573 V BluetoothPbapService: Accepting socket connection...
08-31 15:25:36.718  6955  6955 D BluetoothHeadset: Proxy object connected
08-31 15:25:36.719  6955  6955 D HeadsetProfile: Bluetooth service connected
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:36.719  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:36.719  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:36.720  2168  2168 D c       : Getting all permits...
08-31 15:25:36.720  2168  2168 D a       : Opening database...
08-31 15:25:36.721  6955  6955 D BluetoothPbap: Proxy object connected
08-31 15:25:36.721  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:36.721  6955  6955 D PbapServerProfile: Bluetooth service connected
08-31 15:25:36.722  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:36.723  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:36.723  2168  2168 D a       : Opening database auth.proximity.permit_store...
08-31 15:25:36.724  2168  2168 D a       : Closing database...
08-31 15:25:36.725  6955  6955 D DockEventReceiver: finishStartingService: stopping service
08-31 15:25:36.737  6955  6955 D BluetoothPermissionRequest: onReceive
,08-31 15:25:36.739  6955  6955 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 15:25:36.742  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:25:36.745  7093  7093 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 15:25:36.746  7093  7093 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 15:25:36.752  7093  7093 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 15:25:36.772  7093  7093 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 15:25:36.772  7093  7093 V BtOppService: onCreate
,08-31 15:25:36.777  7093  7093 V BluetoothOppNotification: send message
08-31 15:25:36.780  7093  7093 V BtOppService: Starting RfcommListener
08-31 15:25:36.784  7093  7093 D BluetoothOppPreference: Dumping Names:  
08-31 15:25:36.784  7093  7093 D BluetoothOppPreference: {}
08-31 15:25:36.784  7093  7093 D BluetoothOppPreference: Dumping Channels:  
08-31 15:25:36.784  7093  7093 D BluetoothOppPreference: {}
08-31 15:25:36.784  7093  7093 V BtOppService: onStartCommand
08-31 15:25:36.787  7093  7581 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-31 15:25:36.789  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.789  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 15:25:36.794  7093  7093 V BluetoothOppNotification: new notify threadi!
08-31 15:25:36.794  7093  7093 V BluetoothOppNotification: send delay message
08-31 15:25:36.795  7093  7093 V BtOppService: start RfcommListener
08-31 15:25:36.799  7093  7093 V BtOppService: RfcommListener started
08-31 15:25:36.802  7093  7583 V BtOppRfcommListener: Starting RFCOMM listener....
,08-31 15:25:36.802  7093  7578 V BtOppService: Deleted complete outbound shares, number =  0
08-31 15:25:36.802  1044  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:36.803  7093  7583 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:36.805  7093  7578 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 15:25:36.805  7093  7582 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 15:25:36.805  7093  7578 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 15:25:36.806  7093  7583 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-31 15:25:36.806  7093  7583 V BtOppRfcommListener: Started RFCOMM listener....
08-31 15:25:36.806  7093  7583 I BtOppRfcommListener: Accept thread started.
08-31 15:25:36.806  7093  7583 V BtOppRfcommListener: Accepting connection...
08-31 15:25:36.807  7093  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 15:25:36.808  7093  7578 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31c86e35 on behalf of 
08-31 15:25:36.811  7093  7582 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35e942ca on behalf of 
08-31 15:25:36.816  7093  7582 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 15:25:36.817  7093  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38e72c3b on behalf of 
08-31 15:25:36.817  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:36.817  7093  7093 V BluetoothFtpService: Ftp Service onCreate
08-31 15:25:36.817  7093  7093 I BluetoothFtpService: Ftp Service onCreate
08-31 15:25:36.817  7093  7093 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:25:36.817  7093  7093 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.817  7093  7093 V BluetoothFtpService: Starting Listening on sockets
08-31 15:25:36.818  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:25:36.818  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:25:36.818  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:25:36.818  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.818  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 15:25:36.818  7093  7093 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 15:25:36.820  7093  7581 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 15:25:36.821  7093  7582 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:36.821  7093  7093 V BtOppService: ContentObserver received notification
08-31 15:25:36.821  7093  7093 V BtOppService: ContentObserver received notification
08-31 15:25:36.821  7093  7093 V BluetoothFtpService: Handler(): got msg=1
08-31 15:25:36.822  7093  7093 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 15:25:36.822  7093  7093 V BluetoothFtpService: Ftp Service initSocket
08-31 15:25:36.823  7093  7582 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e9eb8b1 on behalf of 
08-31 15:25:36.823  7093  7584 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 15:25:36.823  7093  7584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 15:25:36.825  7093  7582 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 15:25:36.826  7093  7584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fc0c196 on behalf of 
08-31 15:25:36.826  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:36.827  7093  7093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:36.828  7093  7093 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
,08-31 15:25:36.829  7093  7093 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 15:25:36.831  7093  7585 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 15:25:36.832  7093  7584 V BluetoothOppNotification: update too frequent, put in queue
08-31 15:25:36.834  7093  7582 V BluetoothOppNotification: outbound notification was removed.
08-31 15:25:36.834  7093  7582 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:36.834  7093  7584 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 15:25:36.836  7093  7582 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30125117 on behalf of 
08-31 15:25:36.837  7093  7582 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 15:25:36.838  7093  7582 V BluetoothOppNotification: inbound notification was removed.
08-31 15:25:36.838  7093  7582 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 15:25:36.839  7093  7582 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b4bb904 on behalf of 
,08-31 15:25:36.858  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
,08-31 15:25:36.858  7093  7093 V BluetoothSapService: Sap Service onCreate
,08-31 15:25:36.860  7093  7093 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:36.860  7093  7093 V BluetoothSapService: state: 12
08-31 15:25:36.861  7093  7093 V BluetoothSapService: Starting SAP server process
08-31 15:25:36.862  7093  7093 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 15:25:36.848  7586  7586 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:36.863  7093  7587 V BluetoothSapService: Sap Service initRfcommSocket
08-31 15:25:36.848  7586  7586 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:36.864  1044  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:36.865  7093  7587 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:36.866  7093  7587 V BluetoothSapService: Succeed to create listening socket 
08-31 15:25:36.866  7093  7587 V BluetoothSapService: Accepting socket connection...
08-31 15:25:36.883  7586  7586 V BT_SAP  : Event pipe created
08-31 15:25:36.883  7586  7586 V BT_SAP  : create_server_socket qcom.sap.server
08-31 15:25:36.883  7586  7586 V BT_SAP  : created socket fd 6
,08-31 15:25:37.298  1044  1375 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:37.298  1044  1375 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:37.326  1044  1425 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 15:25:37.332  1044  1425 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 15:25:37.532  1044  2036 I ActivityManager: Killing 7142:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-31 15:25:37.568  1044  2018 W libprocessgroup: failed to open /acct/uid_10011/pid_7142/cgroup.procs: No such file or directory
,08-31 15:25:37.799  7093  7093 V BluetoothOppNotification: new notify threadi!
,08-31 15:25:37.800  7093  7093 V BluetoothOppNotification: send delay message
,08-31 15:25:37.812  7093  7597 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 15:25:37.815  7093  7597 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@54d6170 on behalf of 
08-31 15:25:37.819  7093  7597 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 15:25:37.822  7093  7597 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:37.823  7093  7597 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2242cce9 on behalf of 
08-31 15:25:37.824  7093  7597 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 15:25:37.825  7093  7597 V BluetoothOppNotification: outbound notification was removed.
08-31 15:25:37.825  7093  7597 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:37.827  7093  7597 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16166d6e on behalf of 
08-31 15:25:37.827  7093  7597 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 15:25:37.829  7093  7597 V BluetoothOppNotification: inbound notification was removed.
08-31 15:25:37.829  7093  7597 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 15:25:37.831  7093  7597 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@df84c0f on behalf of 
,08-31 15:25:38.340  1044  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:25:38.340  1044  1908 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@25183851 mBinding = false
,08-31 15:25:38.369  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:25:38.369  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:25:38.369  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,08-31 15:25:38.374  1044  1119 D BluetoothManagerService: Message: 2
08-31 15:25:38.375  1044  1119 D BluetoothManagerService: Sending off request.
08-31 15:25:38.376  7093  7566 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 15:25:38.376  7093  7464 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 15:25:38.377  7093  7464 D BluetoothAdapterProperties: Setting state to 13
08-31 15:25:38.377  7093  7464 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 15:25:38.377  7093  7464 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:25:38.378  7093  7464 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 15:25:38.379  7093  7468 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:25:38.381  7093  7464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 15:25:38.383  7093  7571 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-31 15:25:38.387  7093  7573 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:38.388  7093  7583 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:38.388  7093  7585 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:38.389  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 15:25:38.389  7093  7523 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 15:25:38.391  7093  7464 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 15:25:38.395  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 15:25:38.395  7093  7523 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:25:38.404  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:38.404  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:38.410  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:38.410  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:38.415  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:38.415  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:38.416  6699  6699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:38.417  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:38.419  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:38.419  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 15:25:38.419  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 15:25:38.422  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:38.438  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:38.442  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:38.443  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:38.445  7093  7093 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:38.445  7093  7093 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:25:38.445  7093  7093 V BluetoothMapService: Handler(): got msg=4
08-31 15:25:38.445  7093  7093 D BluetoothMapService: MAP Service closeService in
08-31 15:25:38.445  7093  7093 D BluetoothMapMasInstance: MAP Service shutdown
08-31 15:25:38.445  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:25:38.445  7093  7093 V BluetoothMapService: MAP Service closeService out
08-31 15:25:38.447  7093  7093 V BtOppService: Receiver DISABLED_ACTION 
08-31 15:25:38.447  7093  7093 I BtOppRfcommListener: stopping Accept Thread
08-31 15:25:38.447  7093  7093 V BtOppRfcommListener: close mBtServerSocket
,08-31 15:25:38.450  7093  7583 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 15:25:38.451  7093  7093 V BtOppRfcommListener: waiting for thread to terminate
08-31 15:25:38.451  7093  7093 V BtOppRfcommListener: done waiting for thread to terminate
08-31 15:25:38.454  6955  6955 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-31 15:25:38.455  7093  7587 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:38.463  6955  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 15:25:38.467  7093  7093 V BtOppService: onDestroy
08-31 15:25:38.469  7093  7093 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 15:25:38.474  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:25:38.474  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:38.474  7093  7093 V BluetoothPbapReceiver: ***********state = 13
08-31 15:25:38.475  7093  7093 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-31 15:25:38.479  7093  7093 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:38.479  7093  7093 V BluetoothPbapService: state: 13
08-31 15:25:38.479  7093  7093 V BluetoothPbapService: Pbap Service closeService in
08-31 15:25:38.483  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:38.484  7093  7093 V BluetoothPbapService: successfully stopped pbap service
08-31 15:25:38.484  7093  7093 V BluetoothPbapService: Pbap Service closeService out
08-31 15:25:38.485  7093  7093 V BluetoothPbapService: Pbap Service onDestroy
08-31 15:25:38.485  7093  7093 V BluetoothPbapService: Pbap Service closeService in
08-31 15:25:38.485  7093  7093 V BluetoothPbapService: Pbap Service closeService out
08-31 15:25:38.485  7093  7093 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 15:25:38.508  6955  6955 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:38.511  6955  6955 D BluetoothPbap: Proxy object disconnected
08-31 15:25:38.511  6955  6955 D PbapServerProfile: Bluetooth service disconnected
08-31 15:25:38.518  6955  6955 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 15:25:38.527  6955  6955 D BluetoothPermissionRequest: onReceive
08-31 15:25:38.527  6955  6955 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 15:25:38.533  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 15:25:38.537  7093  7093 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 15:25:38.537  7093  7093 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 15:25:38.538  7093  7093 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 15:25:38.543  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:38.543  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 15:25:38.545  7093  7093 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:25:38.545  7093  7093 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:38.545  7093  7093 V BluetoothFtpService: Ftp Service closeService
08-31 15:25:38.545  7093  7093 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-31 15:25:38.548  7093  7093 V BluetoothFtpService: successfully stopped ftp service
,08-31 15:25:38.548  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-31 15:25:38.548  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-31 15:25:38.548  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
,08-31 15:25:38.548  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:38.548  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 15:25:38.548  7093  7093 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 15:25:38.550  7093  7093 V BluetoothFtpService: Ftp Service onDestroy
08-31 15:25:38.550  7093  7093 V BluetoothFtpService: Ftp Service closeService
08-31 15:25:38.554  7093  7093 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:38.554  7093  7093 V BluetoothSapService: state: 13
08-31 15:25:38.554  7093  7093 V BluetoothSapService: Stopping SAP server process
08-31 15:25:38.555  7093  7093 V BluetoothSapService: Sap Service closeSapService in
08-31 15:25:38.555  7093  7093 V BluetoothSapService: Close listen Socket : 
08-31 15:25:38.555  7093  7093 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:25:38.555  7093  7093 V BluetoothSapService: Close sapd  Socket : 
08-31 15:25:38.557  7093  7093 V BluetoothSapService: Sap Service closeSapService out
08-31 15:25:38.557  7093  7093 V BluetoothSapService: Sap Service onDestroy
08-31 15:25:38.557  7093  7093 V BluetoothSapService: Sap Service closeSapService in
08-31 15:25:38.557  7093  7093 V BluetoothSapService: Close listen Socket : 
,08-31 15:25:38.557  7093  7093 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:25:38.557  7093  7093 V BluetoothSapService: Close sapd  Socket : 
08-31 15:25:38.558  7093  7093 V BluetoothSapService: Sap Service closeSapService out
,08-31 15:25:39.298  7093  7468 D bt_hci_bdroid: cleanup
,08-31 15:25:39.311  7093  7525 I bt_lpm  : LPM is already off!!!
08-31 15:25:39.311  7093  7546 I bt_userial_mct: exiting userial_read_thread
08-31 15:25:39.311  7093  7546 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 15:25:39.312  7093  7523 W bt-btif : ag scb idx 1 not allocated
08-31 15:25:39.312  7093  7523 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:39.312  7093  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:39.313  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:25:39.313  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:39.313  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:25:39.313  7093  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:39.313  7093  7523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:25:39.313  7093  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:39.313  7093  7523 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:25:39.315  7093  7468 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 15:25:39.315  7093  7525 I bt_vendor: hw_epilog_process
08-31 15:25:39.315  7093  7468 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 15:25:39.315  7093  7468 D bt_userial_mct: userial_close
08-31 15:25:39.315  7093  7468 E bt_userial_mct: pthread_join() FAILED result:3
08-31 15:25:39.315  7093  7468 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 15:25:39.327  7093  7468 D bt_hci_bdroid: set_power 0
08-31 15:25:39.327  7093  7468 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 15:25:39.327  7093  7468 I bt_vendor: bluetooth satus is on
08-31 15:25:39.327  7093  7468 I bt_vendor: bt-vendor : resetting BT status
08-31 15:25:39.327  7093  7468 I bt_vendor: Starting hciattach daemon
08-31 15:25:39.327  7093  7468 I bt_vendor: try to set false
,08-31 15:25:39.333  7093  7468 I bt_vendor: Starting hciattach daemon
08-31 15:25:39.334  7093  7468 I bt_vendor: try to set false
08-31 15:25:39.335  7093  7468 I bt_vendor: cleanup
08-31 15:25:39.336  7093  7523 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 15:25:39.336  7093  7468 I GKI_LINUX: GKI_exit_task 0 done
08-31 15:25:39.336  7093  7468 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 15:25:39.337  7093  7464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 15:25:39.345  7093  7093 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:25:39.348  7093  7093 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:25:39.349  7093  7093 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:25:39.349  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:39.349  7093  7500 D HeadsetStateMachine: Exit Disconnected: -1
08-31 15:25:39.354  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-31 15:25:39.354  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-31 15:25:39.354  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-31 15:25:39.355  7093  7464 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 15:25:39.355  1044  1044 D BluetoothHeadset: Proxy object disconnected
08-31 15:25:39.355  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 15:25:39.355  7093  7093 D A2dpService: Received stop request...Stopping profile...
08-31 15:25:39.356  7093  7515 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:25:39.357  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-31 15:25:39.363  7093  7093 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 15:25:39.363  7093  7093 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:25:39.363  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:39.365  7093  7093 D HidService: Received stop request...Stopping profile...
08-31 15:25:39.365  1044  1044 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:39.365  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 15:25:39.366  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:39.370  7093  7093 D HealthService: Received stop request...Stopping profile...
,08-31 15:25:39.372  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:39.375  7093  7093 D PanService: Received stop request...Stopping profile...
08-31 15:25:39.375  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:39.376  7093  7093 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:25:39.377  7093  7093 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 15:25:39.377  7093  7093 D BtGatt.GattService: stop()
08-31 15:25:39.377  7093  7093 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 15:25:39.379  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:39.379  7093  7093 D HeadsetStateMachine: Unbinding service...
08-31 15:25:39.381  7093  7093 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:25:39.381  7093  7093 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:25:39.381  7093  7093 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:25:39.381  7093  7093 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:25:39.381  7093  7093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 15:25:39.381  7093  7093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:25:39.381  7093  7093 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:25:39.382  7093  7093 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:25:39.382  7093  7093 D BluetoothMapService: stop()
,08-31 15:25:39.385  7093  7093 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 15:25:39.386  7093  7093 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 15:25:39.387  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:39.388  7093  7093 I BluetoothA2dpServiceJni: cleanupNative
08-31 15:25:39.389  7093  7516 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 15:25:39.389  7093  7093 I GKI_LINUX: GKI_exit_task 2 done
08-31 15:25:39.389  7093  7093 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 15:25:39.389  7093  7093 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:25:39.389  7093  7093 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:25:39.390  7093  7093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:25:39.390  7093  7093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:25:39.390  7093  7093 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:25:39.390  7093  7093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:25:39.390  7093  7093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 15:25:39.393  7093  7093 V BluetoothMapService: Handler(): got msg=4
08-31 15:25:39.393  7093  7093 D BluetoothMapService: MAP Service closeService in
08-31 15:25:39.393  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:25:39.393  7093  7093 V BluetoothMapService: MAP Service closeService out
08-31 15:25:39.394  7093  7464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 15:25:39.394  7093  7464 D BluetoothAdapterProperties: Setting state to 10
08-31 15:25:39.394  7093  7464 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-31 15:25:39.398  7093  7093 D BluetoothMapService: cleanup()
08-31 15:25:39.398  7093  7093 D BluetoothMapService: MAP Service closeService in
08-31 15:25:39.398  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:25:39.398  7093  7093 V BluetoothMapService: MAP Service closeService out
08-31 15:25:39.400  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:39.400  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 15:25:39.400  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-31 15:25:39.402  7093  7464 I BluetoothAdapterState: Entering OffState
08-31 15:25:39.402  1839  2754 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:25:39.403  6955  6974 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:25:39.404  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:25:39.404  6955  6974 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:25:39.405  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:25:39.405  6955  6974 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:25:39.408  6955  6974 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:25:39.409  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:25:39.409  6955  6974 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:25:39.410  6955  6974 D BluetoothMap: onBluetoothStateChange: up=false
08-31 15:25:39.411  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:25:39.412  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 15:25:39.412  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 15:25:39.414  1044  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 15:25:39.414  1044  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 15:25:39.414  1044  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@25183851 mBinding = false
08-31 15:25:39.414  1044  1119 D BluetoothManagerService: Sending unbind request.
08-31 15:25:39.419  7093  7468 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 15:25:39.422  7093  7093 I GKI_LINUX: GKI_exit_task 1 done
08-31 15:25:39.422  7093  7093 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 15:25:39.423  7093  7093 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 15:25:39.423  7093  7093 I art     : --- WEIRD: removing null entry 248
08-31 15:25:39.423  7093  7093 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 15:25:39.423  7093  7093 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 15:25:39.424  7093  7093 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 15:25:39.425  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 15:25:39.428  7093  7093 I art     : System.exit called, status: 0
08-31 15:25:39.428  7093  7093 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 15:25:39.485  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:39.485  1928  2121 D LGBluetoothAPIService: Message: 2
08-31 15:25:39.485  1928  2121 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@8432f83 mBinding = false
08-31 15:25:39.485  1928  2121 D LGBluetoothAPIService: Sending unbind request.
08-31 15:25:39.486  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:39.488  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:39.491   312  2136 V AudioFlinger: 7093 died, releasing its sessions
08-31 15:25:39.491   312  2136 V AudioFlinger:  pid 1839 @ 0
08-31 15:25:39.491   312  2136 V AudioFlinger:  pid 3427 @ 1
08-31 15:25:39.491   312  2136 V AudioFlinger:  pid 3427 @ 2
08-31 15:25:39.491  6955  6955 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 15:25:39.494  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:39.498  6955  6955 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 15:25:39.498  6955  6955 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 15:25:39.501  1044  1713 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-31 15:25:39.501  1044  1713 W ActivityManager: android.os.DeadObjectException
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-31 15:25:39.501  1044  1713 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 15:25:39.503  1589  1589 D BluetoothAdapter: 29862123: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:39.503  1589  1589 D BluetoothAdapter: 29862123: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:39.504  6955  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:25:39.557  1044  1764 I ActivityManager: Process com.android.bluetooth (pid 7093) has died
08-31 15:25:39.557  1044  1764 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-31 15:25:39.630  1044  1561 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7646 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 15:25:39.633  6955  6955 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:39.705  7646  7646 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 15:25:39.705  7646  7646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:25:39.706  7646  7646 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 15:25:39.707  7646  7646 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 15:25:39.733  7646  7646 D BluetoothAdapterApp: Loading JNI Library
,08-31 15:25:39.775  7646  7646 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@78bfa98 Instance Count = 1
,08-31 15:25:39.787  7646  7646 D BluetoothAdapterApp: onCreate
08-31 15:25:39.821  7646  7646 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-31 15:25:39.821  7646  7646 D ProfileConfigQcom: Adding HeadsetService
08-31 15:25:39.822  7646  7646 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 15:25:39.822  7646  7646 D ProfileConfigQcom: Adding A2dpService
08-31 15:25:39.822  7646  7646 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 15:25:39.822  7646  7646 D ProfileConfigQcom: Adding HidService
08-31 15:25:39.823  7646  7646 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 15:25:39.823  7646  7646 D ProfileConfigQcom: Adding HealthService
08-31 15:25:39.823  7646  7646 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 15:25:39.824  7646  7646 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 15:25:39.824  7646  7646 D ProfileConfigQcom: Adding PanService
08-31 15:25:39.825  7646  7646 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 15:25:39.825  7646  7646 D ProfileConfigQcom: Adding GattService
08-31 15:25:39.827  7646  7646 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 15:25:39.827  7646  7646 D ProfileConfigQcom: Adding BluetoothMapService
08-31 15:25:39.828  7646  7646 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 15:25:39.829  7646  7646 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:25:39.830  7646  7646 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:39.830  7646  7646 V BluetoothPbapReceiver: ***********state = 10
,08-31 15:25:39.832  7646  7646 V LGMDMManagerInternal: Create singleton instance
,08-31 15:25:39.934  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:39.942  6955  6955 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 15:25:39.944  1044  1982 I ActivityManager: Killing 7191:com.lge.email/u0a23 (adj 15): empty #17
08-31 15:25:39.974  1044  1909 W libprocessgroup: failed to open /acct/uid_10023/pid_7191/cgroup.procs: No such file or directory
,08-31 15:25:39.990  6955  6955 D BluetoothPermissionRequest: onReceive
,08-31 15:25:39.992  6955  6955 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 15:25:39.993  6955  6955 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 15:25:39.995  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:25:40.000  7646  7646 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 15:25:40.005  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:40.010  7646  7646 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:25:40.011  7646  7646 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:25:40.011  7646  7646 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:25:40.013  7646  7646 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:40.013  7646  7646 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 15:25:40.019  7042  7042 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 15:25:41.444  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:25:41.445  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:42.169  1044  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2a0c7524 type 2 when 139301 com.google.android.gms} when 139301
,08-31 15:25:42.179  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-31 15:25:42.179  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4424
08-31 15:25:42.181   308  7675 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 15:25:42.182  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 15:25:44.460  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:44.460  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f3e6ca4 added. We now have 6 listener(s)
08-31 15:25:44.460  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:44.478  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:44.478  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d866a0d added. We now have 7 listener(s)
08-31 15:25:44.478  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:44.481  6699  6809 I System.out: IsBluetoothEnabled
08-31 15:25:44.482  1044  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:44.482  1044  1561 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-31 15:25:44.482  1044  1119 D BluetoothManagerService: Message: 2
08-31 15:25:44.489  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:44.492  1044  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:44.492  1044  1982 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 15:25:44.512  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:25:44.512  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:25:44.512  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-31 15:25:44.512  1044  1119 D BluetoothManagerService: Message: 1
08-31 15:25:44.512  1044  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 15:25:44.549  1044  1119 D BluetoothManagerService: Message: 20
08-31 15:25:44.549  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b38a089:true
,08-31 15:25:44.552  7646  7646 D BluetoothAdapterState: make
08-31 15:25:44.556  7646  7646 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 15:25:44.557  7646  7646 I bluedroid-qcom: init
08-31 15:25:44.558  7646  7679 I BluetoothAdapterState: Entering OffState
08-31 15:25:44.558  7646  7646 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 15:25:44.558  7646  7646 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 15:25:44.558  7646  7646 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:25:44.559  7646  7646 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 15:25:44.559  7646  7646 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 15:25:44.560  7646  7646 I bluedroid-qcom: get_profile_interface socket
08-31 15:25:44.560  7646  7646 I bluedroid-qcom: get_profile_interface map_client
,08-31 15:25:44.563  7646  7683 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 15:25:44.558  7682  7682 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:44.558  7682  7682 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:44.575  7682  7682 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 15:25:44.575  7682  7682 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 15:25:44.575  7682  7682 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 15:25:44.579  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 15:25:44.580  1044  1119 D BluetoothManagerService: Message: 40
08-31 15:25:44.580  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 15:25:44.581  7646  7662 I bluedroid-qcom: config_hci_snoop_log
08-31 15:25:44.582  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 15:25:44.582  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 15:25:44.584  7646  7683 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 15:25:44.586  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 15:25:44.586  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 15:25:44.586  7646  7683 D BluetoothAdapterProperties: Name is: G3
08-31 15:25:44.586  7682  7682 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 15:25:44.594  7682  7682 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 15:25:44.594  7682  7682 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-31 15:25:44.606  7646  7679 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 15:25:44.610  7646  7679 D BluetoothAdapterProperties: Setting state to 11
08-31 15:25:44.610  7646  7679 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 15:25:44.614  7646  7679 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 15:25:44.617  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:44.617  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 15:25:44.617  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 15:25:44.618  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:44.620  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:44.625  6955  6955 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-31 15:25:44.629  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:44.630  7646  7679 D BluetoothBondStateMachine: make
08-31 15:25:44.632  7646  7646 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:25:44.632  7646  7646 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:44.632  7646  7646 V BluetoothPbapReceiver: ***********state = 11
08-31 15:25:44.633  7646  7679 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:44.633  7646  7679 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 15:25:44.633  7646  7679 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:44.633  7646  7679 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 15:25:44.633  7646  7679 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 15:25:44.639  7646  7694 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 15:25:44.640  7646  7679 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:25:44.644  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:44.650  7646  7646 D HeadsetService: Received start request. Starting profile...
08-31 15:25:44.651  7646  7646 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:25:44.651  7646  7646 D LGBluetoothHfpAdapter: Version 1.6
08-31 15:25:44.652  7646  7679 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:44.654  7646  7646 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 15:25:44.655  7646  7646 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:25:44.656  7646  7646 D HeadsetStateMachine: make
,08-31 15:25:44.660  7646  7679 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:44.665  6955  6955 D BluetoothPermissionRequest: onReceive
08-31 15:25:44.670  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:25:44.673  7646  7679 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:44.679  7646  7679 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:25:44.690  7646  7679 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:44.695  7646  7679 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:25:44.700  7646  7646 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:25:44.706  7646  7646 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:25:44.711  7646  7679 V LGMDMManager: Create singleton instance
08-31 15:25:44.713  7646  7646 D HeadsetStateMachine: max_hf_connections = 1
,08-31 15:25:44.713  7646  7646 I bluedroid-qcom: get_profile_interface handsfree
08-31 15:25:44.713  7646  7679 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 15:25:44.716  7646  7646 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 15:25:44.716   312  1381 V AudioPolicyService: registerClient() client 0xb0410920, uid 1002
08-31 15:25:44.717   312  2136 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 15:25:44.717   312  2136 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:25:44.717   312  2136 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:25:44.717  7646  7646 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 15:25:44.717   312   312 V AudioFlinger: registerClient() client 0xb1433088, pid 7646
08-31 15:25:44.718   312  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:44.718   312  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:44.718   312  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:44.718   312  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:44.718  1589  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:44.718  1589  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:44.718  1589  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:44.718  1589  1610 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:44.718  1839  2575 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:44.718  1839  2575 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:44.719  1839  2575 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:44.719  1839  2575 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:44.719  3427  3443 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:44.719  3427  3443 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:44.719  3427  3443 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:44.719  3427  3443 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:44.719  1044  1713 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:44.719  7646  7646 V ToneGenerator: Create Track: 0xb4928a80
08-31 15:25:44.719  1044  1713 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:25:44.719  7646  7646 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 15:25:44.719  7646  7646 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 15:25:44.719  1044  1713 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:44.719  1044  1713 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:25:44.719  7646  7693 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:25:44.719  7646  7693 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 15:25:44.719  7646  7693 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:25:44.720  7646  7693 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 15:25:44.720   312  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:25:44.720   312  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 15:25:44.720   312  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:25:44.720   312  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:25:44.720   312  13,81 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 15:25:44.721   312  2136 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:25:44.721   312  2136 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 15:25:44.721   312  2136 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:25:44.721   312  2136 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:25:44.721  7646  7646 V AudioSystem: getLatency() output 2, latency 50
08-31 15:25:44.721  7646  7646 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 15:25:44.721  7646  7646 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 15:25:44.721   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:25:44.721   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:25:44.721   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:25:44.721   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:25:44.721   312   312 V AudioFlinger: createTrack() lSessionId: 23
08-31 15:25:44.722  7646  7646 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 15:25:44.722   312   312 V AudioFlinger: acquiring 23 from 7646, for 7646
08-31 15:25:44.722   312   312 V AudioFlinger:  added new entry for 23
08-31 15:25:44.723  7646  7646 V ToneGenerator: ToneGenerator INIT OK, time: 141886
08-31 15:25:44.723  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:44.724  7646  7700 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 15:25:44.724  7646  7700 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:25:44.724  7646  7700 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:25:44.724  7646  7700 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 15:25:44.726   312  2137 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7646
08-31 15:25:44.726  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:44.727   312  2137 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 15:25:44.727   312  2137 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 15:25:44.727   312  2137 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 15:25:44.727   312  2137 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 15:25:44.727   312  2137 V voice   : voice_set_parameters: exit with code(0)
,08-31 15:25:44.727   312  2137 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 15:25:44.727   312  2137 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 15:25:44.727   312  2137 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 15:25:44.727   312  2137 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 15:25:44.727   312  2137 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 15:25:44.727   312  2137 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 15:25:44.727  7646  7700 V ToneGenerator: ToneGenerator destructor
08-31 15:25:44.727  7646  7700 V ToneGenerator: stopTone
08-31 15:25:44.727  7646  7700 V ToneGenerator: Delete Track: 0xb4928a80
,08-31 15:25:44.728  7646  7700 V AudioTrack: ~AudioTrack, releasing session id from 7646 on behalf of 7646
08-31 15:25:44.728   312  2136 V AudioFlinger: releasing 23 from 7646 for 7646
08-31 15:25:44.728   312  2136 V AudioFlinger:  decremented refcount to 0
08-31 15:25:44.728   312  2136 V AudioFlinger: purging stale effects
08-31 15:25:44.728   312  2136 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 15:25:44.728   312  2136 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 15:25:44.728   312  2136 V AudioFlinger: PlaybackThread::Track destructor
08-31 15:25:44.728   312  1272 V AudioPolicyService: AudioCommandThread() waking up
08-31 15:25:44.728   312  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
,08-31 15:25:44.728   312  2136 V AudioFlinger: removeClient_l() pid 7646, calling pid 312
08-31 15:25:44.728   312  1272 V AudioPolicyManager: releaseOutput() 2
08-31 15:25:44.728   312  1272 V AudioPolicyService: AudioCommandThread() going to sleep
,08-31 15:25:44.728  7646  7646 D A2dpService: Received start request. Starting profile...
,08-31 15:25:44.729  7646  7646 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 15:25:44.730  7646  7646 V Avrcp   : make
08-31 15:25:44.731  7646  7646 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-31 15:25:44.731  7646  7646 I bluedroid-qcom: get_profile_interface avrcp
08-31 15:25:44.742  7646  7646 V AudioManager: registerRemoteController: size of Media player list: 0
,08-31 15:25:44.744  7646  7646 E AudioManager: No RCC entry present to update,
08-31 15:25:44.744  7646  7646 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 15:25:44.748  7646  7646 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 15:25:44.750  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-31 15:25:44.750  7646  7646 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 15:25:44.753  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 15:25:44.838  1044  1059 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:25:44.838  1044  1059 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:25:44.954  1044  1963 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 15:25:44.962  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 15:25:44.967  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 15:25:44.967  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 15:25:44.967  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 15:25:44.967  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 15:25:44.968  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-31 15:25:44.968  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 15:25:44.968  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 15:25:44.968  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 15:25:44.968  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:25:44.968  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 15:25:44.968  7646  7646 I BluetoothA2dpServiceJni: classInitNative
08-31 15:25:44.968  7646  7646 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:25:44.968  7646  7646 D A2dpStateMachine: make
08-31 15:25:44.971  7646  7646 I bluedroid-qcom: get_profile_interface a2dp
,08-31 15:25:44.971  7646  7708 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 15:25:44.975  7646  7646 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 15:25:44.975  7646  7646 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter],
08-31 15:25:44.978  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:44.978  7646  7707 D A2dpStateMachine: Enter Disconnected: -2
08-31 15:25:44.981  7646  7646 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 15:25:44.985  7646  7646 D HidService: Received start request. Starting profile...
,08-31 15:25:44.985  7646  7646 I bluedroid-qcom: get_profile_interface hidhost
08-31 15:25:44.986  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:44.987  7646  7646 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:25:44.991  7646  7646 D HealthService: Received start request. Starting profile...
08-31 15:25:44.995  7646  7646 I bluedroid-qcom: get_profile_interface health
08-31 15:25:44.995  7646  7646 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:25:44.996  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:44.998  7646  7646 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:25:45.004  7646  7646 D PanService: Received start request. Starting profile...
08-31 15:25:45.004  7646  7646 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:25:45.004  7646  7646 I bluedroid-qcom: get_profile_interface pan
08-31 15:25:45.023  7646  7646 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 15:25:45.023  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
,08-31 15:25:45.027  7646  7646 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 15:25:45.046  7646  7646 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:25:45.048  7646  7646 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:25:45.048  7646  7646 D BtGatt.GattService: start()
08-31 15:25:45.048  7646  7646 I bluedroid-qcom: get_profile_interface gatt
08-31 15:25:45.048  7646  7646 D BtGatt.AdvertiseManager: advertise manager created
08-31 15:25:45.058  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:45.060  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:45.060  7646  7646 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 15:25:45.061  7646  7646 V BluetoothMapService: BluetoothMapBinder()
08-31 15:25:45.062  7646  7646 D BluetoothMapService: Received start request. Starting profile...
08-31 15:25:45.062  7646  7646 D BluetoothMapService: start()
08-31 15:25:45.073  7646  7646 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 15:25:45.074  7646  7646 D BluetoothMapEmailAppObserver: createReceiver()
,08-31 15:25:45.079  7646  7646 D BluetoothMapEmailAppObserver: initObservers()
08-31 15:25:45.079  7646  7646 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 15:25:45.094  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
,08-31 15:25:45.095  7646  7646 D HeadsetStateMachine: Proxy object connected
08-31 15:25:45.096  7646  7646 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 15:25:45.096  7646  7646 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 15:25:45.103  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:25:45.104  7646  7700 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 15:25:45.105  7646  7700 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 15:25:45.106  7646  7700 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 15:25:45.106  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:25:45.110  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 15:25:45.116  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:25:45.118  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:45.120  7646  7646 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 15:25:45.124  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 15:25:45.131  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 15:25:45.131  7646  7646 V BluetoothMapService: Handler(): got msg=1
08-31 15:25:45.133  7646  7679 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 15:25:45.133  7646  7679 I bluedroid-qcom: enable
08-31 15:25:45.134  7646  7722 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 15:25:45.134  7646  7722 I bt-btu  : btu_task pending for preload complete event
08-31 15:25:45.134  7646  7679 I bt_hci_bdroid: init
08-31 15:25:45.134  7646  7646 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:25:45.134  7646  7646 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:25:45.134  7646  7646 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:25:45.134  7646  7646 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:45.135  7646  7646 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 15:25:45.136  7646  7679 I bt_vendor: bt-vendor : init
08-31 15:25:45.136  7646  7679 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 15:25:45.136  7646  7679 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 15:25:45.136  7646  7679 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 15:25:45.136  7646  7679 D bt_userial_mct: userial_init
,08-31 15:25:45.139  7646  7679 D bt_hci_bdroid: set_power 1
08-31 15:25:45.139  7646  7679 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 15:25:45.140  7646  7679 I bt_vendor: Starting hciattach daemon
08-31 15:25:45.140  7646  7679 I bt_vendor: try to set true
08-31 15:25:45.128  7725  7725 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:45.128  7725  7725 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:45.168  7726  7726 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 15:25:45.236  7732  7732 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 15:25:45.262  7733  7733 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 15:25:45.288  7735  7735 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 15:25:45.300  7736  7736 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 15:25:45.312  7737  7737 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-31 15:25:45.324  7738  7738 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 15:25:45.346  7740  7740 I libmdmdetect: ESOC framework not supported
,08-31 15:25:45.348  7740  7740 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 15:25:45.358  7740  7740 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 15:25:45.358  7740  7740 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 15:25:45.358  7740  7740 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 15:25:45.358  7740  7740 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 15:25:45.358  7740  7740 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 15:25:45.358  7740  7740 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 15:25:45.358  7740  7740 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 15:25:45.398  7740  7741 E QC-QMI  : qmi_client [7740] 15: failed to locate client data
,08-31 15:25:45.405   480   480 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-31 15:25:45.405   480   480 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-31 15:25:45.458  7742  7742 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 15:25:45.487  7743  7743 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 15:25:45.542  7646  7679 I bt_vendor: bluetooth satus is on
,08-31 15:25:45.543  7646  7679 D bt_hci_bdroid: preload
08-31 15:25:45.543  7646  7724 D bt_userial_mct: userial_open(port:0)
08-31 15:25:45.543  7646  7724 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 15:25:45.547  7646  7724 I bt_vendor: Done intiailizing UART
,08-31 15:25:45.552  7646  7724 I bt_vendor: Done intiailizing UART
,08-31 15:25:45.552  7646  7724 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 15:25:45.553  7646  7724 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 15:25:45.553  7646  7722 I bt-btu  : btu_task received preload complete event
08-31 15:25:45.555  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 15:25:45.555  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-31 15:25:45.557  7646  7745 D bt_userial_mct: Entering userial_read_thread(),
,08-31 15:25:45.562  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003,
,08-31 15:25:45.570  7646  7722 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 15:25:45.570  7646  7722 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:25:45.570  7646  7722 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 15:25:45.570  7646  7722 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:25:45.570  7646  7722 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 15:25:45.570  7646  7722 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 15:25:45.570  7646  7722 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 15:25:45.571  7646  7722 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:25:45.571  7646  7722 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 15:25:45.571  7646  7722 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 15:25:45.571  7646  7722 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:25:45.573  7646  7722 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:25:45.573  7646  7722 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:25:45.586  7646  7722 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 15:25:45.586  7646  7722 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:25:45.586  7646  7722 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:25:45.646  7646  7722 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 15:25:45.646  7646  7722 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0179061 
08-31 15:25:45.646  7646  7722 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0179061 
,08-31 15:25:45.668  7646  7683 E bt-btif : Calling BTA_HhEnable
08-31 15:25:45.668  7646  7683 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 15:25:45.669  7646  7683 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 15:25:45.672  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 15:25:45.673  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 15:25:45.673  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 15:25:45.673  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 15:25:45.673  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 15:25:45.674  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 15:25:45.675  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 15:25:45.675  7646  7683 D BluetoothAdapterProperties: Name is: G3
08-31 15:25:45.678  7646  7683 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:25:45.678  7646  7683 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:25:45.678  7646  7683 D bt_hci_bdroid: postload
08-31 15:25:45.679  7646  7724 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:45.680  7646  7683 D bte_conf: Device ID record 1 : primary
08-31 15:25:45.680  7646  7683 D bte_conf:   vendorId            = 00c4
08-31 15:25:45.680  7646  7683 D bte_conf:   vendorIdSource      = 0001
08-31 15:25:45.680  7646  7683 D bte_conf:   product             = 13a1
08-31 15:25:45.680  7646  7683 D bte_conf:   version             = 1000
08-31 15:25:45.680  7646  7683 D bte_conf:   clientExecutableURL = 
08-31 15:25:45.680  7646  7683 D bte_conf:   serviceDescription  = 
08-31 15:25:45.680  7646  7683 D bte_conf:   documentationURL    = 
08-31 15:25:45.680  7646  7683 D bte_conf: bte_load_did_conf no section named DID2.
08-31 15:25:45.681  7646  7722 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-31 15:25:45.686  7646  7724 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:45.690  7646  7724 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:45.690  7646  7679 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 15:25:45.691  7646  7679 D BluetoothAdapterProperties: ScanMode =  20
08-31 15:25:45.691  7646  7679 D BluetoothAdapterProperties: State =  11
08-31 15:25:45.691  7646  7679 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 15:25:45.691  7646  7679 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 15:25:45.691  7646  7679 D BluetoothAdapterProperties: Setting state to 12
08-31 15:25:45.691  7646  7679 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 15:25:45.692  7646  7683 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 15:25:45.692  7646  7683 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 15:25:45.678  7750  7750 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:25:45.688  7750  7750 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:45.707  7646  7722 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:45.707  7646  7722 W bt-smp  : Plain text(LSB ~ MSB) = 1c 00 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:45.707  7646  7722 W bt-smp  : Encrypted text(LSB ~ MSB) = 24 fc ba 0a 69 c7 a5 40 af 60 8e 3b 85 fa 92 48 
08-31 15:25:45.707  7646  7724 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:25:45.707  7646  7722 W bt-btm  : Stopping oneshot timer
08-31 15:25:45.708  1044  1119 D BluetoothManagerService: Message: 60
08-31 15:25:45.708  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 15:25:45.708  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-31 15:25:45.711  7646  7745 E bt_mct  : hci lib postload completed
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:45.730  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:45.747  7646  7683 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:25:45.748  7646  7683 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 15:25:45.752  7646  7722 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:45.752  7646  7722 W bt-smp  : Plain text(LSB ~ MSB) = e6 a7 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:45.752  7646  7722 W bt-smp  : Encrypted text(LSB ~ MSB) = 68 8d 0b 79 23 a8 1e aa c0 4a 8c e0 a7 d9 86 00 
08-31 15:25:45.753  7646  7722 W bt-btm  : Stopping oneshot timer
08-31 15:25:45.757  7646  7679 I BluetoothAdapterState: Entering On State
08-31 15:25:45.758  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:25:45.762  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:45.773  7646  7722 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:45.773  7646  7722 W bt-smp  : Plain text(LSB ~ MSB) = 8b ae 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:45.774  7646  7722 W bt-smp  : Encrypted text(LSB ~ MSB) = bf 99 2b 57 41 a0 ce 49 37 f7 fc ef ae f5 43 a1 
08-31 15:25:45.774  7646  7722 W bt-btm  : Stopping oneshot timer
,08-31 15:25:45.794  7646  7679 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 15:25:45.794  7646  7679 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 15:25:45.794  7646  7679 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-31 15:25:45.800  7646  7679 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-31 15:25:45.801  7646  7722 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-31 15:25:45.801  7646  7722 W bt-smp  : Plain text(LSB ~ MSB) = 71 e1 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:45.801  7646  7722 W bt-smp  : Encrypted text(LSB ~ MSB) = 71 b5 14 05 f3 d0 bb e3 6c 65 6d 5f 7b 36 3f 89 
08-31 15:25:45.801  7646  7722 W bt-btm  : Stopping oneshot timer
08-31 15:25:45.805  1839  1839 D BluetoothHeadset: Proxy object connected
08-31 15:25:45.807  7646  7679 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-31 15:25:45.813  6955  7063 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:25:45.820  1839  2575 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:25:45.825  1839  1839 D BluetoothHeadset: Proxy object connected
08-31 15:25:45.826  6955  6973 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:25:45.826  6955  6973 D BluetoothPan: onBluetoothStateChange call bindService
08-31 15:25:45.830  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:25:45.830  7764  7764 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 15:25:45.831  1044  1044 D BluetoothA2dp: Proxy object connected
08-31 15:25:45.832  7646  7722 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:25:45.832  7646  7722 W bt-smp  : Plain text(LSB ~ MSB) = d9 da 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:25:45.832  7646  7722 W bt-smp  : Encrypted text(LSB ~ MSB) = 12 27 25 be d9 6e 36 aa bd 59 5d 75 1f ac ec f4 
08-31 15:25:45.832  7646  7722 W bt-btm  : Stopping oneshot timer
08-31 15:25:45.833  6955  6974 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:25:45.836  6955  6955 D BluetoothA2dp: Proxy object connected
08-31 15:25:45.836  6955  6955 D A2dpProfile: Bluetooth service connected
08-31 15:25:45.839  6955  6955 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:25:45.839  6955  6955 D PanProfile: Bluetooth service connected
08-31 15:25:45.840  6955  6973 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:25:45.842  6955  6955 D BluetoothHeadset: Proxy object connected
08-31 15:25:45.842  6955  6955 D HeadsetProfile: Bluetooth service connected
08-31 15:25:45.843  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:25:45.845  1839  1839 D BluetoothHeadset: Proxy object connected
,08-31 15:25:45.847  6955  7063 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 15:25:45.848  6955  6955 D BluetoothInputDevice: Proxy object connected
08-31 15:25:45.848  6955  6955 D HidProfile: Bluetooth service connected
08-31 15:25:45.850  6955  6973 D BluetoothMap: onBluetoothStateChange: up=true
08-31 15:25:45.853  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:25:45.854  6955  6955 D BluetoothMap: Proxy object connected
08-31 15:25:45.854  6955  6955 D MapProfile: Bluetooth service connected
08-31 15:25:45.854  6955  6955 D BluetoothMap: getConnectedDevices()
08-31 15:25:45.855  1044  1044 D BluetoothHeadset: Proxy object connected
08-31 15:25:45.855  1044  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 15:25:45.856  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 15:25:45.856  7646  7662 V BluetoothMapService: getConnectedDevices()
08-31 15:25:45.858  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-31 15:25:45.859  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:25:45.861  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:45.861  1928  2121 D LGBluetoothAPIService: Message: 1
08-31 15:25:45.861  1928  2121 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 15:25:45.863  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:45.865  1044  1119 D BluetoothManagerService: Message: 40
08-31 15:25:45.865  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 15:25:45.866  7646  7646 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:45.866  7646  7646 D BluetoothMapService: STATE_ON
08-31 15:25:45.868  1928  2121 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 15:25:45.869  6955  6955 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 15:25:45.870  6955  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:25:45.876  6955  6955 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:45.882  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
08-31 15:25:45.882  7646  7646 V BluetoothPbapService: Pbap Service onCreate
08-31 15:25:45.883  7646  7646 V BluetoothPbapService: Starting PBAP service
08-31 15:25:45.884  7646  7646 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 15:25:45.884  7646  7646 V BluetoothPbapService: Pbap Service onBind
08-31 15:25:45.885  6955  6955 D BluetoothPbap: Proxy object connected
08-31 15:25:45.885  6955  6955 D PbapServerProfile: Bluetooth service connected
08-31 15:25:45.885  7646  7646 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:45.886  7646  7646 V BluetoothPbapService: state: 12
08-31 15:25:45.886  7646  7646 V BluetoothMapService: Handler(): got msg=1
08-31 15:25:45.886  7646  7646 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 15:25:45.887  7646  7773 D BluetoothMapMasInstance: MAS initSocket()
08-31 15:25:45.888  7646  7773 D BluetoothMapMasInstance:   masId = 00
08-31 15:25:45.888  7646  7773 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 15:25:45.888  7646  7773 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 15:25:45.888  7646  7773 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 15:25:45.888  7646  7646 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-31 15:25:45.888  7646  7646 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 15:25:45.890  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 15:25:45.890  1044  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:45.890  1928  2121 D LGBluetoothAPIService: Message: 100
08-31 15:25:45.890  1928  2121 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 15:25:45.890  7646  7646 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:25:45.890  7646  7646 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:45.890  7646  7646 V BluetoothPbapReceiver: ***********state = 12
08-31 15:25:45.891  7646  7773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:45.892  7646  7646 V BluetoothPbapService: Handler(): got msg=1
08-31 15:25:45.892  7646  7646 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 15:25:45.893  7646  7773 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 15:25:45.893  7646  7773 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 15:25:45.893  7646  7773 D BluetoothMapMasInstance: Accepting socket connection...
08-31 15:25:45.893  7646  7774 V BluetoothPbapService: Pbap Service initSocket
08-31 15:25:45.894  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:45.894  2168  2168 D c       : Getting all permits...
08-31 15:25:45.894  2168  2168 D a       : Opening database...
08-31 15:25:45.894  1044  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:45.894  7646  7683 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:25:45.895  7646  7683 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 15:25:45.895  7646  7774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:45.897  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:45.898  2168  2168 D a       : Opening database auth.proximity.permit_store...
08-31 15:25:45.898  2168  2168 D a       : Closing database...
,08-31 15:25:45.900  7646  7774 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-31 15:25:45.900  7646  7774 V BluetoothPbapService: Succeed to create listening socket 
08-31 15:25:45.900  7646  7774 V BluetoothPbapService: Accepting socket connection...
08-31 15:25:45.911  6955  6955 D BluetoothPermissionRequest: onReceive
,08-31 15:25:45.914  6955  6955 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 15:25:45.916  6955  6955 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:25:45.919  7646  7646 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 15:25:45.920  7646  7646 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 15:25:45.927  7646  7646 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 15:25:45.952  7646  7646 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 15:25:45.953  7646  7646 V BtOppService: onCreate
,08-31 15:25:45.958  7646  7646 V BluetoothOppNotification: send message
,08-31 15:25:45.962  7646  7646 V BtOppService: Starting RfcommListener
08-31 15:25:45.969  7646  7646 D BluetoothOppPreference: Dumping Names:  
08-31 15:25:45.969  7646  7646 D BluetoothOppPreference: {}
08-31 15:25:45.969  7646  7646 D BluetoothOppPreference: Dumping Channels:  
08-31 15:25:45.969  7646  7646 D BluetoothOppPreference: {}
08-31 15:25:45.972  7646  7646 V BtOppService: onStartCommand
,08-31 15:25:45.978  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:45.978  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 15:25:45.983  7646  7646 V BluetoothOppNotification: new notify threadi!
08-31 15:25:45.984  7646  7783 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-31 15:25:45.985  7646  7780 V BtOppService: Deleted complete outbound shares, number =  0
08-31 15:25:45.985  7646  7646 V BluetoothOppNotification: send delay message
08-31 15:25:45.986  7646  7783 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 15:25:45.986  7646  7646 V BtOppService: start RfcommListener
08-31 15:25:45.986  7646  7784 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 15:25:45.989  7646  7780 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 15:25:45.991  7646  7646 V BtOppService: RfcommListener started
08-31 15:25:45.991  7646  7785 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 15:25:45.992  1044  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:45.993  7646  7785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:45.994  7646  7785 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-31 15:25:45.995  7646  7785 V BtOppRfcommListener: Started RFCOMM listener....
08-31 15:25:45.995  7646  7785 I BtOppRfcommListener: Accept thread started.
08-31 15:25:45.995  7646  7785 V BtOppRfcommListener: Accepting connection...
08-31 15:25:45.996  7646  7780 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-31 15:25:46.017  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
,08-31 15:25:46.017  7646  7646 V BluetoothFtpService: Ftp Service onCreate
08-31 15:25:46.017  7646  7646 I BluetoothFtpService: Ftp Service onCreate
08-31 15:25:46.017  7646  7646 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:25:46.018  7646  7646 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:46.018  7646  7646 V BluetoothFtpService: Starting Listening on sockets
08-31 15:25:46.018  7646  7646 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:25:46.018  7646  7646 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:25:46.018  7646  7646 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:25:46.018  7646  7646 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:46.018  7646  7646 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 15:25:46.019  7646  7646 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 15:25:46.022  7646  7646 V BtOppService: ContentObserver received notification
08-31 15:25:46.022  7646  7646 V BtOppService: ContentObserver received notification
08-31 15:25:46.022  7646  7646 V BluetoothFtpService: Handler(): got msg=1
08-31 15:25:46.022  7646  7646 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 15:25:46.023  7646  7646 V BluetoothFtpService: Ftp Service initSocket
08-31 15:25:46.029  1044  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:46.029  7646  7646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:25:46.031  7646  7646 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-31 15:25:46.031  7646  7646 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 15:25:46.033  7646  7786 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 15:25:46.052  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32ab84b0
,08-31 15:25:46.052  7646  7646 V BluetoothSapService: Sap Service onCreate
08-31 15:25:46.055  7646  7646 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:46.055  7646  7646 V BluetoothSapService: state: 12
,08-31 15:25:46.055  7646  7646 V BluetoothSapService: Starting SAP server process
08-31 15:25:46.057  7646  7646 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 15:25:46.048  7787  7787 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:46.048  7787  7787 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:46.059  7646  7788 V BluetoothSapService: Sap Service initRfcommSocket
08-31 15:25:46.059  1044  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:46.060  7646  7788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:46.062  7646  7788 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 15:25:46.062  7646  7788 V BluetoothSapService: Succeed to create listening socket 
08-31 15:25:46.062  7646  7788 V BluetoothSapService: Accepting socket connection...
08-31 15:25:46.070  7787  7787 V BT_SAP  : Event pipe created
08-31 15:25:46.070  7787  7787 V BT_SAP  : create_server_socket qcom.sap.server
08-31 15:25:46.070  7787  7787 V BT_SAP  : created socket fd 6
,08-31 15:25:46.122  1044  1060 I art     : Explicit concurrent mark sweep GC freed 32376(1598KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.517ms total 132.981ms
,08-31 15:25:46.123  7646  7783 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e9eb8b1 on behalf of 
08-31 15:25:46.124  7646  7780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fc0c196 on behalf of 
08-31 15:25:46.124  7646  7783 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 15:25:46.124  7646  7783 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-31 15:25:46.126  7646  7784 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30125117 on behalf of 
08-31 15:25:46.129  7646  7784 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 15:25:46.130  7646  7783 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b4bb904 on behalf of 
08-31 15:25:46.130  7646  7783 V BluetoothOppNotification: update too frequent, put in queue
08-31 15:25:46.131  7646  7783 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 15:25:46.132  7646  7784 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:46.134  7646  7784 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eb52eed on behalf of 
08-31 15:25:46.136  7646  7784 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 15:25:46.140  7646  7784 V BluetoothOppNotification: outbound notification was removed.
08-31 15:25:46.140  7646  7784 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:46.142  7646  7784 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fbf6122 on behalf of 
08-31 15:25:46.143  7646  7784 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 15:25:46.146  7646  7784 V BluetoothOppNotification: inbound notification was removed.
08-31 15:25:46.146  7646  7784 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 15:25:46.148  7646  7784 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2660e7b3 on behalf of 
,08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:46.555  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:46.568  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:46.572  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:46.572  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39994dc2 added. We now have 8 listener(s)
08-31 15:25:46.572  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:46.579  1044  2036 D WifiServiceImplEx: setWifiEnabled: false pid=6699, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:25:46.579  1044  2036 D WifiService: setWifiEnabled: false pid=6699, uid=10118
08-31 15:25:46.579  1044  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:25:46.584  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:46.585  1044  1764 D WifiServiceImplEx: setWifiEnabled: true pid=6699, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:25:46.586  1044  1764 D WifiService: setWifiEnabled: true pid=6699, uid=10118
08-31 15:25:46.586  1044  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:25:46.609  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 15:25:46.609  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 15:25:46.609  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-31 15:25:46.611  1044  1425 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 15:25:46.611  1044  1425 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 15:25:46.613  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-31 15:25:46.614  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 15:25:46.614  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 15:25:46.614  1044  1425 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 15:25:46.614  1044  1425 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-31 15:25:46.614  1044  1425 E WifiHW  : unknown target_country: EU , set to default
08-31 15:25:46.614  1044  1425 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 15:25:46.614  1044  1425 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-31 15:25:46.614  1044  1425 I WifiUtil: gEnableBmps=1
08-31 15:25:47.003  7646  7646 V BluetoothOppNotification: new notify threadi!
,08-31 15:25:47.016  7646  7646 V BluetoothOppNotification: send delay message
08-31 15:25:47.024  7646  7801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-31 15:25:47.044  7646  7801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@54d6170 on behalf of 
08-31 15:25:47.044  7646  7801 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 15:25:47.049  7646  7801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:47.050  7646  7801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2242cce9 on behalf of 
08-31 15:25:47.051  7646  7801 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 15:25:47.052  7646  7801 V BluetoothOppNotification: outbound notification was removed.
08-31 15:25:47.052  7646  7801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:25:47.053  7646  7801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16166d6e on behalf of 
08-31 15:25:47.054  7646  7801 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 15:25:47.056  7646  7801 V BluetoothOppNotification: inbound notification was removed.
08-31 15:25:47.056  7646  7801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 15:25:47.057  7646  7801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@df84c0f on behalf of 
,08-31 15:25:47.222   308   894 D SoftapController: Softap fwReload - Ok
,08-31 15:25:47.230  1044  1425 E NetdConnector: NDC Command {66 softap fwreload wlan0 STA} took too long (612ms)
08-31 15:25:47.239   308   894 D CommandListener: Setting iface cfg
08-31 15:25:47.239   308   894 D CommandListener: Trying to bring down wlan0
,08-31 15:25:47.242   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:25:47.245  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:47.245  1044  1119 D Tethering: InitialState.processMessage what=4
08-31 15:25:47.245  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:47.258  1044  1425 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 15:25:47.248  7809  7809 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:47.268  7809  7809 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:25:47.287  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:47.287  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:47.287  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:25:47.287  1044  1425 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 15:25:47.287  1044  1425 D WifiMonitor: connecting to supplicant
08-31 15:25:47.333  7809  7809 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 15:25:47.343  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 15:25:47.344  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 15:25:47.346  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:47.346  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:25:47.346  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:25:47.346  6955  6955 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:25:47.346  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:47.353  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:47.356  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:25:47.358  6955  6955 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:25:47.359  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:25:47.359  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:25:47.359  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:25:47.359  6955  6955 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:25:47.359  6955  6955 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 15:25:47.363  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:47.363  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:25:47.363  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:25:47.363  6955  6955 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:25:47.364  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:25:47.365  6955  6955 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:25:47.365  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:25:47.365  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:25:47.365  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:25:47.365  6955  6955 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:25:47.365  6955  6955 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 15:25:47.371  7809  7809 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 15:25:47.371  7809  7809 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 15:25:47.374  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:47.378  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:47.384  7064  7827 W FormManager: Network not available. Please check & try again.
08-31 15:25:47.384  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:25:47.395  7064  7828 V FormManager: Network unavailable.
,08-31 15:25:47.398  7064  7828 V FormManager: Network unavailable.
08-31 15:25:47.444  7809  7809 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 15:25:47.525  7809  7809 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 15:25:47.546  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-31 15:25:47.547  7809  7809 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 15:25:47.547  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 15:25:47.547  7809  7809 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 15:25:47.547  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 15:25:47.548  1044  7829 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 15:25:47.548  1044  1425 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 15:25:47.548  1044  7829 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 15:25:47.548  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 15:25:47.548  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 15:25:47.548  1044  1425 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:47.548  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 15:25:47.549  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 15:25:47.549  1044  1425 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:47.549  1044  1425 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 15:25:47.549  1044  1425 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 15:25:47.550  1044  1425 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 15:25:47.551  1044  1425 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 15:25:47.551  1044  1425 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 15:25:47.551  1044  1425 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:25:47.551  1044  1425 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:25:47.551  1044  1425 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:25:47.552  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:47.552  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:47.552  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:47.552  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:47.552  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:25:47.553  1044  1425 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 15:25:47.553  1044  1425 D WifiNative-wlan0: SET update_config 1: returned true
08-31 15:25:47.553  1044  1425 D WifiConfigStore: Loading config and enabling all networks 
08-31 15:25:47.553  1044  1425 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 15:25:47.554  1044  1425 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 15:25:47.555  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:47.556  1928  1928 D WfdService: Waiting for WifiP2p enabling
08-31 15:25:47.561  1044  1425 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:47.565  6699  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:47.567  6699  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:47.569  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 15:25:47.569  1044  1455 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 15:25:47.573  1044  1425 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 15:25:47.573  1044  1425 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:25:47.578  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:25:47.582  1044  1425 D WifiStateMachine: enableVerboseLogging : level 2
08-31 15:25:47.582  1044  1425 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 15:25:47.583  1044  1425 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 15:25:47.583  1044  1425 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 15:25:47.583  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:47.584  1044  1425 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 15:25:47.584  1044  1425 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 15:25:47.584  1044  1425 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 15:25:47.584  1044  1425 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 15:25:47.585  1044  1425 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 15:25:47.585  1044  1425 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 15:25:47.585  1044  1425 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 15:25:47.585  1044  1425 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 15:25:47.586  1044  1425 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 15:25:47.586  1044  1425 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 15:25:47.587  1044  1425 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 15:25:47.588  1044  1425 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:25:47.588  1044  1425 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 15:25:47.588  1044  1425 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 15:25:47.588  1044  1425 D WifiNative-HAL: Setting external_sim to 1
08-31 15:25:47.588  1044  1425 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 15:25:47.588  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-31 15:25:47.588  1928  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 15:25:47.589  1928  2299 D WfdsService: Set the WFDS Monitor: true
08-31 15:25:47.589  1928  2299 D WfdsMonitor: WfdsMonitorThread create
08-31 15:25:47.589  1044  1425 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 15:25:47.589  1044  1425 I WifiNative-HAL: startHal
08-31 15:25:47.589  1044  1425 D wifi    : setting scan oui 0xaf664220
08-31 15:25:47.590  1044  1425 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:25:47.590  1044  1425 I WifiNative-HAL: startHal
08-31 15:25:47.590  1044  1425 D wifi    : setting scan oui 0xaf664220
08-31 15:25:47.590  1044  1425 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 15:25:47.591  1044  1425 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 15:25:47.591  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 15:25:47.591  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 15:25:47.592  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:47.592  1044  1425 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 15:25:47.592  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:25:47.593  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-31 15:25:47.593  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:25:47.593  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 15:25:47.593  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 15:25:47.594  1928  2299 D WfdsMonitor: WFDS Monitor is created and started
08-31 15:25:47.594  1928  2299 D WfdsService: WiFi: Supplicant connection re-established
08-31 15:25:47.594  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 15:25:47.594  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:25:47.594  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:25:47.595  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:25:47.595  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:25:47.595  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 15:25:47.595  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:25:47.595  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 15:25:47.595  7809  7809 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 15:25:47.596  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 15:25:47.596  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:25:47.596  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:25:47.596  1044  1425 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:25:47.597  1044  1425 E WifiNative: : [144,742,803 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 15:25:47.597  1044  1425 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 15:25:47.597  1044  1425 D WifiNative-wlan0: RECONNECT: returned true
08-31 15:25:47.597  1044  1425 D WifiNative-wlan0: doString: [STATUS]
08-31 15:25:47.598  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:25:47.598  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 15:25:47.598  1044  1425 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 15:25:47.598  1044  1425 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:25:47.598  1044  1425 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:25:47.599  1044  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.600  7064  7832 W FormManager: Network not available. Please check & try again.
08-31 15:25:47.601   308   894 D CommandListener: Setting iface cfg
08-31 15:25:47.601   308   894 D CommandListener: Trying to bring up p2p0
08-31 15:25:47.601  1044  1375 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 15:25:47.601  1044  1375 D LGWifiP2pService: P2pEnablingState
,08-31 15:25:47.601  1044  1375 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.601  1044  1375 D LGWifiP2pService: P2p socket connection successful
08-31 15:25:47.601  1044  1375 D LGWifiP2pService: P2pEnabledState
08-31 15:25:47.601  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 15:25:47.602  1044  1044 D RttService: SCAN_AVAILABLE : 3
08-31 15:25:47.602  1044  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.602  1044  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.602  1044  1542 I WifiNative-HAL: startHal
08-31 15:25:47.602  1044  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf664220
08-31 15:25:47.602  1044  1542 D wifi    : failed to get capabilities : -3
08-31 15:25:47.602  1044  1542 E WifiScanningService: could not get scan capabilities
08-31 15:25:47.602  1928  7834 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 15:25:47.603  1044  1375 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 15:25:47.603  1044  1425 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 15:25:47.603  1928  7834 E CtrlSupplicant: Succeed to open control connection
08-31 15:25:47.603  1928  7834 E CtrlSupplicant: Succeed to open monitor connection
08-31 15:25:47.603  1044  1425 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 15:25:47.604  1044  1425 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 15:25:47.604  1044  1425 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 15:25:47.605  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 15:25:47.605  1928  1928 D WfdsService: WifiP2pState is changed : true
08-31 15:25:47.605  1044  1425 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 15:25:47.605  1928  2299 D WfdsService: Receive the WFDS_ENABLE Method
08-31 15:25:47.605  1928  2299 D WfdsService: Set the WFDS Monitor: true
08-31 15:25:47.605  1928  7834 D WfdsMonitor: Supplicant connection established
08-31 15:25:47.605  1928  2299 D WfdsService: Connected to the supplicant for wfds
08-31 15:25:47.605  1928  2299 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 15:25:47.605  1044  1425 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 15:25:47.605  7809  7809 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 15:25:47.605  1928  2299 D WfdsService: selectPreferredScanChannel [36]
08-31 15:25:47.605  1928  2299 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 15:25:47.605  1928  2299 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-31 15:25:47.605  1044  1425 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 15:25:47.606  1044  1425 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 15:25:47.606  7809  7809 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 15:25:47.606  1044  1375 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 15:25:47.606  1044  1375 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 15:25:47.607  1044  1375 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 15:25:47.607  1044  1425 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-31 15:25:47.608  1044  1425 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-31 15:25:47.609  1044  1425 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 15:25:47.609  1044  1425 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 15:25:47.609  7809  7809 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 15:25:47.609  1044  1425 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 15:25:47.610  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 15:25:47.610  1044  1425 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 15:25:47.610  1928  1928 D WfdsService: isConnected: false
08-31 15:25:47.611  1044  1425 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 15:25:47.611  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 15:25:47.611  1044  1375 D WifiNative-p2p0: SET device_name G3: returned true
08-31 15:25:47.612  1044  1375 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 15:25:47.612  1044  1375 D LGWifiP2pService: before postfix = G3
08-31 15:25:47.612  1044  1375 D WifiServerServiceExt: postfix byte check : 2
08-31 15:25:47.612  1044  1375 D LGWifiP2pService: after postfix = G3
08-31 15:25:47.612  1044  1375 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 15:25:47.614  7064  7833 V FormManager: Network unavailable.
08-31 15:25:47.615  1044  1375 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 15:25:47.615  1044  1375 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 15:25:47.616  1044  1375 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 15:25:47.616  1044  1375 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 15:25:47.616  1044  1375 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 15:25:47.617  1044  1375 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 15:25:47.617  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:25:47.617  7809  7809 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.618  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:25:47.618  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.618  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.618  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.618  7809  7809 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:25:47.618  7809  7809 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.618  1928  7834 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.619  1044  7829 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.619  1044  7829 E WifiMonitor: WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.619  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.619  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.619  7809  7809 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.619  1928  7834 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.619  1044  7829 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.619  1044  1425 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 15:25:47.619  1044  7829 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.619  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE ,init=DRIVER type=WORLD
08-31 15:25:47.619  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.620  1044  1425 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:25:47.620  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:47.620  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:25:47.620  1044  1425 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:25:47.620  1044  1425 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:25:47.620  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 15:25:47.620  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 15:25:47.620  7809  7809 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:47.621  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:47.621  1044  1425 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 15:25:47.621  1044  1425 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 15:25:47.622  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 15:25:47.622  1044  1425 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 15:25:47.622  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:47.622  1044  1425 D WifiNative-wlan0: doBoolean: SCAN
08-31 15:25:47.622  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:47.622  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:25:47.622  1044  1425 D WifiNative-wlan0: SCAN: returned false
08-31 15:25:47.623  1044  1425 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=144769  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:25:47.623  1044  1375 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 15:25:47.623  1044  1375 D WifiNative-HAL: p2pGetDeviceAddress
08-31 15:25:47.623  1044  1375 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-31 15:25:47.624  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=144771  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-31 15:25:47.625  1044  1425 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:47.625  1044  1425 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:47.625  1044  1425 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:47.626  1044  1375 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 15:25:47.626  1044  1375 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 15:25:47.626  1044  1375 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 15:25:47.626  1044  1375 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 15:25:47.627  1044  1375 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 15:25:47.627  1044  1375 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 15:25:47.627  1044  1375 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 15:25:47.627  1044  1375 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:47.627  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:47.628  1044  1425 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:47.628  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:25:47.629  1044  1425 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:25:47.629  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 15:25:47.629  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 15:25:47.629  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:47.629  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:47.629  1928  1928 D WfdsService: Update P2p Interface State: 3
08-31 15:25:47.629  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 15:25:47.630  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:47.630  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:47.631  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:47.631  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:47.632  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:47.632  1044  1044 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 15:25:47.635,  1044  1375 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 15:25:47.635  1044  1375 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 15:25:47.635  6699  6809 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 15:25:47.636  1044  1375 D LGWifiP2pService: InactiveState
08-31 15:25:47.636  1044  1375 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.636  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.636  1044  1375 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 15:25:47.636  6699  6809 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 15:25:47.636  7064  7833 V FormManager: Network unavailable.
08-31 15:25:47.637  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:25:47.637  7809  7809 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.637  1928  7834 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:25:47.638  7809  7809 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:25:47.638  7809  7809 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.638  1928  7834 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.638  1044  1375 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 15:25:47.638  6699  6809 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34722a74 Bundle[{}]
08-31 15:25:47.638  1044  1375 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.638  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.638  1044  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.638  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  7809  7809 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  1928  7834 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  6699  6809 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:47.639  1044  1375 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  6699  6809 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  1044  1375 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:47.639  1044  1044 E WifiServerServiceExt: No p2p device connected
08-31 15:25:47.640  1044  7829 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:25:47.640  1044  7829 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.640  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.640  6699  6809 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 15:25:47.640  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:25:47.640  1044  7829 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.640  1044  7829 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 15:25:47.640  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.640  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.640  1044  7829 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:25:47.640  1044  7829 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.640  1044  7829 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.640  1044  7829 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:25:47.640  6699  6809 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 15:25:47.641  1928  2299 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 15:25:47.641  6699  6809 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 15:25:47.642  6699  6809 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 15:25:47.643  7427  7427 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 15:25:47.643  7427  7427 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 15:25:47.643  7427  7427 V [BNRBootReceiver]: Boot Receiver Return
08-31 15:25:47.645  4328  7835 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:25:47.648  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:47.649  6699  6809 I System.out: Running OutgoingSocketThread
08-31 15:25:47.654  6699  7837 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
08-31 15:25:47.654  4328  7836 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:25:47.654  4328  7836 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:25:47.655  6699  7837 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60010
,08-31 15:25:47.655  6699  7837 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 15:25:47.658  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:47.663  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:25:47.667  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:25:47.668  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:47.669  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:25:48.201  7809  7809 E wpa_supplicant: USIM:  scard_init function
08-31 15:25:48.202  7809  7809 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 15:25:48.212  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-31 15:25:48.213  1044  7829 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 15:25:48.213  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 15:25:48.213  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: WPS-AP-AVAILABLE 
08-31 15:25:48.213  1044  7829 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 15:25:48.213  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:25:48.213  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 15:25:48.214  1044  1425 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 15:25:48.215  1044  1425 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 15:25:48.215  1044  1425 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 15:25:48.215  1044  1425 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 15:25:48.215  1044  1425 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 15:25:48.235  1044  1425 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=145381  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 15:25:48.245  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.245  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.245  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 15:25:48.246  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.246  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.248  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=145394  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 15:25:48.249  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:48.259  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.260  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.260  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.260  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.260  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 15:25:48.261  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:48.261  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 15:25:48.263  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:48.271  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 15:25:48.283  6955  6955 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 15:25:48.287  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.299  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:48.307  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.315  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:25:48.319  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.320  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:25:48.325  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.334  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:48.342  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.349  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.350  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.350  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:25:48.363  7809  7809 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 15:25:48.373  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 15:25:48.374  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 15:25:48.374  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 15:25:48.374  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 15:25:48.374  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:25:48.374  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:25:48.375  1044  1425 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=145521  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 15:25:48.376  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=145522  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 15:25:48.377  1044  1425 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=145523
08-31 15:25:48.377  1044  1425 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=145524
08-31 15:25:48.377  7809  7809 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 15:25:48.377  7809  7809 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:25:48.378  1044  1425 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=145524
08-31 15:25:48.378  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:25:48.378  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:25:48.378  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 15:25:48.378  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:25:48.378  1044  7829 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:25:48.378  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=145524
08-31 15:25:48.378  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 15:25:48.378  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:25:48.378  1044  7829 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:25:48.378  1044  1425 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=145525
08-31 15:25:48.380  1044  1425 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=145526  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 15:25:48.382  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:25:48.383  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:25:48.386  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.386  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.386  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 15:25:48.387  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.387  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.389  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.389  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 15:25:48.389  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:48.400  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=145546  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 15:25:48.401  1044  1425 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=145547  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 15:25:48.402  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=145548  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 15:25:48.402  1044  1425 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=145549
08-31 15:25:48.403  1044  1425 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=145549
,08-31 15:25:48.403  1044  1425 D WifiNative-wlan0: doString: [STATUS]
08-31 15:25:48.404  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.404  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.404  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 15:25:48.404  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:48.404  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 15:25:48.405  1044  1425 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 15:25:48.406  1044  7829 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:25:48.406  1044  7829 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:25:48.407  1044  1425 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 15:25:48.411  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.412  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.413  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:48.413  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:48.427  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.438  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.438  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.438  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:25:48.441  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:48.441  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:25:48.442  6955  6955 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:25:48.442  6955  6955 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:25:48.442  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:25:48.443  6955  6955 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:25:48.444  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 15:25:48.444  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:25:48.444  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:25:48.444  6955  6955 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:25:48.444  6955  6955 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 15:25:48.444  6955  6955 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 15:25:48.448  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.454  1044  1425 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 15:25:48.454  1044  1425 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 15:25:48.460  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:48.463  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.463  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.463  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 15:25:48.463  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.463  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.465  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:48.467  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.467  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.467  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.467  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 15:25:48.467  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.468  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:48.471  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.471  1044  1425 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 15:25:48.471  1044  1425 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:25:48.471  1044  1425 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:25:48.472  1044  1484 D ConnectivityService: Got NetworkAgent Messenger
08-31 15:25:48.472  1044  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 15:25:48.472  1044  1484 D ConnectivityService: NetworkAgent connected
08-31 15:25:48.472  1044  1425 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:25:48.472  1044  1425 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:25:48.477  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.477  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.478  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:25:48.481  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:25:48.484  1044  1425 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:25:48.484  1044  1425 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:25:48.484  1044  1425 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:25:48.484  1044  1425 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:25:48.484  1044  1425 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:25:48.491  1044  1425 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:25:48.492  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:48.492   308   894 D CommandListener: Setting iface cfg
08-31 15:25:48.494  1044  1425 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 15:25:48.494  1044  7865 D DhcpStateMachine: StoppedState
08-31 15:25:48.494  1044  7865 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.494  1044  7865 D DhcpStateMachine: WaitBeforeStartState
08-31 15:25:48.495  1044  1425 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=145641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:25:48.495  1044  1425 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=145641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:25:48.495  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=145641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:25:48.496  1044  1425 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:48.496  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:48.496  1044  1425 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:48.496  1044  1425 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:48.497  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:25:48.497  1044  1425 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 15:25:48.497  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:48.497  1044  1044 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 15:25:48.498  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.499  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:48.499  1044  1044 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 15:25:48.500  1044  1425 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=145647  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:25:48.501  1044  1425 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=145647  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:25:48.502  1044  1425 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=145648  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:25:48.503  1044  1425 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:99572] from screen [on:0 period:-523834025] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 15:25:48.504  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-523834024] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 15:25:48.504  1044  1425 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 15:25:48.510  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.510  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:48.510  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.510  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:25:48.510  1044  1484 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-31 15:25:48.511  1044  1425 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 15:25:48.513  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.513  1044  1425 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.513  1044  1425 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.514  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.514  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.514  1044  1425 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.515  1044  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 15:25:48.515  1044  1425 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-31 15:25:48.516  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-31 15:25:48.516  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 15:25:48.516  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 15:25:48.517  1044  1425 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 15:25:48.517  1044  1425 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 15:25:48.517  1044  1425 D WifiNative-wlan0: SET ps 0: returned true
08-31 15:25:48.517  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 15:25:48.517  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 15:25:48.518  1044  1425 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 15:25:48.518  1044  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e403e36 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.518  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e403e36 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.518  1044  7865 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.518  1044  7865 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 15:25:48.518  1044  1425 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 15:25:48.518  1044  1425 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 15:25:48.519  1044  1425 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 15:25:48.519   308   894 D CommandListener: Setting iface cfg
08-31 15:25:48.520   308   894 D CommandListener: Trying to bring up wlan0
08-31 15:25:48.521  1044  1425 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 15:25:48.522  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:25:48.523  1044  1425 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 15:25:48.525  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:25:48.525  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 15:25:48.525  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.526  1044  1425 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.526  1044  1425 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 15:25:48.527  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.527  1044  1425 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:25:48.528  1044  1425 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 15:25:48.528  1044  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 15:25:48.528  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 15:25:48.528  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:25:48.528  1044  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.528  1044  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.528  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:25:48.529  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.529  1044  1425 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:25:48.529  1044  1425 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 15:25:48.529  7809  7809 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 15:25:48.530  1044  1425 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 15:25:48.530  1044  1425 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:25:48.536  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.536  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.537  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:25:48.547  1044  1425 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:25:48.548  1044  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-31 15:25:48.548  1044  1425 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 15:25:48.549  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 15:25:48.549  1044  1425 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 15:25:48.549  1044  1484 D ConnectivityService: ignoring duplicate network state non-change
08-31 15:25:48.552  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.552  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.554  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:48.554  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.554  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.554  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 15:25:48.558  1044  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 15:25:48.559  1044  1484 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 15:25:48.562  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.563  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.563  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 15:25:48.564  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 15:25:48.565  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.566  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 15:25:48.570  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.570  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.570  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 15:25:48.573  1044  1425 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 15:25:48.576  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.576  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:25:48.576  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 15:25:48.589  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:25:48.589  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:48.589  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 15:25:48.589  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:48.592  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.593  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 15:25:48.593  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:25:48.598  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:48.598  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 15:25:48.598  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:48.604  1044  1484 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 15:25:48.604  1044  1484 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 15:25:48.606  1044  1484 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-31 15:25:48.608   308   894 E Netd    : netlink response contains error (File exists)
08-31 15:25:48.608  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:48.608  1044  1484 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-31 15:25:48.609  1044  1484 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 15:25:48.609  1044  1484 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 15:25:48.609  1044  1484 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 15:25:48.611  1044  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 15:25:48.611  1044  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 15:25:48.613  1044  1484 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 15:25:48.613  1044  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 15:25:48.613  1044  7864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.613  1044  7864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 15:25:48.613  1044  7864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:48.613  1044  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:48.613  1044  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:25:48.613  1044  7864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 15:25:48.613  1044  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 15:25:48.614  1044  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:48.614  1044  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 15:25:48.614  1044  1484 D ConnectivityService: currentScore = 0, newScore = 20
08-31 15:25:48.614  1044  1484 D ConnectivityService:    accepting network in place of null
08-31 15:25:48.614  1044  1484 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:48.615  1044  1425 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:48.615  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:48.615  1044  1425 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:48.615  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:25:48.616   308  7870 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 15:25:48.617  1044  1484 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvision,ingNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 15:25:48.617  1044  1484 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 15:25:48.617  1044  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:25:48.617  1044  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:48.618  1044  1044 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 15:25:48.619  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:25:48.619  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:25:48.619  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-31 15:25:48.622  1044  1484 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 15:25:48.622  1044  1484 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 15:25:48.624  1044  1484 D ConnectivityService: validation of new default Network = false
08-31 15:25:48.624  1044  1484 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 15:25:48.624  1044  1484 D DSQN    : enableDataServiceNotify 
08-31 15:25:48.624  1044  1484 D DSQN    : start dsqn bin
08-31 15:25:48.633  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:25:48.635  1044  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 15:25:48.635  1044  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:48.635  1044  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:25:48.635  1044  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:25:48.628  7871  7871 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:48.628  7871  7871 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:48.637  1589  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 15:25:48.650  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.651  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.652  1044  1374 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 15:25:48.654  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:25:48.655  6699  6809 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
08-31 15:25:48.655  6699  6809 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
08-31 15:25:48.655  7871  7871 E DSQN    : DSQN ssw
08-31 15:25:48.658  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:25:48.659  6699  6809 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
08-31 15:25:48.660  6699  6809 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 15:25:48.660  6699  6809 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
08-31 15:25:48.664  1804  7872 I CheckinService: active receiver: enabled
08-31 15:25:48.664  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.664  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220367d3 added. We now have 2 listener(s)
,08-31 15:25:48.679  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:48.679  1044  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.680  1804  7872 I CheckinService: Preparing to send checkin request
08-31 15:25:48.680  1804  7872 I EventLogService: Accumulating logs since 1472649862390
08-31 15:25:48.682  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.682  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.682  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.682  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.682  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2547af10 added. We now have 9 listener(s)
08-31 15:25:48.682  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.683  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:25:48.685  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:48.691  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:48.693  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.693  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:48.694  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.694  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b2840e added. We now have 3 listener(s)
08-31 15:25:48.695  1044  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.695  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:48.695  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:25:48.697  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:48.697  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.698  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:25:48.699  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.699  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.700  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.700  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.700  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2212ae2f added. We now have 10 listener(s)
08-31 15:25:48.700  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:48.700  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:48.700  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:48.700  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:48.701  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.701  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.701  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.701  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.701  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220367d3 removed from the list
08-31 15:25:48.701  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.701  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2547af10 removed from the list
08-31 15:25:48.701  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:48.701  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.701  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.701  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.701  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.704  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.704  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.704  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.704  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2547af10 not in the list
08-31 15:25:48.704  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.704  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.705  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.705  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.705  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.705  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2212ae2f removed from the list
08-31 15:25:48.705  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.705  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.706  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.706  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting ,down...
08-31 15:25:48.706  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b2840e removed from the list
08-31 15:25:48.706  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.706  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a60ac3c added. We now have 2 listener(s)
08-31 15:25:48.707  1044  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.709  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.709  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.709  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.709  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.709  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220bcdc5 added. We now have 9 listener(s)
08-31 15:25:48.709  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.710  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:25:48.712  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:48.716  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:48.718  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.718  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:48.718  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.718  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2525fe4b added. We now have 3 listener(s)
08-31 15:25:48.718  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.719  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.719  1044  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.720  1044  7865 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 15:25:48.721  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.721  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.721  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.721  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.721  1044  7865 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 15:25:48.721  1044  7865 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 15:25:48.721  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1daa5028 added. We now have 10 listener(s)
08-31 15:25:48.721  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.721  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:48.721  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:48.721  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:48.721  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a n,ew listener
08-31 15:25:48.721  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:25:48.723  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:25:48.708  7877  7877 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:25:48.708  7877  7877 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:25:48.726  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.728  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:25:48.728  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.729  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.729  1044  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.731  1804  7872 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-31 15:25:48.733  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:25:48.733  7877  7877 I dhcpcd  : version 5.5.6 starting
08-31 15:25:48.735  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 15:25:48.735  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:25:48.735  7877  7877 E dhcpcd  : get_duid: m
,08-31 15:25:48.735  7877  7877 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 15:25:48.735  7877  7877 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 15:25:48.736  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:25:48.738  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.739  6699  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:25:48.739  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:48.739  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:48.741  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:48.741  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:48.741  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:48.741  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.741  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.741  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.741  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.741  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:48.741  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a60ac3c removed from the list
08-31 15:25:48.741  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.741  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220bcdc5 removed from the list
08-31 15:25:48.741  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:48.741  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.745  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.745  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.745  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.745  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:48.745  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.745  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.745  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220bcdc5 not in the list
08-31 15:25:48.745  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already r,emoved
08-31 15:25:48.746  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.747  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:25:48.748  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:48.748  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:48.748  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.748  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.748  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1daa5028 removed from the list
08-31 15:25:48.748  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.748  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.748  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.748  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.748  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2525fe4b removed from the list
08-31 15:25:48.748  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.749  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16d43427 added. We now have 2 listener(s)
08-31 15:25:48.749  1044  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.752  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.752  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.752  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.753  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.753  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.753  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6846d4 added. We now have 9 listener(s)
08-31 15:25:48.753  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.753  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:25:48.758  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.759  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:48.760  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.761  7022  7022 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 15:25:48.762  7022  7022 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:48.762  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:48.763  7022  7022 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 15:25:48.763  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:25:48.763  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:48.763  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.763  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1864ab72 added. We now have 3 listener(s)
08-31 15:25:48.764  1044  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.765  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.768  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.768  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.768  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.769  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.769  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b45ebc3 added. We now have 10 listener(s)
08-31 15:25:48.769  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.769  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:48.769  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:48.769  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:48.770  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:48.770  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:48.770  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:25:48.772  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.774  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:25:48.775  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:25:48.776  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:25:48.779  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:25:48.779  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:25:48.781  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:25:48.781  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.782  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 15:25:48.782  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:25:48.783  6699  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:25:48.783  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:48.784  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:48.784  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:48.784  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.784  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.784  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.784  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.784  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16d43427 removed from the list
08-31 15:25:48.784  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:48.784  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6846d4 removed from the list
08-31 15:25:48.784  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:48.784  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.785  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.785  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.787  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.787  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.787  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:48.787  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6846d4 not in the list
08-31 15:25:48.787  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.787  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.787  6955  6955 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:25:48.788  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.789  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:48.789  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:48.789  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.789  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.789  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b45ebc3 removed from the list
08-31 15:25:48.789  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.789  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.789  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.789  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.789  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1864ab72 removed from the list
08-31 15:25:48.790  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.790  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26ce0cbe added. We now have 2 listener(s)
08-31 15:25:48.790  1044  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.792  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.792  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.793  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.793  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.793  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2691811f added. We now have 9 listener(s)
08-31 15:25:48.793  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.793  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:25:48.794  7877  7877 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 15:25:48.794  7877  7877 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 15:25:48.794  7877  7877 D d,hcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 15:25:48.794  7877  7877 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 15:25:48.795  7877  7877 D dhcpcd  : wlan0: sending REQUEST (xid 0xc522c69f), next in 4.26 seconds
08-31 15:25:48.795  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:48.797  6955  6955 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:48.798  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:48.803  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.803  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:48.803  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:25:48.803  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20d4b235 added. We now have 3 listener(s)
08-31 15:25:48.803  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.804  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:25:48.804  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:25:48.804  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.805  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.806  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.806  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.806  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.806  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.806  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12da36ca added. We now have 10 listener(s)
08-31 15:25:48.806  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.806  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:48.806  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:48.806  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:48.806  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:48.806  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:25:48.806  7022  7022 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 15:25:48.807  7022  7022 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 15:25:48.807  7022  7022 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 15:25:48.809  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:25:48.810  1044  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:25:48.814  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:25:48.815  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:25:48.816  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:25:48.817  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.818  6699  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:25:48.819  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:48.819  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:48.819  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:48.820  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.820  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.820  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.820  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.820  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26ce0cbe removed from the list
08-31 15:25:48.820  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.820  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2691811f removed from the list
08-31 15:25:48.820  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:48.820  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.820  7877  7877 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 15:25:48.820  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.820  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.821  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.821  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.821  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.821  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2691811f not in the list
08-31 15:25:48.821  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.821  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.822  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:25:48.822  6699  6809 D BluetoothLeScanner: could not find callback wrapper
08-31 15:25:48.822  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:48.822  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.822  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.822  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12da36ca removed from the list
08-31 15:25:48.822  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.823  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.823  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.823  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.823  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20d4b235 removed from the list
08-31 15:25:48.824  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.824  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c2b3cb1 added. We now have 2 listener(s)
08-31 15:25:48.824  1044  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.826  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.826  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.826  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.826  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.826  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cccf596 added. We now have 9 listener(s)
08-31 15:25:48.826  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.827  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:25:48.828  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:48.830  6699  6809 V io.jxcore.node.ConnectivityMonitor:     - active network ,type is Wi-Fi: true
08-31 15:25:48.831  6699  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:48.831  6699  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:48.832  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:48.832  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14950d04 added. We now have 3 listener(s)
08-31 15:25:48.832  1044  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:25:48.833  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:48.834  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:25:48.834  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:48.834  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:48.834  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:48.834  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@285f2ed added. We now have 10 listener(s)
08-31 15:25:48.834  6699  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:48.834  6699  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:48.834  6699  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:48.834  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:48.834  6699  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:48.834  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.834  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.834  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:48.834  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.834  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c2b3cb1 removed from the list
08-31 15:25:48.834  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.834  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cccf596 removed from the list
08-31 15:25:48.834  6699  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:48.835  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.835  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.835  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.836  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.836  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.836  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.836  6699  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cccf596 not in the list
08-31 15:25:48.836  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.836  6699  6809 D org.thaliproject.p2p.btconnec,torlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.837  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:48.837  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:48.837  6699  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:48.837  6699  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@285f2ed removed from the list
08-31 15:25:48.837  6699  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:48.837  6699  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:48.837  6699  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:48.837  6699  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:48.837  6699  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14950d04 removed from the list
08-31 15:25:48.838  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 15:25:48.838  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 15:25:48.838  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 15:25:48.839  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:48.839  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 15:25:48.839  6699  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:48.849  6699  7884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
08-31 15:25:48.850  6699  7884 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
08-31 15:25:48.850  6699  7884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 15:25:48.853  6699  7885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
08-31 15:25:48.854  6699  7885 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
08-31 15:25:48.854  6699  7885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 15:25:48.856  6699  6809 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 15:25:48.856  6699  6809 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 15:25:48.856  6699  6809 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 15:25:48.856  6699  6809 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 15:25:48.856  6699  6809 D com.test.thalitest.ThaliTestRunner: Total duration: 22942 ms
08-31 15:25:48.857  6699  6809 I jxcore-log: *Native tests were executed*
08-31 15:25:48.857  6699  6809 I jxcore-log: 
08-31 15:25:48.857  6699  6809 I jxcore-log: Total number of executed tests:  80
08-31 15:25:48.857  6699  6809 I jxcore-log: 
08-31 15:25:48.857  6699  6809 I jxcore-log: Number of passed tests:  80
08-31 15:25:48.857  6699  6809 I jxcore-log: 
08-31 15:25:48.857  6699  6809 I jxcore-log: Number of failed tests:  0
08-31 15:25:48.857  6699  6809 I jxcore-log: 
08-31 15:25:48.857  6699  6809 I jxcore-log: Number of ignored tests:  0
08-31 15:25:48.857  6699  6809 I jxcore-log: 
08-31 15:25:48.858  6699  6809 I jxcore-log: Total duration:  22942
08-31 15:25:48.858  6699  6809 I jxcore-log: 
08-31 15:25:48.858  6699  6809 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 15:25:48.858  6699  6809 I jxcore-log: 
08-31 15:25:48.860  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.860  6699  6809 I jxcore-log: 
08-31 15:25:48.862  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.862  6699  6809 I jxcore-log: 
08-31 15:25:48.863  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.863  6699  6809 I jxcore-log: 
,08-31 15:25:48.864  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.864  6699  6809 I jxcore-log: 
08-31 15:25:48.864  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.864  6699  6809 I jxcore-log: 
08-31 15:25:48.865  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.865  6699  6809 I jxcore-log: 
08-31 15:25:48.868  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.868  6699  6809 I jxcore-log: 
08-31 15:25:48.869  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:25:48.869  6699  6809 I jxcore-log: 
08-31 15:25:48.870  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.870  6699  6809 I jxcore-log: 
08-31 15:25:48.871  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:25:48.871  6699  6809 I jxcore-log: 
08-31 15:25:48.872  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.872  6699  6809 I jxcore-log: 
08-31 15:25:48.872  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.872  6699  6809 I jxcore-log: 
08-31 15:25:48.873  1044  1713 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7886 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-31 15:25:48.873  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:25:48.873  6699  6809 I jxcore-log: 
08-31 15:25:48.874  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:25:48.874  6699  6809 I jxcore-log: 
08-31 15:25:48.875  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:25:48.875  6699  6809 I jxcore-log: 
08-31 15:25:48.876  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.876  6699  6809 I jxcore-log: 
08-31 15:25:48.876  7877  7877 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 15:25:48.876  7877  7877 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 15:25:48.877  7877  7877 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 15:25:48.877  7877  7877 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 15:25:48.877  7877  7877 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 15:25:48.877  7877  7877 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 15:25:48.877  7877  7877 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 15:25:48.877  7877  7877 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 15:25:48.878  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.878  6699  6809 I jxcore-log: 
08-31 15:25:48.878  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.878  6699  6809 I jxcore-log: 
,08-31 15:25:48.879  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.879  6699  6809 I jxcore-log: 
,08-31 15:25:48.879  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.879  6699  6809 I jxcore-log: 
08-31 15:25:48.880  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.880  6699  6809 I jxcore-log: 
08-31 15:25:48.881  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.881  6699  6809 I jxcore-log: 
08-31 15:25:48.881  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:48.881  6699  6809 I jxcore-log: 
08-31 15:25:48.882  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:48.882  6699  6809 I jxcore-log: 
08-31 15:25:48.882  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:48.882  6699  6809 I jxcore-log: 
08-31 15:25:48.883  6699  6699 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 15:25:48.883  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.883  6699  6809 I jxcore-log: 
08-31 15:25:48.884  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.884  6699  6809 I jxcore-log: 
08-31 15:25:48.884  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.884  6699  6809 I jxcore-log: 
08-31 15:25:48.885  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.885  6699  6809 I jxcore-log: 
08-31 15:25:48.885  6699  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:48.885  6699  6809 I jxcore-log: 
,08-31 15:25:48.928  7886  7886 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 15:25:48.928  7886  7886 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 15:25:48.955  7886  7886 I MultiDex: VM with version 2.1.0 has multidex support
08-31 15:25:48.955  7886  7886 I MultiDex: install
08-31 15:25:48.955  7886  7886 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 15:25:48.964  7886  7886 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-31 15:25:48.967  2168  2168 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 15:25:48.998  2168  2168 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 15:25:48.999  2168  2168 D c       : Getting all permits...
,08-31 15:25:48.999  2168  2168 D a       : Opening database...
08-31 15:25:49.002  2168  2168 D a       : Opening database auth.proximity.permit_store...
08-31 15:25:49.003  2168  2168 D a       : Closing database...
08-31 15:25:49.103  7909  7909 D AndroidRuntime: 
08-31 15:25:49.103  7909  7909 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 15:25:49.106  7909  7909 D AndroidRuntime: CheckJNI is OFF
,08-31 15:25:49.124  1044  7865 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 15:25:49.126  1044  7865 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 15:25:49.126  1044  7865 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 15:25:49.126  1044  7865 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 15:25:49.126  1044  7865 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 15:25:49.126  1044  7865 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 15:25:49.126  1044  7865 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 15:25:49.126  1044  7865 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 15:25:49.127  1044  7865 D DhcpStateMachine: RunningState
08-31 15:25:49.274  7909  7909 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 15:25:49.289  1044  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-31 15:25:49.290  1044  1115 I ActivityManager: Killing 6699:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-31 15:25:49.360  1044  1999 I WindowState: WIN DEATH: Window{206dc065 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 15:25:49.361  1044  1474 D WifiService: Client connection lost with reason: 4
08-31 15:25:49.369  1044  1999 D InputDispatcher: Window went away: Window{206dc065 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 15:25:49.507  1044  1115 I ActivityManager:   Force finishing activity ActivityRecord{2d9b8da6 u0 com.test.thalitest/.MainActivity t6}
,08-31 15:25:49.539   340   346 E GBMv2   : DFP En is all cleared set to be enabled
08-31 15:25:49.542  1044  1765 W ActivityManager: Spurious death for ProcessRecord{39498717 6699:com.test.thalitest/u0a118}, curProc for 6699: null
,08-31 15:25:49.552  1044  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-31 15:25:49.554  1044  1125 I ActivityManager:   Force finishing activity ActivityRecord{2d9b8da6 u0 com.test.thalitest/.MainActivity t6 f}
08-31 15:25:49.555  1044  1125 W ActivityManager: Duplicate finish request for ActivityRecord{2d9b8da6 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 15:25:49.582  1928  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-31 15:25:49.583  1928  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f675500 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 15:25:49.583  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 15:25:49.585  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-31 15:25:49.586  1928  2845 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 15:25:49.587  1928  2845 D SplitWindowPolicy: topRunningActivity=ActivityInfo{38e56139 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 15:25:49.587  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 15:25:49.589  2019  2111 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-31 15:25:49.591  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-31 15:25:49.602  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 15:25:49.603  3712  3712 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-31 15:25:49.606  7646  7646 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 15:25:49.606  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 15:25:49.607  1044  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 15:25:49.637  4621  4621 I art     : Explicit concurrent mark sweep GC freed 718(40KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 434us total 67.335ms
08-31 15:25:49.647  4507  4507 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 15:25:49.647  4507  4507 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 15:25:49.647  4507  4507 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 15:25:49.647  4507  4507 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 15:25:49.647  4507  4507 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:25:49.647  4507  4507 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:25:49.647  4507  4507 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:25:49.647  4507  4507 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 15:25:49.647  4507  4507 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:49.647  4507  4507 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:49.647  4507  4507 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 15:25:49.647  4507  4507 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-31 15:25:49.651  2456  2632 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 15:25:49.655  7886  7904 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:25:49.655  7886  7904 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:25:49.668  1044  1927 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:25:49.677  1044  1114 W InputMethodInfo: Duplicated subtype definition found: , voice
08-31 15:25:49.688  6487  6487 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 15:25:49.693  1804  1804 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-31 15:25:49.743  1044  1963 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7950 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-31 15:25:49.746  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 15:25:49.746  1891  1891 D ActionManagerService: notifyUserLog: 1000003
,08-31 15:25:49.748  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 15:25:49.748  3712  4529 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 15:25:49.749  1044  1999 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:25:49.749  1044  1999 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:25:49.752  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 15:25:49.756  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-31 15:25:49.756  1856  1856 D SplitUIService: removed split : 
08-31 15:25:49.767  1044  1425 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:25:49.768  1044  1425 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:25:49.768  1044  1425 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:25:49.768  1044  1425 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:25:49.769  1044  1425 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:25:49.769  1044  1425 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 15:25:49.771  2168  2168 I ConfigService: onCreate
08-31 15:25:49.772  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 15:25:49.776  1044  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-31 15:25:49.776  1044  1484 D ConnectivityService: identical MTU - not setting
08-31 15:25:49.776  1044  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 15:25:49.777  1044  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 15:25:49.777  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-31 15:25:49.777  1856  1856 I SplitUIService: split app #11
08-31 15:25:49.777  1044  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:49.777  1044  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:25:49.777  1044  1484 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:25:49.777  1589  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 15:25:49.778  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 15:25:49.779  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 15:25:49.780  1804  1804 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-31 15:25:49.786  2168  2168 I ConfigService: onBind returning update interface
08-31 15:25:49.787  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 15:25:49.787  2168  2168 I ConfigService: onBind returning config service
08-31 15:25:49.788  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-31 15:25:49.788  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 15:25:49.788  3712  4529 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 15:25:49.789  3712  3728 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , display: false
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , animation: false }
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , display: false
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , animation: false }
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , display: false
08-31 15:25:49.790  2019  2019 I GBoardWebViewUtils: , animation: false }
,08-31 15:25:49.797  2019  7969 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 15:25:49.807  2168  2168 I ConfigService: onDestroy
08-31 15:25:49.807  1044  1764 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 15:25:49.807  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 15:25:49.807  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:25:49.808  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 15:25:49.812  1804  7971 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 15:25:49.815  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 15:25:49.815  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-31 15:25:49.826  1044  2036 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:25:49.830  1044  1044 D administrator: Handling package changes for user 0
08-31 15:25:49.835  7950  7950 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-31 15:25:49.836  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 15:25:49.836  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-31 15:25:49.840  1044  2018 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7974 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-31 15:25:49.873  1589  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 15:25:49.873  1589  1637 D KeyguardModel: createShortcutInfo...
08-31 15:25:49.874  1589  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 15:25:49.874  1589  1637 D KeyguardModel: createShortcutInfo...
,08-31 15:25:49.887   334   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 15:25:49.888  3188  7994 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-31 15:25:49.889  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 15:25:49.890  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:49.890  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 15:25:49.893  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 15:25:49.898  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 15:25:49.898  1589  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 15:25:49.899  5982  7987 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-31 15:25:49.901  1589  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 15:25:49.901  1589  1637 D KeyguardModel: createShortcutInfo...
08-31 15:25:49.907  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 15:25:49.907  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:25:49.908  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:25:49.908  1589  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 15:25:49.909  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-31 15:25:49.918  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 15:25:49.918  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 15:25:49.919  1044  1044 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 15:25:49.920  7984  7984 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-31 15:25:49.922  1044  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-31 15:25:49.923  1804  7997 I PeopleContactsSync: CP2 sync disabled
,08-31 15:25:49.923  1589  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 15:25:49.923  1589  1637 D KeyguardModel: createShortcutInfo...
08-31 15:25:49.930  1804  4790 I Icing   : doRemovePackageData com.test.thalitest
08-31 15:25:49.930  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:49.931  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 15:25:49.931  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 15:25:49.931  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 15:25:49.932  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:25:49.932  1589  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 15:25:49.933  1589  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 15:25:49.933  1589  1637 D KeyguardModel: createShortcutInfo...
08-31 15:25:49.936  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-31 15:25:49.936  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-31 15:25:49.940  1589  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 15:25:49.940  1589  1637 D KeyguardModel: createShortcutInfo...
08-31 15:25:49.943  1589  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 15:25:49.943  1589  1637 D KeyguardModel: createShortcutInfo...
08-31 15:25:49.946  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:25:49.946  1589  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 15:25:49.949  1589  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 15:25:49.949  1589  1637 D KeyguardModel: createShortcutInfo...
,08-31 15:25:49.957  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:25:49.957  1589  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 15:25:49.959  1589  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 15:25:49.959  1589  1637 D KeyguardModel: createShortcutInfo...
08-31 15:25:49.961  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:25:49.961  1589  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 15:25:49.967  1589  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 15:25:49.967  1589  1637 D KeyguardModel: createShortcutInfo...
,08-31 15:25:49.969  1804  7996 W GmsApplication: Using Auth Proxy for data requests.
08-31 15:25:49.975  1804  7996 W GmsApplication: Using Auth Proxy for data requests.
08-31 15:25:49.978  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-31 15:25:49.978  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 15:25:50.006  7984  7984 I dex2oat : dex2oat took 85.449ms (threads: 4)
,08-31 15:25:50.010  2019  2033 I art     : Background partial concurrent mark sweep GC freed 6985(319KB) AllocSpace objects, 5(19MB) LOS objects, 34% free, 60MB/92MB, paused 2.283ms total 106.986ms
08-31 15:25:50.015  7886  7904 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:25:50.015  7886  7904 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:25:50.015  7886  7904 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:25:50.015  7886  7904 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:25:50.015  7886  7904 I Adreno-EGL: Remote Branch: 
08-31 15:25:50.015  7886  7904 I Adreno-EGL: Local Patches: 
08-31 15:25:50.015  7886  7904 I Adreno-EGL: Reconstruct Branch: 
08-31 15:25:50.032  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-31 15:25:50.037  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:25:50.038  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 15:25:50.040  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 15:25:50.041  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 15:25:50.042  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-31 15:25:50.047  1044  1125 I art     : Explicit concurrent mark sweep GC freed 75839(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 2.133ms total 459.015ms
08-31 15:25:50.054  1044  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15fa422e u0 com.lge.launcher2/.Launcher t5} time:147217
08-31 15:25:50.055  7974  7974 I AppUp4:AppBoxCP: onCreate
08-31 15:25:50.056  7974  7974 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 15:25:50.061  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 15:25:50.061  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:25:50.063  7974  7974 I AppUp4:DB:  setFingerPrint start
08-31 15:25:50.063  7974  7974 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 15:25:50.067  2019  2154 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 15:25:50.067  2019  2154 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-31 15:25:50.080  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 15:25:50.081  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-31 15:25:50.082  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:25:50.082  7974  7974 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 15:25:50.082  7974  7974 I AppUp4:DB:  SDK version = 21
08-31 15:25:50.082  7974  7974 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-31 15:25:50.083  7974  7974 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 15:25:50.089  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 15:25:50.091  2577  2577 D [Concierge]Service: onStartCommand(). Type : 8
08-31 15:25:50.091  2577  2577 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-31 15:25:50.091  2577  2577 D [Concierge]Service: Update widget ID : 11
08-31 15:25:50.093  2019  2019 D [Concierge]WidgetView: change position of spinner
,08-31 15:25:50.094  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1472649950094
08-31 15:25:50.095  2577  2577 D [Concierge]Service: onStartCommand(). Type : 0
08-31 15:25:50.101  7886  7904 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:25:50.101  7886  7904 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:25:50.101  7886  7904 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:25:50.101  7886  7904 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:25:50.101  7886  7904 I Adreno-EGL: Remote Branch: 
08-31 15:25:50.101  7886  7904 I Adreno-EGL: Local Patches: 
08-31 15:25:50.101  7886  7904 I Adreno-EGL: Reconstruct Branch: 
08-31 15:25:50.121  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 857000433
08-31 15:25:50.121  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-31 15:25:50.121  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 15:25:50.123  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3514fef5
08-31 15:25:50.124  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-31 15:25:50.125  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 15:25:50.126  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:25:50.127  7974  7974 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-31 15:25:50.131  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 15:25:50.131  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 15:25:50.132  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 15:25:50.140  7886  7904 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:25:50.140  7886  7904 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:25:50.140  7886  7904 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:25:50.140  7886  7904 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:25:50.140  7886  7904 I Adreno-EGL: Remote Branch: 
08-31 15:25:50.140  7886  7904 I Adreno-EGL: Local Patches: 
08-31 15:25:50.140  7886  7904 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:25:50.153  7909  7909 D AndroidRuntime: Shutting down VM
,08-31 15:25:50.162  1044  1764 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8008 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-31 15:25:50.162  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472649830363, New one : 1472649950094
08-31 15:25:50.162  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-31 15:25:50.162  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 15:25:50.184  1044  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8023 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 15:25:50.185  1044  1764 I ActivityManager: Killing 7228:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-31 15:25:50.203  1044  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:50.213  1044  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-31 15:25:50.227  1044  2018 W libprocessgroup: failed to open /acct/uid_10046/pid_7228/cgroup.procs: No such file or directory
08-31 15:25:50.227  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 15:25:50.230  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 15:25:50.231  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 15:25:50.232  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 15:25:50.233  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 15:25:50.234  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 15:25:50.235  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:25:50.235  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:25:50.258  8008  8008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:50.258  8008  8008 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:25:50.258  8008  8008 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-31 15:25:50.259  8008  8008 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 15:25:50.260  8008  8008 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 15:25:50.276  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 15:25:50.285  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 15:25:50.285  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-31 15:25:50.290  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 15:25:50.291  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:25:50.303  1044  1561 I ActivityManager: Killing 7247:com.android.chrome/u0a57 (adj 15): empty #17
,08-31 15:25:50.313  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@156656d2 time:147476
08-31 15:25:50.320  8008  8008 I SystemConfig: BUILD Country: EU
,08-31 15:25:50.320  8008  8008 I SystemConfig: BUILD Operator: OPEN
08-31 15:25:50.408  1044  1909 W libprocessgroup: failed to open /acct/uid_10057/pid_7247/cgroup.procs: No such file or directory
,08-31 15:25:50.419  1044  1060 I ActivityManager: Killing 7265:com.lge.drmservice/u0a62 (adj 15): empty #17
08-31 15:25:50.437  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-31 15:25:50.451  2168  4225 I art     : Explicit concurrent mark sweep GC freed 5860(335KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.339ms total 32.858ms
,08-31 15:25:50.470   308  7870 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 15:25:50.473  2019  2855 I GBoardtInterface: onReloaded()
08-31 15:25:50.474  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-31 15:25:50.488  1044  1927 W libprocessgroup: failed to open /acct/uid_10062/pid_7265/cgroup.procs: No such file or directory
,08-31 15:25:50.490  3712  3728 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 15:25:50.492  8008  8043 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-31 15:25:50.492  2360  2513 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 15:25:50.492  8008  8043 I SystemConfig: existFile = false
08-31 15:25:50.492  8008  8043 I SystemConfig: canReadFile = false
08-31 15:25:50.492  8008  8043 I SystemConfig: systemFeature RCS result false
08-31 15:25:50.492  8008  8043 D SystemConfig: refreshRcsSupport() :false
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:25:50.493  2360  2513 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:25:50.494  2360  8047 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 15:25:50.498  2360  8047 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-31 15:25:50.499  2360  8047 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 15:25:50.499  2360  8047 E AndroidRuntime: Process: android.process.acore, PID: 2360
08-31 15:25:50.499  2360  8047 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64,)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:25:50.499  2360  8047 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 15:25:50.520  1044  1963 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8048 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a

```
