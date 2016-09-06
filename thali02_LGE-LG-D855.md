#### Test 83444050adbb179_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-06 19:22:23.158  6598  6598 D DocsApplication: Installing DEX configuration.
09-06 19:22:23.181  6598  6598 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-06 19:22:23.185  6598  6598 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2b5477ab com.google.android.apps.docs}
09-06 19:22:23.202  6598  6598 D TAG     : onCreate()
09-06 19:22:23.230  6598  6598 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-06 19:22:23.935  1801  4754 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-06 19:22:23.981  1801  4754 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-06 19:22:24.064  1801  4754 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-06 19:22:24.331  6624  6624 D AndroidRuntime: 
09-06 19:22:24.331  6624  6624 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:22:24.334  6624  6624 D AndroidRuntime: CheckJNI is OFF
09-06 19:22:24.388  6598  6598 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:24.388  6598  6598 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:22:24.505  6154  6154 I LockScreenSettings: New app installed broadcast received ..
09-06 19:22:24.507  6154  6154 I LockScreenSettings: Number of installed packages  1
09-06 19:22:24.525  6624  6624 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 19:22:24.530  1029  1870 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:22:24.533  6598  6598 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-06 19:22:24.540  1925  1940 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-06 19:22:24.544  1029  1870 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-06 19:22:24.545  1029  1870 D ActivityManager: setTaskToReturnTo : TaskRecord{bdbcbf7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:22:24.545  1029  1870 D ActivityManager: setTaskToReturnTo : TaskRecord{bdbcbf7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:22:24.546  1029  1870 D WindowStateEx: AppWindowTokenEx init.. 
09-06 19:22:24.547   348   365 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:22:24.575  1029  1870 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6651 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:22:24.577  6624  6624 D AndroidRuntime: Shutting down VM
09-06 19:22:24.599  1029  1907 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:22:24.636  1029  1960 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6673 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:22:24.668  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-06 19:22:24.668  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f741e17 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:22:24.669  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-06 19:22:24.669  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32660204 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:22:24.707  6651  6651 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-06 19:22:24.710  6673  6673 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-06 19:22:24.710  6673  6673 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
09-06 19:22:24.750  1029  1720 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6696 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-06 19:22:24.751  1029  1720 I ActivityManager: Killing 5831:com.google.android.gm/u0a64 (adj 15): empty #17
09-06 19:22:24.764  6651  6651 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 19:22:24.801  1029  1960 W libprocessgroup: failed to open /acct/uid_10064/pid_5831/cgroup.procs: No such file or directory
,09-06 19:22:24.811  6651  6651 I LibraryLoader: Loading: webviewchromium
09-06 19:22:24.815  6651  6651 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3501-3505)
,09-06 19:22:24.815  6651  6651 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:22:24.832  6651  6651 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23e69edd}
,09-06 19:22:24.833  6651  6651 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:22:24.834  6651  6651 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:22:24.844  6651  6651 I BrowserStartupController: Initializing chromium process, renderers=0
09-06 19:22:24.845  6651  6651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:22:24.873  6651  6651 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-06 19:22:24.873  6651  6651 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-06 19:22:24.873  6651  6651 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-06 19:22:24.879   318   318 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10118
09-06 19:22:24.886  1029  1100 D BluetoothManagerService: Message: 20
09-06 19:22:24.886  1029  1100 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a7d70c9:true
,09-06 19:22:24.887  6651  6651 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:22:24.887  6651  6651 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:22:24.887  6651  6651 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:22:24.887  6651  6651 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:22:24.887  6651  6651 I Adreno-EGL: Remote Branch: 
09-06 19:22:24.887  6651  6651 I Adreno-EGL: Local Patches: 
09-06 19:22:24.887  6651  6651 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:22:24.902  6696  6696 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-06 19:22:24.923  6696  6696 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-06 19:22:24.927  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-06 19:22:24.960  1029  1871 I ActivityManager: Killing 5878:com.google.android.talk/u0a72 (adj 15): empty #17
,09-06 19:22:24.970  6651  6726 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-06 19:22:24.977  6651  6651 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-06 19:22:24.991  6651  6651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:22:24.996  6651  6651 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:22:25.000  6651  6651 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-06 19:22:25.004  6651  6651 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-06 19:22:25.004  6651  6651 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-06 19:22:25.015  6651  6651 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-06 19:22:25.021  1029  1961 W libprocessgroup: failed to open /acct/uid_10072/pid_5878/cgroup.procs: No such file or directory
,09-06 19:22:25.023  6651  6651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:22:25.023  6651  6651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:22:25.049  6651  6742 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:22:25.049  6651  6742 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:22:25.064  6651  6742 D OpenGLRenderer: Enabling debug mode 0
,09-06 19:22:25.084  6651  6651 D Atlas   : Validating map...
,09-06 19:22:25.090  1029  1560 D SplitWindow: check instance of lgWin Window{2c668d56 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 19:22:25.118  6651  6740 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:25.119  6651  6740 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:22:25.277  1029  1101 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +615ms (total +730ms)
09-06 19:22:25.278  1029  1101 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3cc54a64 u0 com.test.thalitest/.MainActivity t6} time:103968
,09-06 19:22:25.279  6651  6651 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1b46f750 time:103970
09-06 19:22:25.382  6651  6651 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:22:25.440  6651  6651 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-06 19:22:25.440  6651  6651 I chromium: 
,09-06 19:22:25.489  6651  6740 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-06 19:22:25.489  6651  6740 I chromium: 
,09-06 19:22:25.662  6651  6756 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,09-06 19:22:25.677  6651  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:22:25.677  6651  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:22:25.677  6651  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:22:25.677  6651  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:22:25.677  6651  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 19:22:25.677  6651  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35911b14 added. We now have 1 listener(s)
09-06 19:22:25.685  1029  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:25.688  6651  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-06 19:22:25.690  6651  6756 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-06 19:22:25.692  6651  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:22:25.692  6651  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:22:25.700  6651  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f42fd03 added. We now have 1 listener(s)
09-06 19:22:25.701  6651  6756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:22:25.706  1029  1528 D WifiService: New client listening to asynchronous messages
,09-06 19:22:25.714  6651  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:22:25.714  6651  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:22:25.717  6651  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:22:25.717  6651  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:22:25.717  6651  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 19:22:25.721  6651  6756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:22:25.722  1029  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:25.723  6651  6756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-06 19:22:25.732  6651  6756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:22:25.733  6651  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:25.733  6651  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:22:25.733  6651  6756 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:22:25.736  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:25.736  6651  6756 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:22:25.738  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:25.774  6651  6651 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:22:26.031   348   367 E GBMv2   : DFP En is all cleared set to be enabled
,09-06 19:22:26.031   348   367 E GBMv2   : Set value is all cleared set the max
,09-06 19:22:26.031   348   367 I GBMv2   : DFP Enabled. Ignore VFP set
09-06 19:22:26.849  6651  6759 W jxcore-log: Initializing JXcore engine
09-06 19:22:26.850  6651  6759 W jxcore-log: JXcore engine is ready
,09-06 19:22:26.910  6759  6759 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8927]" dev="sockfs" ino=8927 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 19:22:26.910  6759  6759 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-06 19:22:26.920  6759  6759 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7750]" dev="sockfs" ino=7750 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 19:22:26.920  6759  6759 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-06 19:22:26.920  6759  6759 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30900]" dev="sockfs" ino=30900 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-06 19:22:26.953  6651  6759 W jxcore-log: Starting JXcore engine
,09-06 19:22:27.117  6651  6759 W jxcore-log: Platform android
09-06 19:22:27.117  6651  6759 W jxcore-log: 
09-06 19:22:27.117  6651  6759 W jxcore-log: Process ARCH arm
09-06 19:22:27.117  6651  6759 W jxcore-log: 
,09-06 19:22:27.270  2778  2778 I MusicWidget: mDelayedStopHandler : unbind
,09-06 19:22:27.272  2109  2109 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-06 19:22:27.273  2109  2109 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-06 19:22:27.275  2109  2109 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-06 19:22:27.276  2109  2109 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-06 19:22:27.277  2109  2109 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-06 19:22:27.277  2109  2109 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-06 19:22:27.290  2109  2109 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-06 19:22:27.291  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,09-06 19:22:27.292  1029  1961 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3d4da913com.lge.music.MediaPlaybackService$5@1b46f750
09-06 19:22:27.300  2109  2109 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-06 19:22:27.300  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.301  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.303  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-06 19:22:27.305  2109  2109 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@10b34bd9
09-06 19:22:27.306  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.307  2109  2109 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-06 19:22:27.307  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.311  2109  2109 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-06 19:22:27.312  2109  2109 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-06 19:22:27.312  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.313  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.313  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.315  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-06 19:22:27.319  2109  2109 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:22:27.320  2109  2109 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-06 19:22:27.321  2109  2109 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-06 19:22:27.322  2109  2109 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-06 19:22:27.322  2109  2109 V MediaPlayer[Native]: reset
09-06 19:22:27.332  2109  2109 V MediaPlayer[Native]: setListener
09-06 19:22:27.333  2109  2109 V MediaPlayer[Native]: disconnect
09-06 19:22:27.333  2109  2109 V MediaPlayer[Native]: destructor
09-06 19:22:27.333   318   318 V AudioFlinger: releasing 18 from 2109 for -1
09-06 19:22:27.333   318   318 V AudioFlinger:  decremented refcount to 0
09-06 19:22:27.333   318   318 V AudioFlinger: purging stale effects
09-06 19:22:27.333  2109  2109 V MediaPlayer[Native]: disconnect
09-06 19:22:27.334  2109  2109 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-06 19:22:27.336  2109  2109 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-06 19:22:27.336  2109  2109 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-06 19:22:27.339  2109  2109 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
,09-06 19:22:27.340  2109  2109 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-06 19:22:27.340  2109  2109 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-06 19:22:27.340  2109  2109 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 343006537
09-06 19:22:27.341  2109  2109 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 343006537
09-06 19:22:27.353  2109  2109 I SmartShareClient: [SmartShareManagerClient] terminate service: 2109/MediaPlaybackService/643883911
,09-06 19:22:27.361  2109  2109 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-06 19:22:27.361  2109  2109 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@155da64e
09-06 19:22:27.380  2109  2109 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-06 19:22:27.380  2109  2109 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-06 19:22:27.381  2109  2109 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-06 19:22:27.381  2109  2109 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,09-06 19:22:27.385  1029  1045 I ActivityManager: Killing 5671:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-06 19:22:27.386  2109  2109 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
09-06 19:22:27.402  5650  5650 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-06 19:22:27.402  5650  5650 W System.err: android.os.DeadObjectException
09-06 19:22:27.403  5650  5650 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:22:27.403  5650  5650 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:22:27.403  5650  5650 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 19:22:27.403  5650  5650 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 19:22:27.403  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:22:27.403  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:22:27.403  5650  5650 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:22:27.403  5650  5650 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:22:27.403  5650  5650 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:22:27.403  5650  5650 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:22:27.403  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:22:27.403  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:22:27.403  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:22:27.403  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:22:27.403  5650  5650 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 19:22:27.403  5650  5650 W System.err: android.os.DeadObjectException
09-06 19:22:27.404  5650  5650 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:22:27.404  5650  5650 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-06 19:22:27.404  5650  5650 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 19:22:27.404  5650  5650 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 19:22:27.404  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:22:27.404  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:22:27.404  5650  5650 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:22:27.404  5650  5650 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:22:27.404  5650  5650 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,09-06 19:22:27.404  5650  5650 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:22:27.404  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:22:27.404  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:22:27.404  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:22:27.404  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:22:27.404  5650  5650 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 19:22:27.405  5650  5650 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-06 19:22:27.522  6651  6759 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:22:27.522  6651  6759 I jxcore-log: 
,09-06 19:22:27.523  6651  6759 W jxcore-log: JXcore engine is started
,09-06 19:22:27.534  6651  6756 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:22:27.537  6651  6651 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:22:27.652  1029  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_5671/cgroup.procs: No such file or directory
,09-06 19:22:27.653  1029  1560 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-06 19:22:27.667  5650  5650 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 19:22:27.667  5650  5650 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-06 19:22:27.752  1029  1942 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6769 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:22:27.755  5650  5650 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 19:22:27.828  6769  6769 D UEI.SmartControl: Quickset Services start...
,09-06 19:22:27.831  6769  6769 I UEI.SmartControl: Manufacture = LGE
09-06 19:22:27.831  6769  6769 D UEI.SmartControl: Id = LGNevo
09-06 19:22:27.832  6769  6769 D UEI.SmartControl: File observer start...
09-06 19:22:27.833  6769  6769 E UEI.SmartControl: IR Port is disabled: false
09-06 19:22:27.833  6769  6769 D UEI.SmartControl: Starting file observer...
09-06 19:22:27.833  6769  6769 D UEI.SmartControl: Extracting JNI libs...
09-06 19:22:27.833  6769  6769 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-06 19:22:27.946  6769  6769 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-06 19:22:27.946  6769  6769 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-06 19:22:27.946  6769  6769 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-06 19:22:28.019  6769  6769 I UEI.SmartControl: --- Selecting new region: 6
09-06 19:22:28.021  6769  6769 I UEI.SmartControl: Model = LG-D855
,09-06 19:22:28.030  6769  6769 D UEI.SmartControl: QS Service created
09-06 19:22:28.063  6769  6769 I UEI.SmartControl: Service initServices...
09-06 19:22:28.067  6769  6769 D UEI.SmartControl: QS start get config
,09-06 19:22:28.121  6769  6769 D UEI.SmartControl: Loading JNI Libs...
,09-06 19:22:28.474  6598  6598 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-06 19:22:28.475  1029  1044 I ActivityManager: Killing 5650:com.lge.qremote/u0a112 (adj 15): empty #17
,09-06 19:22:28.503  6769  6769 I UEI.SmartControl: Supports setup maps: true
09-06 19:22:28.508  6769  6769 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:22:28.508  6769  6769 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:22:28.508  6769  6769 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:22:28.509  6769  6769 I UEI.SmartControl: ### init IR Blaster...
,09-06 19:22:28.521  6769  6769 D serial_port: Configuring serial port
09-06 19:22:28.525  6769  6769 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:22:28.525  6769  6769 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:22:28.525  6769  6769 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:22:28.525  6769  6769 I UEI.SmartControl: Get version...
09-06 19:22:28.546  6769  6797 D UEI.SmartControl: serial port data available: 21
,09-06 19:22:28.573  6769  6769 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:22:28.573  6769  6769 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:22:28.573  6769  6769 I UEI.SmartControl: QS saving settings...
09-06 19:22:28.574  6769  6769 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:22:28.590  6769  6797 D UEI.SmartControl: serial port data available: 4
,09-06 19:22:28.620  1029  1870 W libprocessgroup: failed to open /acct/uid_10112/pid_5650/cgroup.procs: No such file or directory
,09-06 19:22:28.628  6769  6769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 19:22:28.629  6769  6810 I UEI.SmartControl: Device manager: loading config....
09-06 19:22:28.630  6769  6810 D UEI.SmartControl: ----------- loading internal config...
09-06 19:22:28.634  6769  6769 E UEI.SmartControl: Services init done
09-06 19:22:28.634  6769  6769 D UEI.SmartControl: QS Service init finished
,09-06 19:22:28.636  6769  6769 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:22:28.636  6769  6769 D UEI.SmartControl: QS Service version code: 201091
09-06 19:22:28.637  6769  6769 D UEI.SmartControl: Service requested: Control
09-06 19:22:28.646  6769  6810 E UEI.SmartControl: Loading SETTINGS...
09-06 19:22:28.648  6769  6769 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-06 19:22:28.650  6769  6769 D UEI.SmartControl: Service.onUnbind: IControl
09-06 19:22:28.651  6769  6769 D UEI.SmartControl: Service.onDestroy
09-06 19:22:28.651  6769  6769 D UEI.SmartControl: Lock is in USE false
09-06 19:22:28.652  6769  6769 D UEI.SmartControl: unbind internal service
09-06 19:22:28.657  6769  6769 D serial_port: close(fd = 25)
09-06 19:22:28.660  6769  6769 I UEI.SmartControl: Serial port is closed.
09-06 19:22:28.661  6769  6769 I UEI.SmartControl: Serial port is closed.
09-06 19:22:28.661  6769  6810 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:22:28.661  6769  6769 D UEI.SmartControl: Blaster closed
09-06 19:22:28.661  6769  6769 D UEI.SmartControl: Shut down QS...
09-06 19:22:28.662  6769  6769 D UEI.SmartControl: Stopping QS lib
09-06 19:22:28.662  6769  6769 D UEI.SmartControl: QS lib stop result = true
09-06 19:22:28.662  6769  6769 D UEI.SmartControl: Stopped QS lib
09-06 19:22:28.663  6769  6769 D UEI.SmartControl: Stopped file observer...
09-06 19:22:28.663  6769  6769 D UEI.SmartControl: QS shutdown complete
09-06 19:22:28.664  6769  6769 D UEI.SmartControl: QS Service created
,09-06 19:22:28.665  6769  6808 I UEI.SmartControl: Notify AllClients services are ready: 11
09-06 19:22:28.665  6769  6808 D UEI.SmartControl: -----service ready thread exits
09-06 19:22:28.694  6769  6769 I UEI.SmartControl: Service initServices...
09-06 19:22:28.694  6769  6769 D UEI.SmartControl: QS start get config
,09-06 19:22:28.979  6769  6769 I UEI.SmartControl: Supports setup maps: true
,09-06 19:22:28.981  6769  6769 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:22:28.981  6769  6769 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:22:28.981  6769  6769 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:22:28.981  6769  6769 I UEI.SmartControl: ### init IR Blaster...
09-06 19:22:28.984  6769  6769 D serial_port: Configuring serial port
09-06 19:22:28.985  6769  6769 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:22:28.985  6769  6769 I UEI.SmartControl: Setting serial record hearder size = 2
,09-06 19:22:28.985  6769  6769 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:22:28.985  6769  6769 I UEI.SmartControl: Get version...
09-06 19:22:28.999  6769  6818 D UEI.SmartControl: serial port data available: 21
,09-06 19:22:29.030  6769  6769 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:22:29.030  6769  6769 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:22:29.030  6769  6769 I UEI.SmartControl: QS saving settings...
09-06 19:22:29.032  6769  6769 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:22:29.048  6769  6818 D UEI.SmartControl: serial port data available: 4
,09-06 19:22:29.077  6769  6769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:22:29.082  6769  6769 E UEI.SmartControl: Services init done
09-06 19:22:29.082  6769  6769 D UEI.SmartControl: QS Service init finished
09-06 19:22:29.085  6769  6821 I UEI.SmartControl: Device manager: loading config....
09-06 19:22:29.085  6769  6821 D UEI.SmartControl: ----------- loading internal config...
09-06 19:22:29.089  6769  6769 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:22:29.089  6769  6769 D UEI.SmartControl: QS Service version code: 201091
09-06 19:22:29.090  6769  6769 D UEI.SmartControl: Service requested: Control
09-06 19:22:29.097  6769  6821 E UEI.SmartControl: Loading SETTINGS...
,09-06 19:22:29.102  6769  6769 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 19:22:29.105  1029  1870 I ActivityManager: Killing 6315:com.android.calendar/u0a13 (adj 15): empty #17
09-06 19:22:29.120  6769  6821 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-06 19:22:29.131  6769  6820 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:22:29.131  6769  6820 D UEI.SmartControl: -----service ready thread exits
09-06 19:22:29.201  1029  1942 W libprocessgroup: failed to open /acct/uid_10013/pid_6315/cgroup.procs: No such file or directory
,09-06 19:22:29.203  6769  6769 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@10b34bd9 that was originally bound here
09-06 19:22:29.203  6769  6769 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@10b34bd9 that was originally bound here
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:22:29.203  6769  6769 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:22:29.205  6769  6769 D UEI.SmartControl: Internal service binding...
09-06 19:22:29.473  6598  6636 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-06 19:22:29.651  6769  6813 D UEI.SmartControl: Internal timer expired: 2
,09-06 19:22:32.187  1801  2355 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-06 19:22:32.191   312  6828 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-06 19:22:32.191   312  6828 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-06 19:22:32.191   312  6828 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-06 19:22:32.450  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
,09-06 19:22:32.456  1801  1801 I ConfigFetchService: stopping self
09-06 19:22:32.462  2138  2138 I ConfigService: onDestroy
09-06 19:22:32.833  6769  6780 E UEI.SmartControl: file observer is disposed!
,09-06 19:22:34.055  6769  6819 D serial_port: close(fd = 24)
,09-06 19:22:34.061  6769  6819 I UEI.SmartControl: Serial port is closed.
09-06 19:22:34.075  6769  6822 D UEI.SmartControl: Internal timer expired: 3
09-06 19:22:34.075  6769  6822 D UEI.SmartControl: unbind internal service
,09-06 19:22:34.085  6769  6769 D UEI.SmartControl: Service.onUnbind: IControl
09-06 19:22:34.088  6769  6769 D UEI.SmartControl: Service.onDestroy
09-06 19:22:34.088  6769  6769 D UEI.SmartControl: Lock is in USE false
09-06 19:22:34.088  6769  6769 D UEI.SmartControl: unbind internal service
09-06 19:22:34.088  6769  6769 I UEI.SmartControl: Serial port is closed.
09-06 19:22:34.088  6769  6769 I UEI.SmartControl: Serial port is closed.
09-06 19:22:34.088  6769  6769 D UEI.SmartControl: Blaster closed
09-06 19:22:34.088  6769  6769 D UEI.SmartControl: Shut down QS...
09-06 19:22:34.089  6769  6769 D UEI.SmartControl: Stopping QS lib
09-06 19:22:34.089  6769  6769 D UEI.SmartControl: QS lib stop result = true
09-06 19:22:34.089  6769  6769 D UEI.SmartControl: Stopped QS lib
09-06 19:22:34.089  6769  6769 D UEI.SmartControl: QS shutdown complete
,09-06 19:22:37.294  1029  1089 I ActivityManager: Waited long enough for: ServiceRecord{18d3621f u0 com.google.android.gms/.wearable.service.WearableService}
,09-06 19:22:37.346  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:22:37.346  6651  6759 I jxcore-log: 
,09-06 19:22:37.349  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:22:37.349  6651  6759 I jxcore-log: 
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:22:37.353  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:37.355  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:37.357  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:22:37.357  6651  6759 I jxcore-log: 
09-06 19:22:37.359  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:22:37.359  6651  6759 I jxcore-log: 
,09-06 19:22:37.396  2109  2109 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,09-06 19:22:38.269  6651  6759 D executeNativeTests: Running unit tests
,09-06 19:22:38.403  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:22:38.403  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 added. We now have 2 listener(s)
,09-06 19:22:38.407  1029  1715 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:38.410  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:22:38.410  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:22:38.410  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:22:38.410  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:38.410  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d added. We now have 2 listener(s)
09-06 19:22:38.410  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:22:38.411  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:22:38.413  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:22:38.418  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:22:38.421  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.422  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:22:38.423  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.425  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.429  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:22:38.433  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:22:38.433  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:22:38.437  6651  6759 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 19:22:38.438  6651  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:22:38.438  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:22:38.438  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:22:38.438  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:22:38.439  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.440  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.440  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.441  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.441  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.441  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:22:38.441  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:22:38.442  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 removed from the list
09-06 19:22:38.442  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.442  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d removed from the list
09-06 19:22:38.442  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.442  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:38.445  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.446  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.447  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.447  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.447  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.447  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.450  6651  6759 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:22:38.450  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.450  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.450  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.451  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.451  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.451  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.451  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.451  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.451  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.451  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.451  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.451  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.451  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.451  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.455  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.455  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.455  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.455  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
,09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:22:38.466  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:22:38.467  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:22:38.467  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.468  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.468  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.469  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.469  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:22:38.469  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.469  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.469  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.469  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.469  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.469  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:22:38.469  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.469  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.469  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:38.476  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.476  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.476  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.476  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.477  6651  6759 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:22:38.480  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:22:38.483  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:22:38.486  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.486  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:22:38.488  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.490  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.490  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:22:38.491  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:22:38.491  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:22:38.491  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:22:38.491  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:22:38.496  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:22:38.498  1029  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:38.504  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:22:38.511  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:22:38.515  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:22:38.517  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:22:38.517  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:22:38.519  6651  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:22:38.520  6651  6759 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:22:38.523  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.524  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.524  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:22:38.526  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.526  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.526  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:22:38.526  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.526  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.526  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.526  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.526  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.527  6651  6759 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:22:38.530  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:22:38.533  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:38.535  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.535  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:22:38.539  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.541  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.541  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:22:38.541  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:22:38.541  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:22:38.541  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:22:38.541  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:22:38.546  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:22:38.546  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:22:38.550  6651  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:22:38.550  6651  6759 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:22:38.552  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.552  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.552  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.553  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.553  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.553  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:22:38.553  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.553  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.553  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.553  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.553  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.554  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.554  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.554  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.554  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.557  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.557  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.557  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.557  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.558  6651  6759 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:22:38.560  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:22:38.566  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:38.567  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.568  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:22:38.569  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.571  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.571  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:22:38.571  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:22:38.571  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:22:38.571  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:22:38.571  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:22:38.578  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:22:38.578  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:22:38.580  6651  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:22:38.580  6651  6759 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:22:38.580  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.580  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.580  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.582  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.582  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.582  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.582  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.582  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.582  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:22:38.582  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.582  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.582  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.582  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.582  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.583  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.583  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:38.586  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.586  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.587  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.587  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.587  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.587  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.588  6651  6759 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:22:38.588  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.588  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.588  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.589  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.589  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.589  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.589  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.589  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.589  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.589  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.589  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.589  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.589  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.589  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.591  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.591  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.591  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.591  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.591  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.591  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.592  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:22:38.593  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.593  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: ,NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.593  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.593  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.593  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.593  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.593  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.593  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.594  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.594  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.594  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.594  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.594  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.594  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.595  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.595  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.600  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.600  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.600  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.600  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.601  6651  6759 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:22:38.602  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.602  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.602  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.602  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.602  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.602  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.602  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.602  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.602  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.603  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.603  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.603  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.603  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.603  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.604  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.604  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.604  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.604  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.604  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.605  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.605  6651  6759 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:22:38.606  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.606  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.606  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.606  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.606  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.606  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.606  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.606  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.606  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.606  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.606  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.606  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.606  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.607  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.612  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.612  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.613  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.613  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.613  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.613  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.613  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:22:38.615  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:22:38.615  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:22:38.615  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:22:38.616  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:22:38.616  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:22:38.616  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.616  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.616  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.616  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.617  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.617  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.617  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.617  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.617  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.617  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.617  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.617  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.617  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.617  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.618  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.618  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:22:38.622  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.622  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.622  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.622  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.623  6651  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:22:38.624  6651  6759 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:22:38.624  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:22:38.630  6651  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:22:38.630  6651  6759 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:22:38.630  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:22:38.631  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:22:38.631  6651  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:22:38.632  6651  6759 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:22:38.632  6651  6759 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:22:38.632  6651  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:22:38.632  6651  6759 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:22:38.632  6651  6759 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:22:38.632  6651  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:22:38.632  6651  6759 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:22:38.632  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:22:38.644  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:22:38.646  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:22:38.646  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:22:38.647  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:22:38.647  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:22:38.647  6651  6759 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:22:38.647  6651  6759 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:22:38.647  6651  6759 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:22:38.657  6651  6832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
09-06 19:22:38.659  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.659  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.659  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.659  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.660  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.660  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.660  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-06 19:22:38.661  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.661  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.661  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.661  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.661  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.661  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.661  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.661  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.667  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.667  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.668  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.668  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.668  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.668  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.672  6651  6837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
09-06 19:22:38.672  6651  6837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
09-06 19:22:38.672  6651  6837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
,09-06 19:22:38.679  6651  6759 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:22:38.680  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.680  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.680  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.680  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.680  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.680  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.680  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.680  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.680  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.680  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.680  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.680  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.680  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.680  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.683  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.683  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.686  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.686  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.686  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.686  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
,09-06 19:22:38.687  6651  6759 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-06 19:22:38.688  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.688  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.688  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.689  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.689  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.689  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.689  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.689  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.689  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.689  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.689  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.689  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.689  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.689  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.690  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.690  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.691  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.691  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.691  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.691  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.692  6651  6759 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:22:38.692  6651  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:22:38.692  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:22:38.692  6651  6759 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:22:38.692  6651  6759 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:22:38.693  6651  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:22:38.693  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:22:38.693  6651  6759 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfu,lly disconnected (peer ID: 00:11:22:33:44:55
09-06 19:22:38.693  6651  6759 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:22:38.693  6651  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:22:38.693  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:22:38.693  6651  6759 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:22:38.693  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.693  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.693  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.693  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.693  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.693  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:38.693  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.693  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.694  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
,09-06 19:22:38.694  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.694  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.694  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:38.694  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.694  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.696  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:22:38.696  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.696  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.696  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:22:38.696  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.696  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.697  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:22:38.697  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.697  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.697  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
,09-06 19:22:38.697  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.697  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.697  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.697  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:22:38.697  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.698  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.698  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
,09-06 19:22:38.698  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-06 19:22:38.698  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.698  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.698  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.698  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.698  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.698  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.698  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.698  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.698  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.698  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.698  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.698  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.698  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.698  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.698  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.698  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.698  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.699  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.700  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.702  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.702  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:22:38.702  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.702  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.713  6651  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:22:38.714  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:22:38.715  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:22:38.717  6651  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:22:38.717  6651  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:22:38.718  6651  6,651 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:22:38.718  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:22:38.718  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-06 19:22:38.722  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.723  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:22:38.723  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:22:38.723  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:22:38.723  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.723  6651  6759 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:22:38.723  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.723  6651  6651 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:22:38.723  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.723  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:22:38.723  6651  6759 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:22:38.723  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:22:38.724  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:22:38.724  1029  1715 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:38.725  6651  6848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:38.725  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:22:38.725  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:22:38.725  6651  6759 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:22:38.726  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.726  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.727  6651  6759 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:22:38.727  3880  3897 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-06 19:22:38.727  6651  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:22:38.727  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.727  6651  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:22:38.727  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.727  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.727  6651  6651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:22:38.727  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.727  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.728  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.728  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.728  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.728  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.728  6651  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 19:22:38.728  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.728  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.728  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.728  6651  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:22:38.728  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.728  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.728  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.728  6651  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:22:38.728  6651  6651 D org.thaliproject.p2p.btconnectorlib,.ConnectionManager: onIsServerStartedChanged: false
09-06 19:22:38.730  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.730  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.730  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.730  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.731  6651  6759 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:22:38.731  6651  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:22:38.731  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:22:38.731  6651  6759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:22:38.732  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.732  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.732  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:22:38.732  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.732  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.732  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.732  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.732  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:22:38.732  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.732  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.732  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.732  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:38.732  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.732  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:38.736  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.736  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.736  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.736  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.737  1029  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:38.738  1029  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:38.739  1029  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:38.740  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.740  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.740  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:22:38.740  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.740  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.740  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.741  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.741  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.741  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.741  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.741  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.741  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.741  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.741  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.742  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.742  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.742  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.742  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.744  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:22:38.744  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:22:38.744  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, ski,pping...
09-06 19:22:38.744  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:22:38.744  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.744  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.744  6651  6759 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f904e4 not in the list
09-06 19:22:38.744  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.744  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.744  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:22:38.744  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.744  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.744  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:22:38.744  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:22:38.745  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:22:38.745  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:22:38.745  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:22:38.745  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ddcbd4d not in the list
09-06 19:22:38.747  6651  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:22:38.747  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:22:38.747  6651  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-06 19:22:38.747  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:22:38.747  6651  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-06 19:22:38.748  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:22:38.751  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:22:38.751  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:22:38.752  6651  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:22:38.752  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:22:38.752  6651  6759 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:22:38.752  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:22:38.753  6651  6759 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:22:38.753  6651  6759 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:22:38.754  6651  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:22:38.754  6651  6759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:22:38.755  6651  6759 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:22:38.755  6651  6759 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:22:38.755  6651  6759 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:22:38.755  6651  6759 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:22:38.756  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:38.756  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22d9cd5a added. We now have 2 listener(s)
09-06 19:22:38.756  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:22:38.770  6651  6759 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 19:22:38.773  1029  1979 D WifiServiceImplEx: setWifiEnabled: true pid=6651, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:22:38.774  1029  1979 D WifiService: setWifiEnabled: true pid=6651, uid=10118
09-06 19:22:38.774  1029  1979 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:22:38.777  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:38.777  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20ea0b8b added. We now have 3 listener(s)
09-06 19:22:38.777  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:22:38.782  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:38.782  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bad7468 added. We now have 4 listener(s)
09-06 19:22:38.782  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:22:38.786  6651  6832 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-06 19:22:38.787  6651  6832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
09-06 19:22:38.788  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:38.789  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c27081 added. We now have 5 listener(s)
09-06 19:22:38.789  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:22:38.792  1029  2016 D WifiServiceImplEx: setWifiEnabled: false pid=6651, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:22:38.793  1029  2016 D WifiService: setWifiEnabled: false pid=6651, uid=10118
09-06 19:22:38.793  1029  2016 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:22:38.816  1029  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:38.816  1029  2015 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33f6f166 mBinding = false
09-06 19:22:38.817  1029  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:38.817  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:38.818  1029  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,09-06 19:22:38.818  1029  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:38.819  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:22:38.819  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:38.819  1029  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:22:38.819  1029  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:22:38.819  1029  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:22:38.820  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:22:38.821  1029  1029 D Ulp_jni : JNI:system_update. Event-4
09-06 19:22:38.821  1029  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:22:38.821  1029  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:22:38.837  1029  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:22:38.837  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:22:38.837  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-06 19:22:38.838  1029  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.838  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.838  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:22:38.838  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:22:38.839  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:22:38.839   312   887 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:22:38.841  1029  2849 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.848  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:22:38.849  1029  1100 D BluetoothManagerService: Message: 2
09-06 19:22:38.851  1029  1100 D BluetoothManagerService: Sending off request.
09-06 19:22:38.852  3880  3898 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:22:38.854  3880  3955 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:22:38.854  3880  3955 D BluetoothAdapterProperties: Setting state to 13
09-06 19:22:38.854  3880  3955 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:22:38.857  3880  3955 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:22:38.857  3880  3955 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:22:38.866  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:38.866  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:22:38.866  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:22:38.871  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:38.871  3880  3880 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:38.872  3880  3880 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:22:38.872  3880  3880 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:22:38.872  3880  3880 V BluetoothMapService: Handler(): got msg=4
09-06 19:22:38.872  3880  3880 D BluetoothMapService: MAP Service closeService in
09-06 19:22:38.872  3880  3880 D BluetoothMapMasInstance: MAP Service shutdown
,09-06 19:22:38.873  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-06 19:22:38.876  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:22:38.877  3880  4159 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 19:22:38.878  3880  3880 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:22:38.878  3880  3880 V BluetoothMapService: MAP Service closeService out
09-06 19:22:38.878  3880  3880 I BtOppRfcommListener: stopping Accept Thread
09-06 19:22:38.878  3880  3880 V BtOppRfcommListener: close mBtServerSocket
09-06 19:22:38.878  3880  3880 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:22:38.878  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:22:38.879  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-06 19:22:38.879  3880  4200 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:38.880  3880  4200 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:22:38.880  3880  3880 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:22:38.882  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:22:38.883  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:38.883  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:38.883  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:22:38.899  1029  1029 D Ulp_jni : JNI:system_update. Event-4
,09-06 19:22:38.913  1029  1089 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6855 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:22:38.920  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:22:38.920  3880  3880 V BtOppService: onDestroy
09-06 19:22:38.922  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 19:22:38.922  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:38.922  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:38.923  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:38.923  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:38.923  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:22:38.924  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.924  1029  1029 D WifiHS20: hidePasspointNotification off =false
09-06 19:22:38.925  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:38.925  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:38.925  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:38.925  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:22:38.929  1029  1029 D WifiHS20: hidePasspointNotification off =false
09-06 19:22:38.932  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:38.933  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:38.933  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:22:38.934  1029  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.935  3880  3880 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 19:22:38.936  1029  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.936  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.936  1029  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@16d80ac3
09-06 19:22:38.936  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:38.936  1029  1522 D LGWifiP2pService: P2pDisablingState
09-06 19:22:38.936  1029  1522 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHa,ndler }
09-06 19:22:38.937  1029  1522 D LGWifiP2pService: p2p socket connection lost
09-06 19:22:38.937  1029  1522 D LGWifiP2pService: P2pDisabledState
09-06 19:22:38.937  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.937  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.938  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:22:38.938  1029  1029 D RttService: SCAN_AVAILABLE : 1
09-06 19:22:38.938  1029  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.939  1029  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.941  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:22:38.941  1925  1925 D WfdsService: WifiP2pState is changed : false
09-06 19:22:38.941  1925  2324 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:22:38.941  1925  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:22:38.942  1925  2324 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:22:38.942  1925  2324 D WfdsService: STATE : WfdsDisabledState - enter
09-06 19:22:38.942  1925  2326 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:22:38.942  1925  2760 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:22:38.942  1925  2760 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:22:38.942  1925  2760 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:22:38.942  1925  2760 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:22:38.943  1925  2324 W WfdsService: DefaultState - msg [9445378] is not handled
,09-06 19:22:38.947  1029  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.947  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.948  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.948  1029  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:22:38.949  1029  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.954  1029  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:22:38.954  1029  1529 D DSQN    : disableDataServiceNotify
09-06 19:22:38.954  1029  1529 D DSQN    : stop dsqn bin
09-06 19:22:38.954  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:38.955  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 19:22:38.959  1029  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:22:38.960  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:38.960  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:38.962  1029  1522 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.962  1029  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.962  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:38.962  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:22:38.962  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:22:38.963  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:22:38.963  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:22:38.963  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:22:38.963   312   887 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:22:38.964  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:38.964  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:38.965  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:38.972  1029  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 19:22:38.972  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:38.972  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:38.972  1029  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:38.972  1029  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:22:38.973  1029  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.973  1029  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:22:38.973  1029  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:22:38.973  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:22:38.973  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:22:38.973  1029  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:38.975  1029  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:22:38.976  1029  1045 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6876 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:22:38.980  1029  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 19:22:38.980  1029  1029 D WifiHS20: hidePasspointNotification off =false
09-06 19:22:38.980  1029  1523 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:22:38.980  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:22:38.980  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:22:38.980  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:22:38.981  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:38.981  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:38.981  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:22:38.984  1029  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:38.984  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:22:38.984  1029  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:38.984  1029  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:38.984  1029  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:38.984  1029  1529 D NetworkManagementService: Removing idletimer
09-06 19:22:38.985  1029  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:38.985  1029  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:38.985  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:22:38.985  1029  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:22:38.985  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:22:38.987  1029  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:22:38.987  1029  1029 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:22:38.990  1029  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:22:38.991  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 19:22:38.997  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:22:38.997  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:38.997  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:38.997  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:38.997  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:38.997  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:38.998  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:39.000  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:39.000  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:39.000  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Can,not do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:39.000  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:22:39.004  6855  6855 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:22:39.004  6855  6855 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-06 19:22:39.004  6855  6855 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:22:39.004  6855  6855 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-06 19:22:39.005  6855  6855 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:22:39.006  6855  6855 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:22:39.012  1029  1961 I art     : Explicit concurrent mark sweep GC freed 29272(1432KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.779ms total 150.321ms
09-06 19:22:39.013  1029  1029 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:22:39.013  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:22:39.013  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:39.014  1029  1029 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 19:22:39.014  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:22:39.014  1029  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 19:22:39.014  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:22:39.014  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:22:39.014  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:22:39.014  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:22:39.014  3880  3959 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:22:39.014  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-06 19:22:39.014  3880  3955 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:22:39.015  3880  4202 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:39.015  3880  3955 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:22:39.016  3880  4161 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:39.016  3880  4205 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:39.017  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:22:39.017  3880  4025 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:22:39.019  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:22:39.019  3880  4025 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:22:39.027  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:39.027  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:22:39.031  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:39.031  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:22:39.049  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:22:39.050  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:39.050  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:39.057  1029  2849 D DhcpStateMachine: StoppedState
09-06 19:22:39.057  1029  2849 D DhcpStateMachine: StoppedState{ when=-93ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:39.059  1029  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:22:39.060  1029  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 19:22:39.076  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-06 19:22:39.077  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:39.077  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:39.078  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:39.086  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:22:39.088  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-06 19:22:39.088  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:39.089  1029  1979 I ActivityManager: Killing 6266:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-06 19:22:39.099  2744  2744 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:22:39.099  2744  2744 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:22:39.099  2744  2744 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
09-06 19:22:39.100  1029  2759 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:22:39.100  1029  2759 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-06 19:22:39.115  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 19:22:39.131  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-06 19:22:39.132  1029  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 19:22:39.132  1029  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:22:39.132  1029  2759 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:22:39.132  1029  1100 D Tethering: InitialState.processMessage what=4
09-06 19:22:39.132  1029  2759 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:22:39.133  1029  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117812
09-06 19:22:39.133  1029  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117812
09-06 19:22:39.134  1029  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:22:39.134  1029  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:22:39.134  2744  2744 W wpa_supplicant: USIM:  scard_deinit function
09-06 19:22:39.134  1029  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:22:39.135  1029  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:22:39.141  1029  1906 W libprocessgroup: failed to open /acct/uid_10014/pid_6266/cgroup.procs: No such file or directory
09-06 19:22:39.145  1029  1100 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:22:39.148  3880  3880 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:22:39.148  3880  3880 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:39.148  3880  3880 V BluetoothPbapReceiver: ***********state = 13
09-06 19:22:39.150  1029  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:39.150  3880  3880 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 19:22:39.150  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:39.151  3880  3880 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:39.151  3880  3880 V BluetoothPbapService: state: 13
09-06 19:22:39.151  3880  3880 V BluetoothPbapService: Pbap Service closeService in
09-06 19:22:39.153  3880  3880 V BluetoothPbapService: successfully stopped pbap service
09-06 19:22:39.153  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:22:39.153  3880  3880 V BluetoothPbapService: Pbap Service closeService out
09-06 19:22:39.153  3880  3880 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:22:39.153  3880  3880 V BluetoothPbapService: Pbap Service closeService in
09-06 19:22:39.153  3880  3880 V BluetoothPbapService: Pbap Service closeService out
09-06 19:22:39.153  3880  3880 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 19:22:39.157  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:39.192  6855  6855 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:39.192  6855  6855 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:22:39.204  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:22:39.211  1029  1720 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6897 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-06 19:22:39.213  1029  1100 D BluetoothManagerService: Message: 20
09-06 19:22:39.213  1029  1100 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f0192c0:true
09-06 19:22:39.226  1029  1100 D BluetoothManagerService: Message: 30
,09-06 19:22:39.228  6651  6651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:22:39.230  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:22:39.230  1029  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:22:39.230  1029  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 19:22:39.230  1029  2759 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 19:22:39.231  1029  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-06 19:22:39.234  1029  1100 D BluetoothManagerService: Message: 30
09-06 19:22:39.237  6855  6855 D LocalBluetoothProfileManager: Adding local MAP profile
09-06 19:22:39.239  6855  6855 D BluetoothMap: Create BluetoothMap proxy object
,09-06 19:22:39.240  1029  1100 D BluetoothManagerService: Message: 30
09-06 19:22:39.244  1029  1100 D BluetoothManagerService: Message: 30
09-06 19:22:39.246  6855  6855 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-06 19:22:39.247  6855  6855 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-06 19:22:39.269  6855  6855 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-06 19:22:39.275  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-06 19:22:39.289  6855  6855 D DockEventReceiver: finishStartingService: stopping service
09-06 19:22:39.300  6855  6855 D BluetoothInputDevice: Proxy object connected
09-06 19:22:39.301  6855  6855 D HidProfile: Bluetooth service connected
,09-06 19:22:39.303  6855  6855 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:22:39.304  6855  6855 D PanProfile: Bluetooth service connected
09-06 19:22:39.309  6855  6855 D BluetoothMap: Proxy object connected
09-06 19:22:39.310  6855  6855 D MapProfile: Bluetooth service connected
,09-06 19:22:39.310  6855  6855 D BluetoothMap: getConnectedDevices()
09-06 19:22:39.311  6855  6855 D BluetoothMap: Bluetooth is Not enabled
09-06 19:22:39.311  6855  6855 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:22:39.359  1029  1942 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6919 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-06 19:22:39.370  1029  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 19:22:39.370  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:22:39.370  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:22:39.370  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:22:39.377  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:22:39.378  1925  1925 D WfdsService: Supplicant Connection state is changed : false
09-06 19:22:39.379  1925  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:22:39.379  1925  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:22:39.379  1925  2324 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:22:39.375  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 19:22:39.379  1029  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:22:39.380  1029  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,09-06 19:22:39.381  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:39.383  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:39.383  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:22:39.383  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:39.385   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 27.532ms
09-06 19:22:39.392  6897  6897 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:22:39.392  6897  6897 W LG Account v2.2: No ProfileInfo entries
09-06 19:22:39.393  6897  6897 I LG Account v2.2: isEnabled: false
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Country: EU
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Operator: OPEN
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Ranking support: false
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Comfort support: false
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Accessory: true
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Health device: true
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:22:39.393  6897  6897 I Feature : [Lifetracker]Device Number: 3
,09-06 19:22:39.398  1029  1942 I ActivityManager: Killing 6348:com.android.defcontainer/u0a4 (adj 15): empty #17
09-06 19:22:39.404   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 18.463ms
09-06 19:22:39.421   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 16.617ms
,09-06 19:22:39.449  1029  2015 W libprocessgroup: failed to open /acct/uid_10004/pid_6348/cgroup.procs: No such file or directory
09-06 19:22:39.456  6855  6855 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:22:39.464  1029  1368 V AlarmManager: RTC_WAKEUP set : Alarm{2788908 type 0 when 1473182557725 com.android.vending} when 1473182557725
09-06 19:22:39.472  6855  6855 D BluetoothPermissionRequest: onReceive
,09-06 19:22:39.476  6919  6919 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:22:39.479  6855  6855 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:22:39.490  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 19:22:39.495  3880  3880 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 19:22:39.495  3880  3880 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-06 19:22:39.496  3880  3880 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 19:22:39.502  3880  3880 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:39.502  3880  3880 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-06 19:22:39.503  3880  3880 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:22:39.503  3880  3880 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:39.503  3880  3880 V BluetoothFtpService: Ftp Service closeService
09-06 19:22:39.503  3880  3880 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 19:22:39.505  3880  3880 V BluetoothFtpService: successfully stopped ftp service
09-06 19:22:39.505  3880  3880 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:39.505  3880  3880 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:39.506  3880  3880 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:39.506  3880  3880 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:39.506  3880  3880 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:22:39.506  3880  3880 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:22:39.508  3880  3880 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:22:39.508  3880  3880 V BluetoothFtpService: Ftp Service closeService
09-06 19:22:39.511  6919  6919 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-06 19:22:39.561  1029  1560 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6943 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:22:39.563  3880  3880 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:39.563  3880  3880 V BluetoothSapService: state: 13
09-06 19:22:39.563  3880  3880 V BluetoothSapService: Stopping SAP server process
,09-06 19:22:39.564  3880  3880 V BluetoothSapService: Sap Service closeSapService in
09-06 19:22:39.565  3880  3880 V BluetoothSapService: Close listen Socket : 
09-06 19:22:39.565  3880  3880 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:22:39.565  3880  3880 V BluetoothSapService: Close sapd  Socket : 
09-06 19:22:39.565  1029  1906 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:22:39.567  3880  3880 V BluetoothSapService: Sap Service closeSapService out
09-06 19:22:39.567  3880  3880 V BluetoothSapService: Sap Service onDestroy
09-06 19:22:39.567  3880  3880 V BluetoothSapService: Sap Service closeSapService in
09-06 19:22:39.567  3880  3880 V BluetoothSapService: Close listen Socket : 
09-06 19:22:39.567  3880  3880 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:22:39.567  3880  3880 V BluetoothSapService: Close sapd  Socket : 
09-06 19:22:39.568  3880  3880 V BluetoothSapService: Sap Service closeSapService out
,09-06 19:22:39.604  6919  6919 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-06 19:22:39.604  6919  6919 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 19:22:39.605  6919  6919 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:22:39.605  6919  6919 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:22:39.605  6919  6919 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:22:39.607  6919  6919 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 19:22:39.615  6919  6919 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-06 19:22:39.623  6943  6943 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:22:39.626  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:22:39.630  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:39.640  1029  1960 I ActivityManager: Killing 6519:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-06 19:22:39.682  1029  1715 W libprocessgroup: failed to open /acct/uid_10008/pid_6519/cgroup.procs: No such file or directory
,09-06 19:22:39.683  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:22:39.686  6919  6919 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 19:22:39.688  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:39.692  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:22:39.692  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:22:39.692  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:39.694  6919  6919 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-06 19:22:39.698  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:39.706  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:39.714  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:39.715  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:39.717  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:22:39.722  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:22:39.726  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:22:39.726  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:22:39.726  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:39.730  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:39.740  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:39.749  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:22:39.749  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:39.751  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:22:39.806  1029  1906 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6963 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-06 19:22:39.835  6115  6115 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-06 19:22:39.840  1029  1720 I ActivityManager: Killing 6038:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-06 19:22:39.872  1029  1979 W libprocessgroup: failed to open /acct/uid_10011/pid_6038/cgroup.procs: No such file or directory
09-06 19:22:39.915  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:22:39.918  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:22:39.927  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:22:39.959  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:22:39.959  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:22:39.960  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:22:39.960  6855  6855 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:22:39.961  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 19:22:39.962  6963  6983 W FormManager: Network not available. Please check & try again.
09-06 19:22:39.969  6963  6984 V FormManager: Network unavailable.
09-06 19:22:39.973  6963  6984 V FormManager: Network unavailable.
,09-06 19:22:39.982  6855  6855 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:22:39.982  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:22:39.983  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:22:39.983  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:22:39.983  6855  6855 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:22:39.983  6855  6855 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:22:39.987  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:22:39.987  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:22:39.989  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:39.990  1029  2016 I ActivityManager: Killing 6058:com.android.contacts/u0a19 (adj 15): empty #17
09-06 19:22:40.021  3880  3959 D bt_hci_bdroid: cleanup
09-06 19:22:40.021  3880  4027 I bt_lpm  : LPM is already off!!!
09-06 19:22:40.021  3880  4116 I bt_userial_mct: exiting userial_read_thread
09-06 19:22:40.021  3880  4116 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:22:40.021  1029  1871 W libprocessgroup: failed to open /acct/uid_10019/pid_6058/cgroup.procs: No such file or directory
09-06 19:22:40.021  3880  4025 W bt-btif : ag scb idx 1 not allocated
09-06 19:22:40.021  3880  4025 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:22:40.021  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:40.021  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:40.022  3880  4025 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:40.022  3880  4025 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:22:40.022  3880  3959 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:22:40.022  3880  4027 I bt_vendor: hw_epilog_process
09-06 19:22:40.022  3880  3959 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 19:22:40.022  3880  3959 D bt_userial_mct: userial_close
09-06 19:22:40.022  3880  3959 E bt_userial_mct: pthread_join() FAILED result:3
09-06 19:22:40.022  3880  3959 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-06 19:22:40.025  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:40.033  4308  6988 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:22:40.035  6876  6876 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 19:22:40.035  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:22:40.035  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:40.038  4308  6989 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:22:40.039  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:22:40.040  4308  6989 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:22:40.050  6963  6991 W FormManager: Network not available. Please check & try again.
09-06 19:22:40.051  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:40.052  6963  6992 V FormManager: Network unavailable.
09-06 19:22:40.060  6963  6992 V FormManager: Network unavailable.
,09-06 19:22:40.074  6919  6919 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 19:22:40.076  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:22:40.076  6919  6919 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 19:22:40.105  4499  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-06 19:22:40.116  6919  6919 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:40.117  6919  6919 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:22:40.119  3880  3959 D bt_hci_bdroid: set_power 0
09-06 19:22:40.119  3880  3959 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:22:40.119  3880  3959 I bt_vendor: bluetooth satus is on
,09-06 19:22:40.119  3880  3959 I bt_vendor: bt-vendor : resetting BT status
09-06 19:22:40.120  3880  3959 I bt_vendor: Starting hciattach daemon
09-06 19:22:40.120  3880  3959 I bt_vendor: try to set false
09-06 19:22:40.120  3880  3959 I bt_vendor: Starting hciattach daemon
09-06 19:22:40.121  3880  3959 I bt_vendor: try to set false
09-06 19:22:40.121  3880  3959 I bt_vendor: cleanup
09-06 19:22:40.122  3880  4025 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 19:22:40.127  6919  6919 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 19:22:40.129  6919  6919 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 19:22:40.129  6919  6919 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 19:22:40.129  6919  6919 V SoundPool: doLoad: loading sample sampleID=1
09-06 19:22:40.131  3880  3959 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:22:40.131  3880  3959 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:22:40.132  3880  3955 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:22:40.134  3880  3880 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:22:40.137  3880  3880 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:22:40.137  3880  3880 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:22:40.137  3880  3880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9872a52
09-06 19:22:40.138  3880  3972 D HeadsetStateMachine: Exit Disconnected: -1
09-06 19:22:40.139  3880  3955 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:22:40.140  3880  3880 D A2dpService: Received stop request...Stopping profile...
09-06 19:22:40.140  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:40.140  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:40.140  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:40.140  1029  1029 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:40.140  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:22:40.140  3880  4006 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:22:40.141  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 19:22:40.142  3880  3880 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:22:40.142  3880  3880 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:22:40.142  3880  3880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9872a52
09-06 19:22:40.144  3880  3880 D HidService: Received stop request...Stopping profile...
09-06 19:22:40.144  3880  3880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9872a52
09-06 19:22:40.145  6855  6855 D BluetoothInputDevice: Proxy object disconnected
09-06 19:22:40.145  1029  1029 D BluetoothA2dp: Proxy object disconnected
09-06 19:22:40.145  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:22:40.145  6855  6855 D HidProfile: Bluetooth service disconnected
09-06 19:22:40.146  3880  3880 D HealthService: Received stop request...Stopping profile...
09-06 19:22:40.146  3880  3880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9872a52
09-06 19:22:40.148  3880  3880 D PanService: Received stop request...Stopping profile...
09-06 19:22:40.148  3880  3880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9872a52
09-06 19:22:40.150  6855  6855 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:22:40.150  6855  6855 D PanProfile: Bluetooth service disconnected
09-06 19:22:40.150  3880  3880 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:22:40.151  6919  7001 V SoundPool: Start decode
09-06 19:22:40.151  6919  7001 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-06 19:22:40.152  6919  6919 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:22:40.152  3880  3880 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:22:40.152  3880  3880 D BtGatt.GattService: stop()
09-06 19:22:40.153  3880  3880 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:22:40.154  3880  3880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9872a52
09-06 19:22:40.154  3880  3880 D HeadsetStateMachine: Unbinding service...
09-06 19:22:40.156  3880  3880 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:22:40.156  3880  3880 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:22:40.156  3880  3880 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:22:40.156  3880  3880 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:22:40.156  3880  3880 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:22:40.156  3880  3880 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:22:40.156  3880  3880 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:22:40.157  3880  3880 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:22:40.157  3880  3880 D BluetoothMapService: stop()
09-06 19:22:40.158   318  2154 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 19:22:40.158   318  2154 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 19:22:40.158  3880  3880 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:22:40.158   318  2154 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 19:22:40.158   318  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 19:22:40.158   318  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 19:22:40.158   318  2154 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 19:22:40.158  3880  3880 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 19:22:40.158   318  2154 V MediaPlayerService: player type = 3
09-06 19:22:40.158   318  2154 V AwesomePlayer: AwesomePlayer create()
09-06 19:22:40.161  3880  3880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9872a52
09-06 19:22:40.164   318  2154 V AwesomePlayer: reset_l() 
09-06 19:22:40.164   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:22:40.164   318  2154 V AwesomePlayer: setAudioSink() 
09-06 19:22:40.164   318  2154 V AwesomePlayer: reset_l() 
09-06 19:22:40.164   318  2154 V AudioCache: notify(0xb5474a80, 8, 0, 0)
09-06 19:22:40.164   318  2154 V AudioCache: ignored
09-06 19:22:40.164   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:22:40.164  3880  3880 I BluetoothA2dpServiceJni: cleanupNative
09-06 19:22:40.164  3880  4007 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:22:40.165  3880  3880 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:22:40.165  3880  3880 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:22:40.165  3880  3880 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:22:40.165  3880  3880 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:22:40.165  3880  3880 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:22:40.165  3880  3880 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:22:40.165  3880  3880 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:22:40.165  3880  3880 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:22:40.165  6855  6855 D BluetoothMap: Proxy object disconnected
09-06 19:22:40.165  3880  3880 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:22:40.166  6855  6855 D MapProfile: Bluetooth service disconnected
09-06 19:22:40.166   318  2154 D ,Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 19:22:40.166   318  2154 V AwesomePlayer: setDataSource_l dataSource
09-06 19:22:40.166   318  2154 V LGParserOSAL: SniffLGParser start
09-06 19:22:40.166   318  2154 V LGParserOSAL: MainType:5, SubType=0
09-06 19:22:40.166   318  2154 V LGParserOSAL: #### check Mime : application/ogg
09-06 19:22:40.166  3880  3880 V BluetoothMapService: Handler(): got msg=4
09-06 19:22:40.166   318  2154 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 19:22:40.166  3880  3880 D BluetoothMapService: MAP Service closeService in
09-06 19:22:40.166   318  2154 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 19:22:40.166  3880  3880 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:22:40.166  3880  3880 V BluetoothMapService: MAP Service closeService out
09-06 19:22:40.167  3880  3955 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:22:40.167  3880  3955 D BluetoothAdapterProperties: Setting state to 10
09-06 19:22:40.167  3880  3955 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:22:40.167  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:40.167  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:22:40.168  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-06 19:22:40.168  3880  3955 I BluetoothAdapterState: Entering OffState
09-06 19:22:40.168  3880  3880 D BluetoothMapService: cleanup()
09-06 19:22:40.168  3880  3880 D BluetoothMapService: MAP Service closeService in
09-06 19:22:40.168  3880  3880 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:22:40.168  3880  3880 V BluetoothMapService: MAP Service closeService out
09-06 19:22:40.169  1836  2582 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:22:40.171  6855  6872 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:22:40.172  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:40.172  1836  2563 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:40.173  1029  1100 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:22:40.173  6919  6919 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:22:40.173  6855  6874 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:22:40.174  1029  1100 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:40.174  6855  6872 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:22:40.175  6855  6874 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:22:40.176  1029  1100 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:22:40.176  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 19:22:40.178  1029  1100 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:22:40.178  1029  1100 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:22:40.178  1029  1100 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@33f6f166 mBinding = false
09-06 19:22:40.179  1029  1100 D BluetoothManagerService: Sending unbind request.
09-06 19:22:40.180  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 19:22:40.183  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:40.183  1925  2132 D LGBluetoothAPIService: Message: 2
09-06 19:22:40.184  1925  2132 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1d2443ed mBinding = false
09-06 19:22:40.184  1925  2132 D LGBluetoothAPIService: Sending unbind request.
09-06 19:22:40.184  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:40.186  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:40.188  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:40.188  6855  6855 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:22:40.189  6855  6855 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 19:22:40.189  6855  6855 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 19:22:40.193  3880  3959 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:22:40.193  3880  3880 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:22:40.193  3880  3880 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:22:40.194  3880  3880 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:22:40.194  3880  3880 I art     : --- WEIRD: removing null entry 246
09-06 19:22:40.194  3880  3880 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-06 19:22:40.194  3880  3880 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 19:22:40.195  3880  3880 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:22:40.197  3880  3880 I art     : System.exit called, status: 0
,09-06 19:22:40.197  3880  3880 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:22:40.211  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:22:40.216  1587  1587 D BluetoothAdapter: 567499306: getState() :  mService = null. Returning STATE_OFF
09-06 19:22:40.216  1587  1587 D BluetoothAdapter: 567499306: getState() :  mService = null. Returning STATE_OFF
09-06 19:22:40.217  6769  6769 D UEI.SmartControl: QS Service created
09-06 19:22:40.218  6855  6855 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:22:40.224   318  1366 V AudioFlinger: 3880 died, releasing its sessions
09-06 19:22:40.224   318  1366 V AudioFlinger:  pid 1836 @ 0
09-06 19:22:40.224   318  1366 V AudioFlinger:  pid 3407 @ 1
09-06 19:22:40.224   318  1366 V AudioFlinger:  pid 3407 @ 2
09-06 19:22:40.225  6855  6855 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 19:22:40.237  6769  6769 I UEI.SmartControl: Service initServices...
09-06 19:22:40.238  6769  6769 D UEI.SmartControl: QS start get config
,09-06 19:22:40.239  6919  6919 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:22:40.240  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:22:40.252   318  2154 V LGParserOSAL: supported mime: application/ogg
09-06 19:22:40.252   318  2154 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 19:22:40.252   318  2154 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 19:22:40.252   318  2154 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 19:22:40.252   318  2154 V AwesomePlayer: AudioTrack Setting
09-06 19:22:40.252   318  2154 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 19:22:40.252   318  2154 V AwesomePlayer: setAudioSource() 
09-06 19:22:40.252   318  2154 V MediaPlayerService: prepare
09-06 19:22:40.252   318  2154 V AwesomePlayer: prepareAsync_l() 
09-06 19:22:40.252   318  2154 V MediaPlayerService: wait for prepare
09-06 19:22:40.252   318  7010 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 19:22:40.252   318  7010 V AwesomePlayer: initAudioDecoder() 
09-06 19:22:40.252   318  7010 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:22:40.252   318  7010 V AudioSystem: isOffloadSupported()
09-06 19:22:40.252   318  7010 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:22:40.252   318  7010 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:22:40.252   318  7010 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:22:40.252   318  7010 V AwesomePlayer: getUseOffload() = 0 
09-06 19:22:40.253   318  7010 V OMXCodec: OMXCodec::Create
09-06 19:22:40.253   318  7010 V OMXCodec: findMatchingCodecs()
09-06 19:22:40.253   318  7010 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 19:22:40.253   318  7010 V OMXCodec: matchingCodecs.size()=1
09-06 19:22:40.253   318  7010 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-06 19:22:40.254  6919  6919 V LGMDMManager: Create singleton instance
09-06 19:22:40.254   318  7010 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 19:22:40.254   318  7010 V LGCodecAdapter: LG Codec Adapter start
09-06 19:22:40.254   318  7010 V OMXCodec: OMXCodec Createtor
09-06 19:22:40.254   318  7010 V OMXCodec: setComponentRole
09-06 19:22:40.254   318  7010 V OMXCodec: configureCodec protected=0
09-06 19:22:40.254   318  7010 V LGCodecAdapter: called getLGCodecSpecificData
09-06 19:22:40.254   318  7010 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 19:22:40.254   318  7010 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 19:22:40.254   318  7010 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 19:22:40.254   318  7010 V LGCodecOSAL: Not support LGCodec
09-06 19:22:40.254   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:22:40.254   318  7010 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 19:22:40.254   318  7010 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 19:22:40.254   318  7010 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 19:22:40.254   318  7010 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:22:40.254   318  7010 V AudioSystem: isOffloadSupported()
09-06 19:22:40.254   318  7010 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:22:40.254   318  7010 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:22:40.254   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 19:22:40.254   318  7010 V OMXCodec: init()
09-06 19:22:40.254   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 19:22:40.254   318  7010 V OMXCodec: allocateBuffers
09-06 19:22:40.254   318  7010 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 19:22:40.254   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
09-06 19:22:40.255   318  7010 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
09-06 19:22:40.255   318  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fce0 on output port
09-06 19:22:40.255   318  7010 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:22:40.255   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:22:40.255   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:22:40.255   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 19:22:40.255   318  7010 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:22:40.255   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 19:22:40.255   318  7012 V OMX,Codec: [OMX.google.vorbis.decoder] Now Executing.
09-06 19:22:40.255   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 19:22:40.255   318  7010 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 19:22:40.255   318  7010 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 19:22:40.255   318  7010 V AudioCache: notify(0xb5474a80, 5, 0, 0)
09-06 19:22:40.255   318  7010 V AudioCache: ignored
09-06 19:22:40.255   318  7010 V AudioCache: notify(0xb5474a80, 1, 0, 0)
09-06 19:22:40.255   318  7010 V AudioCache: prepared
09-06 19:22:40.255   318  2154 V AudioCache: wait - success
09-06 19:22:40.255   318  2154 V MediaPlayerService: start
09-06 19:22:40.255   318  2154 V AwesomePlayer: play_l() 
09-06 19:22:40.255   318  2154 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 19:22:40.255   318  2154 V AwesomePlayer: createAudioPlayer_l
09-06 19:22:40.255   318  2154 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 19:22:40.255   318  2154 V AwesomePlayer: startAudioPlayer_l() 
09-06 19:22:40.255   318  2154 D AudioPlayer: start of Playback, useOffload 0
09-06 19:22:40.256   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:22:40.256   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049056
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 19:22:40.258   318  7012 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:22:40.258   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:22:40.259   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
09-06 19:22:40.259   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-06 19:22:40.259   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
09-06 19:22:40.259   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-06 19:22:40.259   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 19:22:40.259   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 19:22:40.260   318  2154 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 19:22:40.261   318  2154 V AudioCache: notify(0xb5474a80, 6, 0, 0)
09-06 19:22:40.261   318  2154 V AudioCache: ignored
09-06 19:22:40.261   318  2154 V MediaPlayerService: wait for playback complete
09-06 19:22:40.261   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.261   318  7014 V AudioCache: memcpy(0xac300000, 0xb57d2000, 4096)
09-06 19:22:40.264   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.264   318  7014 V AudioCache: memcpy(0xac301000, 0xb57d2000, 4096)
09-06 19:22:40.264   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.264   318  7014 V AudioCache: memcpy(0xac302000, 0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: memcpy(0xac303000, 0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: memcpy(0xac304000, 0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: memcpy(0xac305000, 0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.265   318  7014 V AudioCache: memcpy(0xac306000, 0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: memcpy(0xac307000, 0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: memcpy(0xac308000, 0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: memcpy(0xac309000, 0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: memcpy(0xac30a000, 0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.266   318  7014 V AudioCache: memcpy(0xac30b000, 0xb57d2000, 4096)
09-06 19:22:40.267   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.267   318  7014 V AudioCache: memcpy(0xac30c000, 0xb57d2000, 4096)
09-06 19:22:40.267   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.267   318  7014 V AudioCache: memcpy(0xac30d000, 0xb57d2000, 4096)
09-06 19:22:40.268   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.268   318  7014 V AudioCache: memcpy(0xac30e000, 0xb57d2000, 4096)
09-06 19:22:40.268   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.268   318  7014 V AudioCache: memcpy(0xac30f000, 0xb57d2000, 4096)
09-06 19:22:40.268   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.268   318  7014 V AudioCache: memcpy(0xac310000, 0xb57d2000, 4096)
09-06 19:22:40.269   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.269   318  7014 V AudioCache: memcpy(0xac311000, 0xb57d2000, 4096)
09-06 19:22:40.269   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.269   318  7014 V AudioCache: memcpy(0xac312000, 0xb57d2000, 4096)
09-06 19:22:40.270   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.270   318  7014 V AudioCache: memcpy(0xac313000, 0xb57d2000, 4096)
09-06 19:22:40.270   318  7014 V AudioCache: write(0xb57d2000, 4096)
,09-06 19:22:40.270   318  7014 V AudioCache: memcpy(0xac314000, 0xb57d2000, 4096)
09-06 19:22:40.270   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.270   318  7014 V AudioCache: memcpy(0xac315000, 0xb57d2000, 4096)
09-06 19:22:40.271   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.271   318  7014 V AudioCache: memcpy(0xac316000, 0xb57d2000, 4096)
09-06 19:22:40.271   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.271   318  7014 V AudioCache: memcpy(0xac317000, 0xb57d2000, 4096)
09-06 19:22:40.272   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.272   318  7014 V AudioCache: memcpy(0xac318000, 0xb57d2000, 4096)
09-06 19:22:40.272   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.272   318  7014 V AudioCache: memcpy(0xac319000, 0xb57d2000, 4096)
09-06 19:22:40.272   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.272   318  7014 V AudioCache: memcpy(0xac31a000, 0xb57d2000, 4096)
09-06 19:22:40.273   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.273   318  7014 V AudioCache: memcpy(0xac31b000, 0xb57d2000, 4096)
09-06 19:22:40.273   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.273   318  7014 V AudioCache: memcpy(0xac31c000, 0xb57d2000, 4096)
09-06 19:22:40.274   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.274   318  7014 V AudioCache: memcpy(0xac31d000, 0xb57d2000, 4096)
09-06 19:22:40.274   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.274   318  7014 V AudioCache: memcpy(0xac31e000, 0xb57d2000, 4096)
09-06 19:22:40.274   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.274   318  7014 V AudioCache: memcpy(0xac31f000, 0xb57d2000, 4096)
09-06 19:22:40.275   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.275   318  7014 V AudioCache: memcpy(0xac320000, 0xb57d2000, 4096)
09-06 19:22:40.275   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.275   318  7014 V AudioCache: memcpy(0xac321000, 0xb57d2000, 4096)
09-06 19:22:40.276   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.276   318  7014 V AudioCache: memcpy(0xac322000, 0xb57d2000, 4096)
09-06 19:22:40.276   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.276   318  7014 V AudioCache: memcpy(0xac323000, 0xb57d2000, 4096)
09-06 19:22:40.276   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.276   318  7014 V AudioCache: memcpy(0xac324000, 0xb57d2000, 4096)
09-06 19:22:40.277   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.277   318  7014 V AudioCache: memcpy(0xac325000, 0xb57d2000, 4096)
09-06 19:22:40.277   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.277   318  7014 V AudioCache: memcpy(0xac326000, 0xb57d2000, 4096)
09-06 19:22:40.278   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.278   318  7014 V AudioCache: memcpy(0xac327000, 0xb57d2000, 4096)
09-06 19:22:40.278   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.278   318  7014 V AudioCache: memcpy(0xac328000, 0xb57d2000, 4096)
09-06 19:22:40.278   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.278   318  7014 V AudioCache: memcpy(0xac329000, 0xb57d2000, 4096)
09-06 19:22:40.279   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.279   318  7014 V AudioCache: memcpy(0xac32a000, 0xb57d2000, 4096)
09-06 19:22:40.279   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.279   318  7014 V AudioCache: memcpy(0xac32b000, 0xb57d2000, 4096)
09-06 19:22:40.280   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.280   318  7014 V AudioCache: memcpy(0xac32c000, 0xb57d2000, 4096)
09-06 19:22:40.280   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.280   318  7014 V AudioCache: memcpy(0xac32d000, 0xb57d2000, 4096)
09-06 19:22:40.281   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.281   318  7014 V AudioCache: memcpy(0xac32e000, 0xb57d2000, 4096)
09-06 19:22:40.281   318  7014 V Au,dioCache: write(0xb57d2000, 4096)
09-06 19:22:40.281   318  7014 V AudioCache: memcpy(0xac32f000, 0xb57d2000, 4096)
09-06 19:22:40.281   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.281   318  7014 V AudioCache: memcpy(0xac330000, 0xb57d2000, 4096)
09-06 19:22:40.282   318  7014 V AudioCache: write(0xb57d2000, 4096)
09-06 19:22:40.282   318  7014 V AudioCache: memcpy(0xac331000, 0xb57d2000, 4096)
09-06 19:22:40.282   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 19:22:40.282   318  7014 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:22:40.282   318  7014 V AwesomePlayer: postAudioEOS() 
09-06 19:22:40.282   318  7014 V AudioCache: write(0xb57d2000, 280)
09-06 19:22:40.282   318  7014 V AudioCache: memcpy(0xac332000, 0xb57d2000, 280)
09-06 19:22:40.287   318  7010 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 19:22:40.287   318  7010 V AwesomePlayer: onStreamDone
09-06 19:22:40.287   318  7010 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 19:22:40.287   318  7010 V AudioCache: notify(0xb5474a80, 2, 0, 0)
09-06 19:22:40.288   318  7010 V AudioCache: playback complete
09-06 19:22:40.288   318  7010 V AwesomePlayer: pause_l() 
09-06 19:22:40.288   318  7010 V AudioCache: notify(0xb5474a80, 7, 0, 0)
09-06 19:22:40.288   318  7010 V AudioCache: ignored
09-06 19:22:40.288   318  7010 V AwesomePlayer: cancelPlayerEvents
09-06 19:22:40.288   318  2154 V AudioCache: wait - success
09-06 19:22:40.288   318  2154 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 19:22:40.288   318  7010 D AudioPlayer: Pause Playback at 1068125
09-06 19:22:40.288   318  2154 V AwesomePlayer: reset_l() 
09-06 19:22:40.288   318  2154 V AudioCache: notify(0xb5474a80, 8, 0, 0)
09-06 19:22:40.288   318  2154 V AudioCache: ignored
09-06 19:22:40.288   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:22:40.288   318  2154 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 19:22:40.288   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 19:22:40.288   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 19:22:40.288   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 19:22:40.288   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
09-06 19:22:40.288   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vor,bis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 19:22:40.289   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:22:40.289   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 19:22:40.289   318  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 19:22:40.289   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:22:40.289   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 19:22:40.289   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 19:22:40.290   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 19:22:40.290   318  2154 D AudioPlayer: AudioPlayer releasing audio source
09-06 19:22:40.290   318  2154 D AudioPlayer: AudioPlayer done releasing audio source
09-06 19:22:40.290   318  2154 V AwesomePlayer: reset_l() 
09-06 19:22:40.290   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:22:40.290   318  2154 V AwesomePlayer: ~AwesomePlayer call
09-06 19:22:40.290   318  2154 V AwesomePlayer: reset_l() 
09-06 19:22:40.290   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:22:40.290  6919  7001 V SoundPool: close(31)
09-06 19:22:40.290  6919  7001 V SoundPool: pointer = 0x9fe60000, size = 205080, sampleRate = 48000, numChannels = 2
09-06 19:22:40.319  1029  2016 I ActivityManager: Process com.android.bluetooth (pid 3880) has died
09-06 19:22:40.320  1029  2016 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-06 19:22:40.324  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:22:40.332  6855  6855 D BluetoothPermissionRequest: onReceive
09-06 19:22:40.334  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:22:40.335  6855  6855 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:22:40.335  6855  6855 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 19:22:40.335  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 19:22:40.337  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6877
,09-06 19:22:40.339  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 19:22:40.395  1029  1906 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7015 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 19:22:40.450  7015  7015 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:22:40.450  7015  7015 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:22:40.451  7015  7015 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 19:22:40.452  7015  7015 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:22:40.481  7015  7015 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:22:40.514  7015  7015 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b5477ab Instance Count = 1
,09-06 19:22:40.516  6769  6769 I UEI.SmartControl: Supports setup maps: true
09-06 19:22:40.518  6769  6769 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:22:40.518  6769  6769 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:22:40.519  6769  6769 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:22:40.519  6769  6769 I UEI.SmartControl: ### init IR Blaster...
09-06 19:22:40.522  6769  6769 D serial_port: Configuring serial port
09-06 19:22:40.522  6769  6769 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:22:40.522  6769  6769 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:22:40.522  6769  6769 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:22:40.522  6769  6769 I UEI.SmartControl: Get version...
09-06 19:22:40.523  7015  7015 D BluetoothAdapterApp: onCreate
09-06 19:22:40.541  6769  7032 D UEI.SmartControl: serial port data available: 21
,09-06 19:22:40.544  7015  7015 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 19:22:40.544  7015  7015 D ProfileConfigQcom: Adding HeadsetService
09-06 19:22:40.544  7015  7015 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 19:22:40.545  7015  7015 D ProfileConfigQcom: Adding A2dpService
09-06 19:22:40.545  7015  7015 D ProfileConfigQcom: [BTUI] HidService is supported
09-06 19:22:40.545  7015  7015 D ProfileConfigQcom: Adding HidService
09-06 19:22:40.545  7015  7015 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 19:22:40.545  7015  7015 D ProfileConfigQcom: Adding HealthService
09-06 19:22:40.546  7015  7015 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-06 19:22:40.546  7015  7015 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 19:22:40.546  7015  7015 D ProfileConfigQcom: Adding PanService
09-06 19:22:40.547  7015  7015 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 19:22:40.547  7015  7015 D ProfileConfigQcom: Adding GattService
09-06 19:22:40.547  7015  7015 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 19:22:40.547  7015  7015 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:22:40.547  7015  7015 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 19:22:40.549  7015  7015 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-06 19:22:40.554  6855  6855 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:22:40.555  7015  7015 V LGMDMManagerInternal: Create singleton instance
,09-06 19:22:40.568  6769  6769 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:22:40.568  6769  6769 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:22:40.568  6769  6769 I UEI.SmartControl: QS saving settings...
09-06 19:22:40.570  6769  6769 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:22:40.586  6769  7032 D UEI.SmartControl: serial port data available: 4
,09-06 19:22:40.618  7015  7015 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:40.618  6769  6769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:22:40.620  6769  7039 I UEI.SmartControl: Device manager: loading config....
09-06 19:22:40.620  6769  7039 D UEI.SmartControl: ----------- loading internal config...
09-06 19:22:40.622  6769  6769 E UEI.SmartControl: Services init done
09-06 19:22:40.622  6769  6769 D UEI.SmartControl: QS Service init finished
09-06 19:22:40.624  6769  6769 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:22:40.624  6769  6769 D UEI.SmartControl: QS Service version code: 201091
09-06 19:22:40.624  7015  7015 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:40.625  6769  6769 D UEI.SmartControl: Service requested: Control
09-06 19:22:40.625  7015  7015 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:40.625  7015  7015 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:40.626  6769  7039 E UEI.SmartControl: Loading SETTINGS...
09-06 19:22:40.629  7015  7015 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:40.629  6769  7039 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:22:40.629  7015  7015 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 19:22:40.632  6769  6769 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-06 19:22:40.635  6769  7038 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:22:40.635  6769  7038 D UEI.SmartControl: -----service ready thread exits
09-06 19:22:40.641  6769  6769 D UEI.SmartControl: Internal service binding...
09-06 19:22:40.642  6943  6943 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-06 19:22:40.642  6919  6919 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 19:22:40.644  6769  6785 I UEI.SmartControl: ------ IControl API: 11
09-06 19:22:40.644  6769  6785 D UEI.SmartControl: File observer start...
09-06 19:22:40.645  6769  6785 E UEI.SmartControl: IR Port is disabled: false
09-06 19:22:40.645  6769  6785 D UEI.SmartControl: Starting file observer...
09-06 19:22:40.647  6769  6785 I UEI.SmartControl: Registering callback...
09-06 19:22:40.648  6769  6784 I UEI.SmartControl: ------ IControl API: 19
,09-06 19:22:40.649  6769  6784 I UEI.SmartControl: Registering Services Ready callback...
09-06 19:22:40.649  6769  6784 I UEI.SmartControl: Notify client services are ready...
09-06 19:22:40.649  6919  6940 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 19:22:40.649  6919  6999 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 19:22:40.650  6919  6999 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 19:22:40.650  6919  6919 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 19:22:40.651  6919  6919 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 19:22:40.651  6769  6785 I UEI.SmartControl: ------ IControl API: 8
09-06 19:22:40.653  6919  6919 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 19:22:40.653  6919  6919 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 19:22:40.653  6919  6919 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 19:22:40.654  6919  6919 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 19:22:40.654  6919  6919 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 19:22:40.655  6919  6919 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,09-06 19:22:40.656  6919  6919 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-06 19:22:40.658  6919  6919 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 19:22:40.658  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:22:40.659  6919  6919 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:22:40.659  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:22:40.660  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-06 19:22:40.661  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 19:22:40.661  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 19:22:40.662  6919  6919 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473182560661]
09-06 19:22:40.664  6919  6919 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 19:22:40.665  1029  1720 I ActivityManager: Killing 6088:com.android.gallery3d/u0a27 (adj 15): empty #17
09-06 19:22:40.689  6919  7042 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 19:22:40.709  1029  1720 I ActivityManager: Killing 6563:com.lge.email/u0a23 (adj 15): empty #18
,09-06 19:22:40.742  1029  1560 W libprocessgroup: failed to open /acct/uid_10027/pid_6088/cgroup.procs: No such file or directory
,09-06 19:22:40.753  1029  1045 W libprocessgroup: failed to open /acct/uid_10023/pid_6563/cgroup.procs: No such file or directory
,09-06 19:22:40.755  6919  6919 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-06 19:22:40.757  6919  6919 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:22:40.758  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 19:22:40.758  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 19:22:40.759  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-06 19:22:40.759  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 19:22:40.760  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 19:22:40.775  6919  6919 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-06 19:22:41.927  1029  1906 D WifiServiceImplEx: setWifiEnabled: true pid=6651, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-06 19:22:41.935  1029  1906 D WifiService: setWifiEnabled: true pid=6651, uid=10118
09-06 19:22:41.935  1029  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:22:41.961  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:22:41.961  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:22:41.961  1029  1029 D Ulp_jni : JNI:system_update. Event-4
09-06 19:22:41.963  1029  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 19:22:41.963  1029  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 19:22:41.966  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 19:22:41.966  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:22:41.966  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 19:22:41.966  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:22:41.966  1029  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 19:22:41.966  1029  1523 E WifiHW  : unknown target_country: EU , set to default
09-06 19:22:41.966  1029  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 19:22:41.966  1029  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 19:22:41.966  1029  1523 I WifiUtil: gEnableBmps=1
09-06 19:22:41.987  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:41.995  1029  1100 D Tethering: MasterInitialState.processMessage what=3
09-06 19:22:42.003  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:42.006  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:42.007  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:42.013  1029  1100 D Tethering: MasterInitialState.processMessage what=3
09-06 19:22:42.013  1029  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:42.024  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:42.028  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:42.029  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:22:42.040  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:22:42.046  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:22:42.047  6467  6502 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-06 19:22:42.072  2138  2138 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:42.109  1029  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:42.155  1029  1979 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7054 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-06 19:22:42.167  1029  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:22:42.217  1029  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:42.246  7054  7054 I AppUp4:AppBoxCP: onCreate
,09-06 19:22:42.247  7054  7054 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-06 19:22:42.264  7054  7054 I AppUp4:DB:  setFingerPrint start
09-06 19:22:42.265  7054  7054 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-06 19:22:42.275  7054  7054 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-06 19:22:42.275  7054  7054 I AppUp4:DB:  SDK version = 21
09-06 19:22:42.276  7054  7054 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-06 19:22:42.277  7054  7054 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-06 19:22:42.279  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:22:42.279  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:42.282  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:22:42.282  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 19:22:42.289  7054  7054 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:22:42.335  7054  7054 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:42.335  7054  7054 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:22:42.345  7054  7054 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23e69edd
09-06 19:22:42.345  7054  7054 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:22:42.345  7054  7054 D AppUp4:CustFacade: isPhone : true
09-06 19:22:42.346  7054  7054 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:22:42.346  7054  7054 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-06 19:22:42.347  7054  7054 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-06 19:22:42.348  7054  7073 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-06 19:22:42.348  7054  7073 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-06 19:22:42.348  7054  7073 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-06 19:22:42.351  1029  2015 I ActivityManager: Killing 6154:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-06 19:22:42.386  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:42.386  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:22:42.388  1029  1045 W libprocessgroup: failed to open /acct/uid_10080/pid_6154/cgroup.procs: No such file or directory
09-06 19:22:42.391  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:42.396  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:42.407  4308  7079 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:22:42.420  4308  7080 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:42.420  4308  7080 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:22:42.451  1029  1560 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7082 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 19:22:42.513  7082  7082 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:22:42.513  7082  7082 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:22:42.515  7082  7082 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:22:42.515  7082  7082 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 19:22:42.615  7082  7082 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-06 19:22:42.632  7082  7082 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-06 19:22:42.691  7082  7082 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:22:42.707   312   887 D SoftapController: Softap fwReload - Ok
,09-06 19:22:42.711  1029  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (738ms)
09-06 19:22:42.722  1029  1100 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:22:42.726  1029  1100 D Tethering: InitialState.processMessage what=4
09-06 19:22:42.729   312   887 D CommandListener: Setting iface cfg
,09-06 19:22:42.729   312   887 D CommandListener: Trying to bring down wlan0
09-06 19:22:42.730  1029  1100 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:22:42.731   312   887 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:22:42.733  1029  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 19:22:42.720  7108  7108 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:42.720  7108  7108 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:42.744  7082  7082 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:42.745  7082  7082 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:22:42.764  7108  7108 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:22:42.798  7108  7108 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:22:42.798  7108  7108 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-06 19:22:42.834  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:22:42.834  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:22:42.834  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:22:42.834  1029  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:22:42.834  1029  1523 D WifiMonitor: connecting to supplicant
09-06 19:22:42.836  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:42.837  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-06 19:22:42.837  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 19:22:42.838  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:42.839  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:42.862  7108  7108 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:22:42.879  7082  7082 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:22:42.911  7082  7082 I HubEmail: JNI_OnLoad()
09-06 19:22:42.911  7082  7082 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:22:42.911  7082  7082 I HubEmail: registerNatives()
09-06 19:22:42.911  7082  7082 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:22:42.911  7082  7082 I HubEmail: registerNativeMethods()
09-06 19:22:42.911  7082  7082 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:22:42.911  7082  7082 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-06 19:22:42.922  7108  7108 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-06 19:22:42.923  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:22:42.924  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:42.924  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 19:22:42.926  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-06 19:22:42.930  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:22:42.930  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 19:22:42.931  7082  7121 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:42.932  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-06 19:22:42.933  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:22:42.934  1029  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:22:42.934  1029  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-06 19:22:42.934  1029  7122 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:22:42.935  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:22:42.935  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:22:42.935  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 19:22:42.935  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 19:22:42.935  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:22:42.935  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:22:42.935  6963  7119 W FormManager: Network not available. Please check & try again.
09-06 19:22:42.936  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:42.937  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:42.938  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:42.939  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:42.940  1029  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:22:42.940  1029  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,09-06 19:22:42.942  1029  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 19:22:42.942  1029  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:22:42.943  1029  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-06 19:22:42.983  1029  1560 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7123 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-06 19:22:42.985  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:22:42.985  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:22:42.985  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-06 19:22:42.986  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:42.986  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:42.986  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:42.986  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:42.986  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:22:42.987  1029  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:22:42.988  1029  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-06 19:22:42.988  1029  1523 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:22:42.988  1029  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:22:42.989  1029  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:22:42.991  1925  1925 D WfdService: Waiting for WifiP2p enabling
09-06 19:22:42.991  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:42.993  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:22:42.994  1029  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 19:22:42.994  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:42.994  6963  7120 V FormManager: Network unavailable.
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:42.994  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:22:42.994  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:22:42.994  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:42.998  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:42.998  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:22:42.998  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:42.998  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:43.000  6963  7120 V FormManager: Network unavailable.
09-06 19:22:43.004  1029  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 19:22:43.005  1029  1044 I ActivityManager: Killing 6598:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-06 19:22:43.017  1029  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-06 19:22:43.018  1029  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:22:43.042  1029  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:22:43.042  1029  2016 W libprocessgroup: failed to open /acct/uid_10061/pid_6598/cgroup.procs: No such file or directory
09-06 19:22:43.042  1029  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-06 19:22:43.043  1029  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:22:43.043  1029  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:22:43.044  1029  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:22:43.044  1029  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:22:43.044  1029  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:22:43.044  1029  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:22:43.045  1029  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:22:43.045  1029  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:22:43.046  1029  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:22:43.046  1029  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 19:22:43.046  1029  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:22:43.046  1029  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 19:22:43.047  1029  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 19:22:43.058  1029  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:22:43.058  1029  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-06 19:22:43.059  1029  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,09-06 19:22:43.059  1029  1523 D WifiNative-HAL: Setting external_sim to 1
09-06 19:22:43.059  1925  1925 D WfdsService: Supplicant Connection state is changed : true
09-06 19:22:43.059  1029  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
,09-06 19:22:43.060  1925  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:22:43.060  1925  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:22:43.060  1925  2324 D WfdsMonitor: WfdsMonitorThread create
,09-06 19:22:43.060  1029  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:22:43.060  1029  1523 I WifiNative-HAL: startHal
09-06 19:22:43.060  1029  1523 D wifi    : setting scan oui 0x95316420
,09-06 19:22:43.060  1925  2324 D WfdsMonitor: WFDS Monitor is created and started
,09-06 19:22:43.060  1925  2324 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:22:43.061  1029  1523 D WifiStateMachine: Setting OUI to DA-A1-19
,09-06 19:22:43.061  1029  1523 I WifiNative-HAL: startHal
09-06 19:22:43.061  1029  1523 D wifi    : setting scan oui 0x95316420
09-06 19:22:43.061  1029  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,09-06 19:22:43.062  1925  7141 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:22:43.062  1029  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 19:22:43.062  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,09-06 19:22:43.062  1925  7141 E CtrlSupplicant: Succeed to open control connection
09-06 19:22:43.062  1925  7141 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:22:43.063  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,09-06 19:22:43.063  1925  7141 D WfdsMonitor: Supplicant connection established
09-06 19:22:43.063  1925  2324 D WfdsService: Connected to the supplicant for wfds
09-06 19:22:43.064  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,09-06 19:22:43.064  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:22:43.065  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:22:43.065  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,09-06 19:22:43.065  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:22:43.066  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 19:22:43.066  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:22:43.067  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:22:43.067  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-06 19:22:43.068  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:22:43.068  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:22:43.068  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-06 19:22:43.069  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:22:43.069  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 19:22:43.069  7108  7108 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:22:43.070  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true,
09-06 19:22:43.070  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:22:43.070  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:22:43.071  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-06 19:22:43.072  1029  1523 E WifiNative: : [121,750,035 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 19:22:43.072  1029  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:22:43.073  1029  1523 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:22:43.073  1029  1523 D WifiNative-wlan0: doString: [STATUS]
,09-06 19:22:43.073  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:22:43.073  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:22:43.074  1029  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:22:43.074  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1,
,09-06 19:22:43.074  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:22:43.074  1029  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.077   312   887 D CommandListener: Setting iface cfg
,09-06 19:22:43.077   312   887 D CommandListener: Trying to bring up p2p0
09-06 19:22:43.078  1029  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:22:43.078  1029  1522 D LGWifiP2pService: P2pEnablingState
,09-06 19:22:43.078  1029  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.079  1029  1522 D LGWifiP2pService: P2p socket connection successful
09-06 19:22:43.079  1029  1522 D LGWifiP2pService: P2pEnabledState
,09-06 19:22:43.081  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:22:43.083  1029  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:22:43.083  1925  1925 D WfdsService: WifiP2pState is changed : true
09-06 19:22:43.083  1925  2324 D WfdsService: Receive the WFDS_ENABLE Method
09-06 19:22:43.083  1925  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:22:43.083  1925  2324 D WfdsService: Connected to the supplicant for wfds
,09-06 19:22:43.083  1925  2324 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 19:22:43.084  7108  7108 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 19:22:43.084  1925  2324 D WfdsService: selectPreferredScanChannel [36]
,09-06 19:22:43.084  1925  2324 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 19:22:43.085  1029  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:22:43.086  1029  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,09-06 19:22:43.086  1029  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 19:22:43.087  1029  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-06 19:22:43.087  1029  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:22:43.087  1029  1522 D LGWifiP2pService: before postfix = G3
,09-06 19:22:43.087  1029  1522 D WifiServerServiceExt: postfix byte check : 2
09-06 19:22:43.087  1029  1522 D LGWifiP2pService: after postfix = G3
09-06 19:22:43.087  1029  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-06 19:22:43.087  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:22:43.087  1029  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:22:43.087  1029  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:22:43.088  1029  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:22:43.088  1029  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 19:22:43.088  1029  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
,09-06 19:22:43.088  1029  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:22:43.089  1029  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,09-06 19:22:43.089  1029  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:22:43.090  1029  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 19:22:43.090  1925  1925 D WfdsService: isConnected: false
09-06 19:22:43.091  1029  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:22:43.091  1029  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:22:43.092  1029  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 19:22:43.092  1029  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:22:43.093  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121771  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:22:43.097  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:22:43.097  1029  1029 D RttService: SCAN_AVAILABLE : 3
,09-06 19:22:43.098  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.098  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.098  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:22:43.099  1029  1541 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.099  1029  1541 I WifiNative-HAL: startHal
09-06 19:22:43.099  1029  1541 D wifi    : getting scan capabilities on interface[1] = 0x95316420
09-06 19:22:43.099  1029  1541 D wifi    : failed to get capabilities : -3
09-06 19:22:43.099  1029  1541 E WifiScanningService: could not get scan capabilities
09-06 19:22:43.099  1029  1542 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.100  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.100  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:43.101  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.101  1029  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 19:22:43.101  1029  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 19:22:43.103  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:22:43.103  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:22:43.103  1925  1925 D WfdsService: Update P2p Interface State: 3
09-06 19:22:43.103  1029  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 19:22:43.103  1029  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 19:22:43.104  1029  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:22:43.104  1029  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:22:43.104  1029  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 19:22:43.104  1029  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-06 19:22:43.106  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121784  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:22:43.106  1029  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 19:22:43.107  1029  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:22:43.107  1029  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:22:43.107  1029  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 19:22:43.114  7108  7108 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:22:43.114  1029  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:22:43.115  1029  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:22:43.115  1029  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:22:43.115  1029  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 19:22:43.115  7108  7108 E wpa_supplicant: disconnect_rssi_lvl: -100
,09-06 19:22:43.116  1029  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 19:22:43.116  1029  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:22:43.116  1029  1522 D LGWifiP2pService: InactiveState
09-06 19:22:43.116  1029  1522 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.116  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.116  1029  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 19:22:43.116  1029  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.117  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.117  1925  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:22:43.118  1029  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:22:43.118  1029  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.118  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.118  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.118  7108  7108 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:22:43.118  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.118  1925  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.119  1029  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:22:43.119  1925  2324 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 19:22:43.119  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.119  1925  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.120  1029  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.121  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.121  1029  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.121  1029  1029 E WifiServerServiceExt: No p2p device connected
09-06 19:22:43.122  1029  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:22:43.123  1029  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:22:43.123  1029  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.123  1029  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.123  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.123  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.123  1029  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.123  1029  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.123  1029  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:22:43.123  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.123  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.123  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 19:22:43.124  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:22:43.125  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.125  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:22:43.125  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.125  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.125  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:22:43.125  7108  7108 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:22:43.125  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.126  1925  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.126  1029  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:22:43.126  1029  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.126  1029  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.126  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.126  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.126  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.126  1029  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:22:43.127  1925  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.127  10,29  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.127  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.127  1029  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:22:43.127  1029  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:22:43.127  1029  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.127  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.127  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:22:43.127  1029  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:22:43.128  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:22:43.128  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:22:43.128  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:22:43.129  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:22:43.129  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:22:43.129  1029  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:22:43.129  1029  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:22:43.129  1029  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:22:43.129  1029  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:22:43.129  1029  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:22:43.130  1029  1523 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:22:43.130  1029  1523 D WifiNative-wlan0: SCAN: returned false
09-06 19:22:43.130  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121809  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:22:43.133  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.133  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:43.133  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.133  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.133  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:22:43.136  7123  7123 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:43.136  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.136  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121814  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:22:43.136  1029  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:22:43.136  7123  7123 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:22:43.137  1029  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:22:43.137  1029  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:22:43.138  1029  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:22:43.138  1029  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:22:43.139  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:43.139  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:22:43.140  7123  7123 D PhoneMonitor: Register our PhoneStateListener
09-06 19:22:43.140  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:43.141  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:22:43.154  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:22:43.156  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:22:43.167  7123  7123 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-06 19:22:43.168  7123  7123 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-06 19:22:43.168  7123  7123 D TelephonyAutoProfiling: [parse] Load xml
09-06 19:22:43.172  7123  7123 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-06 19:22:43.173  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-06 19:22:43.173  7123  7123 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-06 19:22:43.180  7123  7123 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-06 19:22:43.202  1029  1044 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7144 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:22:43.203  1029  1044 I ActivityManager: Killing 6184:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-06 19:22:43.250  1029  1560 W libprocessgroup: failed to open /acct/uid_10097/pid_6184/cgroup.procs: No such file or directory
,09-06 19:22:43.481  1029  1044 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7168 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-06 19:22:43.482  1029  1044 I ActivityManager: Killing 6673:com.lge.eula/1000 (adj 15): empty #17
09-06 19:22:43.531  1029  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_6673/cgroup.procs: No such file or directory
,09-06 19:22:43.572  7108  7108 E wpa_supplicant: USIM:  scard_init function
09-06 19:22:43.573  7108  7108 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-06 19:22:43.578  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,09-06 19:22:43.578  1029  7122 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 19:22:43.578  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 19:22:43.578  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-06 19:22:43.578  1029  7122 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:22:43.578  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:22:43.578  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-06 19:22:43.579  1029  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-06 19:22:43.579  1029  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-06 19:22:43.579  1029  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-06 19:22:43.582  1029  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-06 19:22:43.582  1029  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-06 19:22:43.632  1029  2016 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7185 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:22:43.634  1029  2016 I ActivityManager: Killing 6696:com.lge.bnr/1000 (adj 15): empty #17
09-06 19:22:43.693  7108  7108 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:22:43.699  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:22:43.699  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:22:43.700  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:22:43.700  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:22:43.700  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:22:43.700  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:22:43.703  7108  7108 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:22:43.704  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:22:43.713  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:22:43.713  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 19:22:43.715  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:22:43.715  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:22:43.715  1029  7122 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:22:43.715  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:22:43.715  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:22:43.715  1029  7122 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:22:43.715  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:22:43.716  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:22:43.721  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122400  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:22:43.722  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122401  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:22:43.722  1029  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6696/cgroup.procs: No such file or directory
09-06 19:22:43.723  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122401  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:22:43.723  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122402  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:22:43.724  1029  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122403
09-06 19:22:43.724  1029  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122403
09-06 19:22:43.725  1029  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122404
09-06 19:22:43.726  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122405
09-06 19:22:43.726  1029  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122405
09-06 19:22:43.727  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-06 19:22:43.733  1029  1100 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:22:43.735  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122414  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:22:43.736  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=122415  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:22:43.737  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=122415  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:22:43.737  1029  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122416
09-06 19:22:43.738  1029  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122416
09-06 19:22:43.738  1029  1523 D WifiNative-wlan0: doString: [STATUS]
09-06 19:22:43.739  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:22:43.739  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 19:22:43.740  1029  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:22:43.742  1029  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 19:22:43.743  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.743  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:43.744  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.744  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.744  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.744  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-06 19:22:43.753  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.754  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.754  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:22:43.760  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.760  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.761  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:22:43.764  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.764  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:22:43.765  1029  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 19:22:43.765  1029  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-06 19:22:43.770  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.774  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.774  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.775  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:22:43.775  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.775  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.775  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-06 19:22:43.777  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.777  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:43.778  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.779  1029  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 19:22:43.779  1029  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:22:43.780  1029  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:22:43.780  1029  1529 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:22:43.780  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:22:43.780  1029  1529 D ConnectivityService: NetworkAgent connected
09-06 19:22:43.780  1029  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:22:43.780  1029  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:22:43.786  1029  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:22:43.786  1029  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:22:43.786  1029  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:22:43.786  1029  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:22:43.786  1029  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:22:43.790  7185  7185 I art     : Almond Protected OAT
,09-06 19:22:43.790  1029  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:22:43.791  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.791  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:43.792   312   887 D CommandListener: Setting iface cfg
09-06 19:22:43.794  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.795  1029  1523 E WifiStateMachine: Start Dhcp Watchdog 2
09-06 19:22:43.795  1029  7213 D DhcpStateMachine: StoppedState
09-06 19:22:43.795  1029  7213 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.795  1029  7213 D DhcpStateMachine: WaitBeforeStartState
,09-06 19:22:43.795  1029  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:22:43.796  1029  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:22:43.797  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.797  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:43.797  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:22:43.797  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:43.798  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:22:43.798  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:43.798  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:22:43.799  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:43.799  1029  1029 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-06 19:22:43.799  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.800  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:43.800  1029  1029 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:22:43.800  1029  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122479  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:22:43.801  1029  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122480  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:22:43.801  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122480  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:22:43.802  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:43.802  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:43.803  1029  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:43.803  1029  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:43.804  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:43.804  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:43.805  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:76961] from screen [on:0 period:8781277] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-06 19:22:43.806  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:8781278] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-06 19:22:43.806  1029  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:22:43.811  1029  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-06 19:22:43.812  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.815  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.815  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.816  1029  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.816  1029  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.816  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.817  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.817  1029  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:22:43.818  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
09-06 19:22:43.818  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
09-06 19:22:43.818  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:22:43.819  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:22:43.819  1029  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:22:43.819  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:22:43.820  1029  1523 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:22:43.820  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 19:22:43.820  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 19:22:43.820  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:22:43.821  1029  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:22:43.821  1029  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:22:43.821  1029  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35faff37 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.821  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35faff37 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.821  1029  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:22:43.821  1029  7213 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.821  1029  7213 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 19:22:43.822   312   887 D CommandListener: Setting iface cfg
09-06 19:22:43.822   312   887 D CommandListener: Trying to bring up wlan0
,09-06 19:22:43.823  1029  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:22:43.824  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.824  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:43.824  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-06 19:22:43.824  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.825  1029  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.825  1029  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.825  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.826  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:43.827  1029  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false,
09-06 19:22:43.827  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:22:43.828  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:22:43.828  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:22:43.828  1029  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.828  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.828  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:22:43.828  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:22:43.828  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:22:43.829  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:22:43.829  1029  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:22:43.829  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:22:43.845  7185  7185 D WeatherApplication: removeAccount
,09-06 19:22:43.846  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:22:43.846  7185  7185 D WeatherApplication: Account.length = 0
09-06 19:22:43.846  7185  7185 E WeatherApplication: OPERATOR:OPEN
,09-06 19:22:43.846  1029  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:22:43.847  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:22:43.847  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-06 19:22:43.847  1029  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:22:43.848  1029  1529 D ConnectivityService: ignoring duplicate network state non-change
,09-06 19:22:43.850  7185  7185 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:43
09-06 19:22:43.852  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.852  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:43.854  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.856  7185  7185 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:22:43.856  7185  7185 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:22:43.858  7185  7185 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:22:43.858  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.858  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.858  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:22:43.860  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:22:43.860  1029  1529 D ConnectivityService: Adding iface wlan0 to network 101
09-06 19:22:43.860  7185  7185 D WeatherAncestor: connectivity changed - connection : true
,09-06 19:22:43.861  7185  7185 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-06 19:22:43.869  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.870  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.870  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:22:43.871  1029  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:22:43.872  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:22:43.875  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 19:22:43.875  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.875  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:22:43.877  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.877  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.877  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:22:43.878  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.878  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:22:43.881  7185  7185 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:22:43.881  7185  7185 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:22:43.881  7185  7185 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-06 19:22:43.882  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.882  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:22:43.882  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.882  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.882  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:43.882  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:22:43.888  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:43.888  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:22:43.888  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:43.895  1029  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:22:43.896  1029  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-06 19:22:43.898  1029  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-06 19:22:43.899   312   887 E Netd    : netlink response contains error (File exists)
09-06 19:22:43.900  1029  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-06 19:22:43.900  1029  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:22:43.900  1029  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,09-06 19:22:43.900  1029  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-06 19:22:43.901  1029  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:22:43.901  1029  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:22:43.901  1029  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-06 19:22:43.902  1029  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 19:22:43.902  1029  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:22:43.902  1029  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:43.902  1029  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:22:43.902  1029  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:43.902  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.902  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:22:43.902  1029  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:22:43.902  1029  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:22:43.902  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.902  1029  1529 D ConnectivityService:    accepting network in place of null
09-06 19:22:43.902  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:22:43.902  1029  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:43.903  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:43.903  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:22:43.903  1029  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:43.903  1029  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:22:43.904  1029  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:22:43.904  1029  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [W,IFI () - 101] isDefaultNetwork=true
09-06 19:22:43.904  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:22:43.906  1029  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:43.906  1029  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:22:43.906  1029  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:22:43.907  1029  1029 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:22:43.908  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:22:43.908  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:22:43.908  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-06 19:22:43.910  1029  1529 D ConnectivityService: validation of new default Network = false
09-06 19:22:43.911   312  7220 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-06 19:22:43.911   312  7220 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-06 19:22:43.913  1029  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:22:43.913  1029  1529 D DSQN    : enableDataServiceNotify 
09-06 19:22:43.913  1029  1529 D DSQN    : start dsqn bin
09-06 19:22:43.920  7185  7185 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-06 19:22:43.920  7185  7185 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:43
09-06 19:22:43.921  1029  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 19:22:43.921  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:43.921  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:43.921  1029  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:43.910  7221  7221 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:22:43.910  7221  7221 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:43.925  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:22:43.937  7221  7221 E DSQN    : DSQN ssw
09-06 19:22:43.937  1029  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:43.937  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:22:43.937  1029  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:22:43.961  1029  2016 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7226 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:22:43.962  1029  2016 I ActivityManager: Killing 2109:com.lge.music/u0a34 (adj 15): empty #17
,09-06 19:22:43.969   312  7220 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 19:22:43.977   318  1366 V AudioFlinger: 2109 died, releasing its sessions
09-06 19:22:43.977   318  1366 V AudioFlinger:  pid 1836 @ 0
09-06 19:22:43.977   318  1366 V AudioFlinger:  pid 3407 @ 1
09-06 19:22:43.977   318  1366 V AudioFlinger:  pid 3407 @ 2
,09-06 19:22:43.981  1029  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:22:43.981  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:22:43.981  1029  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:22:43.982  1029  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:22:43.982  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:22:43.982  1029  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:22:44.002   312   886 D LGDataListener: argv[0]=dsqncommand
,09-06 19:22:44.002   312   886 D LGDataListener: argv[1]=wlan0
09-06 19:22:44.002   312   886 D LGDataListener: argv[2]=1
09-06 19:22:44.002   312   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,09-06 19:22:44.003  1029  1098 D DSQN    : DSQM DsqnNotification wlan0  1
09-06 19:22:44.003  1029  1098 D DSQN    : start to monitor internet connection
09-06 19:22:44.018  1029  2034 W libprocessgroup: failed to open /acct/uid_10034/pid_2109/cgroup.procs: No such file or directory
09-06 19:22:44.018  1801  7223 I CheckinService: active receiver: enabled
,09-06 19:22:44.023  1029  7213 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 19:22:44.023  1029  7213 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 19:22:44.023  1029  7213 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 19:22:44.010  7246  7246 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:44.010  7246  7246 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:44.036  1801  7223 I CheckinService: Preparing to send checkin request
09-06 19:22:44.036  1801  7223 I EventLogService: Accumulating logs since 1473182499221
,09-06 19:22:44.039  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:22:44 GMT], X-Android-Received-Millis=[1473182564036], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473182564002]}
09-06 19:22:44.042  1029  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-06 19:22:44.047  7246  7246 I dhcpcd  : version 5.5.6 starting
09-06 19:22:44.049  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 19:22:44.050  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-06 19:22:44.050  1029  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-06 19:22:44.050  1029  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 19:22:44.050  1029  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:22:44.050  1029  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:44.050  1029  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:22:44.050  1029  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-06 19:22:44.050  7246  7246 E dhcpcd  : get_duid: m
09-06 19:22:44.050  7246  7246 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:22:44.050  7246  7246 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 19:22:44.050  1029  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 19:22:44.050  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:44.050  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:44.051  1029  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:44.051  1029  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:44.051  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:22:44.052  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:22:44.052  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:22:44.053  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:22:44.054  1029  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:44.054  1029  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:22:44.062  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:22:44.063  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:44.063  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:22:44.097  1801  7223 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-06 19:22:44.105  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:22:44.105  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:44.106  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:22:44.119  7246  7246 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-06 19:22:44.132  7246  7246 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:22:44.132  7246  7246 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:22:44.132  7246  7246 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-06 19:22:44.133  7246  7246 D dhcpcd  : wlan0: sending REQUEST (xid 0xd236fa91), next in 3.09 seconds
09-06 19:22:44.138   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:22:44.138   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:22:44.138   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:22:44.138  7226  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 19:22:44.144   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:22:44.144   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:22:44.144   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:22:44.144  7226  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-06 19:22:44.147   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:22:44.147   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:22:44.147   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:22:44.147  7226  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 19:22:44.149   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:22:44.149   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:22:44.149   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:22:44.149  7226  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-06 19:22:44.172  7246  7246 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-06 19:22:44.214  7246  7246 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:22:44.214  7246  7246 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 19:22:44.215  7246  7246 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:22:44.215  7246  7246 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 19:22:44.216  7246  7246 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:22:44.216  7246  7246 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:22:44.216  7246  7246 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:22:44.217  7246  7246 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-06 19:22:44.223  1029  2015 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7261 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-06 19:22:44.249   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 480us total 26.280ms
,09-06 19:22:44.271   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 20.130ms
,09-06 19:22:44.290   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 17.818ms
,09-06 19:22:44.298  7261  7261 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 19:22:44.298  7261  7261 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-06 19:22:44.322  7261  7261 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:22:44.322  7261  7261 I MultiDex: install
09-06 19:22:44.322  7261  7261 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:22:44.331  7261  7261 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-06 19:22:44.394  7226  7226 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 19:22:44.406  7226  7226 I LibraryLoader: Loading: webviewchromium
09-06 19:22:44.409  7226  7226 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3095-3099)
,09-06 19:22:44.409  7226  7226 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:22:44.414  7226  7226 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6ac387c}
09-06 19:22:44.415  7226  7226 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:22:44.415  7226  7226 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:22:44.426  1029  7213 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-06 19:22:44.426  1029  7213 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 19:22:44.426  1029  7213 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:22:44.426  1029  7213 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:22:44.426  1029  7213 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 19:22:44.427  1029  7213 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:22:44.427  1029  7213 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:22:44.427  1029  7213 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,09-06 19:22:44.427  1029  7213 D DhcpStateMachine: RunningState
,09-06 19:22:44.428  7226  7226 I BrowserStartupController: Initializing chromium process, renderers=0
09-06 19:22:44.430  7226  7226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:22:44.446   318  1367 V AudioPolicyService: registerClient() client 0xb04102a0, uid 10093
,09-06 19:22:44.448  7226  7318 W AudioManagerAndroid: Requires BLUETOOTH permission
09-06 19:22:44.459  7226  7226 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 19:22:44.459  7226  7226 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-06 19:22:44.459  7226  7226 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-06 19:22:44.491  7226  7226 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:22:44.491  7226  7226 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:22:44.491  7226  7226 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:22:44.491  7226  7226 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:22:44.491  7226  7226 I Adreno-EGL: Remote Branch: 
09-06 19:22:44.491  7226  7226 I Adreno-EGL: Local Patches: 
09-06 19:22:44.491  7226  7226 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:22:44.592  7226  7226 I NSApplication: Starting up...
,09-06 19:22:44.643  7331  7331 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 19:22:44.657  1029  1906 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7334 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:22:44.657  1029  1906 I ActivityManager: Killing 6115:com.android.vending/u0a44 (adj 15): empty #17
,09-06 19:22:44.687  7331  7331 I dex2oat : dex2oat took 44.148ms (threads: 4)
,09-06 19:22:44.702  7261  7281 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:22:44.702  7261  7281 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:22:44.702  7261  7281 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:22:44.702  7261  7281 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:22:44.702  7261  7281 I Adreno-EGL: Remote Branch: 
09-06 19:22:44.702  7261  7281 I Adreno-EGL: Local Patches: 
09-06 19:22:44.702  7261  7281 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:22:44.730  1029  1560 W libprocessgroup: failed to open /acct/uid_10044/pid_6115/cgroup.procs: No such file or directory
,09-06 19:22:44.757  7334  7334 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:22:44.911  1029  1942 I art     : Explicit concurrent mark sweep GC freed 98216(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.303ms total 81.517ms
,09-06 19:22:44.926  1029  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-06 19:22:44.965  1029  1906 D WifiServiceImplEx: setWifiEnabled: false pid=6651, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:22:44.965  1029  1906 D WifiService: setWifiEnabled: false pid=6651, uid=10118
09-06 19:22:44.965  1029  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:22:44.976  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:22:44.976  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:22:44.977  1029  1029 D Ulp_jni : JNI:system_update. Event-4
09-06 19:22:44.979  1029  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:44.980  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:44.981  1029  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,09-06 19:22:44.982  1029  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:44.983  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:22:44.984  1029  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:22:44.984  1029  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:22:44.984  1029  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:22:44.988  1029  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:22:44.988  1029  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:22:44.994  1029  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:22:44.994  1029  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:44.994  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:44.995  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:22:44.995  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:22:44.995  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:22:44.995  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:22:44.996  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:22:44.996   312   887 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:22:44.996  1029  7213 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:22:45.007  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:22:45.007  6467  6502 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:22:45.032  2138  2138 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:45.041   312  7372 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:22:45.043  1029  1045 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-06 19:22:45.045  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.045  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.045  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:22:45.045  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.045  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:22:45.048  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.ConnectException: failed to connect to clients3.google.com/172.217.21.46 (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-06 19:22:45.049  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:22:45.049  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:45.049  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:22:45.049  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:22:45.051  1029  1098 D DSQN    : Dns fail occured do internet check.
09-06 19:22:45.052  1029  1029 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-06 19:22:45.053  1029  1029 D DSQN    : try Internet connection check
09-06 19:22:45.053  1029  1029 D WifiHS20: hidePasspointNotification off =false
09-06 19:22:45.054  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.054  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.054  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:22:45.054  1029  1529 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:22:45.054  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-06 19:22:45.056  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:45.056  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:45.056  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 19:22:45.057  1029  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:45.057  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.058  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:45.058  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:45.058  1029  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:45.059  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:45.059  1029  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.060  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.060  1029  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@16d80ac3
09-06 19:22:45.060  1029  1522 D LGWifiP2pService: P2pDisablingState
09-06 19:22:45.060  1029  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.060  1029  1522 D LGWifiP2pService: p2p socket connection lost
09-06 19:22:45.060  1029  1522 D LGWifiP2pService: P2pDisabledState
09-06 19:22:45.063  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:22:45.063  1925  1925 D WfdsService: WifiP2pState is changed : false
,09-06 19:22:45.066  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:22:45.066  1925  2324 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:22:45.066  1925  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:22:45.066  1029  1029 D WifiHS20: hidePasspointNotification off =false
09-06 19:22:45.067  1925  2324 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:22:45.067  1925  2324 D WfdsService: STATE : WfdsDisabledState - enter
09-06 19:22:45.067  1925  7141 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:22:45.067  1925  7141 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:22:45.067  1925  7141 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:22:45.067  1925  7141 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:22:45.068  1925  2326 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:22:45.068  1925  2324 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 19:22:45.068  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.068  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.068  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:22:45.068  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:22:45.069  1029  1029 D RttService: SCAN_AVAILABLE : 1
09-06 19:22:45.069  1029  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.069  1029  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.072  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:22:45.072  1029  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:22:45.073  1029  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:22:45.073  1029  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.073  1029  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.073  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:22:45.074  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:22:45.074  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:22:45.074  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:22:45.074  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:22:45.076  7054  7054 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:22:45.077  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:45.077  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:45.080  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.080  7261  7281 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:45.081  7261  7281 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:22:45.095  7054  7054 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23e69edd
09-06 19:22:45.095  7054  7054 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:22:45.095  7054  7054 D AppUp4:CustFacade: isPhone : true
09-06 19:22:45.096  7054  7054 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:22:45.096  7054  7054 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:22:45.098  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:45.099  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:22:45.100  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:45.101   312   887 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:22:45.102  1029  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:22:45.102  1029  1529 D DSQN    : disableDataServiceNotify
09-06 19:22:45.102  1029  1529 D DSQN    : stop dsqn bin
,09-06 19:22:45.102   312  7380 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:22:45.102  1029  7375 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
09-06 19:22:45.103  1029  1098 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:22:45.103  1029  7373 D DSQN    : ThreadInternetCheck internet check NOK 
09-06 19:22:45.103  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:45.103  1029  7373 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
09-06 19:22:45.105  1029  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 19:22:45.105  1029  1029 D WifiHS20: hidePasspointNotification off =false
09-06 19:22:45.106  1029  1523 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:22:45.106  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:22:45.106  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:22:45.106  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:22:45.106  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:22:45.106  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:22:45.107  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.108  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.108  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.108  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:22:45.108  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 19:22:45.110  4308  7382 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:22:45.110  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:45.110  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:45.110  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:45.110  1029  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 19:22:45.110  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: ,BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:45.110  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:45.110  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:45.111  1029  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:22:45.111  1029  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:22:45.111  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.111  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.111  1029  7212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:22:45.111  1029  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:22:45.111  1029  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:22:45.111  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:22:45.111  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:45.111  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:45.111  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:22:45.111  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:45.111  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:45.111  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:22:45.112  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:22:45.112  1029  1029 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-0,6 19:22:45.112  1029  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:45.112  1029  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:22:45.112  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:22:45.113  1029  1029 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:22:45.113  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:22:45.113  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:22:45.113  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:22:45.114  1029  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:45.114  1029  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:45.114  1029  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:45.114  1029  1529 D NetworkManagementService: Removing idletimer
09-06 19:22:45.114  1029  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:22:45.114  1029  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.115  1029  1029 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:22:45.116  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:22:45.116  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:22:45.116  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:22:45.116  1029  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:45.116  1029  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:22:45.117  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:22:45.117  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:22:45.125  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:22:45.138  7082  7082 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:22:45.140  4308  7383 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:45.140  4308  7383 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:22:45.159  7082  7389 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:22:45.164  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:22:45.164  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.165  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.168  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:22:45.168  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:45.168  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:22:45.169  6963  7391 W FormManager: Network not available. Please check & try again.
09-06 19:22:45.170  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:22:45.170  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:22:45.176  6963  7392 V FormManager: Network unavailable.
,09-06 19:22:45.180  7185  7185 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:45
09-06 19:22:45.182  6963  7392 V FormManager: Network unavailable.
09-06 19:22:45.183  7185  7185 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:22:45.183  7185  7185 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:22:45.183  7185  7185 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:22:45.183  7185  7185 D WeatherAncestor: connectivity changed - connection : true
09-06 19:22:45.183  7185  7185 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ade3123
09-06 19:22:45.184  7185  7185 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:22:45.184  7185  7185 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:22:45.184  7185  7185 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:22:45.184  7185  7185 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:22:45.184  7185  7185 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:45
,09-06 19:22:45.202  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:22:45.207  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.208  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.212  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:22:45.212  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:22:45.212  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:22:45.212  6855  6855 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:22:45.212  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:22:45.213  6855  6855 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:22:45.213  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:22:45.213  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:22:45.213  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:22:45.213  6855  6855 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:22:45.213  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:22:45.213  6855  6855 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-06 19:22:45.219  1029  7213 D DhcpStateMachine: StoppedState
09-06 19:22:45.219  1029  7213 D DhcpStateMachine: StoppedState{ when=-144ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:22:45.219  1029  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:22:45.219  1029  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 19:22:45.220  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:22:45.220  7108  7108 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:22:45.221  7108  7108 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
09-06 19:22:45.221  1029  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:22:45.221  1029  7122 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:22:45.224  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:22:45.227  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:22:45.232  6963  7397 V FormManager: Network unavailable.
09-06 19:22:45.233  6963  7396 W FormManager: Network not available. Please check & try again.
09-06 19:22:45.233  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.236  6963  7397 V FormManager: Network unavailable.
,09-06 19:22:45.246  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:45.248  7261  7281 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:22:45.248  7261  7281 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:22:45.248  7261  7281 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:22:45.248  7261  7281 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:22:45.248  7261  7281 I Adreno-EGL: Remote Branch: 
09-06 19:22:45.248  7261  7281 I Adreno-EGL: Local Patches: 
09-06 19:22:45.248  7261  7281 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:22:45.250  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:22:45.251  6963  7399 W FormManager: Network not available. Please check & try again.
09-06 19:22:45.253  6963  7400 V FormManager: Network unavailable.
09-06 19:22:45.254  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.259  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:22:45.260  7108  7108 W wpa_supplicant: USIM:  scard_deinit function
,09-06 19:22:45.260  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-06 19:22:45.260  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:22:45.261  1029  1100 D Tethering: InitialState.processMessage what=4
09-06 19:22:45.261  1029  7122 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:22:45.261  1029  7122 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:22:45.261  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:22:45.261  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:22:45.262  1029  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123941
09-06 19:22:45.262  6963  7400 V FormManager: Network unavailable.
09-06 19:22:45.263  1029  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123941
09-06 19:22:45.263  1029  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123942  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:22:45.264  1029  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123942  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:22:45.264  1029  1100 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:22:45.266  1029  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:45.267  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:22:45.270  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:22:45.271  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:22:45.272  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:22:45.274  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:45.276  4308  7402 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:22:45.278  4308  7403 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:22:45.278  4308  7403 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:22:45.289  7261  7281 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:22:45.289  7261  7281 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:22:45.289  7261  7281 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:22:45.289  7261  7281 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:22:45.289  7261  7281 I Adreno-EGL: Remote Branch: 
09-06 19:22:45.289  7261  7281 I Adreno-EGL: Local Patches: 
09-06 19:22:45.289  7261  7281 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:22:45.325  1029  2034 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7404 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 19:22:45.371   312  7422 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-06 19:22:45.372  1029  1098 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:22:45.374  1801  7223 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-06 19:22:45.382  1801  7223 I CheckinService: active receiver: disabled
,09-06 19:22:45.391  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:22:45.392  1029  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:22:45.392  1029  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 19:22:45.392  1029  7122 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 19:22:45.393  1029  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,09-06 19:22:45.443  7404  7404 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:22:45.443  7404  7404 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 19:22:45.450  7404  7404 V [BNRBootReceiver]: Boot Receiver Return
09-06 19:22:45.450  7404  7404 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:22:45.456  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.470  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.475  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.486  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:22:45.486  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.487  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:22:45.491  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.497  1029  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 19:22:45.497  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:22:45.497  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:22:45.497  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:22:45.497  1925  1925 D WfdsService: Supplicant Connection state is changed : false
09-06 19:22:45.498  1925  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:22:45.498  1925  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:22:45.498  1925  2324 D WfdsMonitor: WFDS Monitor is stopped
,09-06 19:22:45.501  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:22:45.506  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:22:45.506  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:45.506  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:22:45.507  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:22:45.508  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 19:22:45.508  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:45.508  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:22:45.509  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:45.509  1029  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:22:45.509  1029  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,09-06 19:22:45.510  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.517  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.518  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.519  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:22:45.522  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-06 19:22:45.526  6855  6855 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-06 19:22:45.529  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.536  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.545  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.552  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.552  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.553  6919  6919 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:22:45.556  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.563  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.570  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:22:45.578  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.578  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.579  6919  6919 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:22:45.582  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:22:45.599  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.606  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.615  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.616  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:22:45.617  6769  7040 D UEI.SmartControl: Internal timer expired: 4
,09-06 19:22:45.617  6769  7040 D UEI.SmartControl: unbind internal service
09-06 19:22:45.617  6919  6919 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:22:45.625  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.643  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.648  6769  7034 D serial_port: close(fd = 24)
09-06 19:22:45.651  6769  7034 I UEI.SmartControl: Serial port is closed.
09-06 19:22:45.655  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.665  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.666  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.666  6919  6919 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:22:45.672  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.683  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.692  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:22:45.702  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:22:45.703  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.704  6919  6919 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:22:45.717  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:22:45.742  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.752  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.762  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.762  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.768  6919  6919 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:22:45.773  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.787  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.797  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.808  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:22:45.809  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.810  6919  6919 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:22:45.816  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.822  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 19:22:45.835  1029  1528 D WifiService: New client listening to asynchronous messages
,09-06 19:22:45.836  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:45.843  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.854  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:45.868  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.868  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:22:45.870  6919  6919 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-06 19:22:45.871  6919  6919 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:22:45.872  6919  6919 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:22:45.881  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:45.886  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 19:22:45.889  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:45.896  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:45.906  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:22:45.918  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:45.919  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:45.921  6919  6919 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-06 19:22:45.923  6919  6919 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-06 19:22:45.924  6919  6919 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:22:45.930  1029  1715 I ActivityManager: Killing 6897:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-06 19:22:46.014  1029  1961 W libprocessgroup: failed to open /acct/uid_10037/pid_6897/cgroup.procs: No such file or directory
,09-06 19:22:46.031  2138  2138 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-06 19:22:46.053  2138  2138 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-06 19:22:46.054  2138  2138 D c       : Getting all permits...
09-06 19:22:46.054  2138  2138 D a       : Opening database...
,09-06 19:22:46.062  2138  2138 D a       : Opening database auth.proximity.permit_store...
09-06 19:22:46.063  2138  2138 D a       : Closing database...
,09-06 19:22:46.076  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:22:46.083  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:22:46.083  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:22:46.083  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:46.087  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:46.096  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:46.103  1029  1029 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,09-06 19:22:46.104  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:46.105  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:46.107  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:22:46.113  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:22:46.119  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:22:46.119  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:22:46.119  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:22:46.127  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:46.134  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:22:46.142  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:46.142  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:46.144  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:22:46.148  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:22:46.154  6876  6876 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:22:46.154  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:22:46.154  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:46.158  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:22:46.164  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:46.172  6919  6919 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:22:46.173  6919  6919 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:22:46.175  6919  6919 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:22:46.187  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:46.192  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:22:46.202  6963  7431 W FormManager: Network not available. Please check & try again.
,09-06 19:22:46.202  6963  7432 V FormManager: Network unavailable.
09-06 19:22:46.205  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:46.205  6963  7432 V FormManager: Network unavailable.
09-06 19:22:46.226  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:22:46.227  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:22:46.227  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:22:46.227  6855  6855 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:22:46.227  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:22:46.228  6855  6855 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:22:46.229  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:22:46.229  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:22:46.229  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:22:46.229  6855  6855 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:22:46.229  6855  6855 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-06 19:22:46.236  2138  2138 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-06 19:22:46.259  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-06 19:22:46.260  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:22:46.262  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:22:46.266  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:46.274  4308  7433 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:22:46.275  4308  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:22:46.276  4308  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:22:46.282  6876  6876 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 19:22:46.282  6876  6876 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:22:46.282  6876  6876 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:22:46.288  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:22:46.300  6963  7436 W FormManager: Network not available. Please check & try again.
09-06 19:22:46.301  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:22:46.309  6963  7437 V FormManager: Network unavailable.
,09-06 19:22:46.319  6963  7437 V FormManager: Network unavailable.
,09-06 19:22:46.814  1029  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:8784286] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 19:22:46.817  1029  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:8784288] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 19:22:46.908  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:46.921  1029  1100 D Tethering: MasterInitialState.processMessage what=3
09-06 19:22:46.929  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:46.934  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:46.938  1029  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:46.940  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:22:46.942  6467  6502 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:22:46.951  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:22:46.971  2138  2138 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:46.991  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:22:46.991  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:46.991  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:22:46.991  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 19:22:46.995  7054  7054 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:22:46.999  7054  7054 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23e69edd
09-06 19:22:46.999  7054  7054 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:22:47.000  7054  7054 D AppUp4:CustFacade: isPhone : true
09-06 19:22:47.000  7054  7054 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:22:47.000  7054  7054 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:22:47.005  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:47.005  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:22:47.006  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:22:47.012  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:47.020  7082  7082 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:22:47.050  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:22:47.050  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:47.051  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = true
09-06 19:22:47.051  3407  3407 D PhoneState: setPdpRejectCasuse : false
,09-06 19:22:47.056  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:22:47.056  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:22:47.072  4308  7454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:22:47.072  1029  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:22:47.078  4308  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:47.078  4308  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:22:47.081  7185  7185 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:47
09-06 19:22:47.081  7082  7453 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:47.083  7185  7185 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:22:47.083  7185  7185 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:22:47.084  7185  7185 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:22:47.084  7185  7185 D WeatherAncestor: connectivity changed - connection : true
09-06 19:22:47.084  7185  7185 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ade3123
09-06 19:22:47.085  7185  7185 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:22:47.085  7185  7185 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:22:47.085  7185  7185 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:22:47.085  7185  7185 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:22:47.085  7185  7185 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:47
,09-06 19:22:47.098  6963  7469 W FormManager: Network not available. Please check & try again.
09-06 19:22:47.104  6963  7472 V FormManager: Network unavailable.
,09-06 19:22:47.111  6963  7472 V FormManager: Network unavailable.
,09-06 19:22:47.976  1029  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:22:47.977  1029  1871 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 19:22:48.006  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:22:48.007  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:22:48.007  1029  1029 D Ulp_jni : JNI:system_update. Event-4
,09-06 19:22:48.010  1029  1100 D BluetoothManagerService: Message: 1
09-06 19:22:48.010  1029  1100 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-06 19:22:48.040  1029  1100 D BluetoothManagerService: Message: 20
09-06 19:22:48.040  1029  1100 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33318f93:true
,09-06 19:22:48.044  7015  7015 D BluetoothAdapterState: make
09-06 19:22:48.048  7015  7015 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:22:48.048  7015  7015 I bluedroid-qcom: init
09-06 19:22:48.049  7015  7485 I BluetoothAdapterState: Entering OffState
09-06 19:22:48.050  7015  7015 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:22:48.051  7015  7015 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:22:48.051  7015  7015 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:22:48.051  7015  7015 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:22:48.051  7015  7015 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:22:48.053  7015  7015 I bluedroid-qcom: get_profile_interface socket
09-06 19:22:48.053  7015  7015 I bluedroid-qcom: get_profile_interface map_client
,09-06 19:22:48.050  7488  7488 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:48.050  7488  7488 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:48.067  7488  7488 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:22:48.067  7488  7488 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:22:48.067  7488  7488 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-06 19:22:48.071  7015  7489 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:22:48.074  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 19:22:48.074  1029  1100 D BluetoothManagerService: Message: 40
09-06 19:22:48.074  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 19:22:48.075  7015  7031 I bluedroid-qcom: config_hci_snoop_log
09-06 19:22:48.076  1029  1100 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:22:48.077  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:22:48.082  7488  7488 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-06 19:22:48.090  7488  7488 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:22:48.091  7488  7488 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 19:22:48.100  7015  7485 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 19:22:48.100  7015  7485 D BluetoothAdapterProperties: Setting state to 11
09-06 19:22:48.100  7015  7485 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-06 19:22:48.104  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:48.104  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:22:48.104  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 19:22:48.109  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:48.110  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:48.120  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:48.133  6855  6855 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-06 19:22:48.140  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:48.144  7015  7485 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 19:22:48.144  7015  7489 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 19:22:48.153  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.155  7015  7489 D BluetoothAdapterProperties: Name is: G3
09-06 19:22:48.157  1029  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.158  1029  1100 D Tethering: MasterInitialState.processMessage what=3
09-06 19:22:48.161  1029  1100 D Tethering: MasterInitialState.processMessage what=3
09-06 19:22:48.167  7015  7485 D BluetoothBondStateMachine: make
,09-06 19:22:48.168  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:48.170  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:48.172  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:22:48.172  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:48.172  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:22:48.172  7015  7508 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 19:22:48.172  7015  7485 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.173  7015  7485 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:22:48.173  7015  7485 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.173  7015  7485 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,09-06 19:22:48.174  7015  7485 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 19:22:48.174  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:48.175  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:48.181  7015  7015 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:22:48.181  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:22:48.182  7015  7015 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:48.182  7015  7015 V BluetoothPbapReceiver: ***********state = 11
,09-06 19:22:48.182  6467  6502 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:22:48.184  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:22:48.188  7015  7485 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:48.192  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:22:48.195  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:22:48.201  7015  7015 D HeadsetService: Received start request. Starting profile...
09-06 19:22:48.201  7015  7485 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:48.202  7015  7015 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:22:48.202  7015  7015 D LGBluetoothHfpAdapter: Version 1.6
09-06 19:22:48.205  7015  7015 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:22:48.206  7015  7015 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:22:48.207  7015  7015 D HeadsetStateMachine: make
09-06 19:22:48.240  1029  1720 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7510 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-06 19:22:48.244  7015  7015 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:48.244  7015  7015 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:22:48.246  7015  7485 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:48.249  1029  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.249  7015  7015 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:22:48.249  7015  7015 I bluedroid-qcom: get_profile_interface handsfree
09-06 19:22:48.251  7015  7015 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 19:22:48.251   318  1366 V AudioPolicyService: registerClient() client 0xb558a720, uid 1002
09-06 19:22:48.252   318  1367 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:22:48.252   318  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:22:48.252   318  1367 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:22:48.252  7015  7485 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:48.252  7015  7015 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:22:48.252   318   318 V AudioFlinger: registerClient() client 0xb1433100, pid 7015
09-06 19:22:48.253   318  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:48.253  7015  7015 V ToneGenerator: Create Track: 0xb4928a80
09-06 19:22:48.253   318  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:48.253  7015  7015 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:22:48.253  7015  7015 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:22:48.253   318  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:22:48.253   318  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:22:48.253   318  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:22:48.253   318  1366 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:22:48.253  7015  7015 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:22:48.253  7015  7030 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:48.253  7015  7030 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:22:48.254  1029  1906 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:48.254  1029  1906 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:48.254   318  1366 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:22:48.254   318  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:22:48.254   318  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:22:48.254   318  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:22:48.254   318  1366 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:22:48.255  1587  2063 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:48.255  1587  2063 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-06 19:22:48.255  1836  2582 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:48.255  1836  2582 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:48.255  3407  3423 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:48.256  3407  3423 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:48.258   318  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:48.258   318  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:48.258  1029  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:48.258  7015  7015 V AudioSystem: getLatency() output 2, latency 50
09-06 19:22:48.258  1587  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:48.258  1029  1870 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:48.258  1587  1606 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:48.259  7015  7015 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:22:48.259  7015  7015 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:22:48.259  7015  7015 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:22:48.259  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:48.259  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:48.259  3407  3424 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:48.259  3407  3424 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:48.259  7015  7031 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:48.259  7015  7031 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:22:48.259   318  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:22:48.259   318  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:22:48.259   318  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:22:48.259   318  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:22:48.259   318  1367 V AudioFlinger: createTrack() lSessionId: 22
09-06 19:22:48.260  7015  7015 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:22:48.261   318  1366 V AudioFlinger: acquiring 22 from 7015, for 7015
09-06 19:22:48.261   318  1366 V AudioFlinger:  added new entry for 22
09-06 19:22:48.261  7015  7015 V ToneGenerator: ToneGenerator INIT OK, time: 126951
09-06 19:22:48.261  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.261  7015  7509 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:22:48.261  2138  2138 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.261  7015  7509 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:22:48.262  7015  7509 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:22:48.262  7015  7509 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:22:48.266  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.266   318  2154 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7015
09-06 19:22:48.266   318  2154 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:22:48.266   318  2154 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:22:48.266   318  2154 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_,samplerate=8000
09-06 19:22:48.266   318  2154 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 19:22:48.266   318  2154 V voice   : voice_set_parameters: exit with code(0)
09-06 19:22:48.266   318  2154 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:22:48.266   318  2154 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 19:22:48.266   318  2154 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:22:48.266   318  2154 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:22:48.266   318  2154 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:22:48.266   318  2154 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:22:48.267  7015  7509 V ToneGenerator: ToneGenerator destructor
09-06 19:22:48.267  7015  7509 V ToneGenerator: stopTone
09-06 19:22:48.267  7015  7509 V ToneGenerator: Delete Track: 0xb4928a80
09-06 19:22:48.267  7015  7509 V AudioTrack: ~AudioTrack, releasing session id from 7015 on behalf of 7015
09-06 19:22:48.267   318  1367 V AudioFlinger: releasing 22 from 7015 for 7015
09-06 19:22:48.267   318  1367 V AudioFlinger:  decremented refcount to 0
09-06 19:22:48.267   318  1367 V AudioFlinger: purging stale effects
09-06 19:22:48.267  7015  7015 D A2dpService: Received start request. Starting profile...
09-06 19:22:48.267   318  1367 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 19:22:48.267   318  1367 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:22:48.267   318  1256 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:22:48.267   318  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:22:48.267   318  1256 V AudioPolicyManager: releaseOutput() 2
09-06 19:22:48.267   318  1256 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 19:22:48.267   318  1367 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:22:48.267   318  1367 V AudioFlinger: removeClient_l() pid 7015, calling pid 318
09-06 19:22:48.268  7015  7015 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:22:48.268  7015  7015 V Avrcp   : make
09-06 19:22:48.269  7015  7015 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:22:48.269  7015  7015 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:22:48.269  1029  1960 W Process : Unable to open /proc/7523/status
09-06 19:22:48.279  7015  7485 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:48.283  7015  7015 V AudioManager: registerRemoteController: size of Media player list: 0
09-06 19:22:48.284  7015  7015 E AudioManager: No RCC entry present to update
09-06 19:22:48.284  7015  7015 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:22:48.285  7015  7485 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:48.287  7015  7015 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 19:22:48.287  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:22:48.287  7015  7015 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 19:22:48.295  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:22:48.296  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-06 19:22:48.296  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.296  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:22:48.296  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:22:48.296  7015  7485 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:48.300  1029  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:48.301  1029  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:22:48.331  7054  7054 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:22:48.333  7054  7054 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23e69edd
09-06 19:22:48.333  7054  7054 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:22:48.333  7054  7054 D AppUp4:CustFacade: isPhone : true
09-06 19:22:48.333  7054  7054 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:22:48.334  7054  7054 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:22:48.338  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.338  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:22:48.340  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:48.342  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:48.343  7015  7485 V LGMDMManager: Create singleton instance
09-06 19:22:48.344  7015  7485 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:22:48.350  7082  7082 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:22:48.351  4308  7530 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:22:48.353  4308  7531 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.353  4308  7531 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:22:48.373  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:22:48.373  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:22:48.373  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:22:48.374  7510  7510 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:22:48.374  7510  7510 W LG Account v2.2: No ProfileInfo entries
09-06 19:22:48.374  7510  7510 I LG Account v2.2: isEnabled: false
09-06 19:22:48.374  7510  7510 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:22:48.374  7510  7510 I Feature : [Lifetracker]Country: EU
09-06 19:22:48.374  7510  7510 I Feature : [Lifetracker]Operator: OPEN
09-06 19:22:48.374  7510  7510 I Feature : [Lifetracker]Ranking support: false
09-06 19:22:48.374  1029  1560 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:22:48.374  7510  7510 I Feature : [Lifetracker]Comfort support: false
09-06 19:22:48.374  1029  1560 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:22:48.374  7510  7510 I Feature : [Lifetracker]Accessory: true
,09-06 19:22:48.374  7510  7510 I Feature : [Lifetracker]Health device: true
09-06 19:22:48.375  7510  7510 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:22:48.375  7510  7510 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:22:48.375  7510  7510 I Feature : [Lifetracker]Device Number: 3
09-06 19:22:48.375  7082  7534 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:48.377  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:22:48.378  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:22:48.392  6855  6855 D BluetoothPermissionRequest: onReceive
,09-06 19:22:48.393  6963  7537 W FormManager: Network not available. Please check & try again.
09-06 19:22:48.394  6963  7538 V FormManager: Network unavailable.
09-06 19:22:48.396  7185  7185 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:48
09-06 19:22:48.397  7185  7185 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:22:48.397  7185  7185 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:22:48.398  7185  7185 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:22:48.398  7185  7185 D WeatherAncestor: connectivity changed - connection : true
09-06 19:22:48.398  7185  7185 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ade3123
09-06 19:22:48.398  7185  7185 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:22:48.399  7185  7185 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:22:48.399  7185  7185 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:22:48.399  7185  7185 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:22:48.399  7185  7185 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:48
09-06 19:22:48.401  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:22:48.405  6963  7538 V FormManager: Network unavailable.
,09-06 19:22:48.425  6467  6467 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:22:48.425  1029  1907 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:22:48.429  6467  6502 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-06 19:22:48.431  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 19:22:48.434  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:22:48.434  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:22:48.434  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:22:48.434  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:22:48.434  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:22:48.434  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:22:48.435  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:22:48.435  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:22:48.435  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:22:48.435  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:22:48.435  7015  7015 I BluetoothA2dpServiceJni: classInitNative
09-06 19:22:48.435  7015  7015 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:22:48.435  7015  7015 D A2dpStateMachine: make
09-06 19:22:48.436  7015  7015 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:22:48.437  7015  7541 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:22:48.439  7015  7015 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:22:48.439  7015  7015 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:22:48.440  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.440  2138  2138 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.441  7015  7015 D HeadsetStateMachine: Proxy object connected
09-06 19:22:48.441  7015  7015 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:22:48.441  7015  7015 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-06 19:22:48.442  7015  7540 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:22:48.443  7015  7015 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:22:48.444  7015  7015 D HidService: Received start request. Starting profile...
09-06 19:22:48.444  7015  7015 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:22:48.444  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.447  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:22:48.447  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.447  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:22:48.447  7054  7054 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:22:48.449  7015  7015 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:22:48.449  7015  7509 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:22:48.449  7015  7015 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:22:48.449  7015  7509 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:22:48.450  7015  7509 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 19:22:48.450  7054  7054 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:22:48.451  7015  7015 D HealthService: Received start request. Starting profile...
,09-06 19:22:48.452  7054  7054 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23e69edd
09-06 19:22:48.452  7054  7054 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:22:48.452  7054  7054 D AppUp4:CustFacade: isPhone : true
09-06 19:22:48.452  7054  7054 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:22:48.453  7054  7054 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:22:48.453  7015  7015 I bluedroid-qcom: get_profile_interface health
09-06 19:22:48.453  7015  7015 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:22:48.454  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.454  7015  7015 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:22:48.457  7015  7015 D PanService: Received start request. Starting profile...
09-06 19:22:48.457  7015  7015 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:22:48.457  7015  7015 I bluedroid-qcom: get_profile_interface pan
09-06 19:22:48.457  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.457  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:22:48.458  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:48.460  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:22:48.463  7015  7015 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,09-06 19:22:48.463  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.464  7015  7015 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 19:22:48.466  7082  7082 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:22:48.466  4308  7546 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:22:48.469  4308  7547 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.469  4308  7547 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:22:48.470  7015  7015 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:22:48.470  7015  7015 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:22:48.470  7015  7015 D BtGatt.GattService: start()
09-06 19:22:48.470  7015  7015 I bluedroid-qcom: get_profile_interface gatt
09-06 19:22:48.471  7015  7015 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:22:48.476  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
,09-06 19:22:48.477  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.477  7015  7015 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:22:48.479  7015  7015 V BluetoothMapService: BluetoothMapBinder()
09-06 19:22:48.479  7015  7015 D BluetoothMapService: Received start request. Starting profile...
09-06 19:22:48.479  7015  7015 D BluetoothMapService: start()
09-06 19:22:48.482  7082  7553 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:22:48.484  6963  7551 W FormManager: Network not available. Please check & try again.
09-06 19:22:48.484  7015  7015 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 19:22:48.484  7015  7015 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:22:48.487  7015  7015 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:22:48.487  7015  7015 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-06 19:22:48.493  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:22:48.493  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:22:48.493  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:22:48.494  6963  7552 V FormManager: Network unavailable.
09-06 19:22:48.496  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:22:48.496  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:22:48.496  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:48.499  7015  7015 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:22:48.501  6963  7552 V FormManager: Network unavailable.
,09-06 19:22:48.502  7015  7015 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:22:48.505  7015  7015 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:22:48.506  7015  7015 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 19:22:48.507  7185  7185 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:48
09-06 19:22:48.509  7015  7015 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:22:48.510  7185  7185 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:22:48.510  7185  7185 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:22:48.510  7185  7185 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:22:48.510  7185  7185 D WeatherAncestor: connectivity changed - connection : true
09-06 19:22:48.510  7185  7185 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ade3123
09-06 19:22:48.511  7185  7185 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:22:48.511  7185  7185 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:22:48.511  7185  7185 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:22:48.511  7185  7185 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:22:48.511  7185  7185 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:22:48
09-06 19:22:48.512  7015  7015 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 19:22:48.512  7015  7015 V BluetoothMapService: Handler(): got msg=1
,09-06 19:22:48.512  7015  7485 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:22:48.513  7015  7485 I bluedroid-qcom: enable
09-06 19:22:48.513  7015  7485 I bt_hci_bdroid: init
09-06 19:22:48.514  7015  7485 I bt_vendor: bt-vendor : init
09-06 19:22:48.514  7015  7485 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:22:48.514  7015  7485 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:22:48.514  7015  7485 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:22:48.514  7015  7485 D bt_userial_mct: userial_init
09-06 19:22:48.514  7015  7485 D bt_hci_bdroid: set_power 1
09-06 19:22:48.514  7015  7485 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:22:48.514  7015  7555 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:22:48.514  7015  7555 I bt-btu  : btu_task pending for preload complete event
09-06 19:22:48.514  7015  7485 I bt_vendor: Starting hciattach daemon
09-06 19:22:48.514  7015  7485 I bt_vendor: try to set true
09-06 19:22:48.514  7015  7015 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:48.500  7558  7558 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:48.500  7558  7558 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:48.518  7015  7015 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:48.518  7015  7015 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:48.518  7015  7015 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:48.518  7015  7015 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:48.518  7015  7015 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:22:48.536  7559  7559 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:22:48.613  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:22:48.640  7566  7566 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:22:48.677  7568  7568 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:22:48.705  7569  7569 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 19:22:48.748  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:22:48.764  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:22:48.788  7576  7576 I libmdmdetect: ESOC framework not supported
,09-06 19:22:48.789  7576  7576 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 19:22:48.797  7576  7576 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-06 19:22:48.797  7576  7576 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 19:22:48.797  7576  7576 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 19:22:48.797  7576  7576 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 19:22:48.797  7576  7576 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 19:22:48.797  7576  7576 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:22:48.797  7576  7576 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 19:22:48.837  7576  7577 E QC-QMI  : qmi_client [7576] 14: failed to locate client data
09-06 19:22:48.838   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 19:22:48.838   483   483 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-06 19:22:48.891  7578  7578 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 19:22:48.909  7579  7579 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:22:48.969  7015  7485 I bt_vendor: bluetooth satus is on
,09-06 19:22:48.969  7015  7485 D bt_hci_bdroid: preload
,09-06 19:22:48.970  7015  7557 D bt_userial_mct: userial_open(port:0)
09-06 19:22:48.970  7015  7557 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-06 19:22:48.974  7015  7557 I bt_vendor: Done intiailizing UART
,09-06 19:22:48.978  7015  7557 I bt_vendor: Done intiailizing UART
,09-06 19:22:48.978  7015  7557 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:22:48.978  7015  7557 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:22:48.979  7015  7581 D bt_userial_mct: Entering userial_read_thread()
09-06 19:22:48.979  7015  7555 I bt-btu  : btu_task received preload complete event
,09-06 19:22:48.980  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:22:48.980  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,09-06 19:22:48.987  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:22:48.996  7015  7555 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:22:48.997  7015  7555 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:22:49.092  7015  7555 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-06 19:22:49.093  7015  7555 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
09-06 19:22:49.093  7015  7555 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,09-06 19:22:49.119  7015  7489 E bt-btif : Calling BTA_HhEnable
09-06 19:22:49.119  7015  7489 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 19:22:49.119  7015  7489 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:22:49.120  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 19:22:49.120  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 19:22:49.120  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 19:22:49.120  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:22:49.120  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:22:49.122  7015  7489 D BluetoothAdapterProperties: Name is: G3
,09-06 19:22:49.123  7015  7489 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:22:49.123  7015  7489 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:22:49.124  7015  7489 D bt_hci_bdroid: postload
09-06 19:22:49.124  7015  7557 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:49.126  7015  7555 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:22:49.127  7015  7557 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:49.127  7015  7489 D bte_conf: Device ID record 1 : primary
09-06 19:22:49.127  7015  7489 D bte_conf:   vendorId            = 00c4
09-06 19:22:49.127  7015  7489 D bte_conf:   vendorIdSource      = 0001
09-06 19:22:49.127  7015  7489 D bte_conf:   product             = 13a1
09-06 19:22:49.127  7015  7489 D bte_conf:   version             = 1000
09-06 19:22:49.127  7015  7489 D bte_conf:   clientExecutableURL = 
09-06 19:22:49.127  7015  7489 D bte_conf:   serviceDescription  = 
09-06 19:22:49.127  7015  7489 D bte_conf:   documentationURL    = 
09-06 19:22:49.127  7015  7489 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:22:49.120  7586  7586 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:49.120  7586  7586 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:49.130  7015  7557 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:49.134  7015  7485 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:22:49.134  7015  7485 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:22:49.134  7015  7485 D BluetoothAdapterProperties: State =  11
09-06 19:22:49.134  7015  7485 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 19:22:49.134  7015  7485 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:22:49.134  7015  7485 D BluetoothAdapterProperties: Setting state to 12
09-06 19:22:49.135  7015  7485 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:22:49.135  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:49.135  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:22:49.135  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,09-06 19:22:49.141  7015  7555 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:49.141  7015  7555 W bt-smp  : Plain text(LSB ~ MSB) = 51 c8 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:49.141  7015  7555 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f b6 42 5b 37 17 be a7 36 c7 da 63 0d f0 b3 95 
09-06 19:22:49.141  7015  7557 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:49.141  7015  7555 W bt-btm  : Stopping oneshot timer
09-06 19:22:49.142  7015  7489 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:22:49.142  7015  7489 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:22:49.145  7015  7581 E bt_mct  : hci lib postload completed
09-06 19:22:49.152  1029  1089 W ProcessCpuTracker: Skipping unknown process pid 7539
,09-06 19:22:49.155  7015  7485 I BluetoothAdapterState: Entering On State
09-06 19:22:49.156  1836  2563 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:22:49.158  7015  7485 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:22:49.158  7015  7485 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:22:49.158  7015  7485 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 19:22:49.159  7015  7485 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:22:49.161  7015  7489 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:22:49.162  7015  7489 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 19:22:49.162  1029  1089 W ProcessCpuTracker: Skipping unknown process pid 7582
09-06 19:22:49.164  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-06 19:22:49.169  6855  6874 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:22:49.173  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:22:49.180  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:49.183  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:22:49.184  7015  7555 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:49.184  7015  7555 W bt-smp  : Plain text(LSB ~ MSB) = f7 09 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:49.184  7015  7555 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 86 c5 53 e0 67 a2 bd 92 35 78 9b 2b e8 e0 b2 
09-06 19:22:49.184  7015  7555 W bt-btm  : Stopping oneshot timer
,09-06 19:22:49.185  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:22:49.190  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:49.194  7592  7592 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:49.195  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:22:49.197  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:22:49.197  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:22:49.199  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:49.201  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:22:49.201  7015  7555 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:49.201  7015  7555 W bt-smp  : Plain text(LSB ~ MSB) = 26 31 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:49.201  7015  7555 W bt-smp  : Encrypted text(LSB ~ MSB) = 55 0e 00 c8 5f 81 f8 9b c2 7d d3 f5 70 6d 27 69 
09-06 19:22:49.201  7015  7555 W bt-btm  : Stopping oneshot timer
09-06 19:22:49.202  1029  1100 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:22:49.203  6855  6872 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:22:49.204  1029  1029 D BluetoothA2dp: Proxy object connected
09-06 19:22:49.205  7015  7485 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 19:22:49.207  1029  1100 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:22:49.210  1029  1029 D BluetoothHeadset: Proxy object connected
09-06 19:22:49.213  7015  7555 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:49.213  7015  7555 W bt-smp  : Plain text(LSB ~ MSB) = 12 ab 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:49.213  7015  7555 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 28 9f 37 bf 22 c5 45 7e cf 3c 71 8b b3 fc 55 
09-06 19:22:49.213  7015  7555 W bt-btm  : Stopping oneshot timer
09-06 19:22:49.214  6855  6855 D BluetoothMap: Proxy object connected
09-06 19:22:49.214  6855  6872 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:22:49.214  6855  6872 D BluetoothPan: onBluetoothStateChange call bindService
09-06 19:22:49.214  6855  6855 D MapProfile: Bluetooth service connected
09-06 19:22:49.214  6855  6855 D BluetoothMap: getConnectedDevices()
09-06 19:22:49.215  7015  7031 V BluetoothMapService: getConnectedDevices()
09-06 19:22:49.216  6855  6874 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:22:49.218  6855  6855 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:22:49.218  6855  6855 D PanProfile: Bluetooth service connected
09-06 19:22:49.220  1029  1100 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:22:49.220  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-06 19:22:49.222  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:49.222  1925  2132 D LGBluetoothAPIService: Message: 1
09-06 19:22:49.222  1925  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:22:49.226  7226  7257 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-06 19:22:49.227  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:49.228  6651  6651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:22:49.230  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:22:49.230  1029  1100 D BluetoothManagerService: Message: 40
09-06 19:22:49.230  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:22:49.231  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:49.232  1925  2132 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-06 19:22:49.233  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:49.234  6855  6855 D BluetoothInputDevice: Proxy object connected
09-06 19:22:49.234  6855  6855 D HidProfile: Bluetooth service connected
09-06 19:22:49.235  7015  7015 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:49.236  7015  7015 D BluetoothMapService: STATE_ON
09-06 19:22:49.236  7015  7555 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:49.236  7015  7555 W bt-smp  : Plain text(LSB ~ MSB) = 53 34 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:49.236  7015  7555 W bt-smp  : Encrypted text(LSB ~ MSB) = f3 6d 05 06 df 4e 95 be fa 8c 5e 5a 40 ad d2 a3 
09-06 19:22:49.236  7015  7555 W bt-btm  : Stopping oneshot timer
09-06 19:22:49.238  7015  7015 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 19:22:49.238  7015  7015 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 19:22:49.240  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 19:22:49.240  1925  2132 D LGBluetoothAPIService: Message: 100
,09-06 19:22:49.240  1925  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:22:49.240  6855  6855 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 19:22:49.243  1029  1100 D BluetoothManagerService: Message: 30
09-06 19:22:49.246  6855  6855 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 19:22:49.249  1029  1100 D BluetoothManagerService: Message: 30
09-06 19:22:49.253  6855  6855 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 19:22:49.255  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:22:49.257  6855  6855 D BluetoothA2dp: Proxy object connected
09-06 19:22:49.258  6855  6855 D A2dpProfile: Bluetooth service connected
09-06 19:22:49.258  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:49.258  7015  7015 V BluetoothPbapService: Pbap Service onCreate
09-06 19:22:49.259  7015  7015 V BluetoothPbapService: Starting PBAP service
09-06 19:22:49.260  7015  7015 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:22:49.260  7015  7015 V BluetoothMapService: Handler(): got msg=1
09-06 19:22:49.261  7015  7015 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:22:49.261  7015  7015 V BluetoothPbapService: Pbap Service onBind
09-06 19:22:49.262  7015  7606 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:22:49.263  7015  7606 D BluetoothMapMasInstance:   masId = 00
09-06 19:22:49.263  7015  7606 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:22:49.263  7015  7606 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:22:49.263  7015  7606 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,09-06 19:22:49.264  1029  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:49.265  7015  7015 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:49.265  7015  7015 V BluetoothPbapService: state: 12
09-06 19:22:49.265  7015  7015 V BluetoothPbapService: Handler(): got msg=1
09-06 19:22:49.265  7015  7015 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:22:49.265  6855  6855 D BluetoothHeadset: Proxy object connected
09-06 19:22:49.266  7015  7015 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:22:49.266  7015  7015 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:49.266  7015  7015 V BluetoothPbapReceiver: ***********state = 12
09-06 19:22:49.266  6855  6855 D HeadsetProfile: Bluetooth service connected
09-06 19:22:49.268  7015  7606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:49.270  7015  7607 V BluetoothPbapService: Pbap Service initSocket
09-06 19:22:49.270  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:22:49.270  1029  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:49.270  2138  2138 D c       : Getting all permits...
09-06 19:22:49.270  2138  2138 D a       : Opening database...
09-06 19:22:49.273  7015  7489 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:22:49.273  7015  7489 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:22:49.273  2138  2138 D a       : Opening database auth.proximity.permit_store...
09-06 19:22:49.273  2138  2138 D a       : Closing database...
09-06 19:22:49.275  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:49.276  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:49.277  7015  7606 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:22:49.277  7015  7606 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:22:49.277  7015  7606 D BluetoothMapMasInstance: Accepting socket connection...
09-06 19:22:49.278  7015  7607 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:49.281  7015  7607 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 19:22:49.281  6855  6855 D DockEventReceiver: finishStartingService: stopping service
09-06 19:22:49.281  7015  7607 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:22:49.281  7015  7607 V BluetoothPbapService: Accepting socket connection...
09-06 19:22:49.282  6855  6855 D BluetoothPbap: Proxy object connected
09-06 19:22:49.282  6855  6855 D PbapServerProfile: Bluetooth service connected
09-06 19:22:49.288  6855  6855 D BluetoothPermissionRequest: onReceive
,09-06 19:22:49.290  6855  6855 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:22:49.291  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:22:49.294  7015  7015 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 19:22:49.295  7015  7015 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:22:49.300  7015  7015 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 19:22:49.318  7015  7015 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 19:22:49.318  7015  7015 V BtOppService: onCreate
,09-06 19:22:49.323  7015  7015 V BluetoothOppNotification: send message
09-06 19:22:49.327  7015  7015 V BtOppService: Starting RfcommListener
09-06 19:22:49.335  7015  7015 D BluetoothOppPreference: Dumping Names:  
,09-06 19:22:49.335  7015  7015 D BluetoothOppPreference: {}
09-06 19:22:49.335  7015  7015 D BluetoothOppPreference: Dumping Channels:  
09-06 19:22:49.335  7015  7015 D BluetoothOppPreference: {}
09-06 19:22:49.336  7015  7015 V BtOppService: onStartCommand
09-06 19:22:49.340  7015  7613 V BtOppService: Deleted complete outbound shares, number =  0
09-06 19:22:49.342  7015  7613 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 19:22:49.343  7015  7613 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:22:49.343  7015  7015 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:49.343  7015  7015 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:22:49.344  7015  7616 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:22:49.344  7015  7613 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fa5a4dc on behalf of 
09-06 19:22:49.346  7015  7616 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:22:49.350  7015  7616 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fea69e5 on behalf of 
09-06 19:22:49.350  7015  7015 V BluetoothOppNotification: new notify threadi!
,09-06 19:22:49.351  7015  7015 V BluetoothOppNotification: send delay message
09-06 19:22:49.351  7015  7616 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:22:49.352  7015  7015 V BtOppService: start RfcommListener
09-06 19:22:49.354  7015  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:22:49.354  7015  7616 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:22:49.355  7015  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f310cba on behalf of 
09-06 19:22:49.356  7015  7617 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:22:49.357  7015  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:49.358  7015  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b9f476b on behalf of 
,09-06 19:22:49.359  7015  7617 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:22:49.360  7015  7617 V BluetoothOppNotification: outbound notification was removed.
09-06 19:22:49.360  7015  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:49.360  7015  7015 V BtOppService: RfcommListener started
09-06 19:22:49.361  7015  7015 V BtOppService: ContentObserver received notification
09-06 19:22:49.362  7015  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@125632c8 on behalf of 
09-06 19:22:49.363  7015  7617 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:22:49.363  7015  7015 V BtOppService: ContentObserver received notification
09-06 19:22:49.364  7015  7617 V BluetoothOppNotification: inbound notification was removed.
09-06 19:22:49.364  7015  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-06 19:22:49.365  7015  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20dcbf61 on behalf of 
09-06 19:22:49.369  7015  7619 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:22:49.369  7015  7618 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 19:22:49.369  7015  7619 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:22:49.370  1029  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:49.371  7015  7619 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26533a86 on behalf of 
09-06 19:22:49.371  7015  7618 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:49.372  7015  7618 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-06 19:22:49.372  7015  7618 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:22:49.373  7015  7619 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:22:49.373  7015  7618 I BtOppRfcommListener: Accept thread started.
09-06 19:22:49.373  7015  7618 V BtOppRfcommListener: Accepting connection...
09-06 19:22:49.395  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
,09-06 19:22:49.396  7015  7015 V BluetoothFtpService: Ftp Service onCreate
09-06 19:22:49.396  7015  7015 I BluetoothFtpService: Ftp Service onCreate
09-06 19:22:49.396  7015  7015 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:22:49.396  7015  7015 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:49.396  7015  7015 V BluetoothFtpService: Starting Listening on sockets
09-06 19:22:49.396  7015  7015 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:49.397  7015  7015 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:49.397  7015  7015 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:49.397  7015  7015 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:49.397  7015  7015 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 19:22:49.397  7015  7015 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:22:49.401  7015  7015 V BluetoothFtpService: Handler(): got msg=1
09-06 19:22:49.401  7015  7015 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:22:49.401  7015  7015 V BluetoothFtpService: Ftp Service initSocket
09-06 19:22:49.404  1029  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:49.405  7015  7015 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:49.406  7015  7015 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-06 19:22:49.406  7015  7015 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:22:49.408  7015  7620 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-06 19:22:49.423  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
,09-06 19:22:49.423  7015  7015 V BluetoothSapService: Sap Service onCreate
09-06 19:22:49.426  7015  7015 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:22:49.426  7015  7015 V BluetoothSapService: state: 12
09-06 19:22:49.426  7015  7015 V BluetoothSapService: Starting SAP server process
09-06 19:22:49.428  7015  7015 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 19:22:49.429  7015  7622 V BluetoothSapService: Sap Service initRfcommSocket
09-06 19:22:49.430  1029  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:49.420  7621  7621 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:49.420  7621  7621 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:49.431  7015  7622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:49.432  7015  7622 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 19:22:49.432  7015  7622 V BluetoothSapService: Succeed to create listening socket 
09-06 19:22:49.432  7015  7622 V BluetoothSapService: Accepting socket connection...
09-06 19:22:49.454  7621  7621 V BT_SAP  : Event pipe created
09-06 19:22:49.454  7621  7621 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:22:49.454  7621  7621 V BT_SAP  : created socket fd 6
,09-06 19:22:49.495  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-06 19:22:49.495  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-06 19:22:49.505  1029  1528 D WifiController: battery changed pluggedType: 2
,09-06 19:22:49.508  1587  1587 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 308
09-06 19:22:49.508  1587  1587 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-06 19:22:49.511  1925  2106 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-06 19:22:49.511  1925  2106 D LEDHandler: Battery Level Remaining: 100%
09-06 19:22:49.511  1925  2106 D LEDHandler: Battery Temp: 308, mChargingStatus=5, mChargingStop=false
,09-06 19:22:49.515  1587  1587 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-06 19:22:49.520  7404  7404 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-06 19:22:49.520  7015  7509 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:22:50.032  1029  1045 I ActivityManager: Killing 7404:com.lge.bnr/1000 (adj 15): empty #17
,09-06 19:22:50.063  1029  1522 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:22:50.063  1029  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:22:50.071  1029  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_7404/cgroup.procs: No such file or directory
,09-06 19:22:50.110  1029  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 19:22:50.112  1029  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 19:22:50.348  1029  1979 I ActivityManager: Killing 6769:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-06 19:22:50.357  7015  7015 V BluetoothOppNotification: new notify threadi!
09-06 19:22:50.358  7015  7015 V BluetoothOppNotification: send delay message
09-06 19:22:50.373  7015  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 19:22:50.385  6919  6919 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-06 19:22:50.386  6919  6919 W System.err: android.os.DeadObjectException
09-06 19:22:50.386  6919  6919 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:22:50.386  6919  6919 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:22:50.386  6919  6919 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 19:22:50.386  6919  6919 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 19:22:50.386  6919  6919 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:22:50.386  6919  6919 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:22:50.386  6919  6919 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:22:50.386  6919  6919 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:22:50.386  6919  6919 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:22:50.386  6919  6919 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:22:50.386  6919  6919 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,09-06 19:22:50.391  6919  6919 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:22:50.391  6919  6919 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:22:50.391  6919  6919 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:22:50.391  6919  6919 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 19:22:50.392  6919  6919 W System.err: android.os.DeadObjectException
09-06 19:22:50.392  6919  6919 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:22:50.392  6919  6919 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:22:50.392  6919  6919 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 19:22:50.392  6919  6919 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 19:22:50.392  6919  6919 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:22:50.392  6919  6919 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:22:50.392  6919  6919 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:22:50.392  6919  6919 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:22:50.392  6919  6919 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:22:50.392  6919  6919 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:22:50.392  6919  6919 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:22:50.392  6919  6919 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:22:50.392  6919  6919 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:22:50.392  6919  6919 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:22:50.392  6919  6919 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 19:22:50.393  6919  6919 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-06 19:22:50.394  7015  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@283b38e3 on behalf of 
09-06 19:22:50.395  7015  7632 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:22:50.396  7015  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:50.397  7015  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f1e92e0 on behalf of 
09-06 19:22:50.398  7015  7632 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 19:22:50.405  7015  7632 V BluetoothOppNotification: outbound notification was removed.
09-06 19:22:50.406  7015  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:50.407  7015  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a04f999 on behalf of 
09-06 19:22:50.407  7015  7632 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:22:50.409  7015  7632 V BluetoothOppNotification: inbound notification was removed.
09-06 19:22:50.409  7015  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:22:50.410  7015  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d81145e on behalf of 
09-06 19:22:50.413  1029  1870 W libprocessgroup: failed to open /acct/uid_1000/pid_6769/cgroup.procs: No such file or directory
09-06 19:22:50.413  1029  1870 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-06 19:22:50.419  6919  6919 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 19:22:50.420  6919  6919 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:22:50.468  1029  1871 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7633 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:22:50.503  6919  6919 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 19:22:50.574  7633  7633 D UEI.SmartControl: Quickset Services start...
,09-06 19:22:50.578  7633  7633 I UEI.SmartControl: Manufacture = LGE
,09-06 19:22:50.579  7633  7633 D UEI.SmartControl: Id = LGNevo
09-06 19:22:50.581  7633  7633 D UEI.SmartControl: File observer start...
09-06 19:22:50.582  7633  7633 E UEI.SmartControl: IR Port is disabled: false
09-06 19:22:50.583  7633  7633 D UEI.SmartControl: Starting file observer...
09-06 19:22:50.583  7633  7633 D UEI.SmartControl: Extracting JNI libs...
09-06 19:22:50.584  7633  7633 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-06 19:22:50.690  7633  7633 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-06 19:22:50.690  7633  7633 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-06 19:22:50.690  7633  7633 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-06 19:22:50.729  7633  7633 I UEI.SmartControl: --- Selecting new region: 6,
09-06 19:22:50.732  7633  7633 I UEI.SmartControl: Model = LG-D855
,09-06 19:22:50.734  7633  7633 D UEI.SmartControl: QS Service created
,09-06 19:22:50.950  1029  1979 I art     : Explicit concurrent mark sweep GC freed 93025(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.650ms total 213.743ms
,09-06 19:22:51.005  7633  7633 I UEI.SmartControl: Service initServices...
,09-06 19:22:51.013  7633  7633 D UEI.SmartControl: QS start get config
09-06 19:22:51.021  1029  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:51.021  1029  1871 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24cc3fa mBinding = false
,09-06 19:22:51.037  1029  1100 D BluetoothManagerService: Message: 2,
,09-06 19:22:51.042  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 19:22:51.043  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:22:51.043  1029  1029 D Ulp_jni : JNI:system_update. Event-4
09-06 19:22:51.043  1029  1100 D BluetoothManagerService: Sending off request.
09-06 19:22:51.044  7015  7031 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:22:51.045  7015  7485 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:22:51.045  7015  7485 D BluetoothAdapterProperties: Setting state to 13
09-06 19:22:51.045  7015  7485 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:22:51.046  7015  7485 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:22:51.046  7015  7485 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:22:51.048  7015  7489 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:22:51.049  7015  7485 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-06 19:22:51.054  7015  7485 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:22:51.058  7015  7607 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:51.058  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:22:51.059  7015  7555 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:22:51.059  7015  7622 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:51.061  7015  7620 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:51.063  7015  7618 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:22:51.066  7015  7606 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:22:51.068  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:22:51.068  7015  7555 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:22:51.078  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:51.078  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:22:51.083  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:51.083  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:51.085  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:51.085  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:22:51.088  6651  6651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:22:51.088  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:51.089  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:51.089  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:22:51.089  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:22:51.091  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:22:51.096  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:51.103  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:51.106  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:51.107  7015  7015 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:51.108  7015  7015 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:22:51.108  7015  7015 V BluetoothMapService: Handler(): got msg=4
09-06 19:22:51.108  7015  7015 D BluetoothMapService: MAP Service closeService in
09-06 19:22:51.108  7015  7015 D BluetoothMapMasInstance: MAP Service shutdown
09-06 19:22:51.108  7015  7015 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:22:51.109  7015  7015 V BluetoothMapService: MAP Service closeService out
09-06 19:22:51.110  7015  7015 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:22:51.110  7015  7015 I BtOppRfcommListener: stopping Accept Thread
09-06 19:22:51.110  7015  7015 V BtOppRfcommListener: close mBtServerSocket
09-06 19:22:51.111  7015  7618 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:22:51.111  7015  7015 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:22:51.111  7015  7015 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:22:51.115  6855  6855 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-06 19:22:51.127  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 19:22:51.130  7015  7015 V BtOppService: onDestroy
09-06 19:22:51.131  7015  7015 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 19:22:51.136  7015  7015 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:22:51.136  7015  7015 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:51.136  7015  7015 V BluetoothPbapReceiver: ***********state = 13
09-06 19:22:51.144  6855  6855 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:22:51.149  7015  7015 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 19:22:51.156  7015  7015 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:51.156  7015  7015 V BluetoothPbapService: state: 13
09-06 19:22:51.156  7015  7015 V BluetoothPbapService: Pbap Service closeService in
,09-06 19:22:51.160  7015  7015 V BluetoothPbapService: successfully stopped pbap service
09-06 19:22:51.160  7015  7015 V BluetoothPbapService: Pbap Service closeService out
09-06 19:22:51.160  7015  7015 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:22:51.160  7015  7015 V BluetoothPbapService: Pbap Service closeService in
09-06 19:22:51.160  7015  7015 V BluetoothPbapService: Pbap Service closeService out
09-06 19:22:51.160  7015  7015 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 19:22:51.161  6855  6855 D BluetoothPbap: Proxy object disconnected
09-06 19:22:51.161  6855  6855 D PbapServerProfile: Bluetooth service disconnected
09-06 19:22:51.162  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:22:51.175  6855  6855 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:22:51.182  6855  6855 D BluetoothPermissionRequest: onReceive
09-06 19:22:51.183  6855  6855 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:22:51.189  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 19:22:51.195  7015  7015 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 19:22:51.195  7015  7015 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-06 19:22:51.196  7015  7015 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 19:22:51.201  7015  7015 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:51.201  7015  7015 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-06 19:22:51.202  7015  7015 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:22:51.202  7015  7015 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:51.203  7015  7015 V BluetoothFtpService: Ftp Service closeService
09-06 19:22:51.203  7015  7015 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 19:22:51.206  7015  7015 V BluetoothFtpService: successfully stopped ftp service
09-06 19:22:51.206  7015  7015 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:51.206  7015  7015 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:51.206  7015  7015 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:51.206  7015  7015 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:51.206  7015  7015 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:22:51.206  7015  7015 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:22:51.207  7015  7015 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:22:51.207  7015  7015 V BluetoothFtpService: Ftp Service closeService
09-06 19:22:51.210  7015  7015 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:22:51.210  7015  7015 V BluetoothSapService: state: 13
09-06 19:22:51.210  7015  7015 V BluetoothSapService: Stopping SAP server process
09-06 19:22:51.211  7015  7015 V BluetoothSapService: Sap Service closeSapService in
09-06 19:22:51.211  7015  7015 V BluetoothSapService: Close listen Socket : 
09-06 19:22:51.211  7015  7015 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:22:51.212  7015  7015 V BluetoothSapService: Close sapd  Socket : 
09-06 19:22:51.215  7015  7015 V BluetoothSapService: Sap Service closeSapService out
09-06 19:22:51.216  7015  7015 V BluetoothSapService: Sap Service onDestroy
09-06 19:22:51.216  7015  7015 V BluetoothSapService: Sap Service closeSapService in
09-06 19:22:51.216  7015  7015 V BluetoothSapService: Close listen Socket : 
09-06 19:22:51.216  7015  7015 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:22:51.216  7015  7015 V BluetoothSapService: Close sapd  Socket : 
09-06 19:22:51.216  7015  7015 V BluetoothSapService: Sap Service closeSapService out
09-06 19:22:51.217  7633  7633 D UEI.SmartControl: Loading JNI Libs...
,09-06 19:22:51.472  7633  7633 I UEI.SmartControl: Supports setup maps: true
,09-06 19:22:51.475  7633  7633 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:22:51.476  7633  7633 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:22:51.476  7633  7633 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:22:51.476  7633  7633 I UEI.SmartControl: ### init IR Blaster...
09-06 19:22:51.481  7633  7633 D serial_port: Configuring serial port
09-06 19:22:51.485  7633  7633 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:22:51.485  7633  7633 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:22:51.485  7633  7633 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:22:51.485  7633  7633 I UEI.SmartControl: Get version...
,09-06 19:22:51.509  7633  7695 D UEI.SmartControl: serial port data available: 21
,09-06 19:22:51.539  7633  7633 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:22:51.539  7633  7633 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-06 19:22:51.541  7633  7633 I UEI.SmartControl: QS saving settings...
,09-06 19:22:51.544  7633  7633 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:22:51.566  7633  7695 D UEI.SmartControl: serial port data available: 4
,09-06 19:22:51.608  7633  7633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:22:51.612  7633  7704 I UEI.SmartControl: Device manager: loading config....
,09-06 19:22:51.626  7633  7704 D UEI.SmartControl: ----------- loading internal config...
,09-06 19:22:51.633  7633  7633 E UEI.SmartControl: Services init done
09-06 19:22:51.633  7633  7633 D UEI.SmartControl: QS Service init finished
09-06 19:22:51.634  7633  7633 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:22:51.634  7633  7633 D UEI.SmartControl: QS Service version code: 201091
09-06 19:22:51.635  7633  7633 D UEI.SmartControl: Service requested: Control
09-06 19:22:51.642  7633  7704 E UEI.SmartControl: Loading SETTINGS...
,09-06 19:22:51.647  7633  7633 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 19:22:51.652  1029  1906 I ActivityManager: Killing 6919:com.lge.qremote/u0a112 (adj 15): empty #17
09-06 19:22:51.658  7633  7704 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-06 19:22:51.673  7633  7703 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:22:51.673  7633  7703 D UEI.SmartControl: -----service ready thread exits
,09-06 19:22:51.708  1029  1871 W libprocessgroup: failed to open /acct/uid_10112/pid_6919/cgroup.procs: No such file or directory
,09-06 19:22:51.713  7633  7633 D UEI.SmartControl: Internal service binding...
,09-06 19:22:52.002  7015  7489 D bt_hci_bdroid: cleanup
,09-06 19:22:52.009  7015  7557 I bt_lpm  : LPM is already off!!!
09-06 19:22:52.011  7015  7581 I bt_userial_mct: exiting userial_read_thread
09-06 19:22:52.011  7015  7581 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:22:52.011  7015  7555 W bt-btif : ag scb idx 1 not allocated
09-06 19:22:52.011  7015  7555 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:22:52.011  7015  7555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:22:52.011  7015  7555 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:22:52.012  7015  7489 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:22:52.013  7015  7557 I bt_vendor: hw_epilog_process
09-06 19:22:52.013  7015  7489 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 19:22:52.013  7015  7489 D bt_userial_mct: userial_close
09-06 19:22:52.013  7015  7489 E bt_userial_mct: pthread_join() FAILED result:3
09-06 19:22:52.013  7015  7489 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-06 19:22:52.020  7015  7489 D bt_hci_bdroid: set_power 0
09-06 19:22:52.020  7015  7489 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:22:52.020  7015  7489 I bt_vendor: bluetooth satus is on
09-06 19:22:52.020  7015  7489 I bt_vendor: bt-vendor : resetting BT status
09-06 19:22:52.020  7015  7489 I bt_vendor: Starting hciattach daemon
09-06 19:22:52.020  7015  7489 I bt_vendor: try to set false
,09-06 19:22:52.027  7015  7489 I bt_vendor: Starting hciattach daemon
09-06 19:22:52.027  7015  7489 I bt_vendor: try to set false
09-06 19:22:52.028  7015  7489 I bt_vendor: cleanup
09-06 19:22:52.029  7015  7555 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:22:52.029  7015  7489 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:22:52.029  7015  7489 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:22:52.031  7015  7485 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:22:52.036  7015  7015 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:22:52.040  7015  7015 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-06 19:22:52.040  7015  7015 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:22:52.041  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:52.041  7015  7509 D HeadsetStateMachine: Exit Disconnected: -1
,09-06 19:22:52.045  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:52.045  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:52.045  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:52.045  1029  1029 D BluetoothHeadset: Proxy object disconnected
09-06 19:22:52.045  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:22:52.049  7015  7015 D A2dpService: Received stop request...Stopping profile...
,09-06 19:22:52.055  7015  7540 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:22:52.056  7015  7485 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:22:52.057  7015  7015 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 19:22:52.058  7015  7015 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:22:52.058  7015  7015 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:22:52.058  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:52.061  7015  7015 D HidService: Received stop request...Stopping profile...
09-06 19:22:52.061  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
,09-06 19:22:52.063  1029  1029 D BluetoothA2dp: Proxy object disconnected
09-06 19:22:52.063  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:22:52.067  7015  7015 D HealthService: Received stop request...Stopping profile...
09-06 19:22:52.067  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:52.068  7015  7015 D HeadsetStateMachine: Unbinding service...
09-06 19:22:52.069  7015  7015 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:22:52.069  7015  7015 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:22:52.069  7015  7015 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:22:52.069  7015  7015 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:22:52.070  7015  7015 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:22:52.070  7015  7015 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:22:52.070  7015  7015 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:22:52.071  7015  7015 D PanService: Received stop request...Stopping profile...
09-06 19:22:52.071  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:52.072  7015  7015 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:22:52.076  7015  7015 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:22:52.076  7015  7015 D BtGatt.GattService: stop()
09-06 19:22:52.076  7015  7015 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:22:52.078  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:52.080  7015  7015 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:22:52.080  7015  7015 D BluetoothMapService: stop()
09-06 19:22:52.081  7015  7015 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:22:52.081  7015  7015 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 19:22:52.081  7015  7015 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ade3123
09-06 19:22:52.082  7015  7015 I BluetoothA2dpServiceJni: cleanupNative
09-06 19:22:52.083  7015  7541 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:22:52.083  7015  7015 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:22:52.083  7015  7015 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:22:52.083  7015  7015 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:22:52.084  7015  7015 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:22:52.084  7015  7015 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:22:52.084  7015  7015 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:22:52.084  7015  7015 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:22:52.085  7015  7015 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:22:52.085  7015  7015 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:22:52.089  7015  7015 V BluetoothMapService: Handler(): got msg=4
09-06 19:22:52.089  7015  7015 D BluetoothMapService: MAP Service closeService in
09-06 19:22:52.089  7015  7015 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:22:52.089  7015  7015 V BluetoothMapService: MAP Service closeService out
09-06 19:22:52.091  7015  7485 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:22:52.091  7015  7485 D BluetoothAdapterProperties: Setting state to 10
09-06 19:22:52.091  7015  7485 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:22:52.092  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:52.092  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:22:52.092  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-06 19:22:52.092  7015  7485 I BluetoothAdapterState: Entering OffState
09-06 19:22:52.093  6855  7602 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:52.094  7015  7015 D BluetoothMapService: cleanup()
09-06 19:22:52.094  7015  7015 D BluetoothMapService: MAP Service closeService in
09-06 19:22:52.095  7015  7015 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:22:52.095  7015  7015 V BluetoothMapService: MAP Service closeService out
09-06 19:22:52.096  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:52.096  6855  7602 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:22:52.102  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:52.103  1836  2582 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:52.104  1029  1100 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:22:52.104  6855  7602 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:22:52.105  6855  7602 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:22:52.105  1029  1100 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:22:52.105  6855  7602 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:22:52.106  6855  7602 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:22:52.107  1029  1100 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:22:52.107  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 19:22:52.109  1029  1100 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:22:52.109  1029  1100 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:22:52.109  1029  1100 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@24cc3fa mBinding = false
,09-06 19:22:52.111  1029  1100 D BluetoothManagerService: Sending unbind request.
09-06 19:22:52.116  7015  7489 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:22:52.118  7015  7015 I GKI_LINUX: GKI_exit_task 1 done
,09-06 19:22:52.118  7015  7015 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:22:52.118  7015  7015 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:22:52.118  7015  7015 I art     : --- WEIRD: removing null entry 248
09-06 19:22:52.118  7015  7015 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-06 19:22:52.118  7015  7015 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 19:22:52.120  7015  7015 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:22:52.121  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-06 19:22:52.125  7015  7015 I art     : System.exit called, status: 0
09-06 19:22:52.125  7015  7015 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:22:52.144   318  1367 V AudioFlinger: 7015 died, releasing its sessions
09-06 19:22:52.144   318  1367 V AudioFlinger:  pid 1836 @ 0
09-06 19:22:52.144   318  1367 V AudioFlinger:  pid 3407 @ 1
09-06 19:22:52.144   318  1367 V AudioFlinger:  pid 3407 @ 2
,09-06 19:22:52.148  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-06 19:22:52.148  1925  2132 D LGBluetoothAPIService: Message: 101
09-06 19:22:52.148  1925  2132 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-06 19:22:52.149  1925  2132 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-06 19:22:52.149  1925  2132 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-06 19:22:52.152  6855  6855 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 19:22:52.188  1029  1907 I ActivityManager: Process com.android.bluetooth (pid 7015) has died
09-06 19:22:52.189  1029  1907 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-06 19:22:52.189  1029  1907 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-06 19:22:52.201  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:52.202  1925  2132 D LGBluetoothAPIService: Message: 2
09-06 19:22:52.202  1925  2132 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-06 19:22:52.202  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:52.203  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:52.205  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:52.206  6855  6855 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 19:22:52.206  6855  6855 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-06 19:22:52.211  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:22:52.213  1587  1587 D BluetoothAdapter: 567499306: getState() :  mService = null. Returning STATE_OFF
09-06 19:22:52.213  1587  1587 D BluetoothAdapter: 567499306: getState() :  mService = null. Returning STATE_OFF
09-06 19:22:52.272  1029  1560 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7723 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-06 19:22:52.274  6855  6855 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:22:52.342  7723  7723 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:22:52.343  7723  7723 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:22:52.343  7723  7723 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-06 19:22:52.344  7723  7723 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:22:52.366  7723  7723 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:22:52.402  7723  7723 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b5477ab Instance Count = 1
,09-06 19:22:52.408  7723  7723 D BluetoothAdapterApp: onCreate
,09-06 19:22:52.442  7723  7723 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 19:22:52.442  7723  7723 D ProfileConfigQcom: Adding HeadsetService
09-06 19:22:52.443  7723  7723 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 19:22:52.443  7723  7723 D ProfileConfigQcom: Adding A2dpService
09-06 19:22:52.444  7723  7723 D ProfileConfigQcom: [BTUI] HidService is supported
,09-06 19:22:52.446  7723  7723 D ProfileConfigQcom: Adding HidService
,09-06 19:22:52.447  7723  7723 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 19:22:52.447  7723  7723 D ProfileConfigQcom: Adding HealthService
09-06 19:22:52.448  7723  7723 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-06 19:22:52.450  7723  7723 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 19:22:52.450  7723  7723 D ProfileConfigQcom: Adding PanService
09-06 19:22:52.450  7723  7723 D ProfileConfigQcom: [BTUI] GattService is supported
,09-06 19:22:52.451  7723  7723 D ProfileConfigQcom: Adding GattService
09-06 19:22:52.451  7723  7723 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 19:22:52.451  7723  7723 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:22:52.451  7723  7723 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 19:22:52.453  7723  7723 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:22:52.454  7723  7723 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:52.454  7723  7723 V BluetoothPbapReceiver: ***********state = 10
09-06 19:22:52.456  7723  7723 V LGMDMManagerInternal: Create singleton instance
09-06 19:22:52.563  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:22:52.574  6855  6855 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:22:52.576  7723  7723 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 19:22:52.576  7723  7723 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 19:22:52.578  6855  6855 D BluetoothPermissionRequest: onReceive
09-06 19:22:52.579  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-06 19:22:52.581  1925  2132 D LGBluetoothAPIService: Message: 100
09-06 19:22:52.581  1925  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:22:52.584  6855  6855 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:22:52.584  6855  6855 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 19:22:52.588  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:22:52.594  7723  7723 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-06 19:22:52.598  7723  7723 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:52.602  7723  7723 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:52.602  7723  7723 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:52.602  7723  7723 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:52.604  7723  7723 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:52.604  7723  7723 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 19:22:52.607  6943  6943 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-06 19:22:54.041  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:22:54.041  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:22:54.107  1029  1423 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:22:54.127  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-06 19:22:54.190  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 19:22:54.224  1029  1089 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7748 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 19:22:54.242  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-06 19:22:54.255  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-06 19:22:54.267  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:22:54.277  1029  1029 D administrator: Handling package changes for user 0
,09-06 19:22:54.324  7748  7748 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:22:54.358  1029  1029 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-06 19:22:54.358  1029  1029 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 19:22:54.423  1029  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:22:54.426  7748  7748 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:54.426  7748  7748 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:22:54.430  1029  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-06 19:22:54.439  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-06 19:22:54.441  2489  2489 V GmsNetworkLocationProvi: DISABLE
09-06 19:22:54.476  1029  1088 D LocationProviderProxy: applying state to connected service
,09-06 19:22:54.479  2489  2489 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-06 19:22:54.608  7748  7793 I Babel   : MmsConfig: mnc/mcc: 0/0
09-06 19:22:54.609  7748  7793 I Babel   : MmsConfig.loadMmsSettings
09-06 19:22:54.620  7748  7793 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 19:22:54.620  7748  7793 I Babel   : MmsConfig.loadFromDatabase
,09-06 19:22:54.651  7748  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-06 19:22:54.652  7748  7793 I Babel   : MmsConfig.loadFromResources
09-06 19:22:54.657  7748  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:22:54.660  7748  7793 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 19:22:54.669  7748  7791 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:22:54.669  7748  7748 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:22:54.670  7748  7791 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 19:22:54.673  7748  7791 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:22:54.689  7748  7791 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-06 19:22:54.691  7748  7791 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 19:22:54.693  7748  7791 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:22:54.706  1801  7795 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-06 19:22:54.706  1801  7795 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-06 19:22:54.706  7748  7791 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:22:54.711  7054  7054 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:22:54.716  7748  7791 W VideoCapabilities: Unsupported mime video/divx
09-06 19:22:54.718  7054  7054 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23e69edd
09-06 19:22:54.718  7054  7054 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:22:54.718  7054  7054 D AppUp4:CustFacade: isPhone : true
09-06 19:22:54.718  7054  7054 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:22:54.719  7054  7054 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-06 19:22:54.725  7748  7791 W VideoCapabilities: Unsupported mime video/divx311
09-06 19:22:54.729  7748  7791 W VideoCapabilities: Unsupported mime video/divx4
,09-06 19:22:54.731  1801  4754 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-06 19:22:54.740  7748  7791 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:22:54.752  1029  1044 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7799 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-06 19:22:54.756  1029  1906 I ActivityManager: Killing 6876:com.lge.sync/1000 (adj 15): empty #17
,09-06 19:22:54.765  7748  7791 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-06 19:22:54.767  1029  1528 D WifiService: Client connection lost with reason: 4
,09-06 19:22:54.781  7748  7791 W AudioCapabilities: Unsupported mime audio/eac3
,09-06 19:22:54.781  7748  7791 W AudioCapabilities: Unsupported mime audio/ac3
09-06 19:22:54.782  7748  7791 W AudioCapabilities: Unsupported mime audio/g726
09-06 19:22:54.783  7748  7791 W AudioCapabilities: Unsupported mime audio/wma-voice
09-06 19:22:54.784  7748  7791 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 19:22:54.785  7748  7791 W AudioCapabilities: Unsupported mime audio/adpcm
09-06 19:22:54.786  7748  7791 W VideoCapabilities: Unsupported mime video/theora
09-06 19:22:54.788  7748  7791 W VideoCapabilities: Unsupported mime video/mjpg
09-06 19:22:54.901  1029  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6876/cgroup.procs: No such file or directory
,09-06 19:22:54.963  7799  7799 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:22:54.964  7799  7799 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:22:54.964  7799  7799 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 19:22:54.965  7799  7799 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-06 19:22:54.966  7799  7799 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-06 19:22:55.025  7799  7799 I SystemConfig: BUILD Country: EU
09-06 19:22:55.025  7799  7799 I SystemConfig: BUILD Operator: OPEN
,09-06 19:22:55.070  1029  1560 I ActivityManager: Killing 7082:com.lge.email/u0a23 (adj 15): empty #17
,09-06 19:22:55.122  1029  1529 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-06 19:22:55.151  1029  1720 W libprocessgroup: failed to open /acct/uid_10023/pid_7082/cgroup.procs: No such file or directory
,09-06 19:22:55.163  7799  7820 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-06 19:22:55.163  7799  7820 I SystemConfig: existFile = false
09-06 19:22:55.163  7799  7820 I SystemConfig: canReadFile = false
,09-06 19:22:55.163  7799  7820 I SystemConfig: systemFeature RCS result false
09-06 19:22:55.163  7799  7820 D SystemConfig: refreshRcsSupport() :false
09-06 19:22:55.201  1029  1715 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7822 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-06 19:22:55.236  7822  7822 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:22:55.236  7822  7822 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:22:55.237  7822  7822 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 19:22:55.237  7822  7822 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 19:22:55.291  7822  7822 I AppConfig: Total System Memory = 2995761152
09-06 19:22:55.297  7822  7822 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-06 19:22:55.382  1029  2015 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7841 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:22:55.384  1029  2015 I ActivityManager: Killing 6963:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-06 19:22:55.478  1029  2034 W libprocessgroup: failed to open /acct/uid_10026/pid_6963/cgroup.procs: No such file or directory
,09-06 19:22:55.658  7841  7841 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-06 19:22:55.790  7841  7841 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:22:55.790  7841  7841 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:22:55.855  7841  7841 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-06 19:22:55.877  7841  7841 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:22:55.879  7841  7841 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:22:55.896  7841  7841 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:22:55.896  7841  7841 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-06 19:22:55.920  1029  2034 I ActivityManager: Killing 6467:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-06 19:22:55.963  1029  1961 W libprocessgroup: failed to open /acct/uid_1000/pid_6467/cgroup.procs: No such file or directory
,09-06 19:22:55.966  2827  2844 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-06 19:22:55.967  2827  2844 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1deef7f1 on behalf of 7841
09-06 19:22:55.973  4607  7881 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-06 19:22:56.024  1029  1960 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7883 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-06 19:22:56.052  7841  7841 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-06 19:22:56.114  7841  7841 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-06 19:22:56.143  7883  7883 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-06 19:22:56.167  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,09-06 19:22:56.167  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-06 19:22:56.167  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-06 19:22:56.167  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-06 19:22:56.167  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-06 19:22:56.167  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-06 19:22:56.186  1029  1906 I ActivityManager: Killing 7123:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-06 19:22:56.203  1029  2016 W libprocessgroup: failed to open /acct/uid_10046/pid_7123/cgroup.procs: No such file or directory
,09-06 19:22:56.420  1029  1960 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:22:56.456  4607  7881 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 482 ms] updated apps [took 482 ms] 
,09-06 19:22:56.606  7633  7705 D UEI.SmartControl: Internal timer expired: 1,
,09-06 19:22:56.607  7633  7705 D UEI.SmartControl: unbind internal service
,09-06 19:22:56.628  7633  7633 D UEI.SmartControl: Service.onUnbind: IControl
,09-06 19:22:56.635  7633  7633 D UEI.SmartControl: Service.onDestroy
09-06 19:22:56.635  7633  7633 D UEI.SmartControl: Lock is in USE false
09-06 19:22:56.636  7633  7633 D UEI.SmartControl: unbind internal service
09-06 19:22:56.636  7633  7633 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@10b34bd9
09-06 19:22:56.637  7633  7633 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-06 19:22:56.638  7633  7633 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-06 19:22:56.638  7633  7633 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-06 19:22:56.638  7633  7633 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-06 19:22:56.638  7633  7633 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-06 19:22:56.638  7633  7633 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-06 19:22:56.638  7633  7633 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-06 19:22:56.638  7633  7633 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-06 19:22:56.639  7633  7633 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:22:56.639  7633  7633 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:22:56.639  7633  7633 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:22:56.643  7633  7633 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:22:56.643  7633  7633 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:22:56.643  7633  7633 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:22:56.643  7633  7633 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:22:56.643  7633  7633 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@10b34bd9
09-06 19:22:56.647  7633  7633 D serial_port: close(fd = 25)
,09-06 19:22:56.653  7633  7633 I UEI.SmartControl: Serial port is closed.
,09-06 19:22:56.653  7633  7633 I UEI.SmartControl: Serial port is closed.
,09-06 19:22:56.653  7633  7633 D UEI.SmartControl: Blaster closed
,09-06 19:22:56.653  7633  7633 D UEI.SmartControl: Shut down QS...
,09-06 19:22:56.653  7633  7633 D UEI.SmartControl: Stopping QS lib
,09-06 19:22:56.654  7633  7633 D UEI.SmartControl: QS lib stop result = true
09-06 19:22:56.654  7633  7633 D UEI.SmartControl: Stopped QS lib
09-06 19:22:56.654  7633  7633 D UEI.SmartControl: Stopped file observer...
,09-06 19:22:56.654  7633  7633 D UEI.SmartControl: QS shutdown complete
09-06 19:22:57.056  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:57.056  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20ebd567 added. We now have 6 listener(s)
,09-06 19:22:57.056  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:22:57.074  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:57.074  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14196f14 added. We now have 7 listener(s)
09-06 19:22:57.074  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:22:57.075  6651  6759 I System.out: IsBluetoothEnabled
09-06 19:22:57.078  1029  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:57.078  1029  2034 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-06 19:22:57.078  1029  1100 D BluetoothManagerService: Message: 2
09-06 19:22:57.082  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:57.085  1029  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:57.085  1029  1906 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-06 19:22:57.102  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:22:57.102  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:22:57.102  1029  1029 D Ulp_jni : JNI:system_update. Event-4
,09-06 19:22:57.106  1029  1100 D BluetoothManagerService: Message: 1
09-06 19:22:57.106  1029  1100 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-06 19:22:57.133  1029  1100 D BluetoothManagerService: Message: 20
09-06 19:22:57.133  1029  1100 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@abd8588:true
,09-06 19:22:57.136  7723  7723 D BluetoothAdapterState: make
09-06 19:22:57.141  7723  7723 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:22:57.142  7723  7723 I bluedroid-qcom: init
09-06 19:22:57.143  7723  7926 I BluetoothAdapterState: Entering OffState
09-06 19:22:57.143  7723  7723 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:22:57.144  7723  7723 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:22:57.144  7723  7723 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:22:57.144  7723  7723 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:22:57.144  7723  7723 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:22:57.146  7723  7723 I bluedroid-qcom: get_profile_interface socket
09-06 19:22:57.146  7723  7723 I bluedroid-qcom: get_profile_interface map_client
,09-06 19:22:57.150  7723  7930 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:22:57.140  7929  7929 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:57.155  7723  7930 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:22:57.140  7929  7929 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:57.165  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:22:57.166  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
,09-06 19:22:57.169  7723  7930 D BluetoothAdapterProperties: Name is: G3
09-06 19:22:57.171  7929  7929 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:22:57.171  7929  7929 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:22:57.171  7929  7929 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-06 19:22:57.172  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 19:22:57.172  1029  1100 D BluetoothManagerService: Message: 40
09-06 19:22:57.173  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 19:22:57.173  7723  7739 I bluedroid-qcom: config_hci_snoop_log
09-06 19:22:57.174  7929  7929 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-06 19:22:57.177  1029  1100 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:22:57.177  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:22:57.179  7929  7929 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:22:57.179  7929  7929 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-06 19:22:57.188  7723  7926 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 19:22:57.189  7723  7926 D BluetoothAdapterProperties: Setting state to 11
09-06 19:22:57.189  7723  7926 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:22:57.190  7723  7926 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 19:22:57.194  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:57.194  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:22:57.194  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-06 19:22:57.201  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:22:57.202  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:57.205  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:57.212  6855  6855 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-06 19:22:57.223  7723  7926 D BluetoothBondStateMachine: make
09-06 19:22:57.225  7723  7723 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:22:57.225  7723  7723 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:57.225  7723  7723 V BluetoothPbapReceiver: ***********state = 11
09-06 19:22:57.230  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:22:57.234  7723  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.234  7723  7926 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:22:57.234  7723  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.234  7723  7926 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 19:22:57.236  7723  7926 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 19:22:57.237  7723  7944 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 19:22:57.241  7723  7926 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:57.243  6855  6855 D BluetoothPermissionRequest: onReceive
,09-06 19:22:57.252  7723  7926 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:57.254  7723  7723 D HeadsetService: Received start request. Starting profile...
,09-06 19:22:57.255  7723  7723 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:22:57.255  7723  7723 D LGBluetoothHfpAdapter: Version 1.6
09-06 19:22:57.256  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 19:22:57.260  7723  7723 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:22:57.261  7723  7926 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:57.262  7723  7723 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:22:57.262  7723  7723 D HeadsetStateMachine: make
09-06 19:22:57.273  7723  7926 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:22:57.278  7723  7926 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:22:57.283  7723  7926 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:22:57.287  7723  7926 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:22:57.302  7723  7723 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:22:57.302  7723  7723 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:22:57.303  7723  7926 V LGMDMManager: Create singleton instance
,09-06 19:22:57.306  7723  7926 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:22:57.307  7723  7723 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:22:57.307  7723  7723 I bluedroid-qcom: get_profile_interface handsfree
09-06 19:22:57.309  7723  7723 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 19:22:57.310   318  2154 V AudioPolicyService: registerClient() client 0xb04100c0, uid 1002
09-06 19:22:57.312   318  1367 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:22:57.312   318  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:22:57.312   318  1367 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:22:57.312  7723  7723 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:22:57.313   318   318 V AudioFlinger: registerClient() client 0xb1014ac0, pid 7723
09-06 19:22:57.314   318  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:57.314   318  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:57.314  1029  1960 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:57.315  1029  1960 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:57.315  1587  2063 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:57.315  1587  2063 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:57.315  3407  3424 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:57.315  3407  3424 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:57.315  1836  2582 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:57.315  1836  2582 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:22:57.315  7723  7740 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:22:57.315   318  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:57.315   318  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:57.315  1836  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:57.315  1836  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:57.316  1029  1907 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:57.316  1029  1907 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:57.316  3407  4887 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:57.316  3407  4887 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:57.316  1587  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:57.316  1587  1606 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:22:57.316  7723  7740 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:22:57.316  7723  7740 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:22:57.316  7723  7740 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:22:57.316  7723  7723 V ToneGenerator: Create Track: 0xb4928a80
09-06 19:22:57.316  7723  7723 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:22:57.316  7723  7723 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:22:57.316   318  2154 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:22:57.316   318  2154 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:22:57.316   318  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:22:57.316   318  2154 V Au,dioPolicyManagerEx: getOutput() returns output 2
09-06 19:22:57.317   318  1367 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:22:57.317   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:22:57.317   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:22:57.317   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:22:57.317   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:22:57.317  7723  7723 V AudioSystem: getLatency() output 2, latency 50
09-06 19:22:57.317  7723  7723 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:22:57.317  7723  7723 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:22:57.317   318  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:22:57.317   318  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:22:57.317   318  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:22:57.317   318  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:22:57.317   318  1366 V AudioFlinger: createTrack() lSessionId: 23
09-06 19:22:57.318  7723  7723 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:22:57.319   318  2154 V AudioFlinger: acquiring 23 from 7723, for 7723
09-06 19:22:57.319   318  2154 V AudioFlinger:  added new entry for 23
09-06 19:22:57.319  7723  7723 V ToneGenerator: ToneGenerator INIT OK, time: 136009
09-06 19:22:57.319  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.320  7723  7947 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:22:57.320  7723  7947 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:22:57.321  7723  7947 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:22:57.321  7723  7947 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:22:57.321  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.321   318  1367 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7723
09-06 19:22:57.322   318  1367 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:22:57.322   318  1367 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:22:57.322   318  1367 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 19:22:57.322   318  1367 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 19:22:57.322   318  1367 V voice   : voice_set_parameters: exit with code(0)
09-06 19:22:57.322   318  1367 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:22:57.322   318  1367 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 19:22:57.322   318  1367 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:22:57.322   318  1367 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:22:57.322   318  1367 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:22:57.322   318  1367 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:22:57.322  7723  7947 V ToneGenerator: ToneGenerator destructor
09-06 19:22:57.322  7723  7947 V ToneGenerator: stopTone
09-06 19:22:57.323  7723  7947 V ToneGenerator: Delete Track: 0xb4928a80
09-06 19:22:57.323   318   318 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 19:22:57.323   318   318 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:22:57.323   318   318 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:22:57.323   318  1256 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:22:57.323   318   318 V AudioFlinger: removeClient_l() pid 7723, calling pid 318
09-06 19:22:57.323   318  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:22:57.323   318  1256 V AudioPolicyManager: releaseOutput() 2
09-06 19:22:57.323   318  1256 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 19:22:57.323  7723  7947 V AudioTrack: ~AudioTrack, releasing session id from 7723 on behalf of 7723
09-06 19:22:57.324   318  1367 V AudioFlinger: releasing 23 from 7723 for 7723
09-06 19:22:57.324   318  1367 V AudioFlinger:  decremented refcount to 0
09-06 19:22:57.324   318  1367 V AudioFlinger: purging stale effects
09-06 19:22:57.324  7723  7723 D A2dpService: Received start request. Starting profile...
09-06 19:22:57.325  7723  7723 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:22:57.325  1029  2016 W Process : Unable to open /proc/7950/status
09-06 19:22:57.326  7723  7723 V Avrcp   : make
09-06 19:22:57.326  7723  7723 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:22:57.326  7723  7723 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:22:57.337  7723  7723 V AudioManager: registerRemoteController: size of Media player list: 0
09-06 19:22:57.339  7723  7723 E AudioManager: No RCC entry present to update
09-06 19:22:57.339  7723  7723 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:22:57.344  7723  7723 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,09-06 19:22:57.346  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:22:57.346  7723  7723 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 19:22:57.350  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:22:57.499  1029  1961 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:22:57.499  1029  1961 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:22:57.605  1029  1906 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:22:57.614  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 19:22:57.619  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:22:57.621  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-06 19:22:57.621  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:22:57.621  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:22:57.622  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:22:57.622  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:22:57.622  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:22:57.622  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:22:57.622  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:22:57.623  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:22:57.624  7723  7723 I BluetoothA2dpServiceJni: classInitNative
09-06 19:22:57.624  7723  7723 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:22:57.624  7723  7723 D A2dpStateMachine: make
09-06 19:22:57.626  7723  7723 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:22:57.626  7723  7958 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:22:57.629  7723  7723 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:22:57.629  7723  7723 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:22:57.630  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.630  7723  7957 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:22:57.632  7723  7723 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:22:57.634  7723  7723 D HidService: Received start request. Starting profile...
09-06 19:22:57.634  7723  7723 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:22:57.634  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.635  7723  7723 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:22:57.637  7723  7723 D HealthService: Received start request. Starting profile...
,09-06 19:22:57.640  7723  7723 I bluedroid-qcom: get_profile_interface health
09-06 19:22:57.640  7723  7723 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:22:57.640  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.641  7723  7723 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:22:57.642  7723  7723 D PanService: Received start request. Starting profile...
09-06 19:22:57.642  7723  7723 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-06 19:22:57.642  7723  7723 I bluedroid-qcom: get_profile_interface pan
09-06 19:22:57.649  7723  7723 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 19:22:57.649  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.650  7723  7723 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-06 19:22:57.660  7723  7723 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:22:57.661  7723  7723 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:22:57.661  7723  7723 D BtGatt.GattService: start()
09-06 19:22:57.661  7723  7723 I bluedroid-qcom: get_profile_interface gatt
09-06 19:22:57.662  7723  7723 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:22:57.673  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:57.675  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
,09-06 19:22:57.676  7723  7723 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:22:57.677  7723  7723 V BluetoothMapService: BluetoothMapBinder()
09-06 19:22:57.678  7723  7723 D BluetoothMapService: Received start request. Starting profile...
09-06 19:22:57.678  7723  7723 D BluetoothMapService: start()
09-06 19:22:57.682  7723  7723 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 19:22:57.682  7723  7723 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:22:57.683  7723  7723 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:22:57.683  7723  7723 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 19:22:57.693  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
,09-06 19:22:57.693  7723  7723 D HeadsetStateMachine: Proxy object connected
,09-06 19:22:57.694  7723  7723 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:22:57.694  7723  7723 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-06 19:22:57.699  7723  7723 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:22:57.700  7723  7947 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:22:57.701  7723  7947 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:22:57.701  7723  7947 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-06 19:22:57.704  7723  7723 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:22:57.706  7723  7723 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:22:57.713  7723  7723 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:22:57.717  7723  7723 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:22:57.721  7723  7723 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:22:57.721  7723  7723 V PanService: [BTUI] SIM Extra State :ABSENT
,09-06 19:22:57.725  7723  7723 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 19:22:57.726  7723  7723 V BluetoothMapService: Handler(): got msg=1
09-06 19:22:57.727  7723  7926 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:22:57.727  7723  7926 I bluedroid-qcom: enable
09-06 19:22:57.728  7723  7723 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:57.728  7723  7723 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:57.728  7723  7723 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:57.728  7723  7723 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:57.729  7723  7723 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:22:57.729  7723  7965 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:22:57.729  7723  7926 I bt_hci_bdroid: init
09-06 19:22:57.729  7723  7965 I bt-btu  : btu_task pending for preload complete event
09-06 19:22:57.736  7723  7926 I bt_vendor: bt-vendor : init
09-06 19:22:57.736  7723  7926 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:22:57.736  7723  7926 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:22:57.736  7723  7926 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:22:57.736  7723  7926 D bt_userial_mct: userial_init
09-06 19:22:57.737  7723  7926 D bt_hci_bdroid: set_power 1
09-06 19:22:57.737  7723  7926 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-06 19:22:57.737  7723  7926 I bt_vendor: Starting hciattach daemon
09-06 19:22:57.737  7723  7926 I bt_vendor: try to set true
09-06 19:22:57.730  7968  7968 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:57.730  7968  7968 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:57.781  7969  7969 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:22:57.915  7975  7975 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:22:57.944  7976  7976 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:22:57.972  7978  7978 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:22:57.984  7979  7979 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 19:22:57.998  7980  7980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:22:58.010  7981  7981 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:22:58.053  7983  7983 I libmdmdetect: ESOC framework not supported
09-06 19:22:58.053  7983  7983 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 19:22:58.062  7983  7983 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-06 19:22:58.062  7983  7983 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-06 19:22:58.062  7983  7983 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,09-06 19:22:58.062  7983  7983 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,09-06 19:22:58.062  7983  7983 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 19:22:58.062  7983  7983 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:22:58.062  7983  7983 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 19:22:58.100  7983  7987 E QC-QMI  : qmi_client [7983] 15: failed to locate client data
,09-06 19:22:58.109   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-06 19:22:58.109   483   483 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-06 19:22:58.139  7991  7991 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 19:22:58.154  7992  7992 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:22:58.172  7723  7926 I bt_vendor: bluetooth satus is on
09-06 19:22:58.172  7723  7926 D bt_hci_bdroid: preload
,09-06 19:22:58.176  7723  7967 D bt_userial_mct: userial_open(port:0)
09-06 19:22:58.176  7723  7967 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-06 19:22:58.179  7723  7967 I bt_vendor: Done intiailizing UART
09-06 19:22:58.180  7723  7967 I bt_vendor: Done intiailizing UART
09-06 19:22:58.180  7723  7967 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:22:58.180  7723  7967 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:22:58.181  7723  7965 I bt-btu  : btu_task received preload complete event
09-06 19:22:58.181  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:22:58.181  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 19:22:58.182  7723  7994 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:22:58.184  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_A2D,
09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_BNEP,
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-06 19:22:58.190  7723  7965 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:22:58.191  7723  7965 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:22:58.191  7723  7965 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:22:58.191  7723  7965 I         : BTE_InitTraceLevels -- TRC_GATT,
09-06 19:22:58.191  7723  7965 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:22:58.191  7723  7965 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:22:58.191  7723  7965 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:22:58.291  7723  7965 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-06 19:22:58.291  7723  7965 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
09-06 19:22:58.292  7723  7965 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,09-06 19:22:58.331  7723  7930 E bt-btif : Calling BTA_HhEnable
09-06 19:22:58.331  7723  7930 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 19:22:58.331  7723  7930 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 19:22:58.334  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 19:22:58.334  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 19:22:58.334  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 19:22:58.335  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:22:58.335  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:22:58.336  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:22:58.336  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
,09-06 19:22:58.337  7723  7930 D BluetoothAdapterProperties: Name is: G3
09-06 19:22:58.338  7723  7930 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:22:58.338  7723  7930 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:22:58.338  7723  7930 D bt_hci_bdroid: postload
09-06 19:22:58.338  7723  7967 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:58.339  7723  7967 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:58.340  7723  7930 D bte_conf: Device ID record 1 : primary
09-06 19:22:58.340  7723  7930 D bte_conf:   vendorId            = 00c4
09-06 19:22:58.340  7723  7930 D bte_conf:   vendorIdSource      = 0001
09-06 19:22:58.340  7723  7930 D bte_conf:   product             = 13a1
09-06 19:22:58.340  7723  7930 D bte_conf:   version             = 1000
09-06 19:22:58.340  7723  7930 D bte_conf:   clientExecutableURL = 
09-06 19:22:58.340  7723  7930 D bte_conf:   serviceDescription  = 
09-06 19:22:58.340  7723  7930 D bte_conf:   documentationURL    = 
09-06 19:22:58.340  7723  7930 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:22:58.341  7723  7965 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:22:58.341  7723  7967 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:58.344  7723  7926 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:22:58.344  7723  7926 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:22:58.344  7723  7926 D BluetoothAdapterProperties: State =  11
09-06 19:22:58.345  7723  7926 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,09-06 19:22:58.351  7723  7926 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:22:58.340  7996  7996 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:58.353  7723  7926 D BluetoothAdapterProperties: Setting state to 12
09-06 19:22:58.353  7723  7926 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:22:58.353  7723  7930 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:22:58.354  7723  7930 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:22:58.340  7996  7996 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:58.360  1029  1100 D BluetoothManagerService: Message: 60
09-06 19:22:58.360  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:22:58.360  1029  1100 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-06 19:22:58.369  7723  7967 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:22:58.372  7723  7994 E bt_mct  : hci lib postload completed
,09-06 19:22:58.378  7723  7965 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:58.378  7723  7965 W bt-smp  : Plain text(LSB ~ MSB) = ad 06 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:58.378  7723  7965 W bt-smp  : Encrypted text(LSB ~ MSB) = f4 24 2d b1 6e fd 29 b5 8f 3f 4f 01 02 1a db f4 
09-06 19:22:58.378  7723  7965 W bt-btm  : Stopping oneshot timer
09-06 19:22:58.380  7723  7926 I BluetoothAdapterState: Entering On State
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:58.396  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:22:58.405  7723  7930 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:22:58.405  7723  7930 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 19:22:58.407  7723  7965 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:58.407  7723  7965 W bt-smp  : Plain text(LSB ~ MSB) = 26 a7 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:58.407  7723  7965 W bt-smp  : Encrypted text(LSB ~ MSB) = 18 9c de c8 d3 5e 8b 05 48 9a 86 41 49 3d 5f b3 
09-06 19:22:58.408  7723  7965 W bt-btm  : Stopping oneshot timer
,09-06 19:22:58.419  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:22:58.429  7723  7926 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:22:58.430  7723  7926 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:22:58.430  7723  7926 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 19:22:58.436  7723  7926 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:22:58.436  7723  7926 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-06 19:22:58.439  7723  7965 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:58.439  7723  7965 W bt-smp  : Plain text(LSB ~ MSB) = 09 22 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:58.439  7723  7965 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 ff 47 0d 99 cb 38 70 af da 99 b1 85 4b 84 b2 
09-06 19:22:58.440  7723  7965 W bt-btm  : Stopping oneshot timer
,09-06 19:22:58.440  6855  6872 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:22:58.466  1836  2563 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:22:58.470  8006  8006 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 19:22:58.472  6855  6855 D BluetoothHeadset: Proxy object connected
09-06 19:22:58.472  6855  6855 D HeadsetProfile: Bluetooth service connected
09-06 19:22:58.474  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:22:58.474  6855  7602 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:22:58.476  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:22:58.477  7723  7965 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:58.478  7723  7965 W bt-smp  : Plain text(LSB ~ MSB) = c0 74 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:58.478  7723  7965 W bt-smp  : Encrypted text(LSB ~ MSB) = 14 8a f9 67 1a 4a 39 5a 32 c5 c9 08 e8 e0 99 fc 
09-06 19:22:58.478  7723  7965 W bt-btm  : Stopping oneshot timer
09-06 19:22:58.478  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:22:58.478  1836  2582 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:22:58.480  1836  1836 D BluetoothHeadset: Proxy object connected
,09-06 19:22:58.480  1029  1100 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:22:58.481  6855  6872 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:22:58.482  1029  1029 D BluetoothA2dp: Proxy object connected
09-06 19:22:58.484  6855  7602 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:22:58.485  6855  6855 D BluetoothA2dp: Proxy object connected
09-06 19:22:58.485  6855  6855 D A2dpProfile: Bluetooth service connected
09-06 19:22:58.486  1029  1100 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:22:58.487  1029  1029 D BluetoothHeadset: Proxy object connected
09-06 19:22:58.488  6855  6874 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:22:58.488  6855  6874 D BluetoothPan: onBluetoothStateChange call bindService
09-06 19:22:58.488  6855  6855 D BluetoothMap: Proxy object connected
09-06 19:22:58.488  6855  6855 D MapProfile: Bluetooth service connected
09-06 19:22:58.488  6855  6855 D BluetoothMap: getConnectedDevices()
09-06 19:22:58.490  7723  8014 V BluetoothMapService: getConnectedDevices()
09-06 19:22:58.491  6855  7602 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:22:58.492  6855  6855 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:22:58.492  6855  6855 D PanProfile: Bluetooth service connected
09-06 19:22:58.494  7723  7965 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:22:58.495  7723  7965 W bt-smp  : Plain text(LSB ~ MSB) = f7 66 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:22:58.495  7723  7965 W bt-smp  : Encrypted text(LSB ~ MSB) = 26 07 d3 75 c6 81 dc 0f 72 fa 8d 38 cc 8e a1 70 
09-06 19:22:58.495  7723  7965 W bt-btm  : Stopping oneshot timer
09-06 19:22:58.496  6855  6855 D BluetoothInputDevice: Proxy object connected
09-06 19:22:58.496  6855  6855 D HidProfile: Bluetooth service connected
09-06 19:22:58.497  1029  1100 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:22:58.497  1029  1100 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 19:22:58.498  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:22:58.498  1029  1100 D BluetoothManagerService: Message: 40
09-06 19:22:58.498  1029  1100 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:22:58.498  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.500  1925  2132 D LGBluetoothAPIService: Message: 1
09-06 19:22:58.500  1925  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:22:58.500  1925  2132 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-06 19:22:58.500  1925  2132 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 19:22:58.500  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:22:58.504  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:22:58.505  7723  7723 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.505  7723  7723 D BluetoothMapService: STATE_ON
09-06 19:22:58.510  6855  6855 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-06 19:22:58.511  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:22:58.518  6855  6855 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:22:58.523  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:58.523  7723  7723 V BluetoothPbapService: Pbap Service onCreate
09-06 19:22:58.524  7723  7723 V BluetoothPbapService: Starting PBAP service
09-06 19:22:58.525  7723  7723 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:22:58.525  7723  7723 V BluetoothMapService: Handler(): got msg=1
09-06 19:22:58.525  7723  7723 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:22:58.526  7723  7723 V BluetoothPbapService: Pbap Service onBind
09-06 19:22:58.527  7723  8019 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:22:58.527  7723  7723 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.527  6855  6855 D BluetoothPbap: Proxy object connected
09-06 19:22:58.527  7723  7723 V BluetoothPbapService: state: 12
09-06 19:22:58.527  6855  6855 D PbapServerProfile: Bluetooth service connected
09-06 19:22:58.527  7723  7723 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:22:58.527  7723  8019 D BluetoothMapMasInstance:   masId = 00
09-06 19:22:58.527  7723  8019 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:22:58.527  7723  8019 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:22:58.527  7723  8019 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 19:22:58.527  7723  7723 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.527  7723  7723 V BluetoothPbapReceiver: ***********state = 12
09-06 19:22:58.528  7723  7723 V BluetoothPbapService: Handler(): got msg=1
09-06 19:22:58.528  1029  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:58.529  7723  7723 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:22:58.530  7723  8020 V BluetoothPbapService: Pbap Service initSocket
09-06 19:22:58.530  2138  2138 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:22:58.533  1029  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:58.533  2138  2138 D c       : Getting all permits...
09-06 19:22:58.533  2138  2138 D a       : Opening database...
09-06 19:22:58.534  7723  8019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:58.536  7723  8020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:58.537  2138  2138 D a       : Opening database auth.proximity.permit_store...
09-06 19:22:58.538  7723  7930 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:22:58.538  7723  8020 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:22:58.538  2138  2138 D a       : Closing database...
09-06 19:22:58.538  7723  8020 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:22:58.538  7723  8020 V BluetoothPbapService: Accepting socket connection...
09-06 19:22:58.538  7723  8019 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 19:22:58.538  7723  8019 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:22:58.538  7723  8019 D BluetoothMapMasInstance: Accepting socket connection...
09-06 19:22:58.538  7723  7930 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:22:58.540  7723  7930 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:22:58.540  7723  7930 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:22:58.540  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:58.541  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:58.551  6855  6855 D BluetoothPermissionRequest: onReceive
,09-06 19:22:58.553  6855  6855 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:22:58.554  6855  6855 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:22:58.557  7723  7723 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 19:22:58.558  7723  7723 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:22:58.564  7723  7723 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 19:22:58.581  7723  7723 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 19:22:58.581  7723  7723 V BtOppService: onCreate
09-06 19:22:58.585  7723  7723 V BluetoothOppNotification: send message
09-06 19:22:58.588  7723  7723 V BtOppService: Starting RfcommListener
09-06 19:22:58.597  7723  7723 D BluetoothOppPreference: Dumping Names:  
,09-06 19:22:58.597  7723  7723 D BluetoothOppPreference: {}
09-06 19:22:58.597  7723  7723 D BluetoothOppPreference: Dumping Channels:  
09-06 19:22:58.597  7723  7723 D BluetoothOppPreference: {}
09-06 19:22:58.598  7723  7723 V BtOppService: onStartCommand
09-06 19:22:58.602  7723  8030 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:22:58.602  7723  7723 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.602  7723  7723 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:22:58.603  7723  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:22:58.604  7723  8026 V BtOppService: Deleted complete outbound shares, number =  0
09-06 19:22:58.605  7723  7723 V BluetoothOppNotification: new notify threadi!
09-06 19:22:58.606  7723  7723 V BluetoothOppNotification: send delay message
09-06 19:22:58.607  7723  7723 V BtOppService: start RfcommListener
09-06 19:22:58.608  7723  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fa5a4dc on behalf of 
09-06 19:22:58.609  7723  8026 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 19:22:58.610  7723  8026 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:22:58.611  7723  8030 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:22:58.611  7723  8026 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fea69e5 on behalf of 
09-06 19:22:58.612  7723  7723 V BtOppService: RfcommListener started
09-06 19:22:58.612  7723  7723 V BtOppService: ContentObserver received notification
09-06 19:22:58.613  7723  8032 V BtOppRfcommListener: Starting RFCOMM listener....
,09-06 19:22:58.615  1029  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:58.616  7723  8030 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:22:58.616  7723  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:22:58.617  7723  8032 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:58.618  7723  8032 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-06 19:22:58.618  7723  8032 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:22:58.618  7723  8032 I BtOppRfcommListener: Accept thread started.
09-06 19:22:58.618  7723  8032 V BtOppRfcommListener: Accepting connection...
09-06 19:22:58.619  7723  8031 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:22:58.629  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
09-06 19:22:58.629  7723  7723 V BluetoothFtpService: Ftp Service onCreate
09-06 19:22:58.629  7723  7723 I BluetoothFtpService: Ftp Service onCreate
09-06 19:22:58.630  7723  7723 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:22:58.630  7723  7723 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.630  7723  7723 V BluetoothFtpService: Starting Listening on sockets
09-06 19:22:58.630  7723  7723 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:22:58.630  7723  7723 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:22:58.630  7723  7723 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:22:58.630  7723  7723 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.630  7723  7723 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 19:22:58.631  7723  7723 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-06 19:22:58.736  1029  1045 I art     : Explicit concurrent mark sweep GC freed 26500(1296KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.602ms total 116.011ms
09-06 19:22:58.736  7723  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b9f476b on behalf of 
09-06 19:22:58.737  7723  8030 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-06 19:22:58.739  7723  8031 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@125632c8 on behalf of 
09-06 19:22:58.740  7723  8031 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:22:58.740  7723  7723 V BtOppService: ContentObserver received notification
09-06 19:22:58.740  7723  7723 V BluetoothFtpService: Handler(): got msg=1
09-06 19:22:58.741  7723  7723 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:22:58.741  7723  7723 V BluetoothFtpService: Ftp Service initSocket
,09-06 19:22:58.742  7723  8031 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:58.744  7723  8031 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20dcbf61 on behalf of 
09-06 19:22:58.746  7723  8033 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:22:58.746  7723  8033 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:22:58.746  7723  8031 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:22:58.748  7723  8033 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26533a86 on behalf of 
09-06 19:22:58.748  7723  8033 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:22:58.748  7723  8033 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:22:58.749  7723  8031 V BluetoothOppNotification: outbound notification was removed.
09-06 19:22:58.749  7723  8031 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:58.750  7723  8031 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36e8ef47 on behalf of 
09-06 19:22:58.751  1029  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:58.751  7723  8031 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-06 19:22:58.755  7723  7723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:22:58.755  7723  8031 V BluetoothOppNotification: inbound notification was removed.
09-06 19:22:58.755  7723  7723 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-06 19:22:58.756  7723  8031 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:22:58.756  7723  7723 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:22:58.758  7723  8034 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 19:22:58.759  7723  8031 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31ffb374 on behalf of 
09-06 19:22:58.785  7723  7723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a5c620
,09-06 19:22:58.785  7723  7723 V BluetoothSapService: Sap Service onCreate
09-06 19:22:58.787  7723  7723 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:22:58.787  7723  7723 V BluetoothSapService: state: 12
09-06 19:22:58.787  7723  7723 V BluetoothSapService: Starting SAP server process
,09-06 19:22:58.789  7723  7723 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-06 19:22:58.790  7723  8036 V BluetoothSapService: Sap Service initRfcommSocket
,09-06 19:22:58.780  8035  8035 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:58.791  1029  1720 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:22:58.780  8035  8035 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:22:58.796  7723  8036 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:22:58.796  8035  8035 V BT_SAP  : Event pipe created
09-06 19:22:58.796  8035  8035 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:22:58.796  8035  8035 V BT_SAP  : created socket fd 6
09-06 19:22:58.797  7723  8036 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 19:22:58.797  7723  8036 V BluetoothSapService: Succeed to create listening socket 
09-06 19:22:58.797  7723  8036 V BluetoothSapService: Accepting socket connection...
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:22:59.181  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:22:59.188  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:22:59.190  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:22:59.190  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2493bd added. We now have 8 listener(s)
09-06 19:22:59.192  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:22:59.195  1029  1720 D WifiServiceImplEx: setWifiEnabled: false pid=6651, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:22:59.195  1029  1720 D WifiService: setWifiEnabled: false pid=6651, uid=10118
09-06 19:22:59.195  1029  1720 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:22:59.203  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:22:59.204  1029  1942 D WifiServiceImplEx: setWifiEnabled: true pid=6651, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:22:59.205  1029  1942 D WifiService: setWifiEnabled: true pid=6651, uid=10118
09-06 19:22:59.205  1029  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:22:59.219  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 19:22:59.219  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-06 19:22:59.219  1029  1029 D Ulp_jni : JNI:system_update. Event-4
,09-06 19:22:59.221  1029  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-06 19:22:59.221  1029  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288,
,09-06 19:22:59.223  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 19:22:59.223  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:22:59.223  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-06 19:22:59.223  1029  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
,09-06 19:22:59.223  1029  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,09-06 19:22:59.224  1029  1523 E WifiHW  : unknown target_country: EU , set to default
09-06 19:22:59.224  1029  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 19:22:59.224  1029  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-06 19:22:59.224  1029  1523 I WifiUtil: gEnableBmps=1
09-06 19:22:59.608  7723  7723 V BluetoothOppNotification: new notify threadi!
,09-06 19:22:59.631  7723  7723 V BluetoothOppNotification: send delay message
09-06 19:22:59.634  7723  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:22:59.636  7723  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f1e92e0 on behalf of 
09-06 19:22:59.636  7723  8049 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:22:59.638  7723  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:59.639  7723  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a04f999 on behalf of 
09-06 19:22:59.639  7723  8049 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:22:59.641  7723  8049 V BluetoothOppNotification: outbound notification was removed.
09-06 19:22:59.641  7723  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:22:59.642  7723  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d81145e on behalf of 
09-06 19:22:59.642  7723  8049 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-06 19:22:59.648  7723  8049 V BluetoothOppNotification: inbound notification was removed.
,09-06 19:22:59.648  7723  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:22:59.649  7723  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2de803f on behalf of 
09-06 19:22:59.912   312   887 D SoftapController: Softap fwReload - Ok
,09-06 19:22:59.917  1029  1523 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (689ms)
09-06 19:22:59.931   312   887 D CommandListener: Setting iface cfg
09-06 19:22:59.931   312   887 D CommandListener: Trying to bring down wlan0
,09-06 19:22:59.950   312   887 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:22:59.962  1029  1100 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 19:23:00.001  1029  1368 D PowerManagerServiceEx: acquireWakeLockInternal: lock=320048290, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,09-06 19:23:00.027  1029  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-06 19:23:00.027  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-06 19:23:00.027  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-06 19:23:00.028  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:23:00.028  6855  6855 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-06 19:23:00.037  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:23:00.037  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:23:00.037  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:23:00.030  8070  8070 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:23:00.030  8070  8070 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:23:00.042  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 19:23:00.042  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-06 19:23:00.046  1029  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:23:00.046  1029  1523 D WifiMonitor: connecting to supplicant
09-06 19:23:00.047  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:23:00.048  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:00.049  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:00.064  8070  8070 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 19:23:00.064  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-06 19:23:00.064  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-06 19:23:00.064  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-06 19:23:00.064  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-06 19:23:00.073  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-06 19:23:00.073  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-06 19:23:00.074  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-06 19:23:00.074  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-06 19:23:00.076  2564  2564 D [Concierge]Service: onStartCommand(). Type : 9
09-06 19:23:00.078  6855  6855 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:23:00.078  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:23:00.078  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:23:00.078  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:23:00.078  6855  6855 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:23:00.078  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:23:00.079  6855  6855 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:23:00.100  8070  8070 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:23:00.101  8070  8070 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-06 19:23:00.103  1029  1100 D Tethering: InitialState.processMessage what=4
09-06 19:23:00.131  1029  1715 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=8074 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-06 19:23:00.137  1029  1100 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:23:00.164   352   352 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 32.942ms
,09-06 19:23:00.188  8070  8070 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:23:00.194   352   352 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 28.890ms
,09-06 19:23:00.195  8074  8074 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:23:00.206   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 11.748ms
,09-06 19:23:00.216  8074  8074 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-06 19:23:00.248  8074  8074 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-06 19:23:00.249  8074  8074 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,09-06 19:23:00.249  8074  8074 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:23:00.250  8074  8074 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:23:00.250  8074  8074 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:23:00.253  8074  8074 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 19:23:00.258  8074  8074 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 19:23:00.271  8074  8074 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-06 19:23:00.272  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6877
09-06 19:23:00.273  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=320048290 [*alarm*], flags=0x0
,09-06 19:23:00.274  8074  8074 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 19:23:00.278  8070  8070 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-06 19:23:00.281  8074  8074 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 19:23:00.284  8070  8070 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-06 19:23:00.285  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-06 19:23:00.286  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-06 19:23:00.286  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,09-06 19:23:00.286  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,09-06 19:23:00.286  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,09-06 19:23:00.286  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:23:00.286  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:23:00.287  1029  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:23:00.287  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:00.288  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:00.288  1029  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:00.289  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:00.290  1029  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:23:00.290  1029  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 19:23:00.290  1029  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 19:23:00.290  1029  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:23:00.291  1029  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-06 19:23:00.347  1029  1715 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8094 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-06 19:23:00.351  1029  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:23:00.351  1029  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:23:00.351  1029  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:23:00.351  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.351  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.351  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.351  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.351  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:23:00.351  1029  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:23:00.354  1029  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-06 19:23:00.354  1029  1523 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:23:00.354  1029  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:23:00.355  1029  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:23:00.356  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:00.357  1925  1925 D WfdService: Waiting for WifiP2p enabling
,09-06 19:23:00.360  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:23:00.361  1029  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:23:00.364  6651  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:23:00.364  1029  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 19:23:00.366  6651  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:23:00.377  1029  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-06 19:23:00.378  1029  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:23:00.379  1029  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:23:00.379  1029  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 19:23:00.380  1029  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:23:00.380  1029  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:23:00.380  1029  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:23:00.380  1029  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:23:00.380  1029  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:23:00.380  1029  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:23:00.381  1029  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:23:00.381  1029  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:23:00.381  1029  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:23:00.381  1029  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-06 19:23:00.382  1029  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:23:00.382  1029  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 19:23:00.382  1029  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 19:23:00.383  1029  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:23:00.383  1029  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 19:23:00.383  1925  1925 D WfdsService: Supplicant Connection state is changed : true
09-06 19:23:00.383  1029  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 19:23:00.383  1925  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:23:00.383  1029  1523 D WifiNative-HAL: Setting external_sim to 1
09-06 19:23:00.383  1925  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:23:00.383  1029  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 19:23:00.383  1925  2324 D WfdsMonitor: WfdsMonitorThread create
09-06 19:23:00.384  1925  2324 D WfdsMonitor: WFDS Monitor is created and started
09-06 19:23:00.384  1029  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:23:00.384  1925  2324 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:23:00.384  1029  1523 I WifiNative-HAL: startHal
09-06 19:23:00.384  1029  1523 D wifi    : setting scan oui 0x95316420
09-06 19:23:00.384  7748  7748 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.384  1029  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:23:00.384  1029  1523 I WifiNative-HAL: startHal
09-06 19:23:00.384  1029  1523 D wifi    : setting scan oui 0x95316420
09-06 19:23:00.384  1029  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 19:23:00.385  1029  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
,09-06 19:23:00.385  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 19:23:00.385  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 19:23:00.385  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 19:23:00.385  1925  8110 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:23:00.386  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:23:00.386  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:23:00.386  1925  8110 E CtrlSupplicant: Succeed to open control connection
09-06 19:23:00.386  1925  8110 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:23:00.386  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:23:00.386  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:23:00.386  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 19:23:00.387  1925  8110 D WfdsMonitor: Supplicant connection established
09-06 19:23:00.387  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:23:00.387  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:23:00.387  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:23:00.387  1925  2324 D WfdsService: Connected to the supplicant for wfds
09-06 19:23:00.388  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:23:00.388  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:23:00.388  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:23:00.388  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:23:00.388  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 19:23:00.388  8070  8070 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:23:00.389  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 19:23:00.389  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:23:00.389  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:23:00.389  1029  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:23:00.390  1029  1523 E WifiNative: : [139,068,506 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 19:23:00.390  1029  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:23:00.391  1029  1523 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:23:00.391  1029  1523 D WifiNative-wlan0: doString: [STATUS]
09-06 19:23:00.391  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:23:00.392  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:23:00.394  1029  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:23:00.394  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:23:00.394  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:23:00.394  1029  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.396   312   887 D CommandListener: Setting iface cfg
09-06 19:23:00.396   312   887 D CommandListener: Trying to bring up p2p0
09-06 19:23:00.396  1029  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:23:00.396  1029  1522 D LGWifiP2pService: P2pEnablingState
09-06 19:23:00.396  1029  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.397  1029  1522 D LGWifiP2pService: P2p socket connection successful
09-06 19:23:00.397  1029  1522 D LGWifiP2pService: P2pEnabledStat,e
09-06 19:23:00.397  1029  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:23:00.398  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:23:00.398  1925  1925 D WfdsService: WifiP2pState is changed : true
09-06 19:23:00.398  1925  2324 D WfdsService: Receive the WFDS_ENABLE Method
09-06 19:23:00.398  1925  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:23:00.398  1925  2324 D WfdsService: Connected to the supplicant for wfds
09-06 19:23:00.398  1925  2324 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 19:23:00.398  8070  8070 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 19:23:00.398  1925  2324 D WfdsService: selectPreferredScanChannel [36]
09-06 19:23:00.398  1925  2324 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 19:23:00.399  1029  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:23:00.400  1029  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:23:00.400  1029  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:23:00.401  1029  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 19:23:00.401  1029  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:23:00.402  1029  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 19:23:00.402  1029  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:23:00.402  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:23:00.402  1029  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:23:00.403  1029  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 19:23:00.403  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:23:00.403  1029  1029 D RttService: SCAN_AVAILABLE : 3
09-06 19:23:00.403  8070  8070 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:23:00.403  1925  1925 D WfdsService: isConnected: false
09-06 19:23:00.403  1029  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.403  1029  1541 I WifiNative-HAL: startHal
09-06 19:23:00.404  1029  1542 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.406  1029  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 19:23:00.406  1029  1541 D wifi    : getting scan capabilities on interface[1] = 0x95316420
09-06 19:23:00.406  1029  1541 D wifi    : failed to get capabilities : -3
09-06 19:23:00.406  1029  1541 E WifiScanningService: could not get scan capabilities
09-06 19:23:00.406  1029  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
,09-06 19:23:00.407  1029  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-06 19:23:00.407  1029  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:23:00.407  1029  1522 D LGWifiP2pService: before postfix = G3
09-06 19:23:00.407  1029  1522 D WifiServerServiceExt: postfix byte check : 2
09-06 19:23:00.407  1029  1522 D LGWifiP2pService: after postfix = G3
09-06 19:23:00.407  1029  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 19:23:00.408  1029  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:23:00.408  1029  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:23:00.408  1029  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:23:00.408  1029  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 19:23:00.408  1029  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 19:23:00.409  1029  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:23:00.409  1029  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 19:23:00.409  1029  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:23:00.410  1029  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-06 19:23:00.410  1029  1522 D LGWifiP2pService: DeviceAddress: 
09-06 19:23:00.410  1029  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 19:23:00.410  1029  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:23:00.411  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:23:00.411  1029  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:23:00.411  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:23:00.411  1925  1925 D WfdsService: Update P2p Interface State: 3
09-06 19:23:00.411  1029  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 19:23:00.411  1029  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 19:23:00.411  1029  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:23:00.411  1029  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 19:23:00.411  8070  8070 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 19:23:00.411  1029  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:23:00.412  1029  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:23:00.412  1029  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:23:00.412  1029  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 19:23:00.412  1029  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 19:23:00.412  1029  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:23:00.412  1029  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:23:00.412  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,09-06 19:23:00.423  1029  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 19:23:00.423  1029  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:23:00.424  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:23:00.424  8070  8070 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.424  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:23:00.424  1029  1522 D LGWifiP2pService: InactiveState
09-06 19:23:00.424  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.425  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.425  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.425  1029  1522 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.425  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.425  1029  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 19:23:00.425  8070  8070 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:23:00.425  8070  8070 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.425  1925  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:23:00.425  1029  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:23:00.425  1029  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.425  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.425  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.426  1029  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:23:00.426  8070  8070 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.426  1029  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:23:00.427  1029  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:23:00.427  1925  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:23:00.427  1029  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:23:00.427  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:23:00.427  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:23:00.427  1029  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:23:00.427  1029  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.427  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.427  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.427  8070  8070 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.428  1029  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:23:00.428  1029  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.428  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.428  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:23:00.428  1925  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE in,it=USER type=COUNTRY alpha2=CZ]
09-06 19:23:00.428  8070  8070 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:23:00.428  8070  8070 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.428  1925  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:23:00.428  1029  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:23:00.428  1029  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.429  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.429  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.429  1029  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:23:00.429  1029  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.429  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.429  1029  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.429  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:23:00.429  8070  8070 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:23:00.430  1029  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.430  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.430  1029  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.430  1029  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.430  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.430  8070  8070 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.430  1029  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:23:00.430  1029  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:23:00.431  1925  2324 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 19:23:00.431  1029  1522 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.431  1029  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.431  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.431  1925  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-06 19:23:00.431  1029  1522 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.431  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:23:00.431  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:23:00.431  1029  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:23:00.431  1029  1523 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:23:00.431  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:23:00.431  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:23:00.431  1029  1029 E WifiServerServiceExt: No p2p device connected
,09-06 19:23:00.431  1029  8093 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:23:00.431  1029  8093 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.431  1029  8093 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.431  1029  8093 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:23:00.431  1029  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.431  1029  1523 D WifiNative-wlan0: SCAN: returned false
09-06 19:23:00.431  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:00.432  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139111  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-06 19:23:00.434  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:00.434  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:00.435  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:23:00.436  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139114  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:23:00.436  1029  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:23:00.436  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.436  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.436  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:23:00.436  1029  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:23:00.437  1029  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:23:00.437  1029  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:23:00.437  1029  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:23:00.439  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:23:00.439  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:23:00.533  1029  1907 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8117 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:23:00.548  8094  8116 V FormManager: Network unavailable.
09-06 19:23:00.548  8094  8115 W FormManager: Network not available. Please check & try again.
09-06 19:23:00.550  8094  8116 V FormManager: Network unavailable.
,09-06 19:23:00.567  1029  1960 I ActivityManager: Killing 7144:com.android.chrome/u0a57 (adj 15): empty #17
,09-06 19:23:00.604  1029  1979 W libprocessgroup: failed to open /acct/uid_10057/pid_7144/cgroup.procs: No such file or directory
09-06 19:23:00.646  8117  8117 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:23:00.655  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:23:00.668  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:00.672  1029  1715 I ActivityManager: Killing 7168:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-06 19:23:00.734  1029  1960 W libprocessgroup: failed to open /acct/uid_10062/pid_7168/cgroup.procs: No such file or directory
,09-06 19:23:00.761  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:23:00.761  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-06 19:23:00.762  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-06 19:23:00.762  6855  6855 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:23:00.763  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:23:00.764  6855  6855 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:23:00.765  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:23:00.765  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:23:00.765  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:23:00.765  6855  6855 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:23:00.766  6855  6855 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:23:00.777  8074  8074 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 19:23:00.780  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:23:00.782  8074  8074 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 19:23:00.833  8074  8074 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:23:00.833  8074  8074 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:23:00.846  8074  8074 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 19:23:00.848  8074  8074 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 19:23:00.848  8074  8074 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 19:23:00.848  8074  8074 V SoundPool: doLoad: loading sample sampleID=1
09-06 19:23:00.850  8074  8074 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-06 19:23:00.851  8074  8142 V SoundPool: Start decode
09-06 19:23:00.851  8074  8142 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 19:23:00.856   318  2154 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 19:23:00.856   318  2154 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 19:23:00.856   318  2154 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 19:23:00.856   318  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 19:23:00.856   318  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 19:23:00.856   318  2154 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 19:23:00.856   318  2154 V MediaPlayerService: player type = 3
09-06 19:23:00.856   318  2154 V AwesomePlayer: AwesomePlayer create()
09-06 19:23:00.857   318  2154 V AwesomePlayer: reset_l() 
09-06 19:23:00.857   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:23:00.857   318  2154 V AwesomePlayer: setAudioSink() 
09-06 19:23:00.857   318  2154 V AwesomePlayer: reset_l() 
09-06 19:23:00.857   318  2154 V AudioCache: notify(0xb1432440, 8, 0, 0)
09-06 19:23:00.857   318  2154 V AudioCache: ignored
09-06 19:23:00.858   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:23:00.858   318  2154 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 19:23:00.858   318  2154 V AwesomePlayer: setDataSource_l dataSource
09-06 19:23:00.858   318  2154 V LGParserOSAL: SniffLGParser start
09-06 19:23:00.858   318  2154 V LGParserOSAL: MainType:5, SubType=0
09-06 19:23:00.858   318  2154 V LGParserOSAL: #### check Mime : application/ogg
09-06 19:23:00.858   318  2154 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 19:23:00.859   318  2154 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 19:23:00.867  7633  7633 D UEI.SmartControl: QS Service created
,09-06 19:23:00.880  8074  8074 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:23:00.882  8074  8074 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:23:00.882  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-06 19:23:00.905   318  2154 V LGParserOSAL: supported mime: application/ogg
09-06 19:23:00.905   318  2154 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 19:23:00.905   318  2154 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 19:23:00.905   318  2154 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 19:23:00.905   318  2154 V AwesomePlayer: AudioTrack Setting
09-06 19:23:00.905   318  2154 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 19:23:00.905   318  2154 V AwesomePlayer: setAudioSource() 
09-06 19:23:00.905   318  2154 V MediaPlayerService: prepare
09-06 19:23:00.905   318  2154 V AwesomePlayer: prepareAsync_l() 
09-06 19:23:00.905   318  2154 V MediaPlayerService: wait for prepare
09-06 19:23:00.906   318  8143 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 19:23:00.906   318  8143 V AwesomePlayer: initAudioDecoder() 
09-06 19:23:00.906   318  8143 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:23:00.906   318  8143 V AudioSystem: isOffloadSupported()
09-06 19:23:00.906   318  8143 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:23:00.907   318  8143 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:23:00.907   318  8143 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:23:00.907   318  8143 V AwesomePlayer: getUseOffload() = 0 
09-06 19:23:00.907   318  8143 V OMXCodec: OMXCodec::Create
09-06 19:23:00.907   318  8143 V OMXCodec: findMatchingCodecs()
09-06 19:23:00.907  7633  7633 I UEI.SmartControl: Service initServices...
09-06 19:23:00.907   318  8143 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 19:23:00.907   318  8143 V OMXCodec: matchingCodecs.size()=1
09-06 19:23:00.907   318  8143 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 19:23:00.907  7633  7633 D UEI.SmartControl: QS start get config
09-06 19:23:00.907  8074  8074 V LGMDMManager: Create singleton instance
,09-06 19:23:00.908   318  8143 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 19:23:00.908   318  8143 V LGCodecAdapter: LG Codec Adapter start
09-06 19:23:00.908   318  8143 V OMXCodec: OMXCodec Createtor
09-06 19:23:00.908   318  8143 V OMXCodec: setComponentRole
09-06 19:23:00.908   318  8143 V OMXCodec: configureCodec protected=0
09-06 19:23:00.908   318  8143 V LGCodecAdapter: called getLGCodecSpecificData
09-06 19:23:00.908   318  8143 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 19:23:00.908   318  8143 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 19:23:00.909   318  8143 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 19:23:00.909   318  8143 V LGCodecOSAL: Not support LGCodec
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:23:00.909   318  8143 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 19:23:00.909   318  8143 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 19:23:00.909   318  8143 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 19:23:00.909   318  8143 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:23:00.909   318  8143 V AudioSystem: isOffloadSupported()
09-06 19:23:00.909   318  8143 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:23:00.909   318  8143 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 19:23:00.909   318  8143 V OMXCodec: init()
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 19:23:00.909   318  8143 V OMXCodec: allocateBuffers
09-06 19:23:00.909   318  8143 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-06 19:23:00.909   318  8143 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:23:00.909   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:23:00.910   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on output port
09-06 19:23:00.910   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-06 19:23:00.910   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-06 19:23:00.910   318  8143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
09-06 19:23:00.910   318  8143 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:23:00.910   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:23:00.910   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:23:00.910   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 19:23:00.910   318  8143 V OMXCodec: init() mAsyncCompletion wait!!! 
,09-06 19:23:00.910   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 19:23:00.910   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 19:23:00.910   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 19:23:00.910   318  8143 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 19:23:00.910   318  8143 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 19:23:00.910   318  8143 V AudioCache: notify(0xb1432440, 5, 0, 0)
09-06 19:23:00.910   318  8143 V AudioCache: ignored
09-06 19:23:00.910   318  8143 V AudioCache: notify(0xb1432440, 1, 0, 0)
09-06 19:23:00.910   318  8143 V AudioCache: prepared
09-06 19:23:00.910   318  2154 V AudioCache: wait - success
09-06 19:23:00.910   318  2154 V MediaPlayerService: start
09-06 19:23:00.910   318  2154 V AwesomePlayer: play_l() 
09-06 19:23:00.911   318  2154 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 19:23:00.911   318  2154 V AwesomePlayer: createAudioPlayer_l
09-06 19:23:00.911   318  2154 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 19:23:00.911   318  2154 V AwesomePlayer: startAudioPlayer_l() 
09-06 19:23:00.911   318  2154 D AudioPlayer: start of Playback, useOffload 0
09-06 19:23:00.911   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:23:00.911   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048176
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:23:00.913   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 19:23:00.914   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 19:23:00.922   318  8145 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:23:00.922   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:23:00.922   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-06 19:23:00.922   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-06 19:23:00.922   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on output port
09-06 19:23:00.922  8070  8070 E wpa_supplic,ant: USIM:  scard_init function
09-06 19:23:00.922   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-06 19:23:00.922   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 19:23:00.922   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 19:23:00.922  8070  8070 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 19:23:00.923   318  2154 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 19:23:00.923   318  2154 V AudioCache: notify(0xb1432440, 6, 0, 0)
09-06 19:23:00.923   318  2154 V AudioCache: ignored
09-06 19:23:00.923   318  2154 V MediaPlayerService: wait for playback complete
09-06 19:23:00.924  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 19:23:00.925  1029  8093 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 19:23:00.925  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 19:23:00.925  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-06 19:23:00.925  1029  8093 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:23:00.925  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:23:00.925  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 19:23:00.925   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.925   318  8146 V AudioCache: memcpy(0xac300000, 0xb57fb000, 4096)
09-06 19:23:00.926  1029  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:23:00.926  1029  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:23:00.927  1029  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:23:00.927   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.927   318  8146 V AudioCache: memcpy(0xac301000, 0xb57fb000, 4096)
09-06 19:23:00.927  1029  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:23:00.927  1029  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 19:23:00.927   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.927   318  8146 V AudioCache: memcpy(0xac302000, 0xb57fb000, 4096)
09-06 19:23:00.928   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.928   318  8146 V AudioCache: memcpy(0xac303000, 0xb57fb000, 4096)
09-06 19:23:00.928   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.928   318  8146 V AudioCache: memcpy(0xac304000, 0xb57fb000, 4096)
09-06 19:23:00.929   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.929   318  8146 V AudioCache: memcpy(0xac305000, 0xb57fb000, 4096)
09-06 19:23:00.929   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.929   318  8146 V AudioCache: memcpy(0xac306000, 0xb57fb000, 4096)
09-06 19:23:00.930   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.930   318  8146 V AudioCache: memcpy(0xac307000, 0xb57fb000, 4096)
09-06 19:23:00.930   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.930   318  8146 V AudioCache: memcpy(0xac308000, 0xb57fb000, 4096)
09-06 19:23:00.931   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.931   318  8146 V AudioCache: memcpy(0xac309000, 0xb57fb000, 4096)
09-06 19:23:00.931   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.931   318  8146 V AudioCache: memcpy(0xac30a000, 0xb57fb000, 4096)
09-06 19:23:00.932   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.932   318  8146 V AudioCache: memcpy(0xac30b000, 0xb57fb000, 4096)
09-06 19:23:00.932   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.932   318  8146 V AudioCache: memcpy(0xac30c000, 0xb57fb000, 4096)
09-06 19:23:00.933   318  8146 V AudioC,ache: write(0xb57fb000, 4096)
09-06 19:23:00.933   318  8146 V AudioCache: memcpy(0xac30d000, 0xb57fb000, 4096)
09-06 19:23:00.933   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.933   318  8146 V AudioCache: memcpy(0xac30e000, 0xb57fb000, 4096)
09-06 19:23:00.934   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.934   318  8146 V AudioCache: memcpy(0xac30f000, 0xb57fb000, 4096)
09-06 19:23:00.934   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.934   318  8146 V AudioCache: memcpy(0xac310000, 0xb57fb000, 4096)
09-06 19:23:00.935  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139614  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:23:00.935   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.935   318  8146 V AudioCache: memcpy(0xac311000, 0xb57fb000, 4096)
09-06 19:23:00.936   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.936   318  8146 V AudioCache: memcpy(0xac312000, 0xb57fb000, 4096)
09-06 19:23:00.937   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.937   318  8146 V AudioCache: memcpy(0xac313000, 0xb57fb000, 4096)
09-06 19:23:00.937   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.937   318  8146 V AudioCache: memcpy(0xac314000, 0xb57fb000, 4096)
09-06 19:23:00.938   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.938   318  8146 V AudioCache: memcpy(0xac315000, 0xb57fb000, 4096)
09-06 19:23:00.938   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.938   318  8146 V AudioCache: memcpy(0xac316000, 0xb57fb000, 4096)
09-06 19:23:00.939   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.939   318  8146 V AudioCache: memcpy(0xac317000, 0xb57fb000, 4096)
09-06 19:23:00.940   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.940   318  8146 V AudioCache: memcpy(0xac318000, 0xb57fb000, 4096)
09-06 19:23:00.940  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.941  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.941  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:23:00.941  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:00.941  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:00.942  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:00.942  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139621  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:23:00.944   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.944   318  8146 V AudioCache: memcpy(0xac319000, 0xb57fb000, 4096)
09-06 19:23:00.945  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.945  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:00.945  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:23:00.945  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:23:00.945  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:23:00.946   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.946   318  8146 V AudioCache: memcpy(0xac31a000, 0xb57fb000, 4096)
09-06 19:23:00.946   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.946   318  8146 V AudioCache: memcpy(0xac31b000, 0xb57fb000, 4096)
09-06 19:23:00.947   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.947   318  8146 V AudioCache: memcpy(0xac31c000, 0xb57fb000, 4096)
09-06 19:23:00.947   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.947   318  8146 V AudioCache: memcpy(0xac31d000, 0xb57fb000, 4096)
09-06 19:23:00.948   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.948   318  8146 V AudioCache: memcpy(0xac31e000, 0xb57fb000, 4096)
09-06 19:23:00.949   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.949   318  8146 V AudioCache: memcpy(0xac31f000, 0xb57fb000, 4096)
09-06 19:23:00.949   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.949   318  8146 V AudioCache: memcpy(0xac320000, 0xb57fb000, 4096)
09-06 19:23:00.952   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.952   318  8146 V AudioCache: memcpy(0xac321000, 0xb57fb000, 4096)
09-06 19:23:00.953   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.953   318  8146 V AudioCache: memcpy(0xac322000, 0xb57fb000, 4096)
09-06 19:23:00.953   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.953   318  8146 V AudioCache: memcpy(0xac323000, 0xb57fb000, 4096)
09-06 19:23:00.954   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.954   318  8146 V AudioCache: memcpy(0xac324000, 0xb57fb000, 4096)
09-06 19:23:00.954   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.955   318  8146 V AudioCache: memcpy(0xac325000, 0xb57fb000, 4096)
09-06 19:23:00.955   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.955   318  8146 V AudioCache: memcpy(0xac326000, 0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: memcpy(0xac327000, 0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: memcpy(0xac328000, 0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: memcpy(0xac329000, 0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.956   318  8146 V AudioCache: memcpy(0xac32a000, 0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: memcpy(0xac32b000, 0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: memcpy(0xac32c000, 0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: memcpy(0xac32d000, 0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.958   318  8146 V AudioCache: memcpy(0xac32e000, 0xb57fb000, 4096)
09-06 19:23:00.961  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:00.961  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:00.962  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:23:00.965   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 19:23:00.965   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.965   318  8146 V AudioCache: memcpy(0xac32f000, 0xb57fb000, 4096)
09-06 19:23:00.965   318  8146 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:23:00.965   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.965   318  8146 V AudioCache: memcpy(0xac330000, 0xb57fb000, 4096)
09-06 19:23:00.965   318  8146 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:23:00.965   318  8146 V AudioCache: write(0xb57fb000, 4096)
09-06 19:23:00.965   318  8146 V AudioCache: memcpy(0xac331000, 0xb57fb000, 4096)
09-06 19:23:00.965   318  8146 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:23:00.965   318  8146 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:23:00.965   318  8146 V AwesomePlayer: postAudioEOS() 
09-06 19:23:00.965   318  8146 V AudioCache: write(0xb57fb000, 280)
09-06 19:23:00.965   318  8146 V AudioCache: memcpy(0xac332000, 0xb57fb000, 280)
09-06 19:23:00.967   318  8143 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 19:23:00.967   318  8143 V AwesomePlayer: onStreamDone
09-06 19:23:00.967   318  8143 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 19:23:00.967   318  8143 V AudioCache: notify(0xb1432440, 2, 0, 0)
09-06 19:23:00.967   318  8143 V AudioCache: playback complete
09-06 19:23:00.967   318  8143 V AwesomePlayer: pause_l() 
09-06 19:23:00.967   318  8143 V AudioCache: notify(0xb1432440, 7, 0, 0)
09-06 19:23:00.967   318  8143 V AudioCache: ignored
09-06 19:23:00.967   318  8143 V AwesomePlayer: cancelPlayerEvents
09-06 19:23:00.967   318  2154 V AudioCache: wait - success
09-06 19:23:00.967   318  2154 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 19:23:00.968   318  8143 D AudioPlayer: Pause Playback at 1068125
09-06 19:23:00.968   318  2154 V AwesomePlayer: reset_l() 
09-06 19:23:00.968   318  2154 V AudioCache: notify(0xb1432440, 8, 0, 0)
09-06 19:23:00.968   318  2154 V AudioCache: ignored
09-06 19:23:00.968   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:23:00.968   318  2154 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 19:23:00.968   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 19:23:00.968   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 19:23:00.968   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 19:23:00.968   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 19:23:00.969   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 19:23:00.970   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:23:00.970   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 19:23:00.970   318  8145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 19:23:00.970   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:23:00.970   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 19:23:00.970   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 19:23:00.971   318  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 19:23:00.972   318  2154 D AudioPlayer: AudioPlayer releasing audio source
09-06 19:23:00.972   318  2154 D AudioPlayer: AudioPlayer done releasing audio source
09-06 19:23:00.972   318  2154 V AwesomePlayer: reset_l() 
09-06 19:23:00.972   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:23:00.972   318  2154 V AwesomePlayer: ~AwesomePlayer call
09-06 19:23:00.972   318  2154 V AwesomePlayer: reset_l() 
09-06 19:23:00.972   318  2154 V AwesomePlayer: cancelPlayerEvents
09-06 19:23:00.973  8074  8142 V SoundPool: close(31)
09-06 19:23:00.973  8074  8142 V SoundPool: pointer = 0x9fe54000, size = 205080, sampleRate = 48000, numChannels = 2
09-06 19:23:00.991  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:23:00.992  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 19:23:00.993  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2944
09-06 19:23:00.999  8117  8117 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:23:01.003  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:23:01.005  8094  8154 W FormManager: Network not available. Please check & try again.
09-06 19:23:01.006  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:01.016  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-06 19:23:01.016  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:23:01.017  8094  8155 V FormManager: Network unavailable.
09-06 19:23:01.017  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:23:01.020  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:23:01.020  8094  8155 V FormManager: Network unavailable.
09-06 19:23:01.023  4308  8156 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:23:01.025  4308  8157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:23:01.025  4308  8157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:23:01.033  8070  8070 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-06 19:23:01.033  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:23:01.033  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:23:01.033  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:23:01.033  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:23:01.033  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:23:01.033  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:23:01.035  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139713  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:23:01.035  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139714  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:23:01.036  1029  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139715
09-06 19:23:01.036  1029  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139715
09-06 19:23:01.037  1029  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139715
09-06 19:23:01.037  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139716
09-06 19:23:01.037  1029  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139716
09-06 19:23:01.038  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139717  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:23:01.050  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:23:01.050  8070  8070 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:23:01.050  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:23:01.051  8070  8070 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:23:01.051  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:23:01.051  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:23:01.051  1029  8093 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:23:01.051  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:23:01.051  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:23:01.051  1029  8093 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:23:01.052  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:23:01.052  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:23:01.056  1029  1045 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8158 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-06 19:23:01.057  1029  1100 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:23:01.060  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139738  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:23:01.061  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.061  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:01.062  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:23:01.067  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.067  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.067  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:23:01.068  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.068  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.068  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:23:01.068  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:23:01.068  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:23:01.068  1029  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139747  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:23:01.069  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139748  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:23:01.070  1029  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139749
09-06 19:23:01.070  1029  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139749
09-06 19:23:01.071  1029  1523 D WifiNative-wlan0: doString: [STATUS]
09-06 19:23:01.071  1029  8093 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:23:01.071  1029  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:23:01.071  1029  8093 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:23:01.073  1029  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 19:23:01.079  1029  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-06 19:23:01.079  1029  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-06 19:23:01.082  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.082  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:01.083  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.094  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.094  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.094  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-06 19:23:01.097  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.097  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.097  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:23:01.100  1029  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 19:23:01.100  1029  1529 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:23:01.100  1029  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:23:01.100  1029  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:23:01.100  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:23:01.100  1029  1529 D ConnectivityService: NetworkAgent connected
09-06 19:23:01.101  1029  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:23:01.101  1029  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:23:01.105  1029  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:23:01.105  1029  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:23:01.105  1029  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:23:01.106  1029  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:23:01.106  1029  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 19:23:01.109  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.109  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:01.111  1029  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:23:01.112  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.112   312   887 D CommandListener: Setting iface cfg
09-06 19:23:01.114  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.114  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:01.115  1029  8176 D DhcpStateMachine: StoppedState
09-06 19:23:01.115  1029  1523 E WifiStateMachine: Start Dhcp Watchdog 3
09-06 19:23:01.115  1029  8176 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:01.115  1029  8176 D DhcpStateMachine: WaitBeforeStartState
09-06 19:23:01.116  1029  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139794  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:23:01.116  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.116  1029  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139795  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:23:01.116  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139795  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:23:01.117  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:01.117  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:01.118  1029  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:01.118  1029  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:01.119  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:01.119  1029  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:23:01.120  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:23:01.120  1029  1029 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-06 19:23:01.120  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:23:01.120  1029  1029 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:23:01.122  1029  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139800  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:23:01.122  1029  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139801  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:23:01.123  1029  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139802  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:23:01.124  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14307] from screen [on:0 period:8798596] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:23:01.125  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:8798597] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:23:01.125  1029  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:23:01.130  1029  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-06 19:23:01.130  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.131  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.131  1029  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.131  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.132  1029  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.132  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.132  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 19:23:01.134  1029  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:23:01.134  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=152,0,0
09-06 19:23:01.135  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=152,0,0
09-06 19:23:01.135  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:23:01.135  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:23:01.135  1029  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:23:01.135  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:23:01.136  1029  1523 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:23:01.136  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 19:23:01.136  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 19:23:01.136  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:23:01.136  1029  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:23:01.136  1029  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:23:01.137  1029  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:23:01.137  1029  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34661efa target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:01.137  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34661efa target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:01.137  1029  8176 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:01.137  1029  8176 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 19:23:01.137   312   887 D CommandListener: Setting iface cfg
09-06 19:23:01.138   312   887 D CommandListener: Trying to bring up wlan0
09-06 19:23:01.138  1029  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:23:01.139  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:23:01.139  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:23:01.140  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:23:01.140  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:23:01.141  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.141  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.142  1029  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.142  1029  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.143  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.143  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:23:01.143  1029  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:23:01.144  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:23:01.144  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:23:01.144  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:23:01.144  1029  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:01.144  1029  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
0,9-06 19:23:01.145  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-06 19:23:01.146  1029  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:23:01.146  1029  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:23:01.146  8070  8070 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:23:01.146  1029  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:23:01.147  1029  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:23:01.147  8158  8158 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:23:01.147  8158  8158 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-06 19:23:01.150  8158  8158 V [BNRBootReceiver]: Boot Receiver Return
09-06 19:23:01.151  8158  8158 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:23:01.162  1029  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:23:01.163  1029  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:23:01.163  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:23:01.163  1029  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:23:01.164  1029  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:23:01.164  1029  1529 D ConnectivityService: ignoring duplicate network state non-change
,09-06 19:23:01.181  1029  2016 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8178 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:23:01.184  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.184  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.184  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:23:01.184  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.185  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:23:01.186  1029  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:23:01.186  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.187  1029  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:23:01.188  1029  1529 D ConnectivityService: Adding iface wlan0 to network 102
09-06 19:23:01.190  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.190  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.190  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:23:01.190  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 19:23:01.190  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:23:01.191  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.191  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.191  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:23:01.192  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-06 19:23:01.200  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.200  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:01.200  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:23:01.207  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.207  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:23:01.209  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.211  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.211  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:23:01.212  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.214  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:01.214  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:23:01.214  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:23:01.222  1029  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:23:01.222  1029  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 19:23:01.223  1029  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-06 19:23:01.224   312   887 E Netd    : netlink response contains error (File exists)
09-06 19:23:01.224  1029  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-06 19:23:01.225  1029  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:23:01.225  1029  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-06 19:23:01.225  1029  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-06 19:23:01.226  1029  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:23:01.226  1029  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:23:01.226  1029  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-06 19:23:01.226  1029  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 19:23:01.226  1029  8175 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:01.226  1029  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:23:01.226  1029  8175 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:23:01.226  1029  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:23:01.226  1029  8175 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:23:01.226  1029  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:23:01.226  1029  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:23:01.226  1029  8175 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:23:01.226  1029  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:23:01.226  1029  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:23:01.226  1029  1529 D ConnectivityService:    accepting network in place of null
09-06 19:23:01.226  1029  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:23:01.227  1029  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:23:01.227  1029  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:23:01.228  1029  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:23:01.228  1029  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 19:23:01.228  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:23:01.229  1029  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:23:01.229  1029  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:23:01.229   312  8198 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 19:23:01.229  1029  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/,24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:23:01.230  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:23:01.230  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:23:01.231  1029  1029 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:23:01.231  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:23:01.231  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:23:01.231  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:23:01.232  1029  1529 D ConnectivityService: validation of new default Network = false
09-06 19:23:01.232  1029  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:23:01.232  1029  1529 D DSQN    : enableDataServiceNotify 
09-06 19:23:01.232  1029  1529 D DSQN    : start dsqn bin
,09-06 19:23:01.244  1029  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:01.245  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:23:01.246  1029  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 19:23:01.246  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:23:01.246  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:23:01.247  1029  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:23:01.230  8199  8199 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:23:01.247  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:23:01.230  8199  8199 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:23:01.250  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:01.256  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:23:01.256  6651  6759 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 19:23:01.256  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.257  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:01.257  6651  6759 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:23:01.258  6651  6759 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@963bc77 Bundle[{}]
09-06 19:23:01.258  8199  8199 E DSQN    : DSQN ssw
,09-06 19:23:01.258  6651  6759 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:23:01.259  6651  6759 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-06 19:23:01.260  6651  6759 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:23:01.261  6651  6759 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:23:01.261  6651  6759 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-06 19:23:01.261  6651  6759 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 19:23:01.262  8178  8178 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:23:01.265  6651  6759 I System.out: Running OutgoingSocketThread
09-06 19:23:01.266  6651  8203 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
09-06 19:23:01.267  6651  8203 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44193
09-06 19:23:01.267  6651  8203 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-06 19:23:01.281  8178  8178 D PluginManager: init()
,09-06 19:23:01.320  7633  7633 I UEI.SmartControl: Supports setup maps: true
,09-06 19:23:01.322  7633  7633 D UEI.SmartControl: QS start statue = true Error code = 0
,09-06 19:23:01.322  7633  7633 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:23:01.322  7633  7633 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:23:01.322  7633  7633 I UEI.SmartControl: ### init IR Blaster...
09-06 19:23:01.326  7633  7633 D serial_port: Configuring serial port
09-06 19:23:01.326  7633  7633 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:23:01.326  7633  7633 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:23:01.326  7633  7633 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:23:01.326  7633  7633 I UEI.SmartControl: Get version...
09-06 19:23:01.338  1029  8176 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 19:23:01.339  1029  8176 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 19:23:01.339  1029  8176 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-06 19:23:01.330  8205  8205 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:23:01.344  7633  8204 D UEI.SmartControl: serial port data available: 21
09-06 19:23:01.330  8205  8205 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:23:01.349  8205  8205 I dhcpcd  : version 5.5.6 starting
09-06 19:23:01.350  8205  8205 E dhcpcd  : get_duid: m
09-06 19:23:01.350  8205  8205 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:23:01.350  8205  8205 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 19:23:01.371  7633  7633 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:23:01.372  7633  7633 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:23:01.372  7633  7633 I UEI.SmartControl: QS saving settings...
09-06 19:23:01.374  7633  7633 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:23:01.390  7633  8204 D UEI.SmartControl: serial port data available: 4
,09-06 19:23:01.418  7633  8213 I UEI.SmartControl: Device manager: loading config....
,09-06 19:23:01.420  7633  8213 D UEI.SmartControl: ----------- loading internal config...
09-06 19:23:01.423  7633  7633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 19:23:01.424  7633  7633 E UEI.SmartControl: Services init done
09-06 19:23:01.424  7633  7633 D UEI.SmartControl: QS Service init finished
09-06 19:23:01.425  7633  7633 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:23:01.425  7633  7633 D UEI.SmartControl: QS Service version code: 201091
09-06 19:23:01.426  7633  7633 D UEI.SmartControl: Service requested: Control
09-06 19:23:01.428  7633  8213 E UEI.SmartControl: Loading SETTINGS...
09-06 19:23:01.431  7633  7633 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 19:23:01.432  8074  8074 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-06 19:23:01.433  7633  7654 I UEI.SmartControl: ------ IControl API: 11
09-06 19:23:01.433  7633  7654 D UEI.SmartControl: File observer start...
09-06 19:23:01.433  7633  7654 E UEI.SmartControl: IR Port is disabled: false
09-06 19:23:01.433  7633  7654 D UEI.SmartControl: Starting file observer...
09-06 19:23:01.434  7633  7654 I UEI.SmartControl: Registering callback...
09-06 19:23:01.434  7633  7633 D UEI.SmartControl: Internal service binding...
09-06 19:23:01.434  7633  7648 I UEI.SmartControl: ------ IControl API: 19
09-06 19:23:01.435  7633  7648 I UEI.SmartControl: Registering Services Ready callback...
09-06 19:23:01.437  7633  8213 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:23:01.440  8205  8205 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:23:01.441  8205  8205 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:23:01.441  8205  8205 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:23:01.441  8205  8205 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 19:23:01.441  8205  8205 D dhcpcd  : wlan0: sending REQUEST (xid 0xc9cb1e6), next in 4.14 seconds
09-06 19:23:01.458  7633  8212 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:23:01.458  7633  8212 D UEI.SmartControl: -----service ready thread exits
09-06 19:23:01.459  8074  8089 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 19:23:01.459  8074  8140 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 19:23:01.459  8074  8140 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 19:23:01.459  8074  8074 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 19:23:01.459  8074  8074 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 19:23:01.459  7633  7654 I UEI.SmartControl: ------ IControl API: 8
,09-06 19:23:01.460  8074  8074 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,09-06 19:23:01.460  8074  8074 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 19:23:01.460  8074  8074 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 19:23:01.461  8074  8074 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 19:23:01.461  8074  8074 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 19:23:01.461  8074  8074 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 19:23:01.462  8074  8074 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-06 19:23:01.463  8074  8074 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 19:23:01.464  1029  1870 I ActivityManager: Killing 7226:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-06 19:23:01.478  8205  8205 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-06 19:23:01.509  8205  8205 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:23:01.510  8205  8205 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-06 19:23:01.510  8205  8205 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:23:01.511  8205  8205 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 19:23:01.511  8205  8205 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:23:01.511  8205  8205 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:23:01.512  8205  8205 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:23:01.512  8205  8205 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-06 19:23:01.648  8178  8178 W ExternalStrings: load override strings
09-06 19:23:01.648  8178  8178 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:23:01.648  8178  8178 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 19:23:01.651  8178  8178 D StatusProvider: onCreate
09-06 19:23:01.710  1029  1870 I ActivityManager: Killing 7185:com.lge.sizechangable.weather/u0a85 (adj 15): empty #18
,09-06 19:23:01.808  1029  1044 W libprocessgroup: failed to open /acct/uid_10093/pid_7226/cgroup.procs: No such file or directory
,09-06 19:23:01.815  1029  1942 W libprocessgroup: failed to open /acct/uid_10085/pid_7185/cgroup.procs: No such file or directory
,09-06 19:23:01.883  8178  8178 V Signer  : override build config not found
,09-06 19:23:01.884  8178  8178 D Signer  : value of property debug is false
,09-06 19:23:01.930  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-06 19:23:01.930  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,09-06 19:23:01.930  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-06 19:23:01.931  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,09-06 19:23:01.931  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-06 19:23:01.931  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,09-06 19:23:01.932  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,09-06 19:23:01.932  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-06 19:23:01.932  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-06 19:23:01.932  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,09-06 19:23:01.933  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-06 19:23:01.933  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-06 19:23:01.933  8178  8178 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,09-06 19:23:01.941  1029  8176 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-06 19:23:01.943  1029  8176 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 19:23:01.943  1029  8176 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-06 19:23:01.944  1029  8176 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:23:01.944  1029  8176 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,09-06 19:23:01.944  1029  8176 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:23:01.944  1029  8176 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:23:01.944  1029  8176 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,09-06 19:23:01.946  1029  8176 D DhcpStateMachine: RunningState
,09-06 19:23:01.956  8178  8178 V LGMDMManager: Create singleton instance
,09-06 19:23:02.036  8178  8178 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-06 19:23:02.107  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:23:02.119  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:23:02.122   312  8198 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-06 19:23:02.132  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:23:02.139  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.146  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:23:02.149  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.162  8074  8074 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:23:02.167  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 19:23:02.170  6855  6855 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 19:23:02.173  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.173  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:23:02.181  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:23:02.198  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.205  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.205  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:23:02.208  8074  8074 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:23:02.213  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.214  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.227  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:23:02.235  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.243  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.243  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:23:02.243  8074  8074 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:23:02.246  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:23:02.247  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:23:02.247  6855  6855 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:23:02.247  6855  6855 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:23:02.247  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:23:02.248  6855  6855 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:23:02.248  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:23:02.248  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:23:02.248  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:23:02.248  6855  6855 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:23:02.248  6855  6855 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:23:02.249  6855  6855 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:23:02.267  6651  6759 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
09-06 19:23:02.267  6651  6759 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
,09-06 19:23:02.274  6651  6759 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
09-06 19:23:02.276  6651  6759 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 19:23:02.276  6651  6759 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
09-06 19:23:02.281  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.281  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11c4adb2 added. We now have 2 listener(s)
,09-06 19:23:02.281  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.285  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.285  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.285  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.285  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.285  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7566103 added. We now have 9 listener(s)
09-06 19:23:02.285  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.286  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:23:02.288  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:02.292  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:02.295  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.295  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:02.295  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.295  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@368baeb9 added. We now have 3 listener(s)
09-06 19:23:02.295  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:23:02.297  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.299  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.300  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.301  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.301  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.301  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.301  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24cbf2fe added. We now have 10 listener(s)
09-06 19:23:02.301  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.301  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:02.301  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:02.301  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:02.301  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.301  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.301  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:02.302  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.302  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11c4adb2 removed from the list
09-06 19:23:02.302  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.302  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7566103 removed from the list
09-06 19:23:02.302  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:02.302  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.302  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.302  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.303  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.303  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.303  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.303  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7566103 not in the list
09-06 19:23:02.303  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listene,r does not exist in the list - probably already removed
09-06 19:23:02.303  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.304  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.304  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.304  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.304  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24cbf2fe removed from the list
09-06 19:23:02.304  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.304  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.304  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.304  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.304  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@368baeb9 removed from the list
09-06 19:23:02.305  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.305  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d540a5f added. We now have 2 listener(s)
09-06 19:23:02.305  1029  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.308  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.308  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.308  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.308  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.308  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6b8cac added. We now have 9 listener(s)
09-06 19:23:02.308  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:23:02.309  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:23:02.312  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:02.316  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:02.317  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.318  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:02.318  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.318  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b70410a added. We now have 3 listener(s)
09-06 19:23:02.319  1029  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.321  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.322  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.323  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.323  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.323  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.323  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.324  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a58ed7b added. We now have 10 listener(s)
09-06 19:23:02.324  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.324  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:23:02.324  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:23:02.324  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:23:02.324  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:02.324  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:23:02.328  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:23:02.328  1029  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.333  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:23:02.334  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:23:02.335  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:23:02.336  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:02.337  6651  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-06 19:23:02.337  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:02.337  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:02.340  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:02.340  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:02.340  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:02.340  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.340  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.340  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:02.340  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.340  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d540a5f removed from the list
09-06 19:23:02.340  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.340  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6b8cac removed from the list
09-06 19:23:02.340  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:02.340  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.341  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.341  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.342  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.342  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.342  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.342  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6b8cac not in the list
09-06 19:23:02.342  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.342  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.343  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.344  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:23:02.344  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:23:02.344  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.344  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.344  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a58ed7b removed from the list
,09-06 19:23:02.344  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-06 19:23:02.344  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.344  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.344  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:23:02.344  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b70410a removed from the list
09-06 19:23:02.345  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.345  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5963d6 added. We now have 2 listener(s)
09-06 19:23:02.345  1029  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
09-06 19:23:02.348  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.348  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.348  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:23:02.348  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.348  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efee657 added. We now have 9 listener(s)
09-06 19:23:02.348  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.349  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:23:02.352  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:02.356  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:02.357  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.357  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:02.358  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.358  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2206e62d added. We now have 3 listener(s)
09-06 19:23:02.358  1029  1720 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.360  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.361  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.362  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.362  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.362  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.362  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.363  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adfe762 added. We now have 10 listener(s)
09-06 19:23:02.363  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.363  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:23:02.363  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:23:02.363  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:23:02.364  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:23:02.364  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:02.364  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:23:02.366  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:23:02.366  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.367  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.367  1029  1715 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.367  8178  8243 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-06 19:23:02.374  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:23:02.374  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:23:02.374  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:23:02.376  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:23:02.377  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:23:02.378  6651  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:23:02.379  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:02.379  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:02.379  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:02.379  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.379  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.379  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:02.379  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.379  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5963d6 removed from the list
09-06 19:23:02.379  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.379  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efee657 removed from the list
09-06 19:23:02.379  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:02.379  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.380  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.380  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:02.380  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.380  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.380  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.380  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efee657 not in the list
09-06 19:23:02.381  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.381  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.381  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.382  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:23:02.382  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:23:02.382  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.382  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.382  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adfe762 removed from the list
,09-06 19:23:02.382  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:23:02.382  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:02.382  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.382  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:23:02.382  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2206e62d removed from the list
,09-06 19:23:02.383  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.383  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18b829 added. We now have 2 listener(s)
09-06 19:23:02.383  1029  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.385  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.386  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.386  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.386  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.386  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5917ae added. We now have 9 listener(s),
09-06 19:23:02.386  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.386  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.387  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:23:02.393  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:23:02.393  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:02.393  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.393  8074  8074 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:02.397  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:02.398  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.398  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:02.400  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.401  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.401  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc178dc added. We now have 3 listener(s)
09-06 19:23:02.402  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.404  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.406  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.406  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.409  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.409  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.409  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:23:02.410  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.410  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5bade5 added. We now have 10 listener(s)
09-06 19:23:02.410  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.410  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:23:02.410  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:23:02.410  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:23:02.410  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:02.410  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:23:02.413  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:23:02.416  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:23:02.416  1029  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.420  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:23:02.424  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:23:02.427  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:23:02.427  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.427  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.428  8074  8074 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:23:02.428  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:23:02.432  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.433  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.434   312  8198 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 19:23:02.439  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:23:02.441  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:02.442  6651  6759 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:23:02.445  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:02.445  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:02.445  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:02.445  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.446  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.446  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:02.446  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.446  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18b829 removed from the list
09-06 19:23:02.446  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.446  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5917ae removed from the list
09-06 19:23:02.446  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:02.446  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.447  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.447  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.447  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.447  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.447  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.447  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.447  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5917ae not in the list
09-06 19:23:02.447  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.447  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.449  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:23:02.450  6651  6759 D BluetoothLeScanner: could not find callback wrapper
09-06 19:23:02.450  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:23:02.450  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.450  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.450  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5bade5 removed from the list
09-06 19:23:02.450  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.450  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.450  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.450  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.450  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc178dc removed from the list
09-06 19:23:02.451  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.451  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@365b46c8 added. We now have 2 listener(s)
09-06 19:23:02.451  1029  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.454  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:23:02.454  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.454  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.455  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.455  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1e4361 added. We now have 9 listener(s)
09-06 19:23:02.455  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.455  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:23:02.456  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.456  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.457  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:02.458  8074  8074 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:23:02.462  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multi,ple advertisement supported: NOT_SUPPORTED
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:02.462  6651  6759 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:02.464  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:23:02.466  6651  6759 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:23:02.466  6651  6759 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:02.466  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:23:02.466  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d301347 added. We now have 3 listener(s)
09-06 19:23:02.468  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.469  6651  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:02.470  1029  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:23:02.473  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-06 19:23:02.473  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:02.473  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:02.473  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:02.473  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13420774 added. We now have 10 listener(s)
09-06 19:23:02.473  6651  6759 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:02.474  6651  6759 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:02.474  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:02.474  6651  6759 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:02.474  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.474  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.474  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:02.474  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.474  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@365b46c8 removed from the list
09-06 19:23:02.474  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.474  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1e4361 removed from the list
09-06 19:23:02.474  6651  6759 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:02.474  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.478  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:23:02.478  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.478  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.480  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.480  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.480  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.480  6651  6759 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1e4361 not in the list
09-06 19:23:02.480  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:02.480  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.481  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:02.481  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:02.481  6651  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:02.481  6651  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13420774 removed from the list
09-06 19:23:02.481  6651  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:02.481  6651  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:02.481  6651  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:02.481  6651  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:23:02.481  6651  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d301347 removed from the list
09-06 19:23:02.482  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:23:02.482  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:23:02.482  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:23:02.482  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:23:02.483  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:23:02.483  6651  6759 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:02.484  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.488  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.488  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.488  8074  8074 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:23:02.493  6651  8261 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
09-06 19:23:02.493  6651  8261 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
09-06 19:23:02.493  6651  8261 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:23:02.497  6651  8262 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
09-06 19:23:02.497  6651  8262 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
09-06 19:23:02.497  6651  8262 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:23:02.499  6651  6759 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:23:02.499  6651  6759 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:23:02.499  6651  6759 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:23:02.499  6651  6759 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:23:02.499  6651  6759 D com.test.thalitest.ThaliTestRunner: Total duration: 24099 ms
09-06 19:23:02.500  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 and,roid.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.500  6651  6759 I jxcore-log: *Native tests were executed*
09-06 19:23:02.500  6651  6759 I jxcore-log: 
,09-06 19:23:02.501  6651  6759 I jxcore-log: Total number of executed tests:  80
09-06 19:23:02.501  6651  6759 I jxcore-log: 
09-06 19:23:02.501  6651  6759 I jxcore-log: Number of passed tests:  80
09-06 19:23:02.501  6651  6759 I jxcore-log: 
09-06 19:23:02.501  6651  6759 I jxcore-log: Number of failed tests:  0
09-06 19:23:02.501  6651  6759 I jxcore-log: 
09-06 19:23:02.501  6651  6759 I jxcore-log: Number of ignored tests:  0
09-06 19:23:02.501  6651  6759 I jxcore-log: 
09-06 19:23:02.501  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.502  6651  6759 I jxcore-log: Total duration:  24099
09-06 19:23:02.502  6651  6759 I jxcore-log: 
09-06 19:23:02.502  6651  6759 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:23:02.502  6651  6759 I jxcore-log: 
09-06 19:23:02.505  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.505  6651  6759 I jxcore-log: 
09-06 19:23:02.508  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.508  6651  6759 I jxcore-log: 
09-06 19:23:02.509  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.509  6651  6759 I jxcore-log: 
09-06 19:23:02.510  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.510  6651  6759 I jxcore-log: 
09-06 19:23:02.511  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.511  6651  6759 I jxcore-log: 
09-06 19:23:02.513  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.513  6651  6759 I jxcore-log: 
,09-06 19:23:02.516  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:23:02.516  6651  6759 I jxcore-log: 
09-06 19:23:02.517  6651  6651 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:23:02.518  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.518  6651  6759 I jxcore-log: 
09-06 19:23:02.519  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.519  6651  6759 I jxcore-log: 
09-06 19:23:02.519  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:23:02.520  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:23:02.520  6651  6759 I jxcore-log: 
09-06 19:23:02.521  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:23:02.521  6651  6759 I jxcore-log: 
09-06 19:23:02.522  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:23:02.522  6651  6759 I jxcore-log: 
09-06 19:23:02.523  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.523  6651  6759 I jxcore-log: 
09-06 19:23:02.524  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.524  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.524  6651  6759 I jxcore-log: 
09-06 19:23:02.525  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.525  6651  6759 I jxcore-log: 
09-06 19:23:02.525  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.525  6651  6759 I jxcore-log: 
09-06 19:23:02.526  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.526  6651  6759 I jxcore-log: 
09-06 19:23:02.527  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.527  6651  6759 I jxcore-log: 
09-06 19:23:02.528  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.528  6651  6759 I jxcore-log: 
09-06 19:23:02.528  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:23:02.528  6651  6759 I jxcore-log: 
09-06 19:23:02.530  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:23:02.530  6651  6759 I jxcore-log: 
09-06 19:23:02.530  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.530  6651  6759 I jxcore-log: 
,09-06 19:23:02.531  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.531  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.531  6651  6759 I jxcore-log: 
09-06 19:23:02.531  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.532  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.532  6651  6759 I jxcore-log: 
09-06 19:23:02.532  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.532  6651  6759 I jxcore-log: 
09-06 19:23:02.533  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.533  6651  6759 I jxcore-log: 
09-06 19:23:02.534  6651  6759 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:23:02.534  6651  6759 I jxcore-log: 
09-06 19:23:02.536  8074  8074 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:23:02.540  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.541  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.548  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:23:02.553  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.558  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.559  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.559  8074  8074 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:23:02.563  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.563  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.566  8117  8117 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:23:02.569  8117  8117 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:23:02.572  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:23:02.577  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.583  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.583  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.584  8074  8074 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:23:02.585  8074  8074 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:23:02.585  8074  8074 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 19:23:02.590  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:23:02.592  8178  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:23:02.593  8117  8117 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:23:02.594  8117  8117 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:23:02.597  6855  6855 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:23:02.602  6855  6855 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:23:02.609  8074  8074 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:23:02.609  8074  8074 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:23:02.610  8074  8074 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:23:02.610  8074  8074 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:23:02.611  8074  8074 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:23:02.613  8074  8074 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 19:23:02.614  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:23:02.614  8074  8074 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:23:02.614  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:23:02.615  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:23:02.616  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 19:23:02.616  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 19:23:02.617  8074  8074 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473182582617]
,09-06 19:23:02.621  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.622  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.623  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.625  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.626  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.627  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.629  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.631  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.633  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-06 19:23:02.634  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.635  8178  8243 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:23:02.635  8178  8243 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:23:02.637  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:23:02.638  1029  2016 I ActivityManager: Killing 7261:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-06 19:23:02.646  8074  8273 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 19:23:02.710  8178  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-06 19:23:02.723  1029  1960 W libprocessgroup: failed to open /acct/uid_10005/pid_7261/cgroup.procs: No such file or directory
,09-06 19:23:02.734  8074  8074 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-06 19:23:02.736  8074  8074 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:23:02.737  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 19:23:02.737  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 19:23:02.738  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,09-06 19:23:02.739  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 19:23:02.740  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 19:23:02.749  8178  8243 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-06 19:23:02.755  8074  8074 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-06 19:23:02.769  8178  8243 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,09-06 19:23:02.770  8178  8243 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 19:23:02.771  8178  8243 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 19:23:02.772  8178  8243 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-06 19:23:02.772  8178  8243 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-06 19:23:02.778  8178  8243 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-06 19:23:02.781  8178  8243 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-06 19:23:02.835  8269  8269 D AndroidRuntime: 
09-06 19:23:02.835  8269  8269 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 19:23:02.840  8269  8269 D AndroidRuntime: CheckJNI is OFF
,09-06 19:23:03.003  1029  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:23:03.004  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:23:03.005  1029  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:23:03.007  1029  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:23:03.008  1029  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-06 19:23:03.009  1029  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-06 19:23:03.013  1029  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-06 19:23:03.013  1029  1529 D ConnectivityService: identical MTU - not setting
09-06 19:23:03.014  1029  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-06 19:23:03.015  1029  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:23:03.015  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:23:03.015  1029  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-06 19:23:03.017  1029  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:23:03.018  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:23:03.075  8269  8269 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:23:03.092  1029  1089 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-06 19:23:03.094  1029  1089 I ActivityManager: Killing 6651:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-06 19:23:03.178  1029  1961 I WindowState: WIN DEATH: Window{2c668d56 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:23:03.179  1029  1528 D WifiService: Client connection lost with reason: 4
,09-06 19:23:03.197  1029  1961 D InputDispatcher: Window went away: Window{2c668d56 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:23:03.314  1029  1089 I ActivityManager:   Force finishing activity ActivityRecord{3cc54a64 u0 com.test.thalitest/.MainActivity t6}
,09-06 19:23:03.362   348   365 E GBMv2   : DFP En is all cleared set to be enabled
,09-06 19:23:03.367  1029  1960 W ActivityManager: Spurious death for ProcessRecord{151e67b9 6651:com.test.thalitest/u0a118}, curProc for 6651: null
09-06 19:23:03.367  1029  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-06 19:23:03.374  1029  1113 I ActivityManager:   Force finishing activity ActivityRecord{3cc54a64 u0 com.test.thalitest/.MainActivity t6 f}
09-06 19:23:03.374  1029  1113 W ActivityManager: Duplicate finish request for ActivityRecord{3cc54a64 u0 com.test.thalitest/.MainActivity t6 f}
,09-06 19:23:03.394  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-06 19:23:03.395  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{e433a70 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:23:03.397  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-06 19:23:03.403  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,09-06 19:23:03.409  1925  2526 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-06 19:23:03.409  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-06 19:23:03.409  1925  2526 D SplitWindowPolicy: topRunningActivity=ActivityInfo{310e31e9 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:23:03.410  2017  2126 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-06 19:23:03.420  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-06 19:23:03.426  1029  1423 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-06 19:23:03.444  3807  3807 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-06 19:23:03.445  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,09-06 19:23:03.448  7723  7723 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-06 19:23:03.448  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:23:03.453  4607  4607 I art     : Explicit concurrent mark sweep GC freed 8177(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 532us total 50.261ms
09-06 19:23:03.480  1029  1907 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:23:03.512  4499  4499 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-06 19:23:03.512  4499  4499 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-06 19:23:03.512  4499  4499 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-06 19:23:03.512  4499  4499 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-06 19:23:03.512  4499  4499 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:23:03.512  4499  4499 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:23:03.512  4499  4499 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:23:03.512  4499  4499 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:23:03.512  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:03.512  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:23:03.512  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:23:03.512  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:23:03.512  1029  1029 D administrator: Handling package changes for user 0
09-06 19:23:03.512  2489  2644 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:23:03.529  1889  1889 D ActionManagerService: notifyUserLog: 1000003
,09-06 19:23:03.529  8178  8178 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 19:23:03.532  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-06 19:23:03.532  3807  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-06 19:23:03.548  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-06 19:23:03.550  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-06 19:23:03.551  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-06 19:23:03.554  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-06 19:23:03.557  1889  1889 D ActionManagerService: notifyUserLog: 1000004
09-06 19:23:03.558  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-06 19:23:03.558  3807  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-06 19:23:03.559  3807  4467 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:23:03.560  1587  1630 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 19:23:03.560  1587  1630 D KeyguardModel: createShortcutInfo...
,09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , display: false
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , animation: false }
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , display: false
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , animation: false }
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , create_time: 1472828323917
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , display: false
09-06 19:23:03.562  2017  2017 I GBoardWebViewUtils: , animation: false }
09-06 19:23:03.565  1587  1630 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:23:03.565  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.566  1853  1853 D SplitUIManager: split_name #11 / not available #0
09-06 19:23:03.567  1853  1853 D SplitUIService: removed split : 
09-06 19:23:03.572  1587  1630 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:23:03.572  1587  1630 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:23:03.572  1587  1630 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 19:23:03.573  1587  1630 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 19:23:03.579  1029  1870 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:23:03.579  1029  1870 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:23:03.583  1587  1630 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:23:03.583  1587  1630 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 19:23:03.588  2017  8301 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,09-06 19:23:03.592  1587  1630 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:23:03.592  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.599  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-06 19:23:03.603  1587  1630 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:23:03.603  1587  1630 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:23:03.604  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-06 19:23:03.604  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-06 19:23:03.604  1587  1630 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:23:03.604  1587  1630 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 19:23:03.607  1587  1630 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:23:03.607  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.615  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:23:03.615  1587  1630 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:23:03.615  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-06 19:23:03.615  1587  1630 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:23:03.616  1587  1630 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 19:23:03.616  1587  1630 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:23:03.617  1587  1630 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:23:03.617  1587  1630 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 19:23:03.636  1587  1630 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:23:03.636  1587  1630 D KeyguardModel: createShortcutInfo...
,09-06 19:23:03.637  1853  1853 D SplitUIManager: split_name #11 / not available #0
09-06 19:23:03.637  1853  1853 I SplitUIService: split app #11
09-06 19:23:03.638  2138  2138 I ConfigService: onCreate
09-06 19:23:03.638  2138  2138 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-06 19:23:03.642  2138  2138 I ConfigService: onBind returning update interface
09-06 19:23:03.643  1587  1587 D KeyguardModel: handleShortcutListChanged...
09-06 19:23:03.643  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 19:23:03.643  1029  2034 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:23:03.644  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:23:03.645  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:23:03.645  7723  7723 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:23:03.647  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-06 19:23:03.648  1587  1630 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,09-06 19:23:03.648  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.649  2138  2138 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-06 19:23:03.649  2138  2138 I ConfigService: onBind returning config service
09-06 19:23:03.651  1587  1630 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:23:03.651  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.652  1587  1630 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:23:03.652  1587  1630 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 19:23:03.653  1587  1630 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:23:03.653  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.654  1587  1630 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:23:03.654  1587  1630 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 19:23:03.655  1587  1630 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:23:03.655  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.656  1587  1630 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:23:03.656  1587  1630 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 19:23:03.657  1587  1630 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:23:03.657  1587  1630 D KeyguardModel: createShortcutInfo...
09-06 19:23:03.658  1801  1801 I ConfigFetchService: service connected
09-06 19:23:03.677  1029  1044 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:23:03.681  1587  1587 D KeyguardModel: handleShortcutListChanged...
09-06 19:23:03.681  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 19:23:03.691  1029  1088 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-06 19:23:03.692  2138  2138 I ConfigService: onDestroy
09-06 19:23:03.693  1801  8304 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-06 19:23:03.722  5962  8311 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-06 19:23:03.725  1029  1029 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-06 19:23:03.725  1029  1029 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:23:03.725  1029  1029 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-06 19:23:03.727  1029  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-06 19:23:03.734  1801  8312 I PeopleContactsSync: CP2 sync disabled
09-06 19:23:03.743  1029  1113 I art     : Explicit concurrent mark sweep GC freed 78123(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 4.276ms total 341.016ms
,09-06 19:23:03.745  1801  4754 I Icing   : doRemovePackageData com.test.thalitest
09-06 19:23:03.746  7054  7054 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-06 19:23:03.757  1801  8310 W GmsApplication: Using Auth Proxy for data requests.
,09-06 19:23:03.773  2296  8314 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:23:03.779  1029  2015 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8316 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-06 19:23:03.782  1801  8310 W GmsApplication: Using Auth Proxy for data requests.
,09-06 19:23:03.826  2138  2305 I art     : Explicit concurrent mark sweep GC freed 7148(411KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 742us total 26.905ms
,09-06 19:23:03.830  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-06 19:23:03.832  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:23:03.834  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-06 19:23:03.835  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-06 19:23:03.836  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-06 19:23:03.837  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-06 19:23:03.853  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-06 19:23:03.860  1029  1101 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3462fcc u0 com.lge.launcher2/.Launcher t5} time:142550
09-06 19:23:03.860  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-06 19:23:03.861  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:23:03.869  3208  8335 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-06 19:23:03.869   328   417 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-06 19:23:03.870  2017  2246 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-06 19:23:03.870  2017  2246 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-06 19:23:03.877  8316  8316 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:23:03.877  8316  8316 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:23:03.878  8316  8316 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:23:03.878  8316  8316 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:23:03.879  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-06 19:23:03.881  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 19:23:03.881  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:23:03.889  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-06 19:23:03.892  2564  2564 D [Concierge]Service: onStartCommand(). Type : 8
09-06 19:23:03.892  2564  2564 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-06 19:23:03.892  2564  2564 D [Concierge]Service: Update widget ID : 11
09-06 19:23:03.895  2017  2017 D [Concierge]WidgetView: change position of spinner
09-06 19:23:03.896  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1473182583896
09-06 19:23:03.896  2564  2564 D [Concierge]Service: onStartCommand(). Type : 0
09-06 19:23:03.898  8269  8269 D AndroidRuntime: Shutting down VM
09-06 19:23:03.928  1029  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:23:03.933  1029  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-06 19:23:03.938  1029  1113 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8337 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:23:03.941  8316  8316 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-06 19:23:03.945  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 815501576
,09-06 19:23:03.945  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-06 19:23:03.946  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-06 19:23:03.948  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1d623a88
09-06 19:23:03.948  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-06 19:23:03.949  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 19:23:03.949  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:23:03.951  8316  8316 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-06 19:23:03.954  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-06 19:23:03.954  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-06 19:23:03.955  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 19:23:03.955  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473182468730, New one : 1473182583896
09-06 19:23:03.955  2017  2017 D [Concierge]WidgetView: Unregister all receivers
,09-06 19:23:03.955  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 19:23:03.956  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 19:23:03.957  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:23:03.958  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-06 19:23:03.959  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-06 19:23:03.960  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-06 19:23:03.961  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-06 19:23:03.962  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-06 19:23:03.966  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:23:03.966  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 19:23:03.981  1029  1907 I ActivityManager: Killing 7748:com.google.android.talk/u0a72 (adj 15): empty #17
,09-06 19:23:03.986  8316  8316 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:23:04.013  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-06 19:23:04.020  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-06 19:23:04.020  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-06 19:23:04.021  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:23:04.040  1029  1044 W libprocessgroup: failed to open /acct/uid_10072/pid_7748/cgroup.procs: No such file or directory
,09-06 19:23:04.042  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@34e83b0d time:142732
09-06 19:23:04.060  8316  8316 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:23:04.060  8316  8316 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:23:04.109  8316  8316 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-06 19:23:04.120  1029  1907 I ActivityManager: Killing 7841:com.android.vending/u0a44 (adj 15): empty #17
,09-06 19:23:04.130  1029  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=76.0, 0.0, 0.0  rx=74.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:8801602] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:23:04.130  1029  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=76.0, 0.0, 0.0  rx=74.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:8801602] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:23:04.130  1029  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-06 19:23:04.168  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-06 19:23:04.193  1029  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-06 19:23:04.200  1980  1980 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 19:23:04.200  1980  1980 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-06 19:23:04.201  1029  1961 W libprocessgroup: failed to open /acct/uid_10044/pid_7841/cgroup.procs: No such file or directory
09-06 19:23:04.203  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:23:04.203  1980  1980 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:23:04.208  8178  8178 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 19:23:04.210  8178  8178 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 19:23:04.217  7510  7510 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-06 19:23:04.217  2017  2852 I GBoardtInterface: onReloaded()
09-06 19:23:04.220  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-06 19:23:04.220  6855  6855 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-06 19:23:04.223  3807  4467 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:23:04.226  3807  3826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:23:04.226  6855  6855 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-06 19:23:04.226  6855  6855 D HideNavigationAppsReceiver: replacing : false
09-06 19:23:04.228  6855  6855 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-06 19:23:04.229  1029  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:23:04.229  6855  6855 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-06 19:23:04.229  6855  6855 D ButtonCombinationReceiver: replacing : false
09-06 19:23:04.231  1029  1100 D Tethering: MasterInitialState.processMessage what=3
09-06 19:23:04.231  1029  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:23:04.233  2489  2529 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml.bak
09-06 19:23:04.233  1029  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:23:04.234  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-06 19:23:04.249  1029  1715 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8362 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:23:04.252  1889  1889 D ActionManagerService: notifyUserLog: 1000001
09-06 19:23:04.253  3807  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 19:23:04.253  3807  4466 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-06 19:23:04.255  1889  1889 D ActionManagerService: notifyUserLog: 1000001
09-06 19:23:04.256  3807  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 19:23:04.256  3807  4466 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-06 19:23:04.256  3807  4466 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-06 19:23:04.256  3807  4466 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-06 19:23:04.257  3807  4467 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:23:04.259  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-06 19:23:04.259  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-06 19:23:04.261  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-06 19:23:04.261  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,09-06 19:23:04.263  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-06 19:23:04.263  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay

```
