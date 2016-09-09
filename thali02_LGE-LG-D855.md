#### Test 83591764f116baa_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-09 17:12:14.410  6647  6647 D DocsApplication: Installing DEX configuration.
09-09 17:12:14.436  6647  6647 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-09 17:12:14.442  6647  6647 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{fa83f91 com.google.android.apps.docs}
09-09 17:12:14.460  6647  6647 D TAG     : onCreate()
09-09 17:12:14.481  6647  6647 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,09-09 17:12:15.273  1846  4780 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-09 17:12:15.445  1846  4780 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-09 17:12:15.484  1846  4780 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-09 17:12:15.541  6684  6684 D AndroidRuntime: 
09-09 17:12:15.541  6684  6684 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 17:12:15.544  6684  6684 D AndroidRuntime: CheckJNI is OFF
09-09 17:12:15.668  6684  6684 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 17:12:15.671  1037  2018 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 17:12:15.683  1978  3967 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-09 17:12:15.686  1037  2018 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-09 17:12:15.687  1037  2018 D ActivityManager: setTaskToReturnTo : TaskRecord{41da79e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 17:12:15.687  1037  2018 D ActivityManager: setTaskToReturnTo : TaskRecord{41da79e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 17:12:15.688  1037  2018 D WindowStateEx: AppWindowTokenEx init.. 
09-09 17:12:15.689   353   378 E GBMv2   : DFP En is all cleared set to be enabled
09-09 17:12:15.722  1037  2018 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6717 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 17:12:15.723  6684  6684 D AndroidRuntime: Shutting down VM
09-09 17:12:15.763  1978  3967 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-09 17:12:15.763  1978  3967 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2756acdd co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 17:12:15.764  1978  1994 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-09 17:12:15.764  1978  1994 D SplitWindowPolicy: topRunningActivity=ActivityInfo{38812052 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 17:12:15.801  6717  6717 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 17:12:15.857  6717  6717 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-09 17:12:15.863  6717  6717 I LibraryLoader: Loading: webviewchromium
09-09 17:12:15.865  6717  6717 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4740-4742)
09-09 17:12:15.865  6717  6717 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:12:15.875  6717  6717 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dfb3793}
09-09 17:12:15.876  6717  6717 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:12:15.876  6717  6717 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 17:12:15.882  6717  6717 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 17:12:15.883  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:12:15.893  6717  6717 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 17:12:15.894  6717  6717 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,09-09 17:12:15.894  6717  6717 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-09 17:12:15.897   333   333 V AudioPolicyService: registerClient() client 0xb558a660, uid 10118
09-09 17:12:15.901  1037  1099 D BluetoothManagerService: Message: 20
09-09 17:12:15.901  1037  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cb5d738:true
09-09 17:12:15.909  6717  6717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:12:15.909  6717  6717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:12:15.909  6717  6717 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:12:15.909  6717  6717 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:12:15.909  6717  6717 I Adreno-EGL: Remote Branch: 
09-09 17:12:15.909  6717  6717 I Adreno-EGL: Local Patches: 
09-09 17:12:15.909  6717  6717 I Adreno-EGL: Reconstruct Branch: 
09-09 17:12:16.008  6717  6746 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-09 17:12:16.010  6717  6717 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-09 17:12:16.033  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:12:16.035  6647  6647 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:16.035  6647  6647 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:12:16.038  6717  6717 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 17:12:16.041  6717  6717 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 17:12:16.044  6717  6717 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 17:12:16.044  6717  6717 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-09 17:12:16.058  6717  6717 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-09 17:12:16.066  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:12:16.066  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:12:16.088  6717  6762 D OpenGLRenderer: Render dirty regions requested: true
09-09 17:12:16.088  6717  6762 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 17:12:16.094  6717  6762 D OpenGLRenderer: Enabling debug mode 0
09-09 17:12:16.101  6717  6717 D Atlas   : Validating map...
,09-09 17:12:16.104  1037  1786 D SplitWindow: check instance of lgWin Window{139067b2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 17:12:16.134  6717  6760 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:16.134  6717  6760 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:16.162  6172  6172 I LockScreenSettings: New app installed broadcast received ..
,09-09 17:12:16.165  6172  6172 I LockScreenSettings: Number of installed packages  1
09-09 17:12:16.171  6647  6647 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-09 17:12:16.218  1037  1100 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +455ms (total +528ms)
09-09 17:12:16.218  1037  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{be6b27f u0 com.test.thalitest/.MainActivity t6} time:105095
,09-09 17:12:16.219  1037  1780 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:12:16.224  6717  6717 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a331f7e time:105101
09-09 17:12:16.269  1037  2018 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6783 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:12:16.317  6783  6783 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-09 17:12:16.317  6783  6783 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-09 17:12:16.333  6717  6717 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-09 17:12:16.333  6717  6717 I chromium: 
,09-09 17:12:16.343  6717  6717 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-09 17:12:16.366  1037  2018 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6800 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 17:12:16.368  1037  2018 I ActivityManager: Killing 5858:com.google.android.gm/u0a64 (adj 15): empty #17
09-09 17:12:16.441  6717  6817 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,09-09 17:12:16.451  6717  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 17:12:16.451  6717  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 17:12:16.451  6717  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 17:12:16.451  6717  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 17:12:16.451  6717  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 17:12:16.452  6717  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29776be2 added. We now have 1 listener(s)
09-09 17:12:16.454  1037  1053 W libprocessgroup: failed to open /acct/uid_10064/pid_5858/cgroup.procs: No such file or directory
,09-09 17:12:16.463  1037  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:16.466  6717  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-09 17:12:16.468  6717  6817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:16.470  6717  6817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:16.470  6717  6817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 17:12:16.479  6717  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@190766a9 added. We now have 1 listener(s)
09-09 17:12:16.480  6717  6817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:16.485  1037  1546 D WifiService: New client listening to asynchronous messages
09-09 17:12:16.489  6717  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:12:16.489  6717  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 17:12:16.490  6717  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 17:12:16.490  6717  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 17:12:16.490  6717  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 17:12:16.494  6717  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:16.495  1037  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:16.496  6717  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-09 17:12:16.507  6717  6817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:16.507  6717  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:16.507  6717  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 17:12:16.507  6717  6817 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:12:16.511  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:16.513  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:16.513  6717  6817 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 17:12:16.549  6800  6800 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-09 17:12:16.561  6717  6760 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-09 17:12:16.561  6717  6760 I chromium: 
,09-09 17:12:16.573  6800  6800 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-09 17:12:16.583  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 17:12:16.615  6523  6523 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-09 17:12:16.617  1037  1053 I ActivityManager: Killing 5901:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 17:12:16.622  6717  6717 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-09 17:12:16.704  1037  2010 W libprocessgroup: failed to open /acct/uid_10072/pid_5901/cgroup.procs: No such file or directory
,09-09 17:12:16.898   353   380 E GBMv2   : DFP En is all cleared set to be enabled
09-09 17:12:16.899   353   380 E GBMv2   : Set value is all cleared set the max
,09-09 17:12:16.899   353   380 I GBMv2   : DFP Enabled. Ignore VFP set
09-09 17:12:17.680  6717  6820 W jxcore-log: Initializing JXcore engine
09-09 17:12:17.680  6717  6820 W jxcore-log: JXcore engine is ready
,09-09 17:12:17.729  6820  6820 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8454]" dev="sockfs" ino=8454 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 17:12:17.729  6820  6820 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-09 17:12:17.729  6820  6820 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9874]" dev="sockfs" ino=9874 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 17:12:17.729  6820  6820 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-09 17:12:17.729  6820  6820 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31994]" dev="sockfs" ino=31994 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-09 17:12:17.746  6717  6820 W jxcore-log: Starting JXcore engine
,09-09 17:12:17.837  6717  6820 W jxcore-log: Platform android
09-09 17:12:17.837  6717  6820 W jxcore-log: 
09-09 17:12:17.837  6717  6820 W jxcore-log: Process ARCH arm
09-09 17:12:17.837  6717  6820 W jxcore-log: 
,09-09 17:12:18.014  2799  2799 I MusicWidget: mDelayedStopHandler : unbind
,09-09 17:12:18.023  6717  6820 I jxcore-log: JXcore Cordova bridge is ready!
09-09 17:12:18.023  6717  6820 I jxcore-log: 
09-09 17:12:18.023  6717  6820 W jxcore-log: JXcore engine is started
09-09 17:12:18.026  2188  2188 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-09 17:12:18.026  2188  2188 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-09 17:12:18.027  2188  2188 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-09 17:12:18.028  2188  2188 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-09 17:12:18.028  2188  2188 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-09 17:12:18.028  2188  2188 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-09 17:12:18.029  2188  2188 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-09 17:12:18.030  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,09-09 17:12:18.031  1037  2054 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1699bd39com.lge.music.MediaPlaybackService$5@a331f7e
09-09 17:12:18.031  2188  2188 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-09 17:12:18.032  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-09 17:12:18.035  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.036  6717  6817 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 17:12:18.037  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.038  2188  2188 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1c17b9ef
09-09 17:12:18.038  6717  6717 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-09 17:12:18.039  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.040  2188  2188 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-09 17:12:18.040  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.040  2188  2188 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-09 17:12:18.041  2188  2188 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-09 17:12:18.041  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.052  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-09 17:12:18.055  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.056  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.056  2188  2188 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:12:18.057  2188  2188 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-09 17:12:18.059  2188  2188 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-09 17:12:18.059  2188  2188 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-09 17:12:18.059  2188  2188 V MediaPlayer[Native]: reset
09-09 17:12:18.066  2188  2188 V MediaPlayer[Native]: setListener
09-09 17:12:18.066  2188  2188 V MediaPlayer[Native]: disconnect
09-09 17:12:18.066  2188  2188 V MediaPlayer[Native]: destructor
09-09 17:12:18.066   333   333 V AudioFlinger: releasing 18 from 2188 for -1
09-09 17:12:18.066   333   333 V AudioFlinger:  decremented refcount to 0
09-09 17:12:18.066   333   333 V AudioFlinger: purging stale effects
09-09 17:12:18.066  2188  2188 V MediaPlayer[Native]: disconnect
,09-09 17:12:18.068  2188  2188 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-09 17:12:18.073  2188  2188 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-09 17:12:18.073  2188  2188 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-09 17:12:18.074  2188  2188 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-09 17:12:18.074  2188  2188 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-09 17:12:18.074  2188  2188 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-09 17:12:18.074  2188  2188 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 80805087
09-09 17:12:18.075  2188  2188 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 80805087
09-09 17:12:18.078  2188  2188 I SmartShareClient: [SmartShareManagerClient] terminate service: 2188/MediaPlaybackService/595608525
09-09 17:12:18.082  2188  2188 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-09 17:12:18.082  2188  2188 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@2d81cd2c
,09-09 17:12:18.094  2188  2188 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-09 17:12:18.095  2188  2188 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-09 17:12:18.097  2188  2188 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-09 17:12:18.097  2188  2188 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-09 17:12:18.099  1037  2018 I ActivityManager: Killing 5675:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-09 17:12:18.100  2188  2188 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
,09-09 17:12:18.114  5650  5650 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 17:12:18.114  5650  5650 W System.err: android.os.DeadObjectException
,09-09 17:12:18.114  5650  5650 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-09 17:12:18.115  5650  5650 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-09 17:12:18.115  5650  5650 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 17:12:18.115  5650  5650 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 17:12:18.115  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 17:12:18.115  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 17:12:18.115  5650  5650 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:12:18.115  5650  5650 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:12:18.115  5650  5650 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:18.115  5650  5650 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:12:18.115  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:18.115  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:12:18.115  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:12:18.115  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:12:18.115  5650  5650 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 17:12:18.115  5650  5650 W System.err: android.os.DeadObjectException
09-09 17:12:18.116  5650  5650 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:12:18.116  5650  5650 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-09 17:12:18.116  5650  5650 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 17:12:18.116  5650  5650 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 17:12:18.116  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 17:12:18.116  5650  5650 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 17:12:18.116  5650  5650 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:12:18.116  5650  5650 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,09-09 17:12:18.116  5650  5650 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:18.116  5650  5650 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:12:18.116  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:18.116  5650  5650 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:12:18.116  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,09-09 17:12:18.116  5650  5650 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:12:18.116  5650  5650 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 17:12:18.117  5650  5650 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-09 17:12:18.339  1037  1780 W libprocessgroup: failed to open /acct/uid_1000/pid_5675/cgroup.procs: No such file or directory
09-09 17:12:18.340  1037  1780 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-09 17:12:18.347  5650  5650 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,09-09 17:12:18.355  5650  5650 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 17:12:18.387  1037  1053 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6831 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:12:18.387  5650  5650 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 17:12:18.436  6831  6831 D UEI.SmartControl: Quickset Services start...
09-09 17:12:18.437  6831  6831 I UEI.SmartControl: Manufacture = LGE
09-09 17:12:18.437  6831  6831 D UEI.SmartControl: Id = LGNevo
,09-09 17:12:18.439  6831  6831 D UEI.SmartControl: File observer start...
,09-09 17:12:18.439  6831  6831 E UEI.SmartControl: IR Port is disabled: false
,09-09 17:12:18.440  6831  6831 D UEI.SmartControl: Starting file observer...
09-09 17:12:18.440  6831  6831 D UEI.SmartControl: Extracting JNI libs...
09-09 17:12:18.440  6831  6831 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 17:12:18.527  6831  6831 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 17:12:18.527  6831  6831 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 17:12:18.527  6831  6831 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 17:12:18.567  6831  6831 I UEI.SmartControl: --- Selecting new region: 6
09-09 17:12:18.569  6831  6831 I UEI.SmartControl: Model = LG-D855
09-09 17:12:18.571  6831  6831 D UEI.SmartControl: QS Service created
,09-09 17:12:18.596  6831  6831 I UEI.SmartControl: Service initServices...
,09-09 17:12:18.602  6831  6831 D UEI.SmartControl: QS start get config
,09-09 17:12:18.665  6831  6831 D UEI.SmartControl: Loading JNI Libs...
,09-09 17:12:19.036  6831  6831 I UEI.SmartControl: Supports setup maps: true
09-09 17:12:19.042  6831  6831 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 17:12:19.042  6831  6831 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 17:12:19.042  6831  6831 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 17:12:19.042  6831  6831 I UEI.SmartControl: ### init IR Blaster...
,09-09 17:12:19.050  6831  6831 D serial_port: Configuring serial port
09-09 17:12:19.056  6831  6831 E UEI.SmartControl: UEIBLaster setting for 616
09-09 17:12:19.056  6831  6831 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 17:12:19.057  6831  6831 I UEI.SmartControl: configuring settings for MAXQ616
09-09 17:12:19.057  6831  6831 I UEI.SmartControl: Get version...
09-09 17:12:19.073  6831  6852 D UEI.SmartControl: serial port data available: 21
,09-09 17:12:19.102  6831  6831 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 17:12:19.102  6831  6831 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 17:12:19.102  6831  6831 I UEI.SmartControl: QS saving settings...
,09-09 17:12:19.105  6831  6831 D UEI.SmartControl: IR Blaster version: 25672567
09-09 17:12:19.121  6831  6852 D UEI.SmartControl: serial port data available: 4
,09-09 17:12:19.158  6831  6831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 17:12:19.165  6831  6855 I UEI.SmartControl: Device manager: loading config....
09-09 17:12:19.165  6831  6855 D UEI.SmartControl: ----------- loading internal config...
09-09 17:12:19.175  6831  6831 E UEI.SmartControl: Services init done
,09-09 17:12:19.178  6831  6855 E UEI.SmartControl: Loading SETTINGS...
09-09 17:12:19.180  6831  6831 D UEI.SmartControl: QS Service init finished
09-09 17:12:19.181  6831  6831 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 17:12:19.181  6831  6831 D UEI.SmartControl: QS Service version code: 201091
09-09 17:12:19.181  6831  6831 D UEI.SmartControl: Service requested: Control
09-09 17:12:19.183  5650  5650 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 17:12:19.184  6831  6846 I UEI.SmartControl: ------ IControl API: 11
09-09 17:12:19.184  1037  2081 I ActivityManager: Killing 5650:com.lge.qremote/u0a112 (adj 15): empty #17
09-09 17:12:19.185  6831  6846 I UEI.SmartControl: Registering callback...
09-09 17:12:19.188  6831  6855 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-09 17:12:19.194  6831  6854 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 17:12:19.194  6831  6854 D UEI.SmartControl: -----service ready thread exits
09-09 17:12:19.313  1037  2007 W libprocessgroup: failed to open /acct/uid_10112/pid_5650/cgroup.procs: No such file or directory
,09-09 17:12:19.317  6831  6831 D UEI.SmartControl: Internal service binding...
,09-09 17:12:20.128  6647  6647 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-09 17:12:20.135  1037  1577 I ActivityManager: Killing 6328:com.android.calendar/u0a13 (adj 15): empty #17
09-09 17:12:20.217  1037  1973 W libprocessgroup: failed to open /acct/uid_10013/pid_6328/cgroup.procs: No such file or directory
,09-09 17:12:21.102  6647  6754 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 17:12:23.410  1846  6555 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 17:12:23.417   328  6876 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 17:12:23.417   328  6876 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-09 17:12:23.417   328  6876 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-09 17:12:24.163  6831  6856 D UEI.SmartControl: Internal timer expired: 1
09-09 17:12:24.163  6831  6856 D UEI.SmartControl: unbind internal service
,09-09 17:12:24.207  6831  6831 D UEI.SmartControl: Service.onUnbind: IControl
,09-09 17:12:24.220  6831  6831 D UEI.SmartControl: Service.onDestroy
09-09 17:12:24.220  6831  6831 D UEI.SmartControl: Lock is in USE false
09-09 17:12:24.220  6831  6831 D UEI.SmartControl: unbind internal service
09-09 17:12:24.220  6831  6831 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1c17b9ef
09-09 17:12:24.221  6831  6831 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-09 17:12:24.221  6831  6831 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-09 17:12:24.221  6831  6831 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:24.221  6831  6831 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:12:24.221  6831  6831 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:24.221  6831  6831 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:12:24.221  6831  6831 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:12:24.221  6831  6831 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:12:24.221  6831  6831 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1c17b9ef
,09-09 17:12:24.292  6831  6831 D serial_port: close(fd = 25)
,09-09 17:12:24.318  6831  6831 I UEI.SmartControl: Serial port is closed.
,09-09 17:12:24.321  6831  6831 I UEI.SmartControl: Serial port is closed.
,09-09 17:12:24.322  6831  6831 D UEI.SmartControl: Blaster closed
,09-09 17:12:24.322  6831  6831 D UEI.SmartControl: Shut down QS...
09-09 17:12:24.322  6831  6831 D UEI.SmartControl: Stopping QS lib
09-09 17:12:24.323  6831  6831 D UEI.SmartControl: QS lib stop result = true
09-09 17:12:24.323  6831  6831 D UEI.SmartControl: Stopped QS lib
09-09 17:12:24.323  6831  6831 D UEI.SmartControl: Stopped file observer...
09-09 17:12:24.323  6831  6831 D UEI.SmartControl: QS shutdown complete
,09-09 17:12:28.112  2188  2188 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,09-09 17:12:28.370  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 17:12:28.370  6717  6820 I jxcore-log: 
,09-09 17:12:28.372  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 17:12:28.372  6717  6820 I jxcore-log: 
,09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:28.377  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:28.379  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:28.381  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 17:12:28.381  6717  6820 I jxcore-log: 
09-09 17:12:28.383  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 17:12:28.383  6717  6820 I jxcore-log: 
09-09 17:12:28.548  1037  1095 I ActivityManager: Waited long enough for: ServiceRecord{26bffc66 u0 com.google.android.gms/.wearable.service.WearableService}
,09-09 17:12:28.889  6717  6820 D executeNativeTests: Running unit tests
,09-09 17:12:28.969  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:28.969  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 added. We now have 2 listener(s)
,09-09 17:12:28.970  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:28.974  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:28.974  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:28.974  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:28.975  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:28.975  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 added. We now have 2 listener(s)
09-09 17:12:28.975  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:28.975  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:12:28.978  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:28.982  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:28.984  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:28.985  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:28.987  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:28.989  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:28.990  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:12:28.990  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:12:28.990  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:12:28.992  6717  6820 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 17:12:28.992  6717  6820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:12:28.992  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 17:12:28.992  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:28.992  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:28.993  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:28.994  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:28.994  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:28.995  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:28.995  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:28.995  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:12:28.995  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:28.995  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 removed from the list
09-09 17:12:28.995  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:28.995  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 removed from the list
09-09 17:12:28.995  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:12:28.995  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:28.997  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:28.997  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:28.998  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:28.998  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:28.998  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:28.998  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.000  6717  6820 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 17:12:29.000  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.000  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.000  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.001  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.001  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:12:29.001  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.001  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.001  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.001  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.001  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.001  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.001  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.001  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.001  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.002  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:12:29.002  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.002  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.002  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:12:29.006  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:12:29.007  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:12:29.007  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:12:29.007  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 17:12:29.007  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:12:29.007  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-09 17:12:29.007  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:12:29.007  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.007  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.007  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.007  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:29.007  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.007  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.007  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.007  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.007  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
,09-09 17:12:29.007  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.007  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.007  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.007  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.007  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.009  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:12:29.009  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.009  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.009  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.009  6717  6820 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 17:12:29.011  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:29.013  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:29.014  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.014  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:29.016  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.017  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 17:12:29.017  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:29.018  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:29.018  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:29.018  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:29.018  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:29.024  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:29.025  1037  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:29.029  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:12:29.032  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:12:29.034  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 17:12:29.034  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:29.034  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:29.035  6717  6820 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:12:29.036  6717  6820 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:12:29.038  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.038  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.038  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.038  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.038  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.038  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:29.038  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.038  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.038  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.038  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.038  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.039  6717  6820 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:12:29.040  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:29.042  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:29.043  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.043  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:29.044  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.045  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:29.045  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.045  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:29.045  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:29.045  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:29.045  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:29.048  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:29.048  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:29.049  6717  6820 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 17:12:29.052  6717  6820 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:12:29.053  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.053  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.053  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.054  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.054  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.054  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:29.054  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.054  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.054  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.054  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.054  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.054  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.054  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.054  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.055  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.056  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.056  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.056  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.056  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.056  6717  6820 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:12:29.057  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:29.059  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:29.060  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.060  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:29.060  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:29.060  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:29.060  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:29.060  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:29.060  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:29.061  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.062  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.065  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:29.065  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:29.066  6717  6820 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:12:29.066  6717  6820 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:12:29.066  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.066  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.066  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.067  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.067  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.067  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.067  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.067  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.067  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:29.067  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.067  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.067  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.067  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.067  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.067  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.068  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.068  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.068  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.068  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.068  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.068  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.068  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.069  6717  6820 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 17:12:29.069  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.069  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.069  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.069  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.069  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.069  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.069  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.069  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.070  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.070  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.070  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.070  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.070  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.070  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.070  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.070  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.071  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.071  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.071  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.071  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.071  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:12:29.072  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.072  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.072  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.072  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.072  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.072  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.072  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.072  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.072  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.072  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.072  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.072  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.072  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.072  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.073  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.073  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.073  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.073  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.073  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.073  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.074  6717  6820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 17:12:29.074  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.074  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.074  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.074  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.074  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.074  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.074  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.074  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.074  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.074  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.074  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.074  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.074  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.074  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.075  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.075  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.075  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.075  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.076  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.076  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.076  6717  6820 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 17:12:29.076  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.076  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.076  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.076  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.076  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.076  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.077  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.077  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.077  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.077  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.077  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.077  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.077  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.077  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.077  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.077  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.078  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.078  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.078  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.078  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.078  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:12:29.078  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:12:29.078  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:12:29.078  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:29.078  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:12:29.078  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:12:29.078  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.078  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.078  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.079  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.079  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.079  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.079  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.079  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.079  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.079  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.079  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.079  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.079  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.079  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.080  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.080  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.080  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.080  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.080  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.080  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
,09-09 17:12:29.081  6717  6820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:29.081  6717  6820 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:12:29.081  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 17:12:29.082  6717  6820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:29.083  6717  6820 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:12:29.083  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:12:29.083  6717  6820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 17:12:29.083  6717  6820 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:12:29.084  6717  6820 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 17:12:29.084  6717  6820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:29.084  6717  6820 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:12:29.084  6717  6820 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 17:12:29.084  6717  6820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:29.084  6717  6820 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:12:29.084  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 17:12:29.086  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 17:12:29.087  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 17:12:29.087  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 17:12:29.087  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 17:12:29.087  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 17:12:29.088  6717  6820 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 17:12:29.088  6717  6820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:29.088  6717  6820 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 17:12:29.088  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.088  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.088  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.088  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.088  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.088  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.089  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 17:12:29.089  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.089  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.089  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.089  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.089  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.089  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.089  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.089  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.090  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.090  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.091  6717  6898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
09-09 17:12:29.093  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.093  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.093  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.093  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.094  6717  6820 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 17:12:29.094  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.094  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.094  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.094  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.094  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.094  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.094  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.094  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.094  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.094  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.094  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.094  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.094  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.094  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.095  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.095  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.095  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.095  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.095  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.095  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.096  6717  6820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 17:12:29.103  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.103  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.103  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.103  6717  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
09-09 17:12:29.103  6717  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
09-09 17:12:29.103  6717  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
09-09 17:12:29.105  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.105  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.105  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.105  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.105  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.105  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.105  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.105  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.105  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.105  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.105  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.108  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.108  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.109  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.109  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.109  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.109  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.109  6717  6820 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 17:12:29.109  6717  6820 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 17:12:29.109  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:12:29.110  6717  6820 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 17:12:29.110  6717  6820 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:12:29.110  6717  6820 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 17:12:29.110  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:12:29.110  6717  6820 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 17:12:29.110  6717  6820 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:12:29.110  6717  6820 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:12:29.110  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:12:29.110  6717  6820 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 17:12:29.110  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.110  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.110  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.111  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.111  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.111  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.111  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.111  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.111  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.111  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.111  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.111  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.111  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.111  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.111  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.111  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.112  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.112  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.112  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.112  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.112  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.112  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.112  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.112  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.112  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.112  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.112  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.112  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.112  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.113  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.113  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.113  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.113  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.113  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.113  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.113  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.113  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.113  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.114  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.114  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.114  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.114  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.114  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.114  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.114  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.114  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.114  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.114  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.114  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.115  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.115  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.115  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.115  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.115  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.115  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.118  6717  6820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 17:12:29.119  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:29.120  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 17:12:29.121  6717  6820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 17:12:29.121  6717  6820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 17:12:29.122  6717  6717 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 17:12:29.122  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 17:12:29.122  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:12:29.124  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.124  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 17:12:29.124  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 17:12:29.124  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 17:12:29.124  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.124  6717  6820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 17:12:29.132  6717  6717 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 17:12:29.132  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.132  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.132  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:12:29.132  6717  6820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 17:12:29.133  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:12:29.134  6717  6902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 17:12:29.135  6717  6902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 17:12:29.135  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:12:29.135  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:29.135  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:29.135  6717  6820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:12:29.135  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.136  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.137  6717  6820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:29.137  6717  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:29.137  6717  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:29.137  6717  6717 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 17:12:29.137  6717  6717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:29.137  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.137  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.137  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.137  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.137  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.137  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.137  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.137  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.137  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.137  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.137  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.137  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.137  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.137  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.138  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.138  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.138  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.138  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.138  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.139  6717  6820 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 17:12:29.139  6717  6820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:12:29.139  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:12:29.140  6717  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:29.140  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.140  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.140  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.140  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.140  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.140  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.140  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.140  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.140  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.140  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.140  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.140  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.140  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.140  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.141  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.141  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.141  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.141  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.142  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:29.143  1037  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:29.143  1037  2328 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:29.145  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.145  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.145  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.145  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.145  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.145  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.145  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.145  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.145  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.145  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.145  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.145  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.145  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.145  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.146  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.146  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.146  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.146  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.147  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:29.147  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:29.147  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:29.147  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:29.147  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.147  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.147  6717  6820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e48632 not in the list
09-09 17:12:29.147  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.147  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.147  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:29.147  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.147  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.147  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:29.147  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:29.148  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:29.148  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:29.148  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:29.148  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8f83 not in the list
09-09 17:12:29.149  6717  6820 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 17:12:29.149  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:12:29.149  6717  6820 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 17:12:29.149  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:12:29.149  6717  6820 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 17:12:29.149  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:12:29.151  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:12:29.151  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 17:12:29.151  6717  6820 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 17:12:29.151  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:12:29.151  6717  6820 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 17:12:29.151  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:12:29.151  6717  6820 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 17:12:29.151  6717  6820 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 17:12:29.152  6717  6820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 17:12:29.152  6717  6820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 17:12:29.153  6717  6820 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 17:12:29.153  6717  6820 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 17:12:29.153  6717  6820 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 17:12:29.153  6717  6820 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 17:12:29.153  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:29.153  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20e4a418 added. We now have 2 listener(s)
09-09 17:12:29.153  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:29.154  6717  6820 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 17:12:29.156  1037  1053 D WifiServiceImplEx: setWifiEnabled: true pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-09 17:12:29.156  1037  1053 D WifiService: setWifiEnabled: true pid=6717, uid=10118
09-09 17:12:29.156  1037  1053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:12:29.157  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:29.157  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2de95e71 added. We now have 3 listener(s)
09-09 17:12:29.157  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:29.160  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:29.160  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2389d456 added. We now have 4 listener(s)
09-09 17:12:29.160  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:29.161  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:12:29.161  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30e5ccd7 added. We now have 5 listener(s)
09-09 17:12:29.161  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:29.163  1037  1780 D WifiServiceImplEx: setWifiEnabled: false pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:12:29.163  1037  1780 D WifiService: setWifiEnabled: false pid=6717, uid=10118
09-09 17:12:29.163  1037  1780 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:12:29.191  1037  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:29.191  1037  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:29.192  1037  1577 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1d9b6d2f mBinding = false
,09-09 17:12:29.192  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-09 17:12:29.192  1037  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:29.193  1037  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:29.193  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:12:29.193  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:12:29.193  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-09 17:12:29.193  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:29.193  1037  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 17:12:29.194  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:29.194  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:12:29.195  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-09 17:12:29.195  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:12:29.203  6717  6898 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,09-09 17:12:29.203  6717  6898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
,09-09 17:12:29.247  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-09 17:12:29.247  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:12:29.247  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.247  2704  2704 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:12:29.247  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.248  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:12:29.248  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:29.248  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:29.249  1037  2866 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.249   328   897 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:12:29.252  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:12:29.252  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:12:29.252  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-09 17:12:29.252  1037  1099 D BluetoothManagerService: Message: 2
09-09 17:12:29.253  1037  1099 D BluetoothManagerService: Sending off request.
09-09 17:12:29.253  3872  3893 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,09-09 17:12:29.255  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:29.257  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:29.258  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:29.258  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:29.259  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.260  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.260  3872  3966 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 17:12:29.260  3872  3966 D BluetoothAdapterProperties: Setting state to 13
09-09 17:12:29.260  3872  3966 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 17:12:29.261  3872  3966 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:12:29.261  3872  3966 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 17:12:29.265  3872  3974 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:12:29.265  3872  3966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 17:12:29.266  3872  3966 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 17:12:29.266  3872  4225 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 17:12:29.267  3872  4253 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:29.268  3872  4248 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:29.270  3872  4226 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:29.271  1037  1385 V AlarmManager: RTC_WAKEUP set : Alarm{21f7d328 type 0 when 1473433949098 com.android.vending} when 1473433949098
0,9-09 17:12:29.271  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 17:12:29.271  3872  4079 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 17:12:29.272  3872  4250 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 17:12:29.282  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 17:12:29.282  3872  4079 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:12:29.288  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 17:12:29.289  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-09 17:12:29.301  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:29.301  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:29.303  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.303  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:29.304  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:29.304  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:29.305  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:29.305  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 17:12:29.305  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 17:12:29.305  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.305  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:29.330  1037  1095 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6908 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-09 17:12:29.333  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.334  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.334  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.334  1037  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:12:29.334  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.335  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.335  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.336  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.336  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.337  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:29.337  1037  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.338  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.338  1037  1539 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1e7a7a69
09-09 17:12:29.338  1037  1539 D LGWifiP2pService: P2pDisablingState
09-09 17:12:29.338  1037  1539 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.338  1037  1539 D LGWifiP2pService: p2p socket connection lost
09-09 17:12:29.338  1037  1539 D LGWifiP2pService: P2pDisabledState
09-09 17:12:29.340  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:29.340  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:29.342  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-09 17:12:29.343  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-09 17:12:29.344  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.344  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.344  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:29.346  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.347  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-09 17:12:29.347  1037  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 17:12:29.347  1037  1547 D DSQN    : disableDataServiceNotify
09-09 17:12:29.348  1037  1547 D DSQN    : stop dsqn bin
09-09 17:12:29.350  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.350  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.350  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:29.351  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:12:29.351  1037  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.352  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-09 17:12:29.352  1037  1559 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.353  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 17:12:29.354  1978  1978 D WfdsService: WifiP2pState is changed : false
09-09 17:12:29.354  1978  2354 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
,09-09 17:12:29.354  1978  2354 D WfdsService: Set the WFDS Monitor: false
09-09 17:12:29.354  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 17:12:29.354  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:12:29.354  2704  2704 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:12:29.355  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:12:29.355  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:29.355  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:29.355   328   897 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:12:29.356  1978  2354 D WfdsMonitor: WFDS Monitor is stopped
09-09 17:12:29.356  1978  2354 D WfdsService: STATE : WfdsDisabledState - enter
09-09 17:12:29.356  1037  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 17:12:29.356  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:29.356  1978  2355 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 17:12:29.356  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:29.356  1978  2763 D CtrlSupplicant: Received on exit socket, terminate
09-09 17:12:29.356  1978  2763 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 17:12:29.356  1037  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:29.356  1978  2763 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 17:12:29.356  1978  2763 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 17:12:29.357  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 17:12:29.357  1978  2354 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 17:12:29.357  1037  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 17:12:29.357  1037  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 17:12:29.357  1606  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 17:12:29.357  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:12:29.358  1037  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.358  1037  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.358  1037  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 17:12:29.358  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:29.359  3872  3872 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:29.359  3872  3872 D BluetoothMapServi,ce: STATE_TURNING_OFF
09-09 17:12:29.359  3872  3872 V BluetoothMapService: Handler(): got msg=4
09-09 17:12:29.359  3872  3872 D BluetoothMapService: MAP Service closeService in
09-09 17:12:29.359  3872  3872 D BluetoothMapMasInstance: MAP Service shutdown
09-09 17:12:29.359  3872  3872 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:12:29.359  3872  3872 V BluetoothMapService: MAP Service closeService out
09-09 17:12:29.359  3872  3872 V BtOppService: Receiver DISABLED_ACTION 
09-09 17:12:29.359  3872  3872 I BtOppRfcommListener: stopping Accept Thread
09-09 17:12:29.360  3872  3872 V BtOppRfcommListener: close mBtServerSocket
09-09 17:12:29.360  3872  3872 V BtOppRfcommListener: waiting for thread to terminate
09-09 17:12:29.360  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.360  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.360  3872  4248 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:12:29.361  3872  3872 V BtOppRfcommListener: done waiting for thread to terminate
09-09 17:12:29.366  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:29.366  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:29.366  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.367  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-09 17:12:29.373  1846  6555 W ConfigFetchTask: exception on config fetch: java.net.ConnectException: failed to connect to cloudconfig.googleapis.com/172.217.16.202 (port 443) after 120000ms: connect failed: ENETUNREACH (Network is unreachable)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: java.net.ConnectException: failed to connect to cloudconfig.googleapis.com/172.217.16.202 (port 443) after 120000ms: connect failed: ENETUNREACH (Network is unreachable)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at libcore.io.IoBridge.connect(IoBridge.java:124)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at java.net.Socket.connect(Socket.java:882)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.Connection.connect(Connection.java:148)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:276)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:208)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.google.android.gms.config.f.a(SourceFile:112)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at com.google.android.gms.config.f.doInBackground(SourceFile:39)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at libcore.io.Posix.connect(Native Method)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-09 17:12:29.373  1846  6555 W ConfigFetchTask: 	... 20 more
09-09 17:12:29.406  1037  2081 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:29.413  1037  1095 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6932 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:12:29.414  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:29.414  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:12:29.416  3872  3872 V BtOppService: onDestroy
09-09 17:12:29.416  1037  1540 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 17:12:29.416  1037  1540 D WifiNative-p2p0: TERMINATE: returned true
09-09 17:12:29.416  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:29.416  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:29.416  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:12:29.418  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:12:29.418  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:12:29.418  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-09 17:12:29.418  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.418  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.418  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:29.418  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:12:29.419  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:12:29.419  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-09 17:12:29.419  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:29.419  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:29.419  1037  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:29.419  1037  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:29.420  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:12:29.421  1037  1547 D NetworkManagementService: Removing idletimer
09-09 17:12:29.421  1882  1882 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:29.421  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:12:29.422  1037  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.422  1037  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 17:12:29.423  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:12:29.423  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:12:29.423  1037  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:29.424  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:29.424  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:12:29.424  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:12:29.425  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 17:12:29.426  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 17:12:29.427  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:29.427  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 17:12:29.429  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:29.429  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:29.429  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.429  6,717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:29.432  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:29.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:29.433  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.433  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:29.434  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:29.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:29.438  1037  2010 I art     : Explicit concurrent mark sweep GC freed 27518(1380KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.780ms total 153.436ms
09-09 17:12:29.440  3872  3872 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-09 17:12:29.450  1846  1846 I ConfigFetchService: fetch service done; releasing wakelock
09-09 17:12:29.454  1846  1846 I ConfigFetchService: stopping self
,09-09 17:12:29.471  6932  6932 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:29.471  6932  6932 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 17:12:29.471  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:12:29.472  6932  6932 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:12:29.472  6932  6932 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-09 17:12:29.472  2206  2206 I ConfigService: onDestroy
09-09 17:12:29.472  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.473  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.473  6932  6932 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 17:12:29.473  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 17:12:29.473  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:29.473  6932  6932 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 17:12:29.474  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.476  1037  2866 D DhcpStateMachine: StoppedState
09-09 17:12:29.476  1037  2866 D DhcpStateMachine: StoppedState{ when=-121ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:29.477  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 17:12:29.477  1037  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 17:12:29.491  2704  2704 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 17:12:29.491  2704  2704 I wpa_supplicant: monitor socket send errors count : 1
09-09 17:12:29.491  2704  2704 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1978-2\x00 that cannot receive messages
09-09 17:12:29.492  1037  2760 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,09-09 17:12:29.492  1037  2760 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 17:12:29.503  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 17:12:29.504  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.504  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.504  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.520  6908  6908 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 17:12:29.521  6908  6908 W LG Account v2.2: No ProfileInfo entries
09-09 17:12:29.521  6908  6908 I LG Account v2.2: isEnabled: false
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Country: EU
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Operator: OPEN
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Ranking support: false
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Comfort support: false
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Accessory: true
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Health device: true
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Extra Pedometer: false
09-09 17:12:29.521  6908  6908 I Feature : [Lifetracker]Blood glucose device: false
09-09 17:12:29.522  6908  6908 I Feature : [Lifetracker]Device Number: 3
,09-09 17:12:29.526  2704  2704 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:12:29.527  2704  2704 W wpa_supplicant: USIM:  scard_deinit function
09-09 17:12:29.527  1037  2760 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 17:12:29.527  1037  2760 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:12:29.527  1037  2760 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:12:29.527  1037  2760 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 17:12:29.527  1037  2760 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:29.527  1037  2760 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:29.528  1037  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118391
09-09 17:12:29.528  1037  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118391
09-09 17:12:29.528  1037  1099 D Tethering: InitialState.processMessage what=4
09-09 17:12:29.528  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118392  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:12:29.529  1037  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118392  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:12:29.530  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:12:29.531  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:29.531  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:29.542  4515  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-09 17:12:29.548  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:29.580  1037  1780 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6959 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:12:29.587  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:12:29.590   357   357 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 207us total 10.385ms
09-09 17:12:29.591  3872  3872 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:12:29.591  3872  3872 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:29.591  3872  3872 V BluetoothPbapReceiver: ***********state = 13
,09-09 17:12:29.593  3872  3872 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 17:12:29.594  3872  3872 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:29.594  3872  3872 V BluetoothPbapService: state: 13
09-09 17:12:29.595  3872  3872 V BluetoothPbapService: Pbap Service closeService in
09-09 17:12:29.596  1037  1099 D BluetoothManagerService: Message: 20
09-09 17:12:29.596  1037  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d5d327:true
09-09 17:12:29.596  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:29.596  3872  3872 V BluetoothPbapService: successfully stopped pbap service
09-09 17:12:29.597  3872  3872 V BluetoothPbapService: Pbap Service closeService out
09-09 17:12:29.597  3872  3872 V BluetoothPbapService: Pbap Service onDestroy
09-09 17:12:29.597  3872  3872 V BluetoothPbapService: Pbap Service closeService in
09-09 17:12:29.597  3872  3872 V BluetoothPbapService: Pbap Service closeService out
09-09 17:12:29.597  3872  3872 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 17:12:29.599   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 179us total 8.872ms
09-09 17:12:29.608   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 8.866ms
,09-09 17:12:29.612  1037  1099 D BluetoothManagerService: Message: 30
09-09 17:12:29.616  1037  1099 D BluetoothManagerService: Message: 30
09-09 17:12:29.618  6932  6932 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 17:12:29.619  6932  6932 D BluetoothMap: Create BluetoothMap proxy object
,09-09 17:12:29.620  1037  1099 D BluetoothManagerService: Message: 30
09-09 17:12:29.624  1037  1099 D BluetoothManagerService: Message: 30
09-09 17:12:29.625  6932  6932 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 17:12:29.626  6932  6932 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-09 17:12:29.631  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 17:12:29.635  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:12:29.635  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:29.637  1037  1053 I ActivityManager: Killing 6280:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-09 17:12:29.637  6717  6717 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 17:12:29.657  6134  6134 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-09 17:12:29.675  1037  1052 W libprocessgroup: failed to open /acct/uid_10014/pid_6280/cgroup.procs: No such file or directory
,09-09 17:12:29.675  6932  6932 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-09 17:12:29.678  1037  2054 I ActivityManager: Killing 6386:com.android.defcontainer/u0a4 (adj 15): empty #17
09-09 17:12:29.679  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-09 17:12:29.684  2704  2704 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 17:12:29.684  1037  2760 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 17:12:29.684  1037  2760 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 17:12:29.684  1037  2760 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 17:12:29.686  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-09 17:12:29.716  1037  1786 W libprocessgroup: failed to open /acct/uid_10004/pid_6386/cgroup.procs: No such file or directory
,09-09 17:12:29.725  6932  6932 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:29.741  6932  6932 D BluetoothInputDevice: Proxy object connected
,09-09 17:12:29.744  6932  6932 D HidProfile: Bluetooth service connected
,09-09 17:12:29.746  6932  6932 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:12:29.747  6932  6932 D PanProfile: Bluetooth service connected
09-09 17:12:29.749  6932  6932 D BluetoothMap: Proxy object connected
09-09 17:12:29.750  6932  6932 D MapProfile: Bluetooth service connected
09-09 17:12:29.751  6932  6932 D BluetoothMap: getConnectedDevices()
09-09 17:12:29.752  6932  6932 D BluetoothMap: Bluetooth is Not enabled
09-09 17:12:29.775  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:29.788  1978  1978 D WfdsService: Supplicant Connection state is changed : false
09-09 17:12:29.789  1978  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-09 17:12:29.789  1978  2354 D WfdsService: Set the WFDS Monitor: false
09-09 17:12:29.789  1978  2354 D WfdsMonitor: WFDS Monitor is stopped
09-09 17:12:29.789  1037  1540 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 17:12:29.789  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:29.789  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:29.789  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:12:29.793  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 17:12:29.793  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:29.794  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 17:12:29.794  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 17:12:29.795  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 17:12:29.797  2471  2471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:29.798  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:29.800  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:29.841  6932  6932 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:29.841  6932  6932 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:29.854  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:29.856  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 17:12:29.858  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 17:12:29.862  6932  6932 D BluetoothPermissionRequest: onReceive
09-09 17:12:29.865  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 17:12:29.875  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.,
09-09 17:12:29.875  1037  1786 I ActivityManager: Killing 6558:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-09 17:12:29.988  3872  3872 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-09 17:12:29.988  3872  3872 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-09 17:12:29.990  3872  3872 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 17:12:29.992  1037  2328 W libprocessgroup: failed to open /acct/uid_10008/pid_6558/cgroup.procs: No such file or directory
09-09 17:12:30.079  1037  1786 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6989 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 17:12:30.081  3872  3872 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:30.081  3872  3872 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 17:12:30.083  3872  3872 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:12:30.083  3872  3872 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:30.083  3872  3872 V BluetoothFtpService: Ftp Service closeService
09-09 17:12:30.084  3872  3872 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 17:12:30.090  3872  3872 V BluetoothFtpService: successfully stopped ftp service
09-09 17:12:30.090  3872  3872 V BluetoothFtpService: Ftp Service onDestroy
09-09 17:12:30.090  3872  3872 V BluetoothFtpService: Ftp Service closeService
09-09 17:12:30.098  3872  3872 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:30.098  3872  3872 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:30.098  3872  3872 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:30.098  3872  3872 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:30.098  3872  3872 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,09-09 17:12:30.098  3872  3872 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 17:12:30.100  3872  3872 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:30.101  3872  3872 V BluetoothSapService: state: 13
09-09 17:12:30.101  3872  3872 V BluetoothSapService: Stopping SAP server process
09-09 17:12:30.104  3872  3872 V BluetoothSapService: Sap Service closeSapService in
09-09 17:12:30.104  3872  3872 V BluetoothSapService: Close listen Socket : 
09-09 17:12:30.104  3872  3872 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:12:30.104  3872  3872 V BluetoothSapService: Close sapd  Socket : 
09-09 17:12:30.162  1037  2010 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:12:30.164  3872  3872 V BluetoothSapService: Sap Service closeSapService out
09-09 17:12:30.165  3872  3872 V BluetoothSapService: Sap Service onDestroy
09-09 17:12:30.165  3872  3872 V BluetoothSapService: Sap Service closeSapService in
09-09 17:12:30.165  3872  3872 V BluetoothSapService: Close listen Socket : 
09-09 17:12:30.165  3872  3872 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:12:30.165  3872  3872 V BluetoothSapService: Close sapd  Socket : 
09-09 17:12:30.170  3872  3872 V BluetoothSapService: Sap Service closeSapService out
09-09 17:12:30.192  6989  6989 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:12:30.222  6989  6989 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-09 17:12:30.247  7006  7006 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:12:30.264  1037  1053 I ActivityManager: Killing 6056:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-09 17:12:30.278  6989  6989 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-09 17:12:30.278  6989  6989 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 17:12:30.279  6989  6989 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 17:12:30.279  6989  6989 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 17:12:30.280  6989  6989 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 17:12:30.281  6989  6989 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-09 17:12:30.286  3872  4081 I bt_lpm  : LPM is already off!!!
09-09 17:12:30.286  3872  3974 D bt_hci_bdroid: cleanup
09-09 17:12:30.286  3872  4187 I bt_userial_mct: exiting userial_read_thread
09-09 17:12:30.286  3872  4187 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 17:12:30.286  3872  4079 W bt-btif : ag scb idx 1 not allocated
09-09 17:12:30.286  3872  4079 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 17:12:30.286  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:30.286  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:30.286  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:30.287  6989  6989 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:30.287  3872  3974 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:30.287  3872  4081 I bt_vendor: hw_epilog_process
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:30.287  3872  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:30.287  3872  4079 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:12:30.287  3872  3974 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 17:12:30.287  3872  3974 D bt_userial_mct: userial_close
09-09 17:12:30.287  3872  3974 E bt_userial_mct: pthread_join() FAILED result:3
09-09 17:12:30.288  3872  3974 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 17:12:30.320  1037  1718 W libprocessgroup: failed to open /acct/uid_10011/pid_6056/cgroup.procs: No such file or directory
,09-09 17:12:30.332  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:12:30.337  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:12:30.349  3872  3974 D bt_hci_bdroid: set_power 0
,09-09 17:12:30.349  3872  3974 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-09 17:12:30.349  3872  3974 I bt_vendor: bluetooth satus is on
09-09 17:12:30.349  3872  3974 I bt_vendor: bt-vendor : resetting BT status
09-09 17:12:30.349  3872  3974 I bt_vendor: Starting hciattach daemon
09-09 17:12:30.349  3872  3974 I bt_vendor: try to set false
09-09 17:12:30.350  3872  3974 I bt_vendor: Starting hciattach daemon
09-09 17:12:30.350  3872  3974 I bt_vendor: try to set false
09-09 17:12:30.351  3872  3974 I bt_vendor: cleanup
09-09 17:12:30.351  3872  4079 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 17:12:30.352  3872  3974 I GKI_LINUX: GKI_exit_task 0 done
09-09 17:12:30.352  3872  3974 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 17:12:30.354  3872  3966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 17:12:30.358  3872  3872 D HeadsetService: Received stop request...Stopping profile...
09-09 17:12:30.359  3872  3872 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:12:30.359  3872  3872 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:30.359  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d97a3d0
09-09 17:12:30.359  3872  3988 D HeadsetStateMachine: Exit Disconnected: -1
09-09 17:12:30.360  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:30.361  1882  1882 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:30.361  1882  1882 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:30.361  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:30.361  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-09 17:12:30.362  1882  1882 D BluetoothHeadset: Proxy object disconnected
,09-09 17:12:30.364  3872  3872 D A2dpService: Received stop request...Stopping profile...
09-09 17:12:30.364  3872  4045 D A2dpStateMachine: Exit Disconnected: -1
09-09 17:12:30.365  3872  3872 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 17:12:30.365  3872  3966 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 17:12:30.370  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:30.371  3872  3872 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 17:12:30.371  3872  3872 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:30.371  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d97a3d0
09-09 17:12:30.373  6989  6989 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 17:12:30.376  6989  6989 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 17:12:30.376  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:12:30.376  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:12:30.376  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:30.379  1037  1037 D BluetoothA2dp: Proxy object disconnected
09-09 17:12:30.379  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 17:12:30.380  3872  3872 D HidService: Received stop request...Stopping profile...
09-09 17:12:30.380  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d97a3d0
09-09 17:12:30.381  6932  6932 D BluetoothInputDevice: Proxy object disconnected
09-09 17:12:30.381  6932  6932 D HidProfile: Bluetooth service disconnected
09-09 17:12:30.381  3872  3872 D HealthService: Received stop request...Stopping profile...
09-09 17:12:30.382  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d97a3d0
09-09 17:12:30.386  3872  3872 D PanService: Received stop request...Stopping profile...
09-09 17:12:30.386  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:30.387  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d97a3d0
09-09 17:12:30.388  3872  3872 D HeadsetStateMachine: Unbinding service...
,09-09 17:12:30.389  3872  3872 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:12:30.389  3872  3872 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:12:30.389  3872  3872 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:12:30.389  3872  3872 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,09-09 17:12:30.389  3872  3872 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:12:30.389  3872  3872 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:30.389  3872  3872 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:12:30.389  3872  3872 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:12:30.390  3872  3872 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 17:12:30.390  3872  3872 D BtGatt.GattService: stop()
09-09 17:12:30.390  3872  3872 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 17:12:30.392  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d97a3d0
09-09 17:12:30.394  3872  3872 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:12:30.394  3872  3872 D BluetoothMapService: stop()
09-09 17:12:30.394  3872  3872 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 17:12:30.395  3872  3872 D BluetoothMapEmailAppObserver: removeReceiver()
,09-09 17:12:30.395  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d97a3d0
09-09 17:12:30.396  3872  3872 I BluetoothA2dpServiceJni: cleanupNative
09-09 17:12:30.397  3872  4048 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 17:12:30.397  3872  3872 I GKI_LINUX: GKI_exit_task 2 done
09-09 17:12:30.397  3872  3872 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 17:12:30.397  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:30.397  3872  3872 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:12:30.397  6932  6932 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 17:12:30.397  6932  6932 D PanProfile: Bluetooth service disconnected
09-09 17:12:30.397  3872  3872 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:12:30.398  6932  6932 D BluetoothMap: Proxy object disconnected
09-09 17:12:30.398  6932  6932 D MapProfile: Bluetooth service disconnected
09-09 17:12:30.398  3872  3872 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:12:30.398  3872  3872 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:12:30.398  3872  3872 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:12:30.398  3872  3872 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:12:30.399  3872  3872 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:12:30.400  3872  3872 V BluetoothMapService: Handler(): got msg=4
09-09 17:12:30.400  3872  3872 D BluetoothMapService: MAP Service closeService in
09-09 17:12:30.400  3872  3872 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:12:30.400  3872  3872 V BluetoothMapService: MAP Service closeService out
09-09 17:12:30.400  3872  3872 D BluetoothMapService: cleanup()
09-09 17:12:30.400  3872  3872 D BluetoothMapService: MAP Service closeService in
09-09 17:12:30.400  3872  3872 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:12:30.400  3872  3872 V BluetoothMapService: MAP Service closeService out
09-09 17:12:30.400  3872  3966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 17:12:30.401  3872  3966 D BluetoothAdapterProperties: Setting state to 10
09-09 17:12:30.401  3872  3966 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:12:30.401  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:30.401  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 17:12:30.401  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 17:12:30.402  3872  3966 I BluetoothAdapterState: Entering OffState
,09-09 17:12:30.403  6932  6947 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:12:30.406  1882  1898 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:30.407  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:30.407  1882  1897 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:30.413  6932  6947 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:12:30.413  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:30.414  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:30.415  1882  4446 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:12:30.416  6932  6948 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:12:30.417  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:12:30.418  6932  6947 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:12:30.419  1037  1099 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 17:12:30.419  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 17:12:30.421  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:30.423  1037  1099 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 17:12:30.423  1037  1099 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 17:12:30.423  1037  1099 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1d9b6d2f mBinding = false
09-09 17:12:30.424  1037  1099 D BluetoothManagerService: Sending unbind request.
09-09 17:12:30.426  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:30.427  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 17:12:30.438  3872  3974 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 17:12:30.438  3872  3872 I GKI_LINUX: GKI_exit_task 1 done
09-09 17:12:30.438  3872  3872 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 17:12:30.438  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:12:30.438  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:12:30.439  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:30.439  3872  3872 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 17:12:30.439  3872  3872 I art     : --- WEIRD: removing null entry 246
,09-09 17:12:30.439  3872  3872 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-09 17:12:30.440  3872  3872 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 17:12:30.441  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:30.441  1978  2179 D LGBluetoothAPIService: Message: 2
09-09 17:12:30.441  1978  2179 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@383fef23 mBinding = false
09-09 17:12:30.441  1978  2179 D LGBluetoothAPIService: Sending unbind request.
09-09 17:12:30.442  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:12:30.445  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:30.446  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:30.446  6932  6932 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:12:30.448  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 17:12:30.448  6932  6932 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 17:12:30.449  3872  3872 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 17:12:30.452  1606  1606 D BluetoothAdapter: 574249320: getState() :  mService = null. Returning STATE_OFF
09-09 17:12:30.452  1606  1606 D BluetoothAdapter: 574249320: getState() :  mService = null. Returning STATE_OFF
,09-09 17:12:30.455  3872  3872 I art     : System.exit called, status: 0
09-09 17:12:30.455  3872  3872 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 17:12:30.456  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:12:30.462  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:30.468  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:30.471  6932  6932 D DockEventReceiver: finishStartingService: stopping service
09-09 17:12:30.476  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:30.477  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:12:30.479  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:30.483  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 17:12:30.485   333   333 V AudioFlinger: 3872 died, releasing its sessions
09-09 17:12:30.485   333   333 V AudioFlinger:  pid 1882 @ 0
09-09 17:12:30.485   333   333 V AudioFlinger:  pid 3411 @ 1
09-09 17:12:30.485   333   333 V AudioFlinger:  pid 3411 @ 2
09-09 17:12:30.536  1037  1052 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7029 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-09 17:12:30.552  1037  2007 I ActivityManager: Process com.android.bluetooth (pid 3872) has died
,09-09 17:12:30.553  1037  2007 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-09 17:12:30.562  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:30.580  6932  6932 D BluetoothPermissionRequest: onReceive
,09-09 17:12:30.584  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 17:12:30.585  6932  6932 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 17:12:30.590  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:12:30.652  1037  1053 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7046 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 17:12:30.716  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:30.722  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:12:30.727  7046  7046 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-09 17:12:30.728  7046  7046 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:12:30.728  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:30.732  7046  7046 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 17:12:30.733  7046  7046 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 17:12:30.748  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:12:30.749  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:12:30.749  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-09 17:12:30.749  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:12:30.749  7029  7066 W FormManager: Network not available. Please check & try again.
09-09 17:12:30.751  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:12:30.752  7046  7046 D BluetoothAdapterApp: Loading JNI Library
09-09 17:12:30.761  7029  7067 V FormManager: Network unavailable.
,09-09 17:12:30.761  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:12:30.762  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 17:12:30.762  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:12:30.762  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:12:30.763  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:12:30.763  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:12:30.767  7029  7067 V FormManager: Network unavailable.
09-09 17:12:30.767  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:12:30.768  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:30.769  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:30.771  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:30.778  6959  6959 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 17:12:30.778  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:12:30.778  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:30.778  4344  7070 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:12:30.782  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:12:30.786  4344  7071 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:12:30.786  4344  7071 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:30.791  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:30.792  7029  7073 V FormManager: Network unavailable.
09-09 17:12:30.794  7046  7046 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@fa83f91 Instance Count = 1
,09-09 17:12:30.799  7029  7073 V FormManager: Network unavailable.
09-09 17:12:30.800  7029  7072 W FormManager: Network not available. Please check & try again.
,09-09 17:12:30.805  7046  7046 D BluetoothAdapterApp: onCreate
09-09 17:12:30.806  1037  1053 I ActivityManager: Killing 6078:com.android.contacts/u0a19 (adj 15): empty #17
,09-09 17:12:30.826  7046  7046 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 17:12:30.826  7046  7046 D ProfileConfigQcom: Adding HeadsetService
,09-09 17:12:30.826  7046  7046 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-09 17:12:30.826  7046  7046 D ProfileConfigQcom: Adding A2dpService
09-09 17:12:30.826  7046  7046 D ProfileConfigQcom: [BTUI] HidService is supported
09-09 17:12:30.827  7046  7046 D ProfileConfigQcom: Adding HidService
09-09 17:12:30.827  7046  7046 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 17:12:30.827  7046  7046 D ProfileConfigQcom: Adding HealthService
09-09 17:12:30.827  7046  7046 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 17:12:30.828  7046  7046 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 17:12:30.828  7046  7046 D ProfileConfigQcom: Adding PanService
09-09 17:12:30.829  7046  7046 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 17:12:30.829  7046  7046 D ProfileConfigQcom: Adding GattService
09-09 17:12:30.829  7046  7046 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 17:12:30.829  7046  7046 D ProfileConfigQcom: Adding BluetoothMapService
09-09 17:12:30.830  7046  7046 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 17:12:30.831  7046  7046 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-09 17:12:30.836  1037  1780 W libprocessgroup: failed to open /acct/uid_10019/pid_6078/cgroup.procs: No such file or directory
09-09 17:12:30.838  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-09 17:12:30.845  7046  7046 V LGMDMManagerInternal: Create singleton instance
09-09 17:12:30.848  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 17:12:30.849  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 17:12:30.850  6989  6989 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-09 17:12:30.889  6989  6989 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:30.889  6989  6989 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:30.898  6989  6989 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 17:12:30.899  6989  6989 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-09 17:12:30.899  6989  6989 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-09 17:12:30.899  6989  6989 V SoundPool: doLoad: loading sample sampleID=1
09-09 17:12:30.900  6989  7077 V SoundPool: Start decode
09-09 17:12:30.900  6989  7077 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-09 17:12:30.900  6989  6989 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 17:12:30.900   333  1388 V MediaPlayerService: decode(23, 10857164, 17813)
09-09 17:12:30.900   333  1388 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-09 17:12:30.900   333  1388 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-09 17:12:30.900   333  1388 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 17:12:30.900   333  1388 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 17:12:30.901   333  1388 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 17:12:30.901   333  1388 V MediaPlayerService: player type = 3
09-09 17:12:30.901   333  1388 V AwesomePlayer: AwesomePlayer create()
09-09 17:12:30.903   333  1388 V AwesomePlayer: reset_l() 
09-09 17:12:30.903   333  1388 V AwesomePlayer: cancelPlayerEvents
09-09 17:12:30.903   333  1388 V AwesomePlayer: setAudioSink() 
09-09 17:12:30.903   333  1388 V AwesomePlayer: reset_l() 
09-09 17:12:30.903   333  1388 V AudioCache: notify(0xb1432340, 8, 0, 0)
09-09 17:12:30.904   333  1388 V AudioCache: ignored
09-09 17:12:30.904   333  1388 V AwesomePlayer: cancelPlayerEvents
,09-09 17:12:30.904  6831  6831 D UEI.SmartControl: QS Service created
09-09 17:12:30.905  6989  6989 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-09 17:12:30.905   333  1388 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 17:12:30.905   333  1388 V AwesomePlayer: setDataSource_l dataSource
09-09 17:12:30.905   333  1388 V LGParserOSAL: SniffLGParser start
09-09 17:12:30.905   333  1388 V LGParserOSAL: MainType:5, SubType=0
09-09 17:12:30.905   333  1388 V LGParserOSAL: #### check Mime : application/ogg
09-09 17:12:30.905   333  1388 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 17:12:30.905   333  1388 E MediaExtractor: Use LGExtractor :application/ogg 
09-09 17:12:30.907  6989  6989 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:12:30.907  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 17:12:30.916  6831  6831 I UEI.SmartControl: Service initServices...
09-09 17:12:30.917  6831  6831 D UEI.SmartControl: QS start get config
09-09 17:12:30.919  6989  6989 V LGMDMManager: Create singleton instance
09-09 17:12:30.959  7046  7046 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:30.964  7046  7046 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:30.964  7046  7046 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:30.965  7046  7046 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:30.965  7046  7046 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:30.966  7046  7046 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-09 17:12:30.971   333  1388 V LGParserOSAL: supported mime: application/ogg
09-09 17:12:30.971   333  1388 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 17:12:30.971   333  1388 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 17:12:30.971   333  1388 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 17:12:30.971   333  1388 V AwesomePlayer: AudioTrack Setting
09-09 17:12:30.971   333  1388 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 17:12:30.972   333  1388 V AwesomePlayer: setAudioSource() 
09-09 17:12:30.972   333  1388 V MediaPlayerService: prepare
09-09 17:12:30.972   333  1388 V AwesomePlayer: prepareAsync_l() 
09-09 17:12:30.972   333  1388 V MediaPlayerService: wait for prepare
09-09 17:12:30.972   333  7078 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 17:12:30.972   333  7078 V AwesomePlayer: initAudioDecoder() 
09-09 17:12:30.972   333  7078 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 17:12:30.972   333  7078 V AudioSystem: isOffloadSupported()
09-09 17:12:30.972   333  7078 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 17:12:30.973   333  7078 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 17:12:30.973   333  7078 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 17:12:30.973   333  7078 V AwesomePlayer: getUseOffload() = 0 
09-09 17:12:30.973   333  7078 V OMXCodec: OMXCodec::Create
09-09 17:12:30.973   333  7078 V OMXCodec: findMatchingCodecs()
09-09 17:12:30.973   333  7078 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 17:12:30.973   333  7078 V OMXCodec: matchingCodecs.size()=1
09-09 17:12:30.973   333  7078 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-09 17:12:30.975  7006  7006 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-09 17:12:30.975   333  7078 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 17:12:30.975   333  7078 V LGCodecAdapter: LG Codec Adapter start
,09-09 17:12:30.975   333  7078 V OMXCodec: OMXCodec Createtor
09-09 17:12:30.975   333  7078 V OMXCodec: setComponentRole
09-09 17:12:30.975   333  7078 V OMXCodec: configureCodec protected=0
09-09 17:12:30.975   333  7078 V LGCodecAdapter: called getLGCodecSpecificData
09-09 17:12:30.975   333  7078 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 17:12:30.976   333  7078 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 17:12:30.976   333  7078 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 17:12:30.976   333  7078 V LGCodecOSAL: Not support LGCodec
09-09 17:12:30.976   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 17:12:30.976   333  7078 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 17:12:30.976   333  7078 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 17:12:30.976   333  7078 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 17:12:30.976   333  7078 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 17:12:30.976   333  7078 V AudioSystem: isOffloadSupported()
09-09 17:12:30.976   333  7078 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 17:12:30.977   333  7078 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 17:12:30.977   333  7078 V OMXCodec: init()
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-09 17:12:30.977   333  7078 V OMXCodec: allocateBuffers
09-09 17:12:30.977   333  7078 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-09 17:12:30.977   333  7078 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 17:12:30.977   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 17:12:30.978   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
09-09 17:12:30.978   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
09-09 17:12:30.978   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-09 17:12:30.978   333  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-09 17:12:30.978   333  7078 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 17:12:30.978   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 17:12:30.978   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 17:12:30.978   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 17:12:30.978   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 17:12:30.978   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 17:12:30.978   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 17:12:30.978   333  7078 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 17:12:30.978   333  7078 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 17:12:30.978   ,333  7078 V AudioCache: notify(0xb1432340, 5, 0, 0)
09-09 17:12:30.978   333  7078 V AudioCache: ignored
09-09 17:12:30.978   333  7078 V AudioCache: notify(0xb1432340, 1, 0, 0)
09-09 17:12:30.978   333  7078 V AudioCache: prepared
09-09 17:12:30.978   333  1388 V AudioCache: wait - success
09-09 17:12:30.978   333  1388 V MediaPlayerService: start
09-09 17:12:30.978   333  1388 V AwesomePlayer: play_l() 
09-09 17:12:30.978   333  1388 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 17:12:30.978   333  1388 V AwesomePlayer: createAudioPlayer_l
09-09 17:12:30.978   333  1388 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 17:12:30.978   333  1388 V AwesomePlayer: startAudioPlayer_l() 
09-09 17:12:30.978   333  1388 D AudioPlayer: start of Playback, useOffload 0
09-09 17:12:30.979   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 17:12:30.979   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
09-09 17:12:30.981   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 17:12:30.982   333  7081 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 17:12:30.982   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 17:12:30.983   333  1388 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 17:12:30.984   333  1388 V AudioCache: notify(0xb1432340, 6, 0, 0)
09-09 17:12:30.984   333  1388 V AudioCache:, ignored
09-09 17:12:30.984   333  1388 V MediaPlayerService: wait for playback complete
09-09 17:12:30.984   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.984   333  7082 V AudioCache: memcpy(0xac300000, 0xb16f5000, 4096)
09-09 17:12:30.986   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.986   333  7082 V AudioCache: memcpy(0xac301000, 0xb16f5000, 4096)
09-09 17:12:30.986   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.986   333  7082 V AudioCache: memcpy(0xac302000, 0xb16f5000, 4096)
09-09 17:12:30.986   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.986   333  7082 V AudioCache: memcpy(0xac303000, 0xb16f5000, 4096)
09-09 17:12:30.987   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.987   333  7082 V AudioCache: memcpy(0xac304000, 0xb16f5000, 4096)
09-09 17:12:30.987   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.987   333  7082 V AudioCache: memcpy(0xac305000, 0xb16f5000, 4096)
09-09 17:12:30.988   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.988   333  7082 V AudioCache: memcpy(0xac306000, 0xb16f5000, 4096)
09-09 17:12:30.988   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.988   333  7082 V AudioCache: memcpy(0xac307000, 0xb16f5000, 4096)
09-09 17:12:30.989  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 17:12:30.989   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.989   333  7082 V AudioCache: memcpy(0xac308000, 0xb16f5000, 4096)
09-09 17:12:30.989  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-09 17:12:30.990   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.990   333  7082 V AudioCache: memcpy(0xac309000, 0xb16f5000, 4096)
09-09 17:12:30.990   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.990   333  7082 V AudioCache: memcpy(0xac30a000, 0xb16f5000, 4096)
09-09 17:12:30.991   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.991   333  7082 V AudioCache: memcpy(0xac30b000, 0xb16f5000, 4096)
09-09 17:12:30.991  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5401
09-09 17:12:30.992   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.992   333  7082 V AudioCache: memcpy(0xac30c000, 0xb16f5000, 4096)
09-09 17:12:30.992   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.992   333  7082 V AudioCache: memcpy(0xac30d000, 0xb16f5000, 4096)
09-09 17:12:30.993   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.993   333  7082 V AudioCache: memcpy(0xac30e000, 0xb16f5000, 4096)
09-09 17:12:30.993   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.993   333  7082 V AudioCache: memcpy(0xac30f000, 0xb16f5000, 4096)
09-09 17:12:30.994   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.994   333  7082 V AudioCache: memcpy(0xac310000, 0xb16f5000, 4096)
09-09 17:12:30.995   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.995   333  7082 V AudioCache: memcpy(0xac311000, 0xb16f5000, 4096)
09-09 17:12:30.995   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.995   333  7082 V AudioCache: memcpy(0xac312000, 0xb16f5000, 4096)
09-09 17:12:30.996   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.996   333  7082 V AudioCache: memcpy(0xac313000, 0xb16f5000, 4096)
09-09 17:12:30.997   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.997   333  7082 V AudioCache: memcpy(0xac314000, 0xb16f5000, 4096)
09-09 17:12:30.998   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.998   333  7082 V AudioCache: memcpy(0xac315000, 0xb16f5000, 4096)
09-09 17:12:30.999   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:30.999   333  7082 V AudioCache: memcpy(0xac316000, 0xb16f5000, 4096)
09-09 17:12:31.000   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.000   333  7082 V AudioCache: memcpy(0xac317000, 0xb16f5000, 4096)
09-09 17:12:31.000   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.000   333  7082 V AudioCache: memcpy(0xac318000, 0xb16f5000, 4096)
09-09 17:12:31.001   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.001   333  7082 V AudioCache: memcpy(0xac319000, 0xb16f5000, 4096)
09-09 17:12:31.001   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.002   333  7082 V AudioCache: memcpy(0xac31a000, 0xb16f5000, 4096)
09-09 17:12:31.002   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.002   333  7082 V AudioCache: memcpy(0xac31b000, 0xb16f5000, 4096)
09-09 17:12:31.003   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.003   333  7082 V AudioCache: memcpy(0xac31c000, 0xb16f5000, 4096)
09-09 17:12:31.003   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.003   333  7082 V AudioCache: memcpy(0xac31d000, 0xb16f5000, 4096)
09-09 17:12:31.003   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.003   333  7082 V AudioCache: memcpy(0xac31e000, 0xb16f5000, 4096)
09-09 17:12:31.004   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.004   333  7082 V AudioCache: memcpy(0xac31f000, 0xb16f5000, 4096)
09-09 17:12:31.004   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.004   333  7082 V AudioCache: memcpy(0xac320000, 0xb16f5000, 4096)
09-09 17:12:31.005   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.005   333  7082 V AudioCache: memcpy(0xac321000, 0xb16f5000, 4096)
09-09 17:12:31.005   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.005   333  7082 V AudioCache: memcpy(0xac322000, 0xb16f5000, 4096)
09-09 17:12:31.005   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.005   333  7082 V AudioCache: memcpy(0xac323000, 0xb16f5000, 4096)
09-09 17:12:31.006   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.006   333  7082 V AudioCache: memcpy(0xac324000, 0xb16f5000, 4096)
09-09 17:12:31.006   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.006   333  7082 V AudioCache: memcpy(0xac325000, 0xb16f5000, 4096)
09-09 17:12:31.007   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.007   333  7082 V AudioCache: memcpy(0xac326000, 0xb16f5000, 4096)
09-09 17:12:31.007   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.007   333  7082 V AudioCache: memcpy(0xac327000, 0xb16f5000, 4096)
09-09 17:12:31.008   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.008   333  7082 V AudioCache: memcpy(0xac328000, 0xb16f5000, 4096)
09-09 17:12:31.008   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.008   333  7082 V AudioCache: memcpy(0xac329000, 0xb16f5000, 4096)
09-09 17:12:31.009   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.009   333  7082 V AudioCache: memcpy(0xac32a000, 0xb16f5000, 4096)
09-09 17:12:31.009   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.009   333  7082 V AudioCache: memcpy(0xac32b000, 0xb16f5000, 4096)
09-09 17:12:31.010   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.010   333  7082 V AudioCache: memcpy(0xac32c000, 0xb16f5000, 4096)
09-09 17:12:31.010   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.010   333  7082 V AudioCache: memcpy(0xac32d000, 0xb16f5000, 4096)
09-09 17:12:31.011   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.011   333  7082 V AudioCache: memcpy(0xac32e000, 0xb16f5000, 4096)
09-09 17:12:31.011   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.011   333  7082 V AudioCache: memcpy(0xac32f000, 0xb16f5000, 4096)
09-09 17:12:31.012   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.012   333  7082 V AudioCache: memcpy(0xac330000, 0xb16f5000, 4096)
09-09 17:12:31.012   333  7082 V AudioCache: write(0xb16f5000, 4096)
09-09 17:12:31.012   333  7082 V AudioCache: memcpy(0xac331000, 0xb16f5000, 4096)
09-09 17:12:31.013   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 17:12:31.013   333  7082 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 17:12:31.013   333  7082 V AwesomePlayer: postAudioEOS() 
09-09 17:12:31.013   333  7082 V AudioCache: write(0xb16f5000, 280)
09-09 17:12:31.013   333  7082 V AudioCache: memcpy(0xac332000, 0xb16f5000, 280)
09-09 17:12:31.014   333  7078 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 17:12:31.014   333  7078 V AwesomePlayer: onStreamDone
09-09 17:12:31.014   333  7078 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 17:12:31.014   333  7078 V AudioCache: notify(0xb1432340, 2, 0, 0)
09-09 17:12:31.014   333  7078 V AudioCache: playback complete
09-09 17:12:31.014   333  7078 V AwesomePlayer: pause_l() 
09-09 17:12:31.015   333  7078 V AudioCache: notify(0xb1432340, 7, 0, 0)
09-09 17:12:31.015   333  7078 V AudioCache: ignored
09-09 17:12:31.015   333  7078 V AwesomePlayer: cancelPlayerEvents
09-09 17:12:31.015   333  1388 V AudioCache: wait - success
09-09 17:12:31.015   333  1388 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 17:12:31.015   333  7078 D AudioPlayer: Pause Playback at 1068125
09-09 17:12:31.015   333  1388 V AwesomePlayer: reset_l() 
09-09 17:12:31.015   333  1388 V AudioCache: notify(0xb1432340, 8, 0, 0)
09-09 17:12:31.015   333  1388 V AudioCache: ignored
09-09 17:12:31.015   333  1388 V AwesomePlayer: cancelPlayerEvents
09-09 17:12:31.015   333  1388 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 17:12:31.015   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 17:12:31.015   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-09 17:12:31.015   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 17:12:31.015   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 17:12:31.015   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 17:12:31.015   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 17:12:31.015   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 17:12:31.015   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-09 17:12:31.015   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:12:31.016   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 17:12:31.016   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,09-09 17:12:31.016   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,09-09 17:12:31.017   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 17:12:31.017   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 17:12:31.017   333  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 17:12:31.017   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 17:12:31.017   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 17:12:31.017   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 17:12:31.018   333  1388 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-09 17:12:31.018   333  1388 D AudioPlayer: AudioPlayer releasing audio source
09-09 17:12:31.018   333  1388 D AudioPlayer: AudioPlayer done releasing audio source
09-09 17:12:31.019   333  1388 V AwesomePlayer: reset_l() 
09-09 17:12:31.019   333  1388 V AwesomePlayer: cancelPlayerEvents
09-09 17:12:31.019   333  1388 V AwesomePlayer: ~AwesomePlayer call
09-09 17:12:31.019   333  1388 V AwesomePlayer: reset_l() 
09-09 17:12:31.019   333  1388 V AwesomePlayer: cancelPlayerEvents
09-09 17:12:31.019  6989  7077 V SoundPool: close(31)
09-09 17:12:31.019  6989  7077 V SoundPool: pointer = 0xa0021000, size = 205080, sampleRate = 48000, numChannels = 2
09-09 17:12:31.179  6831  6831 I UEI.SmartControl: Supports setup maps: true
,09-09 17:12:31.181  6831  6831 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 17:12:31.181  6831  6831 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-09 17:12:31.181  6831  6831 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 17:12:31.181  6831  6831 I UEI.SmartControl: ### init IR Blaster...
09-09 17:12:31.184  6831  6831 D serial_port: Configuring serial port
09-09 17:12:31.185  6831  6831 E UEI.SmartControl: UEIBLaster setting for 616
09-09 17:12:31.185  6831  6831 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 17:12:31.185  6831  6831 I UEI.SmartControl: configuring settings for MAXQ616
09-09 17:12:31.185  6831  6831 I UEI.SmartControl: Get version...
09-09 17:12:31.204  6831  7083 D UEI.SmartControl: serial port data available: 21
,09-09 17:12:31.230  6831  6831 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 17:12:31.230  6831  6831 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 17:12:31.230  6831  6831 I UEI.SmartControl: QS saving settings...
09-09 17:12:31.232  6831  6831 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 17:12:31.248  6831  7083 D UEI.SmartControl: serial port data available: 4
,09-09 17:12:31.281  6831  7089 I UEI.SmartControl: Device manager: loading config....
,09-09 17:12:31.282  6831  7089 D UEI.SmartControl: ----------- loading internal config...
09-09 17:12:31.283  6831  6831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 17:12:31.287  6831  6831 E UEI.SmartControl: Services init done
09-09 17:12:31.288  6831  6831 D UEI.SmartControl: QS Service init finished
09-09 17:12:31.290  6831  6831 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 17:12:31.290  6831  6831 D UEI.SmartControl: QS Service version code: 201091
09-09 17:12:31.291  6831  6831 D UEI.SmartControl: Service requested: Control
09-09 17:12:31.297  6831  7089 E UEI.SmartControl: Loading SETTINGS...
,09-09 17:12:31.298  6831  6831 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 17:12:31.302  6831  6831 D UEI.SmartControl: Internal service binding...
09-09 17:12:31.303  6989  6989 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 17:12:31.304  6831  6846 I UEI.SmartControl: ------ IControl API: 11
09-09 17:12:31.304  6831  6846 D UEI.SmartControl: File observer start...
09-09 17:12:31.305  6831  6846 E UEI.SmartControl: IR Port is disabled: false
09-09 17:12:31.305  6831  6846 D UEI.SmartControl: Starting file observer...
09-09 17:12:31.305  6831  6846 I UEI.SmartControl: Registering callback...
09-09 17:12:31.306  6831  6847 I UEI.SmartControl: ------ IControl API: 19
09-09 17:12:31.307  6831  6847 I UEI.SmartControl: Registering Services Ready callback...
09-09 17:12:31.310  6831  7089 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 17:12:31.338  6831  7088 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 17:12:31.340  6989  7004 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 17:12:31.341  6831  7088 D UEI.SmartControl: -----service ready thread exits
09-09 17:12:31.342  6989  7075 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 17:12:31.343  6989  7075 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,09-09 17:12:31.345  6989  6989 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,09-09 17:12:31.346  6989  6989 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 17:12:31.347  6831  6846 I UEI.SmartControl: ------ IControl API: 8
09-09 17:12:31.351  6989  6989 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 17:12:31.352  6989  6989 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 17:12:31.353  6989  6989 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 17:12:31.354  6989  6989 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 17:12:31.357  6989  6989 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 17:12:31.358  6989  6989 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,09-09 17:12:31.361  6989  6989 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 17:12:31.376  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 17:12:31.377  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-09 17:12:31.379  6989  6989 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:12:31.379  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 17:12:31.380  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 17:12:31.381  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 17:12:31.382  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-09 17:12:31.383  6989  6989 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473433951382]
09-09 17:12:31.384  6989  6989 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-09 17:12:31.389  1037  2081 I ActivityManager: Killing 6105:com.android.gallery3d/u0a27 (adj 15): empty #17
09-09 17:12:31.407  6989  7094 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-09 17:12:31.445  1037  2081 I ActivityManager: Killing 6608:com.lge.email/u0a23 (adj 15): empty #18
,09-09 17:12:31.483  1037  2010 W libprocessgroup: failed to open /acct/uid_10023/pid_6608/cgroup.procs: No such file or directory
,09-09 17:12:31.487  1037  1987 W libprocessgroup: failed to open /acct/uid_10027/pid_6105/cgroup.procs: No such file or directory
09-09 17:12:31.487  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-09 17:12:31.490  6989  6989 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:12:31.491  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 17:12:31.492  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 17:12:31.493  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 17:12:31.493  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 17:12:31.494  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 17:12:31.509  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 17:12:32.265  1037  2018 D WifiServiceImplEx: setWifiEnabled: true pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:12:32.267  1037  2018 D WifiService: setWifiEnabled: true pid=6717, uid=10118
09-09 17:12:32.267  1037  2018 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:12:32.296  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 17:12:32.297  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-09 17:12:32.297  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-09 17:12:32.298  1037  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 17:12:32.298  1037  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 17:12:32.301  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 17:12:32.301  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 17:12:32.301  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 17:12:32.301  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 17:12:32.301  1037  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 17:12:32.301  1037  1540 E WifiHW  : unknown target_country: EU , set to default
09-09 17:12:32.301  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 17:12:32.301  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 17:12:32.301  1037  1540 I WifiUtil: gEnableBmps=1
09-09 17:12:32.423  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:32.437  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-09 17:12:32.445  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:32.454  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:32.457  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:32.461  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-09 17:12:32.474  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:32.478  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:32.478  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:32.480  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:12:32.488  6523  6547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 17:12:32.492  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 17:12:32.509  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 17:12:32.527  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:32.569  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:32.606  1037  2095 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7113 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 17:12:32.611  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:32.611  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 17:12:32.692  7113  7113 I AppUp4:AppBoxCP: onCreate
,09-09 17:12:32.693  7113  7113 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 17:12:32.704  7113  7113 I AppUp4:DB:  setFingerPrint start
09-09 17:12:32.704  7113  7113 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-09 17:12:32.713  7113  7113 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-09 17:12:32.713  7113  7113 I AppUp4:DB:  SDK version = 21
09-09 17:12:32.713  7113  7113 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 17:12:32.716  7113  7113 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-09 17:12:32.717  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-09 17:12:32.717  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:32.720  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:12:32.720  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 17:12:32.727  7113  7113 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:12:32.771  7113  7113 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:32.772  7113  7113 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:32.781  7113  7113 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@dfb3793
09-09 17:12:32.781  7113  7113 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-09 17:12:32.782  7113  7113 D AppUp4:CustFacade: isPhone : true
09-09 17:12:32.782  7113  7113 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:12:32.783  7113  7113 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 17:12:32.783  7113  7113 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 17:12:32.784  7113  7132 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-09 17:12:32.784  7113  7132 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 17:12:32.784  7113  7132 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-09 17:12:32.787  1037  1718 I ActivityManager: Killing 6647:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-09 17:12:32.851  1037  1987 W libprocessgroup: failed to open /acct/uid_10061/pid_6647/cgroup.procs: No such file or directory
,09-09 17:12:32.852  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:32.852  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:32.855  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:32.861  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:32.865  4344  7144 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:12:32.868  4344  7145 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:32.868  4344  7145 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:32.940  1037  2010 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7146 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 17:12:33.013  1037  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 17:12:33.019   328   897 D SoftapController: Softap fwReload - Ok
09-09 17:12:33.020  1037  1540 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (713ms)
09-09 17:12:33.021  1037  1099 D Tethering: InitialState.processMessage what=4
09-09 17:12:33.022   328   897 D CommandListener: Setting iface cfg
09-09 17:12:33.022   328   897 D CommandListener: Trying to bring down wlan0
09-09 17:12:33.024  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:12:33.024   328   897 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:12:33.028  1037  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 17:12:33.031  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:33.031  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:33.031  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 17:12:33.029  7164  7164 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:33.029  7164  7164 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:33.045  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:33.049  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-09 17:12:33.053  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:33.056  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:33.062  1037  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 17:12:33.062  1037  1540 D WifiMonitor: connecting to supplicant
09-09 17:12:33.064  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 17:12:33.065  7164  7164 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:12:33.099  7146  7146 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:33.100  7146  7146 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:12:33.100  7164  7164 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 17:12:33.101  7164  7164 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 17:12:33.101  7146  7146 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 17:12:33.102  7146  7146 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 17:12:33.195  7146  7146 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 17:12:33.210  7146  7146 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-09 17:12:33.210  7164  7164 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:12:33.272  7146  7146 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 17:12:33.310  7146  7146 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 17:12:33.310  7146  7146 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:33.325  7164  7164 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 17:12:33.337  7164  7164 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-09 17:12:33.338  7164  7164 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 17:12:33.339  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-09 17:12:33.340  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 17:12:33.340  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,09-09 17:12:33.341  1037  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 17:12:33.341  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:33.342  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:33.342  1037  7173 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 17:12:33.342  1037  7173 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 17:12:33.342  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 17:12:33.342  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:33.342  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 17:12:33.343  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 17:12:33.343  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 17:12:33.343  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:33.343  1037  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 17:12:33.343  1037  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 17:12:33.344  1037  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 17:12:33.344  1037  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 17:12:33.345  1037  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 17:12:33.345  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:33.345  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:33.345  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 17:12:33.346  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:33.347  1037  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 17:12:33.347  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:33.348  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:33.348  1037  1540 D WifiNative-wlan0: SET update_config 1: returned true
09-09 17:12:33.348  1037  1540 D WifiConfigStore: Loading config and enabling all networks 
09-09 17:12:33.348  1037  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 17:12:33.350  1037  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 17:12:33.352  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:33.352  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:33.354  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:33.357  1978  1978 D WfdService: Waiting for WifiP2p enabling
,09-09 17:12:33.361  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:33.361  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:33.361  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:33.361  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:33.362  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 17:12:33.363  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 17:12:33.364  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:33.364  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:33.364  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:33.364  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:33.369  1037  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-09 17:12:33.378  1037  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 17:12:33.379  1037  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 17:12:33.379  1037  1540 D WifiStateMachine: enableVerboseLogging : level 2
09-09 17:12:33.379  1037  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 17:12:33.380  1037  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 17:12:33.380  1037  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 17:12:33.380  1037  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 17:12:33.380  1037  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 17:12:33.380  1037  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 17:12:33.381  1037  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 17:12:33.381  1037  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 17:12:33.381  1037  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 17:12:33.381  1037  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 17:12:33.381  1037  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 17:12:33.381  1037  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 17:12:33.382  1037  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 17:12:33.382  1037  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-09 17:12:33.382  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:12:33.383  1037  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 17:12:33.383  1978  1978 D WfdsService: Supplicant Connection state is changed : true
09-09 17:12:33.383  1978  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 17:12:33.383  1978  2354 D WfdsService: Set the WFDS Monitor: true
09-09 17:12:33.383  1978  2354 D WfdsMonitor: WfdsMonitorThread create
09-09 17:12:33.383  1978  2354 D WfdsMonitor: WFDS Monitor is created and started
09-09 17:12:33.383  1978  2354 D WfdsService: WiFi: Supplicant connection re-established
09-09 17:12:33.384  1037  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 17:12:33.384  1037  1540 D WifiNative-HAL: Setting external_sim to 1
09-09 17:12:33.384  1037  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 17:12:33.384  1978  7176 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 17:12:33.384  1037  1540 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 17:12:33.384  1037  1540 I WifiNative-HAL: startHal
09-09 17:12:33.384  1037  1540 D wifi    : setting scan oui 0xaf677b60
09-09 17:12:33.385  1978  7176 E CtrlSupplicant: Succeed to open control connection
09-09 17:12:33.385  1978  7176 E CtrlSupplicant: Succeed to open monitor connection
09-09 17:12:33.385  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:12:33.385  1037  1540 I WifiNative-HAL: startHal
09-09 17:12:33.385  1037  1540 D wifi    : setting scan oui 0xaf677b60
09-09 17:12:33.385  1978  7176 D WfdsMonitor: Supplicant connection established
09-09 17:12:33.385  1037  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 17:12:33.385  1978  2354 D WfdsService: Connected to the supplicant for wfds
09-09 17:12:33.385  1037  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 17:12:33.385  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 17:12:33.385  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 17:12:33.386  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 17:12:33.386  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:12:33.386  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:12:33.386  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 17:12:33.386  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 17:12:33.386  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 17:12:33.386  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 17:12:33.386  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:12:33.386  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 17:12:33.387  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:12:33.387  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:12:33.387  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:12:33.387  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 17:12:33.387  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 17:12:33.387  7164  7164 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 17:12:33.387  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 17:12:33.387  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:12:33.388  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 17:12:33.388  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:12:33.388  1037  1540 E WifiNative: : [122,251,608 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 17:12:33.388  1037  1540 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 17:12:33.389  1037  1540 D W,ifiNative-wlan0: RECONNECT: returned true
09-09 17:12:33.389  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-09 17:12:33.389  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:12:33.389  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 17:12:33.389  1037  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 17:12:33.390  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:33.390  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:33.390  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.391   328   897 D CommandListener: Setting iface cfg
09-09 17:12:33.391   328   897 D CommandListener: Trying to bring up p2p0
09-09 17:12:33.392  1037  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 17:12:33.392  1037  1539 D LGWifiP2pService: P2pEnablingState
09-09 17:12:33.392  1037  1539 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.392  1037  1539 D LGWifiP2pService: P2p socket connection successful
09-09 17:12:33.392  1037  1539 D LGWifiP2pService: P2pEnabledState
09-09 17:12:33.393  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 17:12:33.393  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-09 17:12:33.393  1037  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.393  1037  1558 I WifiNative-HAL: startHal
09-09 17:12:33.393  1037  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf677b60
09-09 17:12:33.393  1037  1558 D wifi    : failed to get capabilities : -3
09-09 17:12:33.393  1037  1558 E WifiScanningService: could not get scan capabilities
,09-09 17:12:33.393  1037  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.393  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 17:12:33.394  1037  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 17:12:33.394  1037  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 17:12:33.394  1037  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 17:12:33.394  1037  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 17:12:33.395  1037  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 17:12:33.395  1037  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 17:12:33.395  1037  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 17:12:33.395  7164  7164 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 17:12:33.395  1037  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 17:12:33.396  1037  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 17:12:33.396  1037  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 17:12:33.396  1037  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 17:12:33.396  7164  7164 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 17:12:33.396  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 17:12:33.396  1978  1978 D WfdsService: WifiP2pState is changed : true
09-09 17:12:33.396  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 17:12:33.397  1978  2354 D WfdsService: Receive the WFDS_ENABLE Method
09-09 17:12:33.397  1978  2354 D WfdsService: Set the WFDS Monitor: true
09-09 17:12:33.397  1978  2354 D WfdsService: Connected to the supplicant for wfds
09-09 17:12:33.397  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 17:12:33.397  1978  2354 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 17:12:33.397  7164  7164 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 17:12:33.397  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 17:12:33.397  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 17:12:33.397  1978  2354 D WfdsService: selectPreferredScanChannel [36]
09-09 17:12:33.397  1978  2354 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 17:12:33.398  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-09 17:12:33.399  7164  7164 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.399  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:12:33.399  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.399  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.399  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.399  7164  7164 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:12:33.399  7164  7164 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.400  1978  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.400  1037  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 17:12:33.400  7164  7164 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.400  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:12:33.400  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:12:33.401  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:12:33.401  1978  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.401  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 17:12:33.401  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 17:12:33.401  7164  7164 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:33.401  1037  1539 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 17:12:33.402  1037  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 17:12:33.402  1037  7173 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.402  1037  7173 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.402  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.402  1037  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 17:12:33.402  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.402  1037  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 17:12:33.402  1037  7173 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.402  1037  7173 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.402  1037  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 17:12:33.402  1037  1540 D WifiNative-wlan0: doBoolean: SCAN
09-09 17:12:33.402  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.402  1037  1540 D WifiNative-wlan0: SCAN: returned false
09-09 17:12:33.403  1978  1978 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 17:12:33.403  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122266  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:12:33.403  1978  1978 D WfdsService: isConnected: false
09-09 17:12:33.404  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122267  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:12:33.404  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:33.404  1037  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09,-09 17:12:33.404  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:33.405  1037  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:33.405  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:33.405  1037  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:33.405  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:33.405  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 17:12:33.406  1037  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:33.406  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:33.406  1037  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:33.406  1037  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 17:12:33.402  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.406  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 17:12:33.406  1037  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 17:12:33.406  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:33.407  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:33.407  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:33.407  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:33.407  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 17:12:33.407  1037  1539 D WifiNative-p2p0: SET device_name G3: returned true
09-09 17:12:33.407  1037  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 17:12:33.408  1037  1539 D LGWifiP2pService: before postfix = G3
09-09 17:12:33.408  1037  1539 D WifiServerServiceExt: postfix byte check : 2
09-09 17:12:33.408  1037  1539 D LGWifiP2pService: after postfix = G3
09-09 17:12:33.408  1037  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-09 17:12:33.408  1037  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 17:12:33.408  1037  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 17:12:33.408  1037  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 17:12:33.408  1037  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 17:12:33.409  1037  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 17:12:33.409  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 17:12:33.409  1037  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 17:12:33.409  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 17:12:33.409  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,09-09 17:12:33.411  1978  1978 I WfdStateTracker: handleP2pThisDeviceChanged
,09-09 17:12:33.411  1978  1978 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 17:12:33.411  1037  1539 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 17:12:33.411  1037  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 17:12:33.411  1978  1978 D WfdsService: Update P2p Interface State: 3
09-09 17:12:33.411  1037  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 17:12:33.411  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,09-09 17:12:33.411  1037  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 17:12:33.412  1037  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 17:12:33.412  1037  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 17:12:33.412  1037  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 17:12:33.434  7146  7146 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 17:12:33.446  1037  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 17:12:33.446  1037  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 17:12:33.446  1037  1539 D LGWifiP2pService: InactiveState
09-09 17:12:33.446  1037  1539 D LGWifiP2pService: InactiveState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.446  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.446  1037  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 17:12:33.447  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 17:12:33.447  7164  7164 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.448  1978  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:12:33.448  7164  7164 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:12:33.448  7164  7164 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.448  1978  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.449  7164  7164 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.449  1037  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 17:12:33.449  1037  1539 D LGWifiP2pService: InactiveState{ when=-38ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.449  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-38ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.449  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.449  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.449  1978  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.449  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.450  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.450  1037  7173 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:12:33.450  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.450  1037  7173 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.450  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.450  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.450  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:33.450  1037  7173 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.450  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.450  1037  7173 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.450  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.450  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.450  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 ,17:12:33.450  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.450  1037  7173 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:33.450  1037  7173 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.450  1037  7173 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.450  1037  7173 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:33.450  1978  2354 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 17:12:33.451  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.451  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.451  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:33.451  1037  1037 E WifiServerServiceExt: No p2p device connected
,09-09 17:12:33.459  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:12:33.459  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:33.459  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 17:12:33.465  7146  7146 I HubEmail: JNI_OnLoad()
,09-09 17:12:33.465  7146  7146 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 17:12:33.465  7146  7146 I HubEmail: registerNatives()
09-09 17:12:33.465  7146  7146 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 17:12:33.465  7146  7146 I HubEmail: registerNativeMethods()
09-09 17:12:33.465  7146  7146 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 17:12:33.465  7146  7146 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 17:12:33.503  1037  2007 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7182 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-09 17:12:33.508  7029  7179 W FormManager: Network not available. Please check & try again.
09-09 17:12:33.508  7029  7180 V FormManager: Network unavailable.
,09-09 17:12:33.511  7146  7181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:33.513  7029  7180 V FormManager: Network unavailable.
09-09 17:12:33.518  1037  2054 I ActivityManager: Killing 6172:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-09 17:12:33.563  1037  2328 W libprocessgroup: failed to open /acct/uid_10080/pid_6172/cgroup.procs: No such file or directory
,09-09 17:12:33.617  7182  7182 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:33.617  7182  7182 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:33.620  7182  7182 D PhoneMonitor: Register our PhoneStateListener
09-09 17:12:33.633  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 17:12:33.637  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 17:12:33.658  7182  7182 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 17:12:33.660  7182  7182 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-09 17:12:33.661  7182  7182 D TelephonyAutoProfiling: [parse] Load xml
09-09 17:12:33.669  7182  7182 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 17:12:33.669  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-09 17:12:33.669  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-09 17:12:33.669  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-09 17:12:33.670  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,09-09 17:12:33.671  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 17:12:33.671  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 17:12:33.671  7182  7182 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-09 17:12:33.684  7182  7182 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 17:12:33.705  1037  2018 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7201 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:12:33.706  1037  2018 I ActivityManager: Killing 6202:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-09 17:12:33.744  1037  1577 W libprocessgroup: failed to open /acct/uid_10097/pid_6202/cgroup.procs: No such file or directory
,09-09 17:12:33.970  1037  1577 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7222 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-09 17:12:33.973  1037  1577 I ActivityManager: Killing 6783:com.lge.eula/1000 (adj 15): empty #17
09-09 17:12:34.033  1037  1973 W libprocessgroup: failed to open /acct/uid_1000/pid_6783/cgroup.procs: No such file or directory
,09-09 17:12:34.045  7164  7164 E wpa_supplicant: USIM:  scard_init function
09-09 17:12:34.046  7164  7164 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 17:12:34.046  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 17:12:34.047  1037  7173 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 17:12:34.047  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 17:12:34.047  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-09 17:12:34.047  1037  7173 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 17:12:34.047  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:12:34.047  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-09 17:12:34.048  1037  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:12:34.049  1037  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:12:34.052  1037  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:12:34.053  1037  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:12:34.053  1037  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 17:12:34.059  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122922  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 17:12:34.061  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122924  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 17:12:34.063  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.063  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.064  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.065  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.065  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 17:12:34.067  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.067  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.067  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 17:12:34.067  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:34.067  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 17:12:34.072  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:12:34.075  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.075  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.077  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.159  7164  7164 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 17:12:34.160  1037  2054 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7239 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:12:34.164  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 17:12:34.165  1037  2054 I ActivityManager: Killing 6800:com.lge.bnr/1000 (adj 15): empty #17
09-09 17:12:34.165  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 17:12:34.165  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 17:12:34.165  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 17:12:34.166  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:34.166  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:34.166  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123029  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 17:12:34.167  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123030  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 17:12:34.168  1037  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123031
09-09 17:12:34.169  1037  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123031
09-09 17:12:34.169  7164  7164 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:12:34.169  1037  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123033
09-09 17:12:34.170  7164  7164 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:12:34.170  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123033
09-09 17:12:34.173  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:34.173  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:34.173  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 17:12:34.173  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:12:34.173  1037  7173 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:12:34.173  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 17:12:34.173  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:12:34.174  1037  7173 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:12:34.174  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:34.174  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-09 17:12:34.177  1037  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123035
,09-09 17:12:34.178  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 17:12:34.214  1037  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:12:34.215  1037  2010 W libprocessgroup: failed to open /acct/uid_1000/pid_6800/cgroup.procs: No such file or directory
,09-09 17:12:34.223  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123086  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 17:12:34.227  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.227  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.228  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.228  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.228  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 17:12:34.229  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.229  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.229  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,09-09 17:12:34.231  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123094  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:12:34.232  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.232  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123095  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:12:34.232  1037  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123095
09-09 17:12:34.233  1037  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123096
09-09 17:12:34.233  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-09 17:12:34.233  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:34.233  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 17:12:34.235  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:34.236  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:34.236  1037  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-09 17:12:34.238  1037  1540 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 17:12:34.240  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.240  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.242  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.252  1037  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 17:12:34.252  1037  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-09 17:12:34.256  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.256  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.256  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:12:34.257  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.257  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.259  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.262  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.262  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.262  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:12:34.266  1037  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 17:12:34.266  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:34.266  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:12:34.266  1037  1547 D ConnectivityService: Got NetworkAgent Messenger
09-09 17:12:34.266  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 17:12:34.266  1037  1547 D ConnectivityService: NetworkAgent connected
09-09 17:12:34.267  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:12:34.267  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 17:12:34.275  7239  7239 I art     : Almond Protected OAT
09-09 17:12:34.278  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:12:34.278  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:34.278  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:12:34.279  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.279  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.279  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:12:34.279  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:12:34.280  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:12:34.287  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:12:34.291   328   897 D CommandListener: Setting iface cfg
09-09 17:12:34.293  1037  1540 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 17:12:34.294  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123157  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:34.294  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123157  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:34.295  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123158  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:34.295  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:34.296  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:34.296  1037  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:34.297  1037  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:34.297  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-09 17:12:34.303  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:34.304  1037  7257 D DhcpStateMachine: StoppedState
09-09 17:12:34.305  1037  7257 D DhcpStateMachine: StoppedState{ when=-11ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.305  1037  7257 D DhcpStateMachine: WaitBeforeStartState
09-09 17:12:34.305  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123168  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:34.306  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123169  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:34.307  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123170  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:34.308  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77182] from screen [on:0 period:260171780] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 17:12:34.309  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:260171781] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 17:12:34.309  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 17:12:34.313  1037  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-09 17:12:34.313  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:34.313  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:34.314  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:34.314  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:34.315  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:34.315  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:34.316  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:34.316  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 17:12:34.316  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 17:12:34.318  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.319  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
09-09 17:12:34.319  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
09-09 17:12:34.319  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,09-09 17:12:34.320  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 17:12:34.320  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:34.320  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 17:12:34.321  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 17:12:34.321  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 17:12:34.322  1037  1540 D WifiNative-wlan0: SET ps 0: returned true
09-09 17:12:34.322  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 17:12:34.322  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 17:12:34.323  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 17:12:34.323  1037  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 17:12:34.323  1037  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:12:34.323  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cc73dbf target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.323  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cc73dbf target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.323  1037  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:12:34.323  1037  7257 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.323  1037  7257 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 17:12:34.324   328   897 D CommandListener: Setting iface cfg
09-09 17:12:34.325   328   897 D CommandListener: Trying to bring up wlan0
09-09 17:12:34.325  1037  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 17:12:34.326  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:34.326  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 17:12:34.326  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 17:12:34.326  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 17:12:34.326  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:12:34.326  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:12:34.326  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.327  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.327  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:12:34.327  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 17:12:34.327  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 17:12:34.327  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 17:12:34.327  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:34.339  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.339  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.339  1037  1539 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:12:34.347  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:34.348  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-09 17:12:34.348  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:34.348  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:34.349  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:34.349  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:34.350  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:34.350  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:34.350  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 17:12:34.351  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:12:34.351  7239  7239 D WeatherApplication: removeAccount
09-09 17:12:34.351  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:12:34.351  1037  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 17:12:34.351  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
,09-09 17:12:34.353  7239  7239 D WeatherApplication: Account.length = 0
09-09 17:12:34.354  7239  7239 E WeatherApplication: OPERATOR:OPEN
09-09 17:12:34.359  7239  7239 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:34
09-09 17:12:34.361  7239  7239 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 17:12:34.362  7239  7239 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:12:34.364  7239  7239 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-09 17:12:34.367  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.367  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.367  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 17:12:34.368  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.368  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.369  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 17:12:34.370  1037  1547 D ConnectivityService: Adding iface wlan0 to network 101
09-09 17:12:34.370  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.370  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.370  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.370  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 17:12:34.371  7239  7239 D WeatherAncestor: connectivity changed - connection : true
09-09 17:12:34.373  7239  7239 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-09 17:12:34.374  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 17:12:34.377  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:12:34.377  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.377  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:12:34.379  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.379  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:34.381  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 17:12:34.384  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 17:12:34.385  1037  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 17:12:34.386  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.386  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.387  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:34.387  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:12:34.388  7239  7239 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:12:34.388  7239  7239 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:12:34.388  7239  7239 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-09 17:12:34.392  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 17:12:34.392  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 17:12:34.392  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.394  1037  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 17:12:34.394  1037  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 17:12:34.396  1037  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 17:12:34.397   328   897 E Netd    : netlink response contains error (File exists)
09-09 17:12:34.397  1037  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 17:12:34.398  1037  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 17:12:34.398  1037  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 17:12:34.398  1037  1547 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 17:12:34.399  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 17:12:34.399  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:34.399  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 17:12:34.399  1037  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 17:12:34.399  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 17:12:34.399  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 17:12:34.400  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:34.400  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:34.400  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 17:12:34.400  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.400  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:34.400  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 17:12:34.400  1037  1547 D ConnectivityService: currentScore = 0, newScore = 20
09-09 17:12:34.400  1037  1547 D ConnectivityService:    accepting network in place of null
09-09 17:12:34.400  1037  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:34.401  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.401  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 17:12:34.401  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:34.401  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 17:12:34.402  1882  1882 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:12:34.403  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:12:34.403  1037  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:12:34.403  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:34.404  1037  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 17:12:34.404  1037  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 17:12:34.404  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:12:34.405  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:34.405  1037  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 17:12:34.405   328  7267 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 17:12:34.406  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 17:12:34.406  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:12:34.406  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:12:34.406  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:12:34.407  1037  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 17:12:34.408  1037  1547 D ConnectivityService: validation of new default Network = false
09-09 17:12:34.408  1037  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 17:12:34.408  1037  1547 D DSQN    : enableDataServiceNotify 
09-09 17:12:34.408  1037  1547 D DSQN    : start dsqn bin
09-09 17:12:34.417  1037  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-09 17:12:34.418  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:12:34.418  1037  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:12:34.419  1037  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:12:34.419  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:12:34.419  1037  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:12:34.422  1037  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-09 17:12:34.432  1846  7268 I CheckinService: active receiver: enabled
09-09 17:12:34.432  7239  7239 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:12:34.433  7239  7239 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:34
09-09 17:12:34.463  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,09-09 17:12:34.463  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:34.459  7269  7269 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:34.459  7269  7269 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:34.463  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:34.464  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:34.465  1606  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:12:34.468  1846  7268 I CheckinService: Preparing to send checkin request
09-09 17:12:34.468  1846  7268 I EventLogService: Accumulating logs since 1473433889779
09-09 17:12:34.477  7269  7269 E DSQN    : DSQN ssw
,09-09 17:12:34.496  1037  1718 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7275 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:12:34.497  1037  1718 I ActivityManager: Killing 2188:com.lge.music/u0a34 (adj 15): empty #17
09-09 17:12:34.508   357   357 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 9.215ms
,09-09 17:12:34.517   333  1389 V AudioFlinger: 2188 died, releasing its sessions
09-09 17:12:34.517   333  1389 V AudioFlinger:  pid 1882 @ 0
09-09 17:12:34.517   333  1389 V AudioFlinger:  pid 3411 @ 1
09-09 17:12:34.517   333  1389 V AudioFlinger:  pid 3411 @ 2
09-09 17:12:34.518   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 8.951ms
09-09 17:12:34.524  1037  7257 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 17:12:34.525  1037  7257 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 17:12:34.525  1037  7257 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-09 17:12:34.527   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.984ms
09-09 17:12:34.519  7292  7292 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:34.519  7292  7292 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:34.531   328  7267 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 17:12:34.536  7292  7292 I dhcpcd  : version 5.5.6 starting
09-09 17:12:34.537  7292  7292 E dhcpcd  : get_duid: m
09-09 17:12:34.537  7292  7292 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 17:12:34.537  7292  7292 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-09 17:12:34.570   328  7267 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 17:12:34.577  7292  7292 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-09 17:12:34.577  1037  2328 W libprocessgroup: failed to open /acct/uid_10034/pid_2188/cgroup.procs: No such file or directory
09-09 17:12:34.577  7292  7292 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:12:34.577  7292  7292 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 17:12:34.577  7292  7292 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 17:12:34.577  7292  7292 D dhcpcd  : wlan0: sending REQUEST (xid 0x927601d8), next in 3.56 seconds
09-09 17:12:34.586  1846  7268 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 17:12:34.598  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:12:34.599  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:34.599   328   896 D LGDataListener: argv[0]=dsqncommand
09-09 17:12:34.599   328   896 D LGDataListener: argv[1]=wlan0
09-09 17:12:34.599   328   896 D LGDataListener: argv[2]=1
09-09 17:12:34.599   328   896 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 17:12:34.599  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:12:34.601  1037  1097 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 17:12:34.602  1037  1097 D DSQN    : start to monitor internet connection
09-09 17:12:34.603  7292  7292 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 17:12:34.662  7292  7292 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 17:12:34.662  7292  7292 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 17:12:34.663  7292  7292 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 17:12:34.663  7292  7292 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 17:12:34.663  7292  7292 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 17:12:34.663  7292  7292 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 17:12:34.663  7292  7292 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:12:34.663  7292  7292 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-09 17:12:34.667   280   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:12:34.667   280   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 17:12:34.667   280   348 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:12:34.668  7275  7302 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 17:12:34.672   280   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:12:34.672   280   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 17:12:34.672   280   348 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:12:34.674  7275  7302 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 17:12:34.703   280   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:12:34.703   280   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 17:12:34.704   280   348 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:12:34.704  7275  7308 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 17:12:34.706   280   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:12:34.706   280   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 17:12:34.706   280   348 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:12:34.707  7275  7308 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 17:12:34.714  1037  2010 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7312 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-09 17:12:34.766  7312  7312 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 17:12:34.767  7312  7312 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 17:12:34.805  7312  7312 I MultiDex: VM with version 2.1.0 has multidex support
09-09 17:12:34.805  7312  7312 I MultiDex: install
,09-09 17:12:34.805  7312  7312 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-09 17:12:34.817  7312  7312 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-09 17:12:34.896  7275  7275 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 17:12:34.915  7275  7275 I LibraryLoader: Loading: webviewchromium
,09-09 17:12:34.924  7275  7275 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 3791-3801)
09-09 17:12:34.925  7275  7275 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:12:34.927  1037  7257 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 17:12:34.930  1037  7257 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 17:12:34.930  1037  7257 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:12:34.930  1037  7257 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 17:12:34.930  1037  7257 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 17:12:34.930  1037  7257 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:12:34.930  1037  7257 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 17:12:34.930  1037  7257 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 17:12:34.930  1037  7257 D DhcpStateMachine: RunningState
09-09 17:12:34.933  7275  7275 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15db58a}
09-09 17:12:34.935  7275  7275 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:12:34.936  7275  7275 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 17:12:34.949  7275  7275 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 17:12:34.950  7275  7275 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:12:34.965  7275  7275 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-09 17:12:34.967  7275  7275 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-09 17:12:34.968  7275  7275 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-09 17:12:34.975   333   333 V AudioPolicyService: registerClient() client 0xb558a3a0, uid 10093
09-09 17:12:34.977  7275  7364 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 17:12:34.986  7275  7275 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:12:34.986  7275  7275 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:12:34.986  7275  7275 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:12:34.986  7275  7275 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:12:34.986  7275  7275 I Adreno-EGL: Remote Branch: 
09-09 17:12:34.986  7275  7275 I Adreno-EGL: Local Patches: 
09-09 17:12:34.986  7275  7275 I Adreno-EGL: Reconstruct Branch: 
09-09 17:12:35.085  7275  7275 I NSApplication: Starting up...
,09-09 17:12:35.113  7312  7328 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:35.113  7312  7328 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:35.145  1037  1718 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7377 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 17:12:35.148  1037  2010 I ActivityManager: Killing 6134:com.android.vending/u0a44 (adj 15): empty #17
09-09 17:12:35.172  7381  7381 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 17:12:35.222  7381  7381 I dex2oat : dex2oat took 50.327ms (threads: 4)
,09-09 17:12:35.224  1037  2007 W libprocessgroup: failed to open /acct/uid_10044/pid_6134/cgroup.procs: No such file or directory
,09-09 17:12:35.239  7312  7328 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:12:35.239  7312  7328 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:12:35.239  7312  7328 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:12:35.239  7312  7328 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:12:35.239  7312  7328 I Adreno-EGL: Remote Branch: 
09-09 17:12:35.239  7312  7328 I Adreno-EGL: Local Patches: 
09-09 17:12:35.239  7312  7328 I Adreno-EGL: Reconstruct Branch: 
,09-09 17:12:35.247  7377  7377 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:35.301  1037  2095 D WifiServiceImplEx: setWifiEnabled: false pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:12:35.301  1037  2095 D WifiService: setWifiEnabled: false pid=6717, uid=10118
,09-09 17:12:35.301  1037  2095 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:12:35.312  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:12:35.313  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:12:35.313  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-09 17:12:35.313  1037  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:35.313  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:35.314  1037  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:35.314  1037  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:35.314  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:12:35.314  1037  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 17:12:35.314  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:35.314  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:12:35.315  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:12:35.315  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:12:35.319  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:12:35.320  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:12:35.320  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:12:35.320  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.320  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.320  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:12:35.320  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:35.320  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:35.321   328   897 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:12:35.323  1037  7257 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.340  7312  7328 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:12:35.340  7312  7328 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:12:35.340  7312  7328 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:12:35.340  7312  7328 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:12:35.340  7312  7328 I Adreno-EGL: Remote Branch: 
09-09 17:12:35.340  7312  7328 I Adreno-EGL: Local Patches: 
09-09 17:12:35.340  7312  7328 I Adreno-EGL: Reconstruct Branch: 
09-09 17:12:35.344  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.ConnectException: failed to connect to clients3.google.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-09 17:12:35.372  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 17:12:35.372  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-09 17:12:35.375  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-09 17:12:35.375  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.376  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.376  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:35.378  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:35.378  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 17:12:35.379  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 17:12:35.382  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:35.382  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:35.382  1037  1539 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.382  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.382  1037  1539 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1e7a7a69
09-09 17:12:35.383  1037  1539 D LGWifiP2pService: P2pDisablingState
09-09 17:12:35.383  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:35.383  1037  1539 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.383  1037  1539 D LGWifiP2pService: p2p socket connection lost
09-09 17:12:35.383  1037  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:12:35.383  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:35.384  1037  1539 D LGWifiP2pService: P2pDisabledState
09-09 17:12:35.385  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 17:12:35.385  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-09 17:12:35.386  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.386  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.386  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:12:35.386  7164  7164 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:12:35.387  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:12:35.387  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:35.387  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:35.388  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.388  7312  7328 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:12:35.388  7312  7328 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:12:35.388  7312  7328 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:12:35.388  7312  7328 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:12:35.388  7312  7328 I Adreno-EGL: Remote Branch: 
09-09 17:12:35.388  7312  7328 I Adreno-EGL: Local Patches: 
09-09 17:12:35.388  7312  7328 I Adreno-EGL: Reconstruct Branch: 
09-09 17:12:35.388  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.388  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:35.388  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:12:35.389  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-09 17:12:35.389  1037  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.390  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 17:12:35.390  1978  1978 D WfdsService: WifiP2pState is changed : false
09-09 17:12:35.390  1978  2354 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 17:12:35.391  1978  2354 D WfdsService: Set the WFDS Monitor: false
09-09 17:12:35.391  1978  2354 D WfdsMonitor: WFDS Monitor is stopped
09-09 17:12:35.391  1978  2354, D WfdsService: STATE : WfdsDisabledState - enter
09-09 17:12:35.391  1978  7176 D CtrlSupplicant: Received on exit socket, terminate
09-09 17:12:35.391  1978  7176 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 17:12:35.391  1978  7176 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 17:12:35.391  1978  7176 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 17:12:35.392  1978  2355 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 17:12:35.392  1978  2354 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 17:12:35.392  1037  1558 D WifiScanningService: DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:12:35.405  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:35.405  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:35.406  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:12:35.420   328   897 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:12:35.421  1037  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 17:12:35.421  1037  1547 D DSQN    : disableDataServiceNotify
09-09 17:12:35.421  1037  1547 D DSQN    : stop dsqn bin
09-09 17:12:35.422  1037  1540 D WifiNative-p2p0: doBoolean: TERMINATE
,09-09 17:12:35.422  1037  1540 D WifiNative-p2p0: TERMINATE: returned true
09-09 17:12:35.422  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:35.422  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:35.422  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:12:35.422  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-09 17:12:35.425  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 17:12:35.425  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:35.425  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.425  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.425  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:35.426  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:35.428  1037  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 17:12:35.428  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:35.428  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:35.428  1037  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:35.428  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 17:12:35.428  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 17:12:35.429  1606  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 17:12:35.429  1037  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 17:12:35.429  1037  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 17:12:35.429  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:12:35.429  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.429  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:35.429  1037  7256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 17:12:35.431  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 17:12:35.431  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:35.431  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 17:12:35.431  1037,  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:35.431  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:12:35.431  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:12:35.431  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:12:35.431  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:12:35.431  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:12:35.432  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:35.432  1037  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:35.432  1037  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:35.432  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:12:35.433  1037  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:35.433  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:35.433  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:12:35.433  1037  1547 D NetworkManagementService: Removing idletimer
09-09 17:12:35.434  1037  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.434  1037  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 17:12:35.434  1882  1882 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:35.434  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-09 17:12:35.434  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:35.434  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:35.434  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:12:35.434  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:35.435  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:35.435  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:35.435  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:35.435  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:35.436  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:12:35.437  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
,09-09 17:12:35.437  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:12:35.437  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-09 17:12:35.445  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:35.463  1037  1547 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 17:12:35.505  7164  7164 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 17:12:35.506  7164  7164 I wpa_supplicant: monitor socket send errors count : 1
09-09 17:12:35.506  7164  7164 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1978-4\x00 that cannot receive messages
,09-09 17:12:35.513  1037  7173 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 17:12:35.513  1037  7173 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 17:12:35.530  7164  7164 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 17:12:35.533  7164  7164 W wpa_supplicant: USIM:  scard_deinit function
09-09 17:12:35.534  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 17:12:35.534  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:12:35.534  1037  7173 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:12:35.535  1037  7173 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 17:12:35.536  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:35.536  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:35.537  1037  1099 D Tethering: InitialState.processMessage what=4
09-09 17:12:35.537  1037  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124400
09-09 17:12:35.539  1037  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124402
09-09 17:12:35.540  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124403  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:12:35.542  1037  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:12:35.547  1037  7257 D DhcpStateMachine: StoppedState
09-09 17:12:35.547  1037  7257 D DhcpStateMachine: StoppedState{ when=-160ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:12:35.568  1037  1718 I art     : Explicit concurrent mark sweep GC freed 104651(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 6.732ms total 119.976ms
,09-09 17:12:35.573  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:12:35.574  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 17:12:35.583  1037  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 17:12:35.583  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:35.583  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-09 17:12:35.610  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:12:35.611  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:35.612  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:12:35.628  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:12:35.630  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:35.630  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:35.663  7164  7164 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 17:12:35.664  1037  7173 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 17:12:35.664  1037  7173 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 17:12:35.664  1037  7173 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-09 17:12:35.666  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-09 17:12:35.716  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 17:12:35.717  6523  6547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 17:12:35.742  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:35.749  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:12:35.749  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:35.749  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:12:35.749  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 17:12:35.751  7113  7113 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:12:35.753  7113  7113 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@dfb3793
09-09 17:12:35.753  7113  7113 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:12:35.753  7113  7113 D AppUp4:CustFacade: isPhone : true
09-09 17:12:35.753  7113  7113 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:12:35.754  7113  7113 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-09 17:12:35.758  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:35.758  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:35.760  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:35.761  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:35.768  1037  1540 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 17:12:35.768  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:35.768  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:35.768  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:12:35.768  1978  1978 D WfdsService: Supplicant Connection state is changed : false
09-09 17:12:35.768  1978  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 17:12:35.768  1978  2354 D WfdsService: Set the WFDS Monitor: false
09-09 17:12:35.768  1978  2354 D WfdsMonitor: WFDS Monitor is stopped
,09-09 17:12:35.768  7146  7146 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 17:12:35.771  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 17:12:35.772  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:35.772  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:35.772  4344  7414 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:12:35.773  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:35.773  2471  2471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.774  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:35.776  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 17:12:35.776  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 17:12:35.776  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 17:12:35.782  4344  7415 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:35.782  4344  7415 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 17:12:35.792  7146  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:35.796  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:12:35.796  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:35.796  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 17:12:35.799  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 17:12:35.799  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:12:35.804  7029  7419 W FormManager: Network not available. Please check & try again.
09-09 17:12:35.810  7239  7239 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:35
09-09 17:12:35.813  7029  7420 V FormManager: Network unavailable.
,09-09 17:12:35.814  7239  7239 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 17:12:35.814  7239  7239 D Weather.Utils: 2 : All the weather widget is gone.
,09-09 17:12:35.815  7029  7420 V FormManager: Network unavailable.
09-09 17:12:35.815  7239  7239 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:12:35.815  7239  7239 D WeatherAncestor: connectivity changed - connection : true
09-09 17:12:35.815  7239  7239 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5a4fc9
09-09 17:12:35.815  7239  7239 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:12:35.816  7239  7239 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:12:35.816  7239  7239 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:12:35.816  7239  7239 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:12:35.816  7239  7239 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:35
09-09 17:12:35.840  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:12:35.840  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:12:35.840  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:12:35.840  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:12:35.841  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-09 17:12:35.842  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:12:35.843  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 17:12:35.843  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:12:35.843  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:12:35.843  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:12:35.843  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:12:35.850   328  7428 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 17:12:35.851  1037  1097 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 17:12:35.851  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:35.852  1846  7268 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-09 17:12:35.855  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 17:12:35.857  7029  7429 W FormManager: Network not available. Please check & try again.
09-09 17:12:35.860  7029  7430 V FormManager: Network unavailable.
09-09 17:12:35.863  7029  7430 V FormManager: Network unavailable.
09-09 17:12:35.864  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:35.867  1846  7268 I CheckinService: active receiver: disabled
,09-09 17:12:35.887  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:35.891  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 17:12:35.893  7029  7432 W FormManager: Network not available. Please check & try again.
09-09 17:12:35.896  7029  7433 V FormManager: Network unavailable.
09-09 17:12:35.896  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:35.901  7029  7433 V FormManager: Network unavailable.
,09-09 17:12:35.906  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:12:35.906  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:35.908  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:35.909  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:35.914  4344  7434 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:12:35.915  4344  7435 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:12:35.915  4344  7435 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:35.953  1037  1577 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7436 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 17:12:36.082  7436  7436 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:12:36.082  7436  7436 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 17:12:36.092  7436  7436 V [BNRBootReceiver]: Boot Receiver Return
,09-09 17:12:36.093  7436  7436 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 17:12:36.100  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:36.111  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.121  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.133  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:12:36.133  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.136  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:36.140  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 17:12:36.143  6932  6932 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 17:12:36.148  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:36.155  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.163  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.175  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.176  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:12:36.178  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:36.181  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.192  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.204  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.211  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.211  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.212  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:36.220  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:36.235  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.241  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:12:36.248  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.249  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.250  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:12:36.255  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.262  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.270  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.278  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:12:36.278  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.279  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:36.282  6831  7090 D UEI.SmartControl: Internal timer expired: 2
09-09 17:12:36.284  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.284  6831  7090 D UEI.SmartControl: unbind internal service
09-09 17:12:36.296  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.306  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.317  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:12:36.318  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:12:36.319  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:36.325  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.341  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.353  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.367  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.368  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.369  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:12:36.386  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.395  6831  7084 D serial_port: close(fd = 24)
,09-09 17:12:36.400  6831  7084 I UEI.SmartControl: Serial port is closed.
09-09 17:12:36.408  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.415  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.432  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:12:36.433  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.441  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:36.446  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:36.458  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.466  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.477  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.477  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:12:36.479  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:36.486  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.494  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 17:12:36.504  1037  1546 D WifiService: New client listening to asynchronous messages
,09-09 17:12:36.505  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:36.511  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.518  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.528  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.529  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.531  6989  6989 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-09 17:12:36.533  6989  6989 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:12:36.534  6989  6989 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 17:12:36.546  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:36.557  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 17:12:36.564  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:36.568  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:36.574  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.585  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.586  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.587  6989  6989 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 17:12:36.587  6989  6989 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:12:36.588  6989  6989 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-09 17:12:36.591  1037  2018 I ActivityManager: Killing 6908:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-09 17:12:36.649  1037  1780 W libprocessgroup: failed to open /acct/uid_10037/pid_6908/cgroup.procs: No such file or directory
,09-09 17:12:36.653  2206  2206 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-09 17:12:36.667  2206  2206 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-09 17:12:36.667  2206  2206 D c       : Getting all permits...
,09-09 17:12:36.667  2206  2206 D a       : Opening database...
09-09 17:12:36.672  2206  2206 D a       : Opening database auth.proximity.permit_store...
09-09 17:12:36.673  2206  2206 D a       : Closing database...
09-09 17:12:36.683  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:36.687  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:12:36.688  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:12:36.688  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:36.691  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:36.697  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:12:36.703  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.704  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.705  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:36.708  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.712  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:12:36.712  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:12:36.712  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:36.717  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:36.722  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.731  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:12:36.732  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:36.734  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:36.740  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:36.745  6959  6959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:12:36.745  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-09 17:12:36.745  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:36.753  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:36.762  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:12:36.770  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:36.771  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:12:36.773  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:36.782  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:36.786  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:12:36.791  7029  7461 W FormManager: Network not available. Please check & try again.
,09-09 17:12:36.797  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.813  7029  7462 V FormManager: Network unavailable.
,09-09 17:12:36.821  7029  7462 V FormManager: Network unavailable.
09-09 17:12:36.821  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:12:36.822  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:36.824  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:36.826  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:12:36.837  4344  7463 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:12:36.838  4344  7464 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:12:36.838  4344  7464 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:36.846  6959  6959 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 17:12:36.846  6959  6959 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:12:36.846  6959  6959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:36.851  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 17:12:36.858  7029  7467 V FormManager: Network unavailable.
,09-09 17:12:36.861  7029  7466 W FormManager: Network not available. Please check & try again.
,09-09 17:12:36.862  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:36.867  7029  7467 V FormManager: Network unavailable.
09-09 17:12:36.883  2206  2206 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-09 17:12:37.317  1037  1540 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:260174788] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 17:12:37.319  1037  1540 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:260174791] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 17:12:37.407  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:37.421  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-09 17:12:37.431  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:37.435  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:37.438  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:37.441  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:12:37.443  6523  6547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 17:12:37.455  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 17:12:37.474  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:37.493  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:12:37.493  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:37.494  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:12:37.494  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 17:12:37.498  7113  7113 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:12:37.502  7113  7113 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@dfb3793
09-09 17:12:37.502  7113  7113 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:12:37.502  7113  7113 D AppUp4:CustFacade: isPhone : true
09-09 17:12:37.503  7113  7113 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:12:37.503  7113  7113 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 17:12:37.508  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:37.508  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:37.510  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:12:37.516  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:37.523  7146  7146 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 17:12:37.554  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:12:37.554  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:37.554  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = true
09-09 17:12:37.554  3411  3411 D PhoneState: setPdpRejectCasuse : false
,09-09 17:12:37.560  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 17:12:37.560  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:12:37.571  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 17:12:37.575  4344  7476 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:12:37.585  4344  7490 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:37.585  4344  7490 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:37.586  7239  7239 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:37
,09-09 17:12:37.588  7146  7475 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:37.593  7239  7239 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 17:12:37.593  7239  7239 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:12:37.594  7029  7491 W FormManager: Network not available. Please check & try again.
09-09 17:12:37.594  7239  7239 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:12:37.594  7239  7239 D WeatherAncestor: connectivity changed - connection : true
09-09 17:12:37.594  7239  7239 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5a4fc9
09-09 17:12:37.595  7239  7239 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:12:37.595  7239  7239 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:12:37.595  7239  7239 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:12:37.595  7239  7239 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:12:37.595  7239  7239 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:37
09-09 17:12:37.599  7029  7492 V FormManager: Network unavailable.
,09-09 17:12:37.605  7029  7492 V FormManager: Network unavailable.
,09-09 17:12:38.315  1037  2328 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:12:38.315  1037  2328 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-09 17:12:38.341  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:12:38.341  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:12:38.341  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,09-09 17:12:38.343  1037  1099 D BluetoothManagerService: Message: 1
09-09 17:12:38.343  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-09 17:12:38.369  1037  1099 D BluetoothManagerService: Message: 20
09-09 17:12:38.370  1037  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@255ac54c:true
,09-09 17:12:38.374  7046  7046 D BluetoothAdapterState: make
09-09 17:12:38.378  7046  7046 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 17:12:38.379  7046  7046 I bluedroid-qcom: init
09-09 17:12:38.380  7046  7508 I BluetoothAdapterState: Entering OffState
09-09 17:12:38.380  7046  7046 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 17:12:38.381  7046  7046 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 17:12:38.381  7046  7046 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:12:38.381  7046  7046 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 17:12:38.381  7046  7046 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 17:12:38.383  7046  7046 I bluedroid-qcom: get_profile_interface socket
09-09 17:12:38.383  7046  7046 I bluedroid-qcom: get_profile_interface map_client
,09-09 17:12:38.387  7046  7512 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 17:12:38.379  7511  7511 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:38.389  7511  7511 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:38.401  7511  7511 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 17:12:38.401  7511  7511 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 17:12:38.401  7511  7511 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-09 17:12:38.406  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 17:12:38.406  1037  1099 D BluetoothManagerService: Message: 40
09-09 17:12:38.406  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 17:12:38.407  7046  7062 I bluedroid-qcom: config_hci_snoop_log
09-09 17:12:38.408  1037  1099 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 17:12:38.408  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 17:12:38.411  7511  7511 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 17:12:38.416  7046  7508 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-09 17:12:38.419  7511  7511 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 17:12:38.420  7511  7511 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 17:12:38.421  7046  7512 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 17:12:38.423  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:12:38.424  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 17:12:38.424  7046  7512 D BluetoothAdapterProperties: Name is: G3
09-09 17:12:38.424  7046  7508 D BluetoothAdapterProperties: Setting state to 11
09-09 17:12:38.424  7046  7508 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 17:12:38.425  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:38.425  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 17:12:38.425  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 17:12:38.430  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:38.433  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.433  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:12:38.436  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:38.440  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 17:12:38.442  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:38.447  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.461  7046  7046 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-09 17:12:38.468  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:38.468  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-09 17:12:38.469  7046  7508 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 17:12:38.472  7046  7046 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:38.472  7046  7046 V BluetoothPbapReceiver: ***********state = 11
09-09 17:12:38.478  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:38.490  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:38.491  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-09 17:12:38.498  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:38.502  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:38.502  7046  7508 D BluetoothBondStateMachine: make
09-09 17:12:38.503  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 17:12:38.505  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:38.508  7046  7508 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.508  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:12:38.508  7046  7508 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 17:12:38.508  7046  7508 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.508  7046  7508 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 17:12:38.509  7046  7508 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 17:12:38.511  6523  6547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 17:12:38.511  7046  7528 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 17:12:38.516  7046  7508 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:12:38.557  1037  1973 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7531 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-09 17:12:38.571  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 17:12:38.572  7046  7046 D HeadsetService: Received start request. Starting profile...
09-09 17:12:38.573  7046  7508 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:12:38.574  7046  7046 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:12:38.575  7046  7046 D LGBluetoothHfpAdapter: Version 1.6
09-09 17:12:38.578  7046  7046 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:12:38.579  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.579  7046  7046 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:12:38.580  7046  7046 D HeadsetStateMachine: make
09-09 17:12:38.581  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:38.581  7046  7508 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:12:38.581  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:38.587  7046  7508 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:12:38.596  7046  7508 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:12:38.603  7046  7508 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:12:38.608  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.612  7046  7508 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:12:38.619  7046  7046 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:38.619  7046  7046 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:12:38.624  7046  7046 D HeadsetStateMachine: max_hf_connections = 1
09-09 17:12:38.624  7046  7046 I bluedroid-qcom: get_profile_interface handsfree
09-09 17:12:38.626  7046  7046 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-09 17:12:38.626  7046  7508 V LGMDMManager: Create singleton instance
09-09 17:12:38.626   333   333 V AudioPolicyService: registerClient() client 0xb558a620, uid 1002
09-09 17:12:38.626   333  1388 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:12:38.626   333  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:12:38.626   333  1388 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:12:38.626  7046  7046 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 17:12:38.627  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:12:38.627   333  1389 V AudioFlinger: registerClient() client 0xb14337c0, pid 7046
09-09 17:12:38.627  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.627   333  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:38.627   333  1382 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-09 17:12:38.627  7046  7046 V ToneGenerator: Create Track: 0xb4928a80
09-09 17:12:38.627  7046  7046 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 17:12:38.627  7046  7046 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
,09-09 17:12:38.627  1037  1780 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:38.627  1037  1780 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:38.627  3411  3426 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,09-09 17:12:38.627  3411  3426 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:38.628  7046  7063 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:38.628  7046  7063 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 17:12:38.628   333  1383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:38.628   333  1383 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:38.628  3411  3427 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:38.628  3411  3427 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:38.628  1037  2007 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:38.628  1037  2007 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:38.628  7046  7063 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:38.628  7046  7063 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 17:12:38.628   333   333 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 17:12:38.628   333   333 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:12:38.628   333   333 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:12:38.628   333   333 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:12:38.628  1606  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:38.628  1606  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:38.628   333   333 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 17:12:38.628  1606  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:38.628  1606  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:38.628   333  1389 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 17:12:38.628  1882  4446 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:38.628   333  1389 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 17:12:38.628   333  1389 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:12:38.628  1882  4446 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:38.628   333  1389 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:12:38.628  1882  4446 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:38.628  1882  4446 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:38.629  7046  7046 V AudioSystem: getLatency() output 2, latency 50
09-09 17:12:38.629  7046  7046 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 17:12:38.629  7046  7046 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 17:12:38.629  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:12:38.629  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 17:12:38.629   333   333 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:12:38.629   333   333 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:12:38.629   333   333 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:12:38.629   333   333 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:12:38.629   333   333 V AudioFlinger: createTrack() lSessionId: 22
09-09 17:12:38.629  7046  7508 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 17:12:38.631  7113  7113 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 17:12:38.631  7046  7046 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 17:12:38.631   333  1388 V AudioFlinger: acquiring 22 from 7046, for 7046
09-09 17:12:38.631   333  1388 V AudioFlinger:  added new entry for 22
09-09 17:12:38.632  7046  7046 V ToneGenerator: ToneGenerator INIT OK, time: 127509
09-09 17:12:38.632  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.633  7046  7543 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 17:12:38.634  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.635  7046  7543 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:12:38.635  7046  7543 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:12:38.635  7046  7046 D A2dpService: Received start request. Starting profile...
09-09 17:12:38.635  7046  7543 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 17:12:38.635   333   333 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7046
09-09 17:12:38.636  7046  7046 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 17:12:38.637  7046  7046 V Avrcp   : make
09-09 17:12:38.637  7046  7046 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 17:12:38.637  7046  7046 I bluedroid-qcom: get_profile_interface avrcp
09-09 17:12:38.637   333   333 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 17:12:38.637   333   333 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 17:12:38.637   333   333 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 17:12:38.637   333   333 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 17:12:38.637   333   333 V voice   : voice_set_parameters: exit with code(0)
09-09 17:12:38.637   333   333 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 17:12:38.637   333   333 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 17:12:38.638   333   333 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 17:12:38.638   333   333 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 17:12:38.638   333   333 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 17:12:38.638   333   333 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 17:12:38.638  7046  7543 V ToneGenerator: ToneGenerator destructor
09-09 17:12:38.638  7046  7543 V ToneGenerator: stopTone
09-09 17:12:38.638  7046  7543 V ToneGenerator: Delete Track: 0xb4928a80
09-09 17:12:38.638  7046  7543 V AudioTrack: ~AudioTrack, releasing session id from 7046 on behalf of 7046
09-09 17:12:38.638  7113  7113 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@dfb3793
09-09 17:12:38.638  7113  7113 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:12:38.638  7113  7113 D AppUp4:CustFacade: isPhone : true
09-09 17:12:38.638   333  1389 V AudioFlinger: releasing 22 from 7046 for 7046
09-09 17:12:38.638   333  1389 V AudioFlinger:  decremented refcount to 0
09-09 17:12:38.638   333  1389 V AudioFlinger: purging stale effects
09-09 17:12:38.639  7113  7113 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:12:38.638   333  1389 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 17:12:38.639   333  1389 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 17:12:38.639   333  1389 V AudioFlinger: PlaybackThread::Track destructor
09-09 17:12:38.639   333  1389 V AudioFlinger: removeClient_l() pid 7046, calling pid 333
09-09 17:12:38.640   333  1230 V AudioPolicyService: AudioCommandThread() waking up
09-09 17:12:38.640   333  1230 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 ,17:12:38.640   333  1230 V AudioPolicyManager: releaseOutput() 2
09-09 17:12:38.640   333  1230 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 17:12:38.640  7113  7113 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 17:12:38.642  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.642  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:38.644  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:38.645  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:38.645  7046  7046 V AudioManager: registerRemoteController: size of Media player list: 0
,09-09 17:12:38.646  7046  7046 E AudioManager: No RCC entry present to update
09-09 17:12:38.646  7046  7046 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 17:12:38.649  7046  7046 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 17:12:38.649  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 17:12:38.649  7046  7046 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-09 17:12:38.652  7146  7146 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 17:12:38.653  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 17:12:38.657  4344  7551 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:12:38.660  4344  7554 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.661  4344  7554 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:38.700  7146  7555 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:12:38.710  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:12:38.710  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.710  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 17:12:38.720  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 17:12:38.721  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:12:38.721  7029  7558 W FormManager: Network not available. Please check & try again.
09-09 17:12:38.729  7531  7531 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 17:12:38.730  7029  7559 V FormManager: Network unavailable.
09-09 17:12:38.730  7531  7531 W LG Account v2.2: No ProfileInfo entries
09-09 17:12:38.731  7531  7531 I LG Account v2.2: isEnabled: false
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Country: EU
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Operator: OPEN
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Ranking support: false
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Comfort support: false
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Accessory: true
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Health device: true
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Extra Pedometer: false
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Blood glucose device: false
09-09 17:12:38.731  7239  7239 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:38
09-09 17:12:38.731  7531  7531 I Feature : [Lifetracker]Device Number: 3
,09-09 17:12:38.736  1037  1973 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:38.736  1037  1973 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:12:38.737  7239  7239 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 17:12:38.737  7239  7239 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:12:38.738  7029  7559 V FormManager: Network unavailable.
09-09 17:12:38.738  7239  7239 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:12:38.738  7239  7239 D WeatherAncestor: connectivity changed - connection : true
09-09 17:12:38.738  7239  7239 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5a4fc9
09-09 17:12:38.739  7239  7239 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:12:38.739  7239  7239 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:12:38.739  7239  7239 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:12:38.739  7239  7239 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:12:38.739  7239  7239 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:38
09-09 17:12:38.741  6932  6932 D BluetoothPermissionRequest: onReceive
09-09 17:12:38.751  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 17:12:38.764  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:12:38.766  6523  6547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 17:12:38.775  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.781  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:12:38.781  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:38.782  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:12:38.782  7113  7113 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 17:12:38.784  7113  7113 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:12:38.786  7113  7113 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@dfb3793
09-09 17:12:38.786  7113  7113 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:12:38.786  7113  7113 D AppUp4:CustFacade: isPhone : true
09-09 17:12:38.786  7113  7113 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:12:38.786  7113  7113 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 17:12:38.789  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.789  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:12:38.790  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:38.792  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:38.796  4344  7562 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:12:38.797  7146  7146 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 17:12:38.799  4344  7563 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:38.799  4344  7563 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:38.812  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:12:38.812  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:38.812  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 17:12:38.817  7146  7564 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:38.817  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 17:12:38.817  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:12:38.820  1037  2095 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 17:12:38.826  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-09 17:12:38.828  7029  7567 W FormManager: Network not available. Please check & try again.
09-09 17:12:38.829  7239  7239 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:38
09-09 17:12:38.829  7029  7568 V FormManager: Network unavailable.
09-09 17:12:38.830  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 17:12:38.830  7239  7239 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 17:12:38.830  7239  7239 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:12:38.830  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 17:12:38.830  7239  7239 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:12:38.830  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 17:12:38.830  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 17:12:38.830  7239  7239 D WeatherAncestor: connectivity changed - connection : true
09-09 17:12:38.830  7239  7239 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5a4fc9
09-09 17:12:38.830  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:12:38.830  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 17:12:38.830  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,09-09 17:12:38.831  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 17:12:38.831  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:12:38.831  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 17:12:38.831  7239  7239 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:12:38.831  7239  7239 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:12:38.831  7239  7239 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:12:38.831  7046  7046 I BluetoothA2dpServiceJni: classInitNative
09-09 17:12:38.831  7239  7239 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:12:38.831  7046  7046 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:12:38.831  7239  7239 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:38
09-09 17:12:38.831  7046  7046 D A2dpStateMachine: make
09-09 17:12:38.833  7046  7046 I bluedroid-qcom: get_profile_interface a2dp
09-09 17:12:38.833  7046  7570 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 17:12:38.835  7029  7568 V FormManager: Network unavailable.
09-09 17:12:38.835  7046  7046 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:12:38.835  7046  7046 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 17:12:38.836  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.837  7046  7046 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 17:12:38.839  7046  7046 D HidService: Received start request. Starting profile...
09-09 17:12:38.839  7046  7046 I bluedroid-qcom: get_profile_interface hidhost
09-09 17:12:38.839  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.839  7046  7046 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 17:12:38.842  7046  7569 D A2dpStateMachine: Enter Disconnected: -2
09-09 17:12:38.843  7046  7046 D HealthService: Received start request. Starting profile...
09-09 17:12:38.844  7046  7046 I bluedroid-qcom: get_profile_interface health
09-09 17:12:38.845  7046  7046 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:12:38.845  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.845  7046  7046 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 17:12:38.847  7046  7046 D PanService: Received start request. Starting profile...
09-09 17:12:38.847  7046  7046 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:12:38.847  7046  7046 I bluedroid-qcom: get_profile_interface pan
09-09 17:12:38.852  7046  7046 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 17:12:38.852  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
,09-09 17:12:38.852  7046  7046 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 17:12:38.856  7046  7046 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:12:38.857  7046  7046 D BtGatt.GattService: Received start request. Starting profile...
09-09 17:12:38.857  7046  7046 D BtGatt.GattService: start()
09-09 17:12:38.857  7046  7046 I bluedroid-qcom: get_profile_interface gatt
09-09 17:12:38.857  7046  7046 D BtGatt.AdvertiseManager: advertise manager created
09-09 17:12:38.862  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.863  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.864  7046  7046 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,09-09 17:12:38.864  7046  7046 V BluetoothMapService: BluetoothMapBinder()
09-09 17:12:38.865  7046  7046 D BluetoothMapService: Received start request. Starting profile...
09-09 17:12:38.865  7046  7046 D BluetoothMapService: start()
09-09 17:12:38.867  7046  7046 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 17:12:38.867  7046  7046 D BluetoothMapEmailAppObserver: createReceiver()
09-09 17:12:38.868  7046  7046 D BluetoothMapEmailAppObserver: initObservers()
09-09 17:12:38.869  7046  7046 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 17:12:38.878  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:38.878  7046  7046 D HeadsetStateMachine: Proxy object connected
09-09 17:12:38.879  7046  7046 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 17:12:38.879  7046  7046 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-09 17:12:38.884  7046  7046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:12:38.885  7046  7543 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 17:12:38.886  7046  7543 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-09 17:12:38.887  7046  7543 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 17:12:38.891  7046  7046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 17:12:38.896  7046  7046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:12:38.901  7046  7046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:12:38.902  7046  7046 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 17:12:38.906  7046  7046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 17:12:38.911  7046  7046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 17:12:38.911  7046  7046 V BluetoothMapService: Handler(): got msg=1
09-09 17:12:38.913  7046  7508 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 17:12:38.913  7046  7508 I bluedroid-qcom: enable
09-09 17:12:38.914  7046  7577 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 17:12:38.914  7046  7577 I bt-btu  : btu_task pending for preload complete event
09-09 17:12:38.914  7046  7508 I bt_hci_bdroid: init
,09-09 17:12:38.917  7046  7508 I bt_vendor: bt-vendor : init
09-09 17:12:38.917  7046  7508 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 17:12:38.917  7046  7508 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 17:12:38.917  7046  7508 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 17:12:38.917  7046  7508 D bt_userial_mct: userial_init
09-09 17:12:38.918  7046  7046 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:38.922  7046  7046 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:38.922  7046  7046 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:38.922  7046  7046 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:38.923  7046  7508 D bt_hci_bdroid: set_power 1
09-09 17:12:38.923  7046  7508 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-09 17:12:38.923  7046  7508 I bt_vendor: Starting hciattach daemon
,09-09 17:12:38.923  7046  7508 I bt_vendor: try to set true
09-09 17:12:38.923  7046  7046 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:38.923  7046  7046 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 17:12:38.919  7580  7580 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:38.919  7580  7580 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:38.979  7581  7581 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 17:12:39.088  7587  7587 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 17:12:39.114  7588  7588 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 17:12:39.163  7593  7593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:12:39.177  7594  7594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 17:12:39.193  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:12:39.198  1037  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{22426212 type 2 when 128059 com.google.android.gms} when 128059
09-09 17:12:39.205  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-09 17:12:39.205  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5401
09-09 17:12:39.209   328  7601 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-09 17:12:39.214  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-09 17:12:39.216  1037  1097 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-09 17:12:39.235  7603  7603 I libmdmdetect: ESOC framework not supported
09-09 17:12:39.236  7603  7603 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-09 17:12:39.244  7603  7603 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-09 17:12:39.244  7603  7603 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-09 17:12:39.244  7603  7603 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 17:12:39.244  7603  7603 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 17:12:39.244  7603  7603 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 17:12:39.244  7603  7603 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 17:12:39.244  7603  7603 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-09 17:12:39.284  7603  7604 E QC-QMI  : qmi_client [7603] 14: failed to locate client data
,09-09 17:12:39.286   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 17:12:39.286   474   474 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-09 17:12:39.308  7605  7605 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 17:12:39.320  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 17:12:39.363  1037  1095 W ProcessCpuTracker: Skipping unknown process pid 7580
,09-09 17:12:39.364  1037  1095 W ProcessCpuTracker: Skipping unknown process pid 7607
,09-09 17:12:39.380  7046  7508 I bt_vendor: bluetooth satus is on
09-09 17:12:39.380  7046  7508 D bt_hci_bdroid: preload
,09-09 17:12:39.382  7046  7579 D bt_userial_mct: userial_open(port:0)
09-09 17:12:39.382  7046  7579 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-09 17:12:39.387  7046  7579 I bt_vendor: Done intiailizing UART
09-09 17:12:39.388  7046  7579 I bt_vendor: Done intiailizing UART
09-09 17:12:39.388  7046  7579 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 17:12:39.388  7046  7579 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 17:12:39.388  7046  7577 I bt-btu  : btu_task received preload complete event
09-09 17:12:39.388  7046  7608 D bt_userial_mct: Entering userial_read_thread()
09-09 17:12:39.389  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 17:12:39.389  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 17:12:39.391  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:12:39.396  7046  7577 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:12:39.491  7046  7577 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-09 17:12:39.491  7046  7577 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa022f061 
09-09 17:12:39.491  7046  7577 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa022f061 
,09-09 17:12:39.539  7046  7512 E bt-btif : Calling BTA_HhEnable
,09-09 17:12:39.539  7046  7512 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 17:12:39.540  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 17:12:39.540  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 17:12:39.540  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 17:12:39.540  7046  7512 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 17:12:39.540  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,09-09 17:12:39.541  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,09-09 17:12:39.550  7046  7512 D BluetoothAdapterProperties: Name is: G3
,09-09 17:12:39.550  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:12:39.551  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 17:12:39.554  7046  7512 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:12:39.554  7046  7512 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:12:39.555  7046  7512 D bt_hci_bdroid: postload
09-09 17:12:39.555  7046  7579 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:12:39.556  7046  7577 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 17:12:39.557  7046  7512 D bte_conf: Device ID record 1 : primary
09-09 17:12:39.557  7046  7512 D bte_conf:   vendorId            = 00c4
09-09 17:12:39.557  7046  7512 D bte_conf:   vendorIdSource      = 0001
09-09 17:12:39.557  7046  7512 D bte_conf:   product             = 13a1
09-09 17:12:39.557  7046  7512 D bte_conf:   version             = 1000
09-09 17:12:39.557  7046  7512 D bte_conf:   clientExecutableURL = 
09-09 17:12:39.557  7046  7512 D bte_conf:   serviceDescription  = 
09-09 17:12:39.557  7046  7512 D bte_conf:   documentationURL    = 
09-09 17:12:39.557  7046  7512 D bte_conf: bte_load_did_conf no section named DID2.
09-09 17:12:39.562  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:39.563  7046  7577 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:39.563  7046  7577 W bt-smp  : Plain text(LSB ~ MSB) = 77 46 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:39.563  7046  7577 W bt-smp  : Encrypted text(LSB ~ MSB) = f0 e9 ca 3e 63 0d 77 b9 2d d4 9d 67 07 29 65 a4 
09-09 17:12:39.564  7046  7579 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:12:39.564  7046  7577 W bt-btm  : Stopping oneshot timer
09-09 17:12:39.566  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:39.559  7610  7610 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:39.559  7610  7610 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:39.568  7046  7508 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 17:12:39.568  7046  7508 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:12:39.568  7046  7508 D BluetoothAdapterProperties: State =  11
09-09 17:12:39.568  7046  7508 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 17:12:39.569  7046  7508 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 17:12:39.569  7046  7508 D BluetoothAdapterProperties: Setting state to 12
09-09 17:12:39.569  7046  7579 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:12:39.569  7046  7508 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:12:39.569  7046  7579 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:12:39.569  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:39.570  7046  7512 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 17:12:39.570  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 17:12:39.570  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-09 17:12:39.570  7046  7512 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:12:39.572  7046  7508 I BluetoothAdapterState: Entering On State
09-09 17:12:39.576  7046  7579 D bt_hci_bdroid: Used up Tx Cmd credits
,09-09 17:12:39.579  7046  7608 E bt_mct  : hci lib postload completed
09-09 17:12:39.582  7046  7508 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 17:12:39.582  7046  7508 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 17:12:39.582  7046  7508 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 17:12:39.583  7046  7508 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 17:12:39.586  6932  6947 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:12:39.586  6932  6947 D BluetoothPan: onBluetoothStateChange call bindService
09-09 17:12:39.596  7046  7577 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:39.596  7046  7577 W bt-smp  : Plain text(LSB ~ MSB) = e3 6e 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:39.596  7046  7577 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 1b 25 66 8a 4e 64 f0 97 b3 95 84 3e 1b a1 17 
09-09 17:12:39.596  7046  7577 W bt-btm  : Stopping oneshot timer
,09-09 17:12:39.640  7046  7508 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-09 17:12:39.656  7618  7618 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-09 17:12:39.663  7046  7577 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:39.663  7046  7577 W bt-smp  : Plain text(LSB ~ MSB) = f3 84 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:39.663  7046  7577 W bt-smp  : Encrypted text(LSB ~ MSB) = 84 87 14 94 69 90 2b 4e 5e 0e 10 26 5e 52 61 b7 
09-09 17:12:39.663  7046  7577 W bt-btm  : Stopping oneshot timer
09-09 17:12:39.665  7046  7512 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:12:39.665  7046  7512 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 17:12:39.667  1882  4446 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:39.670  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:39.672  1882  1882 D BluetoothHeadset: Proxy object connected
09-09 17:12:39.672  1037  1037 D BluetoothHeadset: Proxy object connected
,09-09 17:12:39.676  6932  6932 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:12:39.676  6932  6932 D PanProfile: Bluetooth service connected
09-09 17:12:39.682  1882  1898 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:39.685  1882  1882 D BluetoothHeadset: Proxy object connected
,09-09 17:12:39.686  7046  7577 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:39.686  7046  7577 W bt-smp  : Plain text(LSB ~ MSB) = 45 01 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:39.687  7046  7577 W bt-smp  : Encrypted text(LSB ~ MSB) = 48 23 1e d1 15 98 a4 6b c8 e8 ce 07 20 9d 40 c7 
09-09 17:12:39.687  6932  6948 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:12:39.690  1882  2392 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:39.687  7046  7577 W bt-btm  : Stopping oneshot timer
09-09 17:12:39.694  1882  1882 D BluetoothHeadset: Proxy object connected
09-09 17:12:39.695  6932  6947 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 17:12:39.699  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:12:39.704  1037  1037 D BluetoothA2dp: Proxy object connected
09-09 17:12:39.705  6932  6932 D BluetoothInputDevice: Proxy object connected
09-09 17:12:39.705  6932  6932 D HidProfile: Bluetooth service connected
09-09 17:12:39.706  6932  6948 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:12:39.710  1037  1099 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 17:12:39.710  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-09 17:12:39.712  6932  6932 D BluetoothMap: Proxy object connected
,09-09 17:12:39.712  6932  6932 D MapProfile: Bluetooth service connected
09-09 17:12:39.712  6932  6932 D BluetoothMap: getConnectedDevices()
09-09 17:12:39.713  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-09 17:12:39.714  7046  7577 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:39.714  7046  7577 W bt-smp  : Plain text(LSB ~ MSB) = c1 7e 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:39.714  7046  7577 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b 37 d6 76 38 9e dd bb 4f bd ec 7d 87 b5 40 5b 
09-09 17:12:39.714  7046  7577 W bt-btm  : Stopping oneshot timer
09-09 17:12:39.714  7046  7063 V BluetoothMapService: getConnectedDevices()
09-09 17:12:39.715  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.715  1978  2179 D LGBluetoothAPIService: Message: 1
09-09 17:12:39.715  1978  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 17:12:39.716  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:12:39.721  1037  1099 D BluetoothManagerService: Message: 40
09-09 17:12:39.721  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 17:12:39.725  6717  6717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,09-09 17:12:39.728  7046  7046 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.729  7046  7046 D BluetoothMapService: STATE_ON
09-09 17:12:39.734  1978  2179 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-09 17:12:39.736  6932  6932 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:39.742  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:39.744  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:39.747  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:39.747  7046  7046 V BluetoothPbapService: Pbap Service onCreate
09-09 17:12:39.747  7046  7046 V BluetoothPbapService: Starting PBAP service
09-09 17:12:39.748  1037  1099 D BluetoothManagerService: Message: 30
09-09 17:12:39.749  7046  7046 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 17:12:39.749  7046  7046 V BluetoothPbapService: Pbap Service onBind
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:39.749  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:39.750  7046  7046 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.750  7046  7046 V BluetoothPbapService: state: 12
09-09 17:12:39.750  7046  7046 V BluetoothMapService: Handler(): got msg=1
09-09 17:12:39.751  7046  7046 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 17:12:39.752  7046  7046 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 17:12:39.753  7046  7046 D LGBluetoothAPIServer: [BTUI] onBind()
09-09 17:12:39.753  7046  7046 V BluetoothPbapService: Handler(): got msg=1
09-09 17:12:39.754  1978  1978 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 17:12:39.754  7046  7046 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 17:12:39.754  1978  2179 D LGBluetoothAPIService: Message: 100
09-09 17:12:39.754  1978  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-09 17:12:39.755  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:39.755  6932  6932 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 17:12:39.758  7046  7634 V BluetoothPbapService: Pbap Service initSocket
09-09 17:12:39.759  7046  7633 D BluetoothMapMasInstance: MAS initSocket()
09-09 17:12:39.762  1037  1099 D BluetoothManagerService: Message: 30
09-09 17:12:39.763  7046  7633 D BluetoothMapMasInstance:   masId = 00
09-09 17:12:39.763  7046  7633 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 17:12:39.763  7046  7633 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 17:12:39.763  7046  7633 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 17:12:39.766  1037  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:12:39.766  1037  2095 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:39.769  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-09 17:12:39.771  7046  7633 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:39.771  7046  7634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:39.773  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:12:39.774  7046  7634 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 17:12:39.775  7046  7634 V BluetoothPbapService: Succeed to create listening socket 
09-09 17:12:39.775  7046  7634 V BluetoothPbapService: Accepting socket connection...
09-09 17:12:39.776  7046  7512 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:12:39.776  7046  7512 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 17:12:39.779  6932  6932 D BluetoothPbap: Proxy object connected
,09-09 17:12:39.780  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:39.782  6932  6932 D PbapServerProfile: Bluetooth service connected
09-09 17:12:39.782  6932  6932 D BluetoothA2dp: Proxy object connected
09-09 17:12:39.783  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:39.783  7046  7633 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 17:12:39.783  6932  6932 D A2dpProfile: Bluetooth service connected
09-09 17:12:39.783  7046  7633 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 17:12:39.783  7046  7633 D BluetoothMapMasInstance: Accepting socket connection...
09-09 17:12:39.786  7046  7046 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:12:39.786  7046  7046 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.786  7046  7046 V BluetoothPbapReceiver: ***********state = 12
09-09 17:12:39.787  6932  6932 D BluetoothHeadset: Proxy object connected
09-09 17:12:39.788  6932  6932 D HeadsetProfile: Bluetooth service connected
09-09 17:12:39.789  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:39.790  2206  2206 D c       : Getting all permits...
09-09 17:12:39.790  2206  2206 D a       : Opening database...
09-09 17:12:39.793  2206  2206 D a       : Opening database auth.proximity.permit_store...
09-09 17:12:39.793  2206  2206 D a       : Closing database...
,09-09 17:12:39.794  6932  6932 D DockEventReceiver: finishStartingService: stopping service
09-09 17:12:39.803  6932  6932 D BluetoothPermissionRequest: onReceive
09-09 17:12:39.805  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 17:12:39.806  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 17:12:39.809  7046  7046 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-09 17:12:39.810  7046  7046 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-09 17:12:39.815  7046  7046 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-09 17:12:39.826  7275  7306 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 17:12:39.835  7046  7046 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:12:39.835  7046  7046 V BtOppService: onCreate
,09-09 17:12:39.840  7046  7046 V BluetoothOppNotification: send message
09-09 17:12:39.843  7046  7046 V BtOppService: Starting RfcommListener
09-09 17:12:39.846  7046  7046 D BluetoothOppPreference: Dumping Names:  
09-09 17:12:39.846  7046  7046 D BluetoothOppPreference: {}
09-09 17:12:39.846  7046  7046 D BluetoothOppPreference: Dumping Channels:  
09-09 17:12:39.846  7046  7046 D BluetoothOppPreference: {}
09-09 17:12:39.847  7046  7046 V BtOppService: onStartCommand
09-09 17:12:39.848  7046  7655 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:12:39.849  7046  7046 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.849  7046  7046 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-09 17:12:39.852  7046  7046 V BluetoothOppNotification: new notify threadi!
09-09 17:12:39.852  7046  7046 V BluetoothOppNotification: send delay message
09-09 17:12:39.853  7046  7655 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:12:39.853  7046  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 17:12:39.853  7046  7046 V BtOppService: start RfcommListener
09-09 17:12:39.855  7046  7655 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@335ec0ea on behalf of 
09-09 17:12:39.855  7046  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d1b9fdb on behalf of 
09-09 17:12:39.857  7046  7655 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 17:12:39.857  7046  7656 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 17:12:39.857  7046  7652 V BtOppService: Deleted complete outbound shares, number =  0
09-09 17:12:39.857  7046  7046 V BtOppService: RfcommListener started
09-09 17:12:39.857  7046  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:12:39.858  7046  7657 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 17:12:39.858  1037  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:39.859  7046  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dd9fa78 on behalf of 
09-09 17:12:39.859  7046  7652 V BtOppService: Deleted complete inbound failed shares, number = 0
09-09 17:12:39.859  7046  7656 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-09 17:12:39.860  7046  7652 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 17:12:39.860  7046  7652 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f06551 on behalf of 
09-09 17:12:39.861  7046  7656 V BluetoothOppNotification: outbound notification was removed.
09-09 17:12:39.861  7046  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-09 17:12:39.863  7046  7657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:39.865  7046  7657 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-09 17:12:39.865  7046  7657 V BtOppRfcommListener: Started RFCOMM listener....
09-09 17:12:39.865  7046  7657 I BtOppRfcommListener: Accept thread started.
09-09 17:12:39.865  7046  7657 V BtOppRfcommListener: Accepting connection...
09-09 17:12:39.866  7046  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12e001b6 on behalf of 
09-09 17:12:39.867  7046  7656 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 17:12:39.868  7046  7656 V BluetoothOppNotification: inbound notification was removed.
09-09 17:12:39.868  7046  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 17:12:39.869  7046  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12aa5eb7 on behalf of 
09-09 17:12:39.872  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:39.872  7046  7046 V BluetoothFtpService: Ftp Service onCreate
09-09 17:12:39.872  7046  7046 I BluetoothFtpService: Ftp Service onCreate
09-09 17:12:39.873  7046  7046 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:12:39.873  7046  7046 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.873  7046  7046 V BluetoothFtpService: Starting Listening on sockets
09-09 17:12:39.873  7046  7046 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:39.873  7046  7046 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:39.873  7046  7046 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:39.873  7046  7046 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.873  7046  7046 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 17:12:39.874  7046  7046 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-09 17:12:39.875  7046  7046 V BtOppService: ContentObserver received notification
09-09 17:12:39.876  7046  7046 V BtOppService: ContentObserver received notification
09-09 17:12:39.876  7046  7046 V BluetoothFtpService: Handler(): got msg=1
09-09 17:12:39.876  7046  7046 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 17:12:39.876  7046  7046 V BluetoothFtpService: Ftp Service initSocket
09-09 17:12:39.879  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:39.880  7046  7046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:39.881  7046  7658 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:12:39.881  7046  7658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:12:39.883  7046  7658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1685058d on behalf of 
09-09 17:12:39.883  7046  7046 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-09 17:12:39.883  7046  7046 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-09 17:12:39.883  7046  7658 V BluetoothOppNotification: update too frequent, put in queue
09-09 17:12:39.884  7046  7658 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 17:12:39.887  7046  7659 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 17:12:39.904  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:39.904  7046  7046 V BluetoothSapService: Sap Service onCreate
,09-09 17:12:39.907  7046  7046 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:39.907  7046  7046 V BluetoothSapService: state: 12
09-09 17:12:39.907  7046  7046 V BluetoothSapService: Starting SAP server process
09-09 17:12:39.908  7046  7046 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 17:12:39.899  7660  7660 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:39.899  7660  7660 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:39.910  7046  7661 V BluetoothSapService: Sap Service initRfcommSocket
09-09 17:12:39.911  1037  2328 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:39.913  7046  7661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:39.914  7046  7661 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-09 17:12:39.914  7046  7661 V BluetoothSapService: Succeed to create listening socket 
09-09 17:12:39.914  7046  7661 V BluetoothSapService: Accepting socket connection...
09-09 17:12:39.941  7660  7660 V BT_SAP  : Event pipe created
09-09 17:12:39.941  7660  7660 V BT_SAP  : create_server_socket qcom.sap.server
09-09 17:12:39.941  7660  7660 V BT_SAP  : created socket fd 6
,09-09 17:12:40.057  1037  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b615ab1 type 2 when 128918 com.google.android.gms} when 128918
,09-09 17:12:40.388  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:12:40.388  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:12:40.428  1037  1540 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-09 17:12:40.429  1037  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-09 17:12:40.731  1037  2054 I ActivityManager: Killing 7436:com.lge.bnr/1000 (adj 15): empty #17
,09-09 17:12:40.765  1037  2095 W libprocessgroup: failed to open /acct/uid_1000/pid_7436/cgroup.procs: No such file or directory
,09-09 17:12:40.854  7046  7046 V BluetoothOppNotification: new notify threadi!
09-09 17:12:40.854  7046  7046 V BluetoothOppNotification: send delay message
,09-09 17:12:40.859  1037  2328 I ActivityManager: Killing 6959:com.lge.sync/1000 (adj 15): empty #17
,09-09 17:12:40.868  7046  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-09 17:12:40.884  1037  1546 D WifiService: Client connection lost with reason: 4
,09-09 17:12:40.887  7046  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a496d89 on behalf of 
09-09 17:12:40.888  7046  7672 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 17:12:40.889  7046  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:12:40.890  7046  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@199918e on behalf of 
09-09 17:12:40.891  7046  7672 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 17:12:40.893  7046  7672 V BluetoothOppNotification: outbound notification was removed.
09-09 17:12:40.893  7046  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 17:12:40.894  7046  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a906daf on behalf of 
09-09 17:12:40.894  7046  7672 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 17:12:40.898  7046  7672 V BluetoothOppNotification: inbound notification was removed.
,09-09 17:12:40.898  7046  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-09 17:12:40.900  7046  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@154435bc on behalf of 
,09-09 17:12:40.904  1037  2007 W libprocessgroup: failed to open /acct/uid_1000/pid_6959/cgroup.procs: No such file or directory
,09-09 17:12:41.355  1037  1718 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:12:41.356  1037  1718 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@17fbbb96 mBinding = false,
,09-09 17:12:41.387  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:12:41.388  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:12:41.388  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,09-09 17:12:41.391  1037  1099 D BluetoothManagerService: Message: 2
09-09 17:12:41.392  1037  1099 D BluetoothManagerService: Sending off request.
09-09 17:12:41.393  7046  7631 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 17:12:41.394  7046  7508 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 17:12:41.394  7046  7508 D BluetoothAdapterProperties: Setting state to 13
09-09 17:12:41.394  7046  7508 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 17:12:41.395  7046  7508 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:12:41.395  7046  7508 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 17:12:41.398  7046  7512 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:12:41.400  7046  7508 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-09 17:12:41.405  7046  7508 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:12:41.407  7046  7634 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:41.408  7046  7657 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:41.409  7046  7659 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:41.409  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 17:12:41.409  7046  7577 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 17:12:41.410  7046  7633 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 17:12:41.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 17:12:41.412  7046  7577 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:12:41.423  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:41.423  6717  6717 V io.jxcore.node.ConnectivityMonito,r:     - active network type is Wi-Fi: false
,09-09 17:12:41.429  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:41.429  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:41.432  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:41.432  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:41.434  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:41.434  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:41.435  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:41.435  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 17:12:41.435  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-09 17:12:41.439  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.442  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:12:41.448  7046  7046 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.448  7046  7046 D BluetoothMapService: STATE_TURNING_OFF
09-09 17:12:41.448  7046  7046 V BluetoothMapService: Handler(): got msg=4
09-09 17:12:41.449  7046  7046 D BluetoothMapService: MAP Service closeService in
,09-09 17:12:41.449  7046  7046 D BluetoothMapMasInstance: MAP Service shutdown
09-09 17:12:41.451  7046  7046 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:12:41.451  7046  7046 V BluetoothMapService: MAP Service closeService out
09-09 17:12:41.453  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:41.453  7046  7046 V BtOppService: Receiver DISABLED_ACTION 
09-09 17:12:41.453  7046  7046 I BtOppRfcommListener: stopping Accept Thread
09-09 17:12:41.454  7046  7046 V BtOppRfcommListener: close mBtServerSocket
09-09 17:12:41.454  7046  7657 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:12:41.455  7046  7046 V BtOppRfcommListener: waiting for thread to terminate
09-09 17:12:41.455  7046  7046 V BtOppRfcommListener: done waiting for thread to terminate
09-09 17:12:41.457  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:41.460  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-09 17:12:41.463  7046  7661 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 17:12:41.471  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:12:41.473  7046  7046 V BtOppService: onDestroy
09-09 17:12:41.474  7046  7046 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 17:12:41.479  7046  7046 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:12:41.479  7046  7046 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.480  7046  7046 V BluetoothPbapReceiver: ***********state = 13
,09-09 17:12:41.484  7046  7046 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 17:12:41.486  7046  7046 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.486  7046  7046 V BluetoothPbapService: state: 13
09-09 17:12:41.486  7046  7046 V BluetoothPbapService: Pbap Service closeService in
09-09 17:12:41.489  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:41.490  7046  7046 V BluetoothPbapService: successfully stopped pbap service
09-09 17:12:41.490  7046  7046 V BluetoothPbapService: Pbap Service closeService out
09-09 17:12:41.491  7046  7046 V BluetoothPbapService: Pbap Service onDestroy
09-09 17:12:41.491  7046  7046 V BluetoothPbapService: Pbap Service closeService in
09-09 17:12:41.491  7046  7046 V BluetoothPbapService: Pbap Service closeService out
09-09 17:12:41.491  7046  7046 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-09 17:12:41.512  6932  6932 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:41.519  6932  6932 D BluetoothPbap: Proxy object disconnected
,09-09 17:12:41.519  6932  6932 D PbapServerProfile: Bluetooth service disconnected
09-09 17:12:41.533  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 17:12:41.540  6932  6932 D BluetoothPermissionRequest: onReceive
09-09 17:12:41.540  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 17:12:41.549  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 17:12:41.556  7046  7046 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 17:12:41.556  7046  7046 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-09 17:12:41.557  7046  7046 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 17:12:41.562  7046  7046 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.562  7046  7046 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-09 17:12:41.566  7046  7046 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:12:41.566  7046  7046 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.567  7046  7046 V BluetoothFtpService: Ftp Service closeService
09-09 17:12:41.567  7046  7046 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 17:12:41.570  7046  7046 V BluetoothFtpService: successfully stopped ftp service
09-09 17:12:41.571  7046  7046 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:41.571  7046  7046 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:41.571  7046  7046 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:41.571  7046  7046 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.571  7046  7046 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 17:12:41.571  7046  7046 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 17:12:41.572  7046  7046 V BluetoothFtpService: Ftp Service onDestroy
09-09 17:12:41.572  7046  7046 V BluetoothFtpService: Ftp Service closeService
09-09 17:12:41.579  7046  7046 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:41.579  7046  7046 V BluetoothSapService: state: 13
09-09 17:12:41.579  7046  7046 V BluetoothSapService: Stopping SAP server process
09-09 17:12:41.581  7046  7046 V BluetoothSapService: Sap Service closeSapService in
09-09 17:12:41.582  7046  7046 V BluetoothSapService: Close listen Socket : 
09-09 17:12:41.582  7046  7046 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:12:41.582  7046  7046 V BluetoothSapService: Close sapd  Socket : 
,09-09 17:12:41.585  7046  7046 V BluetoothSapService: Sap Service closeSapService out
09-09 17:12:41.586  7046  7046 V BluetoothSapService: Sap Service onDestroy
09-09 17:12:41.586  7046  7046 V BluetoothSapService: Sap Service closeSapService in
09-09 17:12:41.586  7046  7046 V BluetoothSapService: Close listen Socket : 
09-09 17:12:41.586  7046  7046 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:12:41.586  7046  7046 V BluetoothSapService: Close sapd  Socket : 
09-09 17:12:41.587  7046  7046 V BluetoothSapService: Sap Service closeSapService out
09-09 17:12:41.733  1037  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39e04304 type 2 when 130594 com.google.android.gms} when 130594
,09-09 17:12:41.744   328  7693 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-09 17:12:41.745  1037  1097 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-09 17:12:42.401  7046  7512 D bt_hci_bdroid: cleanup
,09-09 17:12:42.409  7046  7608 I bt_userial_mct: exiting userial_read_thread
09-09 17:12:42.409  7046  7608 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 17:12:42.409  7046  7579 I bt_lpm  : LPM is already off!!!
09-09 17:12:42.410  7046  7577 W bt-btif : ag scb idx 1 not allocated
09-09 17:12:42.411  7046  7577 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:12:42.411  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:42.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:12:42.412  7046  7577 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:42.412  7046  7577 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:12:42.412  7046  7577 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:12:42.412  7046  7577 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:12:42.415  7046  7512 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 17:12:42.415  7046  7579 I bt_vendor: hw_epilog_process
09-09 17:12:42.415  7046  7512 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 17:12:42.415  7046  7512 D bt_userial_mct: userial_close
09-09 17:12:42.415  7046  7512 E bt_userial_mct: pthread_join() FAILED result:3
09-09 17:12:42.415  7046  7512 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 17:12:42.423  7046  7512 D bt_hci_bdroid: set_power 0
09-09 17:12:42.423  7046  7512 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 17:12:42.423  7046  7512 I bt_vendor: bluetooth satus is on
09-09 17:12:42.423  7046  7512 I bt_vendor: bt-vendor : resetting BT status
09-09 17:12:42.423  7046  7512 I bt_vendor: Starting hciattach daemon
09-09 17:12:42.423  7046  7512 I bt_vendor: try to set false
,09-09 17:12:42.430  7046  7512 I bt_vendor: Starting hciattach daemon
09-09 17:12:42.430  7046  7512 I bt_vendor: try to set false
09-09 17:12:42.431  7046  7512 I bt_vendor: cleanup
09-09 17:12:42.432  7046  7577 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 17:12:42.432  7046  7512 I GKI_LINUX: GKI_exit_task 0 done
09-09 17:12:42.432  7046  7512 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 17:12:42.434  7046  7508 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 17:12:42.438  7046  7046 D HeadsetService: Received stop request...Stopping profile...
,09-09 17:12:42.442  7046  7046 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:12:42.443  7046  7046 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:42.443  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:42.443  7046  7543 D HeadsetStateMachine: Exit Disconnected: -1
09-09 17:12:42.447  1882  1882 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:42.447  1882  1882 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:42.448  1882  1882 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:42.449  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:42.449  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 17:12:42.450  7046  7046 D A2dpService: Received stop request...Stopping profile...
,09-09 17:12:42.453  7046  7569 D A2dpStateMachine: Exit Disconnected: -1
09-09 17:12:42.456  7046  7046 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 17:12:42.459  7046  7508 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 17:12:42.459  7046  7046 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 17:12:42.459  7046  7046 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:42.459  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:42.461  1037  1037 D BluetoothA2dp: Proxy object disconnected
09-09 17:12:42.461  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 17:12:42.462  7046  7046 D HidService: Received stop request...Stopping profile...
09-09 17:12:42.462  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
,09-09 17:12:42.468  7046  7046 D HeadsetStateMachine: Unbinding service...
09-09 17:12:42.469  7046  7046 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:12:42.469  7046  7046 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:12:42.469  7046  7046 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:12:42.469  7046  7046 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:12:42.470  7046  7046 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:12:42.470  7046  7046 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:42.470  7046  7046 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:12:42.471  7046  7046 D HealthService: Received stop request...Stopping profile...
09-09 17:12:42.471  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:42.473  7046  7046 D PanService: Received stop request...Stopping profile...
09-09 17:12:42.474  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
,09-09 17:12:42.477  7046  7046 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:12:42.478  7046  7046 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 17:12:42.478  7046  7046 D BtGatt.GattService: stop()
09-09 17:12:42.478  7046  7046 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 17:12:42.479  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:42.481  7046  7046 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:12:42.481  7046  7046 D BluetoothMapService: stop()
09-09 17:12:42.482  7046  7046 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 17:12:42.482  7046  7046 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 17:12:42.483  7046  7046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a4fc9
09-09 17:12:42.484  7046  7046 V BluetoothMapService: Handler(): got msg=4
09-09 17:12:42.484  7046  7046 D BluetoothMapService: MAP Service closeService in
09-09 17:12:42.484  7046  7046 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:12:42.484  7046  7046 V BluetoothMapService: MAP Service closeService out
09-09 17:12:42.485  7046  7508 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 17:12:42.485  7046  7508 D BluetoothAdapterProperties: Setting state to 10
09-09 17:12:42.485  7046  7508 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:12:42.485  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:42.486  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 17:12:42.486  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,09-09 17:12:42.488  7046  7508 I BluetoothAdapterState: Entering OffState
09-09 17:12:42.489  6932  7409 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:12:42.490  7046  7046 I BluetoothA2dpServiceJni: cleanupNative
09-09 17:12:42.490  7046  7570 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 17:12:42.492  7046  7046 I GKI_LINUX: GKI_exit_task 2 done
09-09 17:12:42.492  7046  7046 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 17:12:42.493  1882  4446 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:42.493  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:42.494  6932  7409 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:42.495  7046  7046 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:12:42.495  7046  7046 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:12:42.496  7046  7046 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:12:42.496  7046  7046 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:12:42.496  7046  7046 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:12:42.497  1882  4447 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:42.497  6932  7409 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 17:12:42.502  6932  7409 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:12:42.504  7046  7046 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:12:42.505  7046  7046 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:12:42.506  1882  1897 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:42.507  6932  7409 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:12:42.508  7046  7046 D BluetoothMapService: cleanup()
09-09 17:12:42.508  7046  7046 D BluetoothMapService: MAP Service closeService in
09-09 17:12:42.508  7046  7046 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:12:42.508  7046  7046 V BluetoothMapService: MAP Service closeService out
09-09 17:12:42.509  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:12:42.511  6932  7409 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:12:42.512  1037  1099 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 17:12:42.512  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 17:12:42.514  1037  1099 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 17:12:42.514  1037  1099 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 17:12:42.515  1037  1099 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@17fbbb96 mBinding = false
09-09 17:12:42.516  1037  1099 D BluetoothManagerService: Sending unbind request.
09-09 17:12:42.521  7046  7512 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 17:12:42.523  7046  7046 I GKI_LINUX: GKI_exit_task 1 done
09-09 17:12:42.523  7046  7046 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 17:12:42.523  7046  7046 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 17:12:42.523  7046  7046 I art     : --- WEIRD: removing null entry 248
09-09 17:12:42.523  7046  7046 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-09 17:12:42.524  7046  7046 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 17:12:42.525  7046  7046 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 17:12:42.526  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 17:12:42.529  7046  7046 I art     : System.exit called, status: 0
09-09 17:12:42.529  7046  7046 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 17:12:42.549   333  1388 V AudioFlinger: 7046 died, releasing its sessions
09-09 17:12:42.549   333  1388 V AudioFlinger:  pid 1882 @ 0
09-09 17:12:42.549   333  1388 V AudioFlinger:  pid 3411 @ 1
09-09 17:12:42.549   333  1388 V AudioFlinger:  pid 3411 @ 2
,09-09 17:12:42.555  1978  1978 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-09 17:12:42.556  1978  2179 D LGBluetoothAPIService: Message: 101
09-09 17:12:42.556  1978  2179 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
,09-09 17:12:42.556  1978  2179 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-09 17:12:42.557  1978  2179 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-09 17:12:42.559  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 17:12:42.703  1037  2010 I ActivityManager: Process com.android.bluetooth (pid 7046) has died
09-09 17:12:42.703  1037  2010 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-09 17:12:42.704  1037  2010 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-09 17:12:42.714  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-09 17:12:42.716  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:42.717  1978  2179 D LGBluetoothAPIService: Message: 2
09-09 17:12:42.717  1978  2179 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-09 17:12:42.718  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 17:12:42.718  6932  6932 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 17:12:42.720  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:42.722  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:42.728  1606  1606 D BluetoothAdapter: 574249320: getState() :  mService = null. Returning STATE_OFF
09-09 17:12:42.728  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:12:42.728  1606  1606 D BluetoothAdapter: 574249320: getState() :  mService = null. Returning STATE_OFF
,09-09 17:12:42.793  1037  2007 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7724 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 17:12:42.796  6932  6932 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:42.890  7724  7724 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-09 17:12:42.891  7724  7724 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:12:42.891  7724  7724 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 17:12:42.892  7724  7724 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:12:42.913  7724  7724 D BluetoothAdapterApp: Loading JNI Library
,09-09 17:12:42.953  7724  7724 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@fa83f91 Instance Count = 1
,09-09 17:12:43.042  1037  1095 I art     : Explicit concurrent mark sweep GC freed 84500(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.422ms total 176.235ms
,09-09 17:12:43.047  7724  7724 D BluetoothAdapterApp: onCreate
09-09 17:12:43.067  7724  7724 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-09 17:12:43.067  7724  7724 D ProfileConfigQcom: Adding HeadsetService
09-09 17:12:43.067  7724  7724 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-09 17:12:43.067  7724  7724 D ProfileConfigQcom: Adding A2dpService
09-09 17:12:43.068  7724  7724 D ProfileConfigQcom: [BTUI] HidService is supported
09-09 17:12:43.068  7724  7724 D ProfileConfigQcom: Adding HidService
09-09 17:12:43.068  7724  7724 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 17:12:43.068  7724  7724 D ProfileConfigQcom: Adding HealthService
09-09 17:12:43.068  7724  7724 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 17:12:43.069  7724  7724 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 17:12:43.070  7724  7724 D ProfileConfigQcom: Adding PanService
09-09 17:12:43.070  7724  7724 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 17:12:43.070  7724  7724 D ProfileConfigQcom: Adding GattService
09-09 17:12:43.070  7724  7724 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 17:12:43.070  7724  7724 D ProfileConfigQcom: Adding BluetoothMapService
09-09 17:12:43.071  7724  7724 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 17:12:43.071  7724  7724 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:12:43.073  7724  7724 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:43.073  7724  7724 V BluetoothPbapReceiver: ***********state = 10
09-09 17:12:43.074  7724  7724 V LGMDMManagerInternal: Create singleton instance
09-09 17:12:43.141  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:12:43.145  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 17:12:43.146  7724  7724 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 17:12:43.146  7724  7724 D LGBluetoothAPIServer: [BTUI] onBind()
09-09 17:12:43.153  1978  1978 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 17:12:43.153  1978  2179 D LGBluetoothAPIService: Message: 100
09-09 17:12:43.153  1978  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-09 17:12:43.164  6932  6932 D BluetoothPermissionRequest: onReceive
09-09 17:12:43.168  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 17:12:43.168  6932  6932 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-09 17:12:43.171  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:12:43.178  7724  7724 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-09 17:12:43.184  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:43.194  7724  7724 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:43.194  7724  7724 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:43.195  7724  7724 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:43.197  7724  7724 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:43.197  7724  7724 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-09 17:12:43.202  7006  7006 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-09 17:12:44.467  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:12:44.467  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:44.531  1606  1606 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 17:12:44.568  1037  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 17:12:44.651  1037  1095 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7752 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 17:12:44.658  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 17:12:44.658  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 17:12:44.678  1037  1037 D administrator: Handling package changes for user 0
09-09 17:12:44.678  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 17:12:44.708  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 17:12:44.734  7752  7752 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 17:12:44.794  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 17:12:44.794  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 17:12:44.828  7752  7752 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:44.828  7752  7752 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:44.856  1037  1094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:12:44.865  1037  1094 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 17:12:44.897  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 17:12:44.901  2471  2471 V GmsNetworkLocationProvi: DISABLE
,09-09 17:12:44.948  1037  1094 D LocationProviderProxy: applying state to connected service
,09-09 17:12:44.950  2471  2471 E GCoreFlp: Bound FusedProviderService with LocationManager
09-09 17:12:44.987  7752  7797 I Babel   : MmsConfig: mnc/mcc: 0/0
09-09 17:12:44.987  7752  7797 I Babel   : MmsConfig.loadMmsSettings
,09-09 17:12:44.991  7752  7797 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 17:12:44.992  7752  7797 I Babel   : MmsConfig.loadFromDatabase
,09-09 17:12:45.016  7752  7797 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-09 17:12:45.016  7752  7797 I Babel   : MmsConfig.loadFromResources
09-09 17:12:45.018  7752  7797 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-09 17:12:45.019  7752  7797 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-09 17:12:45.034  7752  7752 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:12:45.069  1037  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{10f475db type 2 when 133932 com.google.android.gms} when 133932
,09-09 17:12:45.078  1846  7799 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 17:12:45.078  1846  7799 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-09 17:12:45.081  7752  7795 W AudioCapabilities: Unsupported mime audio/evrc
09-09 17:12:45.083  7752  7795 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 17:12:45.089  7752  7795 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 17:12:45.090  7113  7113 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:12:45.092  1846  4780 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-09 17:12:45.105  7113  7113 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@dfb3793
09-09 17:12:45.105  7113  7113 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:12:45.105  7113  7113 D AppUp4:CustFacade: isPhone : true
,09-09 17:12:45.108  7113  7113 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:12:45.108  7113  7113 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 17:12:45.127  7752  7795 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-09 17:12:45.130  7752  7795 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 17:12:45.132  7752  7795 W AudioCapabilities: Unsupported mime audio/evrc
09-09 17:12:45.146  7752  7795 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 17:12:45.148  1037  2010 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7802 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-09 17:12:45.149  7752  7795 W VideoCapabilities: Unsupported mime video/divx
09-09 17:12:45.151  7752  7795 W VideoCapabilities: Unsupported mime video/divx311
09-09 17:12:45.154  1037  2095 I ActivityManager: Killing 7146:com.lge.email/u0a23 (adj 15): empty #17
09-09 17:12:45.155  7752  7795 W VideoCapabilities: Unsupported mime video/divx4
09-09 17:12:45.160  7752  7795 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 17:12:45.179  7752  7795 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 17:12:45.184  7752  7795 W AudioCapabilities: Unsupported mime audio/eac3
09-09 17:12:45.185  7752  7795 W AudioCapabilities: Unsupported mime audio/ac3
09-09 17:12:45.186  7752  7795 W AudioCapabilities: Unsupported mime audio/g726
09-09 17:12:45.187  7752  7795 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 17:12:45.188  7752  7795 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 17:12:45.189  7752  7795 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 17:12:45.191  7752  7795 W VideoCapabilities: Unsupported mime video/theora
,09-09 17:12:45.193  7752  7795 W VideoCapabilities: Unsupported mime video/mjpg
,09-09 17:12:45.258  1037  1786 W libprocessgroup: failed to open /acct/uid_10023/pid_7146/cgroup.procs: No such file or directory
09-09 17:12:45.281  7802  7802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:45.282  7802  7802 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:12:45.282  7802  7802 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-09 17:12:45.284  7802  7802 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 17:12:45.284  7802  7802 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 17:12:45.385  7802  7802 I SystemConfig: BUILD Country: EU
09-09 17:12:45.385  7802  7802 I SystemConfig: BUILD Operator: OPEN
,09-09 17:12:45.433  1037  2010 I ActivityManager: Killing 7029:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-09 17:12:45.508  1037  2018 W libprocessgroup: failed to open /acct/uid_10026/pid_7029/cgroup.procs: No such file or directory
,09-09 17:12:45.526  7802  7823 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 17:12:45.526  7802  7823 I SystemConfig: existFile = false
09-09 17:12:45.526  7802  7823 I SystemConfig: canReadFile = false
09-09 17:12:45.526  7802  7823 I SystemConfig: systemFeature RCS result false
09-09 17:12:45.527  7802  7823 D SystemConfig: refreshRcsSupport() :false
,09-09 17:12:45.576  1037  2010 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7826 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 17:12:45.640  7826  7826 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:45.640  7826  7826 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 17:12:45.641  7826  7826 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 17:12:45.641  7826  7826 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 17:12:45.719  7826  7826 I AppConfig: Total System Memory = 2995761152
,09-09 17:12:45.740  7826  7826 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-09 17:12:45.835  1037  1987 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7845 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:12:45.836  1037  1987 I ActivityManager: Killing 6523:com.wsandroid.suite.lge/1000 (adj 15): empty #17
09-09 17:12:45.924  1037  1718 W libprocessgroup: failed to open /acct/uid_1000/pid_6523/cgroup.procs: No such file or directory
,09-09 17:12:46.143  7845  7845 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-09 17:12:46.250  7845  7845 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:46.250  7845  7845 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:12:46.305  7845  7845 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-09 17:12:46.326  7845  7845 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 17:12:46.327  7845  7845 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 17:12:46.342  7845  7845 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-09 17:12:46.343  7845  7845 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-09 17:12:46.365  1037  2095 I ActivityManager: Killing 7182:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-09 17:12:46.397  3458  6315 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-09 17:12:46.402  3458  6315 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@bc8cb06 on behalf of 7845
09-09 17:12:46.403  1037  1780 W libprocessgroup: failed to open /acct/uid_10046/pid_7182/cgroup.procs: No such file or directory
09-09 17:12:46.406  4614  7885 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-09 17:12:46.439  1037  1780 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7886 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 17:12:46.478  7845  7845 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-09 17:12:46.498  7845  7845 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-09 17:12:46.526  7886  7886 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 17:12:46.550  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-09 17:12:46.550  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-09 17:12:46.550  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 17:12:46.550  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 17:12:46.550  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-09 17:12:46.550  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-09 17:12:46.565   328  7917 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-09 17:12:46.567  1037  1097 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 17:12:46.570  1037  2010 I ActivityManager: Killing 7201:com.android.chrome/u0a57 (adj 15): empty #17
09-09 17:12:46.699  1037  1577 W libprocessgroup: failed to open /acct/uid_10057/pid_7201/cgroup.procs: No such file or directory
,09-09 17:12:46.980  1037  1780 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:47.005  4614  7885 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 599 ms] updated apps [took 599 ms] 
,09-09 17:12:47.477  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:12:47.477  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d6470ad added. We now have 6 listener(s)
09-09 17:12:47.477  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:47.486  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:47.486  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e6dfe2 added. We now have 7 listener(s)
09-09 17:12:47.486  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:47.487  6717  6820 I System.out: IsBluetoothEnabled
09-09 17:12:47.488  1037  2328 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:47.488  1037  2328 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-09 17:12:47.489  1037  1099 D BluetoothManagerService: Message: 2
09-09 17:12:47.492  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:47.492  1037  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:47.492  1037  2010 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-09 17:12:47.508  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:12:47.509  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:12:47.509  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-09 17:12:47.510  1037  1099 D BluetoothManagerService: Message: 1
09-09 17:12:47.510  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-09 17:12:47.534  1037  1099 D BluetoothManagerService: Message: 20
09-09 17:12:47.534  1037  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@acda631:true
,09-09 17:12:47.538  7724  7724 D BluetoothAdapterState: make
09-09 17:12:47.543  7724  7724 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 17:12:47.543  7724  7724 I bluedroid-qcom: init
09-09 17:12:47.544  7724  7933 I BluetoothAdapterState: Entering OffState
09-09 17:12:47.545  7724  7724 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 17:12:47.545  7724  7724 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 17:12:47.545  7724  7724 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:12:47.545  7724  7724 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 17:12:47.545  7724  7724 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 17:12:47.547  7724  7724 I bluedroid-qcom: get_profile_interface socket
09-09 17:12:47.547  7724  7724 I bluedroid-qcom: get_profile_interface map_client
,09-09 17:12:47.551  7724  7937 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 17:12:47.549  7936  7936 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:47.556  7724  7937 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 17:12:47.549  7936  7936 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:47.565  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-09 17:12:47.568  1037  1099 D BluetoothManagerService: Message: 40
09-09 17:12:47.568  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 17:12:47.571  7936  7936 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 17:12:47.571  7936  7936 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 17:12:47.571  7936  7936 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-09 17:12:47.572  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:12:47.573  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 17:12:47.573  7724  7741 I bluedroid-qcom: config_hci_snoop_log
09-09 17:12:47.574  1037  1099 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 17:12:47.574  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 17:12:47.575  7936  7936 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 17:12:47.580  7936  7936 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 17:12:47.580  7936  7936 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-09 17:12:47.588  7724  7933 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-09 17:12:47.588  7724  7937 D BluetoothAdapterProperties: Name is: G3
09-09 17:12:47.588  7724  7933 D BluetoothAdapterProperties: Setting state to 11
09-09 17:12:47.589  7724  7933 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 17:12:47.589  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:47.589  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 17:12:47.589  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 17:12:47.591  7724  7933 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 17:12:47.596  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:47.599  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:12:47.602  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:47.605  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 17:12:47.610  7724  7724 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:12:47.610  7724  7724 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:47.610  7724  7724 V BluetoothPbapReceiver: ***********state = 11
,09-09 17:12:47.617  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:47.642  7724  7933 D BluetoothBondStateMachine: make
,09-09 17:12:47.645  6932  6932 D BluetoothPermissionRequest: onReceive
09-09 17:12:47.648  7724  7933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:47.648  7724  7933 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 17:12:47.649  7724  7933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:47.649  7724  7933 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 17:12:47.649  7724  7933 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 17:12:47.651  7724  7951 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 17:12:47.653  7724  7933 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:12:47.654  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:12:47.669  7724  7724 D HeadsetService: Received start request. Starting profile...
,09-09 17:12:47.670  7724  7724 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:12:47.670  7724  7724 D LGBluetoothHfpAdapter: Version 1.6
09-09 17:12:47.672  7724  7933 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:12:47.674  7724  7724 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:12:47.675  7724  7724 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:12:47.676  7724  7724 D HeadsetStateMachine: make
09-09 17:12:47.677  7724  7933 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:12:47.683  7724  7933 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:12:47.689  7724  7933 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:12:47.695  7724  7933 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:12:47.701  7724  7933 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:12:47.715  7724  7724 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:47.715  7724  7724 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:12:47.717  7724  7933 V LGMDMManager: Create singleton instance
,09-09 17:12:47.721  7724  7933 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 17:12:47.721  7724  7724 D HeadsetStateMachine: max_hf_connections = 1
09-09 17:12:47.721  7724  7724 I bluedroid-qcom: get_profile_interface handsfree
09-09 17:12:47.724  7724  7724 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-09 17:12:47.725   333   333 V AudioPolicyService: registerClient() client 0xb1021ba0, uid 1002
09-09 17:12:47.725   333  1388 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:12:47.725   333  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:12:47.725   333  1388 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:12:47.725  7724  7724 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 17:12:47.726   333  1389 V AudioFlinger: registerClient() client 0xb55815f8, pid 7724
09-09 17:12:47.726   333  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:47.726   333  1382 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:47.726  7724  7724 V ToneGenerator: Create Track: 0xb4928a80
09-09 17:12:47.726  7724  7724 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 17:12:47.726  7724  7724 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 17:12:47.727   333  1388 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 17:12:47.727   333  1388 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:12:47.727   333  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:12:47.727   333  1388 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:12:47.727  1882  1898 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:47.727  1882  1898 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:47.727   333  1383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:47.727   333  1383 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:47.727  7724  7724 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 17:12:47.727  1037  1987 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:47.727  1037  1987 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:47.727  7724  7741 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:47.727  3411  3427 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:47.727  7724  7741 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 17:12:47.727  3411  3427 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:47.727  1037  2328 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:47.728  1037  2328 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:47.728  1882  4447 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:47.728  1882  4447 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:47.728  3411  4889 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:47.728  3411  4889 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:47.728  7724  7740 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:47.728  7724  7740 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 17:12:47.728   333  1388 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 17:12:47.728   333   333 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 17:12:,47.728   333   333 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 17:12:47.728   333   333 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:12:47.728   333   333 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:12:47.729  7724  7724 V AudioSystem: getLatency() output 2, latency 50
09-09 17:12:47.729  7724  7724 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 17:12:47.729  1606  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:12:47.729  7724  7724 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 17:12:47.729  1606  1943 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:12:47.729  1606  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:12:47.729  1606  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:12:47.729   333  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:12:47.729   333  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:12:47.729   333  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:12:47.729   333  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:12:47.729   333  1389 V AudioFlinger: createTrack() lSessionId: 23
,09-09 17:12:47.731  7724  7724 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 17:12:47.731   333   333 V AudioFlinger: acquiring 23 from 7724, for 7724
09-09 17:12:47.731   333   333 V AudioFlinger:  added new entry for 23
,09-09 17:12:47.731  7724  7724 V ToneGenerator: ToneGenerator INIT OK, time: 136609
09-09 17:12:47.731  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:47.734  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:47.735  7724  7956 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 17:12:47.735  7724  7956 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:12:47.735  7724  7956 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:12:47.736  7724  7956 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 17:12:47.736   333  1389 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7724
09-09 17:12:47.736  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:47.737   333  1389 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 17:12:47.737   333  1389 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 17:12:47.737   333  1389 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 17:12:47.737   333  1389 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 17:12:47.737   333  1389 V voice   : voice_set_parameters: exit with code(0)
09-09 17:12:47.737   333  1389 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 17:12:47.737   333  1389 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 17:12:47.738   333  1389 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 17:12:47.738   333  1389 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 17:12:47.738   333  1389 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 17:12:47.738   333  1389 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 17:12:47.739  7724  7724 D A2dpService: Received start request. Starting profile...
,09-09 17:12:47.740  7724  7724 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 17:12:47.740  7724  7956 V ToneGenerator: ToneGenerator destructor
09-09 17:12:47.740  7724  7956 V ToneGenerator: stopTone
09-09 17:12:47.740  7724  7956 V ToneGenerator: Delete Track: 0xb4928a80
,09-09 17:12:47.741  7724  7956 V AudioTrack: ~AudioTrack, releasing session id from 7724 on behalf of 7724
09-09 17:12:47.741   333  1388 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 17:12:47.741   333  1389 V AudioFlinger: releasing 23 from 7724 for 7724
09-09 17:12:47.741   333  1388 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
,09-09 17:12:47.741   333  1389 V AudioFlinger:  decremented refcount to 0
09-09 17:12:47.741   333  1388 V AudioFlinger: PlaybackThread::Track destructor
09-09 17:12:47.741   333  1230 V AudioPolicyService: AudioCommandThread() waking up
,09-09 17:12:47.741   333  1389 V AudioFlinger: purging stale effects
09-09 17:12:47.741   333  1388 V AudioFlinger: removeClient_l() pid 7724, calling pid 333
09-09 17:12:47.741   333  1230 V AudioPolicyService: AudioCommandThread() processing release output 2
,09-09 17:12:47.741   333  1230 V AudioPolicyManager: releaseOutput() 2
09-09 17:12:47.741  7724  7724 V Avrcp   : make
09-09 17:12:47.741   333  1230 V AudioPolicyService: AudioCommandThread() going to sleep
,09-09 17:12:47.741  7724  7724 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 17:12:47.741  7724  7724 I bluedroid-qcom: get_profile_interface avrcp
09-09 17:12:47.752  7724  7724 V AudioManager: registerRemoteController: size of Media player list: 0
,09-09 17:12:47.754  7724  7724 E AudioManager: No RCC entry present to update
09-09 17:12:47.754  7724  7724 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:12:47.758  7724  7724 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,09-09 17:12:47.760  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 17:12:47.760  7724  7724 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-09 17:12:47.764  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 17:12:47.920  1037  1786 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:12:47.920  1037  1786 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:48.057  1037  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output,
,09-09 17:12:48.067  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 17:12:48.071  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 17:12:48.072  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:12:48.073  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 17:12:48.073  7724  7724 I BluetoothA2dpServiceJni: classInitNative
09-09 17:12:48.073  7724  7724 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:12:48.073  7724  7724 D A2dpStateMachine: make
09-09 17:12:48.075  7724  7724 I bluedroid-qcom: get_profile_interface a2dp
09-09 17:12:48.075  7724  7965 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-09 17:12:48.078  7724  7724 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:12:48.078  7724  7724 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 17:12:48.079  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.079  7724  7964 D A2dpStateMachine: Enter Disconnected: -2
09-09 17:12:48.080  7724  7724 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 17:12:48.081  7724  7724 D HidService: Received start request. Starting profile...
09-09 17:12:48.081  7724  7724 I bluedroid-qcom: get_profile_interface hidhost
09-09 17:12:48.081  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.082  7724  7724 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:12:48.083  7724  7724 D HealthService: Received start request. Starting profile...
09-09 17:12:48.085  7724  7724 I bluedroid-qcom: get_profile_interface health
09-09 17:12:48.085  7724  7724 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:12:48.085  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.086  7724  7724 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 17:12:48.087  7724  7724 D PanService: Received start request. Starting profile...
09-09 17:12:48.087  7724  7724 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 17:12:48.087  7724  7724 I bluedroid-qcom: get_profile_interface pan
09-09 17:12:48.093  7724  7724 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 17:12:48.093  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.093  7724  7724 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 17:12:48.098  7724  7724 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:12:48.098  7724  7724 D BtGatt.GattService: Received start request. Starting profile...
09-09 17:12:48.098  7724  7724 D BtGatt.GattService: start()
09-09 17:12:48.098  7724  7724 I bluedroid-qcom: get_profile_interface gatt
09-09 17:12:48.099  7724  7724 D BtGatt.AdvertiseManager: advertise manager created
09-09 17:12:48.109  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
,09-09 17:12:48.112  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.113  7724  7724 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 17:12:48.116  7724  7724 V BluetoothMapService: BluetoothMapBinder()
09-09 17:12:48.117  7724  7724 D BluetoothMapService: Received start request. Starting profile...
09-09 17:12:48.117  7724  7724 D BluetoothMapService: start()
09-09 17:12:48.119  7724  7724 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 17:12:48.120  7724  7724 D BluetoothMapEmailAppObserver: createReceiver()
09-09 17:12:48.121  7724  7724 D BluetoothMapEmailAppObserver: initObservers()
09-09 17:12:48.121  7724  7724 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-09 17:12:48.135  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.136  7724  7724 D HeadsetStateMachine: Proxy object connected
,09-09 17:12:48.137  7724  7724 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,09-09 17:12:48.137  7724  7724 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 17:12:48.141  7724  7956 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
09-09 17:12:48.142  7724  7956 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-09 17:12:48.143  7724  7956 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 17:12:48.147  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:12:48.147  7724  7724 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:48.147  7724  7724 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:48.147  7724  7724 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:48.147  7724  7724 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:48.147  7724  7724 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 17:12:48.152  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 17:12:48.157  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:12:48.163  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:12:48.168  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 17:12:48.168  7724  7724 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 17:12:48.172  7724  7724 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 17:12:48.173  7724  7724 V BluetoothMapService: Handler(): got msg=1
09-09 17:12:48.174  7724  7933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 17:12:48.174  7724  7933 I bluedroid-qcom: enable
09-09 17:12:48.174  7724  7933 I bt_hci_bdroid: init
09-09 17:12:48.174  7724  7972 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 17:12:48.174  7724  7972 I bt-btu  : btu_task pending for preload complete event
09-09 17:12:48.177  7724  7933 I bt_vendor: bt-vendor : init
09-09 17:12:48.177  7724  7933 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 17:12:48.178  7724  7933 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 17:12:48.178  7724  7933 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 17:12:48.178  7724  7933 D bt_userial_mct: userial_init
09-09 17:12:48.178  7724  7933 D bt_hci_bdroid: set_power 1
09-09 17:12:48.179  7724  7933 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 17:12:48.179  7724  7933 I bt_vendor: Starting hciattach daemon
09-09 17:12:48.179  7724  7933 I bt_vendor: try to set true
09-09 17:12:48.179  7975  7975 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:48.179  7975  7975 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:12:48.234  7976  7976 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 17:12:48.364  7982  7982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 17:12:48.377  7983  7983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 17:12:48.423  7988  7988 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:12:48.443  7989  7989 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 17:12:48.466  7990  7990 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:12:48.477  7991  7991 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-09 17:12:48.497  7993  7993 I libmdmdetect: ESOC framework not supported
09-09 17:12:48.498  7993  7993 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 17:12:48.509  7993  7993 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-09 17:12:48.509  7993  7993 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-09 17:12:48.509  7993  7993 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 17:12:48.509  7993  7993 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 17:12:48.509  7993  7993 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 17:12:48.509  7993  7993 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 17:12:48.509  7993  7993 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-09 17:12:48.546  7993  7994 E QC-QMI  : qmi_client [7993] 15: failed to locate client data
09-09 17:12:48.547   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 17:12:48.547   474   474 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-09 17:12:48.591  7995  7995 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 17:12:48.605  7996  7996 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 17:12:48.631  7724  7933 I bt_vendor: bluetooth satus is on
09-09 17:12:48.631  7724  7933 D bt_hci_bdroid: preload
,09-09 17:12:48.631  7724  7974 D bt_userial_mct: userial_open(port:0)
09-09 17:12:48.631  7724  7974 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-09 17:12:48.635  7724  7974 I bt_vendor: Done intiailizing UART
,09-09 17:12:48.639  7724  7974 I bt_vendor: Done intiailizing UART
,09-09 17:12:48.639  7724  7974 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-09 17:12:48.639  7724  7974 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 17:12:48.640  7724  7998 D bt_userial_mct: Entering userial_read_thread()
09-09 17:12:48.640  7724  7972 I bt-btu  : btu_task received preload complete event
09-09 17:12:48.640  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,09-09 17:12:48.640  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 17:12:48.643  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:12:48.650  7724  7972 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:12:48.651  7724  7972 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:12:48.699  7724  7972 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-09 17:12:48.700  7724  7972 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa022f061 
09-09 17:12:48.700  7724  7972 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa022f061 
,09-09 17:12:48.715  7724  7937 E bt-btif : Calling BTA_HhEnable
09-09 17:12:48.715  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 17:12:48.715  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 17:12:48.715  7724  7972 W bt-l2cap: btif_storage_get_adapter_property service_mask
09-09 17:12:48.715  7724  7937 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-09 17:12:48.715  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011,
09-09 17:12:48.715  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 17:12:48.715  7724  7937 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 17:12:48.718  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:12:48.718  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 17:12:48.719  7724  7937 D BluetoothAdapterProperties: Name is: G3
09-09 17:12:48.720  7724  7937 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:12:48.720  7724  7937 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:12:48.721  7724  7937 D bt_hci_bdroid: postload
09-09 17:12:48.722  7724  7974 D bt_hci_bdroid: Used up Tx Cmd credits
,09-09 17:12:48.723  7724  7937 D bte_conf: Device ID record 1 : primary
09-09 17:12:48.723  7724  7937 D bte_conf:   vendorId            = 00c4
09-09 17:12:48.723  7724  7937 D bte_conf:   vendorIdSource      = 0001
09-09 17:12:48.723  7724  7937 D bte_conf:   product             = 13a1
09-09 17:12:48.723  7724  7937 D bte_conf:   version             = 1000
09-09 17:12:48.723  7724  7937 D bte_conf:   clientExecutableURL = 
09-09 17:12:48.723  7724  7937 D bte_conf:   serviceDescription  = 
09-09 17:12:48.723  7724  7937 D bte_conf:   documentationURL    = 
09-09 17:12:48.723  7724  7937 D bte_conf: bte_load_did_conf no section named DID2.
09-09 17:12:48.725  7724  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 17:12:48.730  7724  7933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 17:12:48.730  7724  7933 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:12:48.731  7724  7933 D BluetoothAdapterProperties: State =  11
09-09 17:12:48.731  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:48.731  7724  7933 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 17:12:48.731  7724  7933 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 17:12:48.731  7724  7933 D BluetoothAdapterProperties: Setting state to 12
09-09 17:12:48.731  7724  7933 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:12:48.736  7724  7933 I BluetoothAdapterState: Entering On State
09-09 17:12:48.729  8000  8000 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:48.729  8000  8000 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:12:48.743  1037  1099 D BluetoothManagerService: Message: 60
09-09 17:12:48.743  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 17:12:48.744  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-09 17:12:48.745  7724  7937 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 17:12:48.745  6932  6948 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:12:48.745  6932  6948 D BluetoothPan: onBluetoothStateChange call bindService
09-09 17:12:48.746  7724  7974 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:12:48.746  7724  7937 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:12:48.751  7724  7933 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 17:12:48.752  7724  7933 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 17:12:48.752  7724  7933 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 17:12:48.753  7724  7974 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:12:48.753  7724  7933 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 17:12:48.754  1882  1897 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 17:12:48.757  7724  7974 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:12:48.761  7724  7998 E bt_mct  : hci lib postload completed
09-09 17:12:48.763  7724  7937 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:12:48.764  7724  7937 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 17:12:48.764  6932  6932 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:12:48.764  6932  6932 D PanProfile: Bluetooth service connected
09-09 17:12:48.766  1882  1882 D BluetoothHeadset: Proxy object connected
09-09 17:12:48.769  7724  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:48.769  7724  7972 W bt-smp  : Plain text(LSB ~ MSB) = 9f 70 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:48.769  7724  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 b7 7b 26 4d 0b e9 be 9f ed 87 9b ad 87 61 6e 
09-09 17:12:48.769  7724  7972 W bt-btm  : Stopping oneshot timer
,09-09 17:12:48.772  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:48.773  1037  1037 D BluetoothHeadset: Proxy object connected
09-09 17:12:48.778  6932  7409 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:48.780  1882  1898 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:48.783  1882  1882 D BluetoothHeadset: Proxy object connected
,09-09 17:12:48.785  6932  6947 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 17:12:48.786  7724  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:48.786  7724  7972 W bt-smp  : Plain text(LSB ~ MSB) = 3b 00 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:48.786  7724  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = f6 40 eb 0b 19 93 f2 d3 46 2d e6 d0 61 51 d0 dd 
,09-09 17:12:48.786  7724  7972 W bt-btm  : Stopping oneshot timer
,09-09 17:12:48.786  7724  7933 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-09 17:12:48.788  6932  6948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:12:48.789  6932  6932 D BluetoothHeadset: Proxy object connected
09-09 17:12:48.789  6932  6932 D HeadsetProfile: Bluetooth service connected
09-09 17:12:48.791  1882  4446 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:48.795  1882  1882 D BluetoothHeadset: Proxy object connected
09-09 17:12:48.798  7724  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:48.798  7724  7972 W bt-smp  : Plain text(LSB ~ MSB) = 63 da 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:48.798  7724  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = b9 2a 74 db 5e 7d 46 d5 ba 2b 46 77 ba b9 f5 77 
09-09 17:12:48.798  7724  7972 W bt-btm  : Stopping oneshot timer
09-09 17:12:48.801  6932  6947 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:12:48.808  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:12:48.809  6932  6932 D BluetoothA2dp: Proxy object connected
09-09 17:12:48.809  6932  6932 D A2dpProfile: Bluetooth service connected
09-09 17:12:48.810  1037  1037 D BluetoothA2dp: Proxy object connected
09-09 17:12:48.811  7724  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:48.811  7724  7972 W bt-smp  : Plain text(LSB ~ MSB) = 4a c3 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:48.811  7724  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = 39 1b 8d 42 fd 66 61 5e e5 63 e9 83 ba 71 4c c0 
09-09 17:12:48.811  7724  7972 W bt-btm  : Stopping oneshot timer
09-09 17:12:48.813  6932  7409 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:12:48.813  6932  6932 D BluetoothInputDevice: Proxy object connected
09-09 17:12:48.813  6932  6932 D HidProfile: Bluetooth service connected
09-09 17:12:48.817  1037  1099 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 17:12:48.817  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-09 17:12:48.819  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-09 17:12:48.819  6932  6932 D BluetoothMap: Proxy object connected
09-09 17:12:48.819  6932  6932 D MapProfile: Bluetooth service connected
09-09 17:12:48.819  6932  6932 D BluetoothMap: getConnectedDevices()
09-09 17:12:48.820  7724  8003 V BluetoothMapService: getConnectedDevices()
09-09 17:12:48.820  7724  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:12:48.820  7724  7972 W bt-smp  : Plain text(LSB ~ MSB) = 55 0f 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:12:48.820  7724  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = bc 0c ea de 75 41 8d 63 c1 8a e4 a1 7e 7c db ff 
09-09 17:12:48.820  7724  7972 W bt-btm  : Stopping oneshot timer
09-09 17:12:48.824  1037  1099 D BluetoothManagerService: Message: 40
,09-09 17:12:48.824  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 17:12:48.824  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:12:48.828  8016  8016 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-09 17:12:48.828  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:48.831  1978  2179 D LGBluetoothAPIService: Message: 1
09-09 17:12:48.831  1978  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 17:12:48.831  1978  2179 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-09 17:12:48.831  1978  2179 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-09 17:12:48.834  7724  7724 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:48.834  7724  7724 D BluetoothMapService: STATE_ON
09-09 17:12:48.835  7724  7724 V BluetoothMapService: Handler(): got msg=1
09-09 17:12:48.836  7724  7724 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:48.840  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:48.842  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-09 17:12:48.845  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:12:48.846  7724  8017 D BluetoothMapMasInstance: MAS initSocket()
09-09 17:12:48.847  7724  8017 D BluetoothMapMasInstance:   masId = 00
09-09 17:12:48.847  7724  8017 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 17:12:48.847  7724  8017 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 17:12:48.847  7724  8017 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 17:12:48.848  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:48.852  1037  2095 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:48.854  6932  6932 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:48.855  7724  8017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:48.856  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.856  7724  7724 V BluetoothPbapService: Pbap Service onCreate
09-09 17:12:48.856  7724  7724 V BluetoothPbapService: Starting PBAP service
09-09 17:12:48.858  7724  7724 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 17:12:48.858  7724  7724 V BluetoothPbapService: Pbap Service onBind
09-09 17:12:48.860  7724  7724 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:48.860  7724  7724 V BluetoothPbapService: state: 12
09-09 17:12:48.860  7724  8017 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 17:12:48.860  7724  7724 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:12:48.860  7724  7724 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:48.860  7724  7724 V BluetoothPbapReceiver: ***********state = 12
09-09 17:12:48.860  7724  8017 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 17:12:48.860  7724  8017 D BluetoothMapMasInstance: Accepting socket connection...
09-09 17:12:48.860  7724  7937 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:12:48.860  7724  7937 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 17:12:48.861  6932  6932 D BluetoothPbap: Proxy object connected
09-09 17:12:48.861  6932  6932 D PbapServerProfile: Bluetooth service connected
09-09 17:12:48.862  7724  7724 V BluetoothPbapService: Handler(): got msg=1
09-09 17:12:48.863  7724  7724 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 17:12:48.863  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:48.864  7724  8022 V BluetoothPbapService: Pbap Service initSocket
09-09 17:12:48.864  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:48.865  2206  2206 D c       : Getting all permits...
09-09 17:12:48.865  2206  2206 D a       : Opening database...
09-09 17:12:48.866  1037  1718 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:48.866  7724  8022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:48.867  7724  8022 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 17:12:48.868  7724  8022 V BluetoothPbapService: Succeed to create listening socket 
09-09 17:12:48.868  7724  8022 V BluetoothPbapService: Accepting socket connection...
09-09 17:12:48.869  2206  2206 D a       : Opening database auth.proximity.permit_store...
09-09 17:12:48.870  2206  2206 D a       : Closing database...
,09-09 17:12:48.881  6932  6932 D BluetoothPermissionRequest: onReceive
,09-09 17:12:48.883  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 17:12:48.884  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:12:48.887  7724  7724 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-09 17:12:48.889  7724  7724 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-09 17:12:48.895  7724  7724 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-09 17:12:48.914  7724  7724 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:12:48.914  7724  7724 V BtOppService: onCreate
,09-09 17:12:48.919  7724  7724 V BluetoothOppNotification: send message
09-09 17:12:48.923  7724  7724 V BtOppService: Starting RfcommListener
09-09 17:12:48.929  7724  7724 D BluetoothOppPreference: Dumping Names:  
,09-09 17:12:48.929  7724  7724 D BluetoothOppPreference: {}
09-09 17:12:48.929  7724  7724 D BluetoothOppPreference: Dumping Channels:  
09-09 17:12:48.929  7724  7724 D BluetoothOppPreference: {}
,09-09 17:12:48.935  7724  7724 V BtOppService: onStartCommand
09-09 17:12:48.940  7724  8029 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:12:48.941  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:48.941  7724  7724 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 17:12:48.948  7724  7724 V BluetoothOppNotification: new notify threadi!
,09-09 17:12:48.951  7724  7724 V BluetoothOppNotification: send delay message
09-09 17:12:48.954  7724  7724 V BtOppService: start RfcommListener
09-09 17:12:48.954  7724  8026 V BtOppService: Deleted complete outbound shares, number =  0
09-09 17:12:48.955  7724  8029 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:12:48.956  7724  8026 V BtOppService: Deleted complete inbound failed shares, number = 0
,09-09 17:12:48.957  7724  8026 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 17:12:48.962  7724  8026 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@335ec0ea on behalf of 
09-09 17:12:48.962  7724  8029 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d1b9fdb on behalf of 
09-09 17:12:48.964  7724  7724 V BtOppService: RfcommListener started
09-09 17:12:48.966  7724  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 17:12:48.971  7724  8031 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 17:12:48.972  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:48.974  7724  8031 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:48.976  7724  8031 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-09 17:12:48.977  7724  8031 V BtOppRfcommListener: Started RFCOMM listener....
09-09 17:12:48.977  7724  8031 I BtOppRfcommListener: Accept thread started.
09-09 17:12:48.977  7724  8031 V BtOppRfcommListener: Accepting connection...
09-09 17:12:48.977  7724  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dd9fa78 on behalf of 
09-09 17:12:48.978  7724  8029 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-09 17:12:48.983  7724  8030 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-09 17:12:48.985  7724  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:12:48.988  7724  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f06551 on behalf of 
09-09 17:12:48.988  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:48.989  7724  7724 V BluetoothFtpService: Ftp Service onCreate
09-09 17:12:48.989  7724  7724 I BluetoothFtpService: Ftp Service onCreate
09-09 17:12:48.989  7724  7724 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:12:48.989  7724  7724 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:48.989  7724  7724 V BluetoothFtpService: Starting Listening on sockets
09-09 17:12:48.990  7724  8030 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 17:12:48.990  7724  7724 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:12:48.990  7724  7724 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:12:48.990  7724  7724 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:12:48.990  7724  7724 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:48.990  7724  7724 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 17:12:48.990  7724  7724 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 17:12:48.992  7724  7724 V BtOppService: ContentObserver received notification
09-09 17:12:48.992  7724  7724 V BtOppService: ContentObserver received notification
09-09 17:12:48.992  7724  7724 V BluetoothFtpService: Handler(): got msg=1
09-09 17:12:48.993  7724  7724 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 17:12:48.993  7724  7724 V BluetoothFtpService: Ftp Service initSocket
,09-09 17:12:49.000  7724  8032 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:12:49.000  7724  8032 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:12:49.001  7724  8030 V BluetoothOppNotification: outbound notification was removed.
09-09 17:12:49.001  7724  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 17:12:49.001  1037  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:49.003  7724  8032 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12aa5eb7 on behalf of 
09-09 17:12:49.004  7724  7724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:49.005  7724  8032 V BluetoothOppNotification: update too frequent, put in queue
09-09 17:12:49.005  7724  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13f04624 on behalf of 
09-09 17:12:49.005  7724  7724 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=79
09-09 17:12:49.006  7724  7724 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-09 17:12:49.008  7724  8033 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 17:12:49.009  7724  8032 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-09 17:12:49.013  7724  8030 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 17:12:49.015  7724  8030 V BluetoothOppNotification: inbound notification was removed.
09-09 17:12:49.015  7724  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 17:12:49.018  7724  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1685058d on behalf of 
09-09 17:12:49.025  7724  7724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@293966ce
09-09 17:12:49.025  7724  7724 V BluetoothSapService: Sap Service onCreate
09-09 17:12:49.027  7724  7724 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:49.027  7724  7724 V BluetoothSapService: state: 12
09-09 17:12:49.028  7724  7724 V BluetoothSapService: Starting SAP server process
,09-09 17:12:49.030  7724  7724 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 17:12:49.019  8034  8034 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:12:49.019  8034  8034 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:49.032  7724  8035 V BluetoothSapService: Sap Service initRfcommSocket
09-09 17:12:49.032  1037  2081 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:49.033  7724  8035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:49.034  7724  8035 V BluetoothSapService: Succeed to create listening socket 
09-09 17:12:49.034  7724  8035 V BluetoothSapService: Accepting socket connection...
09-09 17:12:49.043  8034  8034 V BT_SAP  : Event pipe created
09-09 17:12:49.043  8034  8034 V BT_SAP  : create_server_socket qcom.sap.server
09-09 17:12:49.044  8034  8034 V BT_SAP  : created socket fd 6
,09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:49.542  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:49.556  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:49.561  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:49.561  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5505f73 added. We now have 8 listener(s)
09-09 17:12:49.561  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:49.572  1037  1718 D WifiServiceImplEx: setWifiEnabled: false pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:12:49.572  1037  1718 D WifiService: setWifiEnabled: false pid=6717, uid=10118
09-09 17:12:49.572  1037  1718 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:12:49.577  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:49.579  1037  1577 D WifiServiceImplEx: setWifiEnabled: true pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-09 17:12:49.581  1037  1577 D WifiService: setWifiEnabled: true pid=6717, uid=10118
09-09 17:12:49.582  1037  1577 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:12:49.601  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 17:12:49.601  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-09 17:12:49.601  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-09 17:12:49.603  1037  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-09 17:12:49.603  1037  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-09 17:12:49.606  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-09 17:12:49.606  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-09 17:12:49.606  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 17:12:49.606  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-09 17:12:49.606  1037  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,09-09 17:12:49.606  1037  1540 E WifiHW  : unknown target_country: EU , set to default
,09-09 17:12:49.606  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
09-09 17:12:49.606  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-09 17:12:49.606  1037  1540 I WifiUtil: gEnableBmps=1
,09-09 17:12:49.955  7724  7724 V BluetoothOppNotification: new notify threadi!
09-09 17:12:49.955  7724  7724 V BluetoothOppNotification: send delay message
,09-09 17:12:49.997  7724  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-09 17:12:50.018  7724  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a496d89 on behalf of 
,09-09 17:12:50.019  7724  8048 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-09 17:12:50.024  7724  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:12:50.025  7724  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@199918e on behalf of 
09-09 17:12:50.026  7724  8048 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 17:12:50.027  7724  8048 V BluetoothOppNotification: outbound notification was removed.
09-09 17:12:50.028  7724  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 17:12:50.218  1037  2095 I art     : Explicit concurrent mark sweep GC freed 25307(1243KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.081ms total 166.750ms
,09-09 17:12:50.221  7724  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a906daf on behalf of 
09-09 17:12:50.222  7724  8048 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 17:12:50.282  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:12:50.282  1037  1099 D Tethering: InitialState.processMessage what=4
,09-09 17:12:50.288   328   897 D SoftapController: Softap fwReload - Ok
09-09 17:12:50.290  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:12:50.303  1037  1540 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (693ms)
,09-09 17:12:50.307   328   897 D CommandListener: Setting iface cfg
09-09 17:12:50.307   328   897 D CommandListener: Trying to bring down wlan0
09-09 17:12:50.307   328   897 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:12:50.313  1037  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 17:12:50.314  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:12:50.314  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:12:50.314  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:12:50.314  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:12:50.315  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-09 17:12:50.318  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:12:50.318  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 17:12:50.318  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:12:50.318  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:12:50.318  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:12:50.318  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:12:50.309  8066  8066 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:50.322  7724  8048 V BluetoothOppNotification: inbound notification was removed.
09-09 17:12:50.323  7724  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 17:12:50.325  7724  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@154435bc on behalf of 
09-09 17:12:50.309  8066  8066 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:12:50.344  8066  8066 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:12:50.353  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:12:50.353  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:12:50.353  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:12:50.353  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:12:50.356  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:12:50.357  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:12:50.358  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 17:12:50.358  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:12:50.358  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:12:50.358  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:12:50.358  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:12:50.377  8066  8066 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 17:12:50.377  8066  8066 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-09 17:12:50.415  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:50.415  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:50.415  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:12:50.415  1037  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 17:12:50.415  1037  1540 D WifiMonitor: connecting to supplicant
09-09 17:12:50.418  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-09 17:12:50.420  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:50.432  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:50.456  8066  8066 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:12:50.477  1037  1095 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8074 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-09 17:12:50.477  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-09 17:12:50.500   357   357 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 22.962ms
,09-09 17:12:50.511  8066  8066 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 17:12:50.520  8066  8066 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-09 17:12:50.522  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 17:12:50.522  1037  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 17:12:50.522  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 17:12:50.522  1037  8090 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-09 17:12:50.523  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 17:12:50.524   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 21.925ms
09-09 17:12:50.525  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:12:50.525  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 17:12:50.526  8066  8066 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 17:12:50.526  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 17:12:50.526  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 17:12:50.526  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 17:12:50.526  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 17:12:50.526  1037  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 17:12:50.527  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:50.528  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:50.529  1037  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 17:12:50.529  1037  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 17:12:50.530  1037  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 17:12:50.530  1037  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 17:12:50.530  1037  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 17:12:50.531  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:12:50.531  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:12:50.531  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:12:50.531  1037  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 17:12:50.533  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.533  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.533  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.533  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.533  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:12:50.533  1037  1540 D WifiNative-wlan0: SET update_config 1: returned true
09-09 17:12:50.533  1037  1540 D WifiConfigStore: Loading config and enabling all networks 
09-09 17:12:50.534  1037  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 17:12:50.534  1037  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 17:12:50.535  1978  1978 D WfdService: Waiting for WifiP2p enabling
09-09 17:12:50.537  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:12:50.539  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 17:12:50.541  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 17:12:50.544  1037  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:50.544  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:50.546  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:50.550   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 22.110ms
,09-09 17:12:50.554  1037  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 17:12:50.555  1037  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 17:12:50.559  1037  1540 D WifiStateMachine: enableVerboseLogging : level 2
09-09 17:12:50.559  1037  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 17:12:50.560  1037  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 17:12:50.560  1037  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 17:12:50.560  1037  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 17:12:50.560  1037  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 17:12:50.561  1037  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 17:12:50.561  1037  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 17:12:50.562  1037  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 17:12:50.562  1037  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 17:12:50.562  1037  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 17:12:50.562  1037  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 17:12:50.563  1037  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 17:12:50.563  1037  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 17:12:50.563  1037  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-09 17:12:50.566  1978  1978 D WfdsService: Supplicant Connection state is changed : true
09-09 17:12:50.567  1978  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 17:12:50.567  1978  2354 D WfdsService: Set the WFDS Monitor: true
09-09 17:12:50.567  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:12:50.567  1978  2354 D WfdsMonitor: WfdsMonitorThread create
09-09 17:12:50.567  1037  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 17:12:50.567  1978  2354 D WfdsMonitor: WFDS Monitor is created and started
09-09 17:12:50.567  1978  2354 D WfdsService: WiFi: Supplicant connection re-established
09-09 17:12:50.567  1037  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 17:12:50.567  1037  1540 D WifiNative-HAL: Setting external_sim to 1
09-09 17:12:50.567  1037  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 17:12:50.568  1037  1540 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 17:12:50.568  1037  1540 I WifiNative-HAL: startHal
09-09 17:12:50.568  1037  1540 D wifi    : setting scan oui 0xaf677b60
09-09 17:12:50.568  1978  8093 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 17:12:50.568  1978  8093 E CtrlSupplicant: Succeed to open control connection
09-09 17:12:50.568  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:12:50.568  1037  1540 I WifiNative-HAL: startHal
09-09 17:12:50.568  1037  1540 D wifi    : setting scan oui 0xaf677b60
09-09 17:12:50.569  1978  8093 E CtrlSupplicant: Succeed to open monitor connection
09-09 17:12:50.570  1037  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 17:12:50.571  1978  8093 D WfdsMonitor: Supplicant connection established
09-09 17:12:50.571  1978  2354 D WfdsService: Connected to the supplicant for wfds
09-09 17:12:50.571  1037  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 17:12:50.571  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 17:12:50.571  7752  7752 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.571  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 17:12:50.572  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 17:12:50.572  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:12:50.572  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:12:50.572  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 17:12:50.572  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 17:12:50.573  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 17:12:50.573  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 17:12:50.573  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:12:50.573  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 17:12:50.573  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:12:50.573  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:12:50.574  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:12:50.574  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 17:12:50.574  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 17:12:50.574  8066  8066 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 17:12:50.574  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 17:12:50.574  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:12:50.574  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 17:12:50.575  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:12:50.576  1037  1540 E WifiNative: : [139,438,459 us] RECONNECT  st,ack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 17:12:50.576  1037  1540 D WifiNative-wlan0: doBoolean: RECONNECT
,09-09 17:12:50.576  1037  1540 D WifiNative-wlan0: RECONNECT: returned true
09-09 17:12:50.576  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-09 17:12:50.577  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:12:50.577  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 17:12:50.577  1037  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 17:12:50.577  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:50.578  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:50.578  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.580   328   897 D CommandListener: Setting iface cfg
09-09 17:12:50.580   328   897 D CommandListener: Trying to bring up p2p0
09-09 17:12:50.580  1037  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 17:12:50.580  1037  1539 D LGWifiP2pService: P2pEnablingState
09-09 17:12:50.581  1037  1539 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.581  1037  1539 D LGWifiP2pService: P2p socket connection successful
09-09 17:12:50.581  1037  1539 D LGWifiP2pService: P2pEnabledState
09-09 17:12:50.581  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 17:12:50.581  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-09 17:12:50.581  1037  1539 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 17:12:50.581  1037  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.581  1037  1558 I WifiNative-HAL: startHal
09-09 17:12:50.581  1037  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf677b60
09-09 17:12:50.581  1037  1558 D wifi    : failed to get capabilities : -3
09-09 17:12:50.581  1037  1558 E WifiScanningService: could not get scan capabilities
09-09 17:12:50.581  1037  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.582  1037  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 17:12:50.582  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 17:12:50.583  1037  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,09-09 17:12:50.583  1037  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 17:12:50.583  1978  1978 D WfdsService: WifiP2pState is changed : true
09-09 17:12:50.583  1037  1539 D WifiNative-p2p0: SET device_name G3: returned true
09-09 17:12:50.583  1037  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 17:12:50.583  1037  1539 D LGWifiP2pService: before postfix = G3
09-09 17:12:50.583  1037  1539 D WifiServerServiceExt: postfix byte check : 2
09-09 17:12:50.583  1037  1539 D LGWifiP2pService: after postfix = G3
09-09 17:12:50.583  1978  2354 D WfdsService: Receive the WFDS_ENABLE Method
09-09 17:12:50.583  1037  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-09 17:12:50.583  1978  2354 D WfdsService: Set the WFDS Monitor: true
09-09 17:12:50.583  1978  2354 D WfdsService: Connected to the supplicant for wfds
09-09 17:12:50.584  1978  2354 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 17:12:50.584  8066  8066 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 17:12:50.584  1978  2354 D WfdsService: selectPreferredScanChannel [36]
09-09 17:12:50.584  1978  2354 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-09 17:12:50.584  1037  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 17:12:50.584  1037  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
,09-09 17:12:50.584  1978  1978 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 17:12:50.585  1978  1978 D WfdsService: isConnected: false
09-09 17:12:50.585  1037  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
,09-09 17:12:50.585  1037  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 17:12:50.585  1037  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 17:12:50.585  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 17:12:50.586  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,09-09 17:12:50.586  1037  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 17:12:50.586  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress
09-09 17:12:50.586  1037  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 17:12:50.586  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,09-09 17:12:50.587  1037  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 17:12:50.587  1037  1539 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 17:12:50.587  1037  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,09-09 17:12:50.587  1037  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 17:12:50.587  1037  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 17:12:50.587  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139451  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-09 17:12:50.587  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 17:12:50.588  1037  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 17:12:50.588  1978  1978 I WfdStateTracker: handleP2pThisDeviceChanged
,09-09 17:12:50.588  1037  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 17:12:50.588  1978  1978 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,09-09 17:12:50.589  1037  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 17:12:50.589  1037  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 17:12:50.590  1978  1978 D WfdsService: Update P2p Interface State: 3
09-09 17:12:50.592  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.592  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.593  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:50.593  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:50.594  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 17:12:50.595  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139458  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:12:50.595  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:50.597  1037  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 17:12:50.597  1037  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 17:12:50.598  1037  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 17:12:50.598  1037  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 17:12:50.600  8066  8066 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,09-09 17:12:50.600  1037  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 17:12:50.600  1037  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 17:12:50.601  1037  1539 D LGWifiP2pService: InactiveState
09-09 17:12:50.601  1037  1539 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.601  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.601  1037  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 17:12:50.602  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 17:12:50.602  8066  8066 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:50.602  1037  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:12:50.602  1037  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:50.603  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:50.603  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:50.603  8066  8066 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:12:50.603  8066  8066 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.603  1037  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 17:12:50.604  1037  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 17:12:50.604  8066  8066 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.604  1037  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 17:12:50.604  1037  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 17:12:50.604  8066  8066 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 17:12:50.604  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 17:12:50.605  1978  8093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:12:50.605  1978  8093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.605  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 17:12:50.605  1978  8093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.605  1037  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.605  1037  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.605  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.605  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.605  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 17:12:50.605  1037  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.605  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 17:12:50.605  1037  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.605  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.605  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.605  1037  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=c,om.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.606  1978  2354 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 17:12:50.607  1037  1539 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.607  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.607  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.607  1037  1037 E WifiServerServiceExt: No p2p device connected
09-09 17:12:50.608  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 17:12:50.608  8066  8066 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:50.608  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:12:50.608  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:50.608  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-09 17:12:50.608  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:12:50.609  8066  8066 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:12:50.609  8066  8066 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.609  1037  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 17:12:50.609  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:12:50.609  8066  8066 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.610  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:12:50.610  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,09-09 17:12:50.610  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 17:12:50.610  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.610  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:50.610  1978  8093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.610  1978  8093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.610  1037  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.610  1037  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-09 17:12:50.611  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.611  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.611  1037  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:12:50.611  1037  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.611  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.611  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:12:50.611  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
,09-09 17:12:50.611  8066  8066 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:50.611  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 17:12:50.611  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:50.611  1037  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:50.611  1037  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:12:50.612  1037  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 17:12:50.612  1037  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 17:12:50.612  1037  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 17:12:50.612  1037  1540 D WifiNative-wlan0: doBoolean: SCAN
09-09 17:12:50.613  1037  1540 D WifiNative-wlan0: SCAN: returned false
09-09 17:12:50.613  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139476  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:12:50.614  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139477  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:12:50.615  1037  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:50.615  1037  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:50.615  1037  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:50.616  1037  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:50.616  1037  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:50.618  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:50.618  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.618  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:50.619  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 17:12:50.619  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:50.619  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 17:12:50.619  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:50.619  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 17:12:50.620  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:50.621  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:50.621  1606  1606 I StatusBar.NetworkContr,oller: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:50.622  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:50.625  6717  6820 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 17:12:50.627  6717  6820 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 17:12:50.629  6717  6820 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16f6ba3d Bundle[{}]
09-09 17:12:50.630  6717  6820 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 17:12:50.631  6717  6820 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 17:12:50.631  6717  6820 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 17:12:50.632  6717  6820 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 17:12:50.633  6717  6820 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 17:12:50.634  6717  6820 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 17:12:50.640  6717  6820 I System.out: Running OutgoingSocketThread
,09-09 17:12:50.643  6717  8097 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
09-09 17:12:50.644  6717  8097 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47599
,09-09 17:12:50.644  6717  8097 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 17:12:50.669  1037  1780 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8099 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:12:50.675  8074  8096 W FormManager: Network not available. Please check & try again.
,09-09 17:12:50.701  8074  8098 V FormManager: Network unavailable.
,09-09 17:12:50.704  8074  8098 V FormManager: Network unavailable.
09-09 17:12:50.726  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:50.730  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 17:12:50.734  1037  2054 I ActivityManager: Killing 7222:com.lge.drmservice/u0a62 (adj 15): empty #17
09-09 17:12:50.736  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:50.807  1037  2054 I ActivityManager: Killing 7239:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-09 17:12:50.870  1037  1780 W libprocessgroup: failed to open /acct/uid_10085/pid_7239/cgroup.procs: No such file or directory
,09-09 17:12:50.877  1037  2010 W libprocessgroup: failed to open /acct/uid_10062/pid_7222/cgroup.procs: No such file or directory
,09-09 17:12:50.915  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:50.923  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 17:12:50.929  8074  8121 W FormManager: Network not available. Please check & try again.
,09-09 17:12:50.933  8074  8122 V FormManager: Network unavailable.
09-09 17:12:50.934  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:50.943  8074  8122 V FormManager: Network unavailable.
,09-09 17:12:50.962  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-09 17:12:50.963  4344  4344 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 17:12:50.967  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:50.970  4344  4344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:12:50.987  4344  8123 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:12:50.995  4344  8124 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-09 17:12:50.995  4344  8124 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:12:51.021  1037  1053 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8125 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 17:12:51.178  8125  8125 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 17:12:51.179  8066  8066 E wpa_supplicant: USIM:  scard_init function
,09-09 17:12:51.180  8066  8066 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 17:12:51.181  8125  8125 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-09 17:12:51.186  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 17:12:51.186  1037  8090 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 17:12:51.187  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 17:12:51.187  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-09 17:12:51.187  1037  8090 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 17:12:51.187  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:12:51.187  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-09 17:12:51.187  1037  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,09-09 17:12:51.188  1037  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0,
09-09 17:12:51.188  1037  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,09-09 17:12:51.189  1037  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0,
09-09 17:12:51.189  1037  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 17:12:51.192  8125  8125 V [BNRBootReceiver]: Boot Receiver Return
,09-09 17:12:51.194  8125  8125 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 17:12:51.278  1037  2095 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8143 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:12:51.283  1037  2095 I ActivityManager: Killing 7275:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-09 17:12:51.289  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 17:12:51.290  8066  8066 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 17:12:51.290  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 17:12:51.290  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 17:12:51.290  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 17:12:51.290  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:51.290  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:51.305  8066  8066 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 17:12:51.305  8066  8066 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-09 17:12:51.306  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-09 17:12:51.306  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:51.307  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,09-09 17:12:51.307  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:12:51.307  1037  8090 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:12:51.307  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,09-09 17:12:51.307  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:12:51.307  1037  8090 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:12:51.307  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:51.307  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:51.397  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140260  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 17:12:51.398  1037  1973 W libprocessgroup: failed to open /acct/uid_10093/pid_7275/cgroup.procs: No such file or directory
,09-09 17:12:51.417  1037  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 17:12:51.420  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140283  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 17:12:51.421  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140284  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 17:12:51.423  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140286  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 17:12:51.427  1037  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140290
09-09 17:12:51.428  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.428  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:51.428  1037  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140292
09-09 17:12:51.429  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.429  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.430  1037  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140293
09-09 17:12:51.430  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 17:12:51.431  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140294
09-09 17:12:51.431  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.432  1037  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140295
09-09 17:12:51.434  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140296  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-09 17:12:51.440  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.440  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.440  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 17:12:51.441  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140304  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 17:12:51.442  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140305  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:12:51.444  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140306  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:12:51.444  1037  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140308
09-09 17:12:51.445  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.445  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.445  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 17:12:51.446  1037  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140309
09-09 17:12:51.446  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-09 17:12:51.447  1037  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:12:51.447  1037  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:12:51.447  1037  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 17:12:51.449  1037  1540 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 17:12:51.452  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.453  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:51.454  1037  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 17:12:51.454  1037  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 17:12:51.455  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:12:51.458  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.458  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:51.460  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.460  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.460  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.460  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:12:51.465  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.465  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.465  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:12:51.470  1037  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 17:12:51.470  1037  1547 D ConnectivityService: Got NetworkAgent Messenger
09-09 17:12:51.470  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 17:12:51.470  1037  1547 D ConnectivityService: NetworkAgent connected
,09-09 17:12:51.470  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:51.470  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:12:51.471  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-09 17:12:51.471  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:12:51.474  8143  8143 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:12:51.476  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.476  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:51.477  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.479  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.479  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:51.479  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:12:51.480  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:51.480  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:12:51.480  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.481  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:12:51.481  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:12:51.486  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-09 17:12:51.488   328   897 D CommandListener: Setting iface cfg
09-09 17:12:51.491  1037  1540 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 17:12:51.491  1037  8161 D DhcpStateMachine: StoppedState
09-09 17:12:51.491  1037  8161 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.491  1037  8161 D DhcpStateMachine: WaitBeforeStartState
09-09 17:12:51.492  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140355  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:51.493  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140356  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:51.493  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140356  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:51.494  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:51.494  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 17:12:51.494  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:51.495  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:51.495  1037  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:51.496  1037  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:51.496  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:51.497  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:12:51.497  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:51.497  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-09 17:12:51.500  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:51.500  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 17:12:51.500  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:51.501  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 17:12:51.501  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140364  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:51.502  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140365  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:51.503  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140366  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:12:51.504  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14184] from screen [on:0 period:260188976] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 17:12:51.505  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:260188977] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 17:12:51.505  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 17:12:51.509  8143  8143 D PluginManager: init()
,09-09 17:12:51.510  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.510  1037  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-09 17:12:51.511  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.511  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.512  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.512  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.513  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.513  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.514  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 17:12:51.514  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
09-09 17:12:51.514  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
09-09 17:12:51.514  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 17:12:51.515  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 17:12:51.515  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 17:12:51.515  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 17:12:51.515  1037  1540 D WifiNative-wlan0: SET ps 0: returned true
09-09 17:12:51.516  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 17:12:51.516  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 17:12:51.516  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 17:12:51.516  1037  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 17:12:51.516  1037  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:12:51.516  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25acfdbe target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.516  1037  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:12:51.516  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25acfdbe target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.516  1037  8161 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.517  1037  8161 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 17:12:51.517   328   897 D CommandListener: Setting iface cfg
09-09 17:12:51.517   328   897 D CommandListener: Trying to bring up wlan0
09-09 17:12:51.519  1037  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 17:12:51.520  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:51.520  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 17:12:51.520  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:12:51.520  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-09 17:12:51.521  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 17:12:51.521  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.522  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.522  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.522  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.523  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:12:51.523  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 17:12:51.524  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 17:12:51.524  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 17:12:51.524  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:12:51.524  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.524  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.524  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:12:51.525  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:12:51.525  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 17:12:51.525  8066  8066 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 17:12:51.526  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 17:12:51.526  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:12:51.542  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:12:51.542  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-09 17:12:51.543  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:12:51.543  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:12:51.543  1037  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 17:12:51.543  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
09-09 17:12:51.545  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 17:12:51.546  1037  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 17:12:51.548  1037  1547 D ConnectivityService: Adding iface wlan0 to network 102
09-09 17:12:51.549  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.549  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:51.551  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.554  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.554  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.554  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-09 17:12:51.565  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.565  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.565  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 17:12:51.567  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 17:12:51.572  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-09 17:12:51.573  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.573  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:12:51.575  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.575  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.575  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:12:51.575  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.576  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 17:12:51.577  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.578  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 17:12:51.578  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.583  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:12:51.583  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:12:51.583  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:12:51.587  1037  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 17:12:51.587  1037  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 17:12:51.589  1037  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 17:12:51.589   328   897 E Netd    : netlink response contains error (File exists)
09-09 17:12:51.590  1037  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 17:12:51.591  1037  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 17:12:51.591  1037  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 17:12:51.591  1037  1547 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 17:12:51.592  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 17:12:51.592  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:51.592  1037  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:51.592  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 17:12:51.592  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:51.592  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:51.592  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 17:12:51.592  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:51.592  1037  8160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.592  1037  8160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 17:12:51.592  1037  8160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:12:51.593  1037  8160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 17:12:51.596   328  8165 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 17:12:51.597  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 17:12:51.597  1037  1547 D ConnectivityService: currentScore = 0, newScore = 20
09-09 17:12:51.597  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:12:51.597  1037  1547 D ConnectivityService:    accepting network in place of null
09-09 17:12:51.598  1037  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:51.598  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 17:12:51.598  1037  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:12:51.598  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.598  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:51.599  1882  1882 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:51.599  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:12:51.600  1037  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 17:12:51.600  1037  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 17:12:51.600  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 17:12:51.600  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:51.600  1037  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 17:12:51.602  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 17:12:51.602  1037  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 17:12:51.602  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:12:51.602  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:12:51.602  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:12:51.603  1037  1547 D ConnectivityService: validation of new default Network = false
09-09 17:12:51.603  1037  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 17:12:51.603  1037  1547 D DSQN    : enableDataServiceNotify 
09-09 17:12:51.603  1037  1547 D DSQN    : start dsqn bin
09-09 17:12:51.608  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:51.608  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:51.608  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:51.609  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:51.609  1606  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:12:51.599  8166  8166 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:51.612  1037  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-09 17:12:51.599  8166  8166 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:51.627  8166  8166 E DSQN    : DSQN ssw
,09-09 17:12:51.632  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:12:51.633  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.633  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.645  6717  6820 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
09-09 17:12:51.645  6717  6820 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
09-09 17:12:51.646   328  8165 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 17:12:51.649  6717  6820 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
09-09 17:12:51.650  6717  6820 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 17:12:51.650  6717  6820 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
09-09 17:12:51.653  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.653  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63fde30 added. We now have 2 listener(s)
09-09 17:12:51.653  1037  1786 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.656  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.656  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.656  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.656  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.656  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28046aa9 added. We now have 9 listener(s)
09-09 17:12:51.657  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.657  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:12:51.658  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:51.662  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:51.663  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.664  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:51.665  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.665  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c77fcf added. We now have 3 listener(s)
09-09 17:12:51.665  1037  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.666  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.667  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.668  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.668  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.668  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.668  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.668  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fcad5c added. We now have 10 listener(s)
09-09 17:12:51.668  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.668  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:51.668  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:51.668  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:51.668  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.668  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.668  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.668  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.668  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63fde30 removed from the list
09-09 17:12:51.668  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.669  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28046aa9 removed from the list
09-09 17:12:51.669  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:51.669  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.669  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:51.669  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.669  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.669  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.669  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.670  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28046aa9 not in the list
09-09 17:12:51.670  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.670  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.670  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.670  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.670  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.670  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fcad5c removed from the list
09-09 17:12:51.670  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.670  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.670  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.670  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.670  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c77fcf removed from the list
09-09 17:12:51.671  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.671  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d900865 added. We now have 2 listener(s)
09-09 17:12:51.671  1037  2081 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:12:51.673  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.673  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.673  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.673  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.673  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c00893a added. We now have 9 listener(s)
09-09 17:12:51.673  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.673  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:12:51.675  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:51.678  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:51.679  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.679  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:51.680  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.680  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.680  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d554348 added. We now have 3 listener(s)
09-09 17:12:51.681  1037  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.681  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.682   328  8165 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-09 17:12:51.684  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.684  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.684  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.684  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.684  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97dc5e1 added. We now have 10 listener(s)
09-09 17:12:51.684  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.684  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:51.684  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:51.684  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:51.685  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:51.685  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:51.687  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:51.687  1037 , 1786 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.690  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:12:51.690  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:12:51.691  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:51.692  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.693  6717  6820 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:12:51.693  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:51.693  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:51.694  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:51.694  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:51.694  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:51.694  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.694  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.694  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.694  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.694  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d900865 removed from the list
09-09 17:12:51.694  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.694  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c00893a removed from the list
09-09 17:12:51.694  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:51.694  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.695  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.695  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.695  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.695  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.695  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.695  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c00893a not in the list
09-09 17:12:51.695  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.695  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.696  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.696  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:51.697  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-09 17:12:51.697  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.697  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.697  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97dc5e1 removed from the list
09-09 17:12:51.697  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.697  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.697  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.697  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.697  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d554348 removed from the list
09-09 17:12:51.697  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.697  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@191f4bf4 added. We now have 2 listener(s)
09-09 17:12:51.698  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,09-09 17:12:51.699  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.699  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.699  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:12:51.699  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.700  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2fdf1d added. We now have 9 listener(s)
09-09 17:12:51.700  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.700  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:12:51.701  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:51.704  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:51.705   328   896 D LGDataListener: argv[0]=dsqncommand
09-09 17:12:51.705   328   896 D LGDataListener: argv[1]=wlan0
09-09 17:12:51.705   328   896 D LGDataListener: argv[2]=1
09-09 17:12:51.705   328   896 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 17:12:51.705  1037  1097 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 17:12:51.705  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.705  1037  1097 D DSQN    : start to monitor internet connection
09-09 17:12:51.705  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:51.706  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.706  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c100b63 added. We now have 3 listener(s)
09-09 17:12:51.706  1037  1718 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.712  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.713  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:51.714  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.714  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.714  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.714  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.714  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27df3360 added. We now have 10 listener(s)
09-09 17:12:51.714  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.714  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:51.715  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:51.715  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:51.715  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:51.715  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:51.715  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:51.718  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:51.718  1037  8161 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 17:12:51.719  1037  8161 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 17:12:51.719  1037  8161 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 17:12:51.720  1037  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.709  8172  8172 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:51.709  8172  8172 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:12:51.724  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:12:51.725  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:12:51.726  8172  8172 I dhcpcd  : version 5.5.6 starting
09-09 17:12:51.726  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:51.727  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.727  8172  8172 E dhcpcd  : get_duid: m
09-09 17:12:51.727  8172  8172 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 17:12:51.727  8172  8172 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-09 17:12:51.728  6717  6820 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 17:12:51.728  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:51.728  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:51.728  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:51.728  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.728  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.728  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.728  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.729  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@191f4bf4 removed from the list
09-09 17:12:51.729  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.729  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2fdf1d removed from the list
09-09 17:12:51.729  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:51.729  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.729  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.729  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.730  1037  8160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 15:12:51 GMT], X-Android-Received-Millis=[1473433971730], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473433971704]}
09-09 17:12:51.730  1037  8160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 17:12:51.730  1037  8160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 17:12:51.730  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.730  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.730  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.731  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2fdf1d not in the list
09-09 17:12:51.731  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.731  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.732  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.733  1037  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 17:12:51.733  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:51.733  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:51.733  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.733  6717  6820 I org.thaliproject.p2p.btconnectorli,b.DiscoveryManager: dispose
09-09 17:12:51.733  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27df3360 removed from the list
09-09 17:12:51.733  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.733  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.733  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.733  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.733  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c100b63 removed from the list
09-09 17:12:51.733  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 17:12:51.733  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:51.733  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:51.733  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 17:12:51.733  1037  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 17:12:51.734  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:51.734  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:12:51.734  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@176dfabf added. We now have 2 listener(s)
09-09 17:12:51.734  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:51.734  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 17:12:51.734  1037  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:12:51.734  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:51.735  1037  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:51.735  1037  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:12:51.735  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:12:51.735  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 17:12:51.735  1882  1882 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:51.735  1882  1882 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>],
09-09 17:12:51.736  1606  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:12:51.737  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.737  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.737  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:12:51.738  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.738  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af4258c added. We now have 9 listener(s)
09-09 17:12:51.738  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.738  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:51.751  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:51.758  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:51.759  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.759  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:51.759  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.759  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2db4ea added. We now have 3 listener(s)
09-09 17:12:51.759  1037  2095 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.761  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.763  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.763  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:12:51.764  8172  8172 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 17:12:51.764  8172  8172 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:12:51.764  8172  8172 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 17:12:51.764  8172  8172 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 17:12:51.764  8172  8172 D dhcpcd  : wlan0: sending REQUEST (xid 0xc765714c), next in 3.92 seconds
09-09 17:12:51.764  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.765  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.765  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.765  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.765  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@269183db added. We now have 10 listener(s)
09-09 17:12:51.765  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.765  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:51.765  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:51.765  6717  6820 I org.thaliproject.p2p.btconn,ectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:51.765  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:51.765  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:51.766  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.767  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:12:51.768  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:51.768  1037  1786 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.772  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:12:51.772  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:12:51.776  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:51.776  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.777  6717  6820 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:12:51.779  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:51.779  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:12:51.779  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:51.779  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.779  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.779  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.779  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.779  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@176dfabf removed from the list
09-09 17:12:51.779  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.779  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af4258c removed from the list
09-09 17:12:51.779  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:51.779  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.780  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.780  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.780  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.780  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.780  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.781  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af4258c not in the list
09-09 17:12:51.781  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.781  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.781  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.782  6717  6820 D BluetoothLeScanner: could not find callback wrapper
09-09 17:12:51.782  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:51.782  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.782  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.782  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@269183db removed from the list
09-09 17:12:51.782  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.782  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.782  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.782  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.782  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2db4ea removed from the list
09-09 17:12,:51.783  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.783  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaa35b6 added. We now have 2 listener(s)
09-09 17:12:51.783  1037  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.785  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.785  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.785  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.785  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.785  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79a82b7 added. We now have 9 listener(s)
09-09 17:12:51.785  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.786  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:51.788  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:51.790  6717  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:51.792  6717  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:51.792  6717  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:51.792  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:51.792  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aabc98d added. We now have 3 listener(s)
09-09 17:12:51.792  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:12:51.793  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.794  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:12:51.794  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:51.795  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:51.795  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:51.795  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@129bf742 added. We now have 10 listener(s)
09-09 17:12:51.795  6717  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:51.795  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:51.795  6717  6820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:51.795  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:51.795  6717  6820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:51.795  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.795  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.795  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:51.795  6717  6820 I org.thal,iproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.795  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaa35b6 removed from the list
09-09 17:12:51.795  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.795  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79a82b7 removed from the list
09-09 17:12:51.795  6717  6820 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:51.795  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.796  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.796  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.796  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.796  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.796  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:51.796  6717  6820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79a82b7 not in the list
09-09 17:12:51.796  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.796  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.797  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:51.797  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:51.797  6717  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:51.797  6717  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@129bf742 removed from the list
09-09 17:12:51.797  6717  6820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:51.797  6717  6820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:51.797  6717  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:51.797  6717  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:51.797  6717  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aabc98d removed from the list
09-09 17:12:51.798  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 17:12:51.798  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 17:12:51.799  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 17:12:51.799  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:51.799  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 17:12:51.799  6717  6820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:51.803  8172  8172 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-09 17:12:51.808  6717  8179 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
09-09 17:12:51.808  6717  8179 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: My test thread name)
09-09 17:12:51.809  6717  8179 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 17:12:51.810  6717  8180 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
09-09 17:12:51.811  6717  8180 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: My test thread name)
09-09 17:12:51.811  6717  8180 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 17:12:51.812  6717  6820 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 17:12:51.812  6717  6820 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 17:12:51.813  6717  6820 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 17:12:51.813  6717  6820 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 17:12:51.813  6717  6820 D com.test.thalitest.ThaliTestRunner: Total duration: 22845 ms
09-09 17:12:51.814  6717  6820 I jxcore-log: *Native tests were executed*
09-09 17:12:51.814  6717  6820 I jxcore-log: 
09-09 17:12:51.814  6717  6820 I jxcore-log: Total number of executed tests:  80
09-09 17:12:51.814  6717  6820 I jxcore-log: 
09-09 17:12:51.814  6717  6820 I jxcore-log: Number of passed tests:  80
09-09 17:12:51.814  6717  6820 I jxcore-log: 
09-09 17:12:51.815  6717  6820 I jxcore-log: Number of failed tests:  0
09-09 17:12:51.815  6717  6820 I jxcore-log: 
09-09 17:12:51.815  6717  6820 I jxcore-log: Number of ignored tests:  0
09-09 17:12:51.815  6717  6820 I jxcore-log: 
09-09 17:12:51.815  6717  6820 I jxcore-log: Total duration:  22845
09-09 17:12:51.815  6717  6820 I jxcore-log: 
09-09 17:12:51.815  6717  6820 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 17:12:51.815  6717  6820 I jxcore-log: 
09-09 17:12:51.819  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.819  6717  6820 I jxcore-log: 
09-09 17:12:51.823  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.823  6717  6820 I jxcore-log: 
09-09 17:12:51.824  6717  6717 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 17:12:51.824  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.824  6717  6820 I jxcore-log: 
09-09 17:12:51.825  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.825  6717  6820 I jxcore-log: 
09-09 17:12:51.826  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.826  6717  6820 I jxcore-log: 
09-09 17:12:51.828  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.828  6717  6820 I jxcore-log: 
09-09 17:12:51.831  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:51.831  6717  6820 I jxcore-log: 
09-09 17:12:51.833  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:51.833  6717  6820 I jxcore-log: 
09-09 17:12:51.834  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.834  6717  6820 I jxcore-log: 
09-09 17:12:51.834  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.834  6717  6820 I jxcore-log: 
09-09 17:12:51.835  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:12:51.835  6717  6820 I jxcore-log: 
,09-09 17:12:51.837  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:51.837  6717  6820 I jxcore-log: 
09-09 17:12:51.838  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:51.838  6717  6820 I jxcore-log: 
09-09 17:12:51.838  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.838  6717  6820 I jxcore-log: 
09-09 17:12:51.839  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.839  6717  6820 I jxcore-log: 
09-09 17:12:51.840  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.840  6717  6820 I jxcore-log: 
09-09 17:12:51.840  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.840  6717  6820 I jxcore-log: 
09-09 17:12:51.841  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.841  6717  6820 I jxcore-log: 
09-09 17:12:51.842  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.842  6717  6820 I jxcore-log: 
09-09 17:12:51.842  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.842  6717  6820 I jxcore-log: 
09-09 17:12:51.843  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:51.843  6717  6820 I jxcore-log: 
09-09 17:12:51.844  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:12:51.844  6717  6820 I jxcore-log: 
09-09 17:12:51.845  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:12:51.845  6717  6820 I jxcore-log: 
09-09 17:12:51.845  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.845  6717  6820 I jxcore-log: 
09-09 17:12:51.846  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.846  6717  6820 I jxcore-log: 
,09-09 17:12:51.847  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.847  6717  6820 I jxcore-log: 
09-09 17:12:51.847  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.847  6717  6820 I jxcore-log: 
09-09 17:12:51.848  6717  6820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:51.848  6717  6820 I jxcore-log: 
,09-09 17:12:51.852  8172  8172 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 17:12:51.853  8172  8172 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 17:12:51.853  8172  8172 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 17:12:51.853  8172  8172 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 17:12:51.854  8172  8172 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 17:12:51.854  8172  8172 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 17:12:51.854  8172  8172 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:12:51.854  8172  8172 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 17:12:51.888  8143  8143 W ExternalStrings: load override strings
09-09 17:12:51.888  8143  8143 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:12:51.888  8143  8143 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-09 17:12:51.890  8143  8143 D StatusProvider: onCreate
,09-09 17:12:51.926  8143  8143 V Signer  : override build config not found
,09-09 17:12:51.927  8143  8143 D Signer  : value of property debug is false
,09-09 17:12:51.949  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-09 17:12:51.949  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-09 17:12:51.949  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-09 17:12:51.949  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-09 17:12:51.949  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-09 17:12:51.949  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-09 17:12:51.950  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-09 17:12:51.950  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-09 17:12:51.950  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-09 17:12:51.950  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-09 17:12:51.950  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-09 17:12:51.950  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-09 17:12:51.950  8143  8143 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,09-09 17:12:51.962  8143  8143 V LGMDMManager: Create singleton instance
,09-09 17:12:52.027  8143  8143 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-09 17:12:52.090  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:52.091  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 17:12:52.110  8185  8185 D AndroidRuntime: 
09-09 17:12:52.110  8185  8185 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 17:12:52.112  8185  8185 D AndroidRuntime: CheckJNI is OFF
09-09 17:12:52.115  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:52.119  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.122  1037  8161 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 17:12:52.123  1037  8161 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 17:12:52.123  1037  8161 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:12:52.123  1037  8161 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 17:12:52.123  1037  8161 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 17:12:52.123  1037  8161 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:12:52.123  1037  8161 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 17:12:52.123  1037  8161 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 17:12:52.123  1037  8161 D DhcpStateMachine: RunningState
,09-09 17:12:52.124  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.124  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.126  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:12:52.128  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:52.129  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:52.136  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:52.141  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.146  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.146  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.148  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 17:12:52.152  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 17:12:52.154  6932  6932 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 17:12:52.157  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:12:52.157  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:12:52.157  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:12:52.157  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:12:52.157  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:12:52.158  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:12:52.158  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 17:12:52.158  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:12:52.158  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:12:52.158  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:12:52.158  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 17:12:52.159  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:12:52.234  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:52.235  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:52.236  8185  8185 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 17:12:52.243  8143  8204 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 17:12:52.255  1037  1095 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-09 17:12:52.255  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:52.255  1037  1095 I ActivityManager: Killing 6717:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-09 17:12:52.260  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.312  1037  2328 I WindowState: WIN DEATH: Window{139067b2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 17:12:52.312  1037  1546 D WifiService: Client connection lost with reason: 4
,09-09 17:12:52.323  1037  2328 D InputDispatcher: Window went away: Window{139067b2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 17:12:52.447  1037  1095 I ActivityManager:   Force finishing activity ActivityRecord{be6b27f u0 com.test.thalitest/.MainActivity t6}
,09-09 17:12:52.503   353   378 E GBMv2   : DFP En is all cleared set to be enabled
,09-09 17:12:52.510  1037  2010 W ActivityManager: Spurious death for ProcessRecord{2cd4f834 6717:com.test.thalitest/u0a118}, curProc for 6717: null
,09-09 17:12:52.512  1037  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-09 17:12:52.515  1037  1105 I ActivityManager:   Force finishing activity ActivityRecord{be6b27f u0 com.test.thalitest/.MainActivity t6 f}
09-09 17:12:52.515  1037  1105 W ActivityManager: Duplicate finish request for ActivityRecord{be6b27f u0 com.test.thalitest/.MainActivity t6 f}
,09-09 17:12:52.547  2096  2096 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-09 17:12:52.549  1978  1995 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-09 17:12:52.549  1978  1995 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23ecef9e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 17:12:52.549  2096  2096 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,09-09 17:12:52.550  1978  1994 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-09 17:12:52.550  1978  1994 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f185a7f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 17:12:52.554  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-09 17:12:52.555  2096  2174 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-09 17:12:52.560  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-09 17:12:52.576  2471  2594 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 17:12:52.583  2042  2042 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 17:12:52.585  3814  3814 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-09 17:12:52.591  7724  7724 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-09 17:12:52.591  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-09 17:12:52.612  1037  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 17:12:52.615  4515  4515 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 17:12:52.616  4515  4515 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-09 17:12:52.616  4515  4515 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 17:12:52.616  4515  4515 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-09 17:12:52.616  4515  4515 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:12:52.616  4515  4515 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:12:52.616  4515  4515 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:52.616  4515  4515 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:12:52.616  4515  4515 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:52.617  4515  4515 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:12:52.617  4515  4515 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:12:52.617  4515  4515 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:12:52.649  4614  4614 I art     : Explicit concurrent mark sweep GC freed 8181(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 574us total 120.133ms
,09-09 17:12:52.662  1037  1094 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-09 17:12:52.671  1037  1037 D administrator: Handling package changes for user 0
09-09 17:12:52.678  1933  1933 D ActionManagerService: notifyUserLog: 1000003
,09-09 17:12:52.679  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-09 17:12:52.681  2096  2096 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-09 17:12:52.683  2096  2096 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-09 17:12:52.684  2096  2096 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-09 17:12:52.687  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-09 17:12:52.688  3814  3830 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262123
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , expire_time: 0
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , display: false
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , animation: false }
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262287
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , expire_time: 0
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , display: false
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , animation: false }
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , create_time: 1473420113195
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , expire_time: 0
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , display: false
09-09 17:12:52.690  2096  2096 I GBoardWebViewUtils: , animation: false }
,09-09 17:12:52.698  1933  1933 D ActionManagerService: notifyUserLog: 1000004
09-09 17:12:52.699  3814  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-09 17:12:52.699  3814  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-09 17:12:52.701  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-09 17:12:52.703  2096  8242 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-09 17:12:52.704  1037  2054 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:52.712  1899  1899 D SplitUIManager: split_name #11 / not available #0
09-09 17:12:52.713  1899  1899 D SplitUIService: removed split : 
09-09 17:12:52.714  1606  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 17:12:52.714  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.724  1606  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 17:12:52.724  1606  1659 D KeyguardModel: createShortcutInfo...
,09-09 17:12:52.725  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-09 17:12:52.726  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-09 17:12:52.727  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.727  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.728  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:52.728  1606  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 17:12:52.728  1606  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:52.729  1606  1659 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 17:12:52.730  1606  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 17:12:52.735  1606  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:12:52.735  1606  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-09 17:12:52.741  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:52.741  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:52.742  1606  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 17:12:52.742  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.747  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 17:12:52.747  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-09 17:12:52.748  1606  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 17:12:52.748  1606  1659 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:12:52.761  1037  1052 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:52.762  1037  1052 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:52.764  1899  1899 D SplitUIManager: split_name #11 / not available #0
09-09 17:12:52.764  1899  1899 I SplitUIService: split app #11
09-09 17:12:52.764  1606  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:12:52.764  1606  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 17:12:52.765  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:52.769  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.781  1606  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 17:12:52.782  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.788  1606  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:52.788  1606  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 17:12:52.788  1606  1659 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 17:12:52.788  1606  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 17:12:52.794  1606  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:12:52.794  1606  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 17:12:52.794  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.794  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.795  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:52.813  1037  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:52.814  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:52.814  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:52.815  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:52.816  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:52.816  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:12:52.817  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-09 17:12:52.817  1037  1547 D ConnectivityService: identical MTU - not setting
09-09 17:12:52.817  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 17:12:52.817  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:52.817  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:12:52.817  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 17:12:52.820  1606  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 17:12:52.820  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.823  1606  1606 D KeyguardModel: handleShortcutListChanged...
09-09 17:12:52.823  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 17:12:52.826  1606  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 17:12:52.826  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.828  1037  1780 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:12:52.828  7724  7724 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 17:12:52.829  1606  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 17:12:52.829  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.818  1037  1547 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:12:52.833  1606  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:12:52.833  1606  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 17:12:52.833  1606  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 17:12:52.834  1606  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 17:12:52.834  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.838  1606  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:12:52.838  1606  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 17:12:52.838  1606  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 17:12:52.838  1606  1659 D KeyguardModel: createShortcutInfo...
09-09 17:12:52.839  1606  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:12:52.839  1606  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 17:12:52.840  1606  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 17:12:52.840  1606  1659 D KeyguardModel: createShortcutInfo...
,09-09 17:12:52.850  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:52.850  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:52.851  2096  2096 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-09 17:12:52.855  1606  1606 D KeyguardModel: handleShortcutListChanged...
09-09 17:12:52.855  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-09 17:12:52.861  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:52.877  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.877  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-09 17:12:52.877  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 17:12:52.878  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 17:12:52.879  1037  1581 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-09 17:12:52.881  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.881  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.882  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:52.885  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:52.885  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:52.889  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:52.892  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.896  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.897  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.897  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:52.902  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:12:52.902  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:52.911  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:52.913  1037  2007 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:12:52.922  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.923  8143  8204 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:12:52.923  8143  8204 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:12:52.927  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:12:52.927  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-09 17:12:52.928  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.929  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:52.931  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:12:52.932  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-09 17:12:52.934  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-09 17:12:52.935  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 17:12:52.936  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:52.936  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-09 17:12:52.937  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:52.949  1037  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{124643ae u0 com.lge.launcher2/.Launcher t5} time:141826
,09-09 17:12:52.955  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-09 17:12:52.956  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:12:52.960  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:52.963  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.965  2096  2300 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 17:12:52.968  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.968  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.968  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:52.970  2096  2300 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 17:12:52.970  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:52.972  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 17:12:52.975  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-09 17:12:52.976  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 17:12:52.976  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:12:52.976  1037  1105 I art     : Explicit concurrent mark sweep GC freed 79031(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.109ms total 429.528ms
09-09 17:12:52.978  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:52.984  2096  2096 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-09 17:12:52.984  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:52.995  2665  2665 D [Concierge]Service: onStartCommand(). Type : 8
09-09 17:12:52.995  2665  2665 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-09 17:12:52.997  2096  2096 D [Concierge]WidgetView: change position of spinner
,09-09 17:12:52.998  2096  2096 I [Concierge]WidgetView: initWebView(). Time : 1473433972998
09-09 17:12:52.999  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:52.999  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:52.999  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:12:53.004  2665  2665 D [Concierge]Service: Update widget ID : 11
09-09 17:12:53.004  2665  2665 D [Concierge]Service: onStartCommand(). Type : 0
09-09 17:12:53.007  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:53.007  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:53.015  8185  8185 D AndroidRuntime: Shutting down VM
,09-09 17:12:53.043  8099  8099 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 17:12:53.055  8143  8204 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-09 17:12:53.076  1037  1105 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8253 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 17:12:53.077  2096  2096 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 70138358
09-09 17:12:53.077  2096  2096 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-09 17:12:53.077  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 17:12:53.080  2096  2096 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@12858977
09-09 17:12:53.081  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-09 17:12:53.082  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 17:12:53.082  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:12:53.087  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-09 17:12:53.088  2096  2096 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-09 17:12:53.088  2096  2096 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-09 17:12:53.089  2096  2096 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473433859183, New one : 1473433972998
09-09 17:12:53.089  2096  2096 D [Concierge]WidgetView: Unregister all receivers
09-09 17:12:53.089  2096  2096 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 17:12:53.090  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:12:53.092  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:12:53.092  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 17:12:53.093  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-09 17:12:53.094  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-09 17:12:53.095  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:12:53.095  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-09 17:12:53.096  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-09 17:12:53.099  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:12:53.099  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 17:12:53.112  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:12:53.134  8143  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-09 17:12:53.135  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 17:12:53.137  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:53.137  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:53.138  6989  6989 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 17:12:53.138  6989  6989 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:12:53.138  6989  6989 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 17:12:53.143  2096  2096 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-09 17:12:53.143  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-09 17:12:53.144  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:12:53.146  1037  1786 I ActivityManager: Killing 7312:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-09 17:12:53.147  8143  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-09 17:12:53.148  8143  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-09 17:12:53.149  8143  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,09-09 17:12:53.150  8143  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-09 17:12:53.150  8143  8204 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-09 17:12:53.158  8143  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-09 17:12:53.160  8143  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-09 17:12:53.163  2096  2096 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25bf9343 time:142041
,09-09 17:12:53.181  1037  1094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:12:53.185  1037  1094 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 17:12:53.246  1037  2095 W libprocessgroup: failed to open /acct/uid_10005/pid_7312/cgroup.procs: No such file or directory
,09-09 17:12:53.248  1037  1385 V AlarmManager: RTC_WAKEUP set : Alarm{284f58fd type 0 when 1473433965852 com.google.android.gms} when 1473433965852
09-09 17:12:53.249  1037  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{279429f2 type 2 when 142072 com.google.android.gms} when 142072
09-09 17:12:53.249  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 17:12:53.251  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:12:53.253  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:12:53.259  8099  8099 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 17:12:53.259  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:12:53.267  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:12:53.279  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:12:53.292  2096  2096 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-09 17:12:53.295  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:12:53.295  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:12:53.296  6989  6989 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 17:12:53.297  6989  6989 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:12:53.298  6989  6989 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 17:12:53.302  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:12:53.304  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-09 17:12:53.305  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:12:53.307  8143  8143 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 17:12:53.308  1037  1786 I ActivityManager: Killing 7752:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 17:12:53.310  8143  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 17:12:53.330  2096  2918 I GBoardtInterface: onReloaded()
,09-09 17:12:53.333  2096  2096 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-09 17:12:53.354  1846  1846 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-09 17:12:53.354  1037  2018 W libprocessgroup: failed to open /acct/uid_10072/pid_7752/cgroup.procs: No such file or directory
,09-09 17:12:53.356  8143  8272 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/keyword_list'.
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.ag.a(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.d.f(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.d.a(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.r.a(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.s.b(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.ak.a(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.ae.a(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.r.a(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.s.run(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:53.356  8143  8272 E SQLiteDatabase: 	at com.mcafee.csf.frame.q.run(Unknown Source)
09-09 17:12:53.357  3814  4500 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: Couldn't open keyword_list for writing (will try read-only):
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in re,ad/write mode.
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.ag.a(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.d.f(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.d.a(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.r.a(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.s.b(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.ak.a(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.ae.a(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.r.a(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.s.run(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:53.357  8143  8272 E SQLiteOpenHelper: 	at com.mcafee.csf.frame.q.run(Unknown Source)
09-09 17:12:53.358  8143  8272 W SQLiteOpenHelper: Opened keyword_list in read-only mode
09-09 17:12:53.363  2206  2206 I ConfigService: onCreate
09-09 17:12:53.363  2206  2206 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-09 17:12:53.363  3814  3830 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:12:53.365  1846  1846 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest c,mp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-09 17:12:53.365  1846  3962 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at com.google.android.gms.config.h.run(SourceFile:121)
09-09 17:12:53.367  2206  8274 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at com.google.android.gms.config.h.run(SourceFile:121)
09-09 17:12:53.367  2206  8274 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:12:53.369  2206  8274 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 17:12:53.370  2206  2206 I ConfigService: onBind returning update interface
09-09 17:12:53.371  2206  2206 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-09 17:12:53.371  2206  2206 I ConfigService: onBind returning config service
09-09 17:12:53.378  2206  2206 I ConfigService: onDestroy
09-09 17:12:53.379  1933  1933 D ActionManagerService: notifyUserLog: 1000001
09-09 17:12:53.380  1846  8276 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-09 17:12:53.382  3814  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 17:12:53.382  3814  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 17:12:53.382  1933  1933 D ActionManagerService: notifyUserLog: 1000001
09-09 17:12:53.383  3814  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 17:12:53.384  3814  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 17:12:53.384  3814  4514 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-09 17:12:53.384  3814  4514 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-09 17:12:53.385  3814  4500 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:12:53.388  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-09 17:12:53.388  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-09 17:12:53.391  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,09-09 17:12:53.391  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 17:12:53.394  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-09 17:12:53.394  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/instrumenthistory'.
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.instrumentation.a.a(Unknown Source)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.instrumentation.d.a(Unknown Source)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.instrumentation.InstrumentationComponent.a(Unknown Source)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:12:53.427  8143  8204 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
,09-09 17:12:53.430  7113  7113 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: Error inserting package=com.test.thalitest
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:12:53.431  7113  7113 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:12:53.441  2302  2431 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.443  2302  2431 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:53.450  5983  8282 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.451,  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.451  1846  8281 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.451  1846  8281 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:53.453  1846  8281 W SQLiteOpenHelper: Opened metrics.db in read-only mode
,09-09 17:12:53.454  1846  8281 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
--------- beginning of crash
09-09 17:12:53.456  1846  8281 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
09-09 17:12:53.456  1846  8281 E AndroidRuntime: Process: com.google.android.gms, PID: 1846
09-09 17:12:53.456  1846  8281 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.456  1846  8281 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:53.457  1846  8284 I PeopleContactsSync: CP2 sync disabled
09-09 17:12:53.468  2302  8285 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOp,enHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
09-09 17:12:53.468  1846  8286 E SQLiteDatabase: 	at com.google.android.gms.drive.database.l.run(SourceFile:519)
,09-09 17:12:53.468  1846  8286 I Process : Sending signal. PID: 1846 SIG: 9
09-09 17:12:53.484  1037  2081 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8287 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 17:12:53.487  1037  1546 D WifiService: Client connection lost with reason: 4
09-09 17:12:53.491  2302  8285 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-09 17:12:53.492  1037  2018 W ActivityManager: Exception when destroying service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks
09-09 17:12:53.492  1037  2018 W ActivityManager: android.os.DeadObjectException
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1681)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1593)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at com.android.server.am.ActiveServices.stopServiceTokenLocked(ActiveServices.java:552)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at com.android.server.am.ActivityManagerService.stopServiceToken(ActivityManagerService.java:15237)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:921)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
09-09 17:12:53.492  1037  2018 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 17:12:53.492  2302  8285 E AndroidRuntime: Process: android.process.acore, PID: 2302
09-09 17:12:53.492  2302  8285 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:12:53.492  2302  8285 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 17:12:53.497  1037  8303 E DropBoxManagerService: 	... 5 more
09-09 17:12:53.543  1037  1973 I ActivityManager: Process com.google.android.gms (pid 1846) has died

```
