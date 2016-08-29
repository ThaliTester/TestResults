#### Test 79763830f89c62d_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 14:20:46.568  6588  6588 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{e3a34bb com.google.android.apps.docs}
08-29 14:20:46.587  6588  6588 D TAG     : onCreate()
08-29 14:20:46.609  6588  6588 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 14:20:47.443   332   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 14:20:47.445  3204  6617 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 14:20:47.463  1804  4765 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-29 14:20:47.526  1804  4765 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-29 14:20:47.593  1804  4765 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-29 14:20:47.678  6618  6618 D AndroidRuntime: 
08-29 14:20:47.678  6618  6618 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 14:20:47.680  6618  6618 D AndroidRuntime: CheckJNI is OFF
08-29 14:20:47.825  6618  6618 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 14:20:47.830  1042  1562 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 14:20:47.843  6588  6588 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:20:47.843  1929  1945 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 14:20:47.843  6588  6588 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 14:20:47.847  1042  1562 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 14:20:47.848  1042  1562 D ActivityManager: setTaskToReturnTo : TaskRecord{2d4ea86c #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 14:20:47.848  1042  1562 D ActivityManager: setTaskToReturnTo : TaskRecord{2d4ea86c #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 14:20:47.849  1042  1562 D WindowStateEx: AppWindowTokenEx init.. 
08-29 14:20:47.849   338   356 E GBMv2   : DFP En is all cleared set to be enabled
08-29 14:20:47.882  1042  1562 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6640 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 14:20:47.884  6618  6618 D AndroidRuntime: Shutting down VM
08-29 14:20:47.917  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 14:20:47.917  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{95f1827 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 14:20:47.918  1929  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 14:20:47.918  1929  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c035ad4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 14:20:47.963  6640  6640 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 14:20:47.968  6145  6145 I LockScreenSettings: New app installed broadcast received ..
08-29 14:20:47.970  6145  6145 I LockScreenSettings: Number of installed packages  1
08-29 14:20:47.983  6588  6588 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-29 14:20:48.011  1042  1983 V SIM_STK : Menu title from STK is T-Mobile
08-29 14:20:48.040  6640  6640 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-29 14:20:48.052  1042  1974 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6671 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 14:20:48.058  6640  6640 I LibraryLoader: Loading: webviewchromium
08-29 14:20:48.060  6640  6640 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2975-2977)
08-29 14:20:48.060  6640  6640 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:20:48.071  6640  6640 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {125bf36d}
08-29 14:20:48.072  6640  6640 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:20:48.072  6640  6640 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 14:20:48.078  6640  6640 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 14:20:48.079  6640  6640 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 14:20:48.086  6640  6640 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 14:20:48.087  6640  6640 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 14:20:48.087  6640  6640 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-29 14:20:48.094   320  1702 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-29 14:20:48.098  1042  1118 D BluetoothManagerService: Message: 20
08-29 14:20:48.098  1042  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30d247b3:true
08-29 14:20:48.103  6640  6640 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 14:20:48.103  6640  6640 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 14:20:48.103  6640  6640 I Adreno-EGL: Build Date: 12/12/14 금
08-29 14:20:48.103  6640  6640 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 14:20:48.103  6640  6640 I Adreno-EGL: Remote Branch: 
08-29 14:20:48.103  6640  6640 I Adreno-EGL: Local Patches: 
08-29 14:20:48.103  6640  6640 I Adreno-EGL: Reconstruct Branch: 
,08-29 14:20:48.143  6671  6671 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 14:20:48.143  6671  6671 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 14:20:48.183  1042  1562 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6706 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 14:20:48.184  1042  1562 I ActivityManager: Killing 5829:com.google.android.gm/u0a64 (adj 15): empty #17
,08-29 14:20:48.294  1042  1059 W libprocessgroup: failed to open /acct/uid_10064/pid_5829/cgroup.procs: No such file or directory
,08-29 14:20:48.341  6640  6701 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 14:20:48.344  6640  6640 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 14:20:48.362  6640  6640 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 14:20:48.366  6640  6640 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 14:20:48.369  6640  6640 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 14:20:48.372  6640  6640 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 14:20:48.373  6640  6640 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-29 14:20:48.377  6706  6706 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-29 14:20:48.385  6640  6640 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-29 14:20:48.397  6706  6706 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 14:20:48.398  6640  6640 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 14:20:48.399  6640  6640 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 14:20:48.399  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 14:20:48.416  1042  1114 W ActivityManager: Activity pause timeout for ActivityRecord{3156ce35 u0 com.test.thalitest/.MainActivity t6}
,08-29 14:20:48.420  6459  6459 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 14:20:48.420  1042  1891 I ActivityManager: Killing 5870:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 14:20:48.494  1042  1910 W libprocessgroup: failed to open /acct/uid_10072/pid_5870/cgroup.procs: No such file or directory
,08-29 14:20:48.513  6640  6736 D OpenGLRenderer: Render dirty regions requested: true
08-29 14:20:48.513  6640  6736 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 14:20:48.515  6640  6730 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 14:20:48.515  6640  6730 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 14:20:48.521  6640  6736 D OpenGLRenderer: Enabling debug mode 0
,08-29 14:20:48.534  6640  6640 D Atlas   : Validating map...
08-29 14:20:48.538  1042  1974 D SplitWindow: check instance of lgWin Window{2e11e9b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 14:20:48.648  1042  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +732ms (total +795ms)
08-29 14:20:48.649  1042  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3156ce35 u0 com.test.thalitest/.MainActivity t6} time:103566
,08-29 14:20:48.663  6640  6640 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24839520 time:103580
,08-29 14:20:48.762  6640  6640 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 14:20:48.762  6640  6640 I chromium: 
,08-29 14:20:48.779  6640  6640 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 14:20:48.844  6640  6730 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 14:20:48.844  6640  6730 I chromium: 
,08-29 14:20:48.885   338   358 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 14:20:48.886   338   358 E GBMv2   : Set value is all cleared set the max
08-29 14:20:48.886   338   358 I GBMv2   : DFP Enabled. Ignore VFP set
,08-29 14:20:49.007  6640  6745 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-29 14:20:49.025  6640  6745 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 14:20:49.025  6640  6745 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 14:20:49.025  6640  6745 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 14:20:49.025  6640  6745 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 14:20:49.025  6640  6745 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 14:20:49.026  6640  6745 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8324fe4 added. We now have 1 listener(s)
08-29 14:20:49.032  1042  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:20:49.035  6640  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 14:20:49.038  6640  6745 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 14:20:49.041  6640  6745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:20:49.041  6640  6745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 14:20:49.051  6640  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27961413 added. We now have 1 listener(s)
08-29 14:20:49.051  6640  6745 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:20:49.058  1042  1531 D WifiService: New client listening to asynchronous messages
08-29 14:20:49.063  6640  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:20:49.063  6640  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 14:20:49.065  6640  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 14:20:49.065  6640  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-29 14:20:49.066  6640  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 14:20:49.076  6640  6745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:49.076  1042  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 14:20:49.079  6640  6745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 14:20:49.096  6640  6745 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:49.097  6640  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:20:49.098  6640  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 14:20:49.098  6640  6745 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:20:49.102  6640  6745 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 14:20:49.103  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:20:49.107  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:49.155  6640  6640 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 14:20:50.054  6640  6748 W jxcore-log: Initializing JXcore engine
08-29 14:20:50.054  6640  6748 W jxcore-log: JXcore engine is ready
,08-29 14:20:50.088  6748  6748 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8357]" dev="sockfs" ino=8357 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-29 14:20:50.088  6748  6748 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 14:20:50.088  6748  6748 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10442]" dev="sockfs" ino=10442 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 14:20:50.088  6748  6748 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 14:20:50.088  6748  6748 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31789]" dev="sockfs" ino=31789 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 14:20:50.103  6640  6748 W jxcore-log: Starting JXcore engine
,08-29 14:20:50.175  6640  6748 W jxcore-log: Platform android
08-29 14:20:50.175  6640  6748 W jxcore-log: 
08-29 14:20:50.175  6640  6748 W jxcore-log: Process ARCH arm
08-29 14:20:50.175  6640  6748 W jxcore-log: 
,08-29 14:20:50.468  6640  6748 I jxcore-log: JXcore Cordova bridge is ready!
08-29 14:20:50.468  6640  6748 I jxcore-log: 
08-29 14:20:50.468  6640  6748 W jxcore-log: JXcore engine is started
,08-29 14:20:50.477  6640  6745 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 14:20:50.481  6640  6640 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 14:20:51.819  2782  2782 I MusicWidget: mDelayedStopHandler : unbind
,08-29 14:20:51.827  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 14:20:51.828  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 14:20:51.828  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 14:20:51.832  2135  2135 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 14:20:51.833  2135  2135 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 14:20:51.833  2135  2135 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 14:20:51.835  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
,08-29 14:20:51.835  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 14:20:51.837  1042  1938 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3f06a152com.lge.music.MediaPlaybackService$5@3265dc23
08-29 14:20:51.837  2135  2135 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 14:20:51.837  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.838  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.839  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.840  2135  2135 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@36d15969
08-29 14:20:51.840  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.841  2135  2135 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 14:20:51.841  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.841  2135  2135 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 14:20:51.842  2135  2135 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 14:20:51.842  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.842  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-29 14:20:51.847  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.848  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.849  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 14:20:51.850  2135  2135 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 14:20:51.851  2135  2135 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 14:20:51.851  2135  2135 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 14:20:51.851  2135  2135 V MediaPlayer[Native]: reset
08-29 14:20:51.858  2135  2135 V MediaPlayer[Native]: setListener
08-29 14:20:51.858  2135  2135 V MediaPlayer[Native]: disconnect
08-29 14:20:51.858  2135  2135 V MediaPlayer[Native]: destructor
,08-29 14:20:51.859   320  1702 V AudioFlinger: releasing 18 from 2135 for -1
08-29 14:20:51.860   320  1702 V AudioFlinger:  decremented refcount to 0
08-29 14:20:51.860   320  1702 V AudioFlinger: purging stale effects
08-29 14:20:51.860  2135  2135 V MediaPlayer[Native]: disconnect
08-29 14:20:51.861  2135  2135 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 14:20:51.862  2135  2135 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 14:20:51.863  2135  2135 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 14:20:51.864  2135  2135 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 14:20:51.864  2135  2135 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 14:20:51.864  2135  2135 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 14:20:51.864  2135  2135 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 612603168
08-29 14:20:51.864  2135  2135 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 612603168
08-29 14:20:51.872  2135  2135 I SmartShareClient: [SmartShareManagerClient] terminate service: 2135/MediaPlaybackService/1053647255
,08-29 14:20:51.877  2135  2135 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 14:20:51.878  2135  2135 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1a366ed9
08-29 14:20:51.880  2135  2135 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 14:20:51.880  2135  2135 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 14:20:51.881  2135  2135 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 14:20:51.881  2135  2135 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 14:20:51.884  1042  1798 I ActivityManager: Killing 5676:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-29 14:20:51.893  2135  2135 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
08-29 14:20:51.901  5650  5650 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 14:20:51.901  5650  5650 W System.err: android.os.DeadObjectException
08-29 14:20:51.901  5650  5650 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 14:20:51.902  5650  5650 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 14:20:51.902  5650  5650 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 14:20:51.902  5650  5650 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 14:20:51.902  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 14:20:51.902  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 14:20:51.902  5650  5650 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:20:51.902  5650  5650 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 14:20:51.902  5650  5650 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 14:20:51.902  5650  5650 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 14:20:51.902  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:51.902  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:51.902  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 14:20:51.902  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 14:20:51.902  5650  5650 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-29 14:20:51.907  5650  5650 W System.err: android.os.DeadObjectException
08-29 14:20:51.907  5650  5650 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 14:20:51.908  5650  5650 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 14:20:51.908  5650  5650 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 14:20:51.908  5650  5650 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 14:20:51.908  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 14:20:51.908  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 14:20:51.908  5650  5650 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:20:51.908  5650  5650 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 14:20:51.908  5650  5650 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 14:20:51.908  5650  5650 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 14:20:51.908  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:51.908  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:51.908  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 14:20:51.908  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 14:20:51.908  5650  5650 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 14:20:51.908  5650  5650 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 14:20:52.096  1042  1798 E libprocessgroup: failed to kill 1 processes for processgroup 5676
,08-29 14:20:52.233  1042  1874 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-29 14:20:52.237  5650  5650 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 14:20:52.237  5650  5650 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 14:20:52.250  6588  6588 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 14:20:52.284  1042  2005 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6761 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 14:20:52.286  1042  1059 I ActivityManager: Killing 5650:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 14:20:52.465  1042  1947 W libprocessgroup: failed to open /acct/uid_10112/pid_5650/cgroup.procs: No such file or directory
,08-29 14:20:52.542  6761  6761 D UEI.SmartControl: Quickset Services start...
,08-29 14:20:52.547  6761  6761 I UEI.SmartControl: Manufacture = LGE
,08-29 14:20:52.547  6761  6761 D UEI.SmartControl: Id = LGNevo
08-29 14:20:52.549  6761  6761 D UEI.SmartControl: File observer start...
08-29 14:20:52.550  6761  6761 E UEI.SmartControl: IR Port is disabled: false
08-29 14:20:52.551  6761  6761 D UEI.SmartControl: Starting file observer...
08-29 14:20:52.551  6761  6761 D UEI.SmartControl: Extracting JNI libs...
08-29 14:20:52.552  6761  6761 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 14:20:52.635  6761  6761 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 14:20:52.636  6761  6761 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 14:20:52.636  6761  6761 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 14:20:52.661  6761  6761 I UEI.SmartControl: --- Selecting new region: 6
,08-29 14:20:52.665  6761  6761 I UEI.SmartControl: Model = LG-D855
08-29 14:20:52.666  6761  6761 D UEI.SmartControl: QS Service created
08-29 14:20:52.682  6761  6761 I UEI.SmartControl: Service initServices...
08-29 14:20:52.687  6761  6761 D UEI.SmartControl: QS start get config
,08-29 14:20:52.744  6761  6761 D UEI.SmartControl: Loading JNI Libs...
,08-29 14:20:52.904  6588  6639 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 14:20:53.062  6761  6761 I UEI.SmartControl: Supports setup maps: true
,08-29 14:20:53.066  6761  6761 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 14:20:53.066  6761  6761 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 14:20:53.066  6761  6761 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 14:20:53.066  6761  6761 I UEI.SmartControl: ### init IR Blaster...
08-29 14:20:53.071  6761  6761 D serial_port: Configuring serial port
08-29 14:20:53.075  6761  6761 E UEI.SmartControl: UEIBLaster setting for 616
08-29 14:20:53.075  6761  6761 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 14:20:53.075  6761  6761 I UEI.SmartControl: configuring settings for MAXQ616
08-29 14:20:53.075  6761  6761 I UEI.SmartControl: Get version...
,08-29 14:20:53.092  6761  6795 D UEI.SmartControl: serial port data available: 21
,08-29 14:20:53.124  6761  6761 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 14:20:53.124  6761  6761 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 14:20:53.124  6761  6761 I UEI.SmartControl: QS saving settings...
08-29 14:20:53.126  6761  6761 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 14:20:53.146  6761  6795 D UEI.SmartControl: serial port data available: 4
,08-29 14:20:53.179  6761  6798 I UEI.SmartControl: Device manager: loading config....
08-29 14:20:53.179  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 14:20:53.180  6761  6798 D UEI.SmartControl: ----------- loading internal config...
08-29 14:20:53.182  6761  6761 E UEI.SmartControl: Services init done
08-29 14:20:53.182  6761  6761 D UEI.SmartControl: QS Service init finished
,08-29 14:20:53.183  6761  6761 D UEI.SmartControl: QS Service version name: 2.1.91
,08-29 14:20:53.183  6761  6761 D UEI.SmartControl: QS Service version code: 201091
08-29 14:20:53.184  6761  6761 D UEI.SmartControl: Service requested: Control
08-29 14:20:53.193  6761  6798 E UEI.SmartControl: Loading SETTINGS...
08-29 14:20:53.195  6761  6761 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-29 14:20:53.198  1042  1892 I ActivityManager: Killing 6299:com.android.calendar/u0a13 (adj 15): empty #17
08-29 14:20:53.201  6761  6798 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 14:20:53.219  6761  6797 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 14:20:53.219  6761  6797 D UEI.SmartControl: -----service ready thread exits
08-29 14:20:53.334  1042  2020 W libprocessgroup: failed to open /acct/uid_10013/pid_6299/cgroup.procs: No such file or directory
08-29 14:20:53.334  6761  6761 D UEI.SmartControl: Internal service binding...
,08-29 14:20:58.167  6761  6796 D serial_port: close(fd = 25)
,08-29 14:20:58.174  6761  6796 I UEI.SmartControl: Serial port is closed.
08-29 14:20:58.179  6761  6799 D UEI.SmartControl: Internal timer expired: 1
08-29 14:20:58.180  6761  6799 D UEI.SmartControl: unbind internal service
08-29 14:20:58.184  6761  6761 D UEI.SmartControl: Service.onUnbind: IControl
,08-29 14:20:58.187  6761  6761 D UEI.SmartControl: Service.onDestroy
08-29 14:20:58.188  6761  6761 D UEI.SmartControl: Lock is in USE false
08-29 14:20:58.188  6761  6761 D UEI.SmartControl: unbind internal service
08-29 14:20:58.189  6761  6761 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@36d15969
08-29 14:20:58.190  6761  6761 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 14:20:58.190  6761  6761 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 14:20:58.190  6761  6761 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-29 14:20:58.190  6761  6761 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-29 14:20:58.190  6761  6761 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 14:20:58.190  6761  6761 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 14:20:58.190  6761  6761 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 14:20:58.191  6761  6761 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-29 14:20:58.191  6761  6761 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:58.191  6761  6761 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 14:20:58.191  6761  6761 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 14:20:58.191  6761  6761 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:58.191  6761  6761 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:58.191  6761  6761 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 14:20:58.191  6761  6761 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 14:20:58.191  6761  6761 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@36d15969
,08-29 14:20:58.192  6761  6761 I UEI.SmartControl: Serial port is closed.
08-29 14:20:58.192  6761  6761 I UEI.SmartControl: Serial port is closed.
08-29 14:20:58.192  6761  6761 D UEI.SmartControl: Blaster closed
08-29 14:20:58.194  6761  6761 D UEI.SmartControl: Shut down QS...
08-29 14:20:58.195  6761  6761 D UEI.SmartControl: Stopping QS lib
08-29 14:20:58.195  6761  6761 D UEI.SmartControl: QS lib stop result = true
08-29 14:20:58.195  6761  6761 D UEI.SmartControl: Stopped QS lib
08-29 14:20:58.196  6761  6761 D UEI.SmartControl: Stopped file observer...
08-29 14:20:58.196  6761  6761 D UEI.SmartControl: QS shutdown complete
,08-29 14:21:00.001  1042  1406 D PowerManagerServiceEx: acquireWakeLockInternal: lock=387193831, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,08-29 14:21:00.042  2599  2599 D [Concierge]Service: onStartCommand(). Type : 9
,08-29 14:21:00.055  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-29 14:21:00.055  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 14:21:00.055  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 14:21:00.055  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
08-29 14:21:00.057  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 14:21:00.057  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-29 14:21:00.057  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-29 14:21:00.058  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 14:21:00.094  4479  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 14:21:00.109  1042  1042 D PowerManagerServiceEx: releaseWakeLockInternal: lock=387193831 [*alarm*], flags=0x0
,08-29 14:21:00.440  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 14:21:00.440  6640  6748 I jxcore-log: 
,08-29 14:21:00.443  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 14:21:00.443  6640  6748 I jxcore-log: 
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:00.456  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:00.467  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:00.476  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 14:21:00.476  6640  6748 I jxcore-log: 
,08-29 14:21:00.479  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 14:21:00.479  6640  6748 I jxcore-log: 
08-29 14:21:00.777  1042  1114 I ActivityManager: Waited long enough for: ServiceRecord{2320a74 u0 com.google.android.gms/.wearable.service.WearableService}
,08-29 14:21:01.091  6640  6748 D executeNativeTests: Running unit tests
,08-29 14:21:01.171  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:01.171  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 added. We now have 2 listener(s)
08-29 14:21:01.172  1042  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:01.174  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:01.174  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:01.174  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:01.174  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:01.174  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd added. We now have 2 listener(s)
08-29 14:21:01.174  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:01.175  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:01.177  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:01.182  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:01.183  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.183  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:01.184  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.186  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.188  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 14:21:01.189  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:21:01.189  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 14:21:01.190  6640  6748 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 14:21:01.191  6640  6748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 14:21:01.191  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:21:01.191  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:01.191  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:01.192  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.192  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.192  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.193  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.193  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.193  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:01.193  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:01.193  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 removed from the list
08-29 14:21:01.193  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:01.193  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd removed from the list,
08-29 14:21:01.193  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.193  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.194  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:01.194  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.194  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:01.194  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.194  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.195  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.196  6640  6748 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 14:21:01.196  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 14:21:01.196  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.196  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.196  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.196  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.196  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.196  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
,08-29 14:21:01.196  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.196  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.196  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.196  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.196  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.196  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.196  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.197  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.197  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.197  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:01.197  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-29 14:21:01.201  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 14:21:01.201  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.201  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.201  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.202  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:01.202  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.202  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.202  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.202  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.202  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.202  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:01.202  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.202  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.202  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.202  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.202  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.202  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:01.202  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.202  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.203  6640  6748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:21:01.206  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:01.208  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:01.209  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.209  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:01.210  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:01.211  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.211  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:01.211  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 14:21:01.211  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:01.211  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.211  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:01.214  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:01.214  1042  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:01.220  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 14:21:01.224  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:21:01.225  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 14:21:01.226  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:21:01.227  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 14:21:01.228  6640  6748 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 14:21:01.228  6640  6748 I io.jxcore.node.ConnectionHelper: start: OK
08-29 14:21:01.231  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.231  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.231  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:21:01.231  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.231  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.231  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:01.231  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.231  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.231  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
,08-29 14:21:01.231  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.231  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.232  6640  6748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:21:01.233  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:01.235  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:01.236  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.236  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:01.237  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:01.238  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.238  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:01.238  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:01.238  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:01.238  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.238  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:01.241  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:01.241  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:01.242  6640  6748 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 14:21:01.243  6640  6748 I io.jxcore.node.ConnectionHelper: start: OK
08-29 14:21:01.244  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.244  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.244  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.244  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.244  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.244  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:01.244  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.244  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.244  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.244  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.244  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.244  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.244  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.245  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.245  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.246  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.246  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.246  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.246  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproj,ect.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.247  6640  6748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:21:01.248  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:01.251  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:01.251  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.251  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:01.252  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:01.253  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:01.253  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:01.253  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.253  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:01.253  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.254  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.256  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:01.257  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:01.258  6640  6748 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 14:21:01.258  6640  6748 I io.jxcore.node.ConnectionHelper: start: OK
08-29 14:21:01.258  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.258  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.262  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.263  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.263  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.263  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.263  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.263  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.263  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:01.263  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.263  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.263  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.263  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.263  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.264  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.264  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.265  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.265  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.266  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.266  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.266  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.266  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.266  6640  6748 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 14:21:01.266  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.266  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.266  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.266  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.266  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.266  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.267  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.267  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.267  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.267  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.267  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.267  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.267  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.267  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.268  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.268  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.268  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.268  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.268  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.268  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.269  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 14:21:01.269  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.269  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.269  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.269  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.269  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.269  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.269  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.269  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.269  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.269  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.269  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.269  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.269  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.269  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.270  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.270  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.270  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.270  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.270  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.270  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.271  6640  6748 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 14:21:01.271  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.271  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.271  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.271  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.271  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.271  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.271  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.271  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.271  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.271  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.271  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.271  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.271  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.271  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.272  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.272  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.273  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.273  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.273  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.273  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.273  6640  6748 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 14:21:01.273  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.273  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.273  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.273  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.273  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.273  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.273  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.273  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.273  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.273  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.273  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.273  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.273  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.273  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.274  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.274  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.275  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.275  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.275  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.275  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.275  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 14:21:01.275  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:21:01.275  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:21:01.275  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:01.275  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 14:21:01.275  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:21:01.276  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.276  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.276  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.276  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.276  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.276  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.276  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.276  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.276  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.276  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.276  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.276  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.276  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.276  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.277  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.277  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:01.277  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.277  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.277  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.277  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.278  6640  6748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:01.278  6640  6748 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:21:01.278  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 14:21:01.280  6640  6748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:01.280  6640  6748 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 14:21:01.280  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 14:21:01.281  6640  6748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 14:21:01.281  6640  6748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:21:01.281  6640  6748 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 14:21:01.281  6640  6748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:01.281  6640  6748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:21:01.281  6640  6748 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 14:21:01.281  6640  6748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:01.281  6640  6748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:21:01.281  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 14:21:01.283  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 14:21:01.284  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 14:21:01.284  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 14:21:01.284  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 14:21:01.284  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 14:21:01.284  6640  6748 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 14:21:01.285  6640  6748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:01.285  6640  6748 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 14:21:01.285  6640  6832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-29 14:21:01.285  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.285  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.285  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.285  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.285  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.285  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.286  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 14:21:01.287  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.287  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.287  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.287  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.287  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.287  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.287  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.287  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.287  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.287  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.288  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.288  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.288  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.288  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.288  6640  6748 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 14:21:01.289  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.289  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.289  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.290  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.290  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.290  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.290  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.290  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.291  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.291  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.291  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.291  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.291  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.291  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.292  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.292  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.293  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.293  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.293  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.293  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.293  6640  6748 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 14:21:01.294  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.294  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.294  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.295  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.296  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.296  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.296  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.296  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.296  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.296  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.296  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.296  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.296  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.296  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.296  6640  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-29 14:21:01.296  6640  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
08-29 14:21:01.296  6640  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
08-29 14:21:01.298  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.298  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.298  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.298  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.299  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.299  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.299  6640  6748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 14:21:01.299  6640  6748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 14:21:01.299  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:21:01.299  6640  6748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 14:21:01.299  6640  6748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:21:01.299  6640  6748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 14:21:01.300  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:21:01.300  6640  6748 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 14:21:01.300  6640  6748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:21:01.300  6640  6748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:21:01.300  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:21:01.300  6640  6748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 14:21:01.300  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.300  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.300  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.300  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.300  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.300  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.300  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.300  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.300  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.300  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.300  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.300  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.300  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.300  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.301  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.301  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.301  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.301  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.301  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.301  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.302  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.302  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.302  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.302  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.302  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.302  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.302  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.302  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.302  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.302  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.302  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.302  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.302  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.302  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.302  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.302  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.302  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.302  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.303  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.303  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.303  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.303  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.303  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.303  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.303  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.303  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.303  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.303  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.303  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.304  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.304  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.304  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.304  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.304  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.304  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.305  6640  6748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 14:21:01.305  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.307  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 14:21:01.309  6640  6748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 14:21:01.309  6640  6748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 14:21:01.310  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 14:21:01.310  6640  6640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 14:21:01.311  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:21:01.311  1042  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:01.312  6640  6834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:01.313  3832  3856 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-29 14:21:01.313  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.313  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 14:21:01.313  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 14:21:01.313  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 14:21:01.313  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.313  6640  6748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 14:21:01.313  6640  6640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 14:21:01.313  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.313  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.313  6640  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 14:21:01.313  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:21:01.313  6640  6748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:01.313  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:21:01.314  6640  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 14:21:01.314  6640  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 14:21:01.318  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:01.318  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:01.318  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:01.318  6640  6748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:21:01.318  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.318  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:01.320  6640  6748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:01.321  6640  6640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:01.321  6640  6640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 14:21:01.321  6640  6640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:01.321  6640  6640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:01.321  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.322  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.322  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.322  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.322  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.322  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.322  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.322  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.322  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.322  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.322  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.322  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.322  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.322  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.322  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.323  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.323  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.323  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.323  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.324  6640  6748 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 14:21:01.324  6640  6748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 14:21:01.324  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:21:01.325  6640  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:01.325  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.325  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.325  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.325  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.325  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.325  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.325  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.325  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.325  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.325  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.325  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.325  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.325  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.325  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.326  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.326  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.326  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.326  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.327  1042  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:01.327  1042  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:01.328  1042  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:01.328  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.328  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.328  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.328  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.328  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.329  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.329  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.329  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.329  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.329  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.329  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.329  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.329  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.329  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.329  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.329  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.329  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.329  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.330  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:01.330  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:01.330  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:01.331  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:01.331  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.332  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.332  6640  6748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382b65b4 not in the list
08-29 14:21:01.332  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.332  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.332  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:01.332  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.332  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.332  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:01.332  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:01.333  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:01.334  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:01.334  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:01.334  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af55dd not in the list
08-29 14:21:01.336  6640  6748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 14:21:01.336  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:21:01.337  6640  6748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 14:21:01.337  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:21:01.337  6640  6748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 14:21:01.337  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:21:01.339  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 14:21:01.339  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 14:21:01.340  6640  6748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 14:21:01.340  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 14:21:01.340  6640  6748 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 14:21:01.340  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 14:21:01.340  6640  6748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 14:21:01.340  6640  6748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 14:21:01.341  6640  6748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 14:21:01.341  6640  6748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 14:21:01.342  6640  6748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 14:21:01.342  6640  6748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 14:21:01.342  6640  6748 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 14:21:01.342  6640  6748 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 14:21:01.346  6640  6832 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-29 14:21:01.347  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:01.347  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1bfcaa added. We now have 2 listener(s)
08-29 14:21:01.347  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:01.347  6640  6832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
08-29 14:21:01.348  6640  6748 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 14:21:01.349  1042  1892 D WifiServiceImplEx: setWifiEnabled: true pid=6640, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 14:21:01.349  1042  1892 D WifiService: setWifiEnabled: true pid=6640, uid=10118
08-29 14:21:01.349  1042  1892 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 14:21:01.350  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:01.350  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1762909b added. We now have 3 listener(s)
08-29 14:21:01.350  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:01.354  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:01.355  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fe8fc38 added. We now have 4 listener(s)
08-29 14:21:01.355  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:01.356  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:01.357  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e5ca411 added. We now have 5 listener(s)
08-29 14:21:01.357  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:01.359  1042  1058 D WifiServiceImplEx: setWifiEnabled: false pid=6640, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 14:21:01.359  1042  1058 D WifiService: setWifiEnabled: false pid=6640, uid=10118
08-29 14:21:01.359  1042  1058 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:21:01.371  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 14:21:01.371  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 14:21:01.371  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-29 14:21:01.372  1042  1526 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:01.373  1042  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:01.373  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:01.373  1042  2020 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2b246aa9 mBinding = false
08-29 14:21:01.373  1042  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:01.374  1042  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:01.374  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:01.374  1042  1526 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 14:21:01.374  1042  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:01.374  1042  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 14:21:01.375  1042  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 14:21:01.375  1042  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 14:21:01.382  1042  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 14:21:01.383  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.383  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.383  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 14:21:01.383  2725  2725 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 14:21:01.384  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 14:21:01.384  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:01.385  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
,08-29 14:21:01.385  1042  2847 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.388  1042  1118 D BluetoothManagerService: Message: 2
08-29 14:21:01.389  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 14:21:01.389  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 14:21:01.389  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-29 14:21:01.390   315   911 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:21:01.390  1042  1118 D BluetoothManagerService: Sending off request.
08-29 14:21:01.391  3832  3856 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 14:21:01.391  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:01.392  3832  3947 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 14:21:01.392  3832  3947 D BluetoothAdapterProperties: Setting state to 13
08-29 14:21:01.393  3832  3947 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 14:21:01.393  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:01.393  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 14:21:01.393  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 14:21:01.394  3832  3947 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 14:21:01.394  3832  3947 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 14:21:01.396  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:01.398  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 14:21:01.413  3832  3832 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:01.413  3832  3832 D BluetoothMapService: STATE_TURNING_OFF
08-29 14:21:01.413  3832  3832 V BluetoothMapService: Handler(): got msg=4
08-29 14:21:01.413  3832  3832 D BluetoothMapService: MAP Service closeService in
08-29 14:21:01.413  3832  3832 D BluetoothMapMasInstance: MAP Service shutdown
,08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 14:21:01.416  3832  4186 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 14:21:01.416  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 14:21:01.416  3832  3832 V BluetoothMapService: MAP Service closeService out
08-29 14:21:01.416  3832  3832 V BtOppService: Receiver DISABLED_ACTION 
08-29 14:21:01.417  3832  3832 I BtOppRfcommListener: stopping Accept Thread
08-29 14:21:01.417  3832  3832 V BtOppRfcommListener: close mBtServerSocket
08-29 14:21:01.417  3832  3832 V BtOppRfcommListener: waiting for thread to terminate
08-29 14:21:01.417  3832  4204 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:01.417  3832  4204 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 14:21:01.417  3832  3832 V BtOppRfcommListener: done waiting for thread to terminate
08-29 14:21:01.439  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:01.439  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:01.439  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.440  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.440  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:01.443  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.446  1042  1114 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6843 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 14:21:01.448  3832  3832 V BtOppService: onDestroy
08-29 14:21:01.448  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.450  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 14:21:01.450  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-29 14:21:01.454  1042  1042 D WifiHS20: hidePasspointNotification off =false
,08-29 14:21:01.465  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:01.465  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:01.465  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.465  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:01.466  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:01.466  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:01.466  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-29 14:21:01.468  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:01.468  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:01.468  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 14:21:01.468  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.468  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:01.473  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-29 14:21:01.476  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:01.477  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:01.477  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 14:21:01.478  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 14:21:01.478  1042  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.478  1042  1042 D RttService: SCAN_AVAILABLE : 1
08-29 14:21:01.478  1042  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.480  1042  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.480  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.480  1042  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@28a331d3
08-29 14:21:01.480  1042  1524 D LGWifiP2pService: P2pDisablingState
08-29 14:21:01.480  1042  1524 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.481  1042  1524 D LGWifiP2pService: p2p socket connection lost
08-29 14:21:01.481  1042  1524 D LGWifiP2pService: P2pDisabledState
08-29 14:21:01.483  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:01.483  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:01.484  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.486  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:01.486  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:01.486  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:01.488  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 14:21:01.489  1929  1929 D WfdsService: WifiP2pState is changed : false
08-29 14:21:01.489  1929  2288 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 14:21:01.489  1929  2288 D WfdsService: Set the WFDS Monitor: false
08-29 14:21:01.489  1929  2288 D WfdsMonitor: WFDS Monitor is stopped
08-29 14:21:01.489  1929  2760 D CtrlSupplicant: Received on exit socket, terminate
08-29 14:21:01.489  1929  2288 D WfdsService: STATE : WfdsDisabledState - enter
08-29 14:21:01.489  1929  2760 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 14:21:01.490  1929  2760 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 14:21:01.490  1929  2760 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 14:21:01.490  1929  2288 W WfdsService: DefaultState - msg [9445378] is not handled
,08-29 14:21:01.491  1042  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 14:21:01.491  1929  2290 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 14:21:01.491  1042  1532 D DSQN    : disableDataServiceNotify
08-29 14:21:01.491  1042  1532 D DSQN    : stop dsqn bin
08-29 14:21:01.493  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.494  1042  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:01.494  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:01.495  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:01.495  1042  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:01.496  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:01.496  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:01.496  1042  1526 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 14:21:01.497  1042  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 14:21:01.497  1042  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.497  1042  1524 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.497  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 14:21:01.497  2725  2725 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 14:21:01.497  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 14:21:01.497  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:01.498  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
08-29 14:21:01.499   315   911 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:21:01.499  1042  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 14:21:01.499  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:01.499  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:01.499  1042  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:01.499  1042  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 14:21:01.500  1042  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 14:21:01.500  1042  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 14:21:01.500  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 14:21:01.500  1042  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:01.500  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.,net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 14:21:01.500  1042  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.500  1042  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.501  1042  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 14:21:01.501  1590  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-29 14:21:01.502  1042  1526 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 14:21:01.504  1042  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 14:21:01.504  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-29 14:21:01.504  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:01.504  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:01.504  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 14:21:01.504  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 14:21:01.504  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 14:21:01.504  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 14:21:01.504  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 14:21:01.505  1042  1526 D WifiNative-p2p0: TERMINATE: returned true
08-29 14:21:01.505  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:01.505  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:01.505  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 14:21:01.506  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 14:21:01.507  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 14:21:01.507  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 14:21:01.507  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:01.508  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:01.508  1042  1042 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 14:21:01.508  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.508  1042  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:01.508  1042  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:01.509  1042  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:01.509  1042  1532 D NetworkManagementService: Removing idletimer
08-29 14:21:01.510  1042  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:01.510  1042  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 14:21:01.510  1042  1532 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 14:21:01.510  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:01.510  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 14:21:01.510  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 14:21:01.510  1042  1526 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: IN,TERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:01.510  1042  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:01.511  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 14:21:01.511  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 14:21:01.511  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 14:21:01.512  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:01.513  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:01.516  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.516  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:01.517  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:01.517  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:01.518  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:01.518  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:01.540  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 14:21:01.541  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.542  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.542  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 14:21:01.556  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 14:21:01.556  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.557  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.557  1042  1938 I art     : Explicit concurrent mark sweep GC freed 40961(1963KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.397ms total 155.170ms
,08-29 14:21:01.591  1042  1974 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6865 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 14:21:01.593  3832  3950 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:01.593  3832  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 14:21:01.593  3832  4190 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:01.593  3832  3947 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 14:21:01.593  3832  4206 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:01.593  3832  4208 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:01.594  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 14:21:01.594  3832  4067 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 14:21:01.595  3832  3832 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 14:21:01.595  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 14:21:01.595  3832  4067 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 14:21:01.600  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.601  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.603  2725  2725 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 14:21:01.604  2725  2725 I wpa_supplicant: monitor socket send errors count : 1
08-29 14:21:01.604  2725  2725 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-2\x00 that cannot receive messages
,08-29 14:21:01.604  1042  2759 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 14:21:01.604  1042  2759 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 14:21:01.611  6843  6843 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:01.611  6843  6843 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 14:21:01.611  6843  6843 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:01.612  6843  6843 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 14:21:01.613  6843  6843 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 14:21:01.613  6843  6843 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 14:21:01.641  2725  2725 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 14:21:01.642  2725  2725 W wpa_supplicant: USIM:  scard_deinit function
08-29 14:21:01.642  1042  1118 D Tethering: InitialState.processMessage what=4
08-29 14:21:01.643  1042  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 14:21:01.643  1042  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 14:21:01.643  1042  2759 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 14:21:01.644  1042  2759 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 14:21:01.644  1042  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:21:01.644  1042  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:01.644  1042  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:01.644  1042  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116546
08-29 14:21:01.645  1042  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116547
08-29 14:21:01.645  1042  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116547  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 14:21:01.646  1042  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116548  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 14:21:01.646  1042  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:01.646  1042  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 14:21:01.668  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 14:21:01.674  1042  2847 D DhcpStateMachine: StoppedState
08-29 14:21:01.674  1042  2847 D DhcpStateMachine: StoppedState{ when=-175ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:01.674  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:01.675  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:01.675  1042  1526 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 14:21:01.676  1042  1526 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 14:21:01.676  1042  1910 I ActivityManager: Killing 6255:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 14:21:01.692  6843  6843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 14:21:01.708  1042  1974 W libprocessgroup: failed to open /acct/uid_10014/pid_6255/cgroup.procs: No such file or directory
,08-29 14:21:01.713  3832  3832 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 14:21:01.713  3832  3832 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:01.713  3832  3832 V BluetoothPbapReceiver: ***********state = 13
08-29 14:21:01.715  3832  3832 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 14:21:01.716  3832  3832 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:01.716  3832  3832 V BluetoothPbapService: state: 13
08-29 14:21:01.717  3832  3832 V BluetoothPbapService: Pbap Service closeService in
08-29 14:21:01.718  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:01.718  3832  3832 V BluetoothPbapService: successfully stopped pbap service
08-29 14:21:01.718  3832  3832 V BluetoothPbapService: Pbap Service closeService out
08-29 14:21:01.718  3832  3832 V BluetoothPbapService: Pbap Service onDestroy
08-29 14:21:01.718  3832  3832 V BluetoothPbapService: Pbap Service closeService in
08-29 14:21:01.718  3832  3832 V BluetoothPbapService: Pbap Service closeService out
08-29 14:21:01.718  3832  3832 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 14:21:01.725  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:01.764  2725  2725 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 14:21:01.764  1042  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 14:21:01.765  1042  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 14:21:01.765  1042  2759 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 14:21:01.766  1042  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-29 14:21:01.776  1042  1058 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6888 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 14:21:01.783  6843  6843 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:01.783  6843  6843 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:01.794  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:01.801   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 23.897ms
,08-29 14:21:01.804  1042  1118 D BluetoothManagerService: Message: 20
08-29 14:21:01.804  1042  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d0649eb:true
08-29 14:21:01.819  1042  1118 D BluetoothManagerService: Message: 30
,08-29 14:21:01.821   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 19.147ms
08-29 14:21:01.822  6640  6640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 14:21:01.828  1042  1118 D BluetoothManagerService: Message: 30
08-29 14:21:01.832  6843  6843 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 14:21:01.834  6843  6843 D BluetoothMap: Create BluetoothMap proxy object
08-29 14:21:01.835  1042  1118 D BluetoothManagerService: Message: 30
08-29 14:21:01.838   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 293us total 17.287ms
08-29 14:21:01.839  1042  1118 D BluetoothManagerService: Message: 30
08-29 14:21:01.841  6843  6843 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 14:21:01.843  6843  6843 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-29 14:21:01.859  6843  6843 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-29 14:21:01.862  6843  6843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-29 14:21:01.869  1042  1526 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 14:21:01.869  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:01.869  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:01.869  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 14:21:01.870  1929  1929 D WfdsService: Supplicant Connection state is changed : false
08-29 14:21:01.870  1929  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 14:21:01.870  1929  2288 D WfdsService: Set the WFDS Monitor: false
08-29 14:21:01.870  1929  2288 D WfdsMonitor: WFDS Monitor is stopped
08-29 14:21:01.871  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 14:21:01.872  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 14:21:01.872  1042  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 14:21:01.872  1042  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 14:21:01.873  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:01.873  2457  2457 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:01.874  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:01.877  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:01.880  6843  6843 D DockEventReceiver: finishStartingService: stopping service
08-29 14:21:01.895  6843  6843 D BluetoothInputDevice: Proxy object connected
,08-29 14:21:01.896  6843  6843 D HidProfile: Bluetooth service connected
08-29 14:21:01.897  6843  6843 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:21:01.898  6843  6843 D PanProfile: Bluetooth service connected
08-29 14:21:01.899  6843  6843 D BluetoothMap: Proxy object connected
08-29 14:21:01.899  6843  6843 D MapProfile: Bluetooth service connected
08-29 14:21:01.899  6843  6843 D BluetoothMap: getConnectedDevices()
08-29 14:21:01.901  6843  6843 D BluetoothMap: Bluetooth is Not enabled
08-29 14:21:01.901  6843  6843 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 14:21:01.903  2135  2135 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
08-29 14:21:01.942  1042  1709 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6912 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-29 14:21:01.944  1042  1709 I ActivityManager: Killing 6349:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-29 14:21:02.025  6888  6888 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 14:21:02.025  1042  1892 W libprocessgroup: failed to open /acct/uid_10004/pid_6349/cgroup.procs: No such file or directory
08-29 14:21:02.026  6888  6888 W LG Account v2.2: No ProfileInfo entries
08-29 14:21:02.026  6888  6888 I LG Account v2.2: isEnabled: false
08-29 14:21:02.027  6888  6888 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 14:21:02.027  6888  6888 I Feature : [Lifetracker]Country: EU
08-29 14:21:02.027  6888  6888 I Feature : [Lifetracker]Operator: OPEN
08-29 14:21:02.027  6888  6888 I Feature : [Lifetracker]Ranking support: false
08-29 14:21:02.027  6888  6888 I Feature : [Lifetracker]Comfort support: false
08-29 14:21:02.028  6888  6888 I Feature : [Lifetracker]Accessory: true
08-29 14:21:02.028  6888  6888 I Feature : [Lifetracker]Health device: true
,08-29 14:21:02.028  6888  6888 I Feature : [Lifetracker]Extra Pedometer: false
08-29 14:21:02.028  6888  6888 I Feature : [Lifetracker]Blood glucose device: false
08-29 14:21:02.028  6888  6888 I Feature : [Lifetracker]Device Number: 3
08-29 14:21:02.054  6843  6843 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 14:21:02.062  6912  6912 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:02.067  6843  6843 D BluetoothPermissionRequest: onReceive
,08-29 14:21:02.070  6843  6843 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 14:21:02.087  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 14:21:02.090  1042  1562 I ActivityManager: Killing 6505:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 14:21:02.147  3832  3832 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 14:21:02.148  3832  3832 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 14:21:02.148  3832  3832 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 14:21:02.150  1042  1938 W libprocessgroup: failed to open /acct/uid_10008/pid_6505/cgroup.procs: No such file or directory
,08-29 14:21:02.152  6912  6912 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-29 14:21:02.165  3832  3832 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:02.165  3832  3832 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 14:21:02.168  3832  3832 V BluetoothFtpService: Ftp Service onStartCommand
08-29 14:21:02.168  3832  3832 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:02.169  3832  3832 V BluetoothFtpService: Ftp Service closeService
08-29 14:21:02.169  3832  3832 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 14:21:02.172  3832  3832 V BluetoothFtpService: successfully stopped ftp service
08-29 14:21:02.173  3832  3832 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:02.173  3832  3832 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:02.173  3832  3832 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 14:21:02.173  3832  3832 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:02.173  3832  3832 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 14:21:02.173  3832  3832 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 14:21:02.175  3832  3832 V BluetoothFtpService: Ftp Service onDestroy
08-29 14:21:02.175  3832  3832 V BluetoothFtpService: Ftp Service closeService
08-29 14:21:02.180  3832  3832 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:02.180  3832  3832 V BluetoothSapService: state: 13
08-29 14:21:02.180  3832  3832 V BluetoothSapService: Stopping SAP server process
,08-29 14:21:02.183  3832  3832 V BluetoothSapService: Sap Service closeSapService in
08-29 14:21:02.183  3832  3832 V BluetoothSapService: Close listen Socket : 
,08-29 14:21:02.183  3832  3832 V BluetoothSapService: Close rfcomm Socket : 
08-29 14:21:02.184  3832  3832 V BluetoothSapService: Close sapd  Socket : 
08-29 14:21:02.187  1042  1406 V AlarmManager: RTC_WAKEUP set : Alarm{90111af type 0 when 1472473261282 com.android.vending} when 1472473261282
08-29 14:21:02.226  6912  6912 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 14:21:02.226  6912  6912 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 14:21:02.226  6912  6912 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 14:21:02.227  6912  6912 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 14:21:02.227  6912  6912 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 14:21:02.229  6912  6912 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 14:21:02.230  1042  1983 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6931 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 14:21:02.231  3832  3832 V BluetoothSapService: Sap Service closeSapService out
08-29 14:21:02.232  3832  3832 V BluetoothSapService: Sap Service onDestroy
08-29 14:21:02.232  3832  3832 V BluetoothSapService: Sap Service closeSapService in
08-29 14:21:02.232  3832  3832 V BluetoothSapService: Close listen Socket : 
08-29 14:21:02.232  3832  3832 V BluetoothSapService: Close rfcomm Socket : 
08-29 14:21:02.232  3832  3832 V BluetoothSapService: Close sapd  Socket : 
08-29 14:21:02.232  3832  3832 V BluetoothSapService: Sap Service closeSapService out
,08-29 14:21:02.236  6912  6912 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 14:21:02.246  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:02.253  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:02.259  1042  2005 V SIM_STK : Menu title from STK is T-Mobile
,08-29 14:21:02.267  6912  6912 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 14:21:02.270  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:02.272  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 14:21:02.272  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:02.273  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:02.273  6912  6912 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 14:21:02.275  6912  6912 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 14:21:02.276  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:02.277  6931  6931 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:02.281  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:02.286  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:02.286  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:02.287  6912  6912 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 14:21:02.290  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:02.292  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 14:21:02.292  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:02.292  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:02.298  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:02.303  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:02.308  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:02.308  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:02.310  6912  6912 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 14:21:02.352  1042  1874 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6951 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 14:21:02.468  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:02.471  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:02.480  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:02.481  6104  6104 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 14:21:02.494  1042  1891 I ActivityManager: Killing 6029:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 14:21:02.556  1042  1983 W libprocessgroup: failed to open /acct/uid_10011/pid_6029/cgroup.procs: No such file or directory
,08-29 14:21:02.567  6951  6970 W FormManager: Network not available. Please check & try again.
,08-29 14:21:02.593  6951  6972 V FormManager: Network unavailable.
,08-29 14:21:02.597  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:02.598  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 14:21:02.598  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 14:21:02.598  6951  6972 V FormManager: Network unavailable.
08-29 14:21:02.598  6843  6843 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 14:21:02.600  3832  3950 D bt_hci_bdroid: cleanup
08-29 14:21:02.600  3832  4069 I bt_lpm  : LPM is already off!!!
08-29 14:21:02.600  3832  4160 I bt_userial_mct: exiting userial_read_thread
08-29 14:21:02.600  3832  4160 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 14:21:02.601  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 14:21:02.601  3832  4067 W bt-btif : ag scb idx 1 not allocated
08-29 14:21:02.601  3832  4067 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:02.601  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:02.602  3832  4067 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:02.602  3832  4067 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:02.602  3832  4067 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:21:02.602  3832  4067 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 14:21:02.602  3832  3950 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 14:21:02.602  3832  4069 I bt_vendor: hw_epilog_process
08-29 14:21:02.603  3832  3950 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 14:21:02.603  3832  3950 D bt_userial_mct: userial_close
08-29 14:21:02.603  3832  3950 E bt_userial_mct: pthread_join() FAILED result:3
08-29 14:21:02.603  3832  3950 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 14:21:02.620  6843  6843 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 14:21:02.621  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 14:21:02.621  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 14:21:02.621  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 14:21:02.621  6843  6843 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 14:21:02.622  6843  6843 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 14:21:02.623  1042  1974 I ActivityManager: Killing 6052:com.android.contacts/u0a19 (adj 15): empty #17
,08-29 14:21:02.681  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 14:21:02.681  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:02.683  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:02.683  1042  1947 W libprocessgroup: failed to open /acct/uid_10019/pid_6052/cgroup.procs: No such file or directory
,08-29 14:21:02.692  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:02.692  3832  3950 D bt_hci_bdroid: set_power 0
08-29 14:21:02.692  3832  3950 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 14:21:02.692  3832  3950 I bt_vendor: bluetooth satus is on
08-29 14:21:02.693  3832  3950 I bt_vendor: bt-vendor : resetting BT status
08-29 14:21:02.693  3832  3950 I bt_vendor: Starting hciattach daemon
08-29 14:21:02.693  3832  3950 I bt_vendor: try to set false
08-29 14:21:02.694  3832  3950 I bt_vendor: Starting hciattach daemon
08-29 14:21:02.694  3832  3950 I bt_vendor: try to set false
08-29 14:21:02.694  3832  3950 I bt_vendor: cleanup
08-29 14:21:02.695  3832  4067 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 14:21:02.695  3832  3950 I GKI_LINUX: GKI_exit_task 0 done
08-29 14:21:02.695  3832  3950 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 14:21:02.697  3832  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 14:21:02.704  4305  6976 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 14:21:02.710  4305  6977 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 14:21:02.710  4305  6977 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 14:21:02.714  3832  3832 D HeadsetService: Received stop request...Stopping profile...
,08-29 14:21:02.721  6865  6865 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-29 14:21:02.721  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:02.722  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:02.723  3832  3832 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 14:21:02.723  3832  3832 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 14:21:02.723  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a00ba2
08-29 14:21:02.723  3832  3991 D HeadsetStateMachine: Exit Disconnected: -1
08-29 14:21:02.724  1042  1042 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:02.724  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 14:21:02.725  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:02.725  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:02.725  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:02.727  3832  3832 D A2dpService: Received stop request...Stopping profile...
08-29 14:21:02.727  3832  4050 D A2dpStateMachine: Exit Disconnected: -1
,08-29 14:21:02.729  3832  3832 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 14:21:02.735  3832  3947 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 14:21:02.737  3832  3832 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 14:21:02.737  3832  3832 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 14:21:02.737  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a00ba2
08-29 14:21:02.737  6951  6979 W FormManager: Network not available. Please check & try again.
08-29 14:21:02.738  1042  1042 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:02.738  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 14:21:02.739  3832  3832 D HeadsetStateMachine: Unbinding service...
,08-29 14:21:02.739  6951  6980 V FormManager: Network unavailable.
08-29 14:21:02.744  3832  3832 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 14:21:02.744  3832  3832 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 14:21:02.744  3832  3832 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 14:21:02.744  3832  3832 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 14:21:02.744  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:02.744  3832  3832 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 14:21:02.744  3832  3832 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 14:21:02.744  3832  3832 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 14:21:02.746  3832  3832 D HidService: Received stop request...Stopping profile...
08-29 14:21:02.746  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a00ba2
08-29 14:21:02.747  3832  3832 D HealthService: Received stop request...Stopping profile...
08-29 14:21:02.747  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a00ba2
08-29 14:21:02.749  3832  3832 D PanService: Received stop request...Stopping profile...
08-29 14:21:02.750  6951  6980 V FormManager: Network unavailable.
08-29 14:21:02.750  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a00ba2
08-29 14:21:02.751  3832  3832 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:21:02.753  3832  3832 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 14:21:02.753  3832  3832 D BtGatt.GattService: stop()
08-29 14:21:02.753  3832  3832 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 14:21:02.754  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a00ba2
08-29 14:21:02.756  3832  3832 D BluetoothMapService: Received stop request...Stopping profile...
08-29 14:21:02.756  3832  3832 D BluetoothMapService: stop()
08-29 14:21:02.758  3832  3832 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 14:21:02.758  3832  3832 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 14:21:02.759  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a00ba2
,08-29 14:21:02.760  3832  3832 I BluetoothA2dpServiceJni: cleanupNative
08-29 14:21:02.760  3832  4052 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 14:21:02.761  3832  3832 I GKI_LINUX: GKI_exit_task 2 done
08-29 14:21:02.761  3832  3832 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 14:21:02.761  3832  3832 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:21:02.761  3832  3832 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 14:21:02.761  3832  3832 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 14:21:02.761  3832  3832 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:21:02.761  3832  3832 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:21:02.762  3832  3832 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:21:02.762  3832  3832 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 14:21:02.763  3832  3832 V BluetoothMapService: Handler(): got msg=4
08-29 14:21:02.763  3832  3832 D BluetoothMapService: MAP Service closeService in
08-29 14:21:02.763  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 14:21:02.763  3832  3832 V BluetoothMapService: MAP Service closeService out
08-29 14:21:02.763  3832  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 14:21:02.763  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:02.763  3832  3947 D BluetoothAdapterProperties: Setting state to 10
08-29 14:21:02.763  3832  3947 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 14:21:02.764  3832  3832 D BluetoothMapService: cleanup()
08-29 14:21:02.764  3832  3832 D BluetoothMapService: MAP Service closeService in
08-29 14:21:02.764  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 14:21:02.764  3832  3832 V BluetoothMapService: MAP Service closeService out
08-29 14:21:02.764  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:02.764  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 14:21:02.764  3832  3947 I BluetoothAdapterState: Entering OffState
08-29 14:21:02.764  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 14:21:02.765  6843  6864 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 14:21:02.765  6843  6843 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:21:02.765  6843  6843 D PanProfile: Bluetooth service disconnected
08-29 14:21:02.765  6843  6843 D BluetoothMap: Proxy object disconnected
08-29 14:21:02.765  6843  6843 D MapProfile: Bluetooth service disconnected
08-29 14:21:02.769  6843  6863 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:21:02.771  1042  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:02.773  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 14:21:02.776  6843  6981 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:21:02.777  1839  2420 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:02.777  1839  2656 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 14:21:02.780  6843  6864 D BluetoothMap: onBluetoothStateChange: up=false
08-29 14:21:02.781  1042  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:02.782  1042  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 14:21:02.782  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 14:21:02.785  1042  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 14:21:02.785  1042  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 14:21:02.785  1042  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2b246aa9 mBinding = false
,08-29 14:21:02.786  1042  1118 D BluetoothManagerService: Sending unbind request.
08-29 14:21:02.788  6912  6912 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 14:21:02.789  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 14:21:02.790  6912  6912 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 14:21:02.794  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 14:21:02.797  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 14:21:02.797  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:02.800  3832  3950 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 14:21:02.800  1929  2111 D LGBluetoothAPIService: Message: 2
08-29 14:21:02.800  3832  3832 I GKI_LINUX: GKI_exit_task 1 done
08-29 14:21:02.800  3832  3832 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 14:21:02.801  3832  3832 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 14:21:02.801  1929  2111 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3712747d mBinding = false
08-29 14:21:02.802  1929  2111 D LGBluetoothAPIService: Sending unbind request.
08-29 14:21:02.802  3832  3832 I art     : --- WEIRD: removing null entry 246
08-29 14:21:02.802  3832  3832 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 14:21:02.803  3832  3832 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 14:21:02.803  6843  6843 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 14:21:02.804  6843  6843 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 14:21:02.804  6843  6843 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 14:21:02.805  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:02.805  3832  3832 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 14:21:02.807  6843  6843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 14:21:02.808  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:02.811  3832  3832 I art     : System.exit called, status: 0
08-29 14:21:02.811  3832  3832 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 14:21:02.815  1590  1590 D BluetoothAdapter: 327712165: getState() :  mService = null. Returning STATE_OFF
08-29 14:21:02.815  1590  1590 D BluetoothAdapter: 327712165: getState() :  mService = null. Returning STATE_OFF
,08-29 14:21:02.819  6843  6843 D DockEventReceiver: finishStartingService: stopping service
08-29 14:21:02.832   320  1367 V AudioFlinger: 3832 died, releasing its sessions
08-29 14:21:02.832   320  1367 V AudioFlinger:  pid 1839 @ 0
08-29 14:21:02.832   320  1367 V AudioFlinger:  pid 3433 @ 1
08-29 14:21:02.832   320  1367 V AudioFlinger:  pid 3433 @ 2
08-29 14:21:02.833  6843  6843 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-29 14:21:02.858  6912  6912 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 14:21:02.858  6912  6912 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 14:21:02.865  6912  6912 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 14:21:02.867  6912  6912 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 14:21:02.867  6912  6912 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 14:21:02.867  6912  6912 V SoundPool: doLoad: loading sample sampleID=1
08-29 14:21:02.868  6912  6986 V SoundPool: Start decode
08-29 14:21:02.868  6912  6986 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 14:21:02.868  6912  6912 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 14:21:02.869   320  1702 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 14:21:02.869   320  1702 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 14:21:02.869   320  1702 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 14:21:02.869   320  1702 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 14:21:02.869   320  1702 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 14:21:02.869   320  1702 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 14:21:02.869   320  1702 V MediaPlayerService: player type = 3
08-29 14:21:02.869   320  1702 V AwesomePlayer: AwesomePlayer create()
08-29 14:21:02.869   320  1702 V AwesomePlayer: reset_l() 
08-29 14:21:02.869   320  1702 V AwesomePlayer: cancelPlayerEvents
08-29 14:21:02.869   320  1702 V AwesomePlayer: setAudioSink() 
08-29 14:21:02.869   320  1702 V AwesomePlayer: reset_l() 
08-29 14:21:02.870   320  1702 V AudioCache: notify(0xb5474540, 8, 0, 0)
08-29 14:21:02.870   320  1702 V AudioCache: ignored
08-29 14:21:02.870   320  1702 V AwesomePlayer: cancelPlayerEvents
08-29 14:21:02.870   320  1702 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 14:21:02.870   320  1702 V AwesomePlayer: setDataSource_l dataSource
08-29 14:21:02.870   320  1702 V LGParserOSAL: SniffLGParser start
08-29 14:21:02.870   320  1702 V LGParserOSAL: MainType:5, SubType=0
08-29 14:21:02.870   320  1702 V LGParserOSAL: #### check Mime : application/ogg
08-29 14:21:02.870   320  1702 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 14:21:02.870   320  1702 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 14:21:02.872  1042  1058 I ActivityManager: Process com.android.bluetooth (pid 3832) has died
08-29 14:21:02.873  1042  1058 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-29 14:21:02.880  6761  6761 D UEI.SmartControl: QS Service created
08-29 14:21:02.881  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:02.885  6912  6912 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 14:21:02.894  6912  6912 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 14:21:02.895  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 14:21:02.896  6843  6843 D BluetoothPermissionRequest: onReceive
08-29 14:21:02.899  6843  6843 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 14:21:02.900  6843  6843 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-29 14:21:02.903  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 14:21:02.909  6761  6761 I UEI.SmartControl: Service initServices...
08-29 14:21:02.910  6761  6761 D UEI.SmartControl: QS start get config
,08-29 14:21:02.914  6912  6912 V LGMDMManager: Create singleton instance
08-29 14:21:02.917   320  1702 V LGParserOSAL: supported mime: application/ogg
08-29 14:21:02.917   320  1702 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 14:21:02.917   320  1702 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 14:21:02.917   320  1702 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 14:21:02.917   320  1702 V AwesomePlayer: AudioTrack Setting
08-29 14:21:02.917   320  1702 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 14:21:02.917   320  1702 V AwesomePlayer: setAudioSource() 
08-29 14:21:02.917   320  1702 V MediaPlayerService: prepare
08-29 14:21:02.917   320  1702 V AwesomePlayer: prepareAsync_l() 
08-29 14:21:02.917   320  1702 V MediaPlayerService: wait for prepare
08-29 14:21:02.917   320  6987 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 14:21:02.917   320  6987 V AwesomePlayer: initAudioDecoder() 
08-29 14:21:02.917   320  6987 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 14:21:02.917   320  6987 V AudioSystem: isOffloadSupported()
08-29 14:21:02.917   320  6987 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 14:21:02.917   320  6987 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 14:21:02.917   320  6987 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 14:21:02.917   320  6987 V AwesomePlayer: getUseOffload() = 0 
08-29 14:21:02.917   320  6987 V OMXCodec: OMXCodec::Create
08-29 14:21:02.918   320  6987 V OMXCodec: findMatchingCodecs()
08-29 14:21:02.918   320  6987 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 14:21:02.918   320  6987 V OMXCodec: matchingCodecs.size()=1
08-29 14:21:02.918   320  6987 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 14:21:02.919   320  6987 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 14:21:02.919   320  6987 V LGCodecAdapter: LG Codec Adapter start
08-29 14:21:02.919   320  6987 V OMXCodec: OMXCodec Createtor
08-29 14:21:02.919   320  6987 V OMXCodec: setComponentRole
08-29 14:21:02.919   320  6987 V OMXCodec: configureCodec protected=0
08-29 14:21:02.919   320  6987 V LGCodecAdapter: called getLGCodecSpecificData
08-29 14:21:02.919   320  6987 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 14:21:02.919   320  6987 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 14:21:02.920   320  6987 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 14:21:02.920   320  6987 V LGCodecOSAL: Not support LGCodec
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 14:21:02.920   320  6987 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 14:21:02.920   320  6987 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 14:21:02.920   320  6987 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 14:21:02.920   320  6987 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 14:21:02.920   320  6987 V AudioSystem: isOffloadSupported()
08-29 14:21:02.920   320  6987 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 14:21:02.920   320  6987 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 14:21:02.920   320  6987 V OMXCodec: init()
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 14:21:02.920   320  6987 V OMXCodec: allocateBuffers
08-29 14:21:02.920   320  6987 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-29 14:21:02.920   320  6987 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 14:21:02.920   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 14:21:02.921   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-29 14:21:02.921   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-29 14:21:02.921   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-29 14:21:02.921   320  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-29 14:21:02.921   320  6987 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 14:21:02.921   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 14:21:02.921   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 14:21:02.921   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 14:21:02.921   320  6987 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 14:21:02.921   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 14:21:02.921   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 14:21:02.921   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 14:21:02.921   320  6987 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 14:21:02.921   320  6987 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 14:21:02.921   320  6987 V AudioCache: notify(0xb5474540, 5, 0, 0)
08-29 14:21:02.921   320  6987 V AudioCache: ignored
08-29 14:21:02.921   320  6987 V AudioCache: notify(0xb5474540, 1, 0, 0)
08-29 14:21:02.921   320  6987 V AudioCache: prepared
08-29 14:21:02.921   320  1702 V AudioCache: wait - success
08-29 14:21:02.921   320  1702 V MediaPlayerService: start
08-29 14:21:02.921   320  1702 V AwesomePlayer: play_l() 
08-29 14:21:02.921   320  1702 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 14:21:02.921   320  1702 V AwesomePlayer: createAudioPlayer_l
08-29 14:21:02.921   320  1702 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 14:21:02.921   320  1702 V AwesomePlayer: startAudioPlayer_l() 
08-29 14:21:02.921   320  1702 D AudioPlayer: start of Playback, useOffload 0
08-29 14:21:02.921   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 14:21:02.921   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 14:21:02.924   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 14:21:02.925   320  6989 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-29 14:21:02.925   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on output port
08-29 14:21:02.926   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 14:21:02.926   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 14:21:02.927   320  1702 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 14:21:02.927   320  1702 V AudioCache: notify(0xb5474540, 6, 0, 0)
08-29 14:21:02.927   320  1702 V AudioCache: ignored
08-29 14:21:02.928   320  1702 V MediaPlayerService: wait for playback complete
08-29 14:21:02.931   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.931   320  6990 V AudioCache: memcpy(0xaf006000, 0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: memcpy(0xaf007000, 0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: memcpy(0xaf008000, 0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: memcpy(0xaf009000, 0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.935   320  6990 V AudioCache: memcpy(0xaf00a000, 0xb57ff000, 4096)
08-29 14:21:02.936   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.936   320  6990 V AudioCache: memcpy(0xaf00b000, 0xb57ff000, 4096)
08-29 14:21:02.937   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.937   320  6990 V AudioCache: memcpy(0xaf00c000, 0xb57ff000, 4096)
08-29 14:21:02.937   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.937   320  6990 V AudioCache: memcpy(0xaf00d000, 0xb57ff000, 4096)
08-29 14:21:02.938   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.938   320  6990 V AudioCache: memcpy(0xaf00e000, 0xb57ff000, 4096)
08-29 14:21:02.938   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.938   320  6990 V AudioCache: memcpy(0xaf00f000, 0xb57ff000, 4096)
08-29 14:21:02.939   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.939   320  6990 V AudioCache: memcpy(0xaf010000, 0xb57ff000, 4096)
08-29 14:21:02.939   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.939   320  6990 V AudioCache: memcpy(0xaf011000, 0xb57ff000, 4096)
08-29 14:21:02.939   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.939   320  6990 V AudioCache: memcpy(0xaf012000, 0xb57ff000, 4096)
08-29 14:21:02.940   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.940   320  6990 V AudioCache: memcpy(0xaf013000, 0xb57ff000, 4096)
08-29 14:21:02.940  1042  1562 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6991 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-29 14:21:02.941   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.941   320  6990 V AudioCache: memcpy(0xaf014000, 0xb57ff000, 4096)
08-29 14:21:02.942   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.942   320  6990 V AudioCache: memcpy(0xaf015000, 0xb57ff000, 4096)
08-29 14:21:02.942   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.942   320  6990 V AudioCache: memcpy(0xaf016000, 0xb57ff000, 4096)
08-29 14:21:02.944   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.944   320  6990 V AudioCache: memcpy(0xaf017000, 0xb57ff000, 4096)
08-29 14:21:02.944   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.944   320  6990 V AudioCache: memcpy(0xaf018000, 0xb57ff000, 4096)
08-29 14:21:02.945   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.945   320  6990 V AudioCache: memcpy(0xaf019000, 0xb57ff000, 4096)
08-29 14:21:02.945   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.945   320  6990 V AudioCache: memcpy(0xaf01a000, 0xb57ff000, 4096)
08-29 14:21:02.946   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.946   320  6990 V AudioCache: memcpy(0xaf01b000, 0xb57ff000, 4096)
08-29 14:21:02.946   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.946   320  6990 V AudioCache: memcpy(0xaf01c000, 0xb57ff000, 4096)
08-29 14:21:02.947   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.947   320  6990 V AudioCache: memcpy(0xaf01d000, 0xb57ff000, 4096)
08-29 14:21:02.948   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.948   320  6990 V AudioCache: memcpy(0xaf01e000, 0xb57ff000, 4096)
08-29 14:21:02.948   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.948   320  6990 V AudioCache: memcpy(0xaf01f000, 0xb57ff000, 4096)
08-29 14:21:02.949   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.949   320  6990 V AudioCache: memcpy(0xaf020000, 0xb57ff000, 4096)
08-29 14:21:02.949   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.949   320  6990 V AudioCache: memcpy(0xaf021000, 0xb57ff000, 4096)
08-29 14:21:02.950   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.950   320  6990 V AudioCache: memcpy(0xaf022000, 0xb57ff000, 4096)
08-29 14:21:02.950   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.950   320  6990 V AudioCache: memcpy(0xaf023000, 0xb57ff000, 4096)
08-29 14:21:02.951   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.951   320  6990 V AudioCache: memcpy(0xaf024000, 0xb57ff000, 4096)
08-29 14:21:02.951   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.951   320  6990 V AudioCache: memcpy(0xaf025000, 0xb57ff000, 4096)
,08-29 14:21:02.953   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.953   320  6990 V AudioCache: memcpy(0xaf026000, 0xb57ff000, 4096)
08-29 14:21:02.954   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.954   320  6990 V AudioCache: memcpy(0xaf027000, 0xb57ff000, 4096)
08-29 14:21:02.955   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.955   320  6990 V AudioCache: memcpy(0xaf028000, 0xb57ff000, 4096)
08-29 14:21:02.955   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.955   320  6990 V AudioCache: memcpy(0xaf029000, 0xb57ff000, 4096)
08-29 14:21:02.956   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.956   320  6990 V AudioCache: memcpy(0xaf02a000, 0xb57ff000, 4096)
08-29 14:21:02.956   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.956   320  6990 V AudioCache: memcpy(0xaf02b000, 0xb57ff000, 4096)
08-29 14:21:02.957   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.957   320  6990 V AudioCache: memcpy(0xaf02c000, 0xb57ff000, 4096)
08-29 14:21:02.957   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.957   320  6990 V AudioCache: memcpy(0xaf02d000, 0xb57ff000, 4096)
08-29 14:21:02.958   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.958   320  6990 V AudioCache: memcpy(0xaf02e000, 0xb57ff000, 4096)
08-29 14:21:02.958   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.958   320  6990 V AudioCache: memcpy(0xaf02f000, 0xb57ff000, 4096)
08-29 14:21:02.959   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.959   320  6990 V AudioCache: memcpy(0xaf030000, 0xb57ff000, 4096)
08-29 14:21:02.959   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.959   320  6990 V AudioCache: memcpy(0xaf031000, 0xb57ff000, 4096)
08-29 14:21:02.960   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.960   320  6990 V AudioCache: memcpy(0xaf032000, 0xb57ff000, 4096)
08-29 14:21:02.960   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.960   320  6990 V AudioCache: memcpy(0xaf033000, 0xb57ff000, 4096)
08-29 14:21:02.961   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.961   320  6990 V AudioCache: memcpy(0xaf034000, 0xb57ff000, 4096)
08-29 14:21:02.961   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.961   320  6990 V AudioCache: memcpy(0xaf035000, 0xb57ff000, 4096)
08-29 14:21:02.962   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.962   320  6990 V AudioCache: memcpy(0xaf036000, 0xb57ff000, 4096)
08-29 14:21:02.962   320  6990 V AudioCache: write(0xb57ff000, 4096)
08-29 14:21:02.962   320  6990 V AudioCache: memcpy(0xaf037000, 0xb57ff000, 4096)
08-29 14:21:02.962   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 14:21:02.963   320  6990 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 14:21:02.963   320  6990 V AwesomePlayer: postAudioEOS() 
08-29 14:21:02.963   320  6990 V AudioCache: write(0xb57ff000, 280)
08-29 14:21:02.963   320  6990 V AudioCache: memcpy(0xaf038000, 0xb57ff000, 280)
08-29 14:21:02.967   320  6987 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 14:21:02.967   320  6987 V AwesomePlayer: onStreamDone
08-29 14:21:02.967   320  6987 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 14:21:02.967   320  6987 V AudioCache: notify(0xb5474540, 2, 0, 0)
08-29 14:21:02.967   320  6987 V AudioCache: playback complete
08-29 14:21:02.967   320  6987 V AwesomePlayer: pause_l() 
08-29 14:21:02.967   320  1702 V AudioCache: wait - success
08-29 14:21:02.967   320  6987 V AudioCache: notify(0xb5474540, 7, 0, 0)
08-29 14:21:02.967   320  6987 V AudioCache: ignored
08-29 14:21:02.967   320  6987 V AwesomePlayer: cancelPlayerEvents
08-29 14:21:02.967   320  1702 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-29 14:21:02.969   320  6987 D AudioPlayer: Pause Playback at 1068125
08-29 14:21:02.969   320  1702 V AwesomePlayer: reset_l() 
08-29 14:21:02.969   320  1702 V AudioCache: notify(0xb5474540, 8, 0, 0)
08-29 14:21:02.969   320  1702 V AudioCache: ignored
08-29 14:21:02.969   320  1702 V AwesomePlayer: cancelPlayerEvents
08-29 14:21:02.969   320  1702 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 14:21:02.969   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 14:21:02.969   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 14:21:02.970   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 14:21:02.970   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 14:21:02.970   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 14:21:02.971   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 14:21:02.971   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 14:21:02.971   320  6989 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 14:21:02.971   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 14:21:02.971   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 14:21:02.971   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 14:21:02.972   320  1702 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 14:21:02.972   320  1702 D AudioPlayer: AudioPlayer releasing audio source
08-29 14:21:02.972   320  1702 D AudioPlayer: AudioPlayer done releasing audio source
08-29 14:21:02.972   320  1702 V AwesomePlayer: reset_l() 
08-,29 14:21:02.972   320  1702 V AwesomePlayer: cancelPlayerEvents
08-29 14:21:02.972   320  1702 V AwesomePlayer: ~AwesomePlayer call
08-29 14:21:02.973   320  1702 V AwesomePlayer: reset_l() 
08-29 14:21:02.973   320  1702 V AwesomePlayer: cancelPlayerEvents
08-29 14:21:02.973  6912  6986 V SoundPool: close(31)
08-29 14:21:02.973  6912  6986 V SoundPool: pointer = 0x9fe4f000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 14:21:02.986  6991  6991 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 14:21:02.986  6991  6991 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:02.986  6991  6991 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 14:21:02.987  6991  6991 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 14:21:03.001  6991  6991 D BluetoothAdapterApp: Loading JNI Library
,08-29 14:21:03.014  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-29 14:21:03.018  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 14:21:03.019  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2540
08-29 14:21:03.024  6991  6991 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e3a34bb Instance Count = 1
08-29 14:21:03.028  6991  6991 D BluetoothAdapterApp: onCreate
,08-29 14:21:03.042  6991  6991 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-29 14:21:03.042  6991  6991 D ProfileConfigQcom: Adding HeadsetService
08-29 14:21:03.043  6991  6991 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 14:21:03.043  6991  6991 D ProfileConfigQcom: Adding A2dpService
08-29 14:21:03.043  6991  6991 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 14:21:03.043  6991  6991 D ProfileConfigQcom: Adding HidService
08-29 14:21:03.043  6991  6991 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 14:21:03.043  6991  6991 D ProfileConfigQcom: Adding HealthService
08-29 14:21:03.043  6991  6991 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 14:21:03.044  6991  6991 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 14:21:03.044  6991  6991 D ProfileConfigQcom: Adding PanService
08-29 14:21:03.044  6991  6991 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 14:21:03.044  6991  6991 D ProfileConfigQcom: Adding GattService
08-29 14:21:03.044  6991  6991 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 14:21:03.044  6991  6991 D ProfileConfigQcom: Adding BluetoothMapService
08-29 14:21:03.045  6991  6991 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 14:21:03.046  6991  6991 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 14:21:03.049  6843  6843 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 14:21:03.053  6991  6991 V LGMDMManagerInternal: Create singleton instance
,08-29 14:21:03.148  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:03.153  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:03.154  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:03.154  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 14:21:03.157  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:03.158  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 14:21:03.173  6931  6931 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 14:21:03.195  6761  6761 I UEI.SmartControl: Supports setup maps: true
,08-29 14:21:03.198  6761  6761 D UEI.SmartControl: QS start statue = true Error code = 0
,08-29 14:21:03.198  6761  6761 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 14:21:03.198  6761  6761 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 14:21:03.198  6761  6761 I UEI.SmartControl: ### init IR Blaster...
,08-29 14:21:03.201  6761  6761 D serial_port: Configuring serial port
08-29 14:21:03.201  6761  6761 E UEI.SmartControl: UEIBLaster setting for 616
08-29 14:21:03.201  6761  6761 I UEI.SmartControl: Setting serial record hearder size = 2
,08-29 14:21:03.201  6761  6761 I UEI.SmartControl: configuring settings for MAXQ616
08-29 14:21:03.201  6761  6761 I UEI.SmartControl: Get version...
08-29 14:21:03.218  6761  7010 D UEI.SmartControl: serial port data available: 21
,08-29 14:21:03.244  6761  6761 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-29 14:21:03.245  6761  6761 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 14:21:03.245  6761  6761 I UEI.SmartControl: QS saving settings...
08-29 14:21:03.247  6761  6761 D UEI.SmartControl: IR Blaster version: 25672567
08-29 14:21:03.266  6761  7010 D UEI.SmartControl: serial port data available: 4
,08-29 14:21:03.298  6761  7016 I UEI.SmartControl: Device manager: loading config....
,08-29 14:21:03.300  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 14:21:03.301  6761  7016 D UEI.SmartControl: ----------- loading internal config...
08-29 14:21:03.305  6761  6761 E UEI.SmartControl: Services init done
08-29 14:21:03.305  6761  6761 D UEI.SmartControl: QS Service init finished
08-29 14:21:03.307  6761  6761 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 14:21:03.308  6761  6761 D UEI.SmartControl: QS Service version code: 201091
08-29 14:21:03.310  6761  6761 D UEI.SmartControl: Service requested: Control
08-29 14:21:03.317  6761  7016 E UEI.SmartControl: Loading SETTINGS...
,08-29 14:21:03.321  6761  6761 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-29 14:21:03.327  6912  6912 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 14:21:03.330  6761  6776 I UEI.SmartControl: ------ IControl API: 11
08-29 14:21:03.330  6761  6776 D UEI.SmartControl: File observer start...
08-29 14:21:03.331  6761  6776 E UEI.SmartControl: IR Port is disabled: false
,08-29 14:21:03.332  6761  6776 D UEI.SmartControl: Starting file observer...
08-29 14:21:03.340  6761  6776 I UEI.SmartControl: Registering callback...
08-29 14:21:03.341  6761  6761 D UEI.SmartControl: Internal service binding...
08-29 14:21:03.343  6761  7016 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 14:21:03.345  6761  6785 I UEI.SmartControl: ------ IControl API: 19
08-29 14:21:03.346  6761  6785 I UEI.SmartControl: Registering Services Ready callback...
08-29 14:21:03.361  6761  7015 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 14:21:03.362  6912  6928 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-29 14:21:03.363  6912  6984 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 14:21:03.363  6912  6984 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 14:21:03.364  6761  7015 D UEI.SmartControl: -----service ready thread exits
08-29 14:21:03.364  6912  6912 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 14:21:03.364  6912  6912 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 14:21:03.364  6761  6776 I UEI.SmartControl: ------ IControl API: 8
08-29 14:21:03.366  6912  6912 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 14:21:03.366  6912  6912 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 14:21:03.367  6912  6912 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 14:21:03.367  6912  6912 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 14:21:03.368  6912  6912 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 14:21:03.368  6912  6912 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 14:21:03.369  6912  6912 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 14:21:03.372  6912  6912 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 14:21:03.373  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 14:21:03.374  6912  6912 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 14:21:03.374  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 14:21:03.375  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 14:21:03.376  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 14:21:03.377  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 14:21:03.378  6912  6912 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472473263378]
08-29 14:21:03.381  6912  6912 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 14:21:03.384  1042  1938 I ActivityManager: Killing 6080:com.android.gallery3d/u0a27 (adj 15): empty #17
08-29 14:21:03.403  6912  7021 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 14:21:03.473  1042  1938 I ActivityManager: Killing 6555:com.lge.email/u0a23 (adj 15): empty #18
,08-29 14:21:03.528  1042  1709 W libprocessgroup: failed to open /acct/uid_10027/pid_6080/cgroup.procs: No such file or directory
,08-29 14:21:03.534  1042  1798 W libprocessgroup: failed to open /acct/uid_10023/pid_6555/cgroup.procs: No such file or directory
,08-29 14:21:03.541  6912  6912 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-29 14:21:03.543  6912  6912 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 14:21:03.544  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 14:21:03.545  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 14:21:03.545  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 14:21:03.546  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 14:21:03.547  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 14:21:03.566  6912  6912 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 14:21:04.445  1042  1562 D WifiServiceImplEx: setWifiEnabled: true pid=6640, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 14:21:04.446  1042  1562 D WifiService: setWifiEnabled: true pid=6640, uid=10118
,08-29 14:21:04.447  1042  1562 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:21:04.470  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 14:21:04.470  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 14:21:04.470  1042  1042 D Ulp_jni : JNI:system_update. Event-4
,08-29 14:21:04.474  1042  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 14:21:04.474  1042  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 14:21:04.477  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 14:21:04.477  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 14:21:04.477  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 14:21:04.477  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 14:21:04.477  1042  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 14:21:04.477  1042  1526 E WifiHW  : unknown target_country: EU , set to default
08-29 14:21:04.477  1042  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 14:21:04.477  1042  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 14:21:04.477  1042  1526 I WifiUtil: gEnableBmps=1
08-29 14:21:04.502  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:04.508  1042  1118 D Tethering: MasterInitialState.processMessage what=3
08-29 14:21:04.519  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:04.523  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:04.527  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:04.530  1042  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:04.534  1042  1118 D Tethering: MasterInitialState.processMessage what=3
,08-29 14:21:04.546  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:04.547  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:04.550  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 14:21:04.560  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 14:21:04.567  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 14:21:04.568  6459  6492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 14:21:04.596  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:04.633  1042  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:04.684  1042  1058 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7048 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 14:21:04.691  1042  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:04.691  1042  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 14:21:04.752  7048  7048 I AppUp4:AppBoxCP: onCreate
,08-29 14:21:04.753  7048  7048 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 14:21:04.763  7048  7048 I AppUp4:DB:  setFingerPrint start
,08-29 14:21:04.763  7048  7048 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 14:21:04.771  7048  7048 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 14:21:04.771  7048  7048 I AppUp4:DB:  SDK version = 21
08-29 14:21:04.771  7048  7048 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 14:21:04.774  7048  7048 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 14:21:04.775  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 14:21:04.775  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:04.778  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 14:21:04.778  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 14:21:04.783  7048  7048 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 14:21:04.836  7048  7048 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:04.836  7048  7048 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:04.846  7048  7048 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@125bf36d
08-29 14:21:04.846  7048  7048 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 14:21:04.846  7048  7048 D AppUp4:CustFacade: isPhone : true
08-29 14:21:04.847  7048  7048 D AppUp4:CustModeStarterReceiver: begin check event
08-29 14:21:04.848  7048  7048 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-29 14:21:04.848  7048  7048 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-29 14:21:04.849  7048  7067 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-29 14:21:04.849  7048  7067 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 14:21:04.850  7048  7067 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 14:21:04.851  1042  1974 I ActivityManager: Killing 6145:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-29 14:21:04.911  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:04.911  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:04.913  1042  1910 W libprocessgroup: failed to open /acct/uid_10080/pid_6145/cgroup.procs: No such file or directory
08-29 14:21:04.914  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 14:21:04.924  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:04.939  4305  7070 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 14:21:04.943  4305  7071 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:04.943  4305  7071 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 14:21:05.019  1042  1058 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7072 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 14:21:05.090  7072  7072 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 14:21:05.091  7072  7072 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:05.093  7072  7072 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 14:21:05.093  7072  7072 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 14:21:05.185  1042  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 14:21:05.186  1042  1118 D Tethering: InitialState.processMessage what=4
,08-29 14:21:05.189   315   911 D SoftapController: Softap fwReload - Ok
08-29 14:21:05.192  1042  1526 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (708ms)
08-29 14:21:05.193  1042  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:21:05.194   315   911 D CommandListener: Setting iface cfg
08-29 14:21:05.194   315   911 D CommandListener: Trying to bring down wlan0
08-29 14:21:05.195   315   911 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:21:05.198  1042  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 14:21:05.201  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:05.201  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:05.201  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 14:21:05.202  1042  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 14:21:05.202  1042  1526 D WifiMonitor: connecting to supplicant
08-29 14:21:05.203  1042  1526 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 14:21:05.198  7098  7098 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:05.208  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:05.198  7098  7098 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:05.209  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 14:21:05.213  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:05.214  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:05.212  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 14:21:05.224  7072  7072 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 14:21:05.228  7098  7098 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 14:21:05.240  7072  7072 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 14:21:05.252  7098  7098 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 14:21:05.252  7098  7098 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 14:21:05.269  7072  7072 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 14:21:05.298  7072  7072 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:05.298  7072  7072 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:05.318  7098  7098 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 14:21:05.371  7098  7098 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 14:21:05.385  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-29 14:21:05.390  7098  7098 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-29 14:21:05.400  7072  7072 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 14:21:05.428  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 14:21:05.428  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:05.429  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 14:21:05.432  7072  7072 I HubEmail: JNI_OnLoad()
08-29 14:21:05.433  7072  7072 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 14:21:05.433  7072  7072 I HubEmail: registerNatives()
08-29 14:21:05.433  7072  7072 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 14:21:05.433  7072  7072 I HubEmail: registerNativeMethods()
08-29 14:21:05.433  7072  7072 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 14:21:05.433  7072  7072 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 14:21:05.516  1042  1891 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7111 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 14:21:05.544  7072  7107 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:05.544  6951  7106 V FormManager: Network unavailable.
08-29 14:21:05.545  6951  7105 W FormManager: Network not available. Please check & try again.
,08-29 14:21:05.548  6951  7106 V FormManager: Network unavailable.
08-29 14:21:05.554  1042  1562 I ActivityManager: Killing 6588:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 14:21:05.588  1042  2020 W libprocessgroup: failed to open /acct/uid_10061/pid_6588/cgroup.procs: No such file or directory
,08-29 14:21:05.663  7111  7111 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:05.663  7111  7111 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:05.667  7111  7111 D PhoneMonitor: Register our PhoneStateListener
08-29 14:21:05.688  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 14:21:05.690  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 14:21:05.725  7111  7111 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 14:21:05.726  7111  7111 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 14:21:05.729  7111  7111 D TelephonyAutoProfiling: [parse] Load xml
08-29 14:21:05.731  1042  1974 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7131 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 14:21:05.731  1042  1974 I ActivityManager: Killing 6175:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-29 14:21:05.746  7111  7111 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 14:21:05.746  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 14:21:05.747  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 14:21:05.747  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 14:21:05.747  7111  7111 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 14:21:05.747  7111  7111 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-29 14:21:05.759  7111  7111 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-29 14:21:05.798  1042  1983 W libprocessgroup: failed to open /acct/uid_10097/pid_6175/cgroup.procs: No such file or directory
08-29 14:21:06.007  1042  1983 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7149 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 14:21:06.011  1042  1983 I ActivityManager: Killing 6671:com.lge.eula/1000 (adj 15): empty #17
08-29 14:21:06.053  1042  1892 W libprocessgroup: failed to open /acct/uid_1000/pid_6671/cgroup.procs: No such file or directory
,08-29 14:21:06.086  7098  7098 E wpa_supplicant: USIM:  scard_init function
08-29 14:21:06.086  7098  7098 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 14:21:06.178  1042  1910 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7166 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 14:21:06.179  1042  1910 I ActivityManager: Killing 6706:com.lge.bnr/1000 (adj 15): empty #17
,08-29 14:21:06.203  7098  7098 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 14:21:06.210  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 14:21:06.211  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 14:21:06.211  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 14:21:06.212  1042  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 14:21:06.213  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.213  7098  7098 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 14:21:06.214  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 14:21:06.215  1042  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.217  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.218  1042  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.219  1042  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,08-29 14:21:06.219  1042  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 14:21:06.220  1042  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 14:21:06.221  1042  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 14:21:06.222  1042  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 14:21:06.222  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:06.223  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:06.223  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 14:21:06.223  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 14:21:06.223  1042  7176 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 14:21:06.223  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 14:21:06.224  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 14:21:06.224  1042  7176 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 14:21:06.224  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:06.224  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:06.253  1042  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 14:21:06.254  1042  1709 W libprocessgroup: failed to open /acct/uid_1000/pid_6706/cgroup.procs: No such file or directory
,08-29 14:21:06.256  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:06.256  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:06.256  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 14:21:06.261  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.262  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.262  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.262  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.262  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 14:21:06.262  1042  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 14:21:06.263  1042  1526 D WifiNative-wlan0: SET update_config 1: returned true
08-29 14:21:06.263  1042  1526 D WifiConfigStore: Loading config and enabling all networks 
08-29 14:21:06.263  1042  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 14:21:06.263  1042  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-29 14:21:06.265  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.266  1929  1929 D WfdService: Waiting for WifiP2p enabling
,08-29 14:21:06.270  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 14:21:06.270  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.270  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:06.270  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.270  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:06.271  1042  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 14:21:06.271  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.271  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:06.271  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.271  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:06.276  1042  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-29 14:21:06.286  1042  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 14:21:06.286  1042  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 14:21:06.287  1042  1526 D WifiStateMachine: enableVerboseLogging : level 2
,08-29 14:21:06.287  1042  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 14:21:06.288  1042  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 14:21:06.288  1042  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 14:21:06.288  1042  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 14:21:06.288  1042  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 14:21:06.288  1042  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 14:21:06.288  1042  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 14:21:06.289  1042  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 14:21:06.289  1042  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 14:21:06.289  1042  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 14:21:06.289  1042  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 14:21:06.290  1042  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 14:21:06.290  1042  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 14:21:06.290  1042  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 14:21:06.290  1042  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 14:21:06.291  1042  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 14:21:06.291  1929  1929 D WfdsService: Supplicant Connection state is changed : true
08-29 14:21:06.291  1929  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 14:21:06.291  1929  2288 D WfdsService: Set the WFDS Monitor: true
08-29 14:21:06.291  1929  2288 D WfdsMonitor: WfdsMonitorThread create
08-29 14:21:06.291  1929  2288 D WfdsMonitor: WFDS Monitor is created and started
08-29 14:21:06.291  1042  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 14:21:06.291  1929  2288 D WfdsService: WiFi: Supplicant connection re-established
08-29 14:21:06.291  1042  1526 D WifiNative-HAL: Setting external_sim to 1
08-29 14:21:06.291  1042  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 14:21:06.292  1042  1526 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 14:21:06.292  1042  1526 I WifiNative-HAL: startHal
08-29 14:21:06.292  1042  1526 D wifi    : setting scan oui 0xaf6cfcc0
08-29 14:21:06.293  1042  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 14:21:06.293  1929  7184 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 14:21:06.293  1042  1526 I WifiNative-HAL: startHal
08-29 14:21:06.293  1042  1526 D wifi    : setting scan oui 0xaf6cfcc0
08-29 14:21:06.293  1042  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 14:21:06.293  1929  7184 E CtrlSupplicant: Succeed to open control connection
08-29 14:21:06.293  1929  7184 E CtrlSupplicant: Succeed to open monitor connection
08-29 14:21:06.294  1042  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 14:21:06.294  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 14:21:06.294  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 14:21:06.294  1929  7184 D WfdsMonitor: Supplicant connection established
08-29 14:21:06.295  1929  2288 D WfdsService: Connected to the supplicant for wfds
,08-29 14:21:06.296  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 14:21:06.296  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 14:21:06.296  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 14:21:06.297  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 14:21:06.297  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 14:21:06.297  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 14:21:06.298  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 14:21:06.298  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 14:21:06.298  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 14:21:06.298  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 14:21:06.298  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 14:21:06.299  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 14:21:06.299  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 14:21:06.299  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 14:21:06.299  7098  7098 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 14:21:06.300  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 14:21:06.300  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 14:21:06.300  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 14:21:06.300  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 14:21:06.301  1042  1526 E WifiNative: : [121,202,752 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 14:21:06.301  1042  1526 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 14:21:06.301  7166  7166 I art     : Almond Protected OAT
08-29 14:21:06.302  1042  1526 D WifiNative-wlan0: RECONNECT: returned true
08-29 14:21:06.302  1042  1526 D WifiNative-wlan0: doString: [STATUS]
08-29 14:21:06.303  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:06.303  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:06.304  1042  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 14:21:06.304  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:06.304  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
08-29 14:21:06.304  1042  1524 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.305  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 14:21:06.305  1042  1042 D RttService: SCAN_AVAILABLE : 3
08-29 14:21:06.306  1042  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.306  1042  1543 I WifiNative-HAL: startHal
08-29 14:21:06.306  1042  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6cfcc0
08-29 14:21:06.306  1042  1543 D wifi    : failed to get capabilities : -3
08-29 14:21:06.306  1042  1543 E WifiScanningService: could not get scan capabilities
08-29 14:21:06.306  1042  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.306  1042  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 14:21:06.306  1042  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 14:21:06.307  1042  1526 E WifiStateMachine:  ConnectModeState CMD_S,TART_DRIVER 0 0
08-29 14:21:06.307  1042  1526 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 14:21:06.308   315   911 D CommandListener: Setting iface cfg
08-29 14:21:06.308   315   911 D CommandListener: Trying to bring up p2p0
08-29 14:21:06.308  1042  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121210  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 14:21:06.308  1042  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 14:21:06.308  1042  1524 D LGWifiP2pService: P2pEnablingState
08-29 14:21:06.308  1042  1524 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:06.308  1042  1524 D LGWifiP2pService: P2p socket connection successful
08-29 14:21:06.308  1042  1524 D LGWifiP2pService: P2pEnabledState
08-29 14:21:06.312  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.312  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.312  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 14:21:06.313  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.313  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:06.314  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.315  1042  1524 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 14:21:06.315  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 14:21:06.315  1929  1929 D WfdsService: WifiP2pState is changed : true
08-29 14:21:06.315  1042  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 14:21:06.315  1929  2288 D WfdsService: Receive the WFDS_ENABLE Method
08-29 14:21:06.315  1929  2288 D WfdsService: Set the WFDS Monitor: true
08-29 14:21:06.315  1929  2288 D WfdsService: Connected to the supplicant for wfds
08-29 14:21:06.315  1929  2288 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 14:21:06.315  7098  7098 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 14:21:06.316  1929  2288 D WfdsService: selectPreferredScanChannel [36]
08-29 14:21:06.316  1929  2288 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 14:21:06.316  1042  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 14:21:06.316  1042  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 14:21:06.316  1042  1524 D WifiNative-p2p0: SET device_name G3: returned true
08-29 14:21:06.316  1042  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 14:21:06.316  1042  1524 D LGWifiP2pService: before postfix = G3
08-29 14:21:06.316  1042  1524 D WifiServerServiceExt: postfix byte check : 2
08-29 14:21:06.316  1042  1524 D LGWifiP2pService: after postfix = G3
,08-29 14:21:06.316  1042  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 14:21:06.317  1042  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 14:21:06.317  1042  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 14:21:06.317  1042  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 14:21:06.317  1042  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 14:21:06.318  1042  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 14:21:06.318  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 14:21:06.318  1042  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 14:21:06.318  1042  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 14:21:06.318  1042  1524 D WifiNative-HAL: p2pGetDeviceAddress
08-29 14:21:06.318  1929  1929 D WfdsService: isConnected: false
08-29 14:21:06.318  1042  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 14:21:06.319  1042  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 14:21:06.319  1042  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 14:21:06.320  1042  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 14:21:06.320  1042  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 14:21:06.320  1042  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 14:21:06.320  1042  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 14:21:06.321  1042  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 14:21:06.321  1042  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 14:21:06.321  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121221  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 14:21:06.321  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 14:21:06.322  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 14:21:06.322  1929  1929 D WfdsService: Update P2p Interface State: 3
08-29 14:21:06.322  1042  1526 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121224
08-29 14:21:06.323  1042  1526 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121225
08-29 14:21:06.323  1042  1526 D WifiNative-wlan0: doString: [STATUS]
08-29 14:21:06.332  1042  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 14:21:06.332  1042  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 14:21:06.332  1042  1524 D LGWifiP2pService: InactiveState
08-29 14:21:06.333  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:06.333  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:06.334  1042  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 14:21:06.335  1042  1526 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 14:21:06.335  1042  1524 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.335  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.335  1042  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-29 14:21:06.337  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 14:21:06.338  7098  7098 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:06.338  1042  7176 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 14:21:06.338  1042  7176 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:06.338  1042  7176 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:06.339  1042  7176 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:06.339  7098  7098 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 14:21:06.339  7098  7098 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.339  1042  7176 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:06.339  1042  7176 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.339  1042  7176 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.339  1042  7176 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.340  7098  7098 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.340  1042  7176 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:06.340  1042  7176 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.340  1042  7176 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.340  1042  7176 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:06.341  1929  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 14:21:06.341  1929  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:06.341  1929  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:06.342  1042  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 14:21:06.342  1042  1524 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.342  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.342  1042  1524 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.342  1042  1524 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.342  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.343  1042  1524 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.342  1042  1526 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 14:21:06.343  1042  1526 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 14:21:06.343  1042  1524 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.343  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.343  1042  1524 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.343  1042  1524 D LGWifiP2pService: InactiveStat,e{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.343  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.343  1042  1524 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.344  1042  1042 E WifiServerServiceExt: No p2p device connected
08-29 14:21:06.345  1929  2288 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 14:21:06.347  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.347  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:06.347  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.347  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.348  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 14:21:06.349  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 14:21:06.353  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.353  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.353  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-29 14:21:06.363  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.363  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.363  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 14:21:06.367  1042  1526 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 14:21:06.367  1042  1532 D ConnectivityService: Got NetworkAgent Messenger
08-29 14:21:06.367  1042  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:06.367  1042  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 14:21:06.367  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 14:21:06.367  1042  1532 D ConnectivityService: NetworkAgent connected
08-29 14:21:06.367  1042  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 14:21:06.367  1042  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 14:21:06.372  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.373  1042  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-29 14:21:06.373  1042  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:06.373  1042  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 14:21:06.373  1042  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 14:21:06.374  1042  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 14:21:06.372  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:06.375  7166  7166 D WeatherApplication: removeAccount
,08-29 14:21:06.377  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 14:21:06.378  7166  7166 D WeatherApplication: Account.length = 0
08-29 14:21:06.378  7166  7166 E WeatherApplication: OPERATOR:OPEN
08-29 14:21:06.379  1042  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 14:21:06.379  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.379  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:06.380   315   911 D CommandListener: Setting iface cfg
08-29 14:21:06.381  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.383  1042  1526 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 14:21:06.384  1042  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=121285  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.384  1042  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=121286  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.384  7166  7166 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:6
08-29 14:21:06.385  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=121286  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.385  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.386  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.386  1042  1526 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.386  1042  1526 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.387  1042  7191 D DhcpStateMachine: StoppedState
08-29 14:21:06.387  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.387  1042  7191 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.387  1042  7191 D DhcpStateMachine: WaitBeforeStartState
08-29 14:21:06.387  1042  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:06.387  7166  7166 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 14:21:06.388  7166  7166 D Weather.Utils: 2 : All the weather widget is gone.
08-29 14:21:06.388  1042  1526 E WifiStateMachine:  ObtainingIpState what:132106 1 0
,08-29 14:21:06.390  1042  1526 E WifiStateMachine:  L2ConnectedState what:132106 1 0
08-29 14:21:06.390  1042  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 14:21:06.391  1042  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 14:21:06.391  1042  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 14:21:06.391  7098  7098 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 14:21:06.392  7166  7166 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 14:21:06.392  1042  1526 E WifiStateMachine:  ObtainingIpState what:132096 -100 0
08-29 14:21:06.392  1042  1526 E WifiStateMachine:  L2ConnectedState what:132096 -100 0
08-29 14:21:06.393  1042  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 14:21:06.393  1042  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 14:21:06.393  1042  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 14:21:06.393  7098  7098 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 14:21:06.394  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:06.395  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:06.395  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
08-29 14:21:06.395  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 14:21:06.395  7166  7166 D WeatherAncestor: connectivity changed - connection : true
08-29 14:21:06.396  1042  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 14:21:06.396  1042  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 14:21:06.396  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 14:21:06.396  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 14:21:06.397  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 14:21:06.397  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 14:21:06.397  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 14:21:06.397  1042  7176 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 14:21:06.397  1042  7176 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 14:21:06.398  1042  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 14:21:06.398  1042  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 14:21:06.398  1042  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 14:21:06.398  1042  1526 D WifiNative-wlan0: doBoolean: SCAN
08-29 14:21:06.399  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 14:21:06.399  7166  7166 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 14:21:06.399  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-29 14:21:06.399  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 14:21:06.399  1042  7176 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 14:21:06.399  1042  7176 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 14:21:06.399  1042  1526 D WifiNative-wlan0: SCAN: returned true
08-29 14:21:06.400  1042  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=121301  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.400  1042  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=121302  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.401  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=121302  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.401  1042  1526 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:06.402  1042  1526 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:06.402  1042  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:06.403  1042  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:06.403  1042  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:06.403  1042  1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:06.404  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:06.404  1042  1042 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 14:21:06.404  1042  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=121306  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.405  1042  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=121307  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.406  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=121307  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:06.407  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75712] from screen [on:0 period:-700516121] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 14:21:06.407  7166  7166 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 14:21:06.408  7166  7166 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 14:21:06.408  7166  7166 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-29 14:21:06.408  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-700516120] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 14:21:06.408  1042  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 14:21:06.429  7166  7166 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 14:21:06.430  7166  7166 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:6
,08-29 14:21:06.481  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.481  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.481  1042  1524 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:06.484  1042  1974 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7194 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 14:21:06.486  1042  1974 I ActivityManager: Killing 2135:com.lge.music/u0a34 (adj 15): empty #17
08-29 14:21:06.505   343   343 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 385us total 18.136ms
,08-29 14:21:06.519   320  1366 V AudioFlinger: 2135 died, releasing its sessions
08-29 14:21:06.519   320  1366 V AudioFlinger:  pid 1839 @ 0
08-29 14:21:06.519   320  1366 V AudioFlinger:  pid 3433 @ 1
08-29 14:21:06.519   320  1366 V AudioFlinger:  pid 3433 @ 2
,08-29 14:21:06.520   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 290us total 15.121ms
08-29 14:21:06.533   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 256us total 12.379ms
,08-29 14:21:06.543  1042  1562 W libprocessgroup: failed to open /acct/uid_10034/pid_2135/cgroup.procs: No such file or directory
,08-29 14:21:06.554  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.556  1042  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 14:21:06.557  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.558  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.559  1042  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.559  1042  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.560  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.561  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.562  1042  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 14:21:06.562  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:06.562  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 14:21:06.563  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-29 14:21:06.564  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-29 14:21:06.564  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 14:21:06.565  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 14:21:06.566  1042  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 14:21:06.566  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 14:21:06.567  1042  1526 D WifiNative-wlan0: SET ps 0: returned true
08-29 14:21:06.567  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,08-29 14:21:06.568  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 14:21:06.570  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 14:21:06.570  1042  7176 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 14:21:06.570  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 14:21:06.570  1042  1526 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 14:21:06.570  1042  1526 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 14:21:06.570  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c1248fe target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.571  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c1248fe target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.571  1042  7191 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.571  1042  7191 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 14:21:06.571  1042  1526 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 14:21:06.572  1929  7184 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-29 14:21:06.573   315   911 D CommandListener: Setting iface cfg
08-29 14:21:06.573  1042  7176 E WifiMonitor: WifiMonitor:p2p0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 14:21:06.573  1042  7176 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 14:21:06.573  1042  7176 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-29 14:21:06.573   315   911 D CommandListener: Trying to bring up wlan0
08-29 14:21:06.573  1042  7176 E WifiMonitor: WifiMonitor:p2p0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
08-29 14:21:06.573  1042  7176 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 14:21:06.573  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.573  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.573  1042  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.573  1929  7184 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-29 14:21:06.574  1042  1526 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 14:21:06.575  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-29 14:21:06.575  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 14:21:06.577  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:06.577  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 14:21:06.577  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 14:21:06.578  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 14:21:06.578  1042  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 14:21:06.579  1042  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 14:21:06.582  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 14:21:06.583  1042  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-29 14:21:06.583  1042  1526 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 14:21:06.584  1042  1526 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 14:21:06.584  1042  1526 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 14:21:06.584  1042  1526 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 14:21:06.585  1042  1526 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 14:21:06.585  1042  1526 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 14:21:06.591  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.592  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.592  1042  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 14:21:06.593  1042  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.593  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.594  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:06.594  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 14:21:06.595  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 14:21:06.595  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.595  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.595  1042  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 14:21:06.595  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 14:21:06.596  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 14:21:06.596  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 14:21:06.596  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 14:21:06.596  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 14:21:06.597  1042  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 14:21:06.597  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:06.613  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
08-29 14:21:06.613  1042  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 14:21:06.614  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 14:21:06.614  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 14:21:06.614  1042  1526 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 14:21:06.614  1042  1532 D ConnectivityService: ignoring duplicate network state non-change
,08-29 14:21:06.618  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.618  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.618  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 14:21:06.619  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 14:21:06.620  1042  1526 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 14:21:06.620  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.621  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:06.621  1042  1532 D ConnectivityService: Adding iface wlan0 to network 101
08-29 14:21:06.622  1042  1526 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:06.623  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:06.624  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.624   280   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 14:21:06.624   280   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 14:21:06.624   280   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 14:21:06.626  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.626  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:06.626  7194  7212 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 14:21:06.626  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.626  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.626  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 14:21:06.627  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 14:21:06.629  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 14:21:06.632  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 14:21:06.634  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.634  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.634  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 14:21:06.635  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 14:21:06.640  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.640  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.640  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 14:21:06.647   280   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 14:21:06.647   280   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 14:21:06.647   280   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 14:21:06.647  7194  7212 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 14:21:06.647  1042  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 14:21:06.647  1042  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 14:21:06.648  1042  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 14:21:06.649   315   911 E Netd    : netlink response contains error (File exists)
,08-29 14:21:06.650  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.650  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 14:21:06.650  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.651  1042  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 14:21:06.652  1042  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 14:21:06.652  1042  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 14:21:06.652  1042  1532 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 14:21:06.653  1042  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 14:21:06.653  1042  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 14:21:06.653  1042  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 14:21:06.653  1042  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 14:21:06.653  1042  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:06.653  1042  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:06.654  1042  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 14:21:06.654  1042  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:06.654  1042  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 14:21:06.654  1042  1532 D ConnectivityService: currentScore = 0, newScore = 20
08-29 14:21:06.654  1042  1532 D ConnectivityService:    accepting network in place of null
08-29 14:21:06.654  1042  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:06.655  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.655  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 14:21:06.655  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:06.655  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 14:21:06.655  1042  1526 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:06.655  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:06.655  1042  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:06.655  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 14:21:06.656  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.656  1839  1839 D Te,lephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:06.657  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 14:21:06.657   315  7219 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 14:21:06.658  1042  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 14:21:06.658  1042  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 14:21:06.658  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 14:21:06.658  1042  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:06.658  1042  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 14:21:06.659  1042  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 14:21:06.659  1042  1042 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 14:21:06.660  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 14:21:06.660  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 14:21:06.660  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 14:21:06.660  1042  1532 D ConnectivityService: validation of new default Network = false
08-29 14:21:06.660  1042  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 14:21:06.660  1042  1532 D DSQN    : enableDataServiceNotify 
08-29 14:21:06.660  1042  1532 D DSQN    : start dsqn bin
,08-29 14:21:06.667  1042  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 14:21:06.667  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:06.667  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:06.668  1042  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:06.658  7221  7221 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:06.658  7221  7221 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:06.671  1590  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 14:21:06.677   280   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 14:21:06.677   280   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-29 14:21:06.677   280   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 14:21:06.678  7194  7220 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 14:21:06.685  7221  7221 E DSQN    : DSQN ssw
08-29 14:21:06.686  1042  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 14:21:06.687   280   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 14:21:06.687   280   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 14:21:06.687   280   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 14:21:06.688  7194  7220 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-29 14:21:06.694  1804  7223 I CheckinService: active receiver: enabled
,08-29 14:21:06.703  1804  7223 I CheckinService: Preparing to send checkin request
,08-29 14:21:06.703  1804  7223 I EventLogService: Accumulating logs since 1472473203191
08-29 14:21:06.706  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 14:21:06.706  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.707  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:06.740  1804  7223 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-29 14:21:06.772  1042  7191 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 14:21:06.773  1042  7191 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 14:21:06.773  1042  7191 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 14:21:06.768  7234  7234 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:06.768  7234  7234 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:06.783  7234  7234 I dhcpcd  : version 5.5.6 starting
08-29 14:21:06.784  7234  7234 E dhcpcd  : get_duid: m
08-29 14:21:06.784  7234  7234 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 14:21:06.785  7234  7234 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 14:21:06.846  1042  1974 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7247 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-29 14:21:06.854  7234  7234 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-29 14:21:06.854  7234  7234 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 14:21:06.854  7234  7234 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 14:21:06.855  7234  7234 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 14:21:06.855  7234  7234 D dhcpcd  : wlan0: sending REQUEST (xid 0x5f8a5660), next in 3.19 seconds
08-29 14:21:06.869  7194  7194 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 14:21:06.875  7194  7194 I LibraryLoader: Loading: webviewchromium
08-29 14:21:06.879  7194  7194 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1792-1796)
08-29 14:21:06.879  7194  7194 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:21:06.884  7194  7194 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8dce34c}
,08-29 14:21:06.885  7194  7194 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:21:06.886  7194  7194 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 14:21:06.892  7247  7247 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 14:21:06.893  7247  7247 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-29 14:21:06.896  7194  7194 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 14:21:06.897  7194  7194 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 14:21:06.906  7194  7194 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 14:21:06.907  7234  7234 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 14:21:06.907  7194  7194 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 14:21:06.907  7194  7194 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-29 14:21:06.911  7247  7247 I MultiDex: VM with version 2.1.0 has multidex support
08-29 14:21:06.911  7247  7247 I MultiDex: install
08-29 14:21:06.911  7247  7247 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 14:21:06.913   320   320 V AudioPolicyService: registerClient() client 0xb04108e0, uid 10093
08-29 14:21:06.917  7194  7194 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 14:21:06.917  7194  7194 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 14:21:06.917  7194  7194 I Adreno-EGL: Build Date: 12/12/14 금
08-29 14:21:06.917  7194  7194 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 14:21:06.917  7194  7194 I Adreno-EGL: Remote Branch: 
08-29 14:21:06.917  7194  7194 I Adreno-EGL: Local Patches: 
08-29 14:21:06.917  7194  7194 I Adreno-EGL: Reconstruct Branch: 
08-29 14:21:06.918  7247  7247 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-29 14:21:06.919  7234  7234 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 14:21:06.919  7234  7234 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 14:21:06.919  7234  7234 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 14:21:06.919  7234  7234 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 14:21:06.920  7234  7234 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 14:21:06.920  7234  7234 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 14:21:06.920  7234  7234 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 14:21:06.920  7234  7234 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-29 14:21:06.921  7194  7270 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 14:21:06.985  7194  7194 I NSApplication: Starting up...
,08-29 14:21:07.044  1042  1798 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7301 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 14:21:07.045  1042  1058 I ActivityManager: Killing 6104:com.android.vending/u0a44 (adj 15): empty #17
,08-29 14:21:07.135  1042  1974 W libprocessgroup: failed to open /acct/uid_10044/pid_6104/cgroup.procs: No such file or directory
,08-29 14:21:07.139  1042  1406 V AlarmManager: ELAPSED_WAKEUP set : Alarm{bb3eb99 type 2 when 121972 com.google.android.gms} when 121972
,08-29 14:21:07.149   315  7219 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 14:21:07.173  7301  7301 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 14:21:07.175  1042  7191 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 14:21:07.177  1042  7191 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 14:21:07.177  1042  7191 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 14:21:07.177  1042  7191 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 14:21:07.177  1042  7191 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 14:21:07.177  1042  7191 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 14:21:07.177  1042  7191 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 14:21:07.177  1042  7191 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 14:21:07.177  1042  7191 D DhcpStateMachine: RunningState
,08-29 14:21:07.269  7247  7264 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:07.270  7247  7264 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:07.322  7323  7323 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 14:21:07.359  1042  1709 I art     : Explicit concurrent mark sweep GC freed 79875(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.676ms total 131.355ms
,08-29 14:21:07.381  7323  7323 I dex2oat : dex2oat took 59.025ms (threads: 4)
,08-29 14:21:07.396  7247  7264 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 14:21:07.396  7247  7264 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 14:21:07.396  7247  7264 I Adreno-EGL: Build Date: 12/12/14 금
08-29 14:21:07.396  7247  7264 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 14:21:07.396  7247  7264 I Adreno-EGL: Remote Branch: 
08-29 14:21:07.396  7247  7264 I Adreno-EGL: Local Patches: 
08-29 14:21:07.396  7247  7264 I Adreno-EGL: Reconstruct Branch: 
,08-29 14:21:07.467  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 14:21:07.468  6459  6492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 14:21:07.477  1042  1562 D WifiServiceImplEx: setWifiEnabled: false pid=6640, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 14:21:07.477  1042  1562 D WifiService: setWifiEnabled: false pid=6640, uid=10118
08-29 14:21:07.477  1042  1562 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 14:21:07.478  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:07.484  1042  1892 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-29 14:21:07.486  1042  1526 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:07.486  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 14:21:07.487  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 14:21:07.487  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-29 14:21:07.487  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:07.487  1042  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:07.487  1042  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:07.488  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 14:21:07.488  1042  1526 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 14:21:07.488  1042  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:07.488  1042  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 14:21:07.488  1042  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 14:21:07.489  1042  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 14:21:07.493  1042  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 14:21:07.493  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.493  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.493  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-29 14:21:07.493  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 14:21:07.493  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 14:21:07.493  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:07.494  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
08-29 14:21:07.494  1042  7191 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.496   315  7342 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 14:21:07.496   315  7342 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-29 14:21:07.500   315   911 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:21:07.524  7247  7264 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 14:21:07.524  7247  7264 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 14:21:07.524  7247  7264 I Adreno-EGL: Build Date: 12/12/14 금
08-29 14:21:07.524  7247  7264 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 14:21:07.524  7247  7264 I Adreno-EGL: Remote Branch: 
08-29 14:21:07.524  7247  7264 I Adreno-EGL: Local Patches: 
08-29 14:21:07.524  7247  7264 I Adreno-EGL: Reconstruct Branch: 
08-29 14:21:07.533  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 14:21:07.533  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:07.534  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 14:21:07.534  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 14:21:07.537  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 14:21:07.537  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-29 14:21:07.538  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-29 14:21:07.555  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-29 14:21:07.556  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:07.557  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.557  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 14:21:07.557  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-29 14:21:07.557  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.557  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.557  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 14:21:07.558  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:07.558  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:07.561  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 14:21:07.561  1042  1042 D RttService: SCAN_AVAILABLE : 1
08-29 14:21:07.562  1042  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.562  1042  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.563  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.563  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.563  1042  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@28a331d3
08-29 14:21:07.563  1042  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:07.563  1042  1524 D LGWifiP2pService: P2pDisablingState
08-29 14:21:07.563  1042  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:07.563  1042  1524 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.563  1042  1524 D LGWifiP2pService: p2p socket connection lost
08-29 14:21:07.563  1042  1524 D LGWifiP2pService: P2pDisabledState
08-29 14:21:07.563  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:07.564  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:07.564  1042  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:07.565  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:07.565  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:07.565  1042  1526 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 14:21:07.565  1042  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 14:21:07.565  1042  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.565  1042  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.565  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 14:21:07.565  7098  7098 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 14:21:07.566  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 14:21:07.566  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:07.566  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
08-29 14:21:07.566  7048  7048 I App,Up4:CustModeStarterReceiver: onReceive
,08-29 14:21:07.571  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 14:21:07.571  1929  1929 D WfdsService: WifiP2pState is changed : false
08-29 14:21:07.571  1929  2288 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 14:21:07.571  1929  2288 D WfdsService: Set the WFDS Monitor: false
08-29 14:21:07.572  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:07.572  1929  2288 D WfdsMonitor: WFDS Monitor is stopped
08-29 14:21:07.572  1929  2288 D WfdsService: STATE : WfdsDisabledState - enter
08-29 14:21:07.572  1929  2290 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 14:21:07.572  1929  7184 D CtrlSupplicant: Received on exit socket, terminate
08-29 14:21:07.572  1929  7184 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 14:21:07.573  1929  7184 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 14:21:07.573  1929  7184 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 14:21:07.574  1929  2288 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 14:21:07.578  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:07.578  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:07.579  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 14:21:07.583   315   911 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:21:07.583  1042  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 14:21:07.583  1042  1532 D DSQN    : disableDataServiceNotify
08-29 14:21:07.583  1042  1532 D DSQN    : stop dsqn bin
08-29 14:21:07.589  1042  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 14:21:07.589  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:07.589  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:07.589  1042  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:07.590  1042  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 14:21:07.590  1042  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 14:21:07.590  1042  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 14:21:07.590  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 14:21:07.590  1590  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 14:21:07.591  1042  1526 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 14:21:07.592  7048  7048 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@125bf36d
08-29 14:21:07.592  7048  7048 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-29 14:21:07.592  7048  7048 D AppUp4:CustFacade: isPhone : true
08-29 14:21:07.592  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-29 14:21:07.593  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.593  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.593  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 14:21:07.593  7048  7048 D AppUp4:CustModeStarterReceiver: begin check event
08-29 14:21:07.593  7048  7048 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 14:21:07.593  1042  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:07.593  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 14:21:07.593  1042  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:07.593  1042  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:07.593  1042  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:07.593  1042  1532 D NetworkManagementService: Removing idletimer
08-29 14:21:07.593  1042  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.594  1042  1532 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 14:21:07.594  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:07.594  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 14:21:07.595  1042  1526 D WifiNative-p2p0: TERMINATE: returned true
08-29 14:21:07.595  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:07.595  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:07.595  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 14:21:07.598  1042  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 14:21:07.599  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 14:21:07.599  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 14:21:07.599  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 14:21:07.599  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 14:21:07.601  1042  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 14:21:07.601  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 14:21:07.601  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 14:21:07.601  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:07.601  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
,08-29 14:21:07.601  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 14:21:07.601  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 14:21:07.602  1042  1526 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:07.602  1042  1526 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:07.602  1042  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:07.603  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 14:21:07.604  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 14:21:07.607  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:07.607  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:07.607  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:07.607  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:07.608  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:07.608  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:07.608  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:07.608  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:07.609  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:07.610  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:07.611  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:07.615  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 14:21:07.615  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:07.615  1042  1042 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 14:21:07.617  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android,.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 14:21:07.625  4305  7357 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 14:21:07.630  4305  7358 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:07.630  4305  7358 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 14:21:07.642  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 14:21:07.643  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:07.643  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:07.651  7072  7072 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 14:21:07.668  1042  1532 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 14:21:07.671  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 14:21:07.671  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:07.671  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 14:21:07.674  7072  7359 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.676  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 14:21:07.677  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:07.677  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:07.677  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:07.679  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 14:21:07.679  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 14:21:07.681  6951  7362 W FormManager: Network not available. Please check & try again.
08-29 14:21:07.683  7098  7098 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 14:21:07.683  7098  7098 I wpa_supplicant: monitor socket send errors count : 1
08-29 14:21:07.683  7098  7098 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-4\x00 that cannot receive messages
,08-29 14:21:07.684  1042  7176 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 14:21:07.685  1042  7176 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 14:21:07.690  6951  7363 V FormManager: Network unavailable.
08-29 14:21:07.690  7166  7166 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:7
,08-29 14:21:07.691  6951  7363 V FormManager: Network unavailable.
08-29 14:21:07.692  7166  7166 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 14:21:07.692  7166  7166 D Weather.Utils: 2 : All the weather widget is gone.
08-29 14:21:07.692  7166  7166 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 14:21:07.692  7166  7166 D WeatherAncestor: connectivity changed - connection : true
08-29 14:21:07.692  7166  7166 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@10fc8033
08-29 14:21:07.693  7166  7166 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 14:21:07.693  7166  7166 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 14:21:07.693  7166  7166 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 14:21:07.693  7166  7166 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 14:21:07.693  7166  7166 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:7
,08-29 14:21:07.706  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 14:21:07.706  7098  7098 W wpa_supplicant: USIM:  scard_deinit function
08-29 14:21:07.707  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 14:21:07.707  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 14:21:07.707  1042  7176 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 14:21:07.707  1042  7176 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 14:21:07.707  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:07.707  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:07.707  1042  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122609
08-29 14:21:07.708  1042  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122610
08-29 14:21:07.708  1042  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122610  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 14:21:07.708  1042  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122610  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 14:21:07.708  1042  1118 D Tethering: InitialState.processMessage what=4
08-29 14:21:07.710  1042  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:21:07.710  1042  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:07.710  1042  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:07.710  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:07.710  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 14:21:07.710  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 14:21:07.710  6843  6843 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 14:21:07.711  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 14:21:07.713  6843  6843 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 14:21:07.713  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 14:21:07.713  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 14:21:07.713  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 14:21:07.713  6843  6843 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 14:21:07.713  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 14:21:07.713  6843  6843 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 14:21:07.719  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:07.722  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:07.724  6951  7366 W FormManager: Network not available. Please check & try again.
08-29 14:21:07.728  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:07.732  6951  7367 V FormManager: Network unavailable.
,08-29 14:21:07.734  1042  7191 D DhcpStateMachine: StoppedState
08-29 14:21:07.734  1042  7191 D DhcpStateMachine: StoppedState{ when=-168ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:07.735  1042  1526 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 14:21:07.735  1042  1526 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 14:21:07.736  6951  7367 V FormManager: Network unavailable.
08-29 14:21:07.742  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:07.744  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:07.747  6951  7369 W FormManager: Network not available. Please check & try again.
08-29 14:21:07.749  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:07.754  6951  7370 V FormManager: Network unavailable.
08-29 14:21:07.756  6951  7370 V FormManager: Network unavailable.
,08-29 14:21:07.763  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 14:21:07.763  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:07.764  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:07.767  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:07.770  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 14:21:07.774  4305  7371 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 14:21:07.775  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:07.776  4305  7372 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 14:21:07.776  4305  7372 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 14:21:07.781  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 14:21:07.788  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:07.788  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:07.789  6912  6912 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:07.813  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 14:21:07.814  1042  7176 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-29 14:21:07.814  1042  7176 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 14:21:07.814  1042  7176 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 14:21:07.815  1042  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 38 0
08-29 14:21:07.818  1042  1983 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7373 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 14:21:07.855  7247  7264 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 14:21:07.855  7247  7264 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 14:21:07.855  7247  7264 I Adreno-EGL: Build Date: 12/12/14 금
08-29 14:21:07.855  7247  7264 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 14:21:07.855  7247  7264 I Adreno-EGL: Remote Branch: 
08-29 14:21:07.855  7247  7264 I Adreno-EGL: Local Patches: 
08-29 14:21:07.855  7247  7264 I Adreno-EGL: Reconstruct Branch: 
,08-29 14:21:07.917  1042  1526 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 14:21:07.917  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:07.917  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:07.917  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 14:21:07.918  1929  1929 D WfdsService: Supplicant Connection state is changed : false
08-29 14:21:07.918  1929  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 14:21:07.918  1929  2288 D WfdsService: Set the WFDS Monitor: false
08-29 14:21:07.918  1929  2288 D WfdsMonitor: WFDS Monitor is stopped
08-29 14:21:07.919  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:07.920  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 14:21:07.921  2457  2457 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:07.922  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 14:21:07.923  1042  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 14:21:07.923  1042  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 14:21:07.923  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:07.924  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:07.931  7373  7373 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 14:21:07.932  7373  7373 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 14:21:07.942  7373  7373 V [BNRBootReceiver]: Boot Receiver Return
08-29 14:21:07.944  7373  7373 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 14:21:07.945   315  7392 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 14:21:07.945  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 14:21:07.946  1804  7223 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-29 14:21:07.946  1042  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 14:21:07.955  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:07.956  1804  7223 I CheckinService: active receiver: disabled
,08-29 14:21:07.960  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:07.975  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 14:21:07.975  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:07.975  6912  6912 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:07.981  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:07.995  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.003  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 14:21:08.011  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:08.011  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:08.012  6912  6912 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 14:21:08.016  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:08.026  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.033  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.041  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:08.041  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:08.042  6912  6912 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 14:21:08.048  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 14:21:08.053  6843  6843 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-29 14:21:08.066  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:08.094  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.103  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.114  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:08.115  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:08.119  1042  1526 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:08.119  1042  1526 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 14:21:08.123  6912  6912 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:08.131  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 14:21:08.146  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.157  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.170  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:08.172  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:08.174  6912  6912 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 14:21:08.179  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:08.191  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 14:21:08.208  1042  1531 D WifiService: New client listening to asynchronous messages
08-29 14:21:08.209  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:08.219  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.236  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.250  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 14:21:08.251  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:08.255  6912  6912 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 14:21:08.258  6912  6912 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 14:21:08.259  6912  6912 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 14:21:08.272  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 14:21:08.286  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 14:21:08.289  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:08.299  6761  7017 D UEI.SmartControl: Internal timer expired: 2
08-29 14:21:08.299  6761  7017 D UEI.SmartControl: unbind internal service
08-29 14:21:08.302  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.319  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.335  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:08.336  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:08.337  6912  6912 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 14:21:08.339  6912  6912 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 14:21:08.340  6912  6912 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 14:21:08.349  1042  2020 I ActivityManager: Killing 6888:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-29 14:21:08.407  1042  1798 W libprocessgroup: failed to open /acct/uid_10037/pid_6888/cgroup.procs: No such file or directory
,08-29 14:21:08.414  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-29 14:21:08.429  2195  2195 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 14:21:08.430  2195  2195 D c       : Getting all permits...
,08-29 14:21:08.430  2195  2195 D a       : Opening database...
08-29 14:21:08.437  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-29 14:21:08.438  2195  2195 D a       : Closing database...
08-29 14:21:08.441  6761  7011 D serial_port: close(fd = 24)
08-29 14:21:08.445  6761  7011 I UEI.SmartControl: Serial port is closed.
,08-29 14:21:08.459  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 14:21:08.462   315  7400 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 14:21:08.465  1042  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 14:21:08.473  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 14:21:08.473  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:08.473  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:08.480  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:08.486  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 14:21:08.498  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:08.498  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:08.502  6912  6912 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 14:21:08.507  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:08.515  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 14:21:08.515  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:08.515  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:08.523  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.531  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.540  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:08.541  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:08.545  6912  6912 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 14:21:08.552  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:08.561  6865  6865 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 14:21:08.561  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:08.562  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:08.569  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:08.577  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.588  6912  6912 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 14:21:08.589  6912  6912 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:08.592  6912  6912 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 14:21:08.612  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:08.618  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:08.631  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.632  6951  7402 W FormManager: Network not available. Please check & try again.
08-29 14:21:08.666  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:08.666  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 14:21:08.666  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 14:21:08.666  6843  6843 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-29 14:21:08.667  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 14:21:08.669  6843  6843 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 14:21:08.669  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 14:21:08.669  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 14:21:08.669  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 14:21:08.669  6843  6843 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 14:21:08.669  6843  6843 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 14:21:08.678  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 14:21:08.678  6951  7403 V FormManager: Network unavailable.
08-29 14:21:08.679  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:08.683  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:08.684  6951  7403 V FormManager: Network unavailable.
,08-29 14:21:08.688  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 14:21:08.700  4305  7404 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 14:21:08.700  6865  6865 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 14:21:08.700  6865  6865 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 14:21:08.700  6865  6865 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:08.704  4305  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 14:21:08.705  4305  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 14:21:08.706  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:08.717  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:08.727  6951  7407 W FormManager: Network not available. Please check & try again.
,08-29 14:21:08.736  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-29 14:21:08.738  6951  7408 V FormManager: Network unavailable.
08-29 14:21:08.743  6951  7408 V FormManager: Network unavailable.
,08-29 14:21:09.559  1042  1526 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-700512970] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 14:21:09.561  1042  1526 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-700512967] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 14:21:09.661  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:09.674  1042  1118 D Tethering: MasterInitialState.processMessage what=3
08-29 14:21:09.682  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:09.686  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:09.690  1042  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:09.692  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 14:21:09.694  6459  6492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 14:21:09.706  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 14:21:09.723  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:09.768  1042  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 14:21:09.773  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 14:21:09.774  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:09.774  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 14:21:09.774  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 14:21:09.776  7048  7048 I AppUp4:CustModeStarterReceiver: onReceive
08-29 14:21:09.780  7048  7048 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@125bf36d
08-29 14:21:09.780  7048  7048 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 14:21:09.780  7048  7048 D AppUp4:CustFacade: isPhone : true
08-29 14:21:09.781  7048  7048 D AppUp4:CustModeStarterReceiver: begin check event
08-29 14:21:09.781  7048  7048 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-29 14:21:09.789  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:09.789  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:09.791  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:09.793  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 14:21:09.803  7072  7072 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 14:21:09.827  4305  7427 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 14:21:09.835  4305  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:09.836  4305  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 14:21:09.837  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 14:21:09.837  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:09.838  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 14:21:09.838  3433  3433 D PhoneState: setPdpRejectCasuse : false
08-29 14:21:09.840  7072  7431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:09.840  6951  7430 V FormManager: Network unavailable.
,08-29 14:21:09.843  6951  7429 W FormManager: Network not available. Please check & try again.
08-29 14:21:09.847  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-29 14:21:09.848  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 14:21:09.849  6951  7430 V FormManager: Network unavailable.
,08-29 14:21:09.864  7166  7166 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:9
,08-29 14:21:09.866  7166  7166 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 14:21:09.866  7166  7166 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 14:21:09.867  7166  7166 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 14:21:09.867  7166  7166 D WeatherAncestor: connectivity changed - connection : true
,08-29 14:21:09.867  7166  7166 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@10fc8033
,08-29 14:21:09.868  7166  7166 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 14:21:09.868  7166  7166 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 14:21:09.868  7166  7166 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 14:21:09.868  7166  7166 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 14:21:09.868  7166  7166 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:9
08-29 14:21:10.491  1042  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 14:21:10.505  1042  2020 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 14:21:10.524  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 14:21:10.524  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 14:21:10.524  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-29 14:21:10.525  1042  1118 D BluetoothManagerService: Message: 1
08-29 14:21:10.525  1042  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 14:21:10.551  1042  1118 D BluetoothManagerService: Message: 20
08-29 14:21:10.552  1042  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e968b3b:true
,08-29 14:21:10.556  6991  6991 D BluetoothAdapterState: make
08-29 14:21:10.560  6991  6991 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 14:21:10.561  6991  6991 I bluedroid-qcom: init
08-29 14:21:10.562  6991  7448 I BluetoothAdapterState: Entering OffState
08-29 14:21:10.562  6991  6991 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 14:21:10.563  6991  6991 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 14:21:10.563  6991  6991 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 14:21:10.563  6991  6991 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 14:21:10.563  6991  6991 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 14:21:10.565  6991  6991 I bluedroid-qcom: get_profile_interface socket
08-29 14:21:10.565  6991  6991 I bluedroid-qcom: get_profile_interface map_client
,08-29 14:21:10.569  6991  7452 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 14:21:10.573  6991  7452 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 14:21:10.568  7451  7451 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:10.568  7451  7451 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:10.582  7451  7451 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 14:21:10.582  7451  7451 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 14:21:10.582  7451  7451 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-29 14:21:10.588  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 14:21:10.588  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 14:21:10.589  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 14:21:10.589  1042  1118 D BluetoothManagerService: Message: 40
08-29 14:21:10.589  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 14:21:10.590  6991  7007 I bluedroid-qcom: config_hci_snoop_log
08-29 14:21:10.591  1042  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 14:21:10.591  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 14:21:10.592  7451  7451 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 14:21:10.594  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.596  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:10.602  7451  7451 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 14:21:10.603  7451  7451 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 14:21:10.611  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:10.615  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:10.624  6991  7448 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-29 14:21:10.626  1042  1118 D Tethering: MasterInitialState.processMessage what=3
08-29 14:21:10.630  1042  1118 D Tethering: MasterInitialState.processMessage what=3
08-29 14:21:10.631  6991  7452 D BluetoothAdapterProperties: Name is: G3
08-29 14:21:10.632  6991  7448 D BluetoothAdapterProperties: Setting state to 11
08-29 14:21:10.632  6991  7448 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 14:21:10.633  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:10.633  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 14:21:10.633  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 14:21:10.634  6991  7448 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 14:21:10.654  1042  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:10.663  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:10.664  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:10.665  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:10.666  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:10.668  6843  6843 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 14:21:10.668  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 14:21:10.670  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:10.673  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 14:21:10.674  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 14:21:10.675  6991  7448 D BluetoothBondStateMachine: make
08-29 14:21:10.677  1042  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.677  6991  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:10.677  6991  7469 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 14:21:10.677  6991  7448 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 14:21:10.677  6991  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
,08-29 14:21:10.677  6991  7448 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 14:21:10.678  6459  6492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 14:21:10.678  6991  7448 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 14:21:10.680  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 14:21:10.681  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:10.681  6991  6991 V BluetoothPbapReceiver: ***********state = 11
08-29 14:21:10.684  6991  7448 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:10.688  1042  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:10.688  1042  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 14:21:10.690  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:10.691  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 14:21:10.696  6991  6991 D HeadsetService: Received start request. Starting profile...
08-29 14:21:10.697  6991  7448 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:10.697  6991  6991 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 14:21:10.697  6991  6991 D LGBluetoothHfpAdapter: Version 1.6
08-29 14:21:10.700  6991  6991 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 14:21:10.703  6991  6991 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 14:21:10.703  6991  6991 D HeadsetStateMachine: make
,08-29 14:21:10.730  6991  6991 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:10.730  6991  6991 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:10.740  1042  1891 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7471 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 14:21:10.742  6991  6991 D HeadsetStateMachine: max_hf_connections = 1
08-29 14:21:10.743  6991  6991 I bluedroid-qcom: get_profile_interface handsfree
08-29 14:21:10.745  6991  7448 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:10.748  6991  6991 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-29 14:21:10.749   320  1366 V AudioPolicyService: registerClient() client 0xb0410b40, uid 1002
08-29 14:21:10.750   320   320 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 14:21:10.750   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 14:21:10.750   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 14:21:10.750  6991  6991 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 14:21:10.752   320  1367 V AudioFlinger: registerClient() client 0xb55815f8, pid 6991
08-29 14:21:10.753   320  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:10.753   320  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:10.753  6991  6991 V ToneGenerator: Create Track: 0xb4928a80
08-29 14:21:10.753   320  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:10.753  6991  6991 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 14:21:10.753  6991  6991 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 14:21:10.753   320  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:10.753  6991  7006 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:10.753  6991  7006 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 14:21:10.753   320  1367 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 14:21:10.753   320  1367 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 14:21:10.753   320  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 14:21:10.753   320  1367 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 14:21:10.753  6991  7006 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:10.753  1590  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:10.753  1590  2084 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:10.753  6991  7006 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 14:21:10.754  1590  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:10.754  1590  2084 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:10.754  1042  1874 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:10.754  1042  1874 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:10.754  1042  1874 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:10.754  1042  1874 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:10.754  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:10.754   320  1366 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 14:21:10.754  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:10.754   320  1702 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 14:21:10.754   320  1702 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 14:21:10.754  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:10.754   320  1702 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 14:21:10.754   320  1702 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 14:21:10.754  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:10.754  6991  6991 V AudioSystem: getLatency() output 2, latency 50
08-29 14:21:10.754  6991  6991 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 14:21:10.754  6991  6991 V AudioTrac,k: createTrack_l() output 2 afLatency 50
08-29 14:21:10.754  6991  7448 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:10.754  3433  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:10.754  3433  3454 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:10.754   320  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 14:21:10.754   320  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 14:21:10.754   320  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 14:21:10.754   320  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 14:21:10.754   320  1367 V AudioFlinger: createTrack() lSessionId: 22
08-29 14:21:10.755  3433  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:10.755  3433  3454 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:10.758  6991  6991 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 14:21:10.758  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.758   320  1366 V AudioFlinger: acquiring 22 from 6991, for 6991
08-29 14:21:10.758   320  1366 V AudioFlinger:  added new entry for 22
08-29 14:21:10.758  6991  6991 V ToneGenerator: ToneGenerator INIT OK, time: 125676
08-29 14:21:10.759  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:10.761  6991  7470 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 14:21:10.761  6991  7470 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 14:21:10.761  6991  7470 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 14:21:10.761  6991  7470 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 14:21:10.761   320  1702 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6991
08-29 14:21:10.762   320  1702 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 14:21:10.762   320  1702 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 14:21:10.762   320  1702 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 14:21:10.762   320  1702 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 14:21:10.762   320  1702 V voice   : voice_set_parameters: exit with code(0)
08-29 14:21:10.762   320  1702 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 14:21:10.762   320  1702 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 14:21:10.762   320  1702 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 14:21:10.762   320  1702 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 14:21:10.762   320  1702 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 14:21:10.762   320  1702 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 14:21:10.763  6991  7470 V ToneGenerator: ToneGenerator destructor
08-29 14:21:10.763  6991  7470 V ToneGenerator: stopTone
08-29 14:21:10.763  6991  7470 V ToneGenerator: Delete Track: 0xb4928a80
,08-29 14:21:10.764  6991  7470 V AudioTrack: ~AudioTrack, releasing session id from 6991 on behalf of 6991
08-29 14:21:10.764   320  1366 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 14:21:10.765   320  1366 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 14:21:10.765   320  1366 V AudioFlinger: PlaybackThread::Track destructor
08-29 14:21:10.765   320  1366 V AudioFlinger: removeClient_l() pid 6991, calling pid 320
08-29 14:21:10.765   320   320 V AudioFlinger: releasing 22 from 6991 for 6991
08-29 14:21:10.765   320   320 V AudioFlinger:  decremented refcount to 0
08-29 14:21:10.765   320  1272 V AudioPolicyService: AudioCommandThread() waking up
08-29 14:21:10.765   320   320 V AudioFlinger: purging stale effects
08-29 14:21:10.765   320  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 14:21:10.765   320  1272 V AudioPolicyManager: releaseOutput() 2
08-29 14:21:10.765   320  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 14:21:10.767  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:10.768  6991  6991 D HeadsetStateMachine: Proxy object connected
08-29 14:21:10.768  6991  7448 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:10.769  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 14:21:10.769  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.769  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 14:21:10.769  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 14:21:10.769  6991  6991 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 14:21:10.770  6991  6991 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 14:21:10.772  7048  7048 I AppUp4:CustModeStarterReceiver: onReceive
08-29 14:21:10.773  6991  7448 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:10.780  6991  6991 D A2dpService: Received start request. Starting profile...
,08-29 14:21:10.780  6991  6991 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 14:21:10.781  6991  6991 V Avrcp   : make
08-29 14:21:10.782  6991  6991 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 14:21:10.782  6991  6991 I bluedroid-qcom: get_profile_interface avrcp
08-29 14:21:10.784  6991  7448 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:10.786  7048  7048 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@125bf36d
08-29 14:21:10.786  7048  7048 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 14:21:10.786  7048  7048 D AppUp4:CustFacade: isPhone : true
08-29 14:21:10.791  6991  6991 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 14:21:10.793  6991  6991 E AudioManager: No RCC entry present to update
08-29 14:21:10.793  7048  7048 D AppUp4:CustModeStarterReceiver: begin check event
08-29 14:21:10.793  6991  6991 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 14:21:10.793  7048  7048 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 14:21:10.795  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.795  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:10.796  6991  6991 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 14:21:10.797  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:10.797  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 14:21:10.797  6991  6991 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 14:21:10.799  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:10.803  4305  7493 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 14:21:10.806  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 14:21:10.807  6991  7448 V LGMDMManager: Create singleton instance
08-29 14:21:10.808  7072  7072 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 14:21:10.809  6991  7448 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 14:21:10.814  4305  7494 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.814  4305  7494 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 14:21:10.881  6951  7497 W FormManager: Network not available. Please check & try again.
,08-29 14:21:10.884  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 14:21:10.884  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.884  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 14:21:10.887  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 14:21:10.888  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 14:21:10.889  6951  7498 V FormManager: Network unavailable.
08-29 14:21:10.890  7072  7495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:10.896  1042  1947 V SIM_STK : Menu title from STK is T-Mobile
08-29 14:21:10.896  1042  1947 V SIM_STK : Menu title from STK is T-Mobile
,08-29 14:21:10.904  6951  7498 V FormManager: Network unavailable.
08-29 14:21:10.908  7166  7166 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:10
,08-29 14:21:10.910  7471  7471 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 14:21:10.910  7471  7471 W LG Account v2.2: No ProfileInfo entries
08-29 14:21:10.910  7471  7471 I LG Account v2.2: isEnabled: false
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Country: EU
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Operator: OPEN
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Ranking support: false
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Comfort support: false
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Accessory: true
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Health device: true
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Extra Pedometer: false
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Blood glucose device: false
08-29 14:21:10.911  7471  7471 I Feature : [Lifetracker]Device Number: 3
08-29 14:21:10.914  7166  7166 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 14:21:10.915  7166  7166 D Weather.Utils: 2 : All the weather widget is gone.
08-29 14:21:10.915  7166  7166 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 14:21:10.915  7166  7166 D WeatherAncestor: connectivity changed - connection : true
08-29 14:21:10.915  7166  7166 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@10fc8033
08-29 14:21:10.916  7166  7166 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 14:21:10.917  7166  7166 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 14:21:10.918  6843  6843 D BluetoothPermissionRequest: onReceive
08-29 14:21:10.918  7166  7166 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 14:21:10.918  7166  7166 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 14:21:10.919  7166  7166 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:10
08-29 14:21:10.921  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 14:21:10.944  6459  6459 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 14:21:10.946  6459  6492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 14:21:10.959  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:10.965  1042  1562 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 14:21:10.968  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 14:21:10.969  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.969  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 14:21:10.969  7048  7048 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 14:21:10.970  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 14:21:10.970  7048  7048 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 14:21:10.973  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 14:21:10.973  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 14:21:10.973  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 14:21:10.973  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 14:21:10.973  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 14:21:10.973  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 14:21:10.974  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 14:21:10.974  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 14:21:10.974  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 14:21:10.974  7048  7048 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@125bf36d
08-29 14:21:10.974  7048  7048 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 14:21:10.974  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 14:21:10.974  7048  7048 D AppUp4:CustFacade: isPhone : true
08-29 14:21:10.974  7048  7048 D AppUp4:CustModeStarterReceiver: begin check event
08-29 14:21:10.974  6991  6991 I BluetoothA2dpServiceJni: classInitNative
08-29 14:21:10.974  6991  6991 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 14:21:10.974  7048  7048 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 14:21:10.974  6991  6991 D A2dpStateMachine: make
08-29 14:21:10.976  6991  6991 I bluedroid-qcom: get_profile_interface a2dp
08-29 14:21:10.976  6991  7503 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 14:21:10.977  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.977  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:10.978  6991  6991 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 14:21:10.978  6991  6991 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 14:21:10.979  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:10.979  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:10.979  6991  7502 D A2dpStateMachine: Enter Disconnected: -2
08-29 14:21:10.980  6991  6991 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 14:21:10.981  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:10.982  6991  6991 D HidService: Received start request. Starting profile...
08-29 14:21:10.983  6991  6991 I bluedroid-qcom: get_profile_interface hidhost
,08-29 14:21:10.984  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:10.985  6991  7470 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 14:21:10.986  6991  7470 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 14:21:10.986  6991  7470 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 14:21:10.986  6991  6991 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 14:21:10.987  7072  7072 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 14:21:10.987  6991  6991 D HealthService: Received start request. Starting profile...
08-29 14:21:10.988  6991  6991 I bluedroid-qcom: get_profile_interface health
08-29 14:21:10.989  6991  6991 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 14:21:10.989  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:10.990  4305  7506 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 14:21:10.991  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 14:21:10.992  6991  6991 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 14:21:10.994  6991  6991 D PanService: Received start request. Starting profile...
08-29 14:21:10.994  6991  6991 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 14:21:10.994  6991  6991 I bluedroid-qcom: get_profile_interface pan
08-29 14:21:10.997  4305  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:10.997  4305  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 14:21:11.004  6991  6991 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 14:21:11.004  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:11.004  6991  6991 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 14:21:11.008  6991  6991 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:21:11.009  6991  6991 D BtGatt.GattService: Received start request. Starting profile...
08-29 14:21:11.009  6991  6991 D BtGatt.GattService: start()
08-29 14:21:11.009  6991  6991 I bluedroid-qcom: get_profile_interface gatt
08-29 14:21:11.010  6991  6991 D BtGatt.AdvertiseManager: advertise manager created
08-29 14:21:11.011  6951  7511 W FormManager: Network not available. Please check & try again.
08-29 14:21:11.015  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 14:21:11.015  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:11.015  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 14:21:11.019  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 14:21:11.019  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 14:21:11.021  7072  7513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:11.023  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:11.023  6951  7512 V FormManager: Network unavailable.
08-29 14:21:11.024  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
,08-29 14:21:11.024  6991  6991 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 14:21:11.025  6991  6991 V BluetoothMapService: BluetoothMapBinder()
08-29 14:21:11.025  6991  6991 D BluetoothMapService: Received start request. Starting profile...
08-29 14:21:11.025  6991  6991 D BluetoothMapService: start()
08-29 14:21:11.029  6991  6991 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 14:21:11.029  6991  6991 D BluetoothMapEmailAppObserver: createReceiver()
08-29 14:21:11.030  6991  6991 D BluetoothMapEmailAppObserver: initObservers()
08-29 14:21:11.030  6991  6991 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 14:21:11.031  6951  7512 V FormManager: Network unavailable.
,08-29 14:21:11.033  7166  7166 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:11
08-29 14:21:11.035  7166  7166 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 14:21:11.035  7166  7166 D Weather.Utils: 2 : All the weather widget is gone.
08-29 14:21:11.035  7166  7166 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 14:21:11.035  7166  7166 D WeatherAncestor: connectivity changed - connection : true
08-29 14:21:11.035  7166  7166 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@10fc8033
08-29 14:21:11.036  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:11.038  7166  7166 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 14:21:11.038  7166  7166 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 14:21:11.038  7166  7166 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 14:21:11.038  7166  7166 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 14:21:11.038  7166  7166 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:21:11
08-29 14:21:11.039  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 14:21:11.042  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 14:21:11.044  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 14:21:11.044  6991  6991 V PanService: [BTUI] SIM Extra State :ABSENT
,08-29 14:21:11.047  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 14:21:11.049  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.049  6991  6991 V BluetoothMapService: Handler(): got msg=1
08-29 14:21:11.050  6991  7448 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 14:21:11.050  6991  7448 I bluedroid-qcom: enable
08-29 14:21:11.050  6991  7448 I bt_hci_bdroid: init
08-29 14:21:11.051  6991  7517 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 14:21:11.052  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.052  6991  7448 I bt_vendor: bt-vendor : init
08-29 14:21:11.052  6991  7448 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 14:21:11.052  6991  7448 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 14:21:11.052  6991  7448 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 14:21:11.052  6991  7448 D bt_userial_mct: userial_init
08-29 14:21:11.052  6991  7517 I bt-btu  : btu_task pending for preload complete event
08-29 14:21:11.052  6991  7448 D bt_hci_bdroid: set_power 1
08-29 14:21:11.052  6991  7448 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 14:21:11.052  6991  7448 I bt_vendor: Starting hciattach daemon
08-29 14:21:11.052  6991  7448 I bt_vendor: try to set true
08-29 14:21:11.048  7520  7520 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:11.048  7520  7520 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:11.056  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:11.056  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:11.056  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 14:21:11.056  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.056  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-29 14:21:11.068  7521  7521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 14:21:11.164  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 14:21:11.197  7528  7528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 14:21:11.249  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 14:21:11.265  7531  7531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 14:21:11.299  7532  7532 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 14:21:11.319  7533  7533 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 14:21:11.359  7535  7535 I libmdmdetect: ESOC framework not supported
08-29 14:21:11.361  7535  7535 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 14:21:11.372  7535  7535 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 14:21:11.372  7535  7535 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 14:21:11.372  7535  7535 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 14:21:11.372  7535  7535 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 14:21:11.372  7535  7535 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 14:21:11.372  7535  7535 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 14:21:11.372  7535  7535 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 14:21:11.418  7535  7536 E QC-QMI  : qmi_client [7535] 14: failed to locate client data
08-29 14:21:11.419   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 14:21:11.419   474   474 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-29 14:21:11.476  7537  7537 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 14:21:11.503  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 14:21:11.555  6991  7448 I bt_vendor: bluetooth satus is on
,08-29 14:21:11.555  6991  7448 D bt_hci_bdroid: preload
08-29 14:21:11.556  6991  7519 D bt_userial_mct: userial_open(port:0)
08-29 14:21:11.556  6991  7519 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 14:21:11.559  6991  7519 I bt_vendor: Done intiailizing UART
08-29 14:21:11.560  6991  7519 I bt_vendor: Done intiailizing UART
08-29 14:21:11.560  6991  7519 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-29 14:21:11.561  6991  7519 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 14:21:11.561  6991  7517 I bt-btu  : btu_task received preload complete event
08-29 14:21:11.562  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 14:21:11.562  6991  7543 D bt_userial_mct: Entering userial_read_thread()
08-29 14:21:11.562  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 14:21:11.564  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 14:21:11.568  6991  7517 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 14:21:11.568  6991  7517 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 14:21:11.568  6991  7517 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 14:21:11.568  6991  7517 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 14:21:11.568  6991  7517 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 14:21:11.568  6991  7517 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 14:21:11.568  6991  7517 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 14:21:11.569  6991  7517 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 14:21:11.628  6991  7517 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 14:21:11.628  6991  7517 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0165061 
08-29 14:21:11.628  6991  7517 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0165061 
,08-29 14:21:11.650  6991  7452 E bt-btif : Calling BTA_HhEnable
08-29 14:21:11.651  6991  7452 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 14:21:11.651  6991  7452 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 14:21:11.651  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 14:21:11.651  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 14:21:11.651  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 14:21:11.652  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-29 14:21:11.652  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 14:21:11.654  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 14:21:11.655  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 14:21:11.655  6991  7452 D BluetoothAdapterProperties: Name is: G3
08-29 14:21:11.658  6991  7452 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:11.658  6991  7452 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:21:11.658  6991  7452 D bt_hci_bdroid: postload
08-29 14:21:11.659  6991  7519 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:11.659  6991  7519 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:11.660  6991  7519 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:11.661  6991  7517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 14:21:11.661  6991  7519 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:11.661  6991  7519 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:11.661  6991  7452 D bte_conf: Device ID record 1 : primary
08-29 14:21:11.661  6991  7452 D bte_conf:   vendorId            = 00c4
08-29 14:21:11.661  6991  7452 D bte_conf:   vendorIdSource      = 0001
08-29 14:21:11.661  6991  7452 D bte_conf:   product             = 13a1
08-29 14:21:11.661  6991  7452 D bte_conf:   version             = 1000
08-29 14:21:11.661  6991  7452 D bte_conf:   clientExecutableURL = 
08-29 14:21:11.661  6991  7452 D bte_conf:   serviceDescription  = 
08-29 14:21:11.661  6991  7452 D bte_conf:   documentationURL    = 
08-29 14:21:11.662  6991  7452 D bte_conf: bte_load_did_conf no section named DID2.
08-29 14:21:11.658  7546  7546 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 14:21:11.668  6991  7448 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 14:21:11.669  6991  7448 D BluetoothAdapterProperties: ScanMode =  20
08-29 14:21:11.669  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:11.669  6991  7448 D BluetoothAdapterProperties: State =  11
08-29 14:21:11.669  6991  7448 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 14:21:11.670  6991  7448 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 14:21:11.670  6991  7448 D BluetoothAdapterProperties: Setting state to 12
08-29 14:21:11.670  6991  7448 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 14:21:11.671  6991  7452 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 14:21:11.672  6991  7452 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 14:21:11.673  6991  7517 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:11.673  6991  7517 W bt-smp  : Plain text(LSB ~ MSB) = d3 99 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:11.668  7546  7546 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:11.673  6991  7517 W bt-smp  : Encrypted text(LSB ~ MSB) = 00 ff 32 b1 2c 23 53 84 4b d7 e5 8a 67 0e 90 61 
08-29 14:21:11.673  6991  7517 W bt-btm  : Stopping oneshot timer
08-29 14:21:11.673  6991  7519 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:11.675  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:11.675  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 14:21:11.676  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 14:21:11.678  6991  7448 I BluetoothAdapterState: Entering On State
08-29 14:21:11.680  6991  7543 E bt_mct  : hci lib postload completed
,08-29 14:21:11.686  6991  7448 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 14:21:11.686  6991  7448 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 14:21:11.686  6991  7448 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 14:21:11.690  6991  7448 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 14:21:11.691  6991  7452 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:21:11.691  6991  7452 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:11.693  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:11.697  6843  6863 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:21:11.699  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:11.701  6843  6981 D BluetoothPan: onBluetoothStateChange on: true
08-29 14:21:11.701  6843  6981 D BluetoothPan: onBluetoothStateChange call bindService
08-29 14:21:11.702  7194  7216 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-29 14:21:11.703  6843  6843 D BluetoothInputDevice: Proxy object connected
08-29 14:21:11.703  6843  6843 D HidProfile: Bluetooth service connected
08-29 14:21:11.703  6991  7517 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:11.703  6991  7517 W bt-smp  : Plain text(LSB ~ MSB) = cb f1 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:11.703  6991  7517 W bt-smp  : Encrypted text(LSB ~ MSB) = f2 01 cf cd 7d 71 bf 63 a0 7c 2f f3 db 55 35 c5 
08-29 14:21:11.703  6991  7517 W bt-btm  : Stopping oneshot timer
08-29 14:21:11.705  1042  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:21:11.707  1839  2420 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:11.710  1042  1042 D BluetoothA2dp: Proxy object connected
08-29 14:21:11.712  1839  1839 D BluetoothHeadset: Proxy object connected
08-29 14:21:11.712  6843  6981 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 14:21:11.714  6843  6843 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:21:11.714  6843  6843 D PanProfile: Bluetooth service connected
08-29 14:21:11.715  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:11.718  1839  1839 D BluetoothHeadset: Proxy object connected
08-29 14:21:11.718  1839  2420 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:21:11.720  6991  7517 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:11.720  6991  7517 W bt-smp  : Plain text(LSB ~ MSB) = 13 f7 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:11.720  6991  7517 W bt-smp  : Encrypted text(LSB ~ MSB) = ec df 80 b7 cc 9b fe 1e 09 c9 b4 9d 92 7f d3 75 
08-29 14:21:11.720  6991  7517 W bt-btm  : Stopping oneshot timer
08-29 14:21:11.724  6843  6864 D BluetoothMap: onBluetoothStateChange: up=true
08-29 14:21:11.724  1839  1839 D BluetoothHeadset: Proxy object connected
08-29 14:21:11.727  1042  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:11.728  1042  1042 D BluetoothHeadset: Proxy object connected
08-29 14:21:11.728  6991  7448 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 14:21:11.729  6843  6843 D BluetoothMap: Proxy object connected
08-29 14:21:11.729  6843  6843 D MapProfile: Bluetooth service connected
08-29 14:21:11.729  6843  6843 D BluetoothMap: getConnectedDevices()
08-29 14:21:11.731  6991  7517 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:11.731  6991  7517 W bt-smp  : Plain text(LSB ~ MSB) = 9d ba 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:11.731  6991  7517 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b 5e bb 7b 4c 3b bb 60 c4 66 f7 85 0a b6 db 08 
08-29 14:21:11.731  6991  7517 W bt-btm  : Stopping oneshot timer
08-29 14:21:11.731  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 14:21:11.732  6991  7553 V BluetoothMapService: getConnectedDevices()
,08-29 14:21:11.733  1042  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 14:21:11.733  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 14:21:11.734  1042  1118 D BluetoothManagerService: Message: 40
08-29 14:21:11.734  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 14:21:11.738  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.738  1929  2111 D LGBluetoothAPIService: Message: 1
08-29 14:21:11.738  1929  2111 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 14:21:11.740  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 14:21:11.744  6640  6640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 14:21:11.748  7554  7554 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-29 14:21:11.750  6991  7517 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:11.750  6991  7517 W bt-smp  : Plain text(LSB ~ MSB) = 5f 76 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:11.750  6991  7517 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 aa c8 32 4a 75 93 6a 3d 8b dc 08 83 12 5c f2 
08-29 14:21:11.750  6991  7517 W bt-btm  : Stopping oneshot timer
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:11.751  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:11.751  6991  6991 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.751  6991  6991 D BluetoothMapService: STATE_ON
08-29 14:21:11.753  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:11.755  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:11.757  6843  6843 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 14:21:11.757  1929  2111 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 14:21:11.760  1042  1118 D BluetoothManagerService: Message: 30
08-29 14:21:11.763  6843  6843 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 14:21:11.770  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:11.770  6991  6991 V BluetoothPbapService: Pbap Service onCreate
08-29 14:21:11.770  6991  6991 V BluetoothPbapService: Starting PBAP service
08-29 14:21:11.770  1042  1118 D BluetoothManagerService: Message: 30
08-29 14:21:11.771  6991  6991 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 14:21:11.772  6991  6991 V BluetoothMapService: Handler(): got msg=1
08-29 14:21:11.772  6991  6991 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 14:21:11.773  6991  6991 V BluetoothPbapService: Pbap Service onBind
08-29 14:21:11.774  6991  7560 D BluetoothMapMasInstance: MAS initSocket()
08-29 14:21:11.774  6991  6991 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.774  6991  6991 V BluetoothPbapService: state: 12
08-29 14:21:11.775  6843  6843 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 14:21:11.776  6991  6991 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 14:21:11.776  6991  6991 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 14:21:11.777  6843  6843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 14:21:11.777  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-29 14:21:11.777  1929  2111 D LGBluetoothAPIService: Message: 100
08-29 14:21:11.777  1929  2111 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 14:21:11.777  6991  6991 V BluetoothPbapService: Handler(): got msg=1
08-29 14:21:11.778  6991  6991 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 14:21:11.781  6843  6843 D BluetoothA2dp: Proxy object connected
08-29 14:21:11.781  6991  7560 D BluetoothMapMasInstance:   masId = 00
08-29 14:21:11.781  6991  7560 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 14:21:11.781  6991  7560 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 14:21:11.781  6991  7560 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 14:21:11.782  6843  6843 D A2dpProfile: Bluetooth service connected
08-29 14:21:11.781  6991  7561 V BluetoothPbapService: Pbap Service initSocket
08-29 14:21:11.785  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 14:21:11.785  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.785  6991  6991 V BluetoothPbapReceiver: ***********state = 12
08-29 14:21:11.786  1042  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:11.786  1042  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:11.787  6843  6843 D BluetoothHeadset: Proxy object connected
08-29 14:21:11.788  6991  7561 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:11.789  6991  7560 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:11.789  6991  7561 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 14:21:11.789  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:11.791  6991  7560 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 14:21:11.792  6991  7452 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:21:11.792  6991  7561 V BluetoothPbapService: Succeed to create listening socket 
08-29 14:21:11.792  6991  7560 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 14:21:11.792  6991  7561 V BluetoothPbapService: Accepting socket connection...
08-29 14:21:11.792  6991  7560 D BluetoothMapMasInstance: Accepting socket connection...
08-29 14:21:11.792  6991  7452 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 14:21:11.793  2195  2195 D c       : Getting all permits...
08-29 14:21:11.793  2195  2195 D a       : Opening database...
08-29 14:21:11.794  6843  6843 D HeadsetProfile: Bluetooth service connected
08-29 14:21:11.795  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:11.797  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:11.800  6843  6843 D BluetoothPbap: Proxy object connected
08-29 14:21:11.800  6843  6843 D PbapServerProfile: Bluetooth service connected
08-29 14:21:11.802  2195  2195 D a       : Opening database auth.proximity.permit_store...
,08-29 14:21:11.803  2195  2195 D a       : Closing database...
08-29 14:21:11.813  6843  6843 D DockEventReceiver: finishStartingService: stopping service
08-29 14:21:11.818  6843  6843 D BluetoothPermissionRequest: onReceive
,08-29 14:21:11.820  6843  6843 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-29 14:21:11.821  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 14:21:11.825  6991  6991 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 14:21:11.827  6991  6991 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 14:21:11.833  6991  6991 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 14:21:11.867  6991  6991 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 14:21:11.867  6991  6991 V BtOppService: onCreate
08-29 14:21:11.872  6991  6991 V BluetoothOppNotification: send message
08-29 14:21:11.877  6991  6991 V BtOppService: Starting RfcommListener
08-29 14:21:11.886  6991  6991 D BluetoothOppPreference: Dumping Names:  
08-29 14:21:11.886  6991  6991 D BluetoothOppPreference: {}
08-29 14:21:11.886  6991  6991 D BluetoothOppPreference: Dumping Channels:  
08-29 14:21:11.886  6991  6991 D BluetoothOppPreference: {}
,08-29 14:21:11.891  6991  6991 V BtOppService: onStartCommand
08-29 14:21:11.894  6991  7568 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 14:21:11.898  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.899  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 14:21:11.903  6991  7568 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 14:21:11.906  6991  6991 V BluetoothOppNotification: new notify threadi!
,08-29 14:21:11.907  6991  6991 V BluetoothOppNotification: send delay message
08-29 14:21:11.908  6991  6991 V BtOppService: start RfcommListener
08-29 14:21:11.909  6991  7565 V BtOppService: Deleted complete outbound shares, number =  0
08-29 14:21:11.912  6991  7568 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38e3f7ac on behalf of 
,08-29 14:21:11.913  6991  7569 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 14:21:11.913  6991  7565 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 14:21:11.914  6991  7565 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 14:21:11.916  6991  7565 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@298f0c75 on behalf of 
08-29 14:21:11.917  6991  7568 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 14:21:11.917  6991  7568 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 14:21:11.918  6991  7568 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3910947b on behalf of 
08-29 14:21:11.918  6991  7569 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f32240a on behalf of 
08-29 14:21:11.920  6991  6991 V BtOppService: RfcommListener started
08-29 14:21:11.921  6991  7569 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 14:21:11.921  6991  7570 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 14:21:11.922  1042  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:11.923  6991  7570 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:11.923  6991  7569 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 14:21:11.924  6991  7568 V BluetoothOppNotification: update too frequent, put in queue
08-29 14:21:11.924  6991  7570 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 14:21:11.925  6991  7570 V BtOppRfcommListener: Started RFCOMM listener....
08-29 14:21:11.925  6991  7570 I BtOppRfcommListener: Accept thread started.
08-29 14:21:11.925  6991  7570 V BtOppRfcommListener: Accepting connection...
08-29 14:21:11.926  6991  7568 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-29 14:21:11.926  6991  7569 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b6ee298 on behalf of 
08-29 14:21:11.928  6991  7569 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 14:21:11.929  6991  7569 V BluetoothOppNotification: outbound notification was removed.
08-29 14:21:11.930  6991  7569 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-29 14:21:11.931  6991  7569 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20d0faf1 on behalf of 
08-29 14:21:11.932  6991  7569 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 14:21:11.934  6991  7569 V BluetoothOppNotification: inbound notification was removed.
08-29 14:21:11.934  6991  7569 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 14:21:11.936  6991  7569 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cd676d6 on behalf of 
08-29 14:21:11.938  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
,08-29 14:21:11.938  6991  6991 V BluetoothFtpService: Ftp Service onCreate
08-29 14:21:11.938  6991  6991 I BluetoothFtpService: Ftp Service onCreate
08-29 14:21:11.939  6991  6991 V BluetoothFtpService: Ftp Service onStartCommand
08-29 14:21:11.939  6991  6991 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.939  6991  6991 V BluetoothFtpService: Starting Listening on sockets
08-29 14:21:11.940  6991  6991 V BtOppService: ContentObserver received notification
08-29 14:21:11.941  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:11.941  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:11.941  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 14:21:11.941  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.941  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 14:21:11.942  6991  6991 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 14:21:11.945  6991  6991 V BtOppService: ContentObserver received notification
08-29 14:21:11.945  6991  6991 V BluetoothFtpService: Handler(): got msg=1
08-29 14:21:11.945  6991  7571 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 14:21:11.945  6991  7571 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-29 14:21:11.947  6991  6991 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 14:21:11.947  6991  6991 V BluetoothFtpService: Ftp Service initSocket
08-29 14:21:11.947  6991  7571 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1abb9044 on behalf of 
08-29 14:21:11.949  6991  7571 V BluetoothOppNotification: update too frequent, put in queue
08-29 14:21:11.951  1042  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:11.951  6991  7571 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 14:21:11.953  6991  6991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:11.954  6991  6991 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-29 14:21:11.955  6991  6991 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 14:21:11.957  6991  7573 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 14:21:11.971  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
,08-29 14:21:11.971  6991  6991 V BluetoothSapService: Sap Service onCreate
08-29 14:21:11.974  6991  6991 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:11.974  6991  6991 V BluetoothSapService: state: 12
08-29 14:21:11.974  6991  6991 V BluetoothSapService: Starting SAP server process
08-29 14:21:11.976  6991  6991 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 14:21:11.968  7574  7574 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:11.968  7574  7574 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:11.979  6991  7575 V BluetoothSapService: Sap Service initRfcommSocket
08-29 14:21:11.980  1042  1709 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:11.981  6991  7575 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:11.984  6991  7575 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 14:21:11.984  6991  7575 V BluetoothSapService: Succeed to create listening socket 
,08-29 14:21:11.984  6991  7575 V BluetoothSapService: Accepting socket connection...
,08-29 14:21:12.001  7574  7574 V BT_SAP  : Event pipe created
08-29 14:21:12.001  7574  7574 V BT_SAP  : create_server_socket qcom.sap.server
08-29 14:21:12.001  7574  7574 V BT_SAP  : created socket fd 6
,08-29 14:21:12.153   315  7219 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 14:21:12.157  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
,08-29 14:21:12.158  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s674ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:12.159  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s569ms what=532487 target=com.android.internal.util.StateMachine$SmHandler },
08-29 14:21:12.159  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s569ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:12.159  1042  7187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 14:21:12.484  1042  1874 I ActivityManager: Killing 7373:com.lge.bnr/1000 (adj 15): empty #17
,08-29 14:21:12.498   315  7342 D libc-netbsd: res_queryN name = mtalk.google.com., class = 1, type = 1
08-29 14:21:12.500  1042  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 14:21:12.528  1042  1891 W libprocessgroup: failed to open /acct/uid_1000/pid_7373/cgroup.procs: No such file or directory
,08-29 14:21:12.567  1042  1524 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:12.567  1042  1524 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:12.598  1042  1526 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 14:21:12.600  1042  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 14:21:12.909  6991  6991 V BluetoothOppNotification: new notify threadi!
,08-29 14:21:12.910  6991  6991 V BluetoothOppNotification: send delay message
,08-29 14:21:12.935  1042  1059 I ActivityManager: Killing 6761:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-29 14:21:12.947  6991  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 14:21:12.960  6912  6912 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 14:21:12.961  6912  6912 W System.err: android.os.DeadObjectException
08-29 14:21:12.961  6912  6912 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 14:21:12.961  6912  6912 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 14:21:12.961  6912  6912 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 14:21:12.961  6912  6912 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 14:21:12.961  6912  6912 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 14:21:12.961  6912  6912 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 14:21:12.961  6912  6912 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:21:12.961  6912  6912 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 14:21:12.961  6912  6912 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 14:21:12.961  6912  6912 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 14:21:12.961  6912  6912 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:12.962  6912  6912 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:12.962  6912  6912 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 14:21:12.962  6912  6912 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 14:21:12.962  6912  6912 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 14:21:12.962  6912  6912 W System.err: android.os.DeadObjectException
,08-29 14:21:12.967  6912  6912 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 14:21:12.967  6912  6912 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 14:21:12.967  6912  6912 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 14:21:12.967  6912  6912 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 14:21:12.967  6912  6912 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 14:21:12.968  6912  6912 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 14:21:12.968  6912  6912 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:21:12.968  6912  6912 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 14:21:12.968  6912  6912 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 14:21:12.968  6912  6912 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 14:21:12.968  6912  6912 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:12.968  6912  6912 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:12.968  6912  6912 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 14:21:12.968  6912  6912 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 14:21:12.968  6912  6912 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 14:21:12.968  6912  6912 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 14:21:12.969  6991  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3036cb0 on behalf of 
08-29 14:21:12.970  6991  7586 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 14:21:12.972  6991  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 14:21:12.974  6991  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13b31729 on behalf of 
08-29 14:21:12.975  6991  7586 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 14:21:12.980  6991  7586 V BluetoothOppNotification: outbound notification was removed.
08-29 14:21:12.980  6991  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 14:21:12.994  1042  1910 W libprocessgroup: failed to open /acct/uid_1000/pid_6761/cgroup.procs: No such file or directory
08-29 14:21:12.994  1042  1910 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 14:21:13.011  6912  6912 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 14:21:13.011  6912  6912 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-29 14:21:13.091  1042  1983 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7587 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 14:21:13.097  6912  6912 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 14:21:13.174  7587  7587 D UEI.SmartControl: Quickset Services start...
,08-29 14:21:13.176  7587  7587 I UEI.SmartControl: Manufacture = LGE
08-29 14:21:13.176  7587  7587 D UEI.SmartControl: Id = LGNevo
08-29 14:21:13.177  7587  7587 D UEI.SmartControl: File observer start...
,08-29 14:21:13.178  7587  7587 E UEI.SmartControl: IR Port is disabled: false
08-29 14:21:13.179  7587  7587 D UEI.SmartControl: Starting file observer...
08-29 14:21:13.180  7587  7587 D UEI.SmartControl: Extracting JNI libs...
08-29 14:21:13.180  7587  7587 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 14:21:13.205  1042  1974 I art     : Explicit concurrent mark sweep GC freed 92145(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.062ms total 223.197ms
08-29 14:21:13.205  6991  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7058aae on behalf of 
08-29 14:21:13.206  6991  7586 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 14:21:13.207  6991  7586 V BluetoothOppNotification: inbound notification was removed.
08-29 14:21:13.207  6991  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 14:21:13.210  6991  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e31404f on behalf of 
08-29 14:21:13.256  7587  7587 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 14:21:13.256  7587  7587 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 14:21:13.256  7587  7587 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 14:21:13.280  7587  7587 I UEI.SmartControl: --- Selecting new region: 6
,08-29 14:21:13.281  7587  7587 I UEI.SmartControl: Model = LG-D855
,08-29 14:21:13.283  7587  7587 D UEI.SmartControl: QS Service created
08-29 14:21:13.293  7587  7587 I UEI.SmartControl: Service initServices...
,08-29 14:21:13.296  7587  7587 D UEI.SmartControl: QS start get config
,08-29 14:21:13.341  7587  7587 D UEI.SmartControl: Loading JNI Libs...
,08-29 14:21:13.546  1042  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 14:21:13.546  1042  1947 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2e277242 mBinding = false
,08-29 14:21:13.571  1042  1118 D BluetoothManagerService: Message: 2
08-29 14:21:13.572  1042  1118 D BluetoothManagerService: Sending off request.
08-29 14:21:13.572  6991  7548 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 14:21:13.573  6991  7448 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 14:21:13.573  6991  7448 D BluetoothAdapterProperties: Setting state to 13
08-29 14:21:13.573  6991  7448 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 14:21:13.580  6991  7448 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 14:21:13.580  6991  7448 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 14:21:13.584  6991  7452 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:13.585  6991  7448 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 14:21:13.585  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:13.585  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 14:21:13.585  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 14:21:13.586  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:13.589  6991  6991 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:13.589  6991  6991 D BluetoothMapService: STATE_TURNING_OFF
08-29 14:21:13.589  6991  6991 V BluetoothMapService: Handler(): got msg=4
08-29 14:21:13.589  6991  6991 D BluetoothMapService: MAP Service closeService in
08-29 14:21:13.589  6991  6991 D BluetoothMapMasInstance: MAP Service shutdown
08-29 14:21:13.590  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 14:21:13.591  6991  7560 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 14:21:13.592  6991  7561 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:13.593  6991  6991 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 14:21:13.593  6991  6991 V BluetoothMapService: MAP Service closeService out
08-29 14:21:13.593  6991  6991 V BtOppService: Receiver DISABLED_ACTION 
08-29 14:21:13.593  6991  7448 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 14:21:13.593  6991  6991 I BtOppRfcommListener: stopping Accept Thread
08-29 14:21:13.593  6991  6991 V BtOppRfcommListener: close mBtServerSocket
08-29 14:21:13.593  6991  6991 V BtOppRfcommListener: waiting for thread to terminate
08-29 14:21:13.594  6991  7570 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:13.595  6991  7570 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 14:21:13.595  6991  6991 V BtOppRfcommListener: done waiting for thread to terminate
08-29 14:21:13.596  6991  7575 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:13.596  6991  7573 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:13.596  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 14:21:13.596  6991  7517 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregi,stration
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 14:21:13.598  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 14:21:13.598  6991  7517 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-29 14:21:13.607  6843  6843 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 14:21:13.609  6991  6991 V BtOppService: onDestroy
08-29 14:21:13.611  6991  6991 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 14:21:13.612  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:13.612  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:13.612  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:13.613  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 14:21:13.613  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-29 14:21:13.613  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:13.613  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:13.614  6843  6843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 14:21:13.616  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:13.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:13.616  6640  6640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:13.616  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:13.617  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:13.618  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:13.621  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 14:21:13.621  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:13.621  6991  6991 V BluetoothPbapReceiver: ***********state = 13
08-29 14:21:13.622  6991  6991 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 14:21:13.623  6991  6991 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:13.623  6991  6991 V BluetoothPbapService: state: 13
08-29 14:21:13.623  6991  6991 V BluetoothPbapService: Pbap Service closeService in
,08-29 14:21:13.627  6991  6991 V BluetoothPbapService: successfully stopped pbap service
08-29 14:21:13.627  6991  6991 V BluetoothPbapService: Pbap Service closeService out
08-29 14:21:13.629  6991  6991 V BluetoothPbapService: Pbap Service onDestroy
08-29 14:21:13.629  6991  6991 V BluetoothPbapService: Pbap Service closeService in
08-29 14:21:13.629  6991  6991 V BluetoothPbapService: Pbap Service closeService out
08-29 14:21:13.629  6843  6843 D DockEventReceiver: finishStartingService: stopping service
08-29 14:21:13.629  6991  6991 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 14:21:13.630  6843  6843 D BluetoothPbap: Proxy object disconnected
08-29 14:21:13.630  6843  6843 D PbapServerProfile: Bluetooth service disconnected
08-29 14:21:13.630  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:13.642  6843  6843 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 14:21:13.647  6843  6843 D BluetoothPermissionRequest: onReceive
08-29 14:21:13.647  6843  6843 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 14:21:13.651  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 14:21:13.653  6991  6991 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-29 14:21:13.653  6991  6991 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 14:21:13.653  6991  6991 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 14:21:13.655  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:13.655  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 14:21:13.658  6991  6991 V BluetoothFtpService: Ftp Service onStartCommand
08-29 14:21:13.658  6991  6991 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:13.658  6991  6991 V BluetoothFtpService: Ftp Service closeService
08-29 14:21:13.658  6991  6991 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 14:21:13.660  6991  6991 V BluetoothFtpService: successfully stopped ftp service
08-29 14:21:13.660  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:13.660  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:13.660  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 14:21:13.660  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:13.660  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 14:21:13.660  6991  6991 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 14:21:13.661  6991  6991 V BluetoothFtpService: Ftp Service onDestroy
08-29 14:21:13.661  6991  6991 V BluetoothFtpService: Ftp Service closeService
08-29 14:21:13.661  6991  6991 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:13.661  6991  6991 V BluetoothSapService: state: 13
08-29 14:21:13.662  6991  6991 V BluetoothSapService: Stopping SAP server process
08-29 14:21:13.662  6991  6991 V BluetoothSapService: Sap Service closeSapService in
08-29 14:21:13.662  6991  6991 V BluetoothSapService: Close listen Socket : 
08-29 14:21:13.663  6991  6991 V BluetoothSapService: Close rfcomm Socket : 
08-29 14:21:13.663  6991  6991 V BluetoothSapService: Close sapd  Socket : 
08-29 14:21:13.664  6991  6991 V BluetoothSapService: Sap Service closeSapService out
08-29 14:21:13.664  6991  6991 V BluetoothSapService: Sap Service onDestroy
08-29 14:21:13.664  6991  6991 V BluetoothSapService: Sap Service closeSapService in
08-29 14:21:13.664  6991  6991 V BluetoothSapService: Close listen Socket : 
08-29 14:21:13.664  6991  6991 V BluetoothSapService: Close rfcomm Socket : 
08-29 14:21:13.664  6991  6991 V BluetoothSapService: Close sapd  Socket : 
08-29 14:21:13.664  6991  6991 V BluetoothSapService: Sap Service closeSapService out
08-29 14:21:13.786  7587  7587 I UEI.SmartControl: Supports setup maps: true
,08-29 14:21:13.791  7587  7587 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 14:21:13.791  7587  7587 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 14:21:13.791  7587  7587 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 14:21:13.791  7587  7587 I UEI.SmartControl: ### init IR Blaster...
08-29 14:21:13.796  7587  7587 D serial_port: Configuring serial port
08-29 14:21:13.800  7587  7587 E UEI.SmartControl: UEIBLaster setting for 616
08-29 14:21:13.800  7587  7587 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 14:21:13.801  7587  7587 I UEI.SmartControl: configuring settings for MAXQ616
08-29 14:21:13.801  7587  7587 I UEI.SmartControl: Get version...
,08-29 14:21:13.820  7587  7639 D UEI.SmartControl: serial port data available: 21
,08-29 14:21:13.849  7587  7587 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 14:21:13.849  7587  7587 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 14:21:13.850  7587  7587 I UEI.SmartControl: QS saving settings...
08-29 14:21:13.852  7587  7587 D UEI.SmartControl: IR Blaster version: 25672567
08-29 14:21:13.869  7587  7639 D UEI.SmartControl: serial port data available: 4
,08-29 14:21:13.910  7587  7642 I UEI.SmartControl: Device manager: loading config....
,08-29 14:21:13.911  7587  7587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 14:21:13.912  7587  7642 D UEI.SmartControl: ----------- loading internal config...
08-29 14:21:13.922  7587  7587 E UEI.SmartControl: Services init done
,08-29 14:21:13.922  7587  7587 D UEI.SmartControl: QS Service init finished
08-29 14:21:13.927  7587  7587 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 14:21:13.927  7587  7587 D UEI.SmartControl: QS Service version code: 201091
08-29 14:21:13.932  7587  7587 D UEI.SmartControl: Service requested: Control
08-29 14:21:13.934  7587  7642 E UEI.SmartControl: Loading SETTINGS...
08-29 14:21:13.938  7587  7587 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-29 14:21:13.940  7587  7642 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 14:21:13.944  6912  6912 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 14:21:13.945  7587  7618 I UEI.SmartControl: ------ IControl API: 11
08-29 14:21:13.946  7587  7641 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 14:21:13.947  1042  2020 I ActivityManager: Killing 6912:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 14:21:13.947  7587  7618 I UEI.SmartControl: Registering callback...
08-29 14:21:13.948  7587  7641 D UEI.SmartControl: -----service ready thread exits
08-29 14:21:14.055  1042  1059 W libprocessgroup: failed to open /acct/uid_10112/pid_6912/cgroup.procs: No such file or directory
,08-29 14:21:14.062  7587  7587 D UEI.SmartControl: Internal service binding...
,08-29 14:21:14.581  6991  7452 D bt_hci_bdroid: cleanup
,08-29 14:21:14.590  6991  7519 I bt_lpm  : LPM is already off!!!
08-29 14:21:14.591  6991  7543 I bt_userial_mct: exiting userial_read_thread
08-29 14:21:14.591  6991  7543 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 14:21:14.593  6991  7517 W bt-btif : ag scb idx 1 not allocated
08-29 14:21:14.593  6991  7517 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-29 14:21:14.594  6991  7517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:21:14.594  6991  7517 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 14:21:14.595  6991  7452 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 14:21:14.596  6991  7519 I bt_vendor: hw_epilog_process
08-29 14:21:14.596  6991  7452 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-29 14:21:14.596  6991  7452 D bt_userial_mct: userial_close
08-29 14:21:14.596  6991  7452 E bt_userial_mct: pthread_join() FAILED result:3
08-29 14:21:14.597  6991  7452 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 14:21:14.603  6991  7452 D bt_hci_bdroid: set_power 0
08-29 14:21:14.603  6991  7452 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 14:21:14.603  6991  7452 I bt_vendor: bluetooth satus is on
08-29 14:21:14.603  6991  7452 I bt_vendor: bt-vendor : resetting BT status
,08-29 14:21:14.603  6991  7452 I bt_vendor: Starting hciattach daemon
08-29 14:21:14.603  6991  7452 I bt_vendor: try to set false
,08-29 14:21:14.613  6991  7452 I bt_vendor: Starting hciattach daemon
08-29 14:21:14.613  6991  7452 I bt_vendor: try to set false
08-29 14:21:14.615  6991  7452 I bt_vendor: cleanup
08-29 14:21:14.615  6991  7517 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 14:21:14.616  6991  7452 I GKI_LINUX: GKI_exit_task 0 done
08-29 14:21:14.616  6991  7452 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 14:21:14.617  6991  7448 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 14:21:14.621  6991  6991 D HeadsetService: Received stop request...Stopping profile...
,08-29 14:21:14.626  6991  6991 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 14:21:14.626  6991  6991 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 14:21:14.626  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:14.627  6991  7470 D HeadsetStateMachine: Exit Disconnected: -1
08-29 14:21:14.629  1042  1042 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:14.629  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 14:21:14.630  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:14.630  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:14.635  6991  7448 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 14:21:14.639  6991  6991 D A2dpService: Received stop request...Stopping profile...
08-29 14:21:14.640  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:14.640  6991  7502 D A2dpStateMachine: Exit Disconnected: -1
08-29 14:21:14.642  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 14:21:14.644  6991  6991 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 14:21:14.644  6991  6991 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 14:21:14.644  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:14.646  1042  1042 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:14.646  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 14:21:14.646  6991  6991 D HidService: Received stop request...Stopping profile...
08-29 14:21:14.647  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
,08-29 14:21:14.652  6991  6991 D HealthService: Received stop request...Stopping profile...
08-29 14:21:14.653  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:14.656  6991  6991 D HeadsetStateMachine: Unbinding service...
08-29 14:21:14.657  6991  6991 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 14:21:14.657  6991  6991 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 14:21:14.657  6991  6991 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 14:21:14.657  6991  6991 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 14:21:14.657  6991  6991 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 14:21:14.657  6991  6991 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 14:21:14.657  6991  6991 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 14:21:14.659  6991  6991 D PanService: Received stop request...Stopping profile...
,08-29 14:21:14.661  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:14.663  6991  6991 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:21:14.664  6991  6991 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 14:21:14.664  6991  6991 D BtGatt.GattService: stop()
08-29 14:21:14.664  6991  6991 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 14:21:14.665  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:14.668  6991  6991 D BluetoothMapService: Received stop request...Stopping profile...
08-29 14:21:14.668  6991  6991 D BluetoothMapService: stop()
08-29 14:21:14.669  6991  6991 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 14:21:14.669  6991  6991 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 14:21:14.670  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10fc8033
08-29 14:21:14.671  6991  6991 I BluetoothA2dpServiceJni: cleanupNative
,08-29 14:21:14.674  6991  7503 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 14:21:14.674  6991  6991 I GKI_LINUX: GKI_exit_task 2 done
08-29 14:21:14.674  6991  6991 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 14:21:14.675  6991  6991 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:21:14.675  6991  6991 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 14:21:14.675  6991  6991 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 14:21:14.675  6991  6991 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:21:14.675  6991  6991 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:21:14.676  6991  6991 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:21:14.676  6991  6991 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 14:21:14.681  6991  6991 V BluetoothMapService: Handler(): got msg=4
08-29 14:21:14.681  6991  6991 D BluetoothMapService: MAP Service closeService in
08-29 14:21:14.681  6991  6991 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 14:21:14.681  6991  6991 V BluetoothMapService: MAP Service closeService out
08-29 14:21:14.684  6991  7448 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 14:21:14.684  6991  7448 D BluetoothAdapterProperties: Setting state to 10
08-29 14:21:14.684  6991  7448 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-29 14:21:14.687  6991  6991 D BluetoothMapService: cleanup()
08-29 14:21:14.687  6991  6991 D BluetoothMapService: MAP Service closeService in
08-29 14:21:14.687  6991  6991 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 14:21:14.687  6991  6991 V BluetoothMapService: MAP Service closeService out
08-29 14:21:14.688  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:14.688  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 14:21:14.688  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 14:21:14.689  6991  7448 I BluetoothAdapterState: Entering OffState
08-29 14:21:14.689  6843  6981 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 14:21:14.689  6843  6981 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:21:14.690  1042  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:14.690  1839  2656 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:14.691  6843  6981 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:14.691  6843  6981 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:21:14.692  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:14.693  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:14.693  6843  6981 D BluetoothMap: onBluetoothStateChange: up=false
08-29 14:21:14.694  6843  6981 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:14.696  1042  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 14:21:14.698  1042  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 14:21:14.699  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 14:21:14.701  1042  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 14:21:14.701  1042  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 14:21:14.701  1042  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2e277242 mBinding = false
08-29 14:21:14.701  1042  1118 D BluetoothManagerService: Sending unbind request.
08-29 14:21:14.706  6991  7452 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 14:21:14.707  6991  6991 I GKI_LINUX: GKI_exit_task 1 done
08-29 14:21:14.707  6991  6991 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 14:21:14.708  6991  6991 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 14:21:14.708  6991  6991 I art     : --- WEIRD: removing null entry 248
08-29 14:21:14.708  6991  6991 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 14:21:14.708  6991  6991 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-29 14:21:14.711  6991  6991 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-29 14:21:14.712  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 14:21:14.714  6991  6991 I art     : System.exit called, status: 0
08-29 14:21:14.714  6991  6991 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 14:21:14.736  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-29 14:21:14.742  1929  2111 D LGBluetoothAPIService: Message: 101
,08-29 14:21:14.744  1929  2111 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 14:21:14.744  1929  2111 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-29 14:21:14.744  1929  2111 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 14:21:14.745  6843  6843 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 14:21:14.732   320  1366 V AudioFlinger: 6991 died, releasing its sessions
08-29 14:21:14.745   320  1366 V AudioFlinger:  pid 1839 @ 0
08-29 14:21:14.745   320  1366 V AudioFlinger:  pid 3433 @ 1
08-29 14:21:14.745   320  1366 V AudioFlinger:  pid 3433 @ 2
08-29 14:21:14.833  1042  1974 I ActivityManager: Process com.android.bluetooth (pid 6991) has died
08-29 14:21:14.833  1042  1974 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-29 14:21:14.834  1042  1974 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-29 14:21:14.842  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:14.843  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 14:21:14.843  1929  2111 D LGBluetoothAPIService: Message: 2,
08-29 14:21:14.843  1929  2111 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-29 14:21:14.846  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:14.847  1590  1590 D BluetoothAdapter: 327712165: getState() :  mService = null. Returning STATE_OFF
08-29 14:21:14.847  1590  1590 D BluetoothAdapter: 327712165: getState() :  mService = null. Returning STATE_OFF
08-29 14:21:14.846  6843  6843 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 14:21:14.848  6843  6843 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 14:21:14.850  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:14.853  6843  6843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 14:21:14.899  1042  1562 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7674 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 14:21:14.901  6843  6843 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:14.994  7674  7674 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 14:21:14.995  7674  7674 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:14.995  7674  7674 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 14:21:14.996  7674  7674 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 14:21:15.019  7674  7674 D BluetoothAdapterApp: Loading JNI Library
,08-29 14:21:15.066  7674  7674 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e3a34bb Instance Count = 1
,08-29 14:21:15.075  7674  7674 D BluetoothAdapterApp: onCreate
08-29 14:21:15.100  7674  7674 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 14:21:15.100  7674  7674 D ProfileConfigQcom: Adding HeadsetService
08-29 14:21:15.100  7674  7674 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 14:21:15.100  7674  7674 D ProfileConfigQcom: Adding A2dpService
08-29 14:21:15.101  7674  7674 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 14:21:15.101  7674  7674 D ProfileConfigQcom: Adding HidService
08-29 14:21:15.101  7674  7674 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 14:21:15.101  7674  7674 D ProfileConfigQcom: Adding HealthService
08-29 14:21:15.102  7674  7674 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 14:21:15.103  7674  7674 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 14:21:15.103  7674  7674 D ProfileConfigQcom: Adding PanService
08-29 14:21:15.103  7674  7674 D ProfileConfigQcom: [BTUI] GattService is supported
,08-29 14:21:15.104  7674  7674 D ProfileConfigQcom: Adding GattService
08-29 14:21:15.104  7674  7674 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 14:21:15.104  7674  7674 D ProfileConfigQcom: Adding BluetoothMapService
08-29 14:21:15.105  7674  7674 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 14:21:15.106  7674  7674 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 14:21:15.107  7674  7674 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:15.107  7674  7674 V BluetoothPbapReceiver: ***********state = 10
08-29 14:21:15.109  7674  7674 V LGMDMManagerInternal: Create singleton instance
08-29 14:21:15.213  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:15.223  7674  7674 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 14:21:15.223  7674  7674 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 14:21:15.223  6843  6843 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 14:21:15.231  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 14:21:15.231  1929  2111 D LGBluetoothAPIService: Message: 100
08-29 14:21:15.231  1929  2111 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-29 14:21:15.241  6843  6843 D BluetoothPermissionRequest: onReceive
08-29 14:21:15.243  6843  6843 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 14:21:15.243  6843  6843 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 14:21:15.245  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 14:21:15.251  7674  7674 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 14:21:15.255  7674  7674 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:15.258  7674  7674 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:15.258  7674  7674 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:15.259  7674  7674 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 14:21:15.260  7674  7674 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:15.260  7674  7674 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-29 14:21:15.265  6931  6931 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 14:21:16.572  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:16.572  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:16.766  1590  1590 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 14:21:16.783  1042  1455 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 14:21:16.793  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-29 14:21:16.828  1042  1042 D administrator: Handling package changes for user 0
,08-29 14:21:16.922  1042  1114 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7714 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 14:21:16.933  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-29 14:21:16.933  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-29 14:21:16.941  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 14:21:16.991  7714  7714 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 14:21:17.008  1042  1042 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-29 14:21:17.008  1042  1042 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-29 14:21:17.081  7714  7714 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:17.081  7714  7714 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:17.097  1042  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 14:21:17.105  1042  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 14:21:17.114  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-29 14:21:17.118  2457  2457 V GmsNetworkLocationProvi: DISABLE
08-29 14:21:17.152  1042  1113 D LocationProviderProxy: applying state to connected service
,08-29 14:21:17.162  2457  2457 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-29 14:21:17.190  7714  7745 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-29 14:21:17.191  7714  7745 I Babel   : MmsConfig.loadMmsSettings
08-29 14:21:17.198  7714  7745 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 14:21:17.198  7714  7745 I Babel   : MmsConfig.loadFromDatabase
,08-29 14:21:17.229  7714  7745 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-29 14:21:17.230  7714  7745 I Babel   : MmsConfig.loadFromResources
08-29 14:21:17.232  7714  7745 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-29 14:21:17.234  7714  7745 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-29 14:21:17.261  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:17.311  7714  7743 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 14:21:17.312  7714  7743 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 14:21:17.315  7714  7743 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 14:21:17.333  7714  7743 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-29 14:21:17.336  7714  7743 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 14:21:17.337  1804  7749 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-29 14:21:17.337  1804  7749 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-29 14:21:17.338  7714  7743 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 14:21:17.355  7048  7048 I AppUp4:CustModeStarterReceiver: onReceive
08-29 14:21:17.357  1804  4765 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-29 14:21:17.359  7048  7048 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@125bf36d
08-29 14:21:17.359  7048  7048 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 14:21:17.359  7048  7048 D AppUp4:CustFacade: isPhone : true
08-29 14:21:17.359  7048  7048 D AppUp4:CustModeStarterReceiver: begin check event
08-29 14:21:17.359  7048  7048 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-29 14:21:17.368  7714  7743 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 14:21:17.372  7714  7743 W VideoCapabilities: Unsupported mime video/divx
08-29 14:21:17.374  7714  7743 W VideoCapabilities: Unsupported mime video/divx311
,08-29 14:21:17.377  7714  7743 W VideoCapabilities: Unsupported mime video/divx4
08-29 14:21:17.383  7714  7743 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 14:21:17.403  1042  1938 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7752 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 14:21:17.407  1042  1947 I ActivityManager: Killing 6865:com.lge.sync/1000 (adj 15): empty #17
,08-29 14:21:17.421  1042  1531 D WifiService: Client connection lost with reason: 4
,08-29 14:21:17.425  7714  7743 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-29 14:21:17.429  7714  7743 W AudioCapabilities: Unsupported mime audio/eac3
08-29 14:21:17.429  7714  7743 W AudioCapabilities: Unsupported mime audio/ac3
08-29 14:21:17.430  7714  7743 W AudioCapabilities: Unsupported mime audio/g726
08-29 14:21:17.431  7714  7743 W AudioCapabilities: Unsupported mime audio/wma-voice
08-29 14:21:17.432  7714  7743 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 14:21:17.434  7714  7743 W AudioCapabilities: Unsupported mime audio/adpcm
08-29 14:21:17.437  7714  7743 W VideoCapabilities: Unsupported mime video/theora
08-29 14:21:17.440  7714  7743 W VideoCapabilities: Unsupported mime video/mjpg
08-29 14:21:17.494  1042  1058 W libprocessgroup: failed to open /acct/uid_1000/pid_6865/cgroup.procs: No such file or directory
,08-29 14:21:17.525  7752  7752 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:17.525  7752  7752 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:17.525  7752  7752 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 14:21:17.526  7752  7752 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 14:21:17.527  7752  7752 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-29 14:21:17.588  7752  7752 I SystemConfig: BUILD Country: EU
08-29 14:21:17.588  7752  7752 I SystemConfig: BUILD Operator: OPEN
,08-29 14:21:17.627  1042  2020 I ActivityManager: Killing 7072:com.lge.email/u0a23 (adj 15): empty #17
,08-29 14:21:17.737  1042  1892 W libprocessgroup: failed to open /acct/uid_10023/pid_7072/cgroup.procs: No such file or directory
,08-29 14:21:17.753  7752  7770 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 14:21:17.753  7752  7770 I SystemConfig: existFile = false
08-29 14:21:17.753  7752  7770 I SystemConfig: canReadFile = false
08-29 14:21:17.753  7752  7770 I SystemConfig: systemFeature RCS result false
08-29 14:21:17.754  7752  7770 D SystemConfig: refreshRcsSupport() :false
,08-29 14:21:17.797  1042  1798 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7775 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-29 14:21:17.859  7775  7775 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:17.860  7775  7775 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 14:21:17.860  7775  7775 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-29 14:21:17.860  7775  7775 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 14:21:17.964  7775  7775 I AppConfig: Total System Memory = 2995761152
,08-29 14:21:17.980  7775  7775 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-29 14:21:18.043  1042  1874 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7794 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 14:21:18.044  1042  1874 I ActivityManager: Killing 6951:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-29 14:21:18.092  1042  1910 W libprocessgroup: failed to open /acct/uid_10026/pid_6951/cgroup.procs: No such file or directory
,08-29 14:21:18.268  7794  7794 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-29 14:21:18.359  7794  7794 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:18.359  7794  7794 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:18.414  7794  7794 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 14:21:18.435  7794  7794 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 14:21:18.436  7794  7794 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 14:21:18.453  7794  7794 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:21:18.453  7794  7794 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-29 14:21:18.490  1042  1892 I ActivityManager: Killing 6459:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-29 14:21:18.527  1042  1562 W libprocessgroup: failed to open /acct/uid_1000/pid_6459/cgroup.procs: No such file or directory
,08-29 14:21:18.530  2827  5623 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-29 14:21:18.532  2827  5623 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a9e2f81 on behalf of 7794
08-29 14:21:18.539  4582  7834 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-29 14:21:18.591  1042  1892 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7836 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 14:21:18.625   343   343 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 28.916ms
,08-29 14:21:18.647  7794  7794 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-29 14:21:18.647   343   343 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 424us total 20.153ms
,08-29 14:21:18.671   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 438us total 22.188ms
,08-29 14:21:18.686  7794  7794 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-29 14:21:18.712  7836  7836 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 14:21:18.741  7836  7836 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-29 14:21:18.741  7836  7836 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-29 14:21:18.741  7836  7836 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-29 14:21:18.741  7836  7836 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-29 14:21:18.741  7836  7836 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-29 14:21:18.741  7836  7836 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-29 14:21:18.759  1042  1798 I ActivityManager: Killing 7111:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-29 14:21:18.788  1042  1938 W libprocessgroup: failed to open /acct/uid_10046/pid_7111/cgroup.procs: No such file or directory
,08-29 14:21:18.909  7587  7643 D UEI.SmartControl: Internal timer expired: 1
,08-29 14:21:18.909  7587  7643 D UEI.SmartControl: unbind internal service
,08-29 14:21:18.915  7587  7587 D UEI.SmartControl: Service.onUnbind: IControl
08-29 14:21:18.916  7587  7587 D UEI.SmartControl: Service.onDestroy
08-29 14:21:18.917  7587  7587 D UEI.SmartControl: Lock is in USE false
08-29 14:21:18.917  7587  7587 D UEI.SmartControl: unbind internal service
08-29 14:21:18.918  7587  7587 D serial_port: close(fd = 25)
08-29 14:21:18.921  7587  7587 I UEI.SmartControl: Serial port is closed.
08-29 14:21:18.924  7587  7587 I UEI.SmartControl: Serial port is closed.
08-29 14:21:18.924  7587  7587 D UEI.SmartControl: Blaster closed
08-29 14:21:18.924  7587  7587 D UEI.SmartControl: Shut down QS...
08-29 14:21:18.925  7587  7587 D UEI.SmartControl: Stopping QS lib
08-29 14:21:18.925  7587  7587 D UEI.SmartControl: QS lib stop result = true
08-29 14:21:18.925  7587  7587 D UEI.SmartControl: Stopped QS lib
08-29 14:21:18.926  7587  7587 D UEI.SmartControl: Stopped file observer...
08-29 14:21:18.926  7587  7587 D UEI.SmartControl: QS shutdown complete
,08-29 14:21:18.986  1042  1709 V SIM_STK : Menu title from STK is T-Mobile
,08-29 14:21:19.009  4582  7834 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 470 ms] updated apps [took 470 ms] 
,08-29 14:21:19.590  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:19.591  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74f9b77 added. We now have 6 listener(s)
,08-29 14:21:19.591  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:19.604  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:19.605  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@134da3e4 added. We now have 7 listener(s)
08-29 14:21:19.605  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:19.605  6640  6748 I System.out: IsBluetoothEnabled
08-29 14:21:19.606  1042  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:19.606  1042  1938 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 14:21:19.608  1042  1118 D BluetoothManagerService: Message: 2
08-29 14:21:19.611  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:19.614  1042  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:19.614  1042  1891 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 14:21:19.633  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 14:21:19.633  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 14:21:19.633  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-29 14:21:19.634  1042  1118 D BluetoothManagerService: Message: 1
08-29 14:21:19.634  1042  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 14:21:19.658  1042  1118 D BluetoothManagerService: Message: 20
08-29 14:21:19.658  1042  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d3e110:true
,08-29 14:21:19.662  7674  7674 D BluetoothAdapterState: make
08-29 14:21:19.667  7674  7674 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 14:21:19.667  7674  7674 I bluedroid-qcom: init
08-29 14:21:19.668  7674  7880 I BluetoothAdapterState: Entering OffState
08-29 14:21:19.669  7674  7674 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 14:21:19.669  7674  7674 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 14:21:19.669  7674  7674 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 14:21:19.669  7674  7674 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 14:21:19.669  7674  7674 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 14:21:19.671  7674  7674 I bluedroid-qcom: get_profile_interface socket
08-29 14:21:19.671  7674  7674 I bluedroid-qcom: get_profile_interface map_client
,08-29 14:21:19.675  7674  7884 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 14:21:19.668  7883  7883 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:19.668  7883  7883 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:19.685  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-29 14:21:19.687  1042  1118 D BluetoothManagerService: Message: 40
08-29 14:21:19.687  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 14:21:19.688  7674  7689 I bluedroid-qcom: config_hci_snoop_log
08-29 14:21:19.690  1042  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 14:21:19.690  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 14:21:19.695  7674  7884 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 14:21:19.698  7883  7883 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 14:21:19.698  7883  7883 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 14:21:19.698  7883  7883 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-29 14:21:19.701  7883  7883 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 14:21:19.704  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 14:21:19.704  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 14:21:19.705  7674  7884 D BluetoothAdapterProperties: Name is: G3
08-29 14:21:19.707  7883  7883 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 14:21:19.707  7883  7883 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 14:21:19.713  7674  7880 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 14:21:19.713  7674  7880 D BluetoothAdapterProperties: Setting state to 11
08-29 14:21:19.713  7674  7880 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 14:21:19.716  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:19.716  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 14:21:19.717  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 14:21:19.721  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:19.721  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 14:21:19.725  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:19.727  6843  6843 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-29 14:21:19.736  7674  7674 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 14:21:19.736  7674  7674 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:19.736  7674  7674 V BluetoothPbapReceiver: ***********state = 11
08-29 14:21:19.739  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:19.754  7674  7880 I LGBluetoothServiceJni: classInitNative: succeeds
,08-29 14:21:19.763  7674  7880 D BluetoothBondStateMachine: make
08-29 14:21:19.766  7674  7880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:19.766  7674  7880 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 14:21:19.766  7674  7880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:19.766  7674  7880 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 14:21:19.767  7674  7880 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-29 14:21:19.768  6843  6843 D BluetoothPermissionRequest: onReceive
08-29 14:21:19.768  7674  7900 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 14:21:19.770  7674  7880 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:19.773  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 14:21:19.781  7674  7880 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:19.782  7674  7674 D HeadsetService: Received start request. Starting profile...
,08-29 14:21:19.783  7674  7674 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 14:21:19.783  7674  7674 D LGBluetoothHfpAdapter: Version 1.6
08-29 14:21:19.786  7674  7674 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 14:21:19.787  7674  7674 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 14:21:19.788  7674  7674 D HeadsetStateMachine: make
08-29 14:21:19.789  7674  7880 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:19.795  7674  7880 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 14:21:19.801  7674  7880 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:19.806  7674  7880 E BluetoothAdapterService: File transfer profiles supported!!
08-29 14:21:19.810  7674  7880 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 14:21:19.824  7674  7674 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:19.825  7674  7880 V LGMDMManager: Create singleton instance
08-29 14:21:19.825  7674  7674 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 14:21:19.826  7674  7880 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 14:21:19.828  7674  7674 D HeadsetStateMachine: max_hf_connections = 1
08-29 14:21:19.828  7674  7674 I bluedroid-qcom: get_profile_interface handsfree
08-29 14:21:19.830  7674  7674 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 14:21:19.831   320  1366 V AudioPolicyService: registerClient() client 0xb0410900, uid 1002
08-29 14:21:19.831   320  1367 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 14:21:19.831   320  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 14:21:19.831   320  1367 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 14:21:19.831  7674  7674 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 14:21:19.832   320  1702 V AudioFlinger: registerClient() client 0xb55819d0, pid 7674
08-29 14:21:19.832   320  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:19.832   320  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:19.832  1042  1058 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:19.833   320  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:19.833   320  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:19.833  1590  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:19.833  1590  2084 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:19.833  1590  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:19.833  1590  2084 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:19.833  1839  2420 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:19.833  1839  2420 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:19.833  1839  2420 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:19.833  7674  7690 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:19.833  1839  2420 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:19.833  7674  7690 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 14:21:19.833  7674  7690 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:19.833  7674  7690 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 14:21:19.833  1042  1058 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:19.833  1042  1058 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:19.833  1042  1058 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:19.834  7674  7674 V ToneGenerator: Create Track: 0xb4928080
08-29 14:21:19.834  7674  7674 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 14:21:19.834  7674  7674 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 14:21:19.834  3433  3452 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 14:21:19.834  3433  3452 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 14:21:19.834   320  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 14:21:19.834  3433  3452 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 14:21:19.834   320  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 14:21:19.834   320  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 14:21:19.834  3433  3452 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 14:21:19.834   320  1366 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 14:21:19.834   320  1367 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 ,14:21:19.835   320  1702 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 14:21:19.835   320  1702 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 14:21:19.835   320  1702 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 14:21:19.835   320  1702 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 14:21:19.835  7674  7674 V AudioSystem: getLatency() output 2, latency 50
08-29 14:21:19.835  7674  7674 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 14:21:19.835  7674  7674 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 14:21:19.835   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 14:21:19.835   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 14:21:19.835   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 14:21:19.835   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 14:21:19.835   320   320 V AudioFlinger: createTrack() lSessionId: 23
08-29 14:21:19.836  7674  7674 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 14:21:19.836   320  1366 V AudioFlinger: acquiring 23 from 7674, for 7674
08-29 14:21:19.836   320  1366 V AudioFlinger:  added new entry for 23
08-29 14:21:19.837  7674  7674 V ToneGenerator: ToneGenerator INIT OK, time: 134754
08-29 14:21:19.837  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:19.838  7674  7902 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,08-29 14:21:19.842  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:19.844  7674  7902 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 14:21:19.844  7674  7902 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 14:21:19.844  7674  7902 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 14:21:19.845  7674  7674 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:19.846   320  1702 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7674
08-29 14:21:19.846   320  1702 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 14:21:19.846  7674  7674 D A2dpService: Received start request. Starting profile...
08-29 14:21:19.846   320  1702 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 14:21:19.846   320  1702 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,08-29 14:21:19.846   320  1702 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 14:21:19.846   320  1702 V voice   : voice_set_parameters: exit with code(0)
08-29 14:21:19.846   320  1702 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 14:21:19.846   320  1702 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 14:21:19.847   320  1702 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 14:21:19.847   320  1702 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 14:21:19.847   320  1702 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 14:21:19.847   320  1702 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 14:21:19.847  7674  7674 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 14:21:19.847  7674  7902 V ToneGenerator: ToneGenerator destructor
08-29 14:21:19.847  7674  7902 V ToneGenerator: stopTone
08-29 14:21:19.847  7674  7902 V ToneGenerator: Delete Track: 0xb4928080
08-29 14:21:19.848  7674  7674 V Avrcp   : make
08-29 14:21:19.848  7674  7674 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 14:21:19.848  7674  7674 I bluedroid-qcom: get_profile_interface avrcp
08-29 14:21:19.849  7674  7902 V AudioTrack: ~AudioTrack, releasing session id from 7674 on behalf of 7674
08-29 14:21:19.849   320  1367 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 14:21:19.849   320  1367 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 14:21:19.849   320  1272 V AudioPolicyService: AudioCommandThread() waking up
08-29 14:21:19.849   320  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 14:21:19.849   320  1272 V AudioPolicyManager: releaseOutput() 2
08-29 14:21:19.849   320  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 14:21:19.849   320  1367 V AudioFlinger: PlaybackThread::Track destructor
08-29 14:21:19.849   320  1367 V AudioFlinger: removeClient_l() pid 7674, calling pid 320
08-29 14:21:19.849   320  1702 V AudioFlinger: releasing 23 from 7674 for 7674
08-29 14:21:19.850   320  1702 V AudioFlinger:  decremented refcount to 0
08-29 14:21:19.850   320  1702 V AudioFlinger: purging stale effects
08-29 14:21:19.857  7674  7674 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 14:21:19.863  7674  7674 E AudioManager: No RCC entry present to update
08-29 14:21:19.863  7674  7674 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 14:21:19.866  7674  7674 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 14:21:19.867  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 14:21:19.867  7674  7674 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 14:21:19.871  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 14:21:19.980  1042  1874 V SIM_STK : Menu title from STK is T-Mobile
08-29 14:21:19.980  1042  1874 V SIM_STK : Menu title from STK is T-Mobile
,08-29 14:21:20.114  1042  1983 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 14:21:20.130  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-29 14:21:20.139  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 14:21:20.140  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 14:21:20.141  7674  7674 I BluetoothA2dpServiceJni: classInitNative
08-29 14:21:20.141  7674  7674 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 14:21:20.141  7674  7674 D A2dpStateMachine: make
08-29 14:21:20.145  7674  7674 I bluedroid-qcom: get_profile_interface a2dp
08-29 14:21:20.145  7674  7911 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 14:21:20.149  7674  7674 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 14:21:20.149  7674  7674 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 14:21:20.151  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:20.151  7674  7910 D A2dpStateMachine: Enter Disconnected: -2
08-29 14:21:20.154  7674  7674 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 14:21:20.157  7674  7674 D HidService: Received start request. Starting profile...
08-29 14:21:20.158  7674  7674 I bluedroid-qcom: get_profile_interface hidhost
08-29 14:21:20.158  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:20.158  7674  7674 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 14:21:20.160  7674  7674 D HealthService: Received start request. Starting profile...
,08-29 14:21:20.164  7674  7674 I bluedroid-qcom: get_profile_interface health
08-29 14:21:20.165  7674  7674 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 14:21:20.165  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:20.166  7674  7674 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 14:21:20.169  7674  7674 D PanService: Received start request. Starting profile...
08-29 14:21:20.169  7674  7674 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 14:21:20.169  7674  7674 I bluedroid-qcom: get_profile_interface pan
08-29 14:21:20.177  7674  7674 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-29 14:21:20.178  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:20.179  7674  7674 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 14:21:20.187  7674  7674 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 14:21:20.187  7674  7674 D BtGatt.GattService: Received start request. Starting profile...
08-29 14:21:20.188  7674  7674 D BtGatt.GattService: start()
08-29 14:21:20.188  7674  7674 I bluedroid-qcom: get_profile_interface gatt
08-29 14:21:20.188  7674  7674 D BtGatt.AdvertiseManager: advertise manager created
08-29 14:21:20.194  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
,08-29 14:21:20.196  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
,08-29 14:21:20.197  7674  7674 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 14:21:20.198  7674  7674 V BluetoothMapService: BluetoothMapBinder()
08-29 14:21:20.199  7674  7674 D BluetoothMapService: Received start request. Starting profile...
08-29 14:21:20.199  7674  7674 D BluetoothMapService: start()
08-29 14:21:20.203  7674  7674 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 14:21:20.203  7674  7674 D BluetoothMapEmailAppObserver: createReceiver()
08-29 14:21:20.204  7674  7674 D BluetoothMapEmailAppObserver: initObservers()
08-29 14:21:20.204  7674  7674 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 14:21:20.215  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:20.216  7674  7674 D HeadsetStateMachine: Proxy object connected
08-29 14:21:20.217  7674  7674 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 14:21:20.217  7674  7674 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 14:21:20.223  7674  7674 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 14:21:20.224  7674  7902 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 14:21:20.224  7674  7902 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 14:21:20.225  7674  7902 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 14:21:20.225  7674  7674 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:20.225  7674  7674 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:20.225  7674  7674 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 14:21:20.225  7674  7674 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:20.226  7674  7674 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 14:21:20.235  7674  7674 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 14:21:20.238  7674  7674 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 14:21:20.243  7674  7674 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 14:21:20.244  7674  7674 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 14:21:20.249  7674  7674 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 14:21:20.254  7674  7674 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 14:21:20.255  7674  7674 V BluetoothMapService: Handler(): got msg=1
08-29 14:21:20.256  7674  7880 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 14:21:20.256  7674  7880 I bluedroid-qcom: enable
08-29 14:21:20.257  7674  7921 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 14:21:20.257  7674  7921 I bt-btu  : btu_task pending for preload complete event
08-29 14:21:20.257  7674  7880 I bt_hci_bdroid: init
08-29 14:21:20.258  7674  7880 I bt_vendor: bt-vendor : init
08-29 14:21:20.258  7674  7880 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 14:21:20.259  7674  7880 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 14:21:20.259  7674  7880 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 14:21:20.259  7674  7880 D bt_userial_mct: userial_init
08-29 14:21:20.259  7674  7880 D bt_hci_bdroid: set_power 1
08-29 14:21:20.259  7674  7880 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 14:21:20.259  7674  7880 I bt_vendor: Starting hciattach daemon
08-29 14:21:20.259  7674  7880 I bt_vendor: try to set true
08-29 14:21:20.248  7924  7924 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:20.248  7924  7924 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 14:21:20.285  7925  7925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 14:21:20.363  7931  7931 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 14:21:20.376  7932  7932 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-29 14:21:20.403  7934  7934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 14:21:20.416  7935  7935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 14:21:20.428  7936  7936 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-29 14:21:20.453  7937  7937 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 14:21:20.478  7939  7939 I libmdmdetect: ESOC framework not supported
,08-29 14:21:20.479  7939  7939 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-29 14:21:20.488  7939  7939 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 14:21:20.488  7939  7939 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 14:21:20.488  7939  7939 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 14:21:20.488  7939  7939 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 14:21:20.488  7939  7939 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 14:21:20.488  7939  7939 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 14:21:20.488  7939  7939 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 14:21:20.524  7939  7940 E QC-QMI  : qmi_client [7939] 15: failed to locate client data
,08-29 14:21:20.525   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 14:21:20.525   474   474 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-29 14:21:20.557  7941  7941 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 14:21:20.583  7942  7942 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 14:21:20.611  7674  7880 I bt_vendor: bluetooth satus is on
,08-29 14:21:20.611  7674  7880 D bt_hci_bdroid: preload
,08-29 14:21:20.611  7674  7923 D bt_userial_mct: userial_open(port:0)
08-29 14:21:20.611  7674  7923 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 14:21:20.615  7674  7923 I bt_vendor: Done intiailizing UART
,08-29 14:21:20.618  7674  7923 I bt_vendor: Done intiailizing UART
08-29 14:21:20.618  7674  7923 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 14:21:20.618  7674  7923 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 14:21:20.618  7674  7944 D bt_userial_mct: Entering userial_read_thread()
08-29 14:21:20.618  7674  7921 I bt-btu  : btu_task received preload complete event
08-29 14:21:20.619  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 14:21:20.619  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 14:21:20.621  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 14:21:20.625  7674  7921 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 14:21:20.626  7674  7921 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 14:21:20.626  7674  7921 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 14:21:20.626  7674  7921 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 14:21:20.704  7674  7921 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-29 14:21:20.704  7674  7921 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0165061 
,08-29 14:21:20.704  7674  7921 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0165061 
,08-29 14:21:20.738  7674  7884 E bt-btif : Calling BTA_HhEnable
,08-29 14:21:20.738  7674  7884 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 14:21:20.738  7674  7884 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 14:21:20.744  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 14:21:20.744  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 14:21:20.744  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 14:21:20.745  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 14:21:20.746  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 14:21:20.746  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 14:21:20.746  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 14:21:20.747  7674  7884 D BluetoothAdapterProperties: Name is: G3
08-29 14:21:20.748  7674  7884 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:20.748  7674  7884 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:21:20.748  7674  7884 D bt_hci_bdroid: postload
08-29 14:21:20.749  7674  7923 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:20.749  7674  7923 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:20.750  7674  7923 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:20.750  7674  7884 D bte_conf: Device ID record 1 : primary
08-29 14:21:20.750  7674  7884 D bte_conf:   vendorId            = 00c4
08-29 14:21:20.750  7674  7884 D bte_conf:   vendorIdSource      = 0001
08-29 14:21:20.750  7674  7884 D bte_conf:   product             = 13a1
08-29 14:21:20.750  7674  7884 D bte_conf:   version             = 1000
08-29 14:21:20.750  7674  7884 D bte_conf:   clientExecutableURL = 
08-29 14:21:20.751  7674  7884 D bte_conf:   serviceDescription  = 
08-29 14:21:20.751  7674  7884 D bte_conf:   documentationURL    = 
08-29 14:21:20.751  7674  7884 D bte_conf: bte_load_did_conf no section named DID2.
08-29 14:21:20.751  7674  7921 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 14:21:20.754  7674  7880 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 14:21:20.755  7674  7880 D BluetoothAdapterProperties: ScanMode =  20
,08-29 14:21:20.759  7674  7880 D BluetoothAdapterProperties: State =  11
08-29 14:21:20.760  7674  7880 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 14:21:20.760  7674  7880 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 14:21:20.760  7674  7880 D BluetoothAdapterProperties: Setting state to 12
08-29 14:21:20.760  7674  7880 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 14:21:20.761  7674  7884 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 14:21:20.761  7674  7884 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 14:21:20.758  7949  7949 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:20.758  7949  7949 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:20.770  1042  1118 D BluetoothManagerService: Message: 60
08-29 14:21:20.770  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 14:21:20.770  1042  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-29 14:21:20.774  7674  7921 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:20.777  7674  7921 W bt-smp  : Plain text(LSB ~ MSB) = f7 90 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:20.777  7674  7921 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 b2 a5 96 b2 a8 f8 ff 64 93 a5 58 fc 3e 2b 78 
08-29 14:21:20.778  7674  7923 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 14:21:20.778  7674  7921 W bt-btm  : Stopping oneshot timer
08-29 14:21:20.778  7674  7944 E bt_mct  : hci lib postload completed
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:20.800  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:20.804  7674  7884 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:21:20.805  7674  7884 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 14:21:20.805  7674  7880 I BluetoothAdapterState: Entering On State
08-29 14:21:20.812  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:20.817  7674  7921 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:20.817  7674  7921 W bt-smp  : Plain text(LSB ~ MSB) = 0b 97 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:20.817  7674  7921 W bt-smp  : Encrypted text(LSB ~ MSB) = 1e 75 0b 0c 59 e5 32 08 e0 55 80 57 89 60 ca e0 
08-29 14:21:20.818  7674  7921 W bt-btm  : Stopping oneshot timer
08-29 14:21:20.829  7674  7880 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 14:21:20.829  7674  7880 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 14:21:20.829  7674  7880 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 14:21:20.837  7674  7880 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 14:21:20.838  6843  6863 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:21:20.842  7674  7921 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-29 14:21:20.842  7674  7921 W bt-smp  : Plain text(LSB ~ MSB) = 45 15 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:20.842  7674  7921 W bt-smp  : Encrypted text(LSB ~ MSB) = e6 03 45 ad 8a ed 0b 5c b2 bf e8 ea 28 ca 24 cb 
08-29 14:21:20.842  7674  7921 W bt-btm  : Stopping oneshot timer
08-29 14:21:20.850  6843  6863 D BluetoothPan: onBluetoothStateChange on: true
08-29 14:21:20.850  6843  6863 D BluetoothPan: onBluetoothStateChange call bindService
08-29 14:21:20.855  7674  7880 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 14:21:20.862  7674  7921 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 14:21:20.862  7674  7921 W bt-smp  : Plain text(LSB ~ MSB) = 06 fe 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:20.862  7674  7921 W bt-smp  : Encrypted text(LSB ~ MSB) = 6b b9 e6 a1 4a 37 5f 39 1d ed 2c a4 29 4d d3 3a 
08-29 14:21:20.862  7674  7921 W bt-btm  : Stopping oneshot timer
08-29 14:21:20.869  1042  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:21:20.885  7674  7921 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-29 14:21:20.885  7674  7921 W bt-smp  : Plain text(LSB ~ MSB) = 80 0c 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 14:21:20.885  7674  7921 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f 27 ca da 7c 6c c1 ac 17 63 4f 49 92 87 f1 ef 
08-29 14:21:20.885  7674  7921 W bt-btm  : Stopping oneshot timer
,08-29 14:21:20.897  7954  7954 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 14:21:20.906  6843  6843 D BluetoothInputDevice: Proxy object connected
,08-29 14:21:20.907  6843  6843 D HidProfile: Bluetooth service connected
08-29 14:21:20.909  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:20.910  1042  1042 D BluetoothA2dp: Proxy object connected
08-29 14:21:20.915  6843  6843 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:21:20.915  6843  6843 D PanProfile: Bluetooth service connected
08-29 14:21:20.917  6843  6864 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:20.917  1839  1839 D BluetoothHeadset: Proxy object connected
,08-29 14:21:20.920  6843  6843 D BluetoothHeadset: Proxy object connected
08-29 14:21:20.920  6843  6843 D HeadsetProfile: Bluetooth service connected
08-29 14:21:20.921  6843  6981 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 14:21:20.923  1839  2420 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:20.925  1839  1839 D BluetoothHeadset: Proxy object connected
08-29 14:21:20.925  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:20.926  1839  1839 D BluetoothHeadset: Proxy object connected
08-29 14:21:20.926  6843  6863 D BluetoothMap: onBluetoothStateChange: up=true
08-29 14:21:20.929  6843  6843 D BluetoothMap: Proxy object connected
08-29 14:21:20.929  6843  6843 D MapProfile: Bluetooth service connected
08-29 14:21:20.929  6843  6843 D BluetoothMap: getConnectedDevices()
,08-29 14:21:20.930  7674  7690 V BluetoothMapService: getConnectedDevices()
08-29 14:21:20.930  6843  6981 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:21:20.934  6843  6843 D BluetoothA2dp: Proxy object connected
08-29 14:21:20.934  6843  6843 D A2dpProfile: Bluetooth service connected
08-29 14:21:20.934  1042  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:20.936  1042  1042 D BluetoothHeadset: Proxy object connected
,08-29 14:21:20.939  1042  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 14:21:20.939  1042  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 14:21:20.941  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 14:21:20.941  1042  1118 D BluetoothManagerService: Message: 40
08-29 14:21:20.942  1042  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-29 14:21:20.943  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:20.943  1929  2111 D LGBluetoothAPIService: Message: 1
08-29 14:21:20.943  1929  2111 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 14:21:20.943  1929  2111 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 14:21:20.943  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 14:21:20.943  1929  2111 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 14:21:20.946  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:20.953  7674  7674 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:20.953  7674  7674 D BluetoothMapService: STATE_ON
08-29 14:21:20.953  7674  7674 V BluetoothMapService: Handler(): got msg=1
08-29 14:21:20.954  7674  7674 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-29 14:21:20.955  7674  7974 D BluetoothMapMasInstance: MAS initSocket()
08-29 14:21:20.956  7674  7974 D BluetoothMapMasInstance:   masId = 00
08-29 14:21:20.956  7674  7974 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 14:21:20.956  7674  7974 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 14:21:20.956  7674  7974 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 14:21:20.956  6843  6843 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 14:21:20.957  6843  6843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 14:21:20.963  6843  6843 D DockEventReceiver: finishStartingService: stopping service
08-29 14:21:20.968  1042  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 14:21:20.969  7674  7974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:20.971  7674  7884 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:21:20.971  7674  7884 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 14:21:20.972  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:20.972  7674  7674 V BluetoothPbapService: Pbap Service onCreate
08-29 14:21:20.972  7674  7674 V BluetoothPbapService: Starting PBAP service
08-29 14:21:20.973  7674  7674 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 14:21:20.974  7674  7674 V BluetoothPbapService: Pbap Service onBind
08-29 14:21:20.974  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:20.975  7674  7974 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 14:21:20.976  7674  7974 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 14:21:20.976  7674  7674 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:20.976  7674  7674 V BluetoothPbapService: state: 12
08-29 14:21:20.976  6843  6843 D BluetoothPbap: Proxy object connected
08-29 14:21:20.976  6843  6843 D PbapServerProfile: Bluetooth service connected
08-29 14:21:20.976  7674  7974 D BluetoothMapMasInstance: Accepting socket connection...
08-29 14:21:20.976  7674  7674 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 14:21:20.976  7674  7674 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:20.977  7674  7674 V BluetoothPbapReceiver: ***********state = 12
08-29 14:21:20.978  7674  7674 V BluetoothPbapService: Handler(): got msg=1
08-29 14:21:20.978  7674  7674 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 14:21:20.979  7674  7976 V BluetoothPbapService: Pbap Service initSocket
,08-29 14:21:20.980  1042  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 14:21:20.981  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:20.981  2195  2195 D c       : Getting all permits...
08-29 14:21:20.981  2195  2195 D a       : Opening database...
08-29 14:21:20.982  7674  7976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:20.983  7674  7976 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 14:21:20.983  7674  7976 V BluetoothPbapService: Succeed to create listening socket 
08-29 14:21:20.983  7674  7976 V BluetoothPbapService: Accepting socket connection...
08-29 14:21:20.986  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-29 14:21:20.986  2195  2195 D a       : Closing database...
08-29 14:21:20.995  6843  6843 D BluetoothPermissionRequest: onReceive
,08-29 14:21:20.997  6843  6843 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 14:21:20.999  6843  6843 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 14:21:21.002  7674  7674 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 14:21:21.004  7674  7674 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 14:21:21.013  7674  7674 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 14:21:21.038  7674  7674 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 14:21:21.038  7674  7674 V BtOppService: onCreate
,08-29 14:21:21.043  7674  7674 V BluetoothOppNotification: send message
08-29 14:21:21.048  7674  7674 V BtOppService: Starting RfcommListener
08-29 14:21:21.056  7674  7674 D BluetoothOppPreference: Dumping Names:  
08-29 14:21:21.056  7674  7674 D BluetoothOppPreference: {}
,08-29 14:21:21.056  7674  7674 D BluetoothOppPreference: Dumping Channels:  
,08-29 14:21:21.056  7674  7674 D BluetoothOppPreference: {}
08-29 14:21:21.058  7674  7674 V BtOppService: onStartCommand
08-29 14:21:21.061  7674  7983 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 14:21:21.065  7674  7980 V BtOppService: Deleted complete outbound shares, number =  0
08-29 14:21:21.065  7674  7983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 14:21:21.066  7674  7674 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:21.067  7674  7674 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 14:21:21.072  7674  7980 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 14:21:21.073  7674  7980 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 14:21:21.073  7674  7674 V BluetoothOppNotification: new notify threadi!
08-29 14:21:21.075  7674  7674 V BluetoothOppNotification: send delay message
,08-29 14:21:21.076  7674  7674 V BtOppService: start RfcommListener
08-29 14:21:21.077  7674  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 14:21:21.077  7674  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38e3f7ac on behalf of 
08-29 14:21:21.079  7674  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@298f0c75 on behalf of 
08-29 14:21:21.080  7674  7984 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 14:21:21.082  7674  7674 V BtOppService: RfcommListener started
08-29 14:21:21.082  7674  7674 V BtOppService: ContentObserver received notification
08-29 14:21:21.084  7674  7985 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 14:21:21.085  1042  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:21.087  7674  7985 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:21.089  7674  7985 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-29 14:21:21.089  7674  7985 V BtOppRfcommListener: Started RFCOMM listener....
08-29 14:21:21.090  7674  7985 I BtOppRfcommListener: Accept thread started.
08-29 14:21:21.090  7674  7985 V BtOppRfcommListener: Accepting connection...
,08-29 14:21:21.108  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
08-29 14:21:21.108  7674  7674 V BluetoothFtpService: Ftp Service onCreate
08-29 14:21:21.108  7674  7674 I BluetoothFtpService: Ftp Service onCreate
08-29 14:21:21.108  7674  7674 V BluetoothFtpService: Ftp Service onStartCommand
08-29 14:21:21.108  7674  7674 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:21.108  7674  7674 V BluetoothFtpService: Starting Listening on sockets
08-29 14:21:21.108  7674  7674 V BtOppService: ContentObserver received notification
08-29 14:21:21.109  7674  7674 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 14:21:21.109  7674  7674 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 14:21:21.109  7674  7674 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 14:21:21.109  7674  7674 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:21.109  7674  7674 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 14:21:21.109  7674  7674 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 14:21:21.186  1042  1874 I art     : Explicit concurrent mark sweep GC freed 26177(1286KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.068ms total 107.888ms
,08-29 14:21:21.187  7674  7983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3910947b on behalf of 
08-29 14:21:21.188  7674  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 14:21:21.189  7674  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b6ee298 on behalf of 
08-29 14:21:21.190  7674  7984 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 14:21:21.192  7674  7674 V BluetoothFtpService: Handler(): got msg=1
08-29 14:21:21.194  7674  7984 V BluetoothOppNotification: outbound notification was removed.
08-29 14:21:21.195  7674  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 14:21:21.195  7674  7674 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 14:21:21.195  7674  7674 V BluetoothFtpService: Ftp Service initSocket
08-29 14:21:21.197  7674  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20d0faf1 on behalf of 
08-29 14:21:21.199  7674  7983 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 14:21:21.199  7674  7983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 14:21:21.200  7674  7983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cd676d6 on behalf of 
08-29 14:21:21.201  7674  7983 V BluetoothOppNotification: update too frequent, put in queue
08-29 14:21:21.201  7674  7983 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-29 14:21:21.205  7674  7984 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 14:21:21.208  7674  7984 V BluetoothOppNotification: inbound notification was removed.
08-29 14:21:21.208  1042  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:21.208  7674  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 14:21:21.209  7674  7674 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:21.210  7674  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f09fd57 on behalf of 
08-29 14:21:21.211  7674  7674 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-29 14:21:21.211  7674  7674 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 14:21:21.213  7674  7986 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-29 14:21:21.227  7674  7674 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5044ff0
,08-29 14:21:21.227  7674  7674 V BluetoothSapService: Sap Service onCreate
08-29 14:21:21.229  7674  7674 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:21.229  7674  7674 V BluetoothSapService: state: 12
08-29 14:21:21.229  7674  7674 V BluetoothSapService: Starting SAP server process
08-29 14:21:21.231  7674  7674 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 14:21:21.218  7987  7987 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:21.218  7987  7987 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:21.234  7674  7988 V BluetoothSapService: Sap Service initRfcommSocket
08-29 14:21:21.235  1042  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:21.236  7674  7988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:21.238  7674  7988 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-29 14:21:21.239  7674  7988 V BluetoothSapService: Succeed to create listening socket 
08-29 14:21:21.239  7674  7988 V BluetoothSapService: Accepting socket connection...
,08-29 14:21:21.243  7987  7987 V BT_SAP  : Event pipe created
,08-29 14:21:21.243  7987  7987 V BT_SAP  : create_server_socket qcom.sap.server
08-29 14:21:21.243  7987  7987 V BT_SAP  : created socket fd 6
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:21.664  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:21.670  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:21.672  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:21.673  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@656704d added. We now have 8 listener(s)
08-29 14:21:21.673  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.676  1042  1874 D WifiServiceImplEx: setWifiEnabled: false pid=6640, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 14:21:21.676  1042  1874 D WifiService: setWifiEnabled: false pid=6640, uid=10118
08-29 14:21:21.676  1042  1874 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 14:21:21.681  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.687  1042  2020 D WifiServiceImplEx: setWifiEnabled: true pid=6640, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 14:21:21.688  1042  2020 D WifiService: setWifiEnabled: true pid=6640, uid=10118
08-29 14:21:21.688  1042  2020 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:21:21.706  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 14:21:21.706  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 14:21:21.706  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-29 14:21:21.708  1042  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 14:21:21.708  1042  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 14:21:21.710  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 14:21:21.710  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 14:21:21.710  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 14:21:21.710  1042  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 14:21:21.710  1042  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 14:21:21.711  1042  1526 E WifiHW  : unknown target_country: EU , set to default
08-29 14:21:21.711  1042  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 14:21:21.711  1042  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 14:21:21.711  1042  1526 I WifiUtil: gEnableBmps=1
08-29 14:21:22.082  7674  7674 V BluetoothOppNotification: new notify threadi!
,08-29 14:21:22.091  7674  7674 V BluetoothOppNotification: send delay message
08-29 14:21:22.109  7674  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 14:21:22.120  7674  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cc717f3 on behalf of 
08-29 14:21:22.127  7674  8006 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-29 14:21:22.143  7674  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-29 14:21:22.156  7674  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3036cb0 on behalf of 
08-29 14:21:22.157  7674  8006 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 14:21:22.166  7674  8006 V BluetoothOppNotification: outbound notification was removed.
08-29 14:21:22.166  7674  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 14:21:22.196  7674  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13b31729 on behalf of 
08-29 14:21:22.196  7674  8006 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 14:21:22.201  7674  8006 V BluetoothOppNotification: inbound notification was removed.
,08-29 14:21:22.201  7674  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 14:21:22.201  7674  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7058aae on behalf of 
08-29 14:21:22.291   315   911 D SoftapController: Softap fwReload - Ok
,08-29 14:21:22.313  1042  1526 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (597ms)
,08-29 14:21:22.373  1042  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:21:22.373  1042  1118 D Tethering: InitialState.processMessage what=4
08-29 14:21:22.374  1042  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 14:21:22.400   315   911 D CommandListener: Setting iface cfg
08-29 14:21:22.401   315   911 D CommandListener: Trying to bring down wlan0
08-29 14:21:22.403  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:22.403  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 14:21:22.403  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 14:21:22.403  6843  6843 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-29 14:21:22.403   315   911 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:21:22.404  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 14:21:22.406  6843  6843 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 14:21:22.407  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 14:21:22.407  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 14:21:22.407  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 14:21:22.407  6843  6843 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 14:21:22.407  6843  6843 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 14:21:22.413  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:22.413  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 14:21:22.413  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 14:21:22.413  6843  6843 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 14:21:22.414  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 14:21:22.415  1042  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 14:21:22.416  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:22.416  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:22.416  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 14:21:22.408  8024  8024 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:22.408  8024  8024 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:22.420  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 14:21:22.422  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:22.422  6843  6843 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 14:21:22.422  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 14:21:22.422  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 14:21:22.423  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 14:21:22.423  6843  6843 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 14:21:22.423  6843  6843 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 14:21:22.424  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 14:21:22.425  1042  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 14:21:22.425  1042  1526 D WifiMonitor: connecting to supplicant
08-29 14:21:22.427  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:22.445  8024  8024 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 14:21:22.469  1042  1058 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8027 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 14:21:22.478  8024  8024 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 14:21:22.478  8024  8024 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 14:21:22.536  8024  8024 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 14:21:22.590  8024  8024 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 14:21:22.597  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 14:21:22.597  1042  1983 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8049 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 14:21:22.597  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 14:21:22.598  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 14:21:22.598  1042  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 14:21:22.599  1042  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:22.600  1042  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:22.600  1042  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 14:21:22.600  1042  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 14:21:22.601  1042  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 14:21:22.601  1042  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,08-29 14:21:22.601  1042  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 14:21:22.602  1042  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 14:21:22.602  1042  1526 E WifiStateMachine: useWiFiOffloading() : false
08-29 14:21:22.602  1042  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 14:21:22.603  8024  8024 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 14:21:22.604  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.604  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.604  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 14:21:22.604  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.604  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 14:21:22.604  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.604  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 14:21:22.604  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 14:21:22.604  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 14:21:22.604  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 14:21:22.604  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-29 14:21:22.606  1042  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 14:21:22.607  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 14:21:22.608  1929  1929 D WfdService: Waiting for WifiP2p enabling
08-29 14:21:22.608  1042  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 14:21:22.608  1042  1526 D WifiNative-wlan0: SET update_config 1: returned true
08-29 14:21:22.608  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:22.608  1042  1526 D WifiConfigStore: Loading config and enabling all networks 
08-29 14:21:22.608  1042  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 14:21:22.609  1042  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:22.616  6640  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:22.618  8027  8047 W FormManager: Network not available. Please check & try again.
08-29 14:21:22.618  1042  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 14:21:22.621  6640  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:22.623  8027  8048 V FormManager: Network unavailable.
08-29 14:21:22.625  8027  8048 V FormManager: Network unavailable.
08-29 14:21:22.631  1042  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 14:21:22.631  1042  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 14:21:22.632  1042  1526 D WifiStateMachine: enableVerboseLogging : level 2
,08-29 14:21:22.633  1042  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 14:21:22.633  1042  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 14:21:22.633  1042  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 14:21:22.634  1042  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 14:21:22.634  1042  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-29 14:21:22.634  1042  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 14:21:22.634  1042  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 14:21:22.635  1042  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 14:21:22.635  1042  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 14:21:22.635  1042  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 14:21:22.635  1042  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 14:21:22.636  1042  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 14:21:22.636  1042  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 14:21:22.636  1042  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 14:21:22.637  1042  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 14:21:22.637  1042  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 14:21:22.637  1929  1929 D WfdsService: Supplicant Connection state is changed : true
08-29 14:21:22.638  1929  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 14:21:22.638  1929  2288 D WfdsService: Set the WFDS Monitor: true
08-29 14:21:22.638  1929  2288 D WfdsMonitor: WfdsMonitorThread create
08-29 14:21:22.638  1042  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 14:21:22.638  1042  1526 D WifiNative-HAL: Setting external_sim to 1
08-29 14:21:22.638  1042  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 14:21:22.638  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.638  1929  2288 D WfdsMonitor: WFDS Monitor is created and started
08-29 14:21:22.638  1929  2288 D WfdsService: WiFi: Supplicant connection re-established
08-29 14:21:22.638  1042  1526 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 14:21:22.638  1042  1526 I WifiNative-HAL: startHal
08-29 14:21:22.638  1042  1526 D wifi    : setting scan oui 0xaf6cfcc0
08-29 14:21:22.639  1042  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 14:21:22.639  1042  1526 I WifiNative-HAL: startHal
08-29 14:21:22.639  1042  1526 D wifi    : setting scan oui 0xaf6cfcc0
08-29 14:21:22.639  1042  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 14:21:22.640  1042  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 14:21:22.640  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 14:21:22.640  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 14:21:22.640  1929  8068 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 14:21:22.640  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 14:21:22.641  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 14:21:22.641  1929  8068 E CtrlSupplicant: Succeed to open control connection
08-29 14:21:22.641  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 14:21:22.641  1929  8068 E CtrlSupplicant: Succeed to open monitor connection
08-29 14:21:22.641  1929  8068 D WfdsMonitor: Supplicant connection established
08-29 14:21:22.641  1929  2288 D WfdsService: Connected to the supplicant for wfds
08-29 14:21:22.641  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 14:21:22.641  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 14:21:22.642  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 14:21:22.642  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 14:21:22.642  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 14:21:22.642  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 14:21:22.643  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 14:2,1:22.644  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 14:21:22.644  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 14:21:22.644  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 14:21:22.644  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 14:21:22.645  8024  8024 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-29 14:21:22.645  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 14:21:22.646  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 14:21:22.646  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 14:21:22.646  1042  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 14:21:22.647  1042  1526 E WifiNative: : [137,548,558 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 14:21:22.647  1042  1526 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 14:21:22.647  1042  1526 D WifiNative-wlan0: RECONNECT: returned true
08-29 14:21:22.647  1042  1526 D WifiNative-wlan0: doString: [STATUS]
08-29 14:21:22.648  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 14:21:22.648  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 14:21:22.648  1042  1526 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 14:21:22.648  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:22.649  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
08-29 14:21:22.649  1042  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.650  1042  2005 I ActivityManager: Killing 7131:com.android.chrome/u0a57 (adj 15): empty #17
08-29 14:21:22.650   315   911 D CommandListener: Setting iface cfg
08-29 14:21:22.650   315   911 D CommandListener: Trying to bring up p2p0
08-29 14:21:22.650  1042  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 14:21:22.651  1042  1524 D LGWifiP2pService: P2pEnablingState
08-29 14:21:22.651  1042  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.651  1042  1524 D LGWifiP2pService: P2p socket connection successful
08-29 14:21:22.651  1042  1524 D LGWifiP2pService: P2pEnabledState
08-29 14:21:22.672  8049  8049 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 14:21:22.688  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:22.689  1042  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-29 14:21:22.689  1042  1524 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 14:21:22.689  1042  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 14:21:22.690  1042  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 14:21:22.690  1042  1526 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 14:21:22.690  1042  1526 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 14:21:22.690  1042  1562 W libprocessgroup: failed to open /acct/uid_10057/pid_7131/cgroup.procs: No such file or directory
08-29 14:21:22.690  1042  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 14:21:22.690  1042  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 14:21:22.690  1042  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=137592  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 14:21:22.690  1042  1524 D WifiNative-p2p0: SET device_name G3: returned true
08-29 14:21:22.690  1042  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 14:21:22.690  1042  1524 D LGWifiP2pService: before postfix = G3
08-29 14:21:22.691  1042  1524 D WifiServerServiceExt: postfix byte check : 2
08-29 14:21:22.691  1042  1524 D LGWifiP2pService: after postfix = G3
08-29 14:21:22.691  1042  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 14:21:22.691  1042  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 14:21:22.691  1042  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 14:21:22.691  1042  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 14:21:22.691  1042  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 14:21:22.692  1042  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 14:21:22.692  1042  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 14:21:22.693  1042  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 14:21:22.693  1042  1524 D WifiNative-HAL: p2pGetDeviceAddress
08-29 14:21:22.693  1042  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 14:21:22.693  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=137595  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 14:21:22.694  1042  1526 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 14:21:22.694  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 14:21:22.695  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 14:21:22.695  1042  1042 D RttService: SCAN_AVAILABLE : 3
08-29 14:21:22.696  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:22.696  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:22.696  1042  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.696  1042  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 14:21:22.696  1042  1543 I WifiNative-HAL: startHal
08-29 14:21:22.696  1042  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6cfcc0
08-29 14:21:22.696  1042  1543 D wifi    : failed to get capabilities : -3
08-29 14:21:22.696  1042  1543 E WifiScanningService: could not get scan capabilities
08-29 14:21:22.696  1042  1544 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.697  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:22.697  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.p,rovider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.697  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.697  1042  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 14:21:22.697  1042  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 14:21:22.697  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 14:21:22.697  1042  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 14:21:22.697  1042  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 14:21:22.698  8024  8024 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 14:21:22.698  1042  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 14:21:22.698  1042  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 14:21:22.698  1929  1929 D WfdsService: WifiP2pState is changed : true
08-29 14:21:22.698  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 14:21:22.698  1042  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 14:21:22.698  1042  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 14:21:22.699  1929  1929 D WfdsService: isConnected: false
08-29 14:21:22.699  1929  2288 D WfdsService: Receive the WFDS_ENABLE Method
08-29 14:21:22.699  1929  2288 D WfdsService: Set the WFDS Monitor: true
08-29 14:21:22.699  1929  2288 D WfdsService: Connected to the supplicant for wfds
,08-29 14:21:22.699  1929  2288 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 14:21:22.699  8024  8024 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 14:21:22.699  1929  2288 D WfdsService: selectPreferredScanChannel [36]
08-29 14:21:22.699  1929  2288 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 14:21:22.699  1042  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 14:21:22.699  1042  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 14:21:22.700  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 14:21:22.701  1042  1526 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 14:21:22.701  1042  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 14:21:22.702  1042  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 14:21:22.702  1042  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-29 14:21:22.702  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 14:21:22.703  1929  1929 D WfdsService: Update P2p Interface State: 3
,08-29 14:21:22.708  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:22.709  8024  8024 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 14:21:22.709  1042  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 14:21:22.709  1042  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 14:21:22.710  1042  1947 I ActivityManager: Killing 7149:com.lge.drmservice/u0a62 (adj 15): empty #17
08-29 14:21:22.710  1042  1526 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 14:21:22.710  1042  1526 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 14:21:22.711  1042  1526 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-29 14:21:22.711  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 14:21:22.712  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 14:21:22.713  8024  8024 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.714  8024  8024 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 14:21:22.714  8024  8024 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.714  1042  1526 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 14:21:22.714  1042  1526 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 14:21:22.714  8024  8024 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.715  1042  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 14:21:22.715  1042  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 14:21:22.715  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 14:21:22.715  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
,08-29 14:21:22.715  8024  8024 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 14:21:22.716  1042  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 14:21:22.716  1042  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 14:21:22.716  1929  8068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.716  1929  8068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.716  1042  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 14:21:22.716  1042  1526 D WifiNative-wlan0: doBoolean: SCAN
08-29 14:21:22.717  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 14:21:22.717  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.717  1042  1526 D WifiNative-wlan0: SCAN: returned false
,08-29 14:21:22.717  1042  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.717  1042  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.717  1042  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.717  1042  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.717  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 14:21:22.717  1042  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=137619  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 14:21:22.717  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 14:21:22.717  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:22.723  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:22.724  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:22.729  6640  6748 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 14:21:22.730  6640  6748 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 14:21:22.732  6640  6748 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2433de87 Bundle[{}]
,08-29 14:21:22.733  6640  6748 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 14:21:22.733  6640  6748 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 14:21:22.735  6640  6748 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 14:21:22.735  6640  6748 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 14:21:22.736  6640  6748 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 14:21:22.737  6640  6748 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 14:21:22.743  6640  6748 I System.out: Running OutgoingSocketThread
08-29 14:21:22.745  6640  8071 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
,08-29 14:21:22.746  6640  8071 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42028
08-29 14:21:22.746  6640  8071 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 14:21:22.775  1042  1524 D LGWifiP2pService: InactiveState
08-29 14:21:22.775  1042  1524 D LGWifiP2pService: InactiveState{ when=-76ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.775  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-76ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.775  1042  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-29 14:21:22.776  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-29 14:21:22.776  8024  8024 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.777  8024  8024 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 14:21:22.777  8024  8024 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.778  8024  8024 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.778  1042  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 14:21:22.778  1929  8068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 14:21:22.778  1042  1524 D LGWifiP2pService: InactiveState{ when=-65ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.778  1929  8068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.778  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-65ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.779  1929  8068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.779  1042  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.779  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.779  1042  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 14:21:22.779  1042  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.779  1042  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.779  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.779  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 14:21:22.779  1042  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.779  1042  1891 W libprocessgroup: failed to open /acct/uid_10062/pid_7149/cgroup.procs: No such file or directory
08-29 14:21:22.779  1042  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.779  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.780  1042  1524 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.779  1042  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.780  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.780  1042  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.780  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.780  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.780  1929  2288 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 14:21:22.780  1042  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 14:21:22.780  1042  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.780  1042  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.781  1042  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android,.internal.util.StateMachine$SmHandler }
08-29 14:21:22.781  1042  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.781  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.781  1042  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 14:21:22.781  1042  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.781  1042  1042 E WifiServerServiceExt: No p2p device connected
08-29 14:21:22.784  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=137686  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 14:21:22.784  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:22.784  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:22.785  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:22.786  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.786  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:22.786  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 14:21:22.786  1042  1526 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:22.787  1042  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:22.788  1042  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:22.789  1042  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 14:21:22.790  1042  1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-29 14:21:22.797  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:22.797  1042  1042 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-29 14:21:22.797  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:22.797  1042  1042 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 14:21:22.800  8049  8049 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:22.803  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:22.807  8027  8073 W FormManager: Network not available. Please check & try again.
08-29 14:21:22.807  8027  8074 V FormManager: Network unavailable.
,08-29 14:21:22.809  8027  8074 V FormManager: Network unavailable.
08-29 14:21:22.811  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:22.824  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 14:21:22.824  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 14:21:22.825  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:22.827  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 14:21:22.833  4305  8075 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 14:21:22.837  4305  8076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 14:21:22.837  4305  8076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 14:21:22.886  1042  1891 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8077 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 14:21:23.021  8077  8077 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 14:21:23.021  8077  8077 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 14:21:23.034  8077  8077 V [BNRBootReceiver]: Boot Receiver Return
,08-29 14:21:23.037  8077  8077 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 14:21:23.126  1042  1891 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8101 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 14:21:23.130  1042  1891 I ActivityManager: Killing 7166:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 14:21:23.165  1042  1058 W libprocessgroup: failed to open /acct/uid_10085/pid_7166/cgroup.procs: No such file or directory
,08-29 14:21:23.200  8101  8101 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 14:21:23.224  8101  8101 D PluginManager: init()
,08-29 14:21:23.269  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 14:21:23.269  1042  8058 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 14:21:23.269  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 14:21:23.269  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: WPS-AP-AVAILABLE 
08-29 14:21:23.269  1042  8058 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-29 14:21:23.270  8024  8024 E wpa_supplicant: USIM:  scard_init function
08-29 14:21:23.271  8024  8024 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 14:21:23.272  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 14:21:23.272  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 14:21:23.274  1042  1526 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 14:21:23.275  1042  1526 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 14:21:23.276  1042  1526 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 14:21:23.276  1042  1526 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 14:21:23.276  1042  1526 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 14:21:23.293  1042  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=138195  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 14:21:23.294  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=138196  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 14:21:23.298  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.298  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:23.299  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.299  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.299  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 14:21:23.299  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:23.299  1042  1042 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 14:21:23.301  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.396  8024  8024 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 14:21:23.401  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-29 14:21:23.401  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 14:21:23.401  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,08-29 14:21:23.402  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 14:21:23.402  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:23.402  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 14:21:23.405  8024  8024 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 14:21:23.405  8024  8024 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 14:21:23.407  1042  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=138309  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-29 14:21:23.408  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:23.408  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:23.408  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-29 14:21:23.408  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 14:21:23.408  1042  8058 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 14:21:23.408  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-29 14:21:23.408  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 14:21:23.409  1042  8058 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 14:21:23.409  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-29 14:21:23.409  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:23.410  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=138312  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 14:21:23.410  1042  1526 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138312
,08-29 14:21:23.411  1042  1526 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138313
08-29 14:21:23.411  1042  1526 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138313
,08-29 14:21:23.411  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138313
08-29 14:21:23.412  1042  1526 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 52 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138314
08-29 14:21:23.414  1042  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=138314  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-29 14:21:23.424  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.424  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.424  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 14:21:23.425  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.425  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:23.426  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.428  1042  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 14:21:23.428  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=138330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 14:21:23.429  1042  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=138331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 14:21:23.431  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.431  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.431  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-29 14:21:23.435  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=138337  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 14:21:23.436  1042  1526 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138338
08-29 14:21:23.436  1042  1526 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138338
08-29 14:21:23.437  1042  1526 D WifiNative-wlan0: doString: [STATUS]
08-29 14:21:23.437  1042  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 14:21:23.437  1042  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 14:21:23.438  1042  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 14:21:23.440  1042  1526 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 14:21:23.446  1042  1526 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 14:21:23.446  1042  1526 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-29 14:21:23.451  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.451  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.451  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 14:21:23.458  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.458  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:23.459  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.459  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.459  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 14:21:23.460  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 14:21:23.464  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.464  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:23.465  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.469  1042  1526 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 14:21:23.469  1042  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:23.469  1042  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 14:21:23.470  1042  1532 D ConnectivityService: Got NetworkAgent Messenger
08-29 14:21:23.470  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 14:21:23.470  1042  1532 D ConnectivityService: NetworkAgent connected
08-29 14:21:23.470  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.470  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:23.470  1042  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 14:21:23.470  1042  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 14:21:23.472  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.482  1042  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 14:21:23.482  1042  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:23.482  1042  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 14:21:23.483  1042  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 14:21:23.483  1042  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 14:21:23.487  1042  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 14:21:23.489   315   911 D CommandListener: Setting iface cfg
08-29 14:21:23.494  1042  1526 E WifiStateMachine: Start Dhcp Watchdog 3
08-29 14:21:23.495  1042  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:23.495  1042  8129 D DhcpStateMachine: StoppedState
08-29 14:21:23.495  1042  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138397  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:23.495  1042  8129 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.495  1042  8129 D DhcpStateMachine: WaitBeforeStartState
08-29 14:21:23.495  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138397  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:23.496  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:23.497  1042  1042 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 14:21:23.499  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:23.499  1042  1042 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-29 14:21:23.500  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:23.500  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:23.501  1042  1526 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:23.501  1042  1526 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:23.501  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:23.502  1042  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 14:21:23.503  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:23.503  1042  1042 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 14:21:23.504  1042  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138406  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:23.504  1042  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138406  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:23.505  1042  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138407  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 14:21:23.506  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13944] from screen [on:0 period:-700499022] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 14:21:23.507  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-700499021] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 14:21:23.507  1042  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 14:21:23.510  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.512  1042  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-29 14:21:23.512  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.513  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.513  1042  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.513  1042  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.514  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.514  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.515  1042  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 14:21:23.515  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=138,0,0
08-29 14:21:23.515  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=138,0,0
08-29 14:21:23.515  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 14:21:23.516  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 14:21:23.516  1042  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 14:21:23.516  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 14:21:23.517  1042  1526 D WifiNative-wlan0: SET ps 0: returned true
08-29 14:21:23.517  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 14:21:23.517  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 14:21:23.517  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 14:21:23.517  1042  1526 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 14:21:23.517  1042  1526 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 14:21:23.517  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5b1751 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.517  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5b1751 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.517  1042  1526 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 14:21:23.517  1042  8129 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.517  1042  8129 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-29 14:21:23.518   315   911 D CommandListener: Setting iface cfg
08-29 14:21:23.518   315   911 D CommandListener: Trying to bring up wlan0
08-29 14:21:23.519  1042  1526 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 14:21:23.520  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:23.520  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 14:21:23.521  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 14:21:23.522  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 14:21:23.522  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.523  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.523  1042  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.524  1042  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.524  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.524  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 14:21:23.525  1042  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-29 14:21:23.526  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 14:21:23.526  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 14:21:23.526  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 14:21:23.526  1042  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.526  1042  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.526  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 14:21:23.527  1042  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 14:21:23.527  1042  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 14:21:23.527  8024  8024 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 14:21:23.528  1042  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 14:21:23.528  1042  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 14:21:23.543  1042  1526 D WifiNative-wlan0: SET ps 1: returned true
,08-29 14:21:23.545  1042  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 14:21:23.545  1042  1526 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 14:21:23.546  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 14:21:23.546  1042  1526 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 14:21:23.546  1042  1532 D ConnectivityService: ignoring duplicate network state non-change
08-29 14:21:23.552  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.552  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:23.553  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.554  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.554  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.554  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 14:21:23.556  1042  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 14:21:23.557  1042  1532 D ConnectivityService: Adding iface wlan0 to network 102
08-29 14:21:23.563  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.563  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.563  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 14:21:23.565  1042  1526 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 14:21:23.567  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 14:21:23.573  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 14:21:23.577  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.577  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 14:21:23.579  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.580  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.580  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.580  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 14:21:23.582  1042  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 14:21:23.582  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.582  1042  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 14:21:23.582  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 14:21:23.582  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.583  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 14:21:23.583  1042  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 14:21:23.584   315   911 E Netd    : netlink response contains error (File exists)
08-29 14:21:23.585  1042  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 14:21:23.586  1042  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 14:21:23.586  1042  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-29 14:21:23.586  1042  1532 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-29 14:21:23.589  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.589  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:23.589  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 14:21:23.589  1042  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 14:21:23.589  1042  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 14:21:23.589  1042  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 14:21:23.589  1042  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 14:21:23.590  1042  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:23.590  1042  8118 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.590  1042  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:23.590  1042  8118 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 14:21:23.590  1042  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 14:21:23.590  1042  8118 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:23.590  1042  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.590  1042  8118 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 14:21:23.590  1042  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 14:21:23.590  1042  1532 D ConnectivityService: currentScore = 0, newScore = 20
08-29 14:21:23.590  1042  1532 D ConnectivityService:    accepting network in place of null
08-29 14:21:23.590  1042  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.590  1042  1526 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.591  1042  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:23.591  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.591   315  8134 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 14:21:23.592  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&I,MS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 14:21:23.595  1042  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 14:21:23.595  1042  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 14:21:23.595  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 14:21:23.598  1042  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:23.599  1042  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 14:21:23.599  1042  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 14:21:23.602  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:23.602  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 14:21:23.602  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.604  1042  1042 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 14:21:23.604  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 14:21:23.604  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 14:21:23.604  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 14:21:23.606  1042  1532 D ConnectivityService: validation of new default Network = false
08-29 14:21:23.607  1042  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 14:21:23.607  1042  1532 D DSQN    : enableDataServiceNotify 
08-29 14:21:23.607  1042  1532 D DSQN    : start dsqn bin
,08-29 14:21:23.611  1042  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 14:21:23.611  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.611  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:23.612  1042  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:23.598  8135  8135 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:23.598  8135  8135 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:23.612  1590  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 14:21:23.620  1042  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-29 14:21:23.624  8135  8135 E DSQN    : DSQN ssw
,08-29 14:21:23.633  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 14:21:23.634  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.635  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.635   315  8134 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 14:21:23.669   315  8134 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 14:21:23.697   315   910 D LGDataListener: argv[0]=dsqncommand
08-29 14:21:23.697   315   910 D LGDataListener: argv[1]=wlan0
08-29 14:21:23.697   315   910 D LGDataListener: argv[2]=1
08-29 14:21:23.697   315   910 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-29 14:21:23.698  1042  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 14:21:23.698  1042  1116 D DSQN    : start to monitor internet connection
08-29 14:21:23.719  1042  8129 D DhcpStateMachine: DHCPV4 request on wlan0
,08-29 14:21:23.720  1042  8129 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 14:21:23.720  1042  8129 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 14:21:23.718  8141  8141 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:23.718  8141  8141 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 14:21:23.726  1042  8118 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 12:21:23 GMT], X-Android-Received-Millis=[1472473283726], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472473283696]}
08-29 14:21:23.726  1042  8118 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 14:21:23.726  1042  8118 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 14:21:23.727  1042  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-29 14:21:23.727  1042  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 14:21:23.727  1042  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:23.727  1042  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:23.727  1042  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 14:21:23.728  1042  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-29 14:21:23.728  1042  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 14:21:23.728  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.728  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:23.729  1042  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:23.730  1042  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.731  1590  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 14:21:23.734  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.735  1042  1526 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:23.735  1042  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:23.735  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 14:21:23.736  1042  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 14:21:23.745  6640  6748 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
08-29 14:21:23.745  6640  6748 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
,08-29 14:21:23.749  6640  6748 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
08-29 14:21:23.751  6640  6748 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 14:21:23.751  6640  6748 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
08-29 14:21:23.754  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.754  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31937702 added. We now have 2 listener(s)
08-29 14:21:23.755  1042  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.755  8141  8141 I dhcpcd  : version 5.5.6 starting
08-29 14:21:23.758  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.758  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.758  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:23.759  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.759  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17987813 added. We now have 9 listener(s)
08-29 14:21:23.759  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:23.759  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:21:23.760  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 14:21:23.760  8141  8141 E dhcpcd  : get_duid: m
08-29 14:21:23.760  8141  8141 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 14:21:23.760  8141  8141 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 14:21:23.761  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:23.767  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:23.767  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.768  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.768  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:23.769  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.769  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba6c449 added. We now have 3 listener(s)
08-29 14:21:23.769  1042  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.772  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.772  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.772  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:23.772  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.772  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f46014e added. We now have 10 listener(s)
08-29 14:21:23.772  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 14:21:23.772  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.773  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:23.776  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.776  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:23.776  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:23.776  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:23.777  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.777  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.777  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:23.777  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.777  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31937702 removed from the list
08-29 14:21:23.777  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.777  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17987813 removed from the list
08-29 14:21:23.777  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:23.777  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.777  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.777  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.778  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.778  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.778  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.778  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17987813 not in the list
08-29 14:21:23.778  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.778  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.779  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.779  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.779  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.779  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f46014e removed from the list
08-29 14:21:23.779  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.779  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.779  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.779  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothConnector: shutdown: Shutting down...
08-29 14:21:23.779  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba6c449 removed from the list
08-29 14:21:23.780  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.780  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@588826f added. We now have 2 listener(s)
08-29 14:21:23.781  1042  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.784  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.784  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.784  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:23.784  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.784  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b78b7c added. We now have 9 listener(s)
08-29 14:21:23.784  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.786  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:23.789  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:23.793  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:23.794  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.794  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:23.795  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.795  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e45a added. We now have 3 listener(s)
08-29 14:21:23.796  1042  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.797  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.799  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:23.800  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.800  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.800  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:23.800  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.801  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc4d68b added. We now have 10 listener(s)
08-29 14:21:23.801  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.801  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:23.801  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:23.801  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 14:21:23.801  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:23.801  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:23.804  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 14:21:23.805  1042  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.809  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 14:21:23.811  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:21:23.812  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:23.813  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:23.814  6640  6748 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 14:21:23.815  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:23.815  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:23.817  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:23.817  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:23.817  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:23.817  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.817  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.817  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:23.817  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.817  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@588826f removed from the list
08-29 14:21:23.817  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.817  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b78b7c removed from the list
08-29 14:21:23.817  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:23.817  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.818  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.818  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.818  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.818  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.818  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.818  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b78b7c not in the list
08-29 14:21:23.818  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.818  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.819  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.820  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:23.820  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:23.820  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.820  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.820  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManag,erSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc4d68b removed from the list
08-29 14:21:23.820  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.820  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.820  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.820  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.820  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e45a removed from the list
08-29 14:21:23.820  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.821  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@129cec26 added. We now have 2 listener(s)
08-29 14:21:23.821  1042  1709 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.823  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.823  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.823  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:23.823  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.823  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8285067 added. We now have 9 listener(s)
08-29 14:21:23.823  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.824  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:21:23.825  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:23.828  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:23.830  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.830  8141  8141 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 14:21:23.830  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:23.830  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.830  8141  8141 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 14:21:23.830  8141  8141 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 14:21:23.830  8141  8141 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 14:21:23.830  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf106bd added. We now have 3 listener(s)
08-29 14:21:23.830  8141  8141 D dhcpcd  : wlan0: sending REQUEST (xid 0x16bfd710), next in 4.01 seconds
08-29 14:21:23.830  1042  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.831  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.833  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.833  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.833  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.834  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:23.834  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.834  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dba4b2 added. We now have 10 listener(s)
08-29 14:21:23.834  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.834  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:23.834  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:23.834  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOpera,tion: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:23.834  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:23.834  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:23.834  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:23.836  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 14:21:23.836  1042  1709 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.839  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:23.840  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:21:23.841  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:23.841  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:23.842  6640  6748 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 14:21:23.843  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:23.843  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:23.843  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:23.843  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.843  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.843  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:23.843  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.843  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@129cec26 removed from the list
08-29 14:21:23.843  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.843  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8285067 removed from the list
08-29 14:21:23.843  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:23.843  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.843  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.843  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.844  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.844  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.844  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.844  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8285067 not in the list
08-29 14:21:23.844  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.844  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.845  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.845  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:23.845  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:23.845  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.845  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.845  6640 , 6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dba4b2 removed from the list
08-29 14:21:23.845  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.845  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.845  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.845  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.845  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf106bd removed from the list
08-29 14:21:23.846  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.846  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222c51b9 added. We now have 2 listener(s)
08-29 14:21:23.846  1042  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.848  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.848  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.848  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:23.848  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.848  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdb59fe added. We now have 9 listener(s)
08-29 14:21:23.848  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.848  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:21:23.849  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:23.851  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:23.853  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.853  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:23.853  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.853  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b2cbac added. We now have 3 listener(s)
08-29 14:21:23.853  1042  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.854  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.856  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.857  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.857  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.857  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:23.857  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.857  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375075 added. We now have 10 listener(s)
08-29 14:21:23.858  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.858  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:23.858  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:23.858  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:23.858  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:23.858  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:23.859  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 14:21:23.860  1042  1798 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.862  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 14:21:23.862  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:21:23.863  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:23.864  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:23.865  6640  6748 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-29 14:21:23.866  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:23.866  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:23.866  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:23.866  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.866  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.866  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:23.866  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.866  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222c51b9 removed from the list
08-29 14:21:23.866  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.867  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdb59fe removed from the list
,08-29 14:21:23.867  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:23.867  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.867  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.867  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:23.868  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.868  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.868  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:23.868  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdb59fe not in the list
08-29 14:21:23.868  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.868  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.868  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-29 14:21:23.869  6640  6748 D BluetoothLeScanner: could not find callback wrapper
08-29 14:21:23.869  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:23.869  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.869  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:23.869  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375075 removed from the list
08-29 14:21:23.869  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.869  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.869  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:23.869  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.869  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b2cbac removed from the list
08-29 14:21:23.870  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.870  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3656f698 added. We now have 2 listener(s)
,08-29 14:21:23.870  1042  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.871  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.871  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.871  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:23.871  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.872  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b97ef1 added. We now have 9 listener(s)
08-29 14:21:23.872  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.873  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:23.874  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:23.877  8141  8141 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:23.877  6640  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:23.878  6640  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:23.879  6640  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:23.880  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.881  6640  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:23.881  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:23.881  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d02157 added. We now have 3 listener(s)
,08-29 14:21:23.881  1042  1798 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 14:21:23.883  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 14:21:23.883  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:23.883  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:23.883  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:23.883  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e10e444 added. We now have 10 listener(s)
08-29 14:21:23.883  6640  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:23.883  6640  6748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:23.883  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:23.883  6640  6748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:23.884  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.884  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:23.884  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:23.884  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.884  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3656f698 removed from the list
08-29 14:21:23.884  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.884  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b97ef1 removed from the list
08-29 14:21:23.884  6640  6748 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:23.884  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.884  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.884  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.885  6640  6748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b97ef1 not in the list
08-29 14:21:23.885  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.885  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:23.885  6640  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e10e444 removed from the list
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:23.885  6640  6748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:23.885  6640  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:23.885  6640  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:23.885  6640  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d02157 removed from the list
08-29 14:21:23.886  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 14:21:23.886  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 14:21:23.886  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 14:21:23.886  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: ,false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:23.886  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 14:21:23.886  6640  6748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:23.894  6640  8149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
08-29 14:21:23.894  6640  8149 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: My test thread name)
08-29 14:21:23.894  8101  8101 W ExternalStrings: load override strings
08-29 14:21:23.894  8101  8101 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source),
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609),
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135),
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 14:21:23.894  8101  8101 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 14:21:23.894  6640  8149 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 14:21:23.896  8101  8101 D StatusProvider: onCreate
08-29 14:21:23.898  6640  8150 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
08-29 14:21:23.898  6640  8150 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: My test thread name)
,08-29 14:21:23.899  6640  8150 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 14:21:23.900  6640  6748 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 14:21:23.900  6640  6748 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 14:21:23.900  6640  6748 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 14:21:23.900  6640  6748 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 14:21:23.900  6640  6748 D com.test.thalitest.ThaliTestRunner: Total duration: 22731 ms
08-29 14:21:23.901  6640  6748 I jxcore-log: *Native tests were executed*
08-29 14:21:23.901  6640  6748 I jxcore-log: 
,08-29 14:21:23.901  6640  6748 I jxcore-log: Total number of executed tests:  80
08-29 14:21:23.901  6640  6748 I jxcore-log: 
08-29 14:21:23.902  6640  6748 I jxcore-log: Number of passed tests:  80
08-29 14:21:23.902  6640  6748 I jxcore-log: 
08-29 14:21:23.902  6640  6748 I jxcore-log: Number of failed tests:  0
,08-29 14:21:23.902  6640  6748 I jxcore-log: 
08-29 14:21:23.902  6640  6748 I jxcore-log: Number of ignored tests:  0
08-29 14:21:23.902  6640  6748 I jxcore-log: 
,08-29 14:21:23.902  6640  6748 I jxcore-log: Total duration:  22731
,08-29 14:21:23.902  6640  6748 I jxcore-log: 
08-29 14:21:23.902  6640  6748 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 14:21:23.902  6640  6748 I jxcore-log: 
08-29 14:21:23.905  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.905  6640  6748 I jxcore-log: 
,08-29 14:21:23.907  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.907  6640  6748 I jxcore-log: 
08-29 14:21:23.908  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.908  6640  6748 I jxcore-log: 
08-29 14:21:23.909  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.909  6640  6748 I jxcore-log: 
08-29 14:21:23.909  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.909  6640  6748 I jxcore-log: 
08-29 14:21:23.910  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.910  6640  6748 I jxcore-log: 
08-29 14:21:23.912  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:23.912  6640  6748 I jxcore-log: 
08-29 14:21:23.913  6640  6640 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 14:21:23.914  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.914  6640  6748 I jxcore-log: 
08-29 14:21:23.915  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.915  6640  6748 I jxcore-log: 
08-29 14:21:23.915  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.915  6640  6748 I jxcore-log: 
08-29 14:21:23.916  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:23.916  6640  6748 I jxcore-log: 
08-29 14:21:23.917  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:23.917  6640  6748 I jxcore-log: 
08-29 14:21:23.917  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:23.917  6640  6748 I jxcore-log: 
08-29 14:21:23.918  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.918  6640  6748 I jxcore-log: 
08-29 14:21:23.918  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.918  6640  6748 I jxcore-log: 
08-29 14:21:23.919  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.919  6640  6748 I jxcore-log: 
08-29 14:21:23.919  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.919  6640  6748 I jxcore-log: 
08-29 14:21:23.920  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.920  6640  6748 I jxcore-log: 
08-29 14:21:23.920  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.920  6640  6748 I jxcore-log: 
08-29 14:21:23.920  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.920  6640  6748 I jxcore-log: 
08-29 14:21:23.921  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:23.921  6640  6748 I jxcore-log: 
08-29 14:21:23.921  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:23.921  6640  6748 I jxcore-log: 
08-29 14:21:23.922  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:23.922  6640  6748 I jxcore-log: 
08-29 14:21:23.922  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.922  6640  6748 I jxcore-log: 
08-29 14:21:23.923  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.923  6640  6748 I jxcore-log: 
08-29 14:21:23.923  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.923  6640  6748 I jxcore-log: 
08-29 14:21:23.924  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.924  6640  6748 I jxcore-log: 
08-29 14:21:23.924  6640  6748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:23.924  6640  6748 I jxcore-log: 
08-29 14:21:23.926  8141  8141 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 14:21:23.926  8141  8141 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 14:21:23.927  8141  8141 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 14:21:23.927  8141  8141 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 14:21:23.927  8141  8141 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 14:21:23.928  8141  8141 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 14:21:23.928  8141  8141 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 14:21:23.928  8141  8141 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-29 14:21:23.963  8101  8101 V Signer  : override build config not found
08-29 14:21:23.964  8101  8101 D Signer  : value of property debug is false
,08-29 14:21:23.998  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-29 14:21:23.999  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-29 14:21:23.999  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-29 14:21:23.999  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-29 14:21:23.999  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-29 14:21:23.999  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-29 14:21:23.999  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-29 14:21:24.000  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-29 14:21:24.000  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-29 14:21:24.000  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-29 14:21:24.000  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-29 14:21:24.000  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-29 14:21:24.001  8101  8101 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-29 14:21:24.010  8101  8101 V LGMDMManager: Create singleton instance
08-29 14:21:24.053  8101  8101 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-29 14:21:24.101  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:24.102  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 14:21:24.109  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:24.113  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:24.123  1042  8129 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 14:21:24.124  1042  8129 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 14:21:24.124  1042  8129 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 14:21:24.124  1042  8129 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 14:21:24.124  1042  8129 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 14:21:24.124  1042  8129 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 14:21:24.124  1042  8129 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 14:21:24.124  1042  8129 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 14:21:24.124  1042  8129 D DhcpStateMachine: RunningState
08-29 14:21:24.157  1042  1058 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8178 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-29 14:21:24.158  1042  1058 I ActivityManager: Killing 7194:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-29 14:21:24.215  8101  8170 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 14:21:24.228  8158  8158 D AndroidRuntime: 
08-29 14:21:24.228  8158  8158 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 14:21:24.231  8158  8158 D AndroidRuntime: CheckJNI is OFF
08-29 14:21:24.343  8158  8158 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 14:21:24.394  1042  1947 W libprocessgroup: failed to open /acct/uid_10093/pid_7194/cgroup.procs: No such file or directory
,08-29 14:21:24.466  1042  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-29 14:21:24.466  1042  1114 I ActivityManager: Killing 6640:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-29 14:21:24.496  8178  8178 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 14:21:24.517  1042  1891 I WindowState: WIN DEATH: Window{2e11e9b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 14:21:24.518  1042  1531 D WifiService: Client connection lost with reason: 4
08-29 14:21:24.525  1042  1891 D InputDispatcher: Window went away: Window{2e11e9b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 14:21:24.657  1042  1526 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 14:21:24.658  1042  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 14:21:24.660  1042  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 14:21:24.661  1042  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 14:21:24.664  1042  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 14:21:24.666  1042  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 14:21:24.668  1042  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-29 14:21:24.670  1042  1532 D ConnectivityService: identical MTU - not setting
08-29 14:21:24.672  1042  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 14:21:24.673  1042  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 14:21:24.673  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:21:24.674  1042  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 14:21:24.675  1042  1532 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 14:21:24.678  1590  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 14:21:24.690  1042  1114 I ActivityManager:   Force finishing activity ActivityRecord{3156ce35 u0 com.test.thalitest/.MainActivity t6}
,08-29 14:21:24.728   338   356 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 14:21:24.731  1042  1148 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 14:21:24.735  1042  1148 I ActivityManager:   Force finishing activity ActivityRecord{3156ce35 u0 com.test.thalitest/.MainActivity t6 f}
08-29 14:21:24.735  1042  1148 W ActivityManager: Duplicate finish request for ActivityRecord{3156ce35 u0 com.test.thalitest/.MainActivity t6 f}
,08-29 14:21:24.768  1042  1798 W ActivityManager: Spurious death for ProcessRecord{1b729231 6640:com.test.thalitest/u0a118}, curProc for 6640: null
08-29 14:21:24.771  2021  2021 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 14:21:24.773  2021  2021 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-29 14:21:24.778  1929  2916 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 14:21:24.778  1929  2916 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5a55040 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 14:21:24.779  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 14:21:24.780  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1756db79 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 14:21:24.785  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-29 14:21:24.798  4582  4582 I art     : Explicit concurrent mark sweep GC freed 8250(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 587us total 52.207ms
08-29 14:21:24.798  1984  1984 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-29 14:21:24.801  2457  2576 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 14:21:24.804  7674  7674 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 14:21:24.804  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 14:21:24.805  3778  3778 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 14:21:24.825  8178  8178 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 14:21:24.837  1042  1455 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 14:21:24.842  1042  1983 V SIM_STK : Menu title from STK is T-Mobile
,08-29 14:21:24.886  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 14:21:24.886  2021  2127 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,08-29 14:21:24.891  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-29 14:21:24.893  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 14:21:24.893  1590  1642 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 14:21:24.893  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:24.894  1893  1893 D ActionManagerService: notifyUserLog: 1000003
08-29 14:21:24.894  2021  2021 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 14:21:24.894  3778  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-29 14:21:24.895  2021  2021 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 14:21:24.896  4479  4479 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 14:21:24.896  4479  4479 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 14:21:24.896  4479  4479 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 14:21:24.896  4479  4479 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 14:21:24.896  4479  4479 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:21:24.896  4479  4479 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 14:21:24.896  4479  4479 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 14:21:24.896  4479  4479 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 14:21:24.896  4479  4479 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:24.896  4479  4479 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:24.896  4479  4479 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 14:21:24.896  4479  4479 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 14:21:24.897  2021  2021 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 14:21:24.901  1893  1893 D ActionManagerService: notifyUserLog: 1000004
,08-29 14:21:24.902  3778  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 14:21:24.902  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 14:21:24.905  3778  3793 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 14:21:24.906  1590  1642 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 14:21:24.906  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , display: false
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , animation: false }
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , display: false
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , animation: false }
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , display: false
08-29 14:21:24.918  2021  2021 I GBoardWebViewUtils: , animation: false }
,08-29 14:21:24.920  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 14:21:24.921  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 14:21:24.922  8178  8178 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 14:21:24.922  8178  8178 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 14:21:24.923  8178  8178 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 14:21:24.923  8178  8178 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 14:21:24.923  8178  8178 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 14:21:24.924  2021  8222 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 14:21:24.930  1590  1642 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 14:21:24.931  1590  1642 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:24.931  1590  1642 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 14:21:24.932  1590  1642 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 14:21:24.938  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-29 14:21:24.938  1856  1856 D SplitUIService: removed split : 
,08-29 14:21:24.939  8178  8178 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 14:21:24.944  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 14:21:24.944  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-29 14:21:24.946  1590  1642 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 14:21:24.946  1590  1642 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 14:21:24.948  1590  1642 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 14:21:24.948  1590  1642 D KeyguardModel: createShortcutInfo...
,08-29 14:21:24.956  1590  1642 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 14:21:24.956  1590  1642 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 14:21:24.963  1042  1974 V SIM_STK : Menu title from STK is T-Mobile
08-29 14:21:24.963  1042  1974 V SIM_STK : Menu title from STK is T-Mobile
08-29 14:21:24.963  1590  1642 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 14:21:24.963  1590  1642 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 14:21:24.968  1590  1642 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 14:21:24.968  1590  1642 D KeyguardModel: createShortcutInfo...
,08-29 14:21:24.973  1042  1042 D administrator: Handling package changes for user 0
08-29 14:21:24.975  8178  8178 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 14:21:24.980  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-29 14:21:24.980  1856  1856 I SplitUIService: split app #11
08-29 14:21:24.988  1590  1642 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:24.988  1590  1642 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 14:21:24.988  1590  1642 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 14:21:24.988  1590  1642 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 14:21:24.988  1590  1642 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 14:21:24.988  1590  1642 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 14:21:24.991  1590  1642 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 14:21:24.991  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:24.993  1042  1892 V SIM_STK : Menu title from STK is T-Mobile
08-29 14:21:24.995  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:24.997  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:25.006  8178  8178 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 14:21:25.008  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.008  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 14:21:25.011  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-29 14:21:25.011  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 14:21:25.015  8101  8170 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:25.015  8101  8170 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 14:21:25.015  1042  1891 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 14:21:25.016  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 14:21:25.018  7674  7674 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 14:21:25.019  1590  1642 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 14:21:25.019  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:25.022  8178  8178 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 14:21:25.025  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 14:21:25.033  1590  1642 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 14:21:25.033  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:25.035  1590  1642 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 14:21:25.035  1590  1642 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 14:21:25.036  8178  8178 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 14:21:25.036  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.037  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.037  1590  1642 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 14:21:25.037  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:25.038  1590  1642 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 14:21:25.038  1590  1642 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 14:21:25.039  1590  1642 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 14:21:25.039  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:25.040  1590  1642 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 14:21:25.040  1590  1642 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 14:21:25.041  1590  1642 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 14:21:25.041  1590  1642 D KeyguardModel: createShortcutInfo...
08-29 14:21:25.052  8178  8178 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 14:21:25.054  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 14:21:25.060  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-29 14:21:25.060  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 14:21:25.061  6843  6843 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-29 14:21:25.065  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.073  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 14:21:25.074  1042  1042 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-29 14:21:25.074  1042  1042 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 14:21:25.075  1042  1042 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 14:21:25.076  1042  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-29 14:21:25.099   332   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 14:21:25.099  3204  8228 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 14:21:25.104  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:25.119  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-29 14:21:25.122  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 14:21:25.123  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 14:21:25.124  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 14:21:25.125  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 14:21:25.126  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-29 14:21:25.143  2021  2021 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-29 14:21:25.144  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 14:21:25.144  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 14:21:25.147  2021  2256 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 14:21:25.147  2021  2256 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-29 14:21:25.147  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.147  8101  8170 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-29 14:21:25.153  1042  1148 I art     : Explicit concurrent mark sweep GC freed 79950(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 4.208ms total 379.705ms
08-29 14:21:25.159  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-29 14:21:25.160  1042  1113 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 14:21:25.161  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 14:21:25.161  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 14:21:25.164  1042  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2eab842b u0 com.lge.launcher2/.Launcher t5} time:140081
08-29 14:21:25.164  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.164  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.165  8178  8178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:25.167  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.167  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 14:21:25.172  2021  2021 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-29 14:21:25.174  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:25.176  2021  2021 D [Concierge]WidgetView: change position of spinner
08-29 14:21:25.176  8101  8170 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-29 14:21:25.177  2021  2021 I [Concierge]WidgetView: initWebView(). Time : 1472473285177
08-29 14:21:25.177  2599  2599 D [Concierge]Service: onStartCommand(). Type : 8
08-29 14:21:25.177  2599  2599 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-29 14:21:25.178  2599  2599 D [Concierge]Service: Update widget ID : 11
08-29 14:21:25.178  2599  2599 D [Concierge]Service: onStartCommand(). Type : 0
08-29 14:21:25.182  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.185  8101  8170 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-29 14:21:25.185  8101  8170 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 14:21:25.186  8101  8170 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-29 14:21:25.187  8101  8170 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-29 14:21:25.187  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.187  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.187  8178  8178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:25.189  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 14:21:25.190  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.192  8101  8170 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-29 14:21:25.193  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:25.196  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.197  2021  2021 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 813248728
08-29 14:21:25.197  2021  2021 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 14:21:25.197  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 14:21:25.199  8101  8170 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-29 14:21:25.200  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.200  2021  2021 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@37287a58
08-29 14:21:25.200  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.200  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 14:21:25.200  8178  8178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:25.201  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 14:21:25.201  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 14:21:25.202  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:25.202  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 14:21:25.202  6843  6843 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 14:21:25.203  6843  6843 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 14:21:25.204  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 14:21:25.204  8101  8170 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-29 14:21:25.206  6843  6843 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 14:21:25.206  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 14:21:25.206  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 14:21:25.206  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 14:21:25.206  6843  6843 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 14:21:25.206  6843  6843 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 14:21:25.206  6843  6843 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 14:21:25.206  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 14:21:25.207  2021  2021 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 14:21:25.207  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 14:21:25.208  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.208  2021  2021 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472473172633, New one : 1472473285177
08-29 14:21:25.208  2021  2021 D [Concierge]WidgetView: Unregister all receivers
08-29 14:21:25.208  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 14:21:25.209  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 14:21:25.210  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 14:21:25.211  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 14:21:25.212  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:25.213  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-29 14:21:25.214  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 14:21:25.215  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 14:21:25.216  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 14:21:25.218  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 14:21:25.218  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 14:21:25.222  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.227  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.227  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.227  8178  8178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 14:21:25.234  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.235  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 14:21:25.238  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:25.241  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.244  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.244  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.244  8178  8178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:25.249  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 14:21:25.250  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.258  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 14:21:25.265  2021  2021 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 14:21:25.265  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 14:21:25.267  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 14:21:25.277  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:25.280  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.286  2021  2021 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2876e39d time:140203
08-29 14:21:25.289  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.289  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:25.294  8178  8178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:25.295  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.297  8101  8172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 14:21:25.302  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 14:21:25.306  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.307  8158  8158 D AndroidRuntime: Shutting down VM
08-29 14:21:25.337  1042  1148 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8237 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 14:21:25.340  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.340  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.341  8178  8178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 14:21:25.342  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.361  8049  8049 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 14:21:25.364  8049  8049 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:25.367  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:25.370  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.380  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.380  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.380  8178  8178 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 14:21:25.381  8178  8178 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 14:21:25.381  8178  8178 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 14:21:25.392  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 14:21:25.394  8049  8049 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 14:21:25.395  8049  8049 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 14:21:25.397  6843  6843 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 14:21:25.400  6843  6843 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 14:21:25.402  1042  1709 I ActivityManager: Killing 7247:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-29 14:21:25.414  1042  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 14:21:25.419  1042  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 14:21:25.426  2021  2021 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 14:21:25.460  2021  2878 I GBoardtInterface: onReloaded()
,08-29 14:21:25.462  2021  2021 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 14:21:25.464  1042  1938 W libprocessgroup: failed to open /acct/uid_10005/pid_7247/cgroup.procs: No such file or directory
08-29 14:21:25.464  8178  8178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 14:21:25.464  8178  8178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 14:21:25.465  8178  8178 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 14:21:25.465  8178  8178 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 14:21:25.465  8178  8178 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 14:21:25.466  3778  3793 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 14:21:25.467  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 14:21:25.468  3778  3794 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 14:21:25.468  8101  8101 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 14:21:25.470  1804  1804 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-29 14:21:25.475  2195  2195 I ConfigService: onCreate
,08-29 14:21:25.475  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 14:21:25.477  1893  1893 D ActionManagerService: notifyUserLog: 1000001
08-29 14:21:25.478  3778  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 14:21:25.478  3778  4470 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 14:21:25.479  1804  1804 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 14:21:25.480  2195  2195 I ConfigService: onBind returning update interface
08-29 14:21:25.481  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 14:21:25.481  2195  2195 I ConfigService: onBind returning config service
08-29 14:21:25.481  1893  1893 D ActionManagerService: notifyUserLog: 1000001
08-29 14:21:25.482  3778  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 14:21:25.482  3778  4470 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 14:21:25.482  3778  4470 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 14:21:25.482  3778  4470 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 14:21:25.483  3778  3793 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 14:21:25.485  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 14:21:25.485  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 14:21:25.487  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,08-29 14:21:25.487  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 14:21:25.489  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 14:21:25.489  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 14:21:25.491  2195  2195 I ConfigService: onDestroy
08-29 14:21:25.491  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 14:21:25.496  1804  8257 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 14:21:25.534  1804  8264 I PeopleContactsSync: CP2 sync disabled
,08-29 14:21:25.537  1804  4765 I Icing   : doRemovePackageData com.test.thalitest
,08-29 14:21:25.538  5953  8263 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-29 14:21:25.557  1804  8262 W GmsApplication: Using Auth Proxy for data requests.
,08-29 14:21:25.561  1804  8262 W GmsApplication: Using Auth Proxy for data requests.
,08-29 14:21:25.586  7048  7048 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-29 14:21:25.604  2335  8268 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 14:21:25.606  2195  2213 I art     : Explicit concurrent mark sweep GC freed 7218(431KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.069ms total 19.881ms
08-29 14:21:25.614  1042  1983 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8269 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 14:21:25.655  8269  8269 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:25.656  8269  8269 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 14:21:25.656  8269  8269 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 14:21:25.657  8269  8269 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 14:21:25.700  8269  8269 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 14:21:25.709  8269  8269 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-29 14:21:25.737  8269  8269 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 14:21:25.744  2335  8268 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-29 14:21:25.745  2335  8268 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 14:21:25.745  2335  8268 E AndroidRuntime: Process: android.process.acore, PID: 2335
08-29 14:21:25.745  2335  8268 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-29 14:21:25.745  2335  8268 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 14:21:25.748  2335  8268 I Process : Sending signal. PID: 2335 SIG: 9
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: Can't write: system_app_crash
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 14:21:25.748  1042  8288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-2,9 14:21:25.748  1042  8288 E DropBoxManagerService: 	... 5 more
08-29 14:21:25.761  8269  8269 D LgDataFeature: LgDataFeature() Constructor: none
08-29 14:21:25.761  8269  8269 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 14:21:25.774  2021  2878 I GBoardtInterface: exportHTML()
,08-29 14:21:25.802  2021  2878 I GBoardtInterface: exportHTML()
,08-29 14:21:25.802  1042  1910 I ActivityManager: Process android.process.acore (pid 2335) has died
08-29 14:21:25.803  1042  1910 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
08-29 14:21:25.803  1042  1910 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
,08-29 14:21:25.825  2021  2878 I GBoardtInterface: exportHTML()
,08-29 14:21:25.833  8269  8269 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-29 14:21:25.838  7775  7775 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
,08-29 14:21:25.838  1042  1892 I ActivityManager: Killing 7587:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 14:21:25.890   338   358 E GBMv2   : DFP En is all cleared set to be enabled
08-29 14:21:25.890   338   358 E GBMv2   : Set value is all cleared set the max
08-29 14:21:25.890   338   358 I GBMv2   : DFP Enabled. Ignore VFP set

```
