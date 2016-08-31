#### Test 828833414094bc4_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 11:01:45.793  6492  6492 D DocsApplication: Installing DEX configuration.
08-31 11:01:45.818  6492  6492 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-31 11:01:45.830  6492  6492 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2532065a com.google.android.apps.docs}
08-31 11:01:45.848  6492  6492 D TAG     : onCreate()
08-31 11:01:45.883  6492  6492 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-31 11:01:46.493   330   444 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 11:01:46.497  3204  6529 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-31 11:01:46.660  1816  4755 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-31 11:01:46.692  1816  4755 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-31 11:01:46.774  6531  6531 D AndroidRuntime: 
08-31 11:01:46.774  6531  6531 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:01:46.776  6531  6531 D AndroidRuntime: CheckJNI is OFF
08-31 11:01:46.804  1816  4755 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-31 11:01:46.942  6531  6531 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 11:01:46.955  1036  1936 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 11:01:46.987  1942  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 11:01:46.991  1036  1936 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 11:01:46.993  1036  1936 D ActivityManager: setTaskToReturnTo : TaskRecord{1e9da1a3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 11:01:46.993  1036  1936 D ActivityManager: setTaskToReturnTo : TaskRecord{1e9da1a3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 11:01:46.994  1036  1936 D WindowStateEx: AppWindowTokenEx init.. 
08-31 11:01:46.995   343   364 E GBMv2   : DFP En is all cleared set to be enabled
08-31 11:01:47.040  1036  1936 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6558 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:01:47.041  6531  6531 D AndroidRuntime: Shutting down VM
08-31 11:01:47.055   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 280us total 13.919ms
08-31 11:01:47.068   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 12.287ms
08-31 11:01:47.079   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 11.300ms
08-31 11:01:47.108  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 11:01:47.109  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23a0e0f6 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 11:01:47.112  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 11:01:47.113  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{244eecf7 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 11:01:47.145  6558  6558 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 11:01:47.207  6558  6558 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-31 11:01:47.212  6558  6558 I LibraryLoader: Loading: webviewchromium
08-31 11:01:47.214  6558  6558 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2841-2843)
08-31 11:01:47.215  6558  6558 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:01:47.227  6558  6558 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1347e014}
08-31 11:01:47.227  6558  6558 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:01:47.228  6558  6558 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:01:47.234  6558  6558 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 11:01:47.235  6558  6558 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:01:47.245  6558  6558 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 11:01:47.246  6558  6558 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 11:01:47.247  6558  6558 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-31 11:01:47.249   321  1396 V AudioPolicyService: registerClient() client 0xb14bfb60, uid 10118
08-31 11:01:47.256  1036  1118 D BluetoothManagerService: Message: 20
08-31 11:01:47.256  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c73b915:true
08-31 11:01:47.259  6558  6558 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:01:47.259  6558  6558 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:01:47.259  6558  6558 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:01:47.259  6558  6558 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:01:47.259  6558  6558 I Adreno-EGL: Remote Branch: 
08-31 11:01:47.259  6558  6558 I Adreno-EGL: Local Patches: 
08-31 11:01:47.259  6558  6558 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:01:47.351  6558  6588 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 11:01:47.359  6558  6558 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 11:01:47.374  6492  6492 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:01:47.374  6492  6492 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:01:47.375  6558  6558 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:01:47.379  6558  6558 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 11:01:47.382  6558  6558 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 11:01:47.384  6558  6558 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 11:01:47.384  6558  6558 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 11:01:47.397  6558  6558 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 11:01:47.403  6558  6558 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:01:47.403  6558  6558 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:01:47.444  6558  6602 D OpenGLRenderer: Render dirty regions requested: true
08-31 11:01:47.444  6558  6602 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 11:01:47.455  6558  6602 D OpenGLRenderer: Enabling debug mode 0
,08-31 11:01:47.466  6558  6558 D Atlas   : Validating map...
08-31 11:01:47.469  1036  1922 D SplitWindow: check instance of lgWin Window{38b659e7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:01:47.510  6558  6599 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:01:47.510  6558  6599 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:01:47.525  6128  6128 I LockScreenSettings: New app installed broadcast received ..
,08-31 11:01:47.527  6128  6128 I LockScreenSettings: Number of installed packages  1
08-31 11:01:47.533  6492  6492 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-31 11:01:47.579  1036  2033 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:01:47.594  6558  6558 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3436b5f3 time:103223
,08-31 11:01:47.620  1036  1995 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6620 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:01:47.621  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +516ms (total +627ms)
08-31 11:01:47.624  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{376faca0 u0 com.test.thalitest/.MainActivity t6} time:103253
,08-31 11:01:47.701  6558  6558 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 11:01:47.701  6558  6558 I chromium: 
,08-31 11:01:47.706  6620  6620 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-31 11:01:47.706  6620  6620 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-31 11:01:47.736  6558  6558 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 11:01:47.761  1036  1996 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6639 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-31 11:01:47.763  1036  1996 I ActivityManager: Killing 5825:com.google.android.gm/u0a64 (adj 15): empty #17
,08-31 11:01:47.826  6558  6599 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 11:01:47.826  6558  6599 I chromium: 
,08-31 11:01:47.866  1036  1758 W libprocessgroup: failed to open /acct/uid_10064/pid_5825/cgroup.procs: No such file or directory
,08-31 11:01:47.952  6639  6639 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-31 11:01:47.952  6558  6659 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435150848
08-31 11:01:47.967  6558  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:01:47.967  6558  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:01:47.967  6558  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:01:47.967  6558  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:01:47.967  6558  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 11:01:47.968  6558  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac2847 added. We now have 1 listener(s)
08-31 11:01:47.973  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:01:47.975  6558  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 11:01:47.978  6639  6639 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 11:01:47.978  6558  6659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:01:47.979  6558  6659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:01:47.980  6558  6659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:01:47.983  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 11:01:47.988  6558  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbc612 added. We now have 1 listener(s)
08-31 11:01:47.988  6558  6659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:01:47.995  1036  1474 D WifiService: New client listening to asynchronous messages
,08-31 11:01:47.999  6558  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:01:47.999  6558  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 11:01:48.002  6558  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 11:01:48.002  6558  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-31 11:01:48.002  6558  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 11:01:48.006  6558  6659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:01:48.009  1036  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:01:48.012  6558  6659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 11:01:48.020  6558  6659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:01:48.020  6558  6659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:01:48.020  6558  6659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-31 11:01:48.020  6558  6659 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:01:48.022  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:01:48.023  6558  6659 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:01:48.024  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:01:48.028  1036  1891 I ActivityManager: Killing 5868:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 11:01:48.058  6558  6558 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:01:48.165  1036  1574 W libprocessgroup: failed to open /acct/uid_10072/pid_5868/cgroup.procs: No such file or directory
,08-31 11:01:48.327   343   367 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 11:01:48.327   343   367 E GBMv2   : Set value is all cleared set the max
08-31 11:01:48.327   343   367 I GBMv2   : DFP Enabled. Ignore VFP set
,08-31 11:01:48.985  6558  6663 W jxcore-log: Initializing JXcore engine
08-31 11:01:48.986  6558  6663 W jxcore-log: JXcore engine is ready
,08-31 11:01:49.068  6663  6663 W Thread-737: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8369]" dev="sockfs" ino=8369 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 11:01:49.068  6663  6663 W Thread-737: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-31 11:01:49.068  6663  6663 W Thread-737: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7785]" dev="sockfs" ino=7785 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 11:01:49.068  6663  6663 W Thread-737: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 11:01:49.068  6663  6663 W Thread-737: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31053]" dev="sockfs" ino=31053 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 11:01:49.105  6558  6663 W jxcore-log: Starting JXcore engine
,08-31 11:01:49.230  6558  6663 W jxcore-log: Platform android
08-31 11:01:49.230  6558  6663 W jxcore-log: 
08-31 11:01:49.230  6558  6663 W jxcore-log: Process ARCH arm
08-31 11:01:49.230  6558  6663 W jxcore-log: 
,08-31 11:01:49.430  6558  6663 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:01:49.430  6558  6663 I jxcore-log: 
,08-31 11:01:49.431  6558  6663 W jxcore-log: JXcore engine is started
,08-31 11:01:49.437  6558  6659 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 11:01:49.439  6558  6558 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-31 11:01:50.701  2807  2807 I MusicWidget: mDelayedStopHandler : unbind
08-31 11:01:50.703  2133  2133 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-31 11:01:50.703  2133  2133 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-31 11:01:50.703  2133  2133 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-31 11:01:50.705  2133  2133 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-31 11:01:50.705  2133  2133 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-31 11:01:50.705  2133  2133 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-31 11:01:50.707  2133  2133 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-31 11:01:50.707  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-31 11:01:50.708  1036  1995 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@35ae8062com.lge.music.MediaPlaybackService$5@3436b5f3
08-31 11:01:50.708  2133  2133 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-31 11:01:50.708  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.709  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.710  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-31 11:01:50.710  2133  2133 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1ecce980
08-31 11:01:50.711  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-31 11:01:50.711  2133  2133 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-31 11:01:50.712  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.712  2133  2133 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,08-31 11:01:50.713  2133  2133 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-31 11:01:50.713  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.713  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.714  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.714  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.715  2133  2133 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:01:50.722  2133  2133 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-31 11:01:50.724  2133  2133 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-31 11:01:50.724  2133  2133 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-31 11:01:50.724  2133  2133 V MediaPlayer[Native]: reset
08-31 11:01:50.730  2133  2133 V MediaPlayer[Native]: setListener
08-31 11:01:50.730  2133  2133 V MediaPlayer[Native]: disconnect
08-31 11:01:50.730  2133  2133 V MediaPlayer[Native]: destructor
08-31 11:01:50.731   321   321 V AudioFlinger: releasing 16 from 2133 for -1
08-31 11:01:50.731   321   321 V AudioFlinger:  decremented refcount to 0
08-31 11:01:50.731   321   321 V AudioFlinger: purging stale effects
08-31 11:01:50.731  2133  2133 V MediaPlayer[Native]: disconnect
08-31 11:01:50.733  2133  2133 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-31 11:01:50.734  2133  2133 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-31 11:01:50.734  2133  2133 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-31 11:01:50.735  2133  2133 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-31 11:01:50.735  2133  2133 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
,08-31 11:01:50.736  2133  2133 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-31 11:01:50.736  2133  2133 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 330150576
08-31 11:01:50.736  2133  2133 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 330150576
08-31 11:01:50.749  2133  2133 I SmartShareClient: [SmartShareManagerClient] terminate service: 2133/MediaPlaybackService/838479398
08-31 11:01:50.762  2133  2133 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-31 11:01:50.762  2133  2133 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3186e529
,08-31 11:01:50.764  2133  2133 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-31 11:01:50.764  2133  2133 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-31 11:01:50.765  2133  2133 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-31 11:01:50.765  2133  2133 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-31 11:01:50.772  1036  1959 I ActivityManager: Killing 5659:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 11:01:50.773  2133  2133 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
08-31 11:01:50.781  5632  5632 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 11:01:50.781  5632  5632 W System.err: android.os.DeadObjectException
08-31 11:01:50.781  5632  5632 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:01:50.781  5632  5632 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:01:50.781  5632  5632 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 11:01:50.781  5632  5632 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 11:01:50.781  5632  5632 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:01:50.781  5632  5632 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:01:50.781  5632  5632 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:01:50.781  5632  5632 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:01:50.781  5632  5632 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:01:50.781  5632  5632 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:01:50.781  5632  5632 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:01:50.781  5632  5632 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:01:50.781  5632  5632 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:01:50.781  5632  5632 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:01:50.782  5632  5632 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 11:01:50.782  5632  5632 W System.err: android.os.DeadObjectException
08-31 11:01:50.782  5632  5632 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:01:50.782  5632  5632 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:01:50.782  5632  5632 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 11:01:50.782  5632  5632 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 11:01:50.782  5632  5632 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:01:50.782  5632  5632 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:01:50.782  5632  5632 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:01:50.782  5632  5632 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:01:50.782  5632  5632 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:01:50.782  5632  5632 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:01:50.782  5632  5632 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:01:50.782  5632  5632 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:01:50.782  5632  5632 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.r,un(ZygoteInit.java:909)
08-31 11:01:50.782  5632  5632 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:01:50.782  5632  5632 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 11:01:50.782  5632  5632 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-31 11:01:50.993  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_5659/cgroup.procs: No such file or directory
,08-31 11:01:50.993  1036  1052 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 11:01:50.998  5632  5632 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 11:01:50.998  5632  5632 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:01:51.035  1036  1996 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6668 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:01:51.036  5632  5632 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 11:01:51.098  6668  6668 D UEI.SmartControl: Quickset Services start...
08-31 11:01:51.100  6668  6668 I UEI.SmartControl: Manufacture = LGE
08-31 11:01:51.100  6668  6668 D UEI.SmartControl: Id = LGNevo
08-31 11:01:51.102  6668  6668 D UEI.SmartControl: File observer start...
08-31 11:01:51.102  6668  6668 E UEI.SmartControl: IR Port is disabled: false
,08-31 11:01:51.103  6668  6668 D UEI.SmartControl: Starting file observer...
08-31 11:01:51.104  6668  6668 D UEI.SmartControl: Extracting JNI libs...
08-31 11:01:51.104  6668  6668 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 11:01:51.195  6668  6668 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 11:01:51.195  6668  6668 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 11:01:51.195  6668  6668 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 11:01:51.233  6668  6668 I UEI.SmartControl: --- Selecting new region: 6
,08-31 11:01:51.236  6668  6668 I UEI.SmartControl: Model = LG-D855
,08-31 11:01:51.238  6668  6668 D UEI.SmartControl: QS Service created
08-31 11:01:51.254  6668  6668 I UEI.SmartControl: Service initServices...
,08-31 11:01:51.260  6668  6668 D UEI.SmartControl: QS start get config
,08-31 11:01:51.324  6668  6668 D UEI.SmartControl: Loading JNI Libs...
,08-31 11:01:51.461  6492  6492 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-31 11:01:51.465  1036  1051 I ActivityManager: Killing 5632:com.lge.qremote/u0a112 (adj 15): empty #17
,08-31 11:01:51.579  6668  6668 I UEI.SmartControl: Supports setup maps: true
,08-31 11:01:51.583  6668  6668 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:01:51.583  6668  6668 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:01:51.583  6668  6668 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:01:51.583  6668  6668 I UEI.SmartControl: ### init IR Blaster...
08-31 11:01:51.588  6668  6668 D serial_port: Configuring serial port
08-31 11:01:51.592  6668  6668 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:01:51.592  6668  6668 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:01:51.592  6668  6668 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:01:51.592  6668  6668 I UEI.SmartControl: Get version...
08-31 11:01:51.602  1036  1758 W libprocessgroup: failed to open /acct/uid_10112/pid_5632/cgroup.procs: No such file or directory
,08-31 11:01:51.609  6668  6693 D UEI.SmartControl: serial port data available: 21
08-31 11:01:51.635  6668  6668 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:01:51.635  6668  6668 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:01:51.635  6668  6668 I UEI.SmartControl: QS saving settings...
08-31 11:01:51.636  6668  6668 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 11:01:51.656  6668  6693 D UEI.SmartControl: serial port data available: 4
,08-31 11:01:51.696  6668  6696 I UEI.SmartControl: Device manager: loading config....
,08-31 11:01:51.699  6668  6696 D UEI.SmartControl: ----------- loading internal config...
08-31 11:01:51.700  6668  6668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 11:01:51.707  6668  6668 E UEI.SmartControl: Services init done
08-31 11:01:51.707  6668  6668 D UEI.SmartControl: QS Service init finished
08-31 11:01:51.708  6668  6668 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:01:51.709  6668  6668 D UEI.SmartControl: QS Service version code: 201091
,08-31 11:01:51.710  6668  6668 D UEI.SmartControl: Service requested: Control
08-31 11:01:51.714  6668  6696 E UEI.SmartControl: Loading SETTINGS...
08-31 11:01:51.715  6668  6668 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:01:51.718  6668  6668 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:01:51.719  6668  6668 D UEI.SmartControl: Service.onDestroy
08-31 11:01:51.719  6668  6668 D UEI.SmartControl: Lock is in USE false
08-31 11:01:51.719  6668  6668 D UEI.SmartControl: unbind internal service
08-31 11:01:51.723  6668  6668 D serial_port: close(fd = 25)
,08-31 11:01:51.726  6668  6668 I UEI.SmartControl: Serial port is closed.
08-31 11:01:51.727  6668  6668 I UEI.SmartControl: Serial port is closed.
08-31 11:01:51.727  6668  6668 D UEI.SmartControl: Blaster closed
08-31 11:01:51.727  6668  6668 D UEI.SmartControl: Shut down QS...
08-31 11:01:51.727  6668  6668 D UEI.SmartControl: Stopping QS lib
08-31 11:01:51.727  6668  6668 D UEI.SmartControl: QS lib stop result = true
08-31 11:01:51.727  6668  6668 D UEI.SmartControl: Stopped QS lib
08-31 11:01:51.728  6668  6696 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:01:51.731  6668  6668 D UEI.SmartControl: Stopped file observer...
08-31 11:01:51.731  6668  6668 D UEI.SmartControl: QS shutdown complete
08-31 11:01:51.732  6668  6695 I UEI.SmartControl: Notify AllClients services are ready: 11
08-31 11:01:51.732  6668  6695 D UEI.SmartControl: -----service ready thread exits
08-31 11:01:51.732  6668  6668 D UEI.SmartControl: QS Service created
08-31 11:01:51.747  6668  6668 I UEI.SmartControl: Service initServices...
08-31 11:01:51.747  6668  6668 D UEI.SmartControl: QS start get config
,08-31 11:01:52.109  6668  6668 I UEI.SmartControl: Supports setup maps: true
08-31 11:01:52.113  6668  6668 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:01:52.113  6668  6668 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:01:52.113  6668  6668 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:01:52.113  6668  6668 I UEI.SmartControl: ### init IR Blaster...
,08-31 11:01:52.118  6668  6668 D serial_port: Configuring serial port
08-31 11:01:52.119  6668  6668 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:01:52.119  6668  6668 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:01:52.119  6668  6668 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:01:52.119  6668  6668 I UEI.SmartControl: Get version...
08-31 11:01:52.133  6668  6699 D UEI.SmartControl: serial port data available: 21
,08-31 11:01:52.160  6668  6668 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:01:52.160  6668  6668 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:01:52.160  6668  6668 I UEI.SmartControl: QS saving settings...
,08-31 11:01:52.164  6668  6668 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:01:52.180  6668  6699 D UEI.SmartControl: serial port data available: 4
,08-31 11:01:52.207  6668  6702 I UEI.SmartControl: Device manager: loading config....
,08-31 11:01:52.208  6668  6668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 11:01:52.209  6668  6702 D UEI.SmartControl: ----------- loading internal config...
08-31 11:01:52.209  6668  6668 E UEI.SmartControl: Services init done
08-31 11:01:52.209  6668  6668 D UEI.SmartControl: QS Service init finished
08-31 11:01:52.210  6668  6668 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:01:52.210  6668  6668 D UEI.SmartControl: QS Service version code: 201091
08-31 11:01:52.211  6668  6668 D UEI.SmartControl: Service requested: Control
08-31 11:01:52.217  6668  6702 E UEI.SmartControl: Loading SETTINGS...
,08-31 11:01:52.221  6668  6668 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:01:52.226  1036  1051 I ActivityManager: Killing 5208:com.android.calendar/u0a13 (adj 15): empty #17
08-31 11:01:52.232  6668  6702 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 11:01:52.247  6668  6701 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:01:52.247  6668  6701 D UEI.SmartControl: -----service ready thread exits
,08-31 11:01:52.324  1036  1936 W libprocessgroup: failed to open /acct/uid_10013/pid_5208/cgroup.procs: No such file or directory
,08-31 11:01:52.331  6668  6668 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1ecce980 that was originally bound here
08-31 11:01:52.331  6668  6668 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1ecce980 that was originally bound here
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:01:52.331  6668  6668 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:01:52.332  6668  6668 D UEI.SmartControl: Internal service binding...
08-31 11:01:52.452  6492  6596 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 11:01:52.719  6668  6698 D UEI.SmartControl: Internal timer expired: 2
,08-31 11:01:56.110  6668  6679 E UEI.SmartControl: file observer is disposed!,
,08-31 11:01:57.190  6668  6700 D serial_port: close(fd = 24)
,08-31 11:01:57.197  6668  6700 I UEI.SmartControl: Serial port is closed.
08-31 11:01:57.209  6668  6703 D UEI.SmartControl: Internal timer expired: 3
08-31 11:01:57.209  6668  6703 D UEI.SmartControl: unbind internal service
,08-31 11:01:57.220  6668  6668 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:01:57.222  6668  6668 D UEI.SmartControl: Service.onDestroy
08-31 11:01:57.222  6668  6668 D UEI.SmartControl: Lock is in USE false
08-31 11:01:57.222  6668  6668 D UEI.SmartControl: unbind internal service
08-31 11:01:57.223  6668  6668 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1fe2727b
08-31 11:01:57.223  6668  6668 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 11:01:57.224  6668  6668 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 11:01:57.224  6668  6668 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 11:01:57.224  6668  6668 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 11:01:57.224  6668  6668 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 11:01:57.224  6668  6668 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 11:01:57.224  6668  6668 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 11:01:57.224  6668  6668 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 11:01:57.224  6668  6668 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:01:57.225  6668  6668 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:01:57.225  6668  6668 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:01:57.225  6668  6668 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:01:57.225  6668  6668 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:01:57.225  6668  6668 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-31 11:01:57.225  6668  6668 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-31 11:01:57.225  6668  6668 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1fe2727b
08-31 11:01:57.225  6668  6668 I UEI.SmartControl: Serial port is closed.
08-31 11:01:57.225  6668  6668 I UEI.SmartControl: Serial port is closed.
,08-31 11:01:57.225  6668  6668 D UEI.SmartControl: Blaster closed
,08-31 11:01:57.226  6668  6668 D UEI.SmartControl: Shut down QS...
08-31 11:01:57.226  6668  6668 D UEI.SmartControl: Stopping QS lib,
08-31 11:01:57.226  6668  6668 D UEI.SmartControl: QS lib stop result = true
,08-31 11:01:57.226  6668  6668 D UEI.SmartControl: Stopped QS lib
,08-31 11:01:57.226  6668  6668 D UEI.SmartControl: QS shutdown complete
,08-31 11:01:59.866  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 11:01:59.866  6558  6663 I jxcore-log: 
,08-31 11:01:59.868  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 11:01:59.868  6558  6663 I jxcore-log: 
,08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:01:59.874  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:01:59.876  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:01:59.878  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:01:59.878  6558  6663 I jxcore-log: 
08-31 11:01:59.880  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:01:59.880  6558  6663 I jxcore-log: 
08-31 11:01:59.897  1036  1114 I ActivityManager: Waited long enough for: ServiceRecord{13d7eb41 u0 com.google.android.gms/.wearable.service.WearableService}
,08-31 11:02:00.000  1036  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=916018145, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-31 11:02:00.020  4498  6726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-31 11:02:00.032  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 11:02:00.040  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 11:02:00.040  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 11:02:00.040  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 11:02:00.040  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-31 11:02:00.041  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 11:02:00.041  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:02:00.041  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:02:00.042  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 11:02:00.083  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=916018145 [*alarm*], flags=0x0
,08-31 11:02:00.442  6558  6663 I jxcore-log: Unit Test app is loaded
08-31 11:02:00.442  6558  6663 I jxcore-log: 
,08-31 11:02:00.451  6558  6558 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 11:02:00.458  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:02:00.458  6558  6663 I jxcore-log: 
08-31 11:02:00.481  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:02:00.482  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13803414 added. We now have 2 listener(s)
08-31 11:02:00.482  1036  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:02:00.485  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:02:00.485  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:02:00.485  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:02:00.485  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:02:00.485  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ec74bd added. We now have 2 listener(s)
08-31 11:02:00.485  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:02:00.486  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:02:00.489  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:00.495  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:02:00.496  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:00.497  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:02:00.499  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:00.502  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:00.502  6558  6663 D ExecuteNativeTests: Running unit tests
,08-31 11:02:00.651  1036  1379 V AlarmManager: RTC_WAKEUP set : Alarm{3b4bdb92 type 0 when 1472634120426 com.android.vending} when 1472634120426
,08-31 11:02:00.652  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:02:00.652  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 added. We now have 3 listener(s)
08-31 11:02:00.657  1036  1732 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:00.659  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:02:00.659  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:02:00.659  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:02:00.659  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:02:00.659  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 added. We now have 3 listener(s)
08-31 11:02:00.659  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:02:00.661  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:02:00.663  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:00.667  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:00.668  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:00.668  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:02:00.670  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:00.671  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:00.674  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:02:00.674  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:02:00.674  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:02:00.674  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:02:00.676  6558  6663 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 11:02:00.677  6558  6663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:02:00.677  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:02:00.677  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:02:00.677  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:02:00.677  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:02:00.677  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:00.678  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:00.678  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:02:00.678  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:02:00.678  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 removed from the list
08-31 11:02:00.678  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:00.678  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 removed from the list
08-31 11:02:00.678  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:00.678  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:00.680  6558  6663 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-31 11:02:00.681  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:00.681  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:00.681  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:00.681  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:00.681  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:00.681  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:00.681  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:00.681  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:00.681  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.Con,nectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:02:00.687  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:02:00.688  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:02:00.688  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:02:00.688  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:02:00.688  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:02:00.688  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 11:02:00.688  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:02:00.688  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:00.688  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:00.688  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:00.688  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:00.688  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:00.688  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:00.688  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:00.688  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:02:00.688  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:00.692  6558  6663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:02:00.693  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:00.697  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:00.698  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:00.699  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:02:00.700  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:00.702  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:00.702  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:02:00.703  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:02:00.703  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:02:00.703  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:00.703  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:02:00.706  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:02:00.706  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:00.711  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:02:00.715  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:02:00.717  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 11:02:00.717  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:02:00.718  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:02:00.719  6558  6663 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:02:00.720  6558  6663 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:02:00.730  1036  1758 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:02:00.781  2133  2133 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19984
,08-31 11:02:00.854  6086  6086 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 11:02:05.734  6558  6663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:02:05.736  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:02:05.736  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:02:10.743  6558  6663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:02:10.743  6558  6663 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-31 11:02:10.744  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:02:10.744  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:02:10.744  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:02:10.744  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:10.744  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:02:10.921  1036  1895 I art     : Explicit concurrent mark sweep GC freed 24655(1251KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.859ms total 146.513ms
,08-31 11:02:10.926  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:02:10.927  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:02:10.928  6558  6663 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:02:10.928  6558  6663 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:02:15.936  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:15.936  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:15.936  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:02:15.936  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:15.936  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:15.936  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:15.936  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:15.937  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:02:15.946  6558  6663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:02:15.949  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:15.953  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:15.954  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:15.955  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:02:15.959  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:15.961  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:15.961  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:02:15.961  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:02:15.961  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:02:15.961  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:15.961  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:02:15.966  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:02:15.969  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:02:15.971  6558  6663 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-31 11:02:15.971  6558  6663 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:02:20.777  2133  2133 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-31 11:02:20.789  2133  2133 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
08-31 11:02:20.972  6558  6663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:02:20.972  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:02:20.972  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:02:25.981  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:02:25.987  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.987  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:02:25.987  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:25.987  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:25.987  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:25.987  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:25.987  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.993  6558  6663 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 11:02:25.993  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:25.994  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.994  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.994  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:25.994  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:25.994  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:25.994  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:25.994  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.994  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.995  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:02:25.995  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:25.995  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.995  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.995  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:25.995  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:25.995  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:25.995  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:25.995  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.996  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.996  6558  6663 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 11:02:25.997  6558  6663 I org.thaliproject.p2p.btconnec,torlib.ConnectionManager: dispose
08-31 11:02:25.997  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.997  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.997  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:25.997  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:25.997  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:25.997  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:25.997  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.997  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.998  6558  6663 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
08-31 11:02:25.998  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:25.998  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.998  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:02:25.998  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:25.998  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:25.998  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list,
08-31 11:02:25.998  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:25.998  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:25.998  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:25.999  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:02:26.003  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:02:26.003  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:02:26.003  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-31 11:02:26.003  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:02:26.013  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:02:26.013  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:02:26.013  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:02:26.013  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:02:26.013  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:26.013  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.014  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.014  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:26.014  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:26.014  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:26.014  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:26.014  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.014  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.015  6558  6663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:02:26.015  6558  6663 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:02:26.015  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:02:26.020  6558  6663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:02:26.020  6558  6663 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer,: [<no peer name> 18:810:810:810:810:810]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:02:26.020  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:02:26.021  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-31 11:02:26.021  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:02:26.025  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:02:26.026  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:02:26.026  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:02:26.028  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:02:26.028  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:02:26.028  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:02:26.028  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:02:26.028  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:02:26.029  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:02:26.029  6558  6663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:02:26.030  6558  6663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:02:26.030  6558  6663 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:02:26.030  6558  6663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:02:26.030  6558  6663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:02:26.030  6558  6663 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:02:26.030  6558  6663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:02:26.030  6558  6663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:02:26.030  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:02:26.035  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-31 11:02:26.042  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:02:26.042  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 11:02:26.043  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:02:26.043  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:02:26.043  6558  6663 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:02:26.044  6558  6663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:02:26.044  6558  6663 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:02:26.047  6558  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 801)
,08-31 11:02:26.053  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:26.053  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.053  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.054  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 11:02:26.055  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:26.055  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:26.055  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:26.055  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:26.055  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.055  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.056  6558  6663 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:02:26.057  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:26.057  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.057  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.057  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:26.057  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:26.057  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:26.057  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:26.057  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.057  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.058  6558  6663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:02:26.058  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:26.059  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.059  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.059  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:26.059  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:26.059  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:26.059  6558  6663 D io.jxcore.node.ConnectivityMonitor: s,top
08-31 11:02:26.059  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.059  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.059  6558  6663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 11:02:26.060  6558  6663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:02:26.060  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:02:26.060  6558  6663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:02:26.060  6558  6663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:02:26.060  6558  6663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:02:26.060  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:02:26.060  6558  6663 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:02:26.060  6558  6663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:02:26.060  6558  6663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:02:26.061  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:02:26.061  6558  6663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-31 11:02:26.066  6558  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 801
08-31 11:02:26.066  6558  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 801)
08-31 11:02:26.066  6558  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 801)
,08-31 11:02:26.074  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:26.074  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.074  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.074  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:26.074  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:26.074  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:26.074  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:26.074  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:26.074  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:26.079  6558  6663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:02:26.085  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:26.089  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:26.092  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:26.092  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:02:26.096  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:26.097  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:26.098  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:02:26.098  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:02:26.098  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:02:26.098  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:26.098  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:02:26.103  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:02:26.103  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:02:26.104  6558  6663 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-31 11:02:26.111  6558  6663 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:02:26.182  6558  6755 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-31 11:02:26.185  6558  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 801)
,08-31 11:02:31.111  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:02:31.111  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:31.111  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:02:31.112  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:31.112  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:31.112  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:31.112  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:02:31.112  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-31 11:02:36.127  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:36.127  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:36.127  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:36.127  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.128  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.128  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:36.128  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:36.128  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.128  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.128  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:36.128  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:36.128  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:36.128  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:36.128  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.128  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:02:36.133  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:02:36.135  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:36.137  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:02:36.139  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:02:36.139  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:02:36.140  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:02:36.140  6558  6779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:02:36.140  6558  6558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:02:36.142  3866  3890 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-31 11:02:36.142  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:02:36.143  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:02:36.143  6558  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-31 11:02:36.145  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:36.146  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:02:36.146  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:02:36.146  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:02:36.147  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.147  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:02:36.148  6558  6779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:02:36.148  6558  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-31 11:02:36.148  6558  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-31 11:02:36.149  6558  6558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:02:36.149  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:36.149  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:36.150  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:02:36.150  6558  6663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:02:36.150  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:02:36.150  6558  6558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:02:36.151  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:02:36.154  6558  6663 D BluetoothLeScanner: could not find callback wrapper
08-31 11:02:36.154  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:02:36.154  6558  6663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:02:36.154  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.154  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.155  6558  6663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:02:36.156  6558  6558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:02:36.156  6558  6558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:02:36.156  6558  6558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:02:36.156  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:36.156  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:36.156  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.156  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.156  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:36.156  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:36.157  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:36.157  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:36.157  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.157  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.158  6558  6663 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 11:02:36.158  6558  6663 D io.jxcore.node.ConnectionModel: remo,veOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:02:36.158  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:02:36.159  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:02:36.159  6558  6663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:02:36.159  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:36.159  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.159  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.159  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:36.159  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:36.159  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:36.159  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:36.159  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.159  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.160  1036  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:02:36.167  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:36.169  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:36.170  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:36.170  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.170  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.170  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:36.170  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:36.170  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:36.170  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:36.170  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.170  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.171  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:02:36.171  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.171  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.171  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275b19f3 not in the list
08-31 11:02:36.171  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:36.171  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a446b0 not in the list
08-31 11:02:36.171  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:36.171  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:36.171  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:36.172  6558  6663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:02:36.172  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:02:36.173  6558  6663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:02:36.173  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:02:36.173  6558  6663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:02:36.173  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:02:36.175  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:02:36.175  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 11:02:36.175  6558  6663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:02:36.175  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:02:36.175  6558  6663 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:02:36.176  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:02:36.176  6558  6663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:02:36.176  6558  6663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-31 11:02:36.176  6558  6663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-31 11:02:36.177  6558  6663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-31 11:02:36.177  6558  6663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:02:36.177  6558  6663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:02:36.179  6558  6663 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:02:36.179  6558  6663 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 11:02:36.180  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:02:36.180  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1df8eb86 added. We now have 3 listener(s)
,08-31 11:02:36.180  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:02:36.183  6558  6663 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 11:02:36.184  1036  1574 D WifiServiceImplEx: setWifiEnabled: true pid=6558, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:02:36.185  1036  1574 D WifiService: setWifiEnabled: true pid=6558, uid=10118
08-31 11:02:36.185  1036  1574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:02:36.659  6558  6558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:02:41.196  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:02:41.196  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a634c47 added. We now have 4 listener(s)
08-31 11:02:41.196  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:02:41.208  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:41.208  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a634c47 removed from the list
08-31 11:02:41.208  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:41.208  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:41.208  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:41.209  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:02:41.209  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@336f4c74 added. We now have 4 listener(s)
08-31 11:02:41.209  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:02:41.211  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:02:41.211  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@336f4c74 removed from the list
08-31 11:02:41.211  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:02:41.211  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:02:41.211  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:02:41.212  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:02:41.212  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2567159d added. We now have 4 listener(s)
08-31 11:02:41.212  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:02:41.215  1036  1732 D WifiServiceImplEx: setWifiEnabled: false pid=6558, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:02:41.215  1036  1732 D WifiService: setWifiEnabled: false pid=6558, uid=10118
08-31 11:02:41.215  1036  1732 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:02:41.248  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:02:41.249  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 11:02:41.251  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-31 11:02:41.253  1036  1431 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:41.254  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:41.254  1036  1431 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:41.254  1036  1431 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:41.255  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:41.255  1036  1431 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:02:41.255  1036  1431 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:02:41.255  1036  1431 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:02:41.256  1036  1431 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:02:41.257  1036  1431 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:02:41.258  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:41.259  1036  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@73f77cb mBinding = false
08-31 11:02:41.272  1036  1431 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:02:41.272  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:02:41.272  2745  2745 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-31 11:02:41.276  1036  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.276  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.277  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:02:41.277  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:02:41.278  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:02:41.278  1036  2870 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.282   316   916 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:02:41.303  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:02:41.303  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:02:41.303  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:02:41.331  1036  1118 D BluetoothManagerService: Message: 2
,08-31 11:02:41.334  1036  1118 D BluetoothManagerService: Sending off request.
08-31 11:02:41.342  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:02:41.343  3866  3887 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:41.358  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:41.364  3866  3948 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 11:02:41.365  3866  3948 D BluetoothAdapterProperties: Setting state to 13
08-31 11:02:41.365  3866  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 11:02:41.370  3866  3948 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:02:41.370  3866  3948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 11:02:41.375  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 11:02:41.375  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-31 11:02:41.380  3866  3951 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:02:41.381  3866  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 11:02:41.382  3866  4221 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 11:02:41.391  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:02:41.391  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 11:02:41.391  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 11:02:41.402  3866  4226 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:02:41.402  3866  4310 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:02:41.403  3866  3948 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 11:02:41.406  3866  4312 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:02:41.407  3866  4314 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:02:41.408  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:41.409  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:02:41.411  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:41.411  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:41.412  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.412  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:41.412  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-31 11:02:41.413  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:41.415  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 11:02:41.415  3866  4063 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-31 11:02:41.419  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:41.419  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 11:02:41.420  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 11:02:41.420  3866  4063 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:02:41.421  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:41.424  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 11:02:41.427  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.427  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.427  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-31 11:02:41.437  1036  1484 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 11:02:41.437  1036  1484 D DSQN    : disableDataServiceNotify
08-31 11:02:41.437  1036  1484 D DSQN    : stop dsqn bin
08-31 11:02:41.438  1036  1922 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-31 11:02:41.438  3866  3866 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:41.438  3866  3866 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:02:41.438  3866  3866 V BluetoothMapService: Handler(): got msg=4
,08-31 11:02:41.438  3866  3866 D BluetoothMapService: MAP Service closeService in
08-31 11:02:41.438  3866  3866 D BluetoothMapMasInstance: MAP Service shutdown
08-31 11:02:41.439  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:02:41.439  3866  3866 V BluetoothMapService: MAP Service closeService out
08-31 11:02:41.439  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.439  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.439  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 11:02:41.439  3866  3866 V BtOppService: Receiver DISABLED_ACTION 
08-31 11:02:41.439  3866  3866 I BtOppRfcommListener: stopping Accept Thread
08-31 11:02:41.440  3866  3866 V BtOppRfcommListener: close mBtServerSocket
08-31 11:02:41.440  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.440  3866  3866 V BtOppRfcommListener: waiting for thread to terminate
08-31 11:02:41.440  3866  4310 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:02:41.440  3866  3866 V BtOppRfcommListener: done waiting for thread to terminate
08-31 11:02:41.441  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-31 11:02:41.442  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:41.442  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:41.443  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:41.444  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.444  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:41.444   316  6807 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:02:41.445  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 11:02:41.446  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:02:41.447  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.447  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:41.447  6558  6558 V io.,jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:41.447  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:41.447  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:41.447  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:41.447  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:41.447  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:41.447  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:41.447  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.448  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:41.449  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:41.451  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:02:41.454  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:41.454  1036  1484 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 11:02:41.454  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:41.454  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:41.455  1036  1484 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:41.455  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 11:02:41.455  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:02:41.455  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.455  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.455  1036  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:02:41.456  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:02:41.456  1036  1484 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 11:02:41.456  1036  1484 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 11:02:41.456  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:02:41.457  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:41.460  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:02:41.483  1036  1114 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6809 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:02:41.484  3866  3866 V BtOppService: onDestroy
08-31 11:02:41.484  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:41.484  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:02:41.484  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:41.484  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.484  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.484  1036  1484 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:41.484  1036  1484 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 11:02:41.484  1036  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d1bd2d2
,08-31 11:02:41.484  1036  1484 D NetworkManagementService: Removing idletimer
08-31 11:02:41.484  1036  1390 D LGWifiP2pService: P2pDisablingState
08-31 11:02:41.485  1036  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.485  1036  1390 D LGWifiP2pService: p2p socket connection lost
08-31 11:02:41.485  1036  1390 D LGWifiP2pService: P2pDisabledState
08-31 11:02:41.485  1036  1484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.485  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:41.485  1036  1484 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 11:02:41.485  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:02:41.486  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-31 11:02:41.487  1036  1431 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.487  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.487  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.487  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.487  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:02:41.487  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:02:41.487  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:02:41.487  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:02:41.487  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:02:41.487  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-31 11:02:41.487  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.488  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:02:41.488  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.488  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:02:41.488  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:02:41.488  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:02:41.488  1036  1431 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.488  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:02:41.488  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:02:41.488  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:02:41.489  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.489  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.489  1036  1556 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.490  ,1036  1431 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:02:41.490  1036  1431 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.490  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.491  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:41.491  1036  1431 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:41.491  1036  1431 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:02:41.491  1036  1431 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 11:02:41.491  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:02:41.491  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.491  1036  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:41.492  2745  2745 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:02:41.492  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:02:41.492  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:02:41.493  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:02:41.493   316   916 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:02:41.494  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:02:41.494  1942  1942 D WfdsService: WifiP2pState is changed : false
08-31 11:02:41.495  1942  2273 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 11:02:41.495  1942  2273 D WfdsService: Set the WFDS Monitor: false
08-31 11:02:41.495  1942  2273 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:02:41.496  1942  2273 D WfdsService: STATE : WfdsDisabledState - enter
08-31 11:02:41.496  1942  2274 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 11:02:41.496  1942  2865 D CtrlSupplicant: Received on exit socket, terminate
08-31 11:02:41.496  1942  2865 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 11:02:41.496  1942  2865 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 11:02:41.496  1942  2865 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 11:02:41.496  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:41.497  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:41.497  1942  2273 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 11:02:41.497  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:41.529  1036  1758 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6827 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:02:41.531  3866  3866 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 11:02:41.535  1036  1431 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 11:02:41.536  1036  1431 D WifiNative-p2p0: TERMINATE: returned true
08-31 11:02:41.536  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:02:41.536  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:02:41.536  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:02:41.537  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-31 11:02:41.538  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.538  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.538  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:02:41.539  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 11:02:41.542  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 11:02:41.542  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-31 11:02:41.542  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 11:02:41.543  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:41.543  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:41.544  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.545  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:41.550  6809  6809 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:02:41.550  6809  6809 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 11:02:41.550  6809  6809 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:02:41.551  6809  6809 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 11:02:41.552  6809  6809 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:02:41.552  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:41.553  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:41.553  6809  6809 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:02:41.553  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.553  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:41.556  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:41.556  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:41.557  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:41.557  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:41.561  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:02:41.562  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:41.563  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:02:41.579  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:02:41.579  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:41.580  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:41.583  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:02:41.583  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:41.584  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:41.600  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:02:41.601  2745  2745 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 11:02:41.602  2745  2745 I wpa_supplicant: monitor socket send errors count : 1
08-31 11:02:41.602  2745  2745 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
08-31 11:02:41.602  1036  2864 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 11:02:41.603  1036  2864 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:02:41.605  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:02:41.608  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:02:41.609  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:02:41.610  1036  1891 I ActivityManager: Killing 5918:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-31 11:02:41.633  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 11:02:41.639  2745  2745 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:02:41.639  1036  2864 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 11:02:41.639  1036  2864 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:02:41.639  1036  2864 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 11:02:41.639  1036  2864 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 11:02:41.640  2745  2745 W wpa_supplicant: USIM:  scard_deinit function
08-31 11:02:41.640  1036  1431 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=157257
08-31 11:02:41.640  1036  1431 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=157257
08-31 11:02:41.640  1036  2864 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:02:41.640  1036  2864 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:02:41.641  1036  1431 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=157258  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:02:41.641  1036  1118 D Tethering: InitialState.processMessage what=4
08-31 11:02:41.642  1036  1431 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=157259  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:02:41.655  1036  2870 D DhcpStateMachine: StoppedState
08-31 11:02:41.655  1036  2870 D DhcpStateMachine: StoppedState{ when=-162ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:02:41.663  1036  2032 W libprocessgroup: failed to open /acct/uid_10014/pid_5918/cgroup.procs: No such file or directory
08-31 11:02:41.672  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:02:41.674  1036  1431 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 11:02:41.675  1036  1431 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 11:02:41.676  3866  3866 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:02:41.676  3866  3866 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:41.677  3866  3866 V BluetoothPbapReceiver: ***********state = 13
08-31 11:02:41.678  1036  1431 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:41.679  1036  1431 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:41.679  3866  3866 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 11:02:41.681  3866  3866 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:41.681  3866  3866 V BluetoothPbapService: state: 13
08-31 11:02:41.682  3866  3866 V BluetoothPbapService: Pbap Service closeService in
08-31 11:02:41.683  3866  3866 V BluetoothPbapService: successfully stopped pbap service
08-31 11:02:41.684  3866  3866 V BluetoothPbapService: Pbap Service closeService out
08-31 11:02:41.684  3866  3866 V BluetoothPbapService: Pbap Service onDestroy
08-31 11:02:41.684  3866  3866 V BluetoothPbapService: Pbap Service closeService in
08-31 11:02:41.684  3866  3866 V BluetoothPbapService: Pbap Service closeService out
08-31 11:02:41.684  3866  3866 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-31 11:02:41.686  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:02:41.694  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:41.722  2745  2745 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 11:02:41.723  1036  2864 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 11:02:41.723  1036  2864 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 11:02:41.723  1036  2864 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 11:02:41.725  1036  1431 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 21 0
,08-31 11:02:41.738  6809  6809 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:02:41.738  6809  6809 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:02:41.748  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:02:41.759  1036  1118 D BluetoothManagerService: Message: 20
08-31 11:02:41.759  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cc88af2:true
08-31 11:02:41.759  1036  1895 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6848 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 11:02:41.771  1036  1118 D BluetoothManagerService: Message: 30
,08-31 11:02:41.775  1036  1118 D BluetoothManagerService: Message: 30
08-31 11:02:41.778  6809  6809 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 11:02:41.780  6809  6809 D BluetoothMap: Create BluetoothMap proxy object
08-31 11:02:41.780  1036  1118 D BluetoothManagerService: Message: 30
08-31 11:02:41.785  1036  1118 D BluetoothManagerService: Message: 30
,08-31 11:02:41.787  6809  6809 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 11:02:41.788  6809  6809 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 11:02:41.803  6809  6809 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-31 11:02:41.807  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-31 11:02:41.826  6809  6809 D DockEventReceiver: finishStartingService: stopping service
08-31 11:02:41.827  1036  1431 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 11:02:41.827  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:02:41.827  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:02:41.827  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-31 11:02:41.831  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-31 11:02:41.831  1942  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 11:02:41.831  1942  2273 D WfdsService: Set the WFDS Monitor: false
08-31 11:02:41.831  1942  2273 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:02:41.832  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:41.832  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:02:41.836  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 11:02:41.836  1036  1447 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 11:02:41.836  1036  1447 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 11:02:41.837  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:41.838  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:41.839  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:41.839  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:41.856  6809  6809 D BluetoothInputDevice: Proxy object connected
,08-31 11:02:41.861  6809  6809 D HidProfile: Bluetooth service connected
08-31 11:02:41.864  6809  6809 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:02:41.865  6809  6809 D PanProfile: Bluetooth service connected
08-31 11:02:41.865  6809  6809 D BluetoothMap: Proxy object connected
08-31 11:02:41.866  6809  6809 D MapProfile: Bluetooth service connected
08-31 11:02:41.866  6809  6809 D BluetoothMap: getConnectedDevices()
08-31 11:02:41.866  6809  6809 D BluetoothMap: Bluetooth is Not enabled
08-31 11:02:41.867  6809  6809 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 11:02:41.923  1036  1995 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6872 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 11:02:41.926  1036  1995 I ActivityManager: Killing 6282:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-31 11:02:41.983  1036  1895 W libprocessgroup: failed to open /acct/uid_10004/pid_6282/cgroup.procs: No such file or directory
,08-31 11:02:41.997  6848  6848 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 11:02:41.998  6848  6848 W LG Account v2.2: No ProfileInfo entries
08-31 11:02:41.998  6848  6848 I LG Account v2.2: isEnabled: false
08-31 11:02:41.999  6848  6848 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 11:02:41.999  6848  6848 I Feature : [Lifetracker]Country: EU
08-31 11:02:41.999  6848  6848 I Feature : [Lifetracker]Operator: OPEN
08-31 11:02:41.999  6848  6848 I Feature : [Lifetracker]Ranking support: false
08-31 11:02:42.000  6848  6848 I Feature : [Lifetracker]Comfort support: false
08-31 11:02:42.000  6848  6848 I Feature : [Lifetracker]Accessory: true
08-31 11:02:42.000  6848  6848 I Feature : [Lifetracker]Health device: true
08-31 11:02:42.000  6848  6848 I Feature : [Lifetracker]Extra Pedometer: false
08-31 11:02:42.000  6848  6848 I Feature : [Lifetracker]Blood glucose device: false
08-31 11:02:42.001  6848  6848 I Feature : [Lifetracker]Device Number: 3
,08-31 11:02:42.015  6872  6872 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:02:42.018  6809  6809 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 11:02:42.025  6809  6809 D BluetoothPermissionRequest: onReceive
08-31 11:02:42.027  6809  6809 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 11:02:42.040  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 11:02:42.044  1036  1052 I ActivityManager: Killing 6405:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 11:02:42.074  3866  3866 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 11:02:42.074  3866  3866 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 11:02:42.075  1036  1574 W libprocessgroup: failed to open /acct/uid_10008/pid_6405/cgroup.procs: No such file or directory
08-31 11:02:42.076  3866  3866 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-31 11:02:42.079  6872  6872 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 11:02:42.082  3866  3866 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:42.082  3866  3866 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:02:42.084  3866  3866 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:02:42.084  3866  3866 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:42.084  3866  3866 V BluetoothFtpService: Ftp Service closeService
08-31 11:02:42.084  3866  3866 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 11:02:42.092  3866  3866 V BluetoothFtpService: successfully stopped ftp service
08-31 11:02:42.093  3866  3866 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:02:42.093  3866  3866 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:02:42.093  3866  3866 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:02:42.093  3866  3866 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:42.093  3866  3866 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 11:02:42.093  3866  3866 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-31 11:02:42.095  3866  3866 V BluetoothFtpService: Ftp Service onDestroy
08-31 11:02:42.095  3866  3866 V BluetoothFtpService: Ftp Service closeService
08-31 11:02:42.139  6872  6872 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 11:02:42.140  6872  6872 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 11:02:42.140  6872  6872 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-31 11:02:42.142  6872  6872 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 11:02:42.143  6872  6872 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 11:02:42.147  6872  6872 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 11:02:42.162  1036  1758 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6894 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:02:42.163  3866  3866 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:42.163  3866  3866 V BluetoothSapService: state: 13
08-31 11:02:42.163  3866  3866 V BluetoothSapService: Stopping SAP server process
08-31 11:02:42.165  3866  3866 V BluetoothSapService: Sap Service closeSapService in
08-31 11:02:42.165  3866  3866 V BluetoothSapService: Close listen Socket : 
08-31 11:02:42.165  3866  3866 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:02:42.166  3866  3866 V BluetoothSapService: Close sapd  Socket : 
08-31 11:02:42.168  3866  3866 V BluetoothSapService: Sap Service closeSapService out
08-31 11:02:42.169  3866  3866 V BluetoothSapService: Sap Service onDestroy
08-31 11:02:42.169  3866  3866 V BluetoothSapService: Sap Service closeSapService in
08-31 11:02:42.169  3866  3866 V BluetoothSapService: Close listen Socket : 
08-31 11:02:42.169  3866  3866 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:02:42.169  3866  3866 V BluetoothSapService: Close sapd  Socket : 
08-31 11:02:42.170  3866  3866 V BluetoothSapService: Sap Service closeSapService out
08-31 11:02:42.170  6872  6872 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 11:02:42.178  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:02:42.182  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:42.196  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:02:42.202  6872  6872 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 11:02:42.206  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:42.210  6872  6872 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 11:02:42.211  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:02:42.211  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-31 11:02:42.211  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:02:42.215  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:42.220  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:42.220  6894  6894 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:02:42.227  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:42.227  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:42.229  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:02:42.231  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:42.234  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:02:42.234  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:02:42.234  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:02:42.238  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:42.244  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:42.248  1036  2032 I ActivityManager: Killing 6016:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-31 11:02:42.278  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:42.278  1036  1959 W libprocessgroup: failed to open /acct/uid_10011/pid_6016/cgroup.procs: No such file or directory
08-31 11:02:42.278  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:42.282  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:02:42.346  1036  2033 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6914 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 11:02:42.422  3866  4063 W bt-btif : ag scb idx 1 not allocated
08-31 11:02:42.422  3866  4063 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-31 11:02:42.422  3866  3951 D bt_hci_bdroid: cleanup
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:02:42.422  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:02:42.423  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:02:42.423  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:02:42.423  3866  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:02:42.423  3866  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:02:42.423  3866  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:02:42.423  3866  4063 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:02:42.423  3866  4065 I bt_lpm  : LPM is already off!!!
08-31 11:02:42.423  3866  4206 I bt_userial_mct: exiting userial_read_thread
08-31 11:02:42.423  3866  4206 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 11:02:42.425  3866  3951 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 11:02:42.425  3866  4065 I bt_vendor: hw_epilog_process
08-31 11:02:42.426  3866  3951 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 11:02:42.426  3866  3951 D bt_userial_mct: userial_close
08-31 11:02:42.426  3866  3951 E bt_userial_mct: pthread_join() FAILED result:3
08-31 11:02:42.426  3866  3951 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 11:02:42.437  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:02:42.440  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:02:42.450  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:42.469  6914  6934 W FormManager: Network not available. Please check & try again.
,08-31 11:02:42.471  3866  3951 D bt_hci_bdroid: set_power 0
08-31 11:02:42.471  3866  3951 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:02:42.471  3866  3951 I bt_vendor: bluetooth satus is on
08-31 11:02:42.471  3866  3951 I bt_vendor: bt-vendor : resetting BT status
08-31 11:02:42.471  3866  3951 I bt_vendor: Starting hciattach daemon
08-31 11:02:42.471  3866  3951 I bt_vendor: try to set false
08-31 11:02:42.472  3866  3951 I bt_vendor: Starting hciattach daemon
08-31 11:02:42.472  3866  3951 I bt_vendor: try to set false
08-31 11:02:42.472  3866  3951 I bt_vendor: cleanup
08-31 11:02:42.473  3866  4063 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 11:02:42.473  3866  3951 I GKI_LINUX: GKI_exit_task 0 done
08-31 11:02:42.473  3866  3951 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 11:02:42.475  3866  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:02:42.477  3866  3866 D HeadsetService: Received stop request...Stopping profile...
08-31 11:02:42.478  3866  3866 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:02:42.478  3866  3866 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:02:42.478  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f58b0bd
08-31 11:02:42.478  3866  3974 D HeadsetStateMachine: Exit Disconnected: -1
08-31 11:02:42.481  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-31 11:02:42.481  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-31 11:02:42.481  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-31 11:02:42.481  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-31 11:02:42.481  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 11:02:42.483  3866  3866 D A2dpService: Received stop request...Stopping profile...
08-31 11:02:42.485  3866  4048 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:02:42.490  3866  3866 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 11:02:42.491  3866  3948 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:02:42.492  3866  3866 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 11:02:42.492  3866  3866 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:02:42.492  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f58b0bd
08-31 11:02:42.492  6914  6935 V FormManager: Network unavailable.
08-31 11:02:42.493  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-31 11:02:42.493  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:02:42.493  3866  3866 D HidService: Received stop request...Stopping profile...
08-31 11:02:42.494  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f58b0bd
08-31 11:02:42.494  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:02:42.495  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:02:42.495  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:02:42.495  3866  3866 D HeadsetStateMachine: Unbinding service...
08-31 11:02:42.496  6809  6809 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:02:42.496  3866  3866 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:02:42.496  3866  3866 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:02:42.496  3866  3866 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:02:42.496  3866  3866 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:02:42.496  3866  3866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:02:42.496  3866  3866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:02:42.496  3866  3866 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:02:42.496  3866  3866 D HealthService: Received stop request...Stopping profile...
08-31 11:02:42.497  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f58b0bd
,08-31 11:02:42.499  3866  3866 D PanService: Received stop request...Stopping profile...
08-31 11:02:42.499  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:02:42.500  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f58b0bd
,08-31 11:02:42.501  3866  3866 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:02:42.501  3866  3866 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:02:42.501  6914  6935 V FormManager: Network unavailable.
08-31 11:02:42.502  3866  3866 D BtGatt.GattService: stop()
08-31 11:02:42.502  3866  3866 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:02:42.502  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f58b0bd
08-31 11:02:42.504  3866  3866 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:02:42.504  3866  3866 D BluetoothMapService: stop()
08-31 11:02:42.504  3866  3866 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 11:02:42.504  3866  3866 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 11:02:42.505  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f58b0bd
08-31 11:02:42.506  3866  3866 I BluetoothA2dpServiceJni: cleanupNative
08-31 11:02:42.506  3866  4049 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:02:42.506  3866  3866 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:02:42.506  3866  3866 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:02:42.507  3866  3866 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:02:42.507  3866  3866 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:02:42.507  3866  3866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:02:42.507  3866  3866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:02:42.507  3866  3866 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:02:42.507  3866  3866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:02:42.507  3866  3866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:02:42.508  3866  3866 V BluetoothMapService: Handler(): got msg=4
08-31 11:02:42.508  3866  3866 D BluetoothMapService: MAP Service closeService in
08-31 11:02:42.508  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:02:42.508  3866  3866 V BluetoothMapService: MAP Service closeService out
08-31 11:02:42.509  3866  3866 D BluetoothMapService: cleanup()
08-31 11:02:42.509  3866  3866 D BluetoothMapService: MAP Service closeService in
08-31 11:02:42.509  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:02:42.509  3866  3866 V BluetoothMapService: MAP Service closeService out
08-31 11:02:42.509  3866  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:02:42.509  3866  3948 D BluetoothAdapterProperties: Setting state to 10
08-31 11:02:42.509  3866  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:02:42.510  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:02:42.511  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 11:02:42.511  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
,08-31 11:02:42.512  3866  3948 I BluetoothAdapterState: Entering OffState
08-31 11:02:42.512  6809  6825 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:02:42.513  1852  2716 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:02:42.514  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:02:42.514  6809  6826 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:02:42.515  6809  6825 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:02:42.515  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:02:42.516  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:02:42.516  6809  6826 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:02:42.517  1852  2448 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:02:42.518  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 11:02:42.518  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-31 11:02:42.523  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 11:02:42.523  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 11:02:42.523  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@73f77cb mBinding = false
,08-31 11:02:42.524  1036  1118 D BluetoothManagerService: Sending unbind request.
08-31 11:02:42.527  6809  6809 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:02:42.527  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:02:42.527  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:02:42.527  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:02:42.528  6809  6809 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:02:42.528  6809  6809 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:02:42.530  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 11:02:42.533  1036  1732 I ActivityManager: Killing 6038:com.android.contacts/u0a19 (adj 15): empty #17
08-31 11:02:42.538  3866  3951 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 11:02:42.538  3866  3866 I GKI_LINUX: GKI_exit_task 1 done
,08-31 11:02:42.539  3866  3866 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 11:02:42.539  3866  3866 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:02:42.539  3866  3866 I art     : --- WEIRD: removing null entry 246
08-31 11:02:42.539  3866  3866 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 11:02:42.539  3866  3866 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 11:02:42.591  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:42.591  1942  2128 D LGBluetoothAPIService: Message: 2
08-31 11:02:42.592  1942  2128 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3fd85764 mBinding = false
08-31 11:02:42.592  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:02:42.592  1942  2128 D LGBluetoothAPIService: Sending unbind request.
,08-31 11:02:42.595  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-31 11:02:42.596  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:42.598  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:42.599  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:42.600  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:02:42.603  1602  1602 D BluetoothAdapter: 809742892: getState() :  mService = null. Returning STATE_OFF
08-31 11:02:42.603  1602  1602 D BluetoothAdapter: 809742892: getState() :  mService = null. Returning STATE_OFF
08-31 11:02:42.603  6809  6809 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:02:42.604  6809  6809 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 11:02:42.604  6809  6809 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 11:02:42.606  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:02:42.610  1036  1574 W libprocessgroup: failed to open /acct/uid_10019/pid_6038/cgroup.procs: No such file or directory
08-31 11:02:42.611  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:02:42.628  3866  3866 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-31 11:02:42.634  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:42.635  3866  3866 I art     : System.exit called, status: 0
08-31 11:02:42.635  3866  3866 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 11:02:42.643  6809  6809 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:02:42.648  4289  6946 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:02:42.657  4289  6947 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:02:42.657  4289  6947 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:02:42.657  6827  6827 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-31 11:02:42.657  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-31 11:02:42.657  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:02:42.666  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:02:42.669   321  1396 V AudioFlinger: 3866 died, releasing its sessions
08-31 11:02:42.669   321  1396 V AudioFlinger:  pid 1852 @ 0
08-31 11:02:42.669   321  1396 V AudioFlinger:  pid 3498 @ 1
08-31 11:02:42.669   321  1396 V AudioFlinger:  pid 3498 @ 2
,08-31 11:02:42.675  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:42.675  6809  6809 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 11:02:42.681  1036  1996 I ActivityManager: Process com.android.bluetooth (pid 3866) has died
08-31 11:02:42.682  1036  1996 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-31 11:02:42.692  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:02:42.695  6914  6949 W FormManager: Network not available. Please check & try again.
,08-31 11:02:42.703  6914  6950 V FormManager: Network unavailable.
08-31 11:02:42.715  6914  6950 V FormManager: Network unavailable.
,08-31 11:02:42.717  6809  6809 D BluetoothPermissionRequest: onReceive
08-31 11:02:42.726  6809  6809 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:02:42.726  6809  6809 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 11:02:42.734  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 11:02:42.825  1036  1959 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6951 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 11:02:42.841  6872  6872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-31 11:02:42.843  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:02:42.843  6872  6872 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-31 11:02:42.882  6872  6872 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:02:42.882  6872  6872 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:02:42.893  6872  6872 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-31 11:02:42.895  6872  6872 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 11:02:42.895  6872  6872 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 11:02:42.895  6872  6872 V SoundPool: doLoad: loading sample sampleID=1
08-31 11:02:42.896  6872  6872 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:02:42.900  6872  6970 V SoundPool: Start decode
08-31 11:02:42.900  6872  6970 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 11:02:42.900  6872  6872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 11:02:42.901  6668  6668 D UEI.SmartControl: QS Service created
08-31 11:02:42.902   321  1397 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 11:02:42.902   321  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 11:02:42.902   321  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 11:02:42.902   321  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 11:02:42.902  6872  6872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:02:42.902   321  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 11:02:42.902   321  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 11:02:42.903   321  1397 V MediaPlayerService: player type = 3
08-31 11:02:42.903   321  1397 V AwesomePlayer: AwesomePlayer create()
08-31 11:02:42.903  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 11:02:42.904   321  1397 V AwesomePlayer: reset_l() 
08-31 11:02:42.904   321  1397 V AwesomePlayer: cancelPlayerEvents
08-31 11:02:42.904   321  1397 V AwesomePlayer: setAudioSink() 
08-31 11:02:42.904   321  1397 V AwesomePlayer: reset_l() 
08-31 11:02:42.904   321  1397 V AudioCache: notify(0xb5474680, 8, 0, 0)
08-31 11:02:42.904   321  1397 V AudioCache: ignored
08-31 11:02:42.904   321  1397 V AwesomePlayer: cancelPlayerEvents
08-31 11:02:42.904   321  1397 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 11:02:42.905   321  1397 V AwesomePlayer: setDataSource_l dataSource
08-31 11:02:42.905   321  1397 V LGParserOSAL: SniffLGParser start
08-31 11:02:42.905   321  1397 V LGParserOSAL: MainType:5, SubType=0
08-31 11:02:42.905   321  1397 V LGParserOSAL: #### check Mime : application/ogg
08-31 11:02:42.905   321  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 11:02:42.905  6951  6951 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 11:02:42.905   321  1397 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 11:02:42.906  6951  6951 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:02:42.906  6951  6951 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 11:02:42.907  6951  6951 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 11:02:42.916  6872  6872 V LGMDMManager: Create singleton instance
,08-31 11:02:42.927  6951  6951 D BluetoothAdapterApp: Loading JNI Library
08-31 11:02:42.936  6668  6668 I UEI.SmartControl: Service initServices...
08-31 11:02:42.936  6668  6668 D UEI.SmartControl: QS start get config
,08-31 11:02:42.964   321  1397 V LGParserOSAL: supported mime: application/ogg
08-31 11:02:42.964   321  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 11:02:42.964   321  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 11:02:42.964   321  1397 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 11:02:42.964   321  1397 V AwesomePlayer: AudioTrack Setting
08-31 11:02:42.964   321  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 11:02:42.964   321  1397 V AwesomePlayer: setAudioSource() 
08-31 11:02:42.964   321  1397 V MediaPlayerService: prepare
08-31 11:02:42.964   321  1397 V AwesomePlayer: prepareAsync_l() 
08-31 11:02:42.964   321  1397 V MediaPlayerService: wait for prepare
08-31 11:02:42.965   321  6971 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 11:02:42.965   321  6971 V AwesomePlayer: initAudioDecoder() 
08-31 11:02:42.965   321  6971 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:02:42.965   321  6971 V AudioSystem: isOffloadSupported()
08-31 11:02:42.965   321  6971 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:02:42.965   321  6971 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 11:02:42.965   321  6971 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:02:42.965   321  6971 V AwesomePlayer: getUseOffload() = 0 
08-31 11:02:42.965   321  6971 V OMXCodec: OMXCodec::Create
08-31 11:02:42.965   321  6971 V OMXCodec: findMatchingCodecs()
08-31 11:02:42.965   321  6971 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 11:02:42.965   321  6971 V OMXCodec: matchingCodecs.size()=1
08-31 11:02:42.965   321  6971 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 11:02:42.966  6951  6951 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2532065a Instance Count = 1
08-31 11:02:42.972   321  6971 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 11:02:42.972   321  6971 V LGCodecAdapter: LG Codec Adapter start
08-31 11:02:42.972   321  6971 V OMXCodec: OMXCodec Createtor
08-31 11:02:42.972   321  6971 V OMXCodec: setComponentRole
08-31 11:02:42.972   321  6971 V OMXCodec: configureCodec protected=0
08-31 11:02:42.972   321  6971 V LGCodecAdapter: called getLGCodecSpecificData
08-31 11:02:42.972   321  6971 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 11:02:42.972   321  6971 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 11:02:42.972  6951  6951 D BluetoothAdapterApp: onCreate
08-31 11:02:42.972   321  6971 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 11:02:42.972   321  6971 V LGCodecOSAL: Not support LGCodec
08-31 11:02:42.972   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:02:42.972   321  6971 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 11:02:42.972   321  6971 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 11:02:42.972   321  6971 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 11:02:42.972   321  6971 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:02:42.972   321  6971 V AudioSystem: isOffloadSupported()
08-31 11:02:42.972   321  6971 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:02:42.972   321  6971 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 11:02:42.973   321  6971 V OMXCodec: init()
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 11:02:42.973   321  6971 V OMXCodec: allocateBuffers
08-31 11:02:42.973   321  6971 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-31 11:02:42.973   321  6971 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-31 11:02:42.973   321  6971 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c22e0 on output port
08-31 11:02:42.973   321  6971 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 11:02:42.981   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:02:42.981   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 11:02:42.981   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 11:02:42.981   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 11:02:42.981   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 11:02:42.981   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 11:02:42.992   321  6971 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 11:02:42.992   321  6971 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 11:02:42.992   321  6971 V AudioCache: notify(0xb5474680, 5, 0, 0)
08-31 11:02:42.992   321  6971 V AudioCache: ignored
08-31 11:02:42.992   321  6971 V AudioCache: notify(0xb5474680, 1, 0, 0)
08-31 11:02:42.992   321  6971 V AudioCache: prepared
08-31 11:02:42.992   321  1397 V AudioCache: wait - success
08-31 11:02:42.992   321  1397 V MediaPlayerService: start
08-31 11:02:42.992   321  1397 V AwesomePlayer: play_l() 
08-31 11:02:42.992   321  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 11:02:42.992   321  1397 V AwesomePlayer: createAudioPlayer_l
08-31 11:02:42.992   321  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 11:02:42.992   321  1397 V AwesomePlayer: startAudioPlayer_l() 
08-31 11:02:42.992   321  1397 D AudioPlayer: start of Playback, useOffload 0
08-31 11:02:42.992   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:02:42.992   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:02:42.994  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 11:02:42.995   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 11:02:42.995   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 11:02:42.995   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 11:02:42.995   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 11:02:42.995   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 11:02:42.995   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044811488
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 11:02:42.996   321  6973 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:02:42.996   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:02:42.997  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 11:02:42.997   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-31 11:02:42.997   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-31 11:02:42.997   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-31 11:02:42.997   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c2830 on output port
08-31 11:02:42.997   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 11:02:42.997   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 11:02:42.998   321  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 11:02:42.999   321  1397 V AudioCache: notify(0xb5474680, 6, 0, 0)
08-31 11:02:42.999   321  1397 V AudioCache: ignored
08-31 11:02:42.999   321  1397 V MediaPlayerService: wait for playback complete
08-31 11:02:42.999   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:42.999   321  6974 V AudioCache: memcpy(0xac300000, 0xb16f2000, 4096)
08-31 11:02:42.999  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5222
08-31 11:02:43.000   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.000   321  6974 V AudioCache: memcpy(0xac301000, 0xb16f2000, 4096)
08-31 11:02:43.000   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.000   321  6974 V AudioCache: memcpy(0xac302000, 0xb16f2000, 4096)
08-31 11:02:43.001   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.001   321  6974 V AudioCache: memcpy(0xac303000, 0xb16f2000, 4096)
08-31 11:02:43.001   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.001   321  6974 V AudioCache: memcpy(0xac304000, 0xb16f2000, 4096)
08-31 11:02:43.002   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.002   321  6974 V AudioCache: memcpy(0xac305000, 0xb16f2000, 4096)
08-31 11:02:43.002   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.002   321  6974 V AudioCache: memcpy(0xac306000, 0xb16f2000, 4096)
08-31 11:02:43.002   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.002   321  6974 V AudioCache: memcpy(0xac307000, 0xb16f2000, 4096)
08-31 11:02:43.002   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.003   321  6974 V AudioCache: memcpy(0xac308000, 0xb16f2000, 4096)
08-31 11:02:43.003   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.003   321  6974 V AudioCache: memcpy(0xac309000, 0xb16f2000, 4096)
08-31 11:02:43.004   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.004   321  6974 V AudioCache: memcpy(0xac30a000, 0xb16f2000, 4096)
08-31 11:02:43.005   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.005   321  6974 V AudioCache: memcpy(0xac30b000, 0xb16f2000, 4096)
08-31 11:02:43.005   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.006   321  6974 V AudioCache: memcpy(0xac30c000, 0xb16f2000, 4096)
08-31 11:02:43.006   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.006   321  6974 V AudioCache: memcpy(0xac30d000, 0xb16f2000, 4096)
08-31 11:02:43.007   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.007   321  6974 V AudioCache: memcpy(0xac30e000, 0xb16f2000, 4096)
08-31 11:02:43.007   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.007   321  6974 V AudioCache: memcpy(0xac30f000, 0xb16f2000, 4096)
08-31 11:02:43.008   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.008   321  6974 V AudioCache: memcpy(0xac310000, 0xb16f2000, 4096)
,08-31 11:02:43.009   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.009   321  6974 V AudioCache: memcpy(0xac311000, 0xb16f2000, 4096)
08-31 11:02:43.010   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.010   321  6974 V AudioCache: memcpy(0xac312000, 0xb16f2000, 4096)
08-31 11:02:43.010   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.010   321  6974 V AudioCache: memcpy(0xac313000, 0xb16f2000, 4096)
08-31 11:02:43.011  6951  6951 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 11:02:43.011  6951  6951 D ProfileConfigQcom: Adding HeadsetService
08-31 11:02:43.011  6951  6951 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 11:02:43.011  6951  6951 D ProfileConfigQcom: Adding A2dpService
08-31 11:02:43.012   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.012   321  6974 V AudioCache: memcpy(0xac314000, 0xb16f2000, 4096)
08-31 11:02:43.012  6951  6951 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 11:02:43.012  6951  6951 D ProfileConfigQcom: Adding HidService
08-31 11:02:43.012  6951  6951 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 11:02:43.012   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.012   321  6974 V AudioCache: memcpy(0xac315000, 0xb16f2000, 4096)
08-31 11:02:43.012  6951  6951 D ProfileConfigQcom: Adding HealthService
08-31 11:02:43.012  6951  6951 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 11:02:43.013   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.013   321  6974 V AudioCache: memcpy(0xac316000, 0xb16f2000, 4096)
08-31 11:02:43.013  6951  6951 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 11:02:43.013  6951  6951 D ProfileConfigQcom: Adding PanService
08-31 11:02:43.013  6951  6951 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 11:02:43.013   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.013   321  6974 V AudioCache: memcpy(0xac317000, 0xb16f2000, 4096)
08-31 11:02:43.013  6951  6951 D ProfileConfigQcom: Adding GattService
08-31 11:02:43.014  6951  6951 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 11:02:43.014  6951  6951 D ProfileConfigQcom: Adding BluetoothMapService
08-31 11:02:43.014   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.014   321  6974 V AudioCache: memcpy(0xac318000, 0xb16f2000, 4096)
08-31 11:02:43.014  6951  6951 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 11:02:43.014   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.014   321  6974 V AudioCache: memcpy(0xac319000, 0xb16f2000, 4096)
08-31 11:02:43.015   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.015   321  6974 V AudioCache: memcpy(0xac31a000, 0xb16f2000, 4096)
08-31 11:02:43.015   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.015   321  6974 V AudioCache: memcpy(0xac31b000, 0xb16f2000, 4096)
08-31 11:02:43.015  6951  6951 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 11:02:43.017   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.017   321  6974 V AudioCache: memcpy(0xac31c000, 0xb16f2000, 4096)
08-31 11:02:43.017   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.017   321  6974 V AudioCache: memcpy(0xac31d000, 0xb16f2000, 4096)
08-31 11:02:43.018   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.018   321  6974 V AudioCache: memcpy(0xac31e000, 0xb16f2000, 4096)
08-31 11:02:43.018   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.018   321  6974 V AudioCache: memcpy(0xac31f000, 0xb16f2000, 4096)
08-31 11:02:43.019  6809  6809 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 11:02:43.019   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.019   321  6974 V AudioCache: memcpy(0xac320000, 0xb16f2000, 4096)
08-31 11:02:43.019   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.019   321  6974 V AudioCache: memcpy(0xac321000, 0xb16f2000, 4096)
08-31 11:02:43.020   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.020   321  6974 V AudioCache: memcpy(0xac322000, 0xb16f2000, 4096)
08-31 11:02:43.020   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.020   321  6974 V AudioCache: memcpy(0xac323000, 0xb16f2000, 4096)
08-31 11:02:43.021   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.021   321  6974 V AudioCache: memcpy(0xac324000, 0xb16f2000, 4096)
08-31 11:02:43.022  6951  6951 V LGMDMManagerInternal: Create singleton instance
08-31 11:02:43.022   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.022   321  6974 V AudioCache: memcpy(0xac325000, 0xb16f2000, 4096)
08-31 11:02:43.023   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.023   321  6974 V AudioCache: memcpy(0xac326000, 0xb16f2000, 4096)
08-31 11:02:43.024   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.024   321  6974 V AudioCache: memcpy(0xac327000, 0xb16f2000, 4096)
08-31 11:02:43.025   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.025   321  6974 V AudioCache: memcpy(0xac328000, 0xb16f2000, 4096)
08-31 11:02:43.025   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.025   321  6974 V AudioCache: memcpy(0xac329000, 0xb16f2000, 4096)
08-31 11:02:43.025   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.025   321  6974 V AudioCache: memcpy(0xac32a000, 0xb16f2000, 4096)
08-31 11:02:43.026   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.026   321  6974 V AudioCache: memcpy(0xac32b000, 0xb16f2000, 4096)
08-31 11:02:43.026   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.026   321  6974 V AudioCache: memcpy(0xac32c000, 0xb16f2000, 4096)
08-31 11:02:43.027   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.027   321  6974 V AudioCache: memcpy(0xac32d000, 0xb16f2000, 4096)
08-31 11:02:43.027   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.027   321  6974 V AudioCache: memcpy(0xac32e000, 0xb16f2000, 4096)
08-31 11:02:43.028   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.028   321  6974 V AudioCache: memcpy(0xac32f000, 0xb16f2000, 4096)
08-31 11:02:43.028   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.028   321  6974 V AudioCache: memcpy(0xac330000, 0xb16f2000, 4096)
08-31 11:02:43.029   321  6974 V AudioCache: write(0xb16f2000, 4096)
08-31 11:02:43.029   321  6974 V AudioCache: memcpy(0xac331000, 0xb16f2000, 4096)
08-31 11:02:43.029   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 11:02:43.029   321  6974 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 11:02:43.029   321  6974 V AwesomePlayer: postAudioEOS() 
08-31 11:02:43.029   321  6974 V AudioCache: write(0xb16f2000, 280)
08-31 11:02:43.029   321  6974 V AudioCache: memcpy(0xac332000, 0xb16f2000, 280)
08-31 11:02:43.030   321  6971 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 11:02:43.030   321  6971 V AwesomePlayer: onStreamDone
08-31 11:02:43.030   321  6971 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 11:02:43.030   321  6971 V AudioCache: notify(0xb5474680, 2, 0, 0)
08-31 11:02:43.030   321  6971 V AudioCache: playback complete
08-31 11:02:43.030   321  6971 V AwesomePlayer: pause_l() 
08-31 11:02:43.031   321  6971 V AudioCache: notify(0xb5474680, 7, 0, 0)
08-31 11:02:43.031   321  6971 V AudioCache: ignored
08-31 11:02:43.031   321  6971 V AwesomePlayer: cancelPlayerEvents
08-31 11:02:43.031   321  6971 D AudioPlayer: Pause Playback at 1068125
08-31 11:02:43.031   321  1397 V AudioCache: wait - success
08-31 11:02:43.031   321  1397 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 11:02:43.031   321  1397 V AwesomePlayer: reset_l() 
08-31 11:02:43.031   321  1397 V AudioCache: notify(0xb5474680, 8, 0, 0)
08-31 11:02:43.031   321  1397 V AudioCache: ignored
08-31 11:02:43.031   321  1397 V AwesomePlayer: cancelPlayerEvents
08-31 11:02:43.031   321  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 11:02:43.031   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 11:02:43.031   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 11:02:43.031   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 11:02:43.031   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-31 11:02:43.031   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c2830 on port 1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 11:02:43.032   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 11:02:43.032   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 11:02:43.032   321  6973 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 11:02:43.032   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 11:02:43.032   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 11:02:43.032   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 11:02:43.033   321  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 11:02:43.033   321  1397 D AudioPlayer: AudioPlayer releasing audio source
08-31 11:02:43.033   321  1397 D AudioPlayer: AudioPlayer done releasing audio source
08-31 11:02:43.033   321  1397 V AwesomePlayer: reset_l() 
08-31 11:02:43.033   321  1397 V AwesomePlayer: cancelPlayerEvents
08-31 11:02:43.033   321  1397 V AwesomePlayer: ~AwesomePlayer call
08-31 11:02:43.033   321  1397 V AwesomePlayer: reset_l() 
08-31 11:02:43.033   321  1397 V AwesomePlayer: cancelPlayerEvents
08-31 11:02:43.033  6872  6970 V SoundPool: close(31)
08-31 11:02:43.033  6872  6970 V SoundPool: pointer = 0x9ffec000, size = 205080, sampleRate = 48000, numChannels = 2
,08-31 11:02:43.087  6951  6951 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:02:43.089  6951  6951 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:02:43.089  6951  6951 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:02:43.089  6951  6951 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:02:43.090  6951  6951 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:43.090  6951  6951 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 11:02:43.102  6894  6894 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 11:02:43.229  6668  6668 I UEI.SmartControl: Supports setup maps: true
,08-31 11:02:43.232  6668  6668 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:02:43.232  6668  6668 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:02:43.232  6668  6668 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:02:43.232  6668  6668 I UEI.SmartControl: ### init IR Blaster...
08-31 11:02:43.236  6668  6668 D serial_port: Configuring serial port
08-31 11:02:43.236  6668  6668 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:02:43.236  6668  6668 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:02:43.236  6668  6668 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:02:43.236  6668  6668 I UEI.SmartControl: Get version...
08-31 11:02:43.255  6668  6977 D UEI.SmartControl: serial port data available: 21
,08-31 11:02:43.281  6668  6668 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 11:02:43.281  6668  6668 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-31 11:02:43.282  6668  6668 I UEI.SmartControl: QS saving settings...
08-31 11:02:43.284  6668  6668 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 11:02:43.302  6668  6977 D UEI.SmartControl: serial port data available: 4
,08-31 11:02:43.338  6668  6668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 11:02:43.342  6668  6668 E UEI.SmartControl: Services init done
08-31 11:02:43.342  6668  6668 D UEI.SmartControl: QS Service init finished
08-31 11:02:43.342  6668  6983 I UEI.SmartControl: Device manager: loading config....
08-31 11:02:43.343  6668  6668 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:02:43.343  6668  6668 D UEI.SmartControl: QS Service version code: 201091
08-31 11:02:43.344  6668  6668 D UEI.SmartControl: Service requested: Control
,08-31 11:02:43.345  6668  6983 D UEI.SmartControl: ----------- loading internal config...
08-31 11:02:43.354  6668  6983 E UEI.SmartControl: Loading SETTINGS...
08-31 11:02:43.356  6668  6668 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:02:43.357  6668  6668 D UEI.SmartControl: Internal service binding...
,08-31 11:02:43.359  6872  6872 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 11:02:43.360  6668  6683 I UEI.SmartControl: ------ IControl API: 11
08-31 11:02:43.360  6668  6683 D UEI.SmartControl: File observer start...
08-31 11:02:43.361  6668  6683 E UEI.SmartControl: IR Port is disabled: false
08-31 11:02:43.361  6668  6683 D UEI.SmartControl: Starting file observer...
08-31 11:02:43.362  6668  6683 I UEI.SmartControl: Registering callback...
08-31 11:02:43.363  6668  6684 I UEI.SmartControl: ------ IControl API: 19
08-31 11:02:43.365  6668  6684 I UEI.SmartControl: Registering Services Ready callback...
08-31 11:02:43.367  6668  6983 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:02:43.377  6668  6982 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:02:43.378  6668  6982 D UEI.SmartControl: -----service ready thread exits
08-31 11:02:43.378  6872  6888 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 11:02:43.379  6872  6968 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 11:02:43.379  6872  6968 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 11:02:43.379  6872  6872 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 11:02:43.380  6872  6872 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 11:02:43.380  6668  6683 I UEI.SmartControl: ------ IControl API: 8
,08-31 11:02:43.383  6872  6872 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 11:02:43.384  6872  6872 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 11:02:43.385  6872  6872 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 11:02:43.386  6872  6872 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 11:02:43.388  6872  6872 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 11:02:43.389  6872  6872 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 11:02:43.391  6872  6872 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-31 11:02:43.394  6872  6872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-31 11:02:43.395  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:02:43.395  6872  6872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:02:43.396  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 11:02:43.397  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 11:02:43.398  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 11:02:43.398  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 11:02:43.399  6872  6872 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472634163399]
08-31 11:02:43.401  6872  6872 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 11:02:43.405  1036  1895 I ActivityManager: Killing 6062:com.android.gallery3d/u0a27 (adj 15): empty #17
08-31 11:02:43.433  6872  6985 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 11:02:43.441  1036  1895 I ActivityManager: Killing 6456:com.lge.email/u0a23 (adj 15): empty #18
08-31 11:02:43.474  1036  1936 W libprocessgroup: failed to open /acct/uid_10027/pid_6062/cgroup.procs: No such file or directory
,08-31 11:02:43.482  1036  1574 W libprocessgroup: failed to open /acct/uid_10023/pid_6456/cgroup.procs: No such file or directory
08-31 11:02:43.490  6872  6872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-31 11:02:43.492  6872  6872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-31 11:02:43.493  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 11:02:43.494  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 11:02:43.495  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 11:02:43.495  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 11:02:43.496  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 11:02:43.506  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 11:02:44.488  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:44.503  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-31 11:02:44.514  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:02:44.518  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:44.519  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:44.522  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:44.524  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-31 11:02:44.529  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:44.537  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:44.538  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:44.539  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:44.540  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:02:44.544  6369  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:02:44.558  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 11:02:44.565  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:02:44.584  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:44.615  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:44.661  1036  1960 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6992 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-31 11:02:44.670  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:44.670  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:44.687   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 459us total 31.567ms
,08-31 11:02:44.710   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.512ms
,08-31 11:02:44.731   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 408us total 20.134ms
,08-31 11:02:44.732  6992  6992 I AppUp4:AppBoxCP: onCreate
08-31 11:02:44.732  6992  6992 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 11:02:44.741  6992  6992 I AppUp4:DB:  setFingerPrint start
08-31 11:02:44.742  6992  6992 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 11:02:44.749  6992  6992 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 11:02:44.749  6992  6992 I AppUp4:DB:  SDK version = 21
08-31 11:02:44.749  6992  6992 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-31 11:02:44.751  6992  6992 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 11:02:44.752  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:02:44.752  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:44.754  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:02:44.754  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:02:44.759  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 11:02:44.792  6992  6992 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:02:44.792  6992  6992 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:02:44.799  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
08-31 11:02:44.799  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:02:44.799  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:02:44.800  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:02:44.800  6992  6992 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 11:02:44.801  6992  6992 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 11:02:44.801  6992  7025 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 11:02:44.802  6992  7025 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 11:02:44.802  6992  7025 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 11:02:44.803  1036  1936 I ActivityManager: Killing 6492:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-31 11:02:44.862  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:44.862  1036  1995 W libprocessgroup: failed to open /acct/uid_10061/pid_6492/cgroup.procs: No such file or directory
08-31 11:02:44.862  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 11:02:44.868  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:44.874  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:44.890  4289  7029 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:02:44.894  4289  7030 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:44.894  4289  7030 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:02:44.929  1036  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7031 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 11:02:45.030  7031  7031 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:02:45.031  7031  7031 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:02:45.033  7031  7031 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:02:45.033  7031  7031 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:02:45.125  7031  7031 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 11:02:45.151  7031  7031 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 11:02:45.213  7031  7031 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:02:45.270  7031  7031 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:02:45.270  7031  7031 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:02:45.366  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23b3195a type 2 when 160982 com.google.android.gms} when 160982
,08-31 11:02:45.404  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:02:45.435  3498  3498 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:02:45.435  3498  3498 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:45.436  3498  3498 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 11:02:45.485  1036  2033 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7065 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 11:02:45.500  7031  7031 I HubEmail: JNI_OnLoad()
08-31 11:02:45.500  7031  7031 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-31 11:02:45.500  7031  7031 I HubEmail: registerNatives()
08-31 11:02:45.500  7031  7031 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:02:45.500  7031  7031 I HubEmail: registerNativeMethods()
,08-31 11:02:45.500  7031  7031 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:02:45.500  7031  7031 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-31 11:02:45.516  6914  7063 W FormManager: Network not available. Please check & try again.
,08-31 11:02:45.522  6914  7064 V FormManager: Network unavailable.
08-31 11:02:45.523  6914  7064 V FormManager: Network unavailable.
,08-31 11:02:45.535  1036  1996 I ActivityManager: Killing 6128:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-31 11:02:45.594  7065  7065 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:02:45.594  7065  7065 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:02:45.597  7065  7065 D PhoneMonitor: Register our PhoneStateListener
08-31 11:02:45.605  1036  1051 W libprocessgroup: failed to open /acct/uid_10080/pid_6128/cgroup.procs: No such file or directory
,08-31 11:02:45.609  7031  7086 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:45.622  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:02:45.624  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 11:02:45.640  7065  7065 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-31 11:02:45.640  7065  7065 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 11:02:45.641  7065  7065 D TelephonyAutoProfiling: [parse] Load xml
08-31 11:02:45.646  7065  7065 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 11:02:45.646  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 11:02:45.646  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 11:02:45.646  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 11:02:45.646  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 11:02:45.647  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 11:02:45.648  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 11:02:45.648  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 11:02:45.648  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 11:02:45.648  7065  7065 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 11:02:45.663  7065  7065 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-31 11:02:45.675  1036  2032 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7101 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:02:45.676  1036  2032 I ActivityManager: Killing 6157:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-31 11:02:45.722  1036  1895 W libprocessgroup: failed to open /acct/uid_10097/pid_6157/cgroup.procs: No such file or directory
,08-31 11:02:45.966  1036  1891 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7124 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-31 11:02:45.968  1036  1891 I ActivityManager: Killing 6620:com.lge.eula/1000 (adj 15): empty #17
,08-31 11:02:46.013  1036  2033 W libprocessgroup: failed to open /acct/uid_1000/pid_6620/cgroup.procs: No such file or directory
,08-31 11:02:46.126  1036  1995 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7144 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:02:46.128  1036  1995 I ActivityManager: Killing 6639:com.lge.bnr/1000 (adj 15): empty #17
,08-31 11:02:46.183  1036  2033 W libprocessgroup: failed to open /acct/uid_1000/pid_6639/cgroup.procs: No such file or directory
,08-31 11:02:46.217  7144  7144 I art     : Almond Protected OAT
,08-31 11:02:46.276  7144  7144 D WeatherApplication: removeAccount
08-31 11:02:46.277  7144  7144 D WeatherApplication: Account.length = 0
08-31 11:02:46.278  7144  7144 E WeatherApplication: OPERATOR:OPEN
,08-31 11:02:46.285  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:46
,08-31 11:02:46.289  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-31 11:02:46.289  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:02:46.292  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-31 11:02:46.296  7144  7144 D WeatherAncestor: connectivity changed - connection : true
,08-31 11:02:46.297  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-31 11:02:46.310  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-31 11:02:46.310  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:02:46.311  7144  7144 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-31 11:02:46.340  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-31 11:02:46.341  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:46
,08-31 11:02:46.394  1036  1895 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7162 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:02:46.396  1036  1895 I ActivityManager: Killing 2133:com.lge.music/u0a34 (adj 15): empty #17
08-31 11:02:46.424   321   321 V AudioFlinger: 2133 died, releasing its sessions
08-31 11:02:46.424   321   321 V AudioFlinger:  pid 1852 @ 0
08-31 11:02:46.424   321   321 V AudioFlinger:  pid 3498 @ 1
08-31 11:02:46.424   321   321 V AudioFlinger:  pid 3498 @ 2
,08-31 11:02:46.472  1036  1891 D WifiServiceImplEx: setWifiEnabled: true pid=6558, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:02:46.472  1036  1891 D WifiService: setWifiEnabled: true pid=6558, uid=10118
08-31 11:02:46.472  1036  1891 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:02:46.474  1036  1995 W libprocessgroup: failed to open /acct/uid_10034/pid_2133/cgroup.procs: No such file or directory
,08-31 11:02:46.485  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:02:46.485  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:02:46.485  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-31 11:02:46.487  1036  1431 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 11:02:46.487  1036  1431 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 11:02:46.488  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 11:02:46.488  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:02:46.488  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 11:02:46.488  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:02:46.488  1036  1431 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 11:02:46.488  1036  1431 E WifiHW  : unknown target_country: EU , set to default
08-31 11:02:46.489  1036  1431 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 11:02:46.489  1036  1431 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-31 11:02:46.489  1036  1431 I WifiUtil: gEnableBmps=1
,08-31 11:02:46.489  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:46.489  1036  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:46.592   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:02:46.592   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:02:46.592   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:02:46.593  7162  7182 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 11:02:46.594   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-31 11:02:46.594   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:02:46.594   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:02:46.595  7162  7182 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 11:02:46.605   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:02:46.605   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:02:46.605   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:02:46.606  7162  7184 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-31 11:02:46.612   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:02:46.612   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:02:46.612   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:02:46.613  7162  7184 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 11:02:46.829  7162  7162 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 11:02:46.843  7162  7162 I LibraryLoader: Loading: webviewchromium
08-31 11:02:46.847  7162  7162 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2471-2476)
08-31 11:02:46.847  7162  7162 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:02:46.854  7162  7162 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3186e529}
08-31 11:02:46.855  7162  7162 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:02:46.856  7162  7162 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:02:46.870  7162  7162 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 11:02:46.872  7162  7162 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:02:46.884  7162  7162 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-31 11:02:46.886  7162  7162 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-31 11:02:46.891  7162  7162 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-31 11:02:46.894   321  2157 V AudioPolicyService: registerClient() client 0xb57f5720, uid 10093
08-31 11:02:46.895  7162  7206 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 11:02:46.905  7162  7162 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:02:46.905  7162  7162 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:02:46.905  7162  7162 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:02:46.905  7162  7162 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:02:46.905  7162  7162 I Adreno-EGL: Remote Branch: 
08-31 11:02:46.905  7162  7162 I Adreno-EGL: Local Patches: 
08-31 11:02:46.905  7162  7162 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:02:47.003  7162  7162 I NSApplication: Starting up...
,08-31 11:02:47.066  1036  1996 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7225 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:02:47.067  1036  1996 I ActivityManager: Killing 6086:com.android.vending/u0a44 (adj 15): empty #17
,08-31 11:02:47.139   316   916 D SoftapController: Softap fwReload - Ok
,08-31 11:02:47.144  1036  2032 W libprocessgroup: failed to open /acct/uid_10044/pid_6086/cgroup.procs: No such file or directory
08-31 11:02:47.146  1036  1431 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (651ms)
08-31 11:02:47.155   316   916 D CommandListener: Setting iface cfg
08-31 11:02:47.155   316   916 D CommandListener: Trying to bring down wlan0
08-31 11:02:47.156   316   916 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:02:47.159  1036  1431 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-31 11:02:47.158  7243  7243 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:02:47.158  7243  7243 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:47.171  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:02:47.171  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:02:47.171  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:02:47.171  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:02:47.172  1036  1118 D Tethering: InitialState.processMessage what=4
08-31 11:02:47.172  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:02:47.190  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 11:02:47.191  1036  1431 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 11:02:47.191  1036  1431 D WifiMonitor: connecting to supplicant
08-31 11:02:47.192  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:47.194  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-31 11:02:47.198  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:47.201  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:47.202  7243  7243 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 11:02:47.202  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:47.236  7225  7225 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:02:47.240  7243  7243 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:02:47.240  7243  7243 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-31 11:02:47.417  7243  7243 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:02:47.519  7243  7243 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 11:02:47.534  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:02:47.535  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 11:02:47.535  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:02:47.535  1036  1431 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:02:47.536  7243  7243 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 11:02:47.536  7243  7243 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 11:02:47.537  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 11:02:47.538  1036  1431 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:02:47.539  1036  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 11:02:47.539  1036  7260 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:02:47.539  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 11:02:47.539  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 11:02:47.539  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:02:47.539  1036  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:02:47.540  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:47.541  1036  1431 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:47.543  1036  1431 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 11:02:47.543  1036  1431 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 11:02:47.546  1036  1431 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 11:02:47.546  1036  1431 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 11:02:47.546  1036  1431 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 11:02:47.548  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:02:47.548  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:02:47.548  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:02:47.548  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:47.548  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:47.548  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:47.548  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:47.548  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-31 11:02:47.551  1036  1431 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 11:02:47.552  1036  1431 D WifiNative-wlan0: SET update_config 1: returned true
08-31 11:02:47.552  1036  1431 D WifiConfigStore: Loading config and enabling all networks 
08-31 11:02:47.552  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:47.552  1036  1431 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 11:02:47.553  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-31 11:02:47.553  1036  1431 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 11:02:47.558  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:47.558  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:47.558  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:47.558  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:47.560  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:47.560  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:47.560  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:47.560  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:02:47.562  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 11:02:47.562  1036  1447 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 11:02:47.562  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:47.562  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:47.563  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:47.563  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:47.577  1036  1431 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-31 11:02:47.581  1036  2032 I art     : Explicit concurrent mark sweep GC freed 60379(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.366ms total 138.129ms
08-31 11:02:47.582  1036  1431 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 11:02:47.583  1036  1431 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:02:47.585  1036  1431 D WifiStateMachine: enableVerboseLogging : level 2
08-31 11:02:47.585  1036  1431 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 11:02:47.586  1036  1431 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 11:02:47.586  1036  1431 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 11:02:47.586  1036  1431 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 11:02:47.586  1036  1431 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 11:02:47.586  1036  1431 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 11:02:47.586  1036  1431 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 11:02:47.587  1036  1431 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 11:02:47.587  1036  1431 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 11:02:47.587  1036  1431 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 11:02:47.587  1036  1431 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 11:02:47.588  1036  1431 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 11:02:47.588  1036  1431 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 11:02:47.588  1036  1431 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 11:02:47.589  1036  1431 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:02:47.589  1036  1431 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 11:02:47.589  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-31 11:02:47.589  1942  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 11:02:47.590  1942  2273 D WfdsService: Set the WFDS Monitor: true
08-31 11:02:47.590  1942  2273 D WfdsMonitor: WfdsMonitorThread create
08-31 11:02:47.590  1942  2273 D WfdsMonitor: WFDS Monitor is created and started
08-31 11:02:47.590  1942  2273 D WfdsService: WiFi: Supplicant connection re-established
08-31 11:02:47.590  1942  7262 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 11:02:47.591  1942  7262 E CtrlSupplicant: Succeed to open control connection
08-31 11:02:47.591  1942  7262 E CtrlSupplicant: Succeed to open monitor connection
08-31 11:02:47.591  1942  7262 D WfdsMonitor: Supplicant connection established
08-31 11:02:47.591  1942  2273 D WfdsService: Connected to the supplicant for wfds
,08-31 11:02:47.592  1036  1431 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 11:02:47.592  1036  1431 D WifiNative-HAL: Setting external_sim to 1
08-31 11:02:47.592  1036  1431 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 11:02:47.593  1036  1431 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 11:02:47.593  1036  1431 I WifiNative-HAL: startHal
08-31 11:02:47.593  1036  1431 D wifi    : setting scan oui 0xaf5996e0
08-31 11:02:47.593  1036  1431 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:02:47.593  1036  1431 I WifiNative-HAL: startHal
08-31 11:02:47.593  1036  1431 D wifi    : setting scan oui 0xaf5996e0
08-31 11:02:47.594  1036  1431 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 11:02:47.594  1036  1431 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 11:02:47.594  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 11:02:47.594  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 11:02:47.595  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 11:02:47.595  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:02:47.595  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:02:47.595  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:02:47.595  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 11:02:47.595  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 11:02:47.596  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 11:02:47.596  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:02:47.596  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:02:47.596  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:02:47.596  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:02:47.596  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:02:47.597  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:02:47.597  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 11:02:47.597  7243  7243 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 11:02:47.597  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 11:02:47.597  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:02:47.597  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:02:47.598  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:02:47.599  1036  1431 E WifiNative: : [163,215,177 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 11:02:47.599  1036  1431 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 11:02:47.600  1036  1431 D WifiNative-wlan0: RECONNECT: returned true
08-31 11:02:47.600  1036  1431 D WifiNative-wlan0: doString: [STATUS]
08-31 11:02:47.600  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:02:47.600  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 11:02:47.601  1036  1431 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:02:47.601  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:02:47.603  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
,08-31 11:02:47.604  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.605  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:02:47.605  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-31 11:02:47.605  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.605   316   916 D CommandListener: Setting iface cfg
08-31 11:02:47.606  1036  1555 I WifiNative-HAL: startHal
08-31 11:02:47.606   316   916 D CommandListener: Trying to bring up p2p0
08-31 11:02:47.606  1036  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf5996e0
08-31 11:02:47.606  1036  1555 D wifi    : failed to get capabilities : -3
08-31 11:02:47.606  1036  1555 E WifiScanningService: could not get scan capabilities
08-31 11:02:47.606  1036  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.606  1036  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 11:02:47.606  1036  1390 D LGWifiP2pService: P2pEnablingState
08-31 11:02:47.606  1036  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.606  1036  1390 D LGWifiP2pService: P2p socket connection successful
08-31 11:02:47.606  1036  1390 D LGWifiP2pService: P2pEnabledState
08-31 11:02:47.606  1036  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 11:02:47.607  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-31 11:02:47.608  1036  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 11:02:47.608  1942  1942 D WfdsService: WifiP2pState is changed : true
08-31 11:02:47.608  1942  2273 D WfdsService: Receive the WFDS_ENABLE Method
08-31 11:02:47.608  1036  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 11:02:47.608  1942  2273 D WfdsService: Set the WFDS Monitor: true
08-31 11:02:47.609  1036  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 11:02:47.609  1942  2273 D WfdsService: Connected to the supplicant for wfds
08-31 11:02:47.609  1942  2273 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 11:02:47.609  7243  7243 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 11:02:47.609  1942  2273 D WfdsService: selectPreferredScanChannel [36]
08-31 11:02:47.609  1942  2273 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 11:02:47.610  1036  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-31 11:02:47.610  1036  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 11:02:47.610  1036  1390 D LGWifiP2pService: before postfix = G3
08-31 11:02:47.610  1036  1390 D WifiServerServiceExt: postfix byte check : 2
08-31 11:02:47.610  1036  1390 D LGWifiP2pService: after postfix = G3
08-31 11:02:47.610  1036  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 11:02:47.611  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 11:02:47.611  1036  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 11:02:47.611  1036  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 11:02:47.611  1036  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 11:02:47.611  1036  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 11:02:47.611  1036  1431 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-31 11:02:47.612  1942  1942 D WfdsService: isConnected: false
08-31 11:02:47.612  1036  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 11:02:47.612  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-31 11:02:47.612  1036  1431 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 11:02:47.612  1036  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 11:02:47.612  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-31 11:02:47.613  1036  1431 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 11:02:47.613  1036  1431 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 11:02:47.613  1036  1431 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 11:02:47.614  1036  1431 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 11:02:47.614  1036  1431 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 11:02:47.614  1036  1431 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 11:02:47.615  7243  7243 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 11:02:47.615  1036  1431 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-31 11:02:47.615  1036  1431 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 11:02:47.616  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-31 11:02:47.616  1036  1431 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 11:02:47.616  1036  1431 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 11:02:47.616  7243  7243 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 11:02:47.617  1036  1390 D LGWifiP2pService: DeviceAddress: 
08-31 11:02:47.617  1036  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 11:02:47.618  1036  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 11:02:47.618  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-31 11:02:47.618  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 11:02:47.618  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 11:02:47.618  1942  1942 D WfdsService: Update P2p Interface State: 3
08-31 11:02:47.618  1036  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 11:02:47.618  1036  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 11:02:47.619  1036  1390 D WifiNative-p2p0:    returned OK
08-31 11:02:47.619  1036  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 11:02:47.620  1036  1390 D WifiNative-p2p0: SAVE_CONFIG: returned false
08-31 11:02:47.620  1036  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:02:47.620  1036  1390 D LGWifiP2pService: InactiveState
,08-31 11:02:47.620  1036  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.620  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.620  1036  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-31 11:02:47.629  1036  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 11:02:47.629  1036  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.629  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:02:47.629  7243  7243 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.629  1942  7262 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:02:47.629  1036  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:02:47.629  1036  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.629  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.629  1036  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.630  7243  7243 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:02:47.630  7243  7243 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.630  1942  7262 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.630  1036  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.630  1036  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.630  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.630  1036  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.630  7243  7243 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.631  1942  7262 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.631  1036  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.631  1036  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.631  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.631  1036  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.631  1036  1431 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:02:47.631  1036  1431 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:02:47.632  1036  1431 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-31 11:02:47.632  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 11:02:47.632  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.632  1036  1390 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.632  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: InactiveState{ when=-13ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: DefaultState{ when=-13ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: InactiveState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: DefaultState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: InactiveState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.633  1036  1390 D LGWifiP2pService: DefaultState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.634  7243  7243 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.634  1036  1036 E WifiServerServiceExt: No p2p device connected
08-31 11:02:47.634  7243  7243 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:02:47.634  7243  7243 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.635  1942  2273 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 11:02:47.635  7243  7243 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.636  1942  7262 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.636  1942  7262 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.636  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:02:47.636  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.636  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.636  1036  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:02:47.636  1036  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.636  1036  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.636  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.636  1036  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.636  1036  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:02:47.636  1036  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.636  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.636  1036  7260 E WifiMonitor: handleEvent unknow,n: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:02:47.637  1036  1431 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 11:02:47.637  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.637  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:47.637  1036  1431 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:02:47.637  1036  1431 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:02:47.638  1036  1431 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:02:47.638  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 11:02:47.638  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 11:02:47.638  7243  7243 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:02:47.639  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 11:02:47.639  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:02:47.639  1036  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:02:47.639  1036  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:02:47.640  1036  1431 D WifiNative-wlan0: DRIVER SETBAND 0: returned true,
08-31 11:02:47.640  1036  1431 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 11:02:47.640  1036  1431 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 11:02:47.640  1036  1431 D WifiNative-wlan0: doBoolean: SCAN
08-31 11:02:47.641  1036  1431 D WifiNative-wlan0: SCAN: returned false
08-31 11:02:47.641  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=163258  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:02:47.644  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:02:47.645  6369  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:02:47.646  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=163263  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-31 11:02:47.646  1036  1431 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:02:47.647  1036  1431 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:02:47.647  1036  1431 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:02:47.648  1036  1431 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:02:47.648  1036  1431 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:02:47.649  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:47.649  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:47.650  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:47.652  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:47.652  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:47.652  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:02:47.654  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:47.654  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 11:02:47.663  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:47.673  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:02:47.673  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:47.674  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:02:47.674  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:02:47.675  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 11:02:47.678  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
,08-31 11:02:47.678  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:02:47.678  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:02:47.679  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:02:47.679  6992  6992 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:02:47.681  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:47.682  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:02:47.684  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:47.685  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:47.688  4289  7270 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:02:47.689  4289  7271 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:47.690  4289  7271 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:02:47.691  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:02:47.706  6914  7273 W FormManager: Network not available. Please check & try again.
,08-31 11:02:47.710  7031  7275 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:47.712  6914  7274 V FormManager: Network unavailable.
08-31 11:02:47.715  3498  3498 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:02:47.715  3498  3498 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:47.715  3498  3498 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 11:02:47.719  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:02:47.719  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 11:02:47.724  6914  7274 V FormManager: Network unavailable.
08-31 11:02:47.730  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:47
,08-31 11:02:47.733  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:02:47.733  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:02:47.733  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-31 11:02:47.733  7144  7144 D WeatherAncestor: connectivity changed - connection : true
08-31 11:02:47.734  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2dcb06b2
08-31 11:02:47.734  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:02:47.734  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:02:47.734  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:02:47.734  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:02:47.735  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:47
08-31 11:02:47.756   316  7278 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:02:47.757  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 11:02:47.757  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:02:47.758  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:02:47.758  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:02:47.758  6809  6809 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:02:47.759  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:02:47.759  6809  6809 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:02:47.759  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:02:47.759  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:02:47.759  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:02:47.759  6809  6809 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:02:47.759  6809  6809 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:02:47.769  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:02:47.773  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:02:47.777  6914  7280 W FormManager: Network not available. Please check & try again.
08-31 11:02:47.781  6914  7281 V FormManager: Network unavailable.
,08-31 11:02:47.783  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:47.783  6914  7281 V FormManager: Network unavailable.
08-31 11:02:47.806  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:02:47.811  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:02:47.815  6914  7283 W FormManager: Network not available. Please check & try again.
,08-31 11:02:47.823  6914  7284 V FormManager: Network unavailable.
,08-31 11:02:47.823  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:02:47.843  6914  7284 V FormManager: Network unavailable.
,08-31 11:02:47.848  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:02:47.850  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:02:47.855  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:47.858  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:02:47.870  4289  7285 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:02:47.876  4289  7286 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:02:47.876  4289  7286 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:02:47.947  1036  1051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7287 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 11:02:48.069  7287  7287 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:02:48.069  7287  7287 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 11:02:48.082  7287  7287 V [BNRBootReceiver]: Boot Receiver Return
08-31 11:02:48.086  7287  7287 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 11:02:48.088  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.098  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:48.108  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.119  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:02:48.120  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:48.123  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:02:48.124  1036  1732 I ActivityManager: Killing 6848:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-31 11:02:48.143  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 11:02:48.143  7243  7243 E wpa_supplicant: USIM:  scard_init function
08-31 11:02:48.143  1036  7260 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 11:02:48.143  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 11:02:48.143  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPS-AP-AVAILABLE 
08-31 11:02:48.143  1036  7260 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 11:02:48.144  7243  7243 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 11:02:48.145  1036  1431 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:02:48.146  1036  1431 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:02:48.147  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:02:48.147  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 11:02:48.148  1036  1431 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:02:48.148  1036  1431 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:02:48.148  1036  1431 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 11:02:48.179  1036  1959 W libprocessgroup: failed to open /acct/uid_10037/pid_6848/cgroup.procs: No such file or directory
,08-31 11:02:48.189  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 11:02:48.200  6809  6809 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 11:02:48.202  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=163818  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 11:02:48.207  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=163823  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 11:02:48.211  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.211  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.211  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:02:48.212  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.212  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:48.215  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.215  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.215  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:02:48.215  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:48.215  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 11:02:48.215  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.217  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.217  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:48.217  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.218  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:02:48.225  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:48.232  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:02:48.242  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.242  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:48.243  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:02:48.247  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.254  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:48.259  7243  7243 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 11:02:48.259  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 11:02:48.259  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 11:02:48.259  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 11:02:48.259  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 11:02:48.260  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:02:48.260  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:02:48.260  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=163877  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:02:48.261  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=163878  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:02:48.262  1036  1431 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=163879
08-31 11:02:48.262  1036  1431 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=163879
08-31 11:02:48.263  1036  1431 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=163879
08-31 11:02:48.263  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=163880
08-31 11:02:48.264  1036  1431 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=163880
08-31 11:02:48.264  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=163881  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:02:48.264  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:02:48.268  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.268  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:48.268  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.268  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.268  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-31 11:02:48.269  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=163885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:02:48.270  1036  1431 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:48.271  7243  7243 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:02:48.271  7243  7243 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:02:48.271  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:02:48.271  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:02:48.271  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 11:02:48.272  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:02:48.272  1036  7260 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:02:48.272  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 11:02:48.272  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:02:48.273  1036  7260 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:02:48.273  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:02:48.273  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:02:48.273  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.275  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.276  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.276  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 11:02:48.276  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:48.276  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 11:02:48.278  1036  1431 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:48.278  1036  1431 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:48.278  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:48.279  1036  1431 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:48.280  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=163896  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-31 11:02:48.280  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.281  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=163897  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:02:48.282  1036  1431 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=163899
08-31 11:02:48.283  1036  1431 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=163899
08-31 11:02:48.283  1036  1431 D WifiNative-wlan0: doString: [STATUS]
08-31 11:02:48.284  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:02:48.284  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:02:48.284  1036  1431 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:02:48.286  1036  1431 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 11:02:48.287  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:48.287  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 11:02:48.295  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.295  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:48.296  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.296  1036  1431 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 11:02:48.296  1036  1431 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 11:02:48.298  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.299  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:48.299  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:02:48.300  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.300  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.300  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:02:48.304  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.304  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.305  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:02:48.308  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:02:48.308  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:02:48.308  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:02:48.308  6809  6809 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:02:48.310  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-31 11:02:48.312  1036  1431 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 11:02:48.312  1036  1431 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:02:48.312  1036  1431 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:02:48.312  1036  1484 D ConnectivityService: Got NetworkAgent Messenger
08-31 11:02:48.312  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 11:02:48.312  1036  1484 D ConnectivityService: NetworkAgent connected
08-31 11:02:48.312  1036  1431 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:02:48.312  1036  1431 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:02:48.312  6809  6809 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:02:48.312  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 11:02:48.313  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:02:48.313  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:02:48.313  6809  6809 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:02:48.313  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 11:02:48.313  6809  6809 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:02:48.317  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.317  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:48.318  1036  1431 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:02:48.318  1036  1431 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:02:48.318  1036  1431 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:02:48.319  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.319  1036  1431 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:02:48.319  1036  1431 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:02:48.320  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.320  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.320  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 11:02:48.323  1036  1431 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:02:48.324   316   916 D CommandListener: Setting iface cfg
08-31 11:02:48.325  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.332  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:48.333  1036  1431 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 11:02:48.333  1036  7315 D DhcpStateMachine: StoppedState
08-31 11:02:48.333  1036  7315 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.333  1036  7315 D DhcpStateMachine: WaitBeforeStartState
08-31 11:02:48.334  1036  1431 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=163950  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:02:48.334  1036  1431 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=163951  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:02:48.335  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=163951  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-31 11:02:48.336  6668  6984 D UEI.SmartControl: Internal timer expired: 4
08-31 11:02:48.337  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:48.337  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 11:02:48.337  6668  6984 D UEI.SmartControl: unbind internal service
08-31 11:02:48.338  1036  1431 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=163955  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:02:48.339  1036  1431 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=163955  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:02:48.339  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=163956  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:02:48.340  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:118054] from screen [on:0 period:-539614188] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:02:48.341  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.342  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-539614186] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:02:48.342  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:02:48.348  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.348  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:48.349  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.351  1036  1484 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-31 11:02:48.351  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.351  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:02:48.352  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.352  1036  1431 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.353  1036  1431 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.353  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.353  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.354  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:02:48.354  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=111,0,0
08-31 11:02:48.354  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=111,0,0
08-31 11:02:48.355  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 11:02:48.355  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 11:02:48.355  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.356  1036  1431 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 11:02:48.356  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 11:02:48.356  1036  1431 D WifiNative-wlan0: SET ps 0: returned true
08-31 11:02:48.357  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 11:02:48.357  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 11:02:48.357  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 11:02:48.357  1036  1431 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 11:02:48.357  1036  1431 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:02:48.357  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bbe7a70 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.358  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bbe7a70 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.358  1036  1431 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:02:48.358  1036  7315 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.358  1036  7315 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 11:02:48.359   316   916 D CommandListener: Setting iface cfg
08-31 11:02:48.359   316   916 D CommandListener: Trying to bring up wlan0
08-31 11:02:48.361  1036  1431 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-31 11:02:48.364  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:48.366  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:48.366  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:02:48.366  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.367  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:48.367  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:02:48.367  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 11:02:48.367  1036  1431 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.368  1036  1431 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.368  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.369  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:48.369  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:02:48.369  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:02:48.370  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:02:48.370  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:02:48.370  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:02:48.370  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.370  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.371  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:02:48.371  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 11:02:48.371  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 11:02:48.372  1036  1431 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 11:02:48.372  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.372  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:02:48.378  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.379  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:48.379  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:02:48.382  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.388  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:02:48.388  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:02:48.389  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:02:48.389  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:02:48.389  1036  1431 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 11:02:48.390  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:48.390  1036  1484 D ConnectivityService: ignoring duplicate network state non-change
,08-31 11:02:48.396  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.396  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:48.397  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.400  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.400  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.400  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:02:48.400  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.401  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 11:02:48.402  1036  1484 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 11:02:48.404  1036  1431 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:02:48.410  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.410  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.410  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:02:48.412  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:02:48.418  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:02:48.418  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:02:48.418  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:02:48.419  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:02:48.421  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 11:02:48.423  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.423  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:48.424  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.424  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:48.424  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:02:48.425  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.429  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.429  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:02:48.429  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.433  1036  1484 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:02:48.434  1036  1484 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 11:02:48.435  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:48.435  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.435  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:02:48.435  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:48.435  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:02:48.436  1036  1484 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 11:02:48.437   316   916 E Netd    : netlink response contains error (File exists)
08-31 11:02:48.437  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:02:48.437  1036  1484 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-31 11:02:48.438  1036  1484 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 11:02:48.438  1036  1484 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 11:02:48.438  1036  1484 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 11:02:48.441  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.442  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:02:48.442  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 11:02:48.442  1036  1484 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 11:02:48.442  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 11:02:48.442  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:02:48.442  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.442  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 11:02:48.442  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:48.442  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:02:48.442  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:48.442  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.442  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:02:48.442  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 11:02:48.442  1036  1484 D ConnectivityService: currentScore = 0, newScore = 20
08-31 11:02:48.442  1036  1484 D ConnectivityService:    accepting network in place of null
08-31 11:02:48.442  1036  1484 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.443  1036  1431 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.443  1036  1431 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:02:48.444  1036  1484 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU,: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11:02:48.444  1036  1484 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 11:02:48.444  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:02:48.444  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.444  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:02:48.446   316  7319 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 11:02:48.449  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:48.449  1036  1484 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,08-31 11:02:48.450  1036  1484 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 11:02:48.451  6668  6978 D serial_port: close(fd = 24)
08-31 11:02:48.452  1036  1484 D ConnectivityService: validation of new default Network = false
08-31 11:02:48.452  1036  1484 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 11:02:48.453  1036  1484 D DSQN    : enableDataServiceNotify 
08-31 11:02:48.453  1036  1484 D DSQN    : start dsqn bin
08-31 11:02:48.457  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 11:02:48.458  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:02:48.458  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:02:48.458  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:02:48.459  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 11:02:48.459  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.459  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-31 11:02:48.458  7320  7320 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:48.458  7320  7320 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:48.461  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:48.461  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:02:48.464  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:48.470  6668  6978 I UEI.SmartControl: Serial port is closed.
08-31 11:02:48.479  7320  7320 E DSQN    : DSQN ssw
,08-31 11:02:48.484  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.491  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.492  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:48.492  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:02:48.497  1036  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-31 11:02:48.497  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:02:48.498  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.499  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.501  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:02:48.511   316  7319 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 11:02:48.515  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:48.517  1816  7324 I CheckinService: active receiver: enabled
,08-31 11:02:48.521  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.527  1816  7324 I CheckinService: Preparing to send checkin request
08-31 11:02:48.527  1816  7324 I EventLogService: Accumulating logs since 1472634062429
08-31 11:02:48.532  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:02:48.532  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:48.535  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:02:48.540  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:02:48.548  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:48.551   316  7319 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-31 11:02:48.553  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.559  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.559  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:48.559  1036  7315 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 11:02:48.560  1036  7315 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-31 11:02:48.560  1036  7315 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-31 11:02:48.560  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:02:48.562  1816  7324 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-31 11:02:48.558  7326  7326 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:48.558  7326  7326 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:48.566  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.570  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:02:48.572  7326  7326 I dhcpcd  : version 5.5.6 starting
,08-31 11:02:48.574  7326  7326 E dhcpcd  : get_duid: m
08-31 11:02:48.574  7326  7326 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 11:02:48.574  7326  7326 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 11:02:48.576  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:02:48.577   316   915 D LGDataListener: argv[0]=dsqncommand
08-31 11:02:48.577   316   915 D LGDataListener: argv[1]=wlan0
08-31 11:02:48.577   316   915 D LGDataListener: argv[2]=1
08-31 11:02:48.577   316   915 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 11:02:48.578  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 11:02:48.578  1036  1116 D DSQN    : start to monitor internet connection
08-31 11:02:48.580  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:48.586  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.592  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.593  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:48.594  6872  6872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:02:48.595  6872  6872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:02:48.595  6872  6872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-31 11:02:48.600  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:48.602  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:02:48 GMT], X-Android-Received-Millis=[1472634168601], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472634168576]}
08-31 11:02:48.602  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 11:02:48.602  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 11:02:48.602  1036  1484 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-31 11:02:48.602  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 11:02:48.602  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:02:48.602  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:48.603  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:02:48.603  1036  1484 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-31 11:02:48.603  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 11:02:48.603  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.603  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:48.604  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:48.604  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:02:48.606  1036  1484 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.607  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 11:02:48.607  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:02:48.607  1036  1431 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.607  1036  1431 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:02:48.607  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:48.608  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:02:48.608  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:02:48.613  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:48.621  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:48.628  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:48.628  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:48.630  6872  6872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:02:48.631  6872  6872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:02:48.631  6872  6872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-31 11:02:48.638  7326  7326 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:02:48.638  7326  7326 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:02:48.638  7326  7326 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:02:48.638  7326  7326 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 11:02:48.638  7326  7326 D dhcpcd  : wlan0: sending REQUEST (xid 0xab183f24), next in 4.71 seconds
08-31 11:02:48.640  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:02:48.642  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:48.642  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:02:48.665  7326  7326 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 11:02:48.700  7326  7326 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 11:02:48.700  7326  7326 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 11:02:48.701  7326  7326 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 11:02:48.701  7326  7326 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 11:02:48.701  7326  7326 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:02:48.701  7326  7326 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:02:48.701  7326  7326 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:02:48.701  7326  7326 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-31 11:02:48.710  1036  1959 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7335 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 11:02:48.796  7335  7335 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 11:02:48.796  7335  7335 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 11:02:48.827  7335  7335 I MultiDex: VM with version 2.1.0 has multidex support
08-31 11:02:48.827  7335  7335 I MultiDex: install
08-31 11:02:48.827  7335  7335 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 11:02:48.841  7335  7335 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-31 11:02:48.846  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 11:02:48.854  2169  2169 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 11:02:48.855  2169  2169 D c       : Getting all permits...
08-31 11:02:48.855  2169  2169 D a       : Opening database...
08-31 11:02:48.860  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-31 11:02:48.861  2169  2169 D a       : Closing database...
08-31 11:02:48.962  1036  7315 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 11:02:48.964  1036  7315 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-31 11:02:48.964  1036  7315 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:02:48.964  1036  7315 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 11:02:48.964  1036  7315 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 11:02:48.964  1036  7315 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:02:48.964  1036  7315 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 11:02:48.964  1036  7315 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 11:02:48.965  1036  7315 D DhcpStateMachine: RunningState
08-31 11:02:49.247  7335  7353 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:02:49.248  7335  7353 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:02:49.327  7383  7383 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 11:02:49.391  7383  7383 I dex2oat : dex2oat took 63.797ms (threads: 4)
,08-31 11:02:49.403  7335  7353 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:02:49.403  7335  7353 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:02:49.403  7335  7353 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:02:49.403  7335  7353 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:02:49.403  7335  7353 I Adreno-EGL: Remote Branch: 
08-31 11:02:49.403  7335  7353 I Adreno-EGL: Local Patches: 
08-31 11:02:49.403  7335  7353 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:02:49.460  1036  1484 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 11:02:49.527  7335  7353 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:02:49.527  7335  7353 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:02:49.527  7335  7353 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:02:49.527  7335  7353 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:02:49.527  7335  7353 I Adreno-EGL: Remote Branch: 
08-31 11:02:49.527  7335  7353 I Adreno-EGL: Local Patches: 
08-31 11:02:49.527  7335  7353 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:02:49.580  7335  7353 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:02:49.580  7335  7353 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:02:49.580  7335  7353 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:02:49.580  7335  7353 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:02:49.580  7335  7353 I Adreno-EGL: Remote Branch: 
08-31 11:02:49.580  7335  7353 I Adreno-EGL: Local Patches: 
08-31 11:02:49.580  7335  7353 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:02:49.879   316  7390 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 11:02:49.880   316  7390 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-31 11:02:49.930   316  7390 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-31 11:02:50.062  1816  7324 I CheckinTask: Sending checkin request (7833 bytes)
,08-31 11:02:50.284  1036  1431 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:02:50.284  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:02:50.285  1036  1431 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:02:50.285  1036  1431 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:02:50.285  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:02:50.286  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:02:50.288  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-31 11:02:50.288  1036  1484 D ConnectivityService: identical MTU - not setting
08-31 11:02:50.288  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:02:50.288  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 11:02:50.289  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:50.289  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:50.289  1036  1484 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-31 11:02:50.292  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 11:02:50.332  1816  7324 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-31 11:02:50.347  1816  7324 I CheckinService: active receiver: disabled
,08-31 11:02:50.372  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-31 11:02:50.390  2169  2169 I GCM     : GCM config loaded
,08-31 11:02:50.409   316  7397 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-31 11:02:50.411   316  7397 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-31 11:02:50.417  7065  7065 V SetupWizard: Connected to Gservices successfully
,08-31 11:02:50.464   316  7397 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-31 11:02:50.750  2169  7399 D GCM     : Connected
,08-31 11:02:50.788  2169  7399 D GCM     : Message class com.google.e.a.a.q
,08-31 11:02:51.355  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=55.5, 0.0, 0.0  rx=57.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-539611174] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:02:51.358  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=55.5, 0.0, 0.0  rx=57.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-539611171] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:02:51.358  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:02:51.384  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:02:51.415  1036  1441 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-31 11:02:51.451  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:51.458  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-31 11:02:51.466  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:51.466  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:51.466  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.466  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:02:51.475  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:51.478  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:51.478  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:51.478  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.478  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:51.481  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:02:51.482  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:02:51.482  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:02:51.486  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:02:51.495  1036  1758 D WifiServiceImplEx: setWifiEnabled: false pid=6558, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:02:51.495  1036  1758 D WifiService: setWifiEnabled: false pid=6558, uid=10118
08-31 11:02:51.495  1036  1758 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:02:51.503  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:02:51.509  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:02:51.509  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 11:02:51.509  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:02:51.513  1036  1431 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:51.513  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:51.514  1036  1431 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:51.514  1036  1431 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:51.515  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:02:51.515  1036  1431 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:02:51.515  1036  1431 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:02:51.515  1036  1431 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:02:51.516  1036  1431 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:02:51.516  1036  1431 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:02:51.520  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 11:02:51.524  1036  1431 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:02:51.524  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:02:51.524  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:02:51.525  1036  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.525  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.526  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:02:51.526  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:02:51.526  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:02:51.527   316   916 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:02:51.533  1036  7315 D DhcpStateMachine: RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:02:51.587  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 11:02:51.588  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-31 11:02:51.602  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-31 11:02:51.609  6369  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:02:51.614  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.614  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.614  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:02:51.618  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:51.618  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:51.619  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 11:02:51.621  1036  1960 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-31 11:02:51.633  1036  1484 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 11:02:51.633  1036  1484 D DSQN    : disableDataServiceNotify
08-31 11:02:51.633  1036  1484 D DSQN    : stop dsqn bin
08-31 11:02:51.633  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-12ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.633  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-12ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.633  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 11:02:51.633  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.634  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-31 11:02:51.637  1036  1431 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 11:02:51.637  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:51.638  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:51.638  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:51.638  1036  1431 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:51.639  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:51.640  1036  1484 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 11:02:51.640  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:51.640  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:51.640  1036  1484 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:02:51.640  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 11:02:51.641  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:02:51.641   316  7421 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:02:51.641  1036  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.641  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.641  1036  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d1bd2d2
08-31 11:02:51.641  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 11:02:51.641  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.641  1036  1390 D LGWifiP2pService: P2pDisablingState
08-31 11:02:51.641  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.642  1036  7313 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:02:51.642  1036  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.642  1036  1390 D LGWifiP2pService: p2p socket connection lost
08-31 11:02:51.642  1036  1390 D LGWifiP2pService: P2pDisabledState
08-31 11:02:51.642  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:02:51.642  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:02:51.643  1036  1431 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:02:51.643  1036  1431 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 11:02:51.643  1036  1484 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: IN,TERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 11:02:51.643  1036  1484 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 11:02:51.643  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:02:51.644  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.644  1036  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.644  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.645  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:02:51.645  7243  7243 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:02:51.645  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:02:51.645  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:02:51.646  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:02:51.647  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-31 11:02:51.648   316   916 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:02:51.650  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.650  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.650  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:02:51.650  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:02:51.650  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-31 11:02:51.650  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.650  1036  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:51.651  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:02:51.651  1942  1942 D WfdsService: WifiP2pState is changed : false
08-31 11:02:51.651  1942  2273 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 11:02:51.651  1942  2273 D WfdsService: Set the WFDS Monitor: false
08-31 11:02:51.652  1942  2273 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:02:51.652  1942  2273 D WfdsService: STATE : WfdsDisabledState - enter
08-31 11:02:51.652  1942  7262 D CtrlSupplicant: Received on exit socket, terminate
08-31 11:02:51.652  1942  7262 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 11:02:51.652  1942  7262 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 11:02:51.652  1942  7262 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 11:02:51.652  1942  2274 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 11:02:51.653  1942  2273 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 11:02:51.654  1036  1431 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 11:02:51.655  1036  1431 D WifiNative-p2p0: TERMINATE: returned true
08-31 11:02:51.655  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:02:51.655  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:02:51.655  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:02:51.655  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:51.655  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:02:51.656  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:51.656  1036  1484 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:51.656  1036  1484 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:51.656  1036  1484 D NetworkManagementService: Removing idletimer
08-31 11:02:51.656  1036  1484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.656  1036  1431 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:51.656  1036  1484 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 11:02:51.656  1036  1431 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:02:51.656  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:02:51.657  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:02:51.657  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-31 11:02:51.658  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.658  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.658  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:02:51.661  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:02:51.662  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:02:51.662  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:02:51.663  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:02:51.663  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:02:51.666  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 11:02:51.668  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:02:51.669  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:51.669  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:51.669  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.669  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:51.670  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:51.670  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.670  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:51.670  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:51.670  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:51.670  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:51.670  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:51.670  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:02:51.670  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:51.671  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 11:02:51.672  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.672  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:02:51.672  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 11:02:51.672  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:02:51.672  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:02:51.672  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:02:51.672  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:02:51.674  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:02:51.674  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:02:51.675  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.686  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:51.686  7162  7185 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-31 11:02:51.695  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:02:51.695  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:51.695  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:02:51.695  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:02:51.697  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:02:51.700  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
08-31 11:02:51.700  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:02:51.700  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:02:51.700  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:02:51.701  6992  6992 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:02:51.703  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:51.703  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:02:51.706  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:51.708  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:51.712  7243  7243 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 11:02:51.712  7243  7243 I wpa_supplicant: monitor socket send errors count : 1
08-31 11:02:51.712  7243  7243 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
08-31 11:02:51.712  1036  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-31 11:02:51.712  1036  7260 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-31 11:02:51.714  4289  7425 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:02:51.717  4289  7426 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:51.717  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:02:51.717  4289  7426 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:02:51.717  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 11:02:51.717  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.718  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.718  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.731  7031  7427 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:02:51.740  3498  3498 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:02:51.740  3498  3498 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:51.740  3498  3498 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 11:02:51.740  3498  3498 D PhoneState: setPdpRejectCasuse : false
08-31 11:02:51.743  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:02:51.743  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:02:51.748  6914  7430 V FormManager: Network unavailable.
,08-31 11:02:51.750  7243  7243 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:02:51.750  7243  7243 W wpa_supplicant: USIM:  scard_deinit function
08-31 11:02:51.751  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 11:02:51.751  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:02:51.751  1036  7260 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:02:51.751  1036  7260 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 11:02:51.751  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:02:51.751  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:02:51.751  1036  1431 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=167368
08-31 11:02:51.752  1036  1431 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=167368
08-31 11:02:51.752  1036  1431 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=167369  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:02:51.752  1036  1431 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=167369  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:02:51.753  1036  1118 D Tethering: InitialState.processMessage what=4
08-31 11:02:51.755  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:51
08-31 11:02:51.756  6914  7429 W FormManager: Network not available. Please check & try again.
08-31 11:02:51.756  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:02:51.756  1036  1431 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:51.757  1036  1431 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:02:51.758  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:02:51.758  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:02:51.758  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:02:51.758  7144  7144 D WeatherAncestor: connectivity changed - connection : true
08-31 11:02:51.758  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2dcb06b2
08-31 11:02:51.759  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:02:51.759  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:02:51.759  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:02:51.759  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:02:51.759  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:51
,08-31 11:02:51.764  6914  7430 V FormManager: Network unavailable.
08-31 11:02:51.772  1036  7315 D DhcpStateMachine: StoppedState
08-31 11:02:51.772  1036  7315 D DhcpStateMachine: StoppedState{ when=-126ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:02:51.773  1036  1431 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-31 11:02:51.774  1036  1431 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 11:02:51.775  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:02:51.776  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.777  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:02:51.782  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:51.785  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:02:51.785  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:02:51.785  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:02:51.789  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:02:51.795  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:51.800  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:51.800  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:51.802  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:02:51.805  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:51.808  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:02:51.808  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:02:51.808  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:02:51.812  7243  7243 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-31 11:02:51.813  1036  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 11:02:51.813  1036  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 11:02:51.813  1036  7260 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 11:02:51.815  1036  1431 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 43 0
08-31 11:02:51.816  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:51.824  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:02:51.835  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:51.835  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:02:51.837  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:02:51.842  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:02:51.846  6827  6827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:02:51.846  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:02:51.846  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:02:51.852  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:02:51.859  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:51.867  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:02:51.867  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:02:51.869  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:02:51.880  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:02:51.885  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:02:51.890  6914  7434 W FormManager: Network not available. Please check & try again.
,08-31 11:02:51.896  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:51.896  6914  7435 V FormManager: Network unavailable.
08-31 11:02:51.908  6914  7435 V FormManager: Network unavailable.
,08-31 11:02:51.918  1036  1431 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 11:02:51.918  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-31 11:02:51.918  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:02:51.918  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:02:51.918  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:02:51.918  1942  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 11:02:51.918  1942  2273 D WfdsService: Set the WFDS Monitor: false
08-31 11:02:51.918  1942  2273 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:02:51.927  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:02:51.927  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:02:51.930  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:51.934  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 11:02:51.934  1036  1447 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 11:02:51.934  1036  1447 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 11:02:51.938  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:51.939  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:51.941  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:51.945  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:02:51.945  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-31 11:02:51.945  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:02:51.945  6809  6809 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:02:51.946  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:02:51.947  6809  6809 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:02:51.948  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:02:51.948  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:02:51.948  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:02:51.948  6809  6809 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:02:51.948  6809  6809 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:02:51.953  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:02:51.953  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:02:51.956  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:51.958  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:02:51.968  4289  7436 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:02:51.969  6827  6827 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 11:02:51.969  6827  6827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:02:51.969  6827  6827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:02:51.973  4289  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 11:02:51.973  4289  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:02:51.974  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:02:51.981  6914  7439 W FormManager: Network not available. Please check & try again.
08-31 11:02:51.983  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:02:51.999  6914  7440 V FormManager: Network unavailable.
,08-31 11:02:52.001  6914  7440 V FormManager: Network unavailable.
08-31 11:02:52.237  1036  1114 W ProcessCpuTracker: Skipping unknown process pid 7410
08-31 11:02:52.239  1036  1114 W ProcessCpuTracker: Skipping unknown process pid 7413
,08-31 11:02:52.243  1036  1114 W ProcessCpuTracker: Skipping unknown process pid 7442
08-31 11:02:52.243  1036  1114 W ProcessCpuTracker: Skipping unknown process pid 7443
08-31 11:02:52.653  1036  1960 I ActivityManager: Killing 6894:com.lge.settings.easy/1000 (adj 15): empty #17
,08-31 11:02:52.685  1036  1758 W libprocessgroup: failed to open /acct/uid_1000/pid_6894/cgroup.procs: No such file or directory
,08-31 11:02:54.398  1036  1431 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-539608130] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:02:54.401  1036  1431 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-539608128] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:02:54.659  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:54.675  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-31 11:02:54.690  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:02:54.694  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:54.695  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:54.696  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:54.698  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:54.704  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:02:54.715  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:54.716  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:02:54.720  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:54.723  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:02:54.725  6369  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:02:54.736  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 11:02:54.745  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 11:02:54.763  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:54.782  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:02:54.782  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:54.782  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:02:54.782  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 11:02:54.786  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:02:54.790  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
08-31 11:02:54.790  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:02:54.790  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:02:54.791  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:02:54.791  6992  6992 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:02:54.796  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:54.796  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:02:54.798  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:02:54.803  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:54.810  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:02:54.837  3498  3498 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:02:54.837  3498  3498 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:54.837  3498  3498 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 11:02:54.848  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:02:54.848  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:02:54.851  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:54.855  4289  7452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:02:54.857  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:54.857  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:02:54.864  4289  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:54.864  4289  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:02:54.866  7031  7451 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:02:54.870  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:54
,08-31 11:02:54.872  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:02:54.872  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:02:54.873  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:02:54.873  7144  7144 D WeatherAncestor: connectivity changed - connection : true
08-31 11:02:54.873  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2dcb06b2
08-31 11:02:54.872  6914  7467 W FormManager: Network not available. Please check & try again.
08-31 11:02:54.874  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:02:54.874  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:02:54.874  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:02:54.874  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:02:54.874  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:54
08-31 11:02:54.880  6914  7468 V FormManager: Network unavailable.
,08-31 11:02:54.886  6914  7468 V FormManager: Network unavailable.
08-31 11:02:54.894  1036  1574 I ActivityManager: Killing 7287:com.lge.bnr/1000 (adj 15): empty #17
,08-31 11:02:54.994  1036  1891 W libprocessgroup: failed to open /acct/uid_1000/pid_7287/cgroup.procs: No such file or directory
,08-31 11:02:55.004  6369  6369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 11:02:55.010  6369  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:02:55.042  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:55.072  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:02:55.072  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:55.072  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:02:55.073  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 11:02:55.076  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:02:55.081  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
08-31 11:02:55.081  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:02:55.081  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:02:55.082  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:02:55.083  6992  6992 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:02:55.090  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:55.091  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 11:02:55.094  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:55.098  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:02:55.108  4289  7474 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:02:55.109  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:02:55.115  4289  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:02:55.115  4289  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:02:55.142  7031  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:02:55.146  6914  7479 W FormManager: Network not available. Please check & try again.
08-31 11:02:55.170  3498  3498 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:02:55.170  3498  3498 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:02:55.170  3498  3498 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 11:02:55.173  6914  7480 V FormManager: Network unavailable.
,08-31 11:02:55.175  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:02:55.175  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:02:55.186  6914  7480 V FormManager: Network unavailable.
08-31 11:02:55.190  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:55
,08-31 11:02:55.193  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-31 11:02:55.194  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
,08-31 11:02:55.194  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-31 11:02:55.195  7144  7144 D WeatherAncestor: connectivity changed - connection : true
,08-31 11:02:55.195  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2dcb06b2,
08-31 11:02:55.197  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:02:55.197  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:02:55.197  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:02:55.197  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-31 11:02:55.197  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:2:55,
,08-31 11:02:56.515  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:02:56.515  1036  2033 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 11:02:56.549  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:02:56.550  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:02:56.550  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:02:56.553  1036  1118 D BluetoothManagerService: Message: 1
08-31 11:02:56.553  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 11:02:56.583  1036  1118 D BluetoothManagerService: Message: 20
08-31 11:02:56.583  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@73688e7:true
,08-31 11:02:56.585  6951  6951 D BluetoothAdapterState: make
08-31 11:02:56.591  6951  6951 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 11:02:56.591  6951  6951 I bluedroid-qcom: init
08-31 11:02:56.593  6951  7492 I BluetoothAdapterState: Entering OffState
08-31 11:02:56.593  6951  6951 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 11:02:56.593  6951  6951 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:02:56.593  6951  6951 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:02:56.593  6951  6951 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:02:56.593  6951  6951 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 11:02:56.595  6951  6951 I bluedroid-qcom: get_profile_interface socket
08-31 11:02:56.595  6951  6951 I bluedroid-qcom: get_profile_interface map_client
,08-31 11:02:56.599  6951  7496 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 11:02:56.603  6951  7496 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 11:02:56.598  7495  7495 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:56.598  7495  7495 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:56.614  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-31 11:02:56.616  1036  1118 D BluetoothManagerService: Message: 40
08-31 11:02:56.616  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 11:02:56.620  7495  7495 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 11:02:56.620  7495  7495 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 11:02:56.620  7495  7495 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 11:02:56.622  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:02:56.622  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:02:56.623  6951  6967 I bluedroid-qcom: config_hci_snoop_log
08-31 11:02:56.624  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 11:02:56.624  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 11:02:56.625  7495  7495 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-31 11:02:56.635  7495  7495 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 11:02:56.635  7495  7495 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 11:02:56.637  6951  7492 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-31 11:02:56.639  6951  7496 D BluetoothAdapterProperties: Name is: G3
08-31 11:02:56.640  6951  7492 D BluetoothAdapterProperties: Setting state to 11
08-31 11:02:56.640  6951  7492 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:02:56.641  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:02:56.641  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 11:02:56.641  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 11:02:56.643  6951  7492 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 11:02:56.646  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:56.646  1036  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:02:56.649  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:02:56.653  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:02:56.656  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:56.657  1036  1431 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-31 11:02:56.658  1036  1431 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-31 11:02:56.658  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:56.659  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:56.661  6809  6809 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-31 11:02:56.678  6951  6951 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-31 11:02:56.680  6951  6951 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:56.681  6951  6951 V BluetoothPbapReceiver: ***********state = 11
08-31 11:02:56.686  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:02:56.688  6951  7492 D BluetoothBondStateMachine: make
08-31 11:02:56.694  6951  7492 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
,08-31 11:02:56.695  6951  7492 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 11:02:56.695  6951  7512 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 11:02:56.695  6951  7492 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:56.695  6951  7492 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 11:02:56.696  6951  7492 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 11:02:56.700  6951  7492 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:02:56.735  1036  1960 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7513 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 11:02:56.740  6951  7492 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:02:56.742  6951  6951 D HeadsetService: Received start request. Starting profile...
08-31 11:02:56.742  6951  6951 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:02:56.742  6951  6951 D LGBluetoothHfpAdapter: Version 1.6
08-31 11:02:56.746  6951  6951 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:02:56.746  6951  7492 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:02:56.747  6951  6951 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:02:56.747  6951  6951 D HeadsetStateMachine: make
08-31 11:02:56.749  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25928cf5 type 2 when 172365 com.google.android.gms} when 172365
,08-31 11:02:56.754   316  7526 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:02:56.755  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 11:02:56.764  6951  7492 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:02:56.767  6872  6872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-31 11:02:56.767  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5222
08-31 11:02:56.771  6951  7492 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:02:56.775  6951  7492 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:02:56.779  6951  7492 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:02:56.787  6951  6951 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:02:56.787  6951  6951 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:02:56.790  6951  7492 V LGMDMManager: Create singleton instance
,08-31 11:02:56.792  6951  6951 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:02:56.792  6951  6951 I bluedroid-qcom: get_profile_interface handsfree
08-31 11:02:56.792  6951  7492 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 11:02:56.794  6951  6951 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 11:02:56.794   321  1397 V AudioPolicyService: registerClient() client 0xb57ebf80, uid 1002
,08-31 11:02:56.795   321   321 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:02:56.795   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:02:56.795   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:02:56.795  6951  6951 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:02:56.795   321  2157 V AudioFlinger: registerClient() client 0xb55818c8, pid 6951
08-31 11:02:56.795   321  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:02:56.795   321  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:02:56.796  6951  6951 V ToneGenerator: Create Track: 0xb4928080
08-31 11:02:56.796  6951  6951 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 11:02:56.796  6951  6951 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 11:02:56.796  1036  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:02:56.796   321  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:02:56.796  1036  1995 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:02:56.796   321  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:02:56.796   321  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:02:56.796   321  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:02:56.796  1602  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:02:56.796  1602  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-31 11:02:56.796  6951  6951 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:02:56.796  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:02:56.796  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:02:56.796  6951  7497 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:02:56.796  6951  7497 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 11:02:56.796  3498  3514 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:02:56.796  3498  3514 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:02:56.796   321  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:02:56.796   321  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:02:56.796   321  1396 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:02:56.796  6951  7497 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:02:56.796  6951  7497 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 11:02:56.796  1036  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:02:56.796   321  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:02:56.796  1036  1574 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:02:56.796   321  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
,08-31 11:02:56.796   321  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:02:56.796   321  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:02:56.797  6951  6951 V AudioSystem: getLatency() output 2, latency 50
08-31 11:02:56.797  6951  6951 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 11:02:56.797  1602  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:02:56.797  6951  6951 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 11:02:56.797  1602  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:02:56.797  1852  3976 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:02:56.797  1852  3976 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:02:56.797  3498  3513 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:02:56.797  3498  3513 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:02:56.797   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:02:56.797   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:02:56.797   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:02:56.797   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:02:56.797   321   321 V AudioFlinger: createTrack() lSessionId: 20
08-31 11:02:56.798  6951  6951 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 11:02:56.798   321  2157 V AudioFlinger: acquiring 20 from 6951, for 6951
08-31 11:02:56.798   321  2157 V AudioFlinger:  added new entry for 20
08-31 11:02:56.798  6951  6951 V ToneGenerator: ToneGenerator INIT OK, time: 172427
08-31 11:02:56.798  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:56.799  6951  7523 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 11:02:56.799  6951  7523 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:02:56.799  6951  7523 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:02:56.799  6951  7523 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 11:02:56.799   321  1396 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6951
08-31 11:02:56.800  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:56.800   321  1396 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 11:02:56.800   321  1396 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 11:02:56.800   321  1396 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 11:02:56.800   321  1396 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 11:02:56.800   321  1396 V voice   : voice_set_parameters: exit with code(0)
08-31 11:02:56.800   321  1396 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 11:02:56.800   321  1396 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 11:02:56.800   321  1396 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 11:02:56.800   321  1396 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 11:02:56.800   321  1396 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 11:02:56.800   321  1396 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 11:02:56.800  6951  7523 V ToneGenerator: ToneGenerator destructor
08-31 11:02:56.800  6951  7523 V ToneGenerator: stopTone
08-31 11:02:56.800  6951  7523 V ToneGenerator: Delete Track: 0xb4928080
08-31 11:02:56.801   321  1397 V AudioPolicyService: AudioCommandThread() adding release output 2
08-3,1 11:02:56.801   321  1397 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 11:02:56.801   321  1274 V AudioPolicyService: AudioCommandThread() waking up
08-31 11:02:56.801   321  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 11:02:56.801   321  1274 V AudioPolicyManager: releaseOutput() 2
08-31 11:02:56.801   321  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 11:02:56.801   321  1397 V AudioFlinger: PlaybackThread::Track destructor
08-31 11:02:56.801   321  1397 V AudioFlinger: removeClient_l() pid 6951, calling pid 321
08-31 11:02:56.802  6951  7523 V AudioTrack: ~AudioTrack, releasing session id from 6951 on behalf of 6951
08-31 11:02:56.802  6951  6951 D A2dpService: Received start request. Starting profile...
08-31 11:02:56.802   321  2157 V AudioFlinger: releasing 20 from 6951 for 6951
08-31 11:02:56.802   321  2157 V AudioFlinger:  decremented refcount to 0
08-31 11:02:56.802   321  2157 V AudioFlinger: purging stale effects
08-31 11:02:56.803  6951  6951 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:02:56.804  6951  6951 V Avrcp   : make
,08-31 11:02:56.804  6951  6951 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-31 11:02:56.804  6951  6951 I bluedroid-qcom: get_profile_interface avrcp
08-31 11:02:56.806  1036  1995 W Process : Unable to open /proc/7536/status
08-31 11:02:56.812  6951  6951 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 11:02:56.813  6951  6951 E AudioManager: No RCC entry present to update
08-31 11:02:56.813  6951  6951 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 11:02:56.816  6951  6951 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-31 11:02:56.817  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 11:02:56.817  6951  6951 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 11:02:56.821  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:02:56.864  7513  7513 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 11:02:56.865  7513  7513 W LG Account v2.2: No ProfileInfo entries
08-31 11:02:56.865  7513  7513 I LG Account v2.2: isEnabled: false
,08-31 11:02:56.865  7513  7513 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 11:02:56.865  7513  7513 I Feature : [Lifetracker]Country: EU
08-31 11:02:56.866  7513  7513 I Feature : [Lifetracker]Operator: OPEN
08-31 11:02:56.866  7513  7513 I Feature : [Lifetracker]Ranking support: false
08-31 11:02:56.866  7513  7513 I Feature : [Lifetracker]Comfort support: false
08-31 11:02:56.866  7513  7513 I Feature : [Lifetracker]Accessory: true
08-31 11:02:56.866  7513  7513 I Feature : [Lifetracker]Health device: true
08-31 11:02:56.867  7513  7513 I Feature : [Lifetracker]Extra Pedometer: false
08-31 11:02:56.867  7513  7513 I Feature : [Lifetracker]Blood glucose device: false
08-31 11:02:56.867  7513  7513 I Feature : [Lifetracker]Device Number: 3
,08-31 11:02:56.879  6809  6809 D BluetoothPermissionRequest: onReceive
,08-31 11:02:56.889  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:02:56.924  1036  1996 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:02:56.924  1036  1996 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:02:57.037  1036  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 11:02:57.045  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 11:02:57.049  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:02:57.050  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:02:57.051  6951  6951 I BluetoothA2dpServiceJni: classInitNative
08-31 11:02:57.051  6951  6951 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:02:57.051  6951  6951 D A2dpStateMachine: make
,08-31 11:02:57.054  6951  6951 I bluedroid-qcom: get_profile_interface a2dp
08-31 11:02:57.055  6951  7543 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:02:57.059  6951  6951 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:02:57.059  6951  6951 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 11:02:57.062  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:57.062  6951  7542 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:02:57.064  6951  6951 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 11:02:57.068  6951  6951 D HidService: Received start request. Starting profile...
08-31 11:02:57.068  6951  6951 I bluedroid-qcom: get_profile_interface hidhost
08-31 11:02:57.069  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:57.069  6951  6951 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:02:57.070  6951  6951 D HealthService: Received start request. Starting profile...
08-31 11:02:57.077  6951  6951 I bluedroid-qcom: get_profile_interface health
,08-31 11:02:57.077  6951  6951 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:02:57.077  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:57.078  6951  6951 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 11:02:57.081  6951  6951 D PanService: Received start request. Starting profile...
08-31 11:02:57.081  6951  6951 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:02:57.081  6951  6951 I bluedroid-qcom: get_profile_interface pan
08-31 11:02:57.089  6951  6951 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 11:02:57.089  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
,08-31 11:02:57.093  6951  6951 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 11:02:57.112  6951  6951 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:02:57.113  6951  6951 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:02:57.113  6951  6951 D BtGatt.GattService: start()
08-31 11:02:57.114  6951  6951 I bluedroid-qcom: get_profile_interface gatt
08-31 11:02:57.115  6951  6951 D BtGatt.AdvertiseManager: advertise manager created
08-31 11:02:57.128  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
,08-31 11:02:57.136  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
,08-31 11:02:57.137  6951  6951 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 11:02:57.138  6951  6951 V BluetoothMapService: BluetoothMapBinder()
08-31 11:02:57.139  6951  6951 D BluetoothMapService: Received start request. Starting profile...
08-31 11:02:57.139  6951  6951 D BluetoothMapService: start()
,08-31 11:02:57.143  6951  6951 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 11:02:57.144  6951  6951 D BluetoothMapEmailAppObserver: createReceiver()
08-31 11:02:57.146  6951  6951 D BluetoothMapEmailAppObserver: initObservers()
08-31 11:02:57.146  6951  6951 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 11:02:57.159  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:57.159  6951  6951 D HeadsetStateMachine: Proxy object connected
08-31 11:02:57.160  6951  6951 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 11:02:57.160  6951  6951 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-31 11:02:57.166  6951  6951 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:02:57.167  6951  7523 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 11:02:57.168  6951  7523 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:02:57.168  6951  7523 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 11:02:57.174  6951  6951 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 11:02:57.178  6951  6951 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:02:57.181  6951  6951 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:02:57.181  6951  6951 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 11:02:57.184  6951  6951 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:02:57.187  6951  6951 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 11:02:57.187  6951  6951 V BluetoothMapService: Handler(): got msg=1
,08-31 11:02:57.189  6951  6951 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:57.190  6951  7492 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:02:57.190  6951  7492 I bluedroid-qcom: enable
08-31 11:02:57.190  6951  7492 I bt_hci_bdroid: init
08-31 11:02:57.191  6951  7492 I bt_vendor: bt-vendor : init
08-31 11:02:57.191  6951  7492 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:02:57.191  6951  7492 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:02:57.192  6951  7492 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 11:02:57.192  6951  7492 D bt_userial_mct: userial_init
08-31 11:02:57.192  6951  6951 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:02:57.192  6951  6951 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:02:57.192  6951  6951 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:02:57.192  6951  6951 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:57.193  6951  6951 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 11:02:57.196  6951  7556 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 11:02:57.196  6951  7556 I bt-btu  : btu_task pending for preload complete event
,08-31 11:02:57.197  6951  7492 D bt_hci_bdroid: set_power 1
08-31 11:02:57.197  6951  7492 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 11:02:57.197  6951  7492 I bt_vendor: Starting hciattach daemon
08-31 11:02:57.197  6951  7492 I bt_vendor: try to set true
08-31 11:02:57.188  7559  7559 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:57.188  7559  7559 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:02:57.225  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 11:02:57.270   348   348 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 26.453ms
,08-31 11:02:57.270  1036  1574 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7562 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:02:57.305   348   348 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 33.200ms
,08-31 11:02:57.321  7591  7591 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 11:02:57.326   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.552ms
08-31 11:02:57.336  7593  7593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:02:57.358  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:02:57.361  7562  7562 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:02:57.371  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 11:02:57.376  1036  1574 I ActivityManager: Killing 6827:com.lge.sync/1000 (adj 15): empty #17
,08-31 11:02:57.382  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-31 11:02:57.393  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 11:02:57.417  7602  7602 I libmdmdetect: ESOC framework not supported
08-31 11:02:57.417  7602  7602 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 11:02:57.424  1036  1732 W libprocessgroup: failed to open /acct/uid_1000/pid_6827/cgroup.procs: No such file or directory
,08-31 11:02:57.425  7602  7602 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-31 11:02:57.425  7602  7602 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 11:02:57.425  7602  7602 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 11:02:57.425  7602  7602 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 11:02:57.425  7602  7602 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 11:02:57.425  7602  7602 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 11:02:57.425  7602  7602 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 11:02:57.464  7602  7603 E QC-QMI  : qmi_client [7602] 14: failed to locate client data
08-31 11:02:57.465   489   489 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 11:02:57.465   489   489 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-31 11:02:57.525  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 11:02:57.555  7605  7605 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:02:57.608  6951  7492 I bt_vendor: bluetooth satus is on
08-31 11:02:57.608  6951  7492 D bt_hci_bdroid: preload
,08-31 11:02:57.609  6951  7558 D bt_userial_mct: userial_open(port:0)
,08-31 11:02:57.609  6951  7558 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 11:02:57.612  6951  7558 I bt_vendor: Done intiailizing UART
08-31 11:02:57.613  6951  7558 I bt_vendor: Done intiailizing UART
08-31 11:02:57.613  6951  7558 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 11:02:57.614  6951  7558 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 11:02:57.614  6951  7556 I bt-btu  : btu_task received preload complete event
08-31 11:02:57.614  6951  7610 D bt_userial_mct: Entering userial_read_thread()
08-31 11:02:57.614  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 11:02:57.615  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 11:02:57.617  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:02:57.621  6951  7556 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:02:57.737  6951  7556 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-31 11:02:57.737  6951  7556 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01fa061 ,
,08-31 11:02:57.737  6951  7556 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01fa061 
,08-31 11:02:57.788  6951  7496 E bt-btif : Calling BTA_HhEnable
,08-31 11:02:57.788  6951  7496 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-31 11:02:57.796  6951  7496 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 11:02:57.799  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-31 11:02:57.800  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 11:02:57.801  6951  7496 D BluetoothAdapterProperties: Name is: G3
08-31 11:02:57.806  6951  7496 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:02:57.806  6951  7496 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:02:57.807  6951  7496 D bt_hci_bdroid: postload
,08-31 11:02:57.819  6951  7496 D bte_conf: Device ID record 1 : primary
08-31 11:02:57.819  6951  7496 D bte_conf:   vendorId            = 00c4
08-31 11:02:57.819  6951  7496 D bte_conf:   vendorIdSource      = 0001
08-31 11:02:57.819  6951  7496 D bte_conf:   product             = 13a1
08-31 11:02:57.819  6951  7496 D bte_conf:   version             = 1000
08-31 11:02:57.819  6951  7496 D bte_conf:   clientExecutableURL = 
08-31 11:02:57.819  6951  7496 D bte_conf:   serviceDescription  = 
08-31 11:02:57.819  6951  7496 D bte_conf:   documentationURL    = 
08-31 11:02:57.819  6951  7496 D bte_conf: bte_load_did_conf no section named DID2.
08-31 11:02:57.824  6951  7558 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:02:57.825  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:02:57.831  6951  7492 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:02:57.831  6951  7492 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:02:57.832  6951  7492 D BluetoothAdapterProperties: State =  11
08-31 11:02:57.832  6951  7492 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 11:02:57.832  6951  7492 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 11:02:57.832  6951  7492 D BluetoothAdapterProperties: Setting state to 12
08-31 11:02:57.832  6951  7492 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:02:57.833  6951  7496 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:02:57.828  7618  7618 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:02:57.828  7618  7618 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:02:57.847  6951  7492 I BluetoothAdapterState: Entering On State
08-31 11:02:57.849  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:02:57.849  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,08-31 11:02:57.849  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:57.858  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:57.872  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:02:57.875  6951  7496 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:02:57.875  6951  7496 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:57.884  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:02:57.889  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:57.898  6951  7492 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 11:02:57.899  6951  7492 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 11:02:57.899  6951  7492 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-31 11:02:57.910  6951  7492 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 11:02:57.910  6951  7492 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 11:02:57.911  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 11:02:57.911  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 11:02:57.911  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-31 11:02:57.913  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 11:02:57.913  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 11:02:57.913  6951  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 11:02:57.914  6951  7496 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:02:57.914  6951  7558 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:02:57.915  6809  6826 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:02:57.942  6951  7558 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 11:02:57.948  7623  7623 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 11:02:57.951  6951  7610 E bt_mct  : hci lib postload completed
08-31 11:02:57.952  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:02:57.956  1852  1852 D BluetoothHeadset: Proxy object connected
,08-31 11:02:57.959  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:02:57.959  1036  1036 D BluetoothHeadset: Proxy object connected
08-31 11:02:57.961  6809  6825 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:02:57.966  6809  6826 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:02:57.967  6951  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:02:57.967  6951  7556 W bt-smp  : Plain text(LSB ~ MSB) = c1 c3 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:02:57.967  6951  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e ab de 0c bc 8b 47 26 75 43 e3 fc 96 24 2b 57 
08-31 11:02:57.967  6951  7556 W bt-btm  : Stopping oneshot timer
08-31 11:02:57.971  1852  2448 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:02:57.976  1852  1852 D BluetoothHeadset: Proxy object connected
08-31 11:02:57.976  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:02:57.978  1036  1036 D BluetoothA2dp: Proxy object connected
08-31 11:02:57.980  6809  6825 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:02:57.980  6809  6825 D BluetoothPan: onBluetoothStateChange call bindService
08-31 11:02:57.984  1852  3976 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:02:57.987  6951  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:02:57.987  6951  7556 W bt-smp  : Plain text(LSB ~ MSB) = a9 11 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:02:57.987  6951  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 de 5d 10 e1 2d a2 3e 83 bd 71 b0 de e3 42 89 
08-31 11:02:57.987  6951  7556 W bt-btm  : Stopping oneshot timer
08-31 11:02:57.989  1852  1852 D BluetoothHeadset: Proxy object connected
08-31 11:02:57.997  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 11:02:57.998  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 11:02:57.998  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 11:02:57.998  6809  6809 D BluetoothInputDevice: Proxy object connected
08-31 11:02:57.998  6809  6809 D HidProfile: Bluetooth service connected
,08-31 11:02:57.999  1036  1118 D BluetoothManagerService: Message: 40
08-31 11:02:58.000  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 11:02:58.004  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:02:58.007  6558  6558 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 11:02:58.010  6951  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-31 11:02:58.010  6951  7556 W bt-smp  : Plain text(LSB ~ MSB) = ba f9 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:02:58.010  6951  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = ee f2 fe a5 5f 4d 89 97 a2 f4 8c bd c0 ac 5a 95 
08-31 11:02:58.010  6951  7556 W bt-btm  : Stopping oneshot timer
08-31 11:02:58.012  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:58.012  1942  2128 D LGBluetoothAPIService: Message: 1
08-31 11:02:58.012  1942  2128 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:02:58.017  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:02:58.019  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:02:58.019  6951  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:02:58.019  6951  7556 W bt-smp  : Plain text(LSB ~ MSB) = 9f 3c 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:02:58.019  6951  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e ad 4d 82 f1 55 ca 6e 36 e7 ce 69 07 33 f4 22 
08-31 11:02:58.019  6951  7556 W bt-btm  : Stopping oneshot timer
08-31 11:02:58.020  6951  6951 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:58.020  6951  6951 D BluetoothMapService: STATE_ON
08-31 11:02:58.021  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:58.023  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:02:58.025  1942  2128 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 11:02:58.026  6809  6809 D BluetoothMap: Proxy object connected
08-31 11:02:58.026  6809  6809 D MapProfile: Bluetooth service connected
08-31 11:02:58.026  6809  6809 D BluetoothMap: getConnectedDevices()
08-31 11:02:58.027  6951  7497 V BluetoothMapService: getConnectedDevices()
08-31 11:02:58.028  6809  6809 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:02:58.028  6809  6809 D PanProfile: Bluetooth service connected
08-31 11:02:58.029  6951  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:02:58.029  6951  7556 W bt-smp  : Plain text(LSB ~ MSB) = fd 3a 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:02:58.029  6951  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = 19 69 7d 0d 4b 2b 1d 43 f0 64 dc 79 fd 80 9f 56 
08-31 11:02:58.029  6951  7556 W bt-btm  : Stopping oneshot timer
08-31 11:02:58.031  6809  6809 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 11:02:58.033  1036  1118 D BluetoothManagerService: Message: 30
08-31 11:02:58.033  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:58.034  6951  6951 V BluetoothPbapService: Pbap Service onCreate
08-31 11:02:58.034  6951  6951 V BluetoothPbapService: Starting PBAP service
08-31 11:02:58.035  6951  6951 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-31 11:02:58.035  6951  6951 V BluetoothPbapService: Pbap Service onBind
08-31 11:02:58.039  6951  6951 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:58.039  6951  6951 V BluetoothPbapService: state: 12
08-31 11:02:58.039  6951  6951 V BluetoothMapService: Handler(): got msg=1
08-31 11:02:58.040  6951  6951 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 11:02:58.040  6809  6809 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 11:02:58.042  6951  6951 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 11:02:58.042  6951  6951 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 11:02:58.042  6951  7643 D BluetoothMapMasInstance: MAS initSocket()
08-31 11:02:58.043  6951  7643 D BluetoothMapMasInstance:   masId = 00
08-31 11:02:58.043  6951  7643 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 11:02:58.043  6951  7643 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 11:02:58.043  6951  7643 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 11:02:58.043  1036  1118 D BluetoothManagerService: Message: 30
08-31 11:02:58.044  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 11:02:58.044  1942  2128 D LGBluetoothAPIService: Message: 100
08-31 11:02:58.044  1942  2128 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 11:02:58.044  1036  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:58.044  6951  6951 V BluetoothPbapService: Handler(): got msg=1
08-31 11:02:58.044  6951  6951 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 11:02:58.045  6951  7643 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:02:58.046  6951  7644 V BluetoothPbapService: Pbap Service initSocket
08-31 11:02:58.047  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:02:58.048  6951  7643 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 11:02:58.048  6951  7643 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 11:02:58.048  6951  7643 D BluetoothMapMasInstance: Accepting socket connection...
08-31 11:02:58.049  6951  7496 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:02:58.049  6951  7496 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 11:02:58.050  6951  7644 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:02:58.051  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:58.052  6951  7644 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 11:02:58.052  6951  7644 V BluetoothPbapService: Succeed to create listening socket 
08-31 11:02:58.053  6951  7644 V BluetoothPbapService: Accepting socket connection...
08-31 11:02:58.053  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:58.053  6809  6809 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 11:02:58.054  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:02:58.055  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:02:58.059  6809  6809 D BluetoothPbap: Proxy object connected
08-31 11:02:58.060  6809  6809 D PbapServerProfile: Bluetooth service connected
08-31 11:02:58.060  6809  6809 D BluetoothA2dp: Proxy object connected
,08-31 11:02:58.060  6951  6951 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:02:58.060  6951  6951 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:58.060  6951  6951 V BluetoothPbapReceiver: ***********state = 12
08-31 11:02:58.060  6809  6809 D A2dpProfile: Bluetooth service connected
08-31 11:02:58.063  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:02:58.064  2169  2169 D c       : Getting all permits...
08-31 11:02:58.064  2169  2169 D a       : Opening database...
08-31 11:02:58.065  6809  6809 D BluetoothHeadset: Proxy object connected
08-31 11:02:58.067  6809  6809 D HeadsetProfile: Bluetooth service connected
08-31 11:02:58.068  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-31 11:02:58.068  2169  2169 D a       : Closing database...
08-31 11:02:58.072  6809  6809 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:02:58.079  6809  6809 D BluetoothPermissionRequest: onReceive
08-31 11:02:58.080  6809  6809 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:02:58.082  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:02:58.084  6951  6951 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-31 11:02:58.085  6951  6951 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-31 11:02:58.090  6951  6951 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 11:02:58.107  6951  6951 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:02:58.107  6951  6951 V BtOppService: onCreate
,08-31 11:02:58.112  6951  6951 V BluetoothOppNotification: send message
08-31 11:02:58.116  6951  6951 V BtOppService: Starting RfcommListener
08-31 11:02:58.122  6951  6951 D BluetoothOppPreference: Dumping Names:  
08-31 11:02:58.122  6951  6951 D BluetoothOppPreference: {}
08-31 11:02:58.122  6951  6951 D BluetoothOppPreference: Dumping Channels:  
08-31 11:02:58.122  6951  6951 D BluetoothOppPreference: {}
,08-31 11:02:58.128  6951  6951 V BtOppService: onStartCommand
,08-31 11:02:58.129  6951  7649 V BtOppService: Deleted complete outbound shares, number =  0
08-31 11:02:58.130  6951  7649 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 11:02:58.130  6951  7653 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:02:58.131  6951  7649 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 11:02:58.131  6951  7653 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:02:58.134  6951  6951 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:58.134  6951  6951 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-31 11:02:58.232  1036  1732 I art     : Explicit concurrent mark sweep GC freed 136179(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.590ms total 100.280ms
08-31 11:02:58.234  6951  7649 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1897902f on behalf of 
,08-31 11:02:58.235  6951  7653 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19d0e63c on behalf of ,
08-31 11:02:58.235  6951  6951 V BluetoothOppNotification: new notify threadi!
08-31 11:02:58.237  6951  6951 V BluetoothOppNotification: send delay message
08-31 11:02:58.238  6951  7654 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:02:58.238  6951  6951 V BtOppService: start RfcommListener
08-31 11:02:58.240  6951  6951 V BtOppService: RfcommListener started
08-31 11:02:58.241  6951  6951 V BtOppService: ContentObserver received notification
08-31 11:02:58.241  6951  6951 V BtOppService: ContentObserver received notification
08-31 11:02:58.242  6951  7653 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:02:58.243  6951  7653 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:02:58.245  6951  7655 V BtOppRfcommListener: Starting RFCOMM listener....
,08-31 11:02:58.246  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:58.247  6951  7655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:02:58.250  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:58.250  6951  7655 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-31 11:02:58.250  6951  6951 V BluetoothFtpService: Ftp Service onCreate
08-31 11:02:58.250  6951  6951 I BluetoothFtpService: Ftp Service onCreate
,08-31 11:02:58.250  6951  6951 V BluetoothFtpService: Ftp Service onStartCommand
,08-31 11:02:58.250  6951  6951 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:58.250  6951  6951 V BluetoothFtpService: Starting Listening on sockets
,08-31 11:02:58.250  6951  6951 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:02:58.250  6951  6951 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-31 11:02:58.250  6951  6951 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:02:58.250  6951  6951 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:02:58.250  6951  6951 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 11:02:58.250  6951  6951 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-31 11:02:58.251  6951  7655 V BtOppRfcommListener: Started RFCOMM listener....
08-31 11:02:58.251  6951  7655 I BtOppRfcommListener: Accept thread started.
08-31 11:02:58.251  6951  7655 V BtOppRfcommListener: Accepting connection...
08-31 11:02:58.253  6951  6951 V BluetoothFtpService: Handler(): got msg=1
08-31 11:02:58.253  6951  6951 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 11:02:58.253  6951  6951 V BluetoothFtpService: Ftp Service initSocket
08-31 11:02:58.255  1036  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:02:58.257  6951  7654 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f029d1a on behalf of 
08-31 11:02:58.257  6951  6951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:02:58.258  6951  6951 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-31 11:02:58.258  6951  6951 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 11:02:58.258  6951  7653 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c17004b on behalf of 
08-31 11:02:58.259  6951  7656 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 11:02:58.261  6951  7654 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:02:58.262  6951  7653 V BluetoothOppNotification: update too frequent, put in queue
,08-31 11:02:58.270  6951  7654 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:02:58.270  6951  7653 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:02:58.271  6951  7654 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ce42a28 on behalf of 
08-31 11:02:58.271  6951  7654 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:02:58.272  6951  7654 V BluetoothOppNotification: outbound notification was removed.
08-31 11:02:58.272  6951  7654 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:02:58.273  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:02:58.273  6951  6951 V BluetoothSapService: Sap Service onCreate
,08-31 11:02:58.273  6951  7654 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14ee5341 on behalf of 
,08-31 11:02:58.274  6951  7654 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:02:58.275  6951  6951 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:02:58.275  6951  6951 V BluetoothSapService: state: 12
08-31 11:02:58.275  6951  6951 V BluetoothSapService: Starting SAP server process
08-31 11:02:58.275  6951  7654 V BluetoothOppNotification: inbound notification was removed.
08-31 11:02:58.275  6951  7654 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:02:58.276  6951  7654 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@170be27d on behalf of 
08-31 11:02:58.276  6951  6951 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 11:02:58.277  6951  7658 V BluetoothSapService: Sap Service initRfcommSocket
,08-31 11:02:58.277  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-31 11:02:58.268  7657  7657 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:02:58.268  7657  7657 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file,
08-31 11:02:58.281  6951  7658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:02:58.282  6951  7658 V BluetoothSapService: Succeed to create listening socket 
08-31 11:02:58.282  6951  7658 V BluetoothSapService: Accepting socket connection...
,08-31 11:02:58.283  7657  7657 V BT_SAP  : Event pipe created
08-31 11:02:58.283  7657  7657 V BT_SAP  : create_server_socket qcom.sap.server
08-31 11:02:58.283  7657  7657 V BT_SAP  : created socket fd 6
08-31 11:02:58.588  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 11:02:58.602  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 11:02:58.623  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 11:02:58.657  1036  1114 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7665 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 11:02:58.666  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-31 11:02:58.670  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-31 11:02:58.688  1036  1036 D administrator: Handling package changes for user 0
,08-31 11:02:58.698  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:02:58.740  7665  7665 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:02:58.813  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-31 11:02:58.813  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-31 11:02:58.813  7665  7665 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:02:58.813  7665  7665 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:02:58.866  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:02:58.875  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-31 11:02:58.886  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 11:02:58.887  2508  2508 V GmsNetworkLocationProvi: DISABLE
08-31 11:02:58.890  7665  7703 I Babel   : MmsConfig: mnc/mcc: 0/0
08-31 11:02:58.890  7665  7703 I Babel   : MmsConfig.loadMmsSettings
08-31 11:02:58.898  7665  7703 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 11:02:58.898  7665  7703 I Babel   : MmsConfig.loadFromDatabase
,08-31 11:02:58.910  7665  7703 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-31 11:02:58.910  7665  7703 I Babel   : MmsConfig.loadFromResources
08-31 11:02:58.912  7665  7703 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 11:02:58.913  7665  7703 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 11:02:58.929  1036  1113 D LocationProviderProxy: applying state to connected service
,08-31 11:02:58.930  2508  2508 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-31 11:02:58.957  7665  7665 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:02:58.963  7665  7702 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:02:58.964  7665  7702 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:02:58.966  7665  7702 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:02:58.979  7665  7702 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 11:02:58.983  7665  7702 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:02:58.984  7665  7702 W AudioCapabilities: Unsupported mime audio/evrc
08-31 11:02:58.988  1816  7707 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 11:02:58.988  1816  7707 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-31 11:02:58.995  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:02:59.001  7665  7702 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-31 11:02:59.002  1816  4755 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-31 11:02:59.005  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
08-31 11:02:59.005  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:02:59.005  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:02:59.005  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:02:59.005  6992  6992 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-31 11:02:59.007  7665  7702 W VideoCapabilities: Unsupported mime video/divx
08-31 11:02:59.013  7665  7702 W VideoCapabilities: Unsupported mime video/divx311
,08-31 11:02:59.016  7665  7702 W VideoCapabilities: Unsupported mime video/divx4
08-31 11:02:59.023  7665  7702 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 11:02:59.038  7665  7702 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 11:02:59.042  7665  7702 W AudioCapabilities: Unsupported mime audio/eac3
08-31 11:02:59.043  7665  7702 W AudioCapabilities: Unsupported mime audio/ac3
08-31 11:02:59.044  7665  7702 W AudioCapabilities: Unsupported mime audio/g726
08-31 11:02:59.046  7665  7702 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 11:02:59.047  7665  7702 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 11:02:59.047  1036  1891 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7710 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-31 11:02:59.048  7665  7702 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 11:02:59.050  7665  7702 W VideoCapabilities: Unsupported mime video/theora
08-31 11:02:59.052  1036  1936 I ActivityManager: Killing 7335:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-31 11:02:59.058  7665  7702 W VideoCapabilities: Unsupported mime video/mjpg
,08-31 11:02:59.162  1036  1960 W libprocessgroup: failed to open /acct/uid_10005/pid_7335/cgroup.procs: No such file or directory
08-31 11:02:59.202  7710  7710 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:02:59.203  7710  7710 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:02:59.204  7710  7710 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-31 11:02:59.207  7710  7710 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 11:02:59.208  7710  7710 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:02:59.239  6951  6951 V BluetoothOppNotification: new notify threadi!
08-31 11:02:59.239  6951  6951 V BluetoothOppNotification: send delay message
,08-31 11:02:59.241  6951  7728 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:02:59.243  6951  7728 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18bfb572 on behalf of 
,08-31 11:02:59.244  6951  7728 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:02:59.246  6951  7728 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:02:59.247  6951  7728 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b152dc3 on behalf of 
08-31 11:02:59.248  6951  7728 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:02:59.249  6951  7728 V BluetoothOppNotification: outbound notification was removed.
08-31 11:02:59.249  6951  7728 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:02:59.250  6951  7728 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c81640 on behalf of 
08-31 11:02:59.251  6951  7728 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:02:59.253  6951  7728 V BluetoothOppNotification: inbound notification was removed.
08-31 11:02:59.253  6951  7728 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-31 11:02:59.255  6951  7728 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8792979 on behalf of 
08-31 11:02:59.292  7710  7710 I SystemConfig: BUILD Country: EU
08-31 11:02:59.292  7710  7710 I SystemConfig: BUILD Operator: OPEN
,08-31 11:02:59.367  1036  1891 I ActivityManager: Killing 7031:com.lge.email/u0a23 (adj 15): empty #17
,08-31 11:02:59.453  1036  1959 W libprocessgroup: failed to open /acct/uid_10023/pid_7031/cgroup.procs: No such file or directory
,08-31 11:02:59.469  7710  7732 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-31 11:02:59.469  7710  7732 I SystemConfig: existFile = false
08-31 11:02:59.469  7710  7732 I SystemConfig: canReadFile = false
08-31 11:02:59.469  7710  7732 I SystemConfig: systemFeature RCS result false
,08-31 11:02:59.471  7710  7732 D SystemConfig: refreshRcsSupport() :false
08-31 11:02:59.506  1036  1574 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7734 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 11:02:59.556  7734  7734 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:02:59.556  7734  7734 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:02:59.557  7734  7734 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 11:02:59.557  7734  7734 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:02:59.641  7734  7734 I AppConfig: Total System Memory = 2995761152
,08-31 11:02:59.652  7734  7734 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 11:02:59.754  1036  1922 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7754 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:02:59.755  1036  1922 I ActivityManager: Killing 6914:com.lge.formmanager/u0a26 (adj 15): empty #17
08-31 11:02:59.832  1036  1758 W libprocessgroup: failed to open /acct/uid_10026/pid_6914/cgroup.procs: No such file or directory
,08-31 11:03:00.037  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-31 11:03:00.037  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 11:03:00.037  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 11:03:00.037  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-31 11:03:00.042  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-31 11:03:00.042  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:03:00.044  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:03:00.045  7754  7754 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 11:03:00.046  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 11:03:00.117  1036  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=916018145, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-31 11:03:00.117  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1341a43c type 2 when 175733 com.google.android.gms} when 175733
,08-31 11:03:00.161  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 11:03:00.198  7754  7754 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:03:00.198  7754  7754 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:03:00.248  7754  7754 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 11:03:00.269  7754  7754 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:03:00.270  7754  7754 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:03:00.287  7754  7754 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:03:00.287  7754  7754 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-31 11:03:00.306  1036  1574 I ActivityManager: Killing 6369:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-31 11:03:00.366  1036  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_6369/cgroup.procs: No such file or directory
,08-31 11:03:00.373  2846  2863 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-31 11:03:00.375  2846  2863 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@274a12f8 on behalf of 7754
08-31 11:03:00.379  4603  7791 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-31 11:03:00.453  1036  1922 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7792 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-31 11:03:00.475  7754  7754 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-31 11:03:00.501  7754  7754 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-31 11:03:00.548  7792  7792 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 11:03:00.577  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-31 11:03:00.577  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-31 11:03:00.577  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-31 11:03:00.577  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 11:03:00.577  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 11:03:00.577  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-31 11:03:00.589  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=916018145 [*alarm*], flags=0x0
08-31 11:03:00.591   316  7814 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-31 11:03:00.592  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:03:00.603  1036  2032 I ActivityManager: Killing 7065:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-31 11:03:00.635  1036  1051 W libprocessgroup: failed to open /acct/uid_10046/pid_7065/cgroup.procs: No such file or directory
,08-31 11:03:00.784  1036  1895 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:03:00.806  4603  7791 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 427 ms] updated apps [took 427 ms] 
,08-31 11:03:01.568  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:03:01.568  1036  2032 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@298c683b mBinding = false
,08-31 11:03:01.599  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:03:01.599  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:03:01.599  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:03:01.602  1036  1118 D BluetoothManagerService: Message: 2
08-31 11:03:01.603  1036  1118 D BluetoothManagerService: Sending off request.
08-31 11:03:01.604  6951  6966 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 11:03:01.605  6951  7492 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 11:03:01.605  6951  7492 D BluetoothAdapterProperties: Setting state to 13
08-31 11:03:01.605  6951  7492 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:03:01.606  6951  7492 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:03:01.606  6951  7492 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 11:03:01.609  6951  7496 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:03:01.610  6951  7492 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:03:01.611  6951  7644 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 11:03:01.615  6951  7655 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:03:01.616  6951  7656 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:03:01.617  6951  7658 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:03:01.618  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 11:03:01.618  6951  7556 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 11:03:01.620  6951  7643 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 11:03:01.621  6951  7492 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 11:03:01.626  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 11:03:01.626  6951  7556 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-31 11:03:01.638  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:01.639  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:03:01.643  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:03:01.643  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:03:01.647  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:01.647  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:03:01.648  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:03:01.648  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:03:01.651  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:01.651  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:03:01.655  6558  6558 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:03:01.657  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:03:01.657  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:03:01.658  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 11:03:01.658  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 11:03:01.660  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:01.662  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:03:01.664  1036  1484 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-31 11:03:01.669  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:01.671  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:01.673  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:01.674  6951  6951 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:01.674  6951  6951 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:03:01.674  6951  6951 V BluetoothMapService: Handler(): got msg=4
08-31 11:03:01.674  6951  6951 D BluetoothMapService: MAP Service closeService in
08-31 11:03:01.674  6951  6951 D BluetoothMapMasInstance: MAP Service shutdown
08-31 11:03:01.674  6951  6951 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:03:01.674  6951  6951 V BluetoothMapService: MAP Service closeService out
08-31 11:03:01.675  6951  6951 V BtOppService: Receiver DISABLED_ACTION 
08-31 11:03:01.676  6951  6951 I BtOppRfcommListener: stopping Accept Thread
08-31 11:03:01.676  6951  6951 V BtOppRfcommListener: close mBtServerSocket
,08-31 11:03:01.678  6951  7655 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:03:01.679  6951  6951 V BtOppRfcommListener: waiting for thread to terminate
08-31 11:03:01.679  6951  6951 V BtOppRfcommListener: done waiting for thread to terminate
08-31 11:03:01.683  6809  6809 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-31 11:03:01.690  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 11:03:01.694  6951  6951 V BtOppService: onDestroy
08-31 11:03:01.695  6951  6951 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 11:03:01.700  6951  6951 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:03:01.700  6951  6951 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:01.700  6951  6951 V BluetoothPbapReceiver: ***********state = 13
08-31 11:03:01.702  6951  6951 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-31 11:03:01.706  6951  6951 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:03:01.706  6951  6951 V BluetoothPbapService: state: 13
08-31 11:03:01.707  6951  6951 V BluetoothPbapService: Pbap Service closeService in
08-31 11:03:01.709  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:03:01.710  6951  6951 V BluetoothPbapService: successfully stopped pbap service
08-31 11:03:01.710  6951  6951 V BluetoothPbapService: Pbap Service closeService out
08-31 11:03:01.711  6951  6951 V BluetoothPbapService: Pbap Service onDestroy
08-31 11:03:01.712  6951  6951 V BluetoothPbapService: Pbap Service closeService in
08-31 11:03:01.712  6951  6951 V BluetoothPbapService: Pbap Service closeService out
08-31 11:03:01.712  6951  6951 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-31 11:03:01.740  6809  6809 D DockEventReceiver: finishStartingService: stopping service
08-31 11:03:01.741  6809  6809 D BluetoothPbap: Proxy object disconnected
08-31 11:03:01.741  6809  6809 D PbapServerProfile: Bluetooth service disconnected
08-31 11:03:01.744  6809  6809 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 11:03:01.748  6809  6809 D BluetoothPermissionRequest: onReceive
08-31 11:03:01.748  6809  6809 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 11:03:01.752  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:03:01.756  6951  6951 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 11:03:01.756  6951  6951 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 11:03:01.756  6951  6951 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 11:03:01.759  6951  6951 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:01.760  6951  6951 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:03:01.760  6951  6951 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:03:01.760  6951  6951 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:01.761  6951  6951 V BluetoothFtpService: Ftp Service closeService
08-31 11:03:01.761  6951  6951 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-31 11:03:01.762  6951  6951 V BluetoothFtpService: successfully stopped ftp service
,08-31 11:03:01.762  6951  6951 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-31 11:03:01.762  6951  6951 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:03:01.762  6951  6951 V BluetoothSapReceiver: SapReceiver onReceive 
,08-31 11:03:01.763  6951  6951 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:01.763  6951  6951 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-31 11:03:01.763  6951  6951 V BluetoothSapReceiver: Calling SAP service start service with action = null,
08-31 11:03:01.764  6951  6951 V BluetoothFtpService: Ftp Service onDestroy,
08-31 11:03:01.764  6951  6951 V BluetoothFtpService: Ftp Service closeService
08-31 11:03:01.764  6951  6951 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:01.764  6951  6951 V BluetoothSapService: state: 13
08-31 11:03:01.765  6951  6951 V BluetoothSapService: Stopping SAP server process
08-31 11:03:01.765  6951  6951 V BluetoothSapService: Sap Service closeSapService in
08-31 11:03:01.766  6951  6951 V BluetoothSapService: Close listen Socket : 
08-31 11:03:01.766  6951  6951 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:03:01.766  6951  6951 V BluetoothSapService: Close sapd  Socket : 
,08-31 11:03:01.768  6951  6951 V BluetoothSapService: Sap Service closeSapService out
08-31 11:03:01.768  6951  6951 V BluetoothSapService: Sap Service onDestroy
08-31 11:03:01.768  6951  6951 V BluetoothSapService: Sap Service closeSapService in
08-31 11:03:01.768  6951  6951 V BluetoothSapService: Close listen Socket : 
08-31 11:03:01.768  6951  6951 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:03:01.768  6951  6951 V BluetoothSapService: Close sapd  Socket : 
08-31 11:03:01.768  6951  6951 V BluetoothSapService: Sap Service closeSapService out
08-31 11:03:02.526  6951  7496 D bt_hci_bdroid: cleanup
,08-31 11:03:02.544  6951  7610 I bt_userial_mct: exiting userial_read_thread
08-31 11:03:02.544  6951  7610 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 11:03:02.544  6951  7558 I bt_lpm  : LPM is already off!!!
08-31 11:03:02.546  6951  7556 W bt-btif : ag scb idx 1 not allocated
08-31 11:03:02.546  6951  7556 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:03:02.546  6951  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:03:02.546  6951  7556 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:03:02.547  6951  7496 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 11:03:02.547  6951  7558 I bt_vendor: hw_epilog_process
08-31 11:03:02.548  6951  7496 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 11:03:02.548  6951  7496 D bt_userial_mct: userial_close
08-31 11:03:02.548  6951  7496 E bt_userial_mct: pthread_join() FAILED result:3
08-31 11:03:02.548  6951  7496 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 11:03:02.552  6951  7496 D bt_hci_bdroid: set_power 0
08-31 11:03:02.552  6951  7496 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:03:02.552  6951  7496 I bt_vendor: bluetooth satus is on
08-31 11:03:02.552  6951  7496 I bt_vendor: bt-vendor : resetting BT status
08-31 11:03:02.552  6951  7496 I bt_vendor: Starting hciattach daemon
08-31 11:03:02.552  6951  7496 I bt_vendor: try to set false
08-31 11:03:02.554  6951  7496 I bt_vendor: Starting hciattach daemon
08-31 11:03:02.554  6951  7496 I bt_vendor: try to set false
,08-31 11:03:02.560  6951  7496 I bt_vendor: cleanup
08-31 11:03:02.562  6951  7556 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 11:03:02.562  6951  7496 I GKI_LINUX: GKI_exit_task 0 done
08-31 11:03:02.562  6951  7496 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 11:03:02.564  6951  7492 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:03:02.571  6951  6951 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:03:02.575  6951  7492 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:03:02.577  6951  6951 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:03:02.577  6951  6951 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:03:02.577  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:03:02.578  6951  7523 D HeadsetStateMachine: Exit Disconnected: -1
08-31 11:03:02.580  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-31 11:03:02.580  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-31 11:03:02.580  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-31 11:03:02.581  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-31 11:03:02.581  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 11:03:02.583  6951  6951 D A2dpService: Received stop request...Stopping profile...
,08-31 11:03:02.585  6951  7542 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:03:02.587  6951  6951 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 11:03:02.589  6951  6951 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 11:03:02.589  6951  6951 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:03:02.589  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:03:02.590  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-31 11:03:02.590  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:03:02.592  6951  6951 D HidService: Received stop request...Stopping profile...
08-31 11:03:02.592  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:03:02.594  6951  6951 D HealthService: Received stop request...Stopping profile...
08-31 11:03:02.594  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
,08-31 11:03:02.599  6951  6951 D PanService: Received stop request...Stopping profile...
08-31 11:03:02.600  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:03:02.601  6951  6951 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:03:02.603  6951  6951 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:03:02.603  6951  6951 D BtGatt.GattService: stop()
08-31 11:03:02.603  6951  6951 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:03:02.604  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:03:02.605  6951  6951 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:03:02.605  6951  6951 D BluetoothMapService: stop()
08-31 11:03:02.606  6951  6951 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 11:03:02.606  6951  6951 D BluetoothMapEmailAppObserver: removeReceiver()
,08-31 11:03:02.608  6951  6951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dcb06b2
08-31 11:03:02.610  6951  6951 D HeadsetStateMachine: Unbinding service...
08-31 11:03:02.612  6951  6951 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:03:02.612  6951  6951 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:03:02.612  6951  6951 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:03:02.612  6951  6951 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:03:02.612  6951  6951 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:03:02.612  6951  6951 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:03:02.612  6951  6951 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:03:02.613  6951  6951 I BluetoothA2dpServiceJni: cleanupNative
08-31 11:03:02.613  6951  7543 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:03:02.614  6951  6951 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:03:02.614  6951  6951 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:03:02.614  6951  6951 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:03:02.614  6951  6951 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:03:02.614  6951  6951 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:03:02.615  6951  6951 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:03:02.615  6951  6951 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:03:02.615  6951  6951 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:03:02.615  6951  6951 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:03:02.618  6951  6951 V BluetoothMapService: Handler(): got msg=4
08-31 11:03:02.618  6951  6951 D BluetoothMapService: MAP Service closeService in
08-31 11:03:02.618  6951  6951 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:03:02.618  6951  6951 V BluetoothMapService: MAP Service closeService out
,08-31 11:03:02.621  6951  7492 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:03:02.621  6951  7492 D BluetoothAdapterProperties: Setting state to 10
08-31 11:03:02.621  6951  7492 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:03:02.624  6951  6951 D BluetoothMapService: cleanup()
08-31 11:03:02.624  6951  6951 D BluetoothMapService: MAP Service closeService in
08-31 11:03:02.624  6951  6951 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:03:02.624  6951  6951 V BluetoothMapService: MAP Service closeService out
08-31 11:03:02.625  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:03:02.625  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 11:03:02.625  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-31 11:03:02.627  6951  7492 I BluetoothAdapterState: Entering OffState
08-31 11:03:02.627  6809  6826 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:03:02.628  1852  2448 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:03:02.628  6809  6826 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:03:02.629  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:03:02.629  6809  6826 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 11:03:02.632  6809  6826 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:03:02.634  6809  6826 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:03:02.635  1852  2716 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:03:02.636  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:03:02.636  6809  6826 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:03:02.637  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:03:02.637  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 11:03:02.638  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 11:03:02.639  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 11:03:02.639  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 11:03:02.639  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@298c683b mBinding = false
08-31 11:03:02.640  1036  1118 D BluetoothManagerService: Sending unbind request.
08-31 11:03:02.645  6951  7496 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 11:03:02.648  6951  6951 I GKI_LINUX: GKI_exit_task 1 done
08-31 11:03:02.648  6951  6951 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 11:03:02.648  6951  6951 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:03:02.648  6951  6951 I art     : --- WEIRD: removing null entry 248
08-31 11:03:02.648  6951  6951 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 11:03:02.648  6951  6951 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 11:03:02.649  6951  6951 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 11:03:02.651  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 11:03:02.653  6951  6951 I art     : System.exit called, status: 0
08-31 11:03:02.653  6951  6951 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 11:03:02.672   321   321 V AudioFlinger: 6951 died, releasing its sessions
08-31 11:03:02.672   321   321 V AudioFlinger:  pid 1852 @ 0
08-31 11:03:02.672   321   321 V AudioFlinger:  pid 3498 @ 1
08-31 11:03:02.672   321   321 V AudioFlinger:  pid 3498 @ 2
,08-31 11:03:02.676  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-31 11:03:02.676  1942  2128 D LGBluetoothAPIService: Message: 101
,08-31 11:03:02.676  1942  2128 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-31 11:03:02.676  1942  2128 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-31 11:03:02.677  1942  2128 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-31 11:03:02.678  6809  6809 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-31 11:03:02.683  1036  1052 I ActivityManager: Process com.android.bluetooth (pid 6951) has died
08-31 11:03:02.684  1036  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-31 11:03:02.684  1036  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-31 11:03:02.703  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:02.703  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-31 11:03:02.706  6809  6809 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-31 11:03:02.706  6809  6809 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 11:03:02.706  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:02.708  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:02.708  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:03:02.710  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:02.710  1942  2128 D LGBluetoothAPIService: Message: 2
08-31 11:03:02.710  1942  2128 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-31 11:03:02.713  1602  1602 D BluetoothAdapter: 809742892: getState() :  mService = null. Returning STATE_OFF
08-31 11:03:02.713  1602  1602 D BluetoothAdapter: 809742892: getState() :  mService = null. Returning STATE_OFF
08-31 11:03:02.762  1036  1936 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7869 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-31 11:03:02.764  6809  6809 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:03:02.825  7869  7869 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 11:03:02.826  7869  7869 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:03:02.826  7869  7869 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 11:03:02.827  7869  7869 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 11:03:02.849  7869  7869 D BluetoothAdapterApp: Loading JNI Library
,08-31 11:03:02.884  7869  7869 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2532065a Instance Count = 1
,08-31 11:03:02.890  7869  7869 D BluetoothAdapterApp: onCreate
08-31 11:03:02.913  7869  7869 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 11:03:02.913  7869  7869 D ProfileConfigQcom: Adding HeadsetService
,08-31 11:03:02.913  7869  7869 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 11:03:02.914  7869  7869 D ProfileConfigQcom: Adding A2dpService
08-31 11:03:02.914  7869  7869 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 11:03:02.914  7869  7869 D ProfileConfigQcom: Adding HidService
08-31 11:03:02.914  7869  7869 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 11:03:02.914  7869  7869 D ProfileConfigQcom: Adding HealthService
08-31 11:03:02.915  7869  7869 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 11:03:02.916  7869  7869 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 11:03:02.916  7869  7869 D ProfileConfigQcom: Adding PanService
08-31 11:03:02.916  7869  7869 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 11:03:02.916  7869  7869 D ProfileConfigQcom: Adding GattService
08-31 11:03:02.917  7869  7869 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 11:03:02.917  7869  7869 D ProfileConfigQcom: Adding BluetoothMapService
08-31 11:03:02.917  7869  7869 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 11:03:02.918  7869  7869 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:03:02.919  7869  7869 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:02.919  7869  7869 V BluetoothPbapReceiver: ***********state = 10
08-31 11:03:02.922  7869  7869 V LGMDMManagerInternal: Create singleton instance
08-31 11:03:02.988  7869  7869 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 11:03:02.988  7869  7869 D LGBluetoothAPIServer: [BTUI] onBind()
,08-31 11:03:02.993  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 11:03:02.994  1942  2128 D LGBluetoothAPIService: Message: 100
08-31 11:03:02.994  1942  2128 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 11:03:02.996  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:03:03.004  6809  6809 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 11:03:03.019  6809  6809 D BluetoothPermissionRequest: onReceive
,08-31 11:03:03.023  6809  6809 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:03:03.023  6809  6809 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 11:03:03.026  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:03:03.033  7869  7869 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-31 11:03:03.038  7869  7869 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:03.042  7869  7869 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:03:03.042  7869  7869 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:03:03.043  7869  7869 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:03:03.044  7869  7869 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:03.044  7869  7869 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-31 11:03:03.056  7562  7562 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 11:03:06.688  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:03:06.688  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:06.702  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:06.702  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2567159d removed from the list
08-31 11:03:06.702  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:06.702  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:06.702  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:06.704  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:06.704  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@157e65e3 added. We now have 4 listener(s)
08-31 11:03:06.704  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:06.705  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:06.705  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@157e65e3 removed from the list
08-31 11:03:06.705  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:06.705  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:06.705  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:06.706  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:06.706  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a6ebbe0 added. We now have 4 listener(s)
08-31 11:03:06.706  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:06.708  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:06.709  1036  1936 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-31 11:03:06.711  1036  1118 D BluetoothManagerService: Message: 2
,08-31 11:03:07.323  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{8a42d96 type 2 when 182926 com.google.android.gms} when 182926
,08-31 11:03:07.330   316  7900 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-31 11:03:07.335  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 11:03:11.718  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:11.729  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:11.729  1036  1052 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 11:03:11.752  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:03:11.752  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:03:11.752  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-31 11:03:11.753  1036  1118 D BluetoothManagerService: Message: 1
08-31 11:03:11.753  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 11:03:11.778  1036  1118 D BluetoothManagerService: Message: 20
08-31 11:03:11.778  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26f1a3b3:true
,08-31 11:03:11.782  7869  7869 D BluetoothAdapterState: make
08-31 11:03:11.787  7869  7869 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 11:03:11.787  7869  7869 I bluedroid-qcom: init
08-31 11:03:11.788  7869  7903 I BluetoothAdapterState: Entering OffState
08-31 11:03:11.789  7869  7869 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 11:03:11.789  7869  7869 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:03:11.789  7869  7869 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:03:11.789  7869  7869 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:03:11.789  7869  7869 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 11:03:11.791  7869  7869 I bluedroid-qcom: get_profile_interface socket
08-31 11:03:11.791  7869  7869 I bluedroid-qcom: get_profile_interface map_client
,08-31 11:03:11.796  7869  7907 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 11:03:11.789  7906  7906 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:11.799  7906  7906 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:11.809  7906  7906 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 11:03:11.809  7906  7906 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 11:03:11.809  7906  7906 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 11:03:11.815  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 11:03:11.815  1036  1118 D BluetoothManagerService: Message: 40
08-31 11:03:11.815  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 11:03:11.816  7869  7884 I bluedroid-qcom: config_hci_snoop_log
08-31 11:03:11.817  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 11:03:11.817  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 11:03:11.819  7869  7907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 11:03:11.819  7906  7906 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 11:03:11.822  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:03:11.822  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:03:11.824  7869  7907 D BluetoothAdapterProperties: Name is: G3
,08-31 11:03:11.827  7906  7906 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 11:03:11.827  7906  7906 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 11:03:11.833  7869  7903 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 11:03:11.833  7869  7903 D BluetoothAdapterProperties: Setting state to 11
08-31 11:03:11.833  7869  7903 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:03:11.835  7869  7903 I LGBluetoothServiceJni: classInitNative: succeeds
,08-31 11:03:11.841  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:03:11.841  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 11:03:11.841  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 11:03:11.845  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:11.845  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:03:11.849  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:11.851  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:11.855  6809  6809 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 11:03:11.861  7869  7869 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:03:11.862  7869  7869 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:11.862  7869  7869 V BluetoothPbapReceiver: ***********state = 11
08-31 11:03:11.866  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:03:11.889  7869  7903 D BluetoothBondStateMachine: make
,08-31 11:03:11.894  7869  7903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:11.894  7869  7903 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 11:03:11.894  7869  7903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:11.894  7869  7903 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 11:03:11.895  7869  7903 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 11:03:11.895  7869  7921 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 11:03:11.899  7869  7903 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:03:11.908  7869  7903 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:03:11.910  6809  6809 D BluetoothPermissionRequest: onReceive
08-31 11:03:11.911  7869  7869 D HeadsetService: Received start request. Starting profile...
08-31 11:03:11.912  7869  7869 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:03:11.912  7869  7869 D LGBluetoothHfpAdapter: Version 1.6
08-31 11:03:11.915  7869  7869 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:03:11.915  7869  7903 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:03:11.916  7869  7869 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:03:11.917  7869  7869 D HeadsetStateMachine: make
08-31 11:03:11.919  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:03:11.924  7869  7903 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:03:11.929  7869  7903 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:03:11.934  7869  7903 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:03:11.938  7869  7903 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:03:11.953  7869  7903 V LGMDMManager: Create singleton instance
,08-31 11:03:11.957  7869  7869 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:03:11.957  7869  7869 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:03:11.958  7869  7903 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 11:03:11.962  7869  7869 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:03:11.962  7869  7869 I bluedroid-qcom: get_profile_interface handsfree
08-31 11:03:11.964  7869  7869 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 11:03:11.965   321  1397 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 1002
08-31 11:03:11.966   321   321 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:03:11.966   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:03:11.966   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
,08-31 11:03:11.967  7869  7869 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:03:11.967   321  2158 V AudioFlinger: registerClient() client 0xb5581640, pid 7869
08-31 11:03:11.968   321  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:03:11.968   321  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-31 11:03:11.968  7869  7869 V ToneGenerator: Create Track: 0xb4928a80
08-31 11:03:11.968  7869  7869 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 11:03:11.968  7869  7869 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 11:03:11.968   321  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:03:11.968  1852  2716 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:03:11.968   321  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:03:11.968  1852  2716 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:03:11.968   321  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:03:11.968   321  2157 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:03:11.968   321  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:03:11.968   321  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:03:11.968  1036  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:03:11.968  1036  1995 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:03:11.968  1036  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:03:11.968  1036  1995 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:03:11.968  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:03:11.969  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:03:11.969  7869  7869 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:03:11.969  7869  7884 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:03:11.969  7869  7884 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 11:03:11.969  7869  7884 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:03:11.969  7869  7884 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 11:03:11.969  3498  3514 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:03:11.969  1602  2101 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:03:11.969  3498  3514 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:03:11.969  1602  2101 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:03:11.969  3498  3514 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:03:11.969  3498  3514 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:03:11.969  1602  2101 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:03:11.969  1602  2101 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:03:11.969   321  1396 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:03:11.970   321   321 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:03:11.970   321   321 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 11:03:11.970   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:03:11.970   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:03:11.970  7869  7869 V AudioSystem: getLatency() output 2, latency 50
08-31 11:03:11.970  7869  7869 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 11:03:11.970  7869  7869 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 11:03:11.970   321  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:03:11.970   321  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:03:11.970   321  2157 V AudioFlinger: [MABL_A,udioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:03:11.970   321  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:03:11.970   321  2157 V AudioFlinger: createTrack() lSessionId: 21
08-31 11:03:11.972  7869  7869 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 11:03:11.972   321  2157 V AudioFlinger: acquiring 21 from 7869, for 7869
08-31 11:03:11.972   321  2157 V AudioFlinger:  added new entry for 21
08-31 11:03:11.972  7869  7869 V ToneGenerator: ToneGenerator INIT OK, time: 187601
08-31 11:03:11.972  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:11.973  7869  7925 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 11:03:11.973  7869  7925 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:03:11.973  7869  7925 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:03:11.973  7869  7925 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 11:03:11.974   321  1397 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7869
08-31 11:03:11.974  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:11.974   321  1397 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 11:03:11.974   321  1397 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 11:03:11.974   321  1397 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 11:03:11.974   321  1397 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 11:03:11.974   321  1397 V voice   : voice_set_parameters: exit with code(0)
08-31 11:03:11.974   321  1397 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 11:03:11.974   321  1397 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 11:03:11.974   321  1397 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 11:03:11.974   321  1397 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 11:03:11.974   321  1397 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 11:03:11.974   321  1397 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 11:03:11.975  7869  7925 V ToneGenerator: ToneGenerator destructor
08-31 11:03:11.975  7869  7925 V ToneGenerator: stopTone
08-31 11:03:11.975  7869  7925 V ToneGenerator: Delete Track: 0xb4928a80
08-31 11:03:11.976  7869  7869 D A2dpService: Received start request. Starting profile...
08-31 11:03:11.976   321  1396 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 11:03:11.976   321  1396 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 11:03:11.976   321  1274 V AudioPolicyService: AudioCommandThread() waking up
08-31 11:03:11.976   321  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 11:03:11.976   321  1274 V AudioPolicyManager: releaseOutput() 2
08-31 11:03:11.976   321  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 11:03:11.976   321  1396 V AudioFlinger: PlaybackThread::Track destructor
08-31 11:03:11.976   321  1396 V AudioFlinger: removeClient_l() pid 7869, calling pid 321
08-31 11:03:11.976  7869  7925 V AudioTrack: ~AudioTrack, releasing session id from 7869 on behalf of 7869
08-31 11:03:11.976   321  2157 V AudioFlinger: releasing 21 from 7869 for 7869
,08-31 11:03:11.976   321  2157 V AudioFlinger:  decremented refcount to 0
08-31 11:03:11.976   321  2157 V AudioFlinger: purging stale effects
08-31 11:03:11.977  7869  7869 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:03:11.978  7869  7869 V Avrcp   : make
,08-31 11:03:11.979  1036  1574 W Process : Unable to open /proc/7927/status
08-31 11:03:11.979  7869  7869 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-31 11:03:11.979  7869  7869 I bluedroid-qcom: get_profile_interface avrcp
08-31 11:03:11.988  7869  7869 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 11:03:11.990  7869  7869 E AudioManager: No RCC entry present to update
08-31 11:03:11.990  7869  7869 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:03:11.994  7869  7869 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-31 11:03:11.995  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 11:03:11.995  7869  7869 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 11:03:12.000  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:03:12.110  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:03:12.110  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:03:12.185  1036  1758 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 11:03:12.191  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 11:03:12.195  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:03:12.196  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:03:12.196  7869  7869 I BluetoothA2dpServiceJni: classInitNative
08-31 11:03:12.197  7869  7869 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:03:12.197  7869  7869 D A2dpStateMachine: make
08-31 11:03:12.199  7869  7869 I bluedroid-qcom: get_profile_interface a2dp
08-31 11:03:12.200  7869  7934 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-31 11:03:12.202  7869  7869 I LGBluetoothA2dpServiceJni: classInitNative: succeeds,
08-31 11:03:12.202  7869  7869 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 11:03:12.202  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:12.203  7869  7933 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:03:12.203  7869  7869 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 11:03:12.205  7869  7869 D HidService: Received start request. Starting profile...
08-31 11:03:12.205  7869  7869 I bluedroid-qcom: get_profile_interface hidhost
08-31 11:03:12.205  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:12.205  7869  7869 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:03:12.207  7869  7869 D HealthService: Received start request. Starting profile...
08-31 11:03:12.211  7869  7869 I bluedroid-qcom: get_profile_interface health
08-31 11:03:12.211  7869  7869 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:03:12.211  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:12.212  7869  7869 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 11:03:12.213  7869  7869 D PanService: Received start request. Starting profile...
08-31 11:03:12.214  7869  7869 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 11:03:12.214  7869  7869 I bluedroid-qcom: get_profile_interface pan
08-31 11:03:12.223  7869  7869 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 11:03:12.224  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:12.225  7869  7869 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 11:03:12.229  7869  7869 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:03:12.229  7869  7869 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:03:12.230  7869  7869 D BtGatt.GattService: start()
08-31 11:03:12.230  7869  7869 I bluedroid-qcom: get_profile_interface gatt
08-31 11:03:12.230  7869  7869 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:03:12.241  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
,08-31 11:03:12.242  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:12.243  7869  7869 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 11:03:12.243  7869  7869 V BluetoothMapService: BluetoothMapBinder()
08-31 11:03:12.244  7869  7869 D BluetoothMapService: Received start request. Starting profile...
08-31 11:03:12.244  7869  7869 D BluetoothMapService: start()
08-31 11:03:12.248  7869  7869 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 11:03:12.248  7869  7869 D BluetoothMapEmailAppObserver: createReceiver()
08-31 11:03:12.249  7869  7869 D BluetoothMapEmailAppObserver: initObservers()
08-31 11:03:12.249  7869  7869 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 11:03:12.258  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:12.259  7869  7869 D HeadsetStateMachine: Proxy object connected
08-31 11:03:12.260  7869  7869 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 11:03:12.260  7869  7869 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-31 11:03:12.266  7869  7869 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:03:12.267  7869  7925 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 11:03:12.267  7869  7925 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:03:12.268  7869  7925 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 11:03:12.275  7869  7869 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 11:03:12.280  7869  7869 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:03:12.284  7869  7869 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:12.293  7869  7869 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 11:03:12.300  7869  7869 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:03:12.300  7869  7869 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 11:03:12.304  7869  7869 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 11:03:12.305  7869  7869 V BluetoothMapService: Handler(): got msg=1
08-31 11:03:12.306  7869  7869 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:03:12.306  7869  7869 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:03:12.306  7869  7869 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:03:12.306  7869  7869 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:12.306  7869  7903 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:03:12.306  7869  7869 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 11:03:12.306  7869  7903 I bluedroid-qcom: enable
08-31 11:03:12.307  7869  7903 I bt_hci_bdroid: init
,08-31 11:03:12.310  7869  7903 I bt_vendor: bt-vendor : init
08-31 11:03:12.310  7869  7903 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:03:12.311  7869  7942 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 11:03:12.311  7869  7942 I bt-btu  : btu_task pending for preload complete event
08-31 11:03:12.311  7869  7903 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:03:12.311  7869  7903 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 11:03:12.311  7869  7903 D bt_userial_mct: userial_init
08-31 11:03:12.313  7869  7903 D bt_hci_bdroid: set_power 1
08-31 11:03:12.313  7869  7903 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 11:03:12.313  7869  7903 I bt_vendor: Starting hciattach daemon
08-31 11:03:12.313  7869  7903 I bt_vendor: try to set true
08-31 11:03:12.308  7945  7945 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:12.308  7945  7945 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:12.344  7946  7946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 11:03:12.433  7952  7952 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 11:03:12.448  7953  7953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:03:12.478  7955  7955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:03:12.492  7956  7956 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 11:03:12.507  7957  7957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:03:12.523  7958  7958 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 11:03:12.559  7960  7960 I libmdmdetect: ESOC framework not supported
,08-31 11:03:12.560  7960  7960 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 11:03:12.568  7960  7960 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 11:03:12.568  7960  7960 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 11:03:12.568  7960  7960 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 11:03:12.568  7960  7960 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 11:03:12.568  7960  7960 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 11:03:12.568  7960  7960 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 11:03:12.569  7960  7960 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 11:03:12.608  7960  7961 E QC-QMI  : qmi_client [7960] 15: failed to locate client data
,08-31 11:03:12.609   489   489 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 11:03:12.609   489   489 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-31 11:03:12.722  7965  7965 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 11:03:12.738  7966  7966 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:03:12.767  7869  7903 I bt_vendor: bluetooth satus is on
,08-31 11:03:12.767  7869  7903 D bt_hci_bdroid: preload
08-31 11:03:12.767  7869  7944 D bt_userial_mct: userial_open(port:0)
08-31 11:03:12.767  7869  7944 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 11:03:12.771  7869  7944 I bt_vendor: Done intiailizing UART
08-31 11:03:12.774  7869  7944 I bt_vendor: Done intiailizing UART
08-31 11:03:12.774  7869  7944 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 11:03:12.774  7869  7944 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 11:03:12.774  7869  7942 I bt-btu  : btu_task received preload complete event
08-31 11:03:12.775  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 11:03:12.776  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 11:03:12.779  7869  7968 D bt_userial_mct: Entering userial_read_thread()
08-31 11:03:12.782  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_PAN,
08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 11:03:12.788  7869  7942 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 11:03:12.896  7869  7942 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-31 11:03:12.897  7869  7942 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01fa061 
08-31 11:03:12.897  7869  7942 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01fa061 
,08-31 11:03:12.952  7869  7907 E bt-btif : Calling BTA_HhEnable
,08-31 11:03:12.953  7869  7907 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-31 11:03:12.953  7869  7907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 11:03:12.963  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 11:03:12.963  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 11:03:12.963  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 11:03:12.963  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 11:03:12.964  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 11:03:12.968  7869  7907 D BluetoothAdapterProperties: Name is: G3
08-31 11:03:12.972  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:03:12.973  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 11:03:12.976  7869  7907 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:03:12.977  7869  7907 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:03:12.977  7869  7907 D bt_hci_bdroid: postload
08-31 11:03:12.977  7869  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:03:12.978  7869  7907 D bte_conf: Device ID record 1 : primary
08-31 11:03:12.978  7869  7907 D bte_conf:   vendorId            = 00c4
08-31 11:03:12.978  7869  7907 D bte_conf:   vendorIdSource      = 0001
08-31 11:03:12.978  7869  7907 D bte_conf:   product             = 13a1
08-31 11:03:12.978  7869  7907 D bte_conf:   version             = 1000
08-31 11:03:12.978  7869  7907 D bte_conf:   clientExecutableURL = 
08-31 11:03:12.978  7869  7907 D bte_conf:   serviceDescription  = 
08-31 11:03:12.978  7869  7907 D bte_conf:   documentationURL    = 
08-31 11:03:12.978  7869  7907 D bte_conf: bte_load_did_conf no section named DID2.
08-31 11:03:12.979  7869  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 11:03:12.982  7869  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:03:12.982  7869  7942 W bt-smp  : Plain text(LSB ~ MSB) = 61 fe 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:03:12.982  7869  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 3f e8 7e a5 c6 4c 4e 76 f8 1d 6d 98 52 07 4c 
08-31 11:03:12.982  7869  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:03:12.982  7869  7942 W bt-btm  : Stopping oneshot timer
08-31 11:03:12.983  7869  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:03:12.983  7869  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:03:12.984  7869  7903 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:03:12.984  7869  7903 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:03:12.984  7869  7903 D BluetoothAdapterProperties: State =  11
08-31 11:03:12.984  7869  7903 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 11:03:12.985  7869  7903 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 11:03:12.985  7869  7903 D BluetoothAdapterProperties: Setting state to 12
08-31 11:03:12.985  7869  7903 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:03:12.989  7869  7907 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:03:12.988  7973  7973 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:12.988  7973  7973 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:12.994  1036  1118 D BluetoothManagerService: Message: 60
08-31 11:03:12.994  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 11:03:12.994  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-31 11:03:12.995  7869  7903 I BluetoothAdapterState: Entering On State
08-31 11:03:13.002  7869  7968 E bt_mct  : hci lib postload completed
,08-31 11:03:13.006  7869  7903 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 11:03:13.007  7869  7903 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 11:03:13.007  7869  7903 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 11:03:13.007  7869  7903 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 11:03:12.989  7869  7907 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:03:13.026  7869  7907 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:03:13.027  7869  7907 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 11:03:13.036  7869  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:03:13.036  7869  7942 W bt-smp  : Plain text(LSB ~ MSB) = ec 21 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:03:13.036  7869  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 a6 7a 2b 02 0e a2 d1 44 1b 45 4c d5 65 27 34 
08-31 11:03:13.037  7869  7942 W bt-btm  : Stopping oneshot timer
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:13.040  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:03:13.048  7869  7903 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 11:03:13.051  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:03:13.059  7869  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:03:13.059  7869  7942 W bt-smp  : Plain text(LSB ~ MSB) = 89 75 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:03:13.059  7869  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 08 b0 19 32 59 61 b3 0c 40 de da c5 51 4b a2 a5 
08-31 11:03:13.060  7869  7942 W bt-btm  : Stopping oneshot timer
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:13.065  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:03:13.071  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:03:13.073  7869  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:03:13.073  7869  7942 W bt-smp  : Plain text(LSB ~ MSB) = 50 8f 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:03:13.073  7869  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = eb 5e af 26 26 ea a2 61 b5 0f b7 fb d9 00 2b 61 
08-31 11:03:13.073  7869  7942 W bt-btm  : Stopping oneshot timer
08-31 11:03:13.098  7869  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:03:13.098  7869  7942 W bt-smp  : Plain text(LSB ~ MSB) = a9 a3 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:03:13.098  7869  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = ea 75 b8 a0 24 e6 8f 27 f8 5a 3d c8 3f 24 76 8e 
08-31 11:03:13.098  7869  7942 W bt-btm  : Stopping oneshot timer
,08-31 11:03:13.109  6809  6826 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:03:13.114  1852  3982 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:03:13.120  6809  6825 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:03:13.120  1852  1852 D BluetoothHeadset: Proxy object connected
08-31 11:03:13.123  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:03:13.123  6809  6809 D BluetoothHeadset: Proxy object connected
08-31 11:03:13.123  6809  6809 D HeadsetProfile: Bluetooth service connected
08-31 11:03:13.124  1036  1036 D BluetoothHeadset: Proxy object connected
08-31 11:03:13.125  7978  7978 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 11:03:13.126  6809  6826 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:03:13.130  6809  6826 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:03:13.130  6809  6809 D BluetoothInputDevice: Proxy object connected
08-31 11:03:13.130  6809  6809 D HidProfile: Bluetooth service connected
08-31 11:03:13.134  6809  6825 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:03:13.134  6809  6809 D BluetoothMap: Proxy object connected
08-31 11:03:13.134  6809  6809 D MapProfile: Bluetooth service connected
08-31 11:03:13.134  6809  6809 D BluetoothMap: getConnectedDevices()
,08-31 11:03:13.135  7869  7884 V BluetoothMapService: getConnectedDevices()
08-31 11:03:13.136  1852  2448 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:03:13.137  6809  6809 D BluetoothA2dp: Proxy object connected
08-31 11:03:13.137  6809  6809 D A2dpProfile: Bluetooth service connected
08-31 11:03:13.138  1852  1852 D BluetoothHeadset: Proxy object connected
08-31 11:03:13.138  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:03:13.139  1036  1036 D BluetoothA2dp: Proxy object connected
08-31 11:03:13.139  6809  6826 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:03:13.139  6809  6826 D BluetoothPan: onBluetoothStateChange call bindService
,08-31 11:03:13.143  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:03:13.143  6809  6809 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:03:13.143  6809  6809 D PanProfile: Bluetooth service connected
08-31 11:03:13.145  1852  1852 D BluetoothHeadset: Proxy object connected
,08-31 11:03:13.145  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 11:03:13.146  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 11:03:13.146  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 11:03:13.147  1036  1118 D BluetoothManagerService: Message: 40
08-31 11:03:13.147  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 11:03:13.149  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:03:13.150  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.150  1942  2128 D LGBluetoothAPIService: Message: 1
08-31 11:03:13.150  1942  2128 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 11:03:13.150  1942  2128 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-31 11:03:13.151  1942  2128 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 11:03:13.155  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:13.156  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:13.265  1036  2033 I art     : Explicit concurrent mark sweep GC freed 28852(1428KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.537ms total 101.518ms
,08-31 11:03:13.268  6809  6809 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 11:03:13.269  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:03:13.270  7869  7869 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.270  7869  7869 D BluetoothMapService: STATE_ON
08-31 11:03:13.279  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:13.279  7869  7869 V BluetoothPbapService: Pbap Service onCreate
08-31 11:03:13.279  7869  7869 V BluetoothPbapService: Starting PBAP service
,08-31 11:03:13.280  7869  7869 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 11:03:13.280  7869  7869 V BluetoothPbapService: Pbap Service onBind
08-31 11:03:13.281  7869  7869 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.281  7869  7869 V BluetoothPbapService: state: 12
08-31 11:03:13.281  7869  7869 V BluetoothMapService: Handler(): got msg=1
08-31 11:03:13.282  7869  7869 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 11:03:13.282  7869  7869 V BluetoothPbapService: Handler(): got msg=1
08-31 11:03:13.282  7869  7869 V BluetoothPbapService: Pbap Service startRfcommSocketListener,
08-31 11:03:13.283  7869  7869 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:03:13.283  7869  7869 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.283  7869  7869 V BluetoothPbapReceiver: ***********state = 12
08-31 11:03:13.285  7869  7998 V BluetoothPbapService: Pbap Service initSocket
08-31 11:03:13.286  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:03:13.287  2169  2169 D c       : Getting all permits...
08-31 11:03:13.287  2169  2169 D a       : Opening database...
08-31 11:03:13.287  7869  7997 D BluetoothMapMasInstance: MAS initSocket()
08-31 11:03:13.288  7869  7997 D BluetoothMapMasInstance:   masId = 00
08-31 11:03:13.288  7869  7997 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 11:03:13.288  7869  7997 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 11:03:13.288  7869  7997 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 11:03:13.288  6809  6809 D DockEventReceiver: finishStartingService: stopping service
08-31 11:03:13.289  6809  6809 D BluetoothPbap: Proxy object connected
08-31 11:03:13.289  6809  6809 D PbapServerProfile: Bluetooth service connected
08-31 11:03:13.296  1036  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:13.296  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:13.297  7869  7997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:03:13.298  7869  7998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:03:13.300  7869  7997 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 11:03:13.301  7869  7997 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 11:03:13.301  7869  7997 D BluetoothMapMasInstance: Accepting socket connection...
,08-31 11:03:13.301  7869  7998 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 11:03:13.301  7869  7998 V BluetoothPbapService: Succeed to create listening socket 
08-31 11:03:13.301  7869  7998 V BluetoothPbapService: Accepting socket connection...
08-31 11:03:13.302  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-31 11:03:13.303  7869  7907 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:03:13.303  7869  7907 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-31 11:03:13.305  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:13.307  2169  2169 D a       : Closing database...
08-31 11:03:13.307  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:13.316  6809  6809 D BluetoothPermissionRequest: onReceive
08-31 11:03:13.319  6809  6809 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:03:13.320  6809  6809 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 11:03:13.322  7869  7869 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 11:03:13.323  7869  7869 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 11:03:13.328  7869  7869 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 11:03:13.338  7869  7869 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:03:13.338  7869  7869 V BtOppService: onCreate
,08-31 11:03:13.342  7869  7869 V BluetoothOppNotification: send message
,08-31 11:03:13.345  7869  7869 V BtOppService: Starting RfcommListener
08-31 11:03:13.348  7869  8004 V BtOppService: Deleted complete outbound shares, number =  0
08-31 11:03:13.349  7869  8004 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 11:03:13.349  7869  8004 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 11:03:13.350  7869  7869 D BluetoothOppPreference: Dumping Names:  
08-31 11:03:13.350  7869  7869 D BluetoothOppPreference: {}
08-31 11:03:13.350  7869  7869 D BluetoothOppPreference: Dumping Channels:  
08-31 11:03:13.350  7869  7869 D BluetoothOppPreference: {}
08-31 11:03:13.350  7869  8004 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3595ae0e on behalf of 
08-31 11:03:13.351  7869  7869 V BtOppService: onStartCommand
08-31 11:03:13.352  7869  8007 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-31 11:03:13.354  7869  7869 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.354  7869  7869 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:03:13.357  7869  7869 V BluetoothOppNotification: new notify threadi!
08-31 11:03:13.357  7869  8007 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:03:13.358  7869  7869 V BluetoothOppNotification: send delay message
08-31 11:03:13.358  7869  7869 V BtOppService: start RfcommListener
08-31 11:03:13.361  7869  8008 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:03:13.361  7869  7869 V BtOppService: RfcommListener started
08-31 11:03:13.361  7869  7869 V BtOppService: ContentObserver received notification
08-31 11:03:13.361  7869  7869 V BtOppService: ContentObserver received notification
08-31 11:03:13.362  7869  8009 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 11:03:13.363  1036  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:13.364  7869  8009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:03:13.366  7869  8008 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19d0e63c on behalf of 
08-31 11:03:13.368  7869  8008 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 11:03:13.368  7869  8009 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-31 11:03:13.369  7869  8009 V BtOppRfcommListener: Started RFCOMM listener....
08-31 11:03:13.369  7869  8009 I BtOppRfcommListener: Accept thread started.
08-31 11:03:13.369  7869  8009 V BtOppRfcommListener: Accepting connection...
08-31 11:03:13.371  7869  8007 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32807fc5 on behalf of 
08-31 11:03:13.373  7869  8008 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:03:13.373  7869  8007 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:03:13.373  7869  8007 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:03:13.375  7869  8008 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f029d1a on behalf of 
08-31 11:03:13.376  7869  8007 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c17004b on behalf of 
,08-31 11:03:13.377  7869  8007 V BluetoothOppNotification: update too frequent, put in queue
08-31 11:03:13.378  7869  8008 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:03:13.378  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:13.378  7869  7869 V BluetoothFtpService: Ftp Service onCreate
08-31 11:03:13.378  7869  7869 I BluetoothFtpService: Ftp Service onCreate
08-31 11:03:13.379  7869  7869 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:03:13.379  7869  7869 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.379  7869  7869 V BluetoothFtpService: Starting Listening on sockets
08-31 11:03:13.379  7869  7869 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:03:13.379  7869  7869 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:03:13.379  7869  7869 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:03:13.379  7869  7869 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.379  7869  7869 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 11:03:13.379  7869  7869 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:03:13.380  7869  8008 V BluetoothOppNotification: outbound notification was removed.
08-31 11:03:13.380  7869  8008 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:03:13.382  7869  7869 V BluetoothFtpService: Handler(): got msg=1
08-31 11:03:13.382  7869  8007 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:03:13.382  7869  8008 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14ee5341 on behalf of 
08-31 11:03:13.382  7869  7869 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 11:03:13.383  7869  7869 V BluetoothFtpService: Ftp Service initSocket
08-31 11:03:13.383  7869  8008 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:03:13.384  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:13.385  7869  7869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:03:13.385  7869  8008 V BluetoothOppNotification: inbound notification was removed.
08-31 11:03:13.385  7869  8008 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:03:13.387  7869  8008 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c1d70e6 on behalf of 
08-31 11:03:13.388  7869  7869 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-31 11:03:13.390  7869  7869 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-31 11:03:13.391  7869  8010 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 11:03:13.413  7869  7869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b284603
08-31 11:03:13.414  7869  7869 V BluetoothSapService: Sap Service onCreate
,08-31 11:03:13.415  7869  7869 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:03:13.415  7869  7869 V BluetoothSapService: state: 12
08-31 11:03:13.415  7869  7869 V BluetoothSapService: Starting SAP server process
08-31 11:03:13.417  7869  7869 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 11:03:13.408  8011  8011 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:13.408  8011  8011 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:13.419  7869  8012 V BluetoothSapService: Sap Service initRfcommSocket
08-31 11:03:13.419  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:13.420  7869  8012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:03:13.422  7869  8012 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 11:03:13.423  7869  8012 V BluetoothSapService: Succeed to create listening socket 
08-31 11:03:13.423  7869  8012 V BluetoothSapService: Accepting socket connection...
08-31 11:03:13.430  8011  8011 V BT_SAP  : Event pipe created
08-31 11:03:13.430  8011  8011 V BT_SAP  : create_server_socket qcom.sap.server
,08-31 11:03:13.430  8011  8011 V BT_SAP  : created socket fd 6
,08-31 11:03:14.360  7869  7869 V BluetoothOppNotification: new notify threadi!
,08-31 11:03:14.369  7869  7869 V BluetoothOppNotification: send delay message
,08-31 11:03:14.375  7869  8022 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:03:14.378  7869  8022 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18bfb572 on behalf of 
,08-31 11:03:14.388  7869  8022 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:03:14.392  7869  8022 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:03:14.393  7869  8022 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b152dc3 on behalf of 
08-31 11:03:14.394  7869  8022 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:03:14.397  7869  8022 V BluetoothOppNotification: outbound notification was removed.
08-31 11:03:14.397  7869  8022 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-31 11:03:14.399  7869  8022 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c81640 on behalf of 
,08-31 11:03:14.400  7869  8022 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:03:14.402  7869  8022 V BluetoothOppNotification: inbound notification was removed.
08-31 11:03:14.402  7869  8022 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:03:14.403  7869  8022 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8792979 on behalf of 
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:16.776  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:03:16.786  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:03:16.786  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:03:16.787  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a6ebbe0 removed from the list
08-31 11:03:16.787  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:16.787  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:16.787  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:16.788  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:16.788  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2da46e99 added. We now have 4 listener(s)
08-31 11:03:16.788  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:16.792  1036  1959 D WifiServiceImplEx: setWifiEnabled: false pid=6558, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 11:03:16.792  1036  1959 D WifiService: setWifiEnabled: false pid=6558, uid=10118
08-31 11:03:16.792  1036  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 11:03:21.803  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:21.816  1036  1891 D WifiServiceImplEx: setWifiEnabled: true pid=6558, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:03:21.817  1036  1891 D WifiService: setWifiEnabled: true pid=6558, uid=10118
08-31 11:03:21.817  1036  1891 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:03:21.837  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 11:03:21.838  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 11:03:21.838  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-31 11:03:21.839  1036  1431 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 11:03:21.839  1036  1431 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 11:03:21.842  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 11:03:21.842  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-31 11:03:21.842  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 11:03:21.842  1036  1431 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:03:21.842  1036  1431 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 11:03:21.842  1036  1431 E WifiHW  : unknown target_country: EU , set to default
08-31 11:03:21.842  1036  1431 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-31 11:03:21.842  1036  1431 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 11:03:21.842  1036  1431 I WifiUtil: gEnableBmps=1
08-31 11:03:21.947   312   312 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-31 11:03:21.948   312   312 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 11:03:21.948   312   312 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 11:03:21.948   312   899 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,08-31 11:03:22.052   312   899 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,08-31 11:03:22.052   312   899 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 11:03:22.053   312   899 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-31 11:03:22.053   312   899 I rmt_storage: 
08-31 11:03:22.056   312   312 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-31 11:03:22.057   885   906 E Diag_Lib: [IMS_FATAL]| 3347 | 906 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,08-31 11:03:22.472   316   916 D SoftapController: Softap fwReload - Ok
,08-31 11:03:22.482  1036  1431 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (636ms)
08-31 11:03:22.484   316   916 D CommandListener: Setting iface cfg
08-31 11:03:22.484   316   916 D CommandListener: Trying to bring down wlan0
08-31 11:03:22.487   316   916 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:03:22.503  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 11:03:22.523  1036  1431 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 11:03:22.518  8033  8033 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:03:22.528  8033  8033 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:03:22.591  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:03:22.591  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:03:22.591  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:03:22.596  8033  8033 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 11:03:22.600  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:03:22.603  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 11:03:22.608  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:22.609  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:22.610  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 11:03:22.610  1036  1431 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 11:03:22.610  1036  1431 D WifiMonitor: connecting to supplicant
08-31 11:03:22.612  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:03:22.613  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:03:22.613  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:03:22.613  6809  6809 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:03:22.613  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:03:22.614  6809  6809 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:03:22.614  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 11:03:22.614  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:03:22.614  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:03:22.614  6809  6809 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:03:22.614  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 11:03:22.614  6809  6809 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 11:03:22.637  8033  8033 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:03:22.637  8033  8033 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 11:03:22.640  1036  1118 D Tethering: InitialState.processMessage what=4
08-31 11:03:22.667  1036  2032 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8052 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 11:03:22.668  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:03:22.710  8033  8033 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:03:22.755  1036  1922 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8073 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:03:22.763  8052  8071 W FormManager: Network not available. Please check & try again.
08-31 11:03:22.765  8033  8033 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 11:03:22.768  8052  8072 V FormManager: Network unavailable.
08-31 11:03:22.769  8052  8072 V FormManager: Network unavailable.
,08-31 11:03:22.775  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:03:22.776  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 11:03:22.776  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:03:22.777  1036  1431 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:03:22.778  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:22.778  1036  1431 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:22.779  1036  1431 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:22.780  1036  1431 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:22.780  1036  1431 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 11:03:22.780  1036  1431 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 11:03:22.781  8033  8033 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 11:03:22.781  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 11:03:22.781  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 11:03:22.781  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:03:22.781  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:03:22.782  1036  1431 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 11:03:22.782  1036  1431 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 11:03:22.782  1036  1431 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 11:03:22.782  1036  1431 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:03:22.782  1036  1431 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:03:22.782  1036  1431 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:03:22.783  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:22.783  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:03:22.783  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:22.783  1036  1431 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 11:03:22.783  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:22.783  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:03:22.784  1036  1431 D WifiNative-wlan0: SET update_config 1: returned true
08-31 11:03:22.784  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:22.785  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-31 11:03:22.787  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 11:03:22.784  1036  1431 D WifiConfigStore: Loading config and enabling all networks 
08-31 11:03:22.787  1036  1447 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 11:03:22.787  1036  1431 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 11:03:22.788  1036  1431 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:22.791  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:03:22.791  1036  1758 I ActivityManager: Killing 7101:com.android.chrome/u0a57 (adj 15): empty #17
08-31 11:03:22.793  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:03:22.796  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:03:22.797  1036  1431 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 11:03:22.798  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:03:22.808  1036  1431 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 11:03:22.808  1036  1431 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 11:03:22.846  1036  1431 D WifiStateMachine: enableVerboseLogging : level 2
08-31 11:03:22.846  1036  1431 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 11:03:22.846  1036  1936 W libprocessgroup: failed to open /acct/uid_10057/pid_7101/cgroup.procs: No such file or directory
08-31 11:03:22.848  1036  1431 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 11:03:22.848  1036  1431 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 11:03:22.849  1036  1431 D WifiNative-wlan0: SET manufacturer LGE: returned true
,08-31 11:03:22.849  1036  1431 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 11:03:22.850  1036  1431 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 11:03:22.850  1036  1431 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 11:03:22.852  1036  1431 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 11:03:22.852  1036  1431 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 11:03:22.853  1036  1431 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 11:03:22.853  1036  1431 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 11:03:22.854  1036  1431 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 11:03:22.854  1036  1431 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 11:03:22.855  1036  1431 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 11:03:22.856  1036  1431 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:03:22.856  1036  1431 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 11:03:22.857  1036  1431 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 11:03:22.857  1036  1431 D WifiNative-HAL: Setting external_sim to 1
08-31 11:03:22.857  1036  1431 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-31 11:03:22.858  1036  1431 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 11:03:22.858  1036  1431 I WifiNative-HAL: startHal
08-31 11:03:22.858  1036  1431 D wifi    : setting scan oui 0xaf5996e0
08-31 11:03:22.859  1036  1431 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:03:22.859  1036  1431 I WifiNative-HAL: startHal
08-31 11:03:22.860  1036  1431 D wifi    : setting scan oui 0xaf5996e0
08-31 11:03:22.860  1036  1431 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 11:03:22.862  1036  1431 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 11:03:22.862  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 11:03:22.863  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 11:03:22.864  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 11:03:22.864  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:03:22.865  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:03:22.866  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:03:22.866  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 11:03:22.866  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 11:03:22.867  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 11:03:22.867  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:03:22.868  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:03:22.869  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:03:22.869  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:03:22.869  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:03:22.870  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:03:22.870  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 11:03:22.871  8033  8033 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 11:03:22.871  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 11:03:22.871  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-31 11:03:22.872  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:03:22.872  1036  1431 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:03:22.875  1036  1431 E WifiNative: : [198,489,682 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 11:03:22.875  1036  1431 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 11:03:22.876  1036  1431 D WifiNative-wlan0: RECONNECT: returned true
08-31 11:03:22.876  1036  1431 D WifiNative-wlan0: doString: [STATUS]
08-31 11:03:22.877  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:03:22.877  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 11:03:22.878  1036  1431 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:03:22.878  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:03:22.879  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:03:22.880  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.882   316   916 D CommandListener: Setting iface cfg
08-31 11:03:22.882   316   916 D CommandListener: Trying to bring up p2p0
08-31 11:03:22.882  1036  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 11:03:22.882  1036  1390 D LGWifiP2pService: P2pEnablingState
08-31 11:03:22.882  1036  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.882  1036  1431 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:03:22.882  1036  1390 D LGWifiP2pService: P2p socket connection successful
08-31 11:03:22.882  1036  1390 D LGWifiP2pService: P2pEnabledState
08-31 11:03:22.883  1036  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 11:03:22.883  1036  1431 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 11:03:22.883  1036  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 11:03:22.884  1036  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 11:03:22.884  1036  1431 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 11:03:22.884  1036  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 11:03:22.884  1036  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-31 11:03:22.884  1036  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 11:03:22.884  1036  1390 D LGWifiP2pService: before postfix = G3
08-31 11:03:22.884  1036  1390 D WifiServerServiceExt: postfix byte check : 2
08-31 11:03:22.884  1036  1390 D LGWifiP2pService: after postfix = G3
08-31 11:03:22.884  1036  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 11:03:22.885  1036  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 11:03:22.885  1036  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 11:03:22.885  1036  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 11:03:22.885  1036  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 11:03:22.885  1036  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 11:03:22.885  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 11:03:22.886  1036  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 11:03:22.886  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-31 11:03:22.886  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 11:03:22.886  1036  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 11:03:22.886  1036  1390 D WifiNative-p2p0: doBoolean: P2,P_FLUSH
08-31 11:03:22.888  1036  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 11:03:22.888  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 11:03:22.888  1036  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 11:03:22.888  1036  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,08-31 11:03:22.889  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-31 11:03:22.889  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:03:22.889  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-31 11:03:22.889  1942  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 11:03:22.889  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.889  1036  1555 I WifiNative-HAL: startHal
08-31 11:03:22.889  1942  2273 D WfdsService: Set the WFDS Monitor: true
08-31 11:03:22.889  1942  2273 D WfdsMonitor: WfdsMonitorThread create
08-31 11:03:22.889  1036  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.890  1942  2273 D WfdsMonitor: WFDS Monitor is created and started
08-31 11:03:22.890  1942  2273 D WfdsService: WiFi: Supplicant connection re-established
08-31 11:03:22.890  1036  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 11:03:22.890  1036  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 11:03:22.890  1036  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf5996e0
08-31 11:03:22.890  1036  1555 D wifi    : failed to get capabilities : -3
08-31 11:03:22.890  1036  1555 E WifiScanningService: could not get scan capabilities
08-31 11:03:22.891  1036  1431 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 11:03:22.891  7665  7665 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:22.891  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 11:03:22.891  1942  1942 D WfdsService: WifiP2pState is changed : true
08-31 11:03:22.892  1942  2273 D WfdsService: Receive the WFDS_ENABLE Method
08-31 11:03:22.892  1942  2273 D WfdsService: Set the WFDS Monitor: true
08-31 11:03:22.892  1942  2273 D WfdsService: Connected to the supplicant for wfds
08-31 11:03:22.892  1942  2273 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 11:03:22.892  1942  2273 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
08-31 11:03:22.892  1942  2273 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
08-31 11:03:22.892  1942  2273 D WfdsService: selectPreferredScanChannel [36]
08-31 11:03:22.892  1942  2273 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 11:03:22.892  1036  1431 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 11:03:22.892  1036  1431 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 11:03:22.892  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 11:03:22.893  1942  1942 D WfdsService: isConnected: false
08-31 11:03:22.893  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 11:03:22.893  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 11:03:22.893  1942  1942 D WfdsService: Update P2p Interface State: 3
08-31 11:03:22.894  1942  8092 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 11:03:22.894  1942  8092 E CtrlSupplicant: Succeed to open control connection
08-31 11:03:22.894  1942  8092 E CtrlSupplicant: Succeed to open monitor connection
08-31 11:03:22.894  1036  1431 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 11:03:22.895  1036  1431 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 11:03:22.899  8033  8033 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 11:03:22.900  1942  8092 D WfdsMonitor: Supplicant connection established
08-31 11:03:22.900  1036  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 11:03:22.900  1036  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:03:22.900  1036  1390 D LGWifiP2pService: InactiveState
08-31 11:03:22.900  1036  1390 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.u,til.StateMachine$SmHandler }
08-31 11:03:22.900  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.900  1036  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 11:03:22.901  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:03:22.902  8033  8033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.902  1942  8092 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:03:22.902  8033  8033 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:03:22.902  8033  8033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 11:03:22.903  1942  8092 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.903  8033  8033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.903  1942  8092 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.903  1036  8089 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:03:22.903  1036  8089 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.903  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.903  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.903  1036  8089 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.903  1036  8089 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.904  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.904  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.904  1036  8089 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.904  1036  8089 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.904  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.904  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.904  1942  2273 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-31 11:03:22.904  1036  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 11:03:22.904  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.904  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.904  1036  1390 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.905  1036  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.905  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.905  1036  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.905  1036  1036 E WifiServerServiceExt: No p2p device connected
08-31 11:03:22.905  1036  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.905  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.905  1036  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.906  1036  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.906  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.906  1036  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.906  1942  2273 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 11:03:22.907  1036  1431 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 11,:03:22.907  1036  1431 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 11:03:22.907  1036  1431 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 11:03:22.908  1036  1431 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 11:03:22.908  8033  8033 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 11:03:22.908  1036  1431 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 11:03:22.909  1036  1431 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 11:03:22.909  1036  1431 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 11:03:22.909  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 11:03:22.910  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:03:22.910  8033  8033 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.910  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:03:22.911  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.911  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.911  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:03:22.911  8033  8033 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:03:22.911  8033  8033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.911  1942  8092 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.912  8033  8033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.912  1036  8089 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.912  1036  8089 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.912  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.912  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.912  1036  8089 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.912  1036  8089 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.912  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.913  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:03:22.913  1036  1431 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 11:03:22.913  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.913  1942  8092 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:03:22.913  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:22.913  8073  8073 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:03:22.913  1036  1431 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:03:22.914  1036  1431 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:03:22.914  1036  1431 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:03:22.914  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-31 11:03:22.914  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 11:03:22.914  8033  8033 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:03:22.914  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 11:03:22.914  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:03:22.914  1036  8089 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:03:22.914  1036  8089 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:03:22.915  1036  1431 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 11:03:22.915  1036  1431 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 11:03:22.915  1036  1431 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 11:03:22.915  1036  1431 D WifiNative-wlan0: doBoolean: SCAN
08-31 11:03:22.915  1036  1431 D WifiNative-wlan0: SCAN: returned false
08-31 11:03:22.916  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198532  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:03:22.917  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:03:22.920  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:22.920  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:22.921  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:22.921  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:03:22.922  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:22.922  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:03:22.922  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198539  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-31 11:03:22.923  1036  1431 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:03:22.923  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:22.923  1036  1431 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:03:22.923  1036  1431 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:03:22.924  1036  1431 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:03:22.924  1036  2032 I ActivityManager: Killing 7124:com.lge.drmservice/u0a62 (adj 15): empty #17
08-31 11:03:22.924  1036  1431 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:03:22.954  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:03:22.954  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-31 11:03:22.954  1036  1995 W libprocessgroup: failed to open /acct/uid_10062/pid_7124/cgroup.procs: No such file or directory
08-31 11:03:22.964  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:03:22.964  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:03:22.964  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:03:22.964  6809  6809 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:03:22.965  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:03:22.965  6809  6809 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:03:22.965  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:03:22.965  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:03:22.965  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:03:22.965  6809  6809 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:03:22.965  6809  6809 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:03:22.972  8073  8073 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:03:22.975  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:03:22.976  8052  8096 W FormManager: Network not available. Please check & try again.
08-31 11:03:22.981  8052  8097 V FormManager: Network unavailable.
08-31 11:03:22.981  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:22.986  8052  8097 V FormManager: Network unavailable.
,08-31 11:03:22.993  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:03:22.994  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:03:22.995  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:03:22.997  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:03:23.001  4289  8098 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:03:23.005  4289  8099 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:03:23.006  4289  8099 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:03:23.044  1036  1959 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8100 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 11:03:23.198  8100  8100 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 11:03:23.199  8100  8100 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 11:03:23.215  8100  8100 V [BNRBootReceiver]: Boot Receiver Return
,08-31 11:03:23.218  8100  8100 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 11:03:23.307  1036  1922 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8124 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:03:23.308  1036  1922 I ActivityManager: Killing 7144:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-31 11:03:23.373  1036  1574 W libprocessgroup: failed to open /acct/uid_10085/pid_7144/cgroup.procs: No such file or directory
,08-31 11:03:23.404  8124  8124 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:03:23.422  8033  8033 E wpa_supplicant: USIM:  scard_init function
,08-31 11:03:23.423  8033  8033 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 11:03:23.425  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 11:03:23.425  1036  8089 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 11:03:23.425  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 11:03:23.425  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPS-AP-AVAILABLE 
08-31 11:03:23.425  1036  8089 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 11:03:23.425  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:03:23.426  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 11:03:23.426  1036  1431 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 11:03:23.427  1036  1431 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 11:03:23.427  1036  1431 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 11:03:23.428  1036  1431 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 11:03:23.428  1036  1431 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 11:03:23.433  8124  8124 D PluginManager: init()
08-31 11:03:23.439  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=199056  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 11:03:23.443  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.443  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.443  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:03:23.445  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.445  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.447  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:03:23.456  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.456  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.456  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:03:23.456  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=199073  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 11:03:23.457  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:03:23.458  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 11:03:23.467  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.467  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.470  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:03:23.537  8033  8033 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 11:03:23.538  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 11:03:23.538  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 11:03:23.538  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 11:03:23.538  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 11:03:23.538  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:03:23.538  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:03:23.539  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:03:23.539  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=199156  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:03:23.540  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=199156  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-31 11:03:23.540  1036  1431 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199157
08-31 11:03:23.541  1036  1431 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199157
08-31 11:03:23.541  1036  1431 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199158
08-31 11:03:23.542  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199159
08-31 11:03:23.543  1036  1431 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199160
08-31 11:03:23.544  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=199161  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:03:23.546  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=199163  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:03:23.547  1036  1431 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:23.547  1036  1431 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:23.548  1036  1431 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:23.548  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-31 11:03:23.548  1036  1431 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:03:23.552  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.552  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.553  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.553  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.553  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:03:23.554  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.554  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.554  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 11:03:23.554  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:03:23.554  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-31 11:03:23.555  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.557  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.557  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.559  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.560  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:03:23.560  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:03:23.560  8033  8033 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:03:23.560  8033  8033 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:03:23.561  1036  1431 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=199177  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:03:23.562  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 11:03:23.562  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=199178  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:03:23.562  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:03:23.562  1036  8089 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:03:23.562  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 11:03:23.562  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:03:23.562  1036  8089 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:03:23.562  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:03:23.562  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:03:23.563  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:03:23.563  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 11:03:23.564  1036  1431 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199180
08-31 11:03:23.564  1036  1431 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199181
08-31 11:03:23.564  1036  1431 D WifiNative-wlan0: doString: [STATUS]
08-31 11:03:23.565  1036  8089 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:03:23.565  1036  8089 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:03:23.565  1036  1431 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:03:23.567  1036  1431 I WifiServiceExtension: setVHTCapabilityType  : false
,08-31 11:03:23.573  1036  1431 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 11:03:23.573  1036  1431 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 11:03:23.576  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.576  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.576  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:03:23.576  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.576  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.577  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.579  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.579  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.579  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:03:23.580  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.580  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.586  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.588  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3434518e type 2 when 196381 com.google.android.gms} when 196381
08-31 11:03:23.591  1036  1431 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-31 11:03:23.591  1036  1484 D ConnectivityService: Got NetworkAgent Messenger
08-31 11:03:23.591  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 11:03:23.591  1036  1484 D ConnectivityService: NetworkAgent connected
08-31 11:03:23.591  1036  1431 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:03:23.591  1036  1431 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:03:23.592  1036  1431 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:03:23.592  1036  1431 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:03:23.596  1036  1431 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:03:23.597  1036  1431 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:03:23.597  1036  1431 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:03:23.598  1036  1431 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:03:23.598  1036  1431 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:03:23.601  1036  1431 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 11:03:23.603   316   916 D CommandListener: Setting iface cfg
08-31 11:03:23.605  1036  1431 E WifiStateMachine: Start Dhcp Watchdog 3
08-31 11:03:23.605  1036  8154 D DhcpStateMachine: StoppedState
08-31 11:03:23.605  1036  8154 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.605  1036  8154 D DhcpStateMachine: WaitBeforeStartState
08-31 11:03:23.605  1036  1431 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=199222  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:03:23.605  1036  1431 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=199222  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:03:23.606  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=199223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:03:23.606  1036  1431 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:03:23.607  1036  1431 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:03:23.607  1036  1431 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199224  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:03:23.608  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29200] from screen [on:0 period:-539578920] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:03:23.609  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-539578919] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:03:23.609  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:03:23.612  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.613  1036  1484 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-31 11:03:23.613  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.613  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.614  1036  1431 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.614  1036  1431 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.614  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.615  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.615  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 11:03:23.615  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
08-31 11:03:23.615  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
08-31 11:03:23.615  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 11:03:23.616  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 11:03:23.616  1036  1431 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 11:03:23.616  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 11:03:23.616  1036  1431 D WifiNative-wlan0: SET ps 0: returned true
08-31 11:03:23.616  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 11:03:23.617  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 11:03:23.617  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 11:03:23.617  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3afca031 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.617  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3afca031 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.617  1036  8154 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.617  1036  8154 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 11:03:23.617  1036  1431 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 11:03:23.618  1036  1431 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:03:23.618  1036  1431 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:03:23.618   316   916 D CommandListener: Setting iface cfg
08-31 11:03:23.618   316   916 D CommandListener: Trying to bring up wlan0
08-31 11:03:23.619  1036  1431 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 11:03:23.620  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:03:23.620  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:03:23.620  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:03:23.620  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:03:23.621  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.621  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.621  1036  1431 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.621  1036  1431 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.622  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.622  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:03:23.622  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 1,02]; created=false
08-31 11:03:23.623  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:03:23.623  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:03:23.623  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:03:23.623  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.623  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.623  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:03:23.623  1036  1431 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:03:23.624  1036  1431 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 11:03:23.624  8033  8033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 11:03:23.624  1036  1431 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 11:03:23.624  1036  1431 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:03:23.644  1036  1431 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:03:23.644  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-31 11:03:23.645  1036  1431 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:03:23.645  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:03:23.645  1036  1431 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 11:03:23.646  1036  1484 D ConnectivityService: ignoring duplicate network state non-change
08-31 11:03:23.648  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.648  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.651  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.651  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.651  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:03:23.654  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.654  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.654  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:03:23.655  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 11:03:23.655  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.655  1036  1484 D ConnectivityService: Adding iface wlan0 to network 102
08-31 11:03:23.657  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 11:03:23.660  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 11:03:23.662  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.662  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.662  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:03:23.664  1036  1431 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:03:23.664  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.664  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:03:23.665  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:03:23.666  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.671  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.672  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:23.672  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:03:23.675  1036  1484 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:03:23.676  1036  1484 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-31 11:03:23.676  1036  1484 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-31 11:03:23.677  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.677  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:03:23.677   316   916 E Netd    : netlink response contains error (File exists)
08-31 11:03:23.677  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.677  1036  1484 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 11:03:23.678  1036  1484 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 11:03:23.678  1036  1484 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
,08-31 11:03:23.678  1036  1484 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-31 11:03:23.680  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:03:23.680  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 11:03:23.680  1036  1484 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 11:03:23.680  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 11:03:23.680  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:03:23.680  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.680  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 11:03:23.680  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:23.680  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:03:23.680  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:23.680  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.680  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:03:23.680  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 11:03:23.680  1036  1484 D ConnectivityService: currentScore = 0, newScore = 20
08-31 11:03:23.680  1036  1484 D ConnectivityService:    accepting network in place of null
08-31 11:03:23.680  1036  1484 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.682  1036  1431 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.682  1036  1431 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:03:23.683   316  8158 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 11:03:23.684  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.685  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:03:23.685  1036  1484 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11,:03:23.685  1036  1484 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 11:03:23.685  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:03:23.686  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:03:23.686  1036  1484 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 11:03:23.686  1036  1484 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 11:03:23.687  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:03:23.687  1036  1484 D ConnectivityService: validation of new default Network = false
08-31 11:03:23.687  1036  1484 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 11:03:23.687  1036  1484 D DSQN    : enableDataServiceNotify 
08-31 11:03:23.687  1036  1484 D DSQN    : start dsqn bin
08-31 11:03:23.688  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:03:23.688  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.688  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-31 11:03:23.691  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:03:23.691  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:03:23.691  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:03:23.688  8159  8159 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:23.688  8159  8159 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:23.699  1036  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 11:03:23.700  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 11:03:23.700  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.700  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:23.700  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:23.701  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:03:23.706  8159  8159 E DSQN    : DSQN ssw
,08-31 11:03:23.714  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-31 11:03:23.715  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.715  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.737   316  8158 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 11:03:23.791   316  8158 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 11:03:23.808  8124  8124 W ExternalStrings: load override strings
08-31 11:03:23.808  8124  8124 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:03:23.808  8124  8124 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-31 11:03:23.809  8124  8124 D StatusProvider: onCreate
,08-31 11:03:23.820  1036  8154 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 11:03:23.826  1036  8154 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 11:03:23.826  1036  8154 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-31 11:03:23.828  8163  8163 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:23.828  8163  8163 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:03:23.844  8124  8124 V Signer  : override build config not found
08-31 11:03:23.845  8124  8124 D Signer  : value of property debug is false
,08-31 11:03:23.857  8163  8163 I dhcpcd  : version 5.5.6 starting
08-31 11:03:23.857   316   915 D LGDataListener: argv[0]=dsqncommand
08-31 11:03:23.857   316   915 D LGDataListener: argv[1]=wlan0
08-31 11:03:23.857   316   915 D LGDataListener: argv[2]=1
08-31 11:03:23.858   316   915 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 11:03:23.858  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
,08-31 11:03:23.859  1036  1116 D DSQN    : start to monitor internet connection
,08-31 11:03:23.863  8163  8163 E dhcpcd  : get_duid: m
08-31 11:03:23.863  8163  8163 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 11:03:23.863  8163  8163 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 11:03:23.884  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:03:23 GMT], X-Android-Received-Millis=[1472634203884], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472634203856]}
08-31 11:03:23.884  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 11:03:23.885  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 11:03:23.885  1036  1484 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-31 11:03:23.885  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 11:03:23.885  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:03:23.885  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:23.885  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:03:23.885  1036  1484 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-31 11:03:23.885  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 11:03:23.885  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.885  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:23.886  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:23.886  1036  1484 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.886  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-31 11:03:23.886  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 11:03:23.886  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-31 11:03:23.886  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-31 11:03:23.887  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-31 11:03:23.887  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-31 11:03:23.887  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-31 11:03:23.887  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-31 11:03:23.887  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-31 11:03:23.887  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-31 11:03:23.887  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-31 11:03:23.888  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-31 11:03:23.888  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-31 11:03:23.888  1036  1431 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.888  1036  1431 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBand,width>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:03:23.888  8124  8124 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-31 11:03:23.888  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:03:23.889  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:23.889  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-31 11:03:23.902  8124  8124 V LGMDMManager: Create singleton instance
,08-31 11:03:23.905  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:03:23.906  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.907  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:23.957  8163  8163 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:03:23.957  8163  8163 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:03:23.957  8163  8163 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:03:23.958  8163  8163 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 11:03:23.958  8124  8124 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-31 11:03:23.958  8163  8163 D dhcpcd  : wlan0: sending REQUEST (xid 0xc18d1541), next in 3.33 seconds
,08-31 11:03:23.993  8163  8163 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 11:03:24.018  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:03:24.021  8163  8163 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 11:03:24.021  8163  8163 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 11:03:24.021  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:03:24.022  8163  8163 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 11:03:24.022  8163  8163 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 11:03:24.022  8163  8163 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:03:24.023  8163  8163 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:03:24.023  8163  8163 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:03:24.024  8163  8163 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 11:03:24.034  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.045  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:24.057  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:03:24.058  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.062  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:03:24.066  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 11:03:24.074  6809  6809 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 11:03:24.080  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.080  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.092  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.098  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:24.109  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:03:24.109  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:03:24.112  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:03:24.169  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.169  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:03:24.172  8124  8173 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-31 11:03:24.176  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.185  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:24.191  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:03:24.191  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.192  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:03:24.194  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:03:24.194  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:03:24.194  6809  6809 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:03:24.194  6809  6809 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 11:03:24.197  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:03:24.197  6809  6809 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:03:24.197  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 11:03:24.197  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:03:24.197  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:03:24.197  6809  6809 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:03:24.197  6809  6809 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 11:03:24.197  6809  6809 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:03:24.200  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.200  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.213  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.219  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:24.227  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:03:24.227  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.227  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:03:24.231  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.232  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.240  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.247  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:03:24.251  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:03:24.252  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.252  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:03:24.255  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:03:24.256  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.263  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:03:24.268  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:03:24.274  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:03:24.274  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.274  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:03:24.278  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.278  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.285  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.290  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:24.296  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:03:24.296  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.296  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:03:24.297  1036  1995 I ActivityManager: Killing 7162:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-31 11:03:24.301   316  8205 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-31 11:03:24.301   316  8205 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-31 11:03:24.329  8124  8173 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:03:24.329  8124  8173 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:03:24.332   316  8205 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-31 11:03:24.405  8124  8173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-31 11:03:24.436  1036  8154 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 11:03:24.439  1036  8154 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 11:03:24.440  1036  8154 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:03:24.440  1036  8154 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 11:03:24.440  1036  8154 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 11:03:24.442  1036  8154 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:03:24.442  1036  8154 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 11:03:24.442  1036  8154 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 11:03:24.443  1036  8154 D DhcpStateMachine: RunningState
08-31 11:03:24.508  1036  1996 W libprocessgroup: failed to open /acct/uid_10093/pid_7162/cgroup.procs: No such file or directory
,08-31 11:03:24.534  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.536  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.553  8124  8173 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-31 11:03:24.560  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.568  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:03:24.575  8124  8173 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-31 11:03:24.576  8124  8173 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 11:03:24.576  8124  8173 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 11:03:24.577  8124  8173 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-31 11:03:24.577  8124  8173 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-31 11:03:24.579  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:03:24.579  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.580  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:03:24.582  8124  8173 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-31 11:03:24.585  8124  8173 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-31 11:03:24.586  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.587  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.593  2169  8208 D GCM     : Connected
,08-31 11:03:24.597  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.605  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:03:24.610  2169  8208 D GCM     : Message class com.google.e.a.a.q
08-31 11:03:24.613  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:03:24.613  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.614  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:03:24.619  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:03:24.620  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.625  8073  8073 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:03:24.630  8073  8073 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:03:24.633  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.639  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:24.647  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:03:24.647  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.648  6872  6872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:03:24.649  6872  6872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-31 11:03:24.650  6872  6872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:03:24.657  8124  8174 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:03:24.658  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:03:24.662  8073  8073 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:03:24.663  8073  8073 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:03:24.666  6809  6809 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:03:24.676  6809  6809 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:03:24.684  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:03:24.684  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:03:24.685  6872  6872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:03:24.686  6872  6872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-31 11:03:24.687  6872  6872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-31 11:03:24.691  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:03:24.693  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:03:24.696  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:03:24.698  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-31 11:03:24.700  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:03:24.702  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:03:24.705  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:03:24.707  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:03:24.710  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-31 11:03:24.713  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-31 11:03:24.715  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-31 11:03:25.518  1036  1431 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:03:25.519  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:03:25.520  1036  1431 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 11:03:25.528  1036  1431 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 11:03:25.528  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 11:03:25.529  1036  1431 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 11:03:25.530  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
,08-31 11:03:25.530  1036  1484 D ConnectivityService: identical MTU - not setting
08-31 11:03:25.530  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:03:25.530  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 11:03:25.530  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 11:03:25.530  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:25.532  1036  1484 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:25.532  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 11:03:26.617  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=70.5, 0.0, 0.0  rx=72.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-539575912] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
08-31 11:03:26.620  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=70.5, 0.0, 0.0  rx=72.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-539575909] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:03:26.620  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:03:26.641  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:03:26.659  1036  1441 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-31 11:03:26.687  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:03:26.703  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:26.726  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:26.732  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:26.737  6558  6558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:03:26.739  6558  6558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:26.749  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:03:26.753  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:03:26.764  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 11:03:26.781  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:03:26.797  8124  8173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:03:26.822  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:03:26.870  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-31 11:03:26.870  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:03:26.870  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:03:26.870  6992  6992 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:26.871  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:03:26.872  1036  1959 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-31 11:03:26.872  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:26.873  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:26.873  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 11:03:26.873  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:03:26.873  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:03:26.873  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:26.874  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:26.874  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2da46e99 removed from the list
08-31 11:03:26.874  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:26.874  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:26.874  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:26.875  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:03:26.879  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
08-31 11:03:26.879  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:03:26.879  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:03:26.879  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:03:26.879  6992  6992 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:03:26.882  6558  8239 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-31 11:03:26.883  6558  8239 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 11:03:26.883  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:03:26.883  4289  4289 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:03:26.8,85  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:03:26.887  4289  4289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:03:26.891  2846  2846 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-31 11:03:26.895  2846  2846 V DownloadManager: DownloadService onCreate
08-31 11:03:26.897  4289  8242 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:03:26.899  4289  8242 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-31 11:03:26.900  4289  8245 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:03:26.900  4289  8245 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:03:26.903  2846  8243 I DownloadManager: in removeSpuriousFiles
08-31 11:03:26.904  2846  8243 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-31 11:03:26.905  2846  8243 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3021d3d1 on behalf of 2846
08-31 11:03:26.907  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-31 11:03:26.909  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-31 11:03:26.909  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:03:26 GMT], X-Android-Received-Millis=[1472634206909], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472634206874]}
08-31 11:03:26.909  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 11:03:26.909  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-31 11:03:26.909  1036  8152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 11:03:26.909  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-31 11:03:26.909  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-31 11:03:26.909  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-31 11:03:26.909  1036  1484 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-31 11:03:26.909  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-31 11:03:26.909  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 11:03:26.909  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-31 11:03:26.910  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-31 11:03:26.910  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:03:26.910  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-31 11:03:26.910  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:26.910  2846  8243 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-31 11:03:26.910  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:03:26.910  1036  1484 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-31 11:03:26.910  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 11:03:26.910  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:03:26.910  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:26.910  1036  1484 D ,ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:03:26.911  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:03:26.912  2846  8243 I DownloadManager: in trimDatabase
08-31 11:03:26.912  2846  8243 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-31 11:03:26.912  2846  8243 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1769b137 on behalf of 2846
,08-31 11:03:26.940  1036  1574 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8247 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 11:03:26.944  4289  8242 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-31 11:03:26.951  2846  2846 V DownloadManager: DownloadService onStartCommand
08-31 11:03:26.951  2846  8244 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-31 11:03:26.952  4289  4289 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-31 11:03:26.952  4289  4289 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-31 11:03:26.953  4289  4289 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-31 11:03:26.954  4289  4289 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-31 11:03:26.957  2846  8244 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@159edc0d on behalf of 2846
08-31 11:03:26.957  4289  4289 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-31 11:03:26.958  2846  8244 V DownloadManager: processing inserted download 1
08-31 11:03:26.959  2846  8244 V DownloadManager: processing inserted download 4
08-31 11:03:26.959   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 16.876ms
08-31 11:03:26.961  2846  8244 V DownloadManager: processing inserted download 7
08-31 11:03:26.962  2846  8244 V DownloadManager: processing inserted download 8
08-31 11:03:26.963  2846  8244 V DownloadManager: processing inserted download 9
08-31 11:03:26.963  2846  8244 V DownloadManager: processing inserted download 10
08-31 11:03:26.964  2846  8244 V DownloadManager: processing inserted download 11
08-31 11:03:26.965  2846  8244 V DownloadManager: processing inserted download 12
08-31 11:03:26.966  2846  8244 V DownloadManager: processing inserted download 13
08-31 11:03:26.966  2846  8244 V DownloadManager: processing inserted download 14
08-31 11:03:26.967  2846  8244 V DownloadManager: processing inserted download 16
08-31 11:03:26.969  2846  2846 V DownloadManager: DownloadService onDestroy
08-31 11:03:26.973   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 13.339ms
,08-31 11:03:26.986   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 12.695ms
,08-31 11:03:26.995  8247  8247 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:03:26.996  8247  8247 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:03:26.997  8247  8247 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-31 11:03:26.997  8247  8247 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:03:27.071  8247  8247 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 11:03:27.092  8247  8247 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 11:03:27.117  8247  8247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:03:27.139  8247  8247 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:03:27.139  8247  8247 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:03:27.267  8247  8247 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:03:27.319  8247  8247 I HubEmail: JNI_OnLoad()
08-31 11:03:27.319  8247  8247 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:03:27.319  8247  8247 I HubEmail: registerNatives()
08-31 11:03:27.319  8247  8247 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:03:27.319  8247  8247 I HubEmail: registerNativeMethods()
08-31 11:03:27.319  8247  8247 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:03:27.320  8247  8247 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-31 11:03:27.341  8247  8278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:03:27.356  3498  3498 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:03:27.356  3498  3498 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:03:27.356  3498  3498 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 11:03:27.356  3498  3498 D PhoneState: setPdpRejectCasuse : false
,08-31 11:03:27.381   316  8281 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 11:03:27.382   316  8281 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-31 11:03:27.407  1036  1895 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8282 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 11:03:27.437   316  8281 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-31 11:03:27.479  8052  8277 V FormManager: There are no updated forms. The schedule will be deleted.
,08-31 11:03:27.485  8052  8277 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-31 11:03:27.509  1036  1052 I ActivityManager: Killing 7665:com.google.android.talk/u0a72 (adj 15): empty #17
,08-31 11:03:27.511  8282  8282 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:03:27.511  8282  8282 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:03:27.519  8282  8282 D PhoneMonitor: Register our PhoneStateListener
,08-31 11:03:27.570  1036  1051 W libprocessgroup: failed to open /acct/uid_10072/pid_7665/cgroup.procs: No such file or directory
,08-31 11:03:27.599  8282  8282 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 11:03:27.603  8282  8282 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 11:03:27.632  8282  8282 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-31 11:03:27.634  8282  8282 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-31 11:03:27.636  8282  8282 D TelephonyAutoProfiling: [parse] Load xml
08-31 11:03:27.642  8282  8282 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 11:03:27.642  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 11:03:27.642  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 11:03:27.642  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 11:03:27.642  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 11:03:27.642  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 11:03:27.642  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 11:03:27.642  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 11:03:27.643  8282  8282 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 11:03:27.643  8282  8282 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 11:03:27.651  8282  8282 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-31 11:03:27.660  1036  1732 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8313 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:03:27.662  1036  1732 I ActivityManager: Killing 7710:com.android.contacts/u0a19 (adj 15): empty #17
08-31 11:03:27.726  1036  2032 W libprocessgroup: failed to open /acct/uid_10019/pid_7710/cgroup.procs: No such file or directory
,08-31 11:03:27.762  1816  8330 I CheckinService: active receiver: enabled
08-31 11:03:27.774  1816  8330 I CheckinService: Preparing to send checkin request
08-31 11:03:27.774  1816  8330 I EventLogService: Accumulating logs since 1472634168527
,08-31 11:03:27.820  1816  8330 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 11:03:27.870   316  8333 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 11:03:27.871   316  8333 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-31 11:03:27.904   316  8333 D libc-netbsd: res_queryN name = www.google.com succeed
,08-31 11:03:27.909   316  8335 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 11:03:27.909   316  8335 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 11:03:27.909   316  8335 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-31 11:03:27.952  1036  1996 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8339 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-31 11:03:27.958  1036  1442 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-31 11:03:28.008  1036  1922 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8356 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 11:03:28.012  1036  1996 I ActivityManager: Killing 7734:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-31 11:03:28.097  1036  1895 W libprocessgroup: failed to open /acct/uid_10027/pid_7734/cgroup.procs: No such file or directory
,08-31 11:03:28.134  8356  8356 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 11:03:28.135  8356  8356 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 11:03:28.170  8356  8356 I MultiDex: VM with version 2.1.0 has multidex support
08-31 11:03:28.170  8356  8356 I MultiDex: install
08-31 11:03:28.170  8356  8356 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 11:03:28.206  1036  1922 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8374 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:03:28.207  1036  1922 I ActivityManager: Killing 7754:com.android.vending/u0a44 (adj 15): empty #17
08-31 11:03:28.326  1036  1895 W libprocessgroup: failed to open /acct/uid_10044/pid_7754/cgroup.procs: No such file or directory
,08-31 11:03:28.336  1036  1431 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-31 11:03:28.338  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-31 11:03:28.339  1036  1431 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-31 11:03:28.341  1036  1431 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-31 11:03:28.343  1036  1431 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-31 11:03:28.344  1036  1431 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-31 11:03:28.361  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b337b03 type 2 when 203943 com.google.android.gms} when 203943
,08-31 11:03:28.384  8374  8374 I art     : Almond Protected OAT
,08-31 11:03:28.397  2169  2337 I art     : Explicit concurrent mark sweep GC freed 10485(636KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.873ms total 65.593ms
08-31 11:03:28.402  8356  8356 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-31 11:03:28.452  8374  8374 D WeatherApplication: removeAccount
08-31 11:03:28.455  8374  8374 D WeatherApplication: Account.length = 0
08-31 11:03:28.455  8374  8374 E WeatherApplication: OPERATOR:OPEN
,08-31 11:03:28.460  8374  8374 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:3:28
08-31 11:03:28.463  8374  8374 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:03:28.463  8374  8374 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:03:28.465  8374  8374 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:03:28.468  8374  8374 D WeatherAncestor: connectivity changed - connection : true
,08-31 11:03:28.469  8374  8374 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-31 11:03:28.478  8374  8374 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:03:28.478  8374  8374 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:03:28.478  8374  8374 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-31 11:03:28.501  8374  8374 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-31 11:03:28.502  8374  8374 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:3:28
08-31 11:03:28.544  1036  1574 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8400 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:03:28.544  1036  1574 I ActivityManager: Killing 7792:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-31 11:03:28.621  1036  1959 W libprocessgroup: failed to open /acct/uid_10080/pid_7792/cgroup.procs: No such file or directory
,08-31 11:03:28.660  8356  8371 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:03:28.660  8356  8371 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:03:28.718   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:03:28.718   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:03:28.718   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:03:28.719  8400  8419 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 11:03:28.720   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:03:28.720   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:03:28.720   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:03:28.720  8400  8419 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 11:03:28.734   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:03:28.734   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:03:28.734   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:03:28.734  8400  8421 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-31 11:03:28.736   280   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:03:28.736   280   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:03:28.736   280   456 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:03:28.737  8400  8421 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 11:03:28.740  8417  8417 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-31 11:03:28.805  8417  8417 I dex2oat : dex2oat took 64.568ms (threads: 4)
,08-31 11:03:28.819  8356  8371 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:03:28.819  8356  8371 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:03:28.819  8356  8371 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:03:28.819  8356  8371 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:03:28.819  8356  8371 I Adreno-EGL: Remote Branch: 
08-31 11:03:28.819  8356  8371 I Adreno-EGL: Local Patches: 
08-31 11:03:28.819  8356  8371 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:03:28.913  8400  8400 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 11:03:28.920  8400  8400 I LibraryLoader: Loading: webviewchromium
08-31 11:03:28.922  8400  8400 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4548-4551)
08-31 11:03:28.923  8400  8400 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:03:28.926  8400  8400 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ffcbe4f}
,08-31 11:03:28.927  8400  8400 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:03:28.928  8400  8400 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:03:28.935  8400  8400 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 11:03:28.936  8400  8400 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:03:28.947  8400  8400 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 11:03:28.948  8400  8400 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-31 11:03:28.948  8400  8400 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-31 11:03:28.955  1036  2032 I art     : Explicit concurrent mark sweep GC freed 79515(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.939ms total 87.712ms
,08-31 11:03:28.959   321  2157 V AudioPolicyService: registerClient() client 0xb57ebac0, uid 10093
08-31 11:03:28.960  8400  8448 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 11:03:28.965  8400  8400 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:03:28.965  8400  8400 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:03:28.965  8400  8400 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:03:28.965  8400  8400 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:03:28.965  8400  8400 I Adreno-EGL: Remote Branch: 
08-31 11:03:28.965  8400  8400 I Adreno-EGL: Local Patches: 
08-31 11:03:28.965  8400  8400 I Adreno-EGL: Reconstruct Branch: 
08-31 11:03:28.985  8356  8371 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:03:28.985  8356  8371 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:03:28.985  8356  8371 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:03:28.985  8356  8371 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:03:28.985  8356  8371 I Adreno-EGL: Remote Branch: 
08-31 11:03:28.985  8356  8371 I Adreno-EGL: Local Patches: 
08-31 11:03:28.985  8356  8371 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:03:29.005  8400  8400 I NSApplication: Starting up...
,08-31 11:03:29.018  1036  1891 I ActivityManager: Killing 7513:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-31 11:03:29.055  8356  8371 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:03:29.055  8356  8371 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:03:29.055  8356  8371 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:03:29.055  8356  8371 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:03:29.055  8356  8371 I Adreno-EGL: Remote Branch: 
08-31 11:03:29.055  8356  8371 I Adreno-EGL: Local Patches: 
08-31 11:03:29.055  8356  8371 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:03:29.135  1036  1758 W libprocessgroup: failed to open /acct/uid_10037/pid_7513/cgroup.procs: No such file or directory
,08-31 11:03:29.170   316  8463 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 11:03:29.171   316  8463 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-31 11:03:29.171   316  8463 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-31 11:03:29.175  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 11:03:29.191  2169  2169 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-31 11:03:29.192  2169  2169 D c       : Getting all permits...
08-31 11:03:29.192  2169  2169 D a       : Opening database...
08-31 11:03:29.196  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-31 11:03:29.196  2169  2169 D a       : Closing database...
,08-31 11:03:29.388   316  8472 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-31 11:03:29.389   316  8472 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-31 11:03:29.422   316  8472 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-31 11:03:29.476  2169  8470 D GCM     : Connected
,08-31 11:03:29.500  2169  8470 D GCM     : Message class com.google.e.a.a.q
08-31 11:03:29.537  1816  8330 I CheckinTask: Sending checkin request (7829 bytes)
,08-31 11:03:29.654  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=45.2, 0.0, 0.0  rx=43.5 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-539572874] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:29.657  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=45.2, 0.0, 0.0  rx=43.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-539572871] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:03:29.657  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:03:29.774  1816  8330 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-31 11:03:29.785  1816  8330 I CheckinService: active receiver: disabled
,08-31 11:03:29.809  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-31 11:03:29.823  2169  2169 I GCM     : GCM config loaded
,08-31 11:03:29.842  8282  8282 V SetupWizard: Connected to Gservices successfully
,08-31 11:03:29.886  6558  8239 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-31 11:03:29.886  6558  8239 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-31 11:03:29.887  6558  8239 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:03:29.887  6558  8239 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:03:29.888  6558  8239 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-31 11:03:29.889  6558  8478 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-31 11:03:29.889  6558  8478 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-31 11:03:29.891  6558  8478 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-31 11:03:29.893  6558  8478 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-31 11:03:29.893  6558  8478 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-31 11:03:29.895  6558  8480 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 832, name: OutgoingSocketThread/Sender)
08-31 11:03:29.899  6558  8483 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 835, name: IncomingSocketThread/Receiver)
08-31 11:03:29.901  6558  8483 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 835, thread name: IncomingSocketThread/Receiver)
08-31 11:03:29.902  6558  8483 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-31 11:03:29.903  6558  8483 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 835, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-31 11:03:29.905  6558  8481 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 833, name: OutgoingSocketThread/Receiver)
08-31 11:03:29.905  6558  8481 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 833, thread name: OutgoingSocketThread/Receiver)
08-31 11:03:29.906  6558  8481 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-31 11:03:29.906  6558  8481 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 833, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-31 11:03:29.907  6558  8482 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 834, name: IncomingSocketThread/Sender)
,08-31 11:03:32.670  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=35.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-539569858] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:32.683  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=35.2 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-539569845] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:32.683  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:03:32.892  6558  6663 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 11:03:32.895  6558  6663 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 11:03:32.900  6558  6663 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@24406cd6 Bundle[{}]
,08-31 11:03:32.908  6558  6663 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:03:32.908  6558  6663 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 11:03:32.909  6558  6663 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 11:03:32.910  6558  6663 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 11:03:32.910  6558  6663 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 11:03:32.912  6558  6663 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 11:03:32.918  6558  6663 I System.out: Running OutgoingSocketThread
08-31 11:03:32.921  6558  8487 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-31 11:03:32.921  6558  8487 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 11:03:33.749  8400  8422 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-31 11:03:34.394  1036  1574 I ActivityManager: Killing 7562:com.lge.settings.easy/1000 (adj 15): empty #17
,08-31 11:03:34.426  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_7562/cgroup.procs: No such file or directory
,08-31 11:03:35.698  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=20.8, 0.0, 0.0  rx=18.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-539566831] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:35.707  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=20.8, 0.0, 0.0  rx=18.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-539566827] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:03:35.707  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:03:35.934  6558  8487 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-31 11:03:35.934  6558  8487 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-31 11:03:35.934  6558  8487 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-31 11:03:35.938  6558  8487 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:03:35.938  6558  8487 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-31 11:03:35.939  6558  8490 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-31 11:03:35.939  6558  8490 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-31 11:03:35.939  6558  8490 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:03:35.940  6558  8490 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:03:35.940  6558  8490 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-31 11:03:35.943  6558  8493 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 845, name: OutgoingSocketThread/Receiver)
08-31 11:03:35.943  6558  8493 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 845, thread name: OutgoingSocketThread/Receiver)
08-31 11:03:35.943  6558  8493 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-31 11:03:35.943  6558  8493 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 845, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-31 11:03:35.945  6558  8494 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 846, name: IncomingSocketThread/Sender)
08-31 11:03:35.947  6558  8495 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 847, name: IncomingSocketThread/Receiver)
08-31 11:03:35.947  6558  8495 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 847, thread name: IncomingSocketThread/Receiver)
08-31 11:03:35.947  6558  8495 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-31 11:03:35.947  6558  8495 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 847, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-31 11:03:35.953  6558  8492 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 844, name: OutgoingSocketThread/Sender)
,08-31 11:03:37.851  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 11:03:37.891  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 11:03:37.911  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:03:37.952  1036  1114 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8496 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 11:03:37.958  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-31 11:03:37.958  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-31 11:03:37.997  1036  1036 D administrator: Handling package changes for user 0
,08-31 11:03:38.008  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:03:38.033  8496  8496 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:03:38.099  8496  8496 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:03:38.099  8496  8496 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:03:38.110  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-31 11:03:38.110  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 11:03:38.155  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:03:38.160  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 11:03:38.166  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 11:03:38.168  2508  2508 V GmsNetworkLocationProvi: DISABLE
,08-31 11:03:38.181  8496  8540 I Babel   : MmsConfig: mnc/mcc: 0/0
08-31 11:03:38.181  8496  8540 I Babel   : MmsConfig.loadMmsSettings
,08-31 11:03:38.187  8496  8540 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 11:03:38.187  8496  8540 I Babel   : MmsConfig.loadFromDatabase
08-31 11:03:38.196  2508  2508 E GCoreFlp: Bound FusedProviderService with LocationManager
08-31 11:03:38.196  1036  1113 D LocationProviderProxy: applying state to connected service
,08-31 11:03:38.209  8496  8540 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-31 11:03:38.209  8496  8540 I Babel   : MmsConfig.loadFromResources
08-31 11:03:38.211  8496  8540 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 11:03:38.212  8496  8540 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 11:03:38.231  8496  8539 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:03:38.232  8496  8539 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:03:38.233  8496  8539 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-31 11:03:38.240  8496  8496 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:03:38.240  8496  8539 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 11:03:38.241  8496  8539 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:03:38.242  8496  8539 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:03:38.249  8496  8539 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-31 11:03:38.251  8496  8539 W VideoCapabilities: Unsupported mime video/divx
08-31 11:03:38.252  8496  8539 W VideoCapabilities: Unsupported mime video/divx311
08-31 11:03:38.253  8496  8539 W VideoCapabilities: Unsupported mime video/divx4
08-31 11:03:38.258  8496  8539 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 11:03:38.273  8496  8539 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 11:03:38.276  1816  8544 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 11:03:38.276  1816  8544 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-31 11:03:38.276  6992  6992 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:03:38.279  6992  6992 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1347e014
08-31 11:03:38.279  6992  6992 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:03:38.279  6992  6992 D AppUp4:CustFacade: isPhone : true
08-31 11:03:38.279  6992  6992 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:03:38.279  6992  6992 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-31 11:03:38.285  8496  8539 W AudioCapabilities: Unsupported mime audio/eac3
08-31 11:03:38.288  8496  8539 W AudioCapabilities: Unsupported mime audio/ac3
,08-31 11:03:38.289  8496  8539 W AudioCapabilities: Unsupported mime audio/g726
08-31 11:03:38.290  8496  8539 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 11:03:38.291  8496  8539 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 11:03:38.293  1816  4755 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-31 11:03:38.293  8496  8539 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 11:03:38.302  8496  8539 W VideoCapabilities: Unsupported mime video/theora
,08-31 11:03:38.305  1036  1051 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8546 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-31 11:03:38.308  8496  8539 W VideoCapabilities: Unsupported mime video/mjpg
08-31 11:03:38.323  1036  1996 I ActivityManager: Killing 8100:com.lge.bnr/1000 (adj 15): empty #17
,08-31 11:03:38.405  1036  1936 W libprocessgroup: failed to open /acct/uid_1000/pid_8100/cgroup.procs: No such file or directory
,08-31 11:03:38.448  8546  8546 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:03:38.448  8546  8546 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:03:38.448  8546  8546 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 11:03:38.450  8546  8546 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 11:03:38.450  8546  8546 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:03:38.500  8546  8546 I SystemConfig: BUILD Country: EU
08-31 11:03:38.500  8546  8546 I SystemConfig: BUILD Operator: OPEN
,08-31 11:03:38.536  1036  2033 I ActivityManager: Killing 8073:com.lge.sync/1000 (adj 15): empty #17
,08-31 11:03:38.641  1036  1758 W libprocessgroup: failed to open /acct/uid_1000/pid_8073/cgroup.procs: No such file or directory
,08-31 11:03:38.644  8546  8565 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-31 11:03:38.644  8546  8565 I SystemConfig: existFile = false
08-31 11:03:38.644  8546  8565 I SystemConfig: canReadFile = false
08-31 11:03:38.645  8546  8565 I SystemConfig: systemFeature RCS result false
08-31 11:03:38.645  8546  8565 D SystemConfig: refreshRcsSupport() :false
,08-31 11:03:38.704  1036  2033 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8567 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 11:03:38.729  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=10.9, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-539563800] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:38.731  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=10.9, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-539563797] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:38.731  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:03:38.762  8567  8567 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:03:38.762  8567  8567 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:03:38.763  8567  8567 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 11:03:38.763  8567  8567 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 11:03:38.883  8567  8567 I AppConfig: Total System Memory = 2995761152
,08-31 11:03:38.895  8567  8567 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-31 11:03:38.930  6558  6663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 856)
,08-31 11:03:38.932  6558  6663 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 11:03:38.932  6558  6663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
08-31 11:03:38.937  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:03:38.937  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0be55e added. We now have 3 listener(s)
08-31 11:03:39.017  1036  1936 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8592 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:03:39.023  1036  1936 I ActivityManager: Killing 6668:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 11:03:39.079  6872  6872 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 11:03:39.079  6872  6872 W System.err: android.os.DeadObjectException
08-31 11:03:39.079  6872  6872 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:03:39.079  6872  6872 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:03:39.080  6872  6872 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 11:03:39.080  6872  6872 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 11:03:39.080  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:03:39.080  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:03:39.080  6872  6872 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:03:39.080  6872  6872 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:03:39.080  6872  6872 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:03:39.080  6872  6872 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:03:39.080  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:03:39.080  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:03:39.080  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:03:39.080  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:03:39.080  6872  6872 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 11:03:39.080  6872  6872 W System.err: android.os.DeadObjectException
08-31 11:03:39.081  6872  6872 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:03:39.081  6872  6872 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:03:39.081  6872  6872 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 11:03:39.081  6872  6872 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 11:03:39.081  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:03:39.081  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:03:39.081  6872  6872 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:03:39.081  6872  6872 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:03:39.081  6872  6872 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:03:39.081  6872  6872 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:03:39.081  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:03:39.081  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:03:39.081  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:03:39.081  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:03:39.082  6872  6872 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 11:03:39.082  6872  6872 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-31 11:03:39.132  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:03:39.137  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-31 11:03:39.137  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:39.137  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:03:39.137  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:39.138  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a77d3f added. We now have 4 listener(s)
,08-31 11:03:39.138  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:39.142  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:03:39.146  1036  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_6668/cgroup.procs: No such file or directory
08-31 11:03:39.147  1036  1574 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 11:03:39.154  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:39.157  6872  6872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 11:03:39.157  6872  6872 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:39.161  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:39.165  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:03:39.166  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:03:39.167  6558  6663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:03:39.168  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:03:39.168  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:03:39.168  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:39.168  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:39.168  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:39.168  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:03:39.168  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0be55e removed from the list
08-31 11:03:39.168  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:39.168  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a77d3f removed from the list
08-31 11:03:39.171  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:39.173  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:39.173  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:39.174  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:39.226  1036  2033 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8613 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:03:39.226  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:39.227  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:39.232  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:39.232  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:39.232  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:39.232  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a77d3f not in the list
08-31 11:03:39.232  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:39.232  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:39.233  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:39.233  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:39.233  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:39.233  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a77d3f not in the list
08-31 11:03:39.233  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:39.233  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:39.233  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:39.233  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0be55e not in the list
08-31 11:03:39.234  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:03:39.234  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c45b55 added. We now have 3 listener(s)
08-31 11:03:39.235  1036  1895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:39.235  6872  6872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 11:03:39.238  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:03:39.238  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:39.238  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:03:39.238  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:39.238  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2cf96a added. We now have 4 listener(s)
08-31 11:03:39.238  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:39.241  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:03:39.244  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:39.250  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:03:39.252  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:39.252  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:03:39.253  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:03:39.253  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:03:39.253  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:03:39.253  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:39.253  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:03:39.257  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:39.259  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:39.259   348   348 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 32.093ms
08-31 11:03:39.260  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:03:39.260  1036  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:39.267  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:03:39.267  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:03:39.269  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:03:39.269  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:39.272  6558  6663 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:03:39.272  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:03:39.272  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:03:39.283   348   348 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 22.541ms
08-31 11:03:39.306   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 508us total 22.518ms
,08-31 11:03:39.320  8613  8613 D UEI.SmartControl: Quickset Services start...
,08-31 11:03:39.323  8613  8613 I UEI.SmartControl: Manufacture = LGE
,08-31 11:03:39.323  8613  8613 D UEI.SmartControl: Id = LGNevo
08-31 11:03:39.324  8613  8613 D UEI.SmartControl: File observer start...
08-31 11:03:39.325  8613  8613 E UEI.SmartControl: IR Port is disabled: false
08-31 11:03:39.325  8613  8613 D UEI.SmartControl: Starting file observer...
08-31 11:03:39.325  8613  8613 D UEI.SmartControl: Extracting JNI libs...
08-31 11:03:39.325  8613  8613 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 11:03:39.412  8613  8613 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 11:03:39.412  8613  8613 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 11:03:39.412  8613  8613 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-31 11:03:39.416  8592  8592 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 11:03:39.449  8613  8613 I UEI.SmartControl: --- Selecting new region: 6
,08-31 11:03:39.451  8613  8613 I UEI.SmartControl: Model = LG-D855
08-31 11:03:39.452  8613  8613 D UEI.SmartControl: QS Service created
08-31 11:03:39.466  8592  8592 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:03:39.466  8592  8592 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:03:39.467  8613  8613 I UEI.SmartControl: Service initServices...
08-31 11:03:39.470  8613  8613 D UEI.SmartControl: QS start get config
,08-31 11:03:39.496  8592  8592 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 11:03:39.509  8613  8613 D UEI.SmartControl: Loading JNI Libs...
08-31 11:03:39.512  8592  8592 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-31 11:03:39.512  8592  8592 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:03:39.528  8592  8592 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:03:39.528  8592  8592 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-31 11:03:39.547  1036  1936 I ActivityManager: Killing 6809:com.android.settings/1000 (adj 15): empty #17
,08-31 11:03:39.709  1036  2033 W libprocessgroup: failed to open /acct/uid_1000/pid_6809/cgroup.procs: No such file or directory
,08-31 11:03:39.718  2846  4453 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 11:03:39.721  2846  4453 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c9e29d3 on behalf of 8592
08-31 11:03:39.728  4603  8660 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-31 11:03:39.739  8592  8592 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-31 11:03:39.741  8613  8613 I UEI.SmartControl: Supports setup maps: true
,08-31 11:03:39.744  8613  8613 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:03:39.744  8613  8613 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:03:39.744  8613  8613 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-31 11:03:39.745  8613  8613 I UEI.SmartControl: ### init IR Blaster...
08-31 11:03:39.749  8613  8613 D serial_port: Configuring serial port
08-31 11:03:39.751  8613  8613 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:03:39.751  8613  8613 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:03:39.752  8613  8613 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:03:39.752  8613  8613 I UEI.SmartControl: Get version...
08-31 11:03:39.760  8592  8592 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-31 11:03:39.768  8613  8662 D UEI.SmartControl: serial port data available: 21
08-31 11:03:39.783  1036  1996 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8664 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 11:03:39.795  8613  8613 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:03:39.795  8613  8613 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:03:39.796  8613  8613 I UEI.SmartControl: QS saving settings...
08-31 11:03:39.796  8613  8613 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 11:03:39.814  8613  8662 D UEI.SmartControl: serial port data available: 4
08-31 11:03:39.839  8664  8664 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 11:03:39.843  8613  8684 I UEI.SmartControl: Device manager: loading config....
08-31 11:03:39.844  8613  8684 D UEI.SmartControl: ----------- loading internal config...
08-31 11:03:39.848  8613  8613 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 11:03:39.849  8613  8613 E UEI.SmartControl: Services init done
08-31 11:03:39.849  8613  8613 D UEI.SmartControl: QS Service init finished
08-31 11:03:39.850  8613  8613 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:03:39.850  8613  8613 D UEI.SmartControl: QS Service version code: 201091
08-31 11:03:39.851  8613  8684 E UEI.SmartControl: Loading SETTINGS...
,08-31 11:03:39.851  8613  8613 D UEI.SmartControl: Service requested: Control
08-31 11:03:39.854  6872  6872 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 11:03:39.855  1036  1895 I ActivityManager: Killing 6872:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 11:03:39.855  8613  8629 I UEI.SmartControl: ------ IControl API: 11
08-31 11:03:39.856  8613  8629 I UEI.SmartControl: Registering callback...
,08-31 11:03:39.857  8613  8684 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:03:39.863  8613  8683 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:03:39.863  8613  8683 D UEI.SmartControl: -----service ready thread exits
08-31 11:03:39.885  8613  8613 D UEI.SmartControl: Internal service binding...
08-31 11:03:39.885  1036  1995 W libprocessgroup: failed to open /acct/uid_10112/pid_6872/cgroup.procs: No such file or directory
,08-31 11:03:39.896  8664  8664 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-31 11:03:39.896  8664  8664 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-31 11:03:39.896  8664  8664 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-31 11:03:39.896  8664  8664 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 11:03:39.897  8664  8664 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 11:03:39.897  8664  8664 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-31 11:03:39.909  1036  1995 I ActivityManager: Killing 8247:com.lge.email/u0a23 (adj 15): empty #17
08-31 11:03:39.954  1036  2033 W libprocessgroup: failed to open /acct/uid_10023/pid_8247/cgroup.procs: No such file or directory
,08-31 11:03:40.223  1036  1732 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:03:40.238  4603  8660 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 510 ms] updated apps [took 510 ms] 
,08-31 11:03:41.750  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-539560778] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:41.763  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-539560766] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:03:41.763  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:03:42.273  6558  6663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:03:42.274  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:03:42.274  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:03:42.286  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:03:42.287  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:03:42.287  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:42.287  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:03:42.287  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c45b55 removed from the list
08-31 11:03:42.287  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:42.287  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2cf96a removed from the list
08-31 11:03:42.287  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:42.288  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:42.290  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:42.290  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:42.297  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:42.297  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:03:42.304  6558  6663 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:42.305  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:42.305  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:42.305  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2cf96a not in the list
08-31 11:03:42.305  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:42.305  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:42.307  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:42.308  6558  6663 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:42.308  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:42.308  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:42.308  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:42.308  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2cf96a not in the list
08-31 11:03:42.308  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:42.308  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:42.308  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:42.308  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c45b55 not in the list
08-31 11:03:42.309  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:03:42.309  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b994236 added. We now have 3 listener(s)
08-31 11:03:42.310  1036  1895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:42.313  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:03:42.313  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:42.313  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:03:42.313  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:42.313  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e31d537 added. We now have 4 listener(s)
08-31 11:03:42.313  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:42.314  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:03:42.322  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:42.328  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:42.331  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:42.331  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:03:42.333  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:42.335  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:42.336  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-31 11:03:42.337  6558  6663 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-31 11:03:42.337  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-31 11:03:42.340  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-31 11:03:42.340  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-31 11:03:42.340  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:03:42.340  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:42.344  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:03:42.344  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:03:42.345  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:03:42.346  6558  6558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:03:42.347  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:03:42.347  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-31 11:03:42.347  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:42.347  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:03:42.354  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:03:42.356  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:42.361  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:42.364  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:03:42.365  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:03:42.366  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:03:42.368  6558  8696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:03:42.370  7869  7885 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-31 11:03:42.370  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-31 11:03:42.371  6558  8696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-31 11:03:42.372  6558  6663 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:03:44.779  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-539557749] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-31 11:03:44.793  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2437 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-539557735] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-31 11:03:44.794  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:03:44.845  8613  8685 D UEI.SmartControl: Internal timer expired: 1
08-31 11:03:44.846  8613  8685 D UEI.SmartControl: unbind internal service
,08-31 11:03:44.859  8613  8613 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:03:44.863  8613  8613 D UEI.SmartControl: Service.onDestroy
08-31 11:03:44.863  8613  8613 D UEI.SmartControl: Lock is in USE false
08-31 11:03:44.863  8613  8613 D UEI.SmartControl: unbind internal service
08-31 11:03:44.863  8613  8613 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1ecce980
08-31 11:03:44.864  8613  8613 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 11:03:44.864  8613  8613 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 11:03:44.864  8613  8613 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:03:44.864  8613  8613 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:03:44.864  8613  8613 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:03:44.864  8613  8613 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:03:44.864  8613  8613 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:03:44.864  8613  8613 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:03:44.864  8613  8613 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1ecce980
,08-31 11:03:44.870  8613  8613 D serial_port: close(fd = 25)
,08-31 11:03:44.873  8613  8613 I UEI.SmartControl: Serial port is closed.
08-31 11:03:44.873  8613  8613 I UEI.SmartControl: Serial port is closed.
08-31 11:03:44.873  8613  8613 D UEI.SmartControl: Blaster closed
08-31 11:03:44.874  8613  8613 D UEI.SmartControl: Shut down QS...
08-31 11:03:44.874  8613  8613 D UEI.SmartControl: Stopping QS lib
08-31 11:03:44.874  8613  8613 D UEI.SmartControl: QS lib stop result = true
08-31 11:03:44.874  8613  8613 D UEI.SmartControl: Stopped QS lib
08-31 11:03:44.876  8613  8613 D UEI.SmartControl: Stopped file observer...
08-31 11:03:44.876  8613  8613 D UEI.SmartControl: QS shutdown complete
08-31 11:03:45.374  6558  6663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:03:45.375  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:03:45.375  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:03:45.375  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:03:45.375  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:03:45.375  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-31 11:03:45.380  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:45.380  6558  6663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:03:45.380  6558  6558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:03:45.381  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:03:45.381  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:45.381  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:45.381  6558  8696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:03:45.381  6558  8696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:03:45.382  6558  8696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:03:45.384  6558  6558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:03:45.384  6558  6558 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-31 11:03:45.384  6558  6558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:03:45.385  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:45.385  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:45.385  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:45.385  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:03:45.385  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b994236 removed from the list
08-31 11:03:45.385  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:45.385  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e31d537 removed from the list
08-31 11:03:45.385  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:45.385  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:45.386  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:45.386  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:45.387  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:45.387  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:45.387  6558  6663 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:45.387  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:45.387  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:45.388  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e31d537 not in the list
08-31 11:03:45.388  6558  6663 W org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:45.388  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:45.390  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:03:45.397  6558  6663 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:45.397  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:45.397  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:45.397  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:45.397  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e31d537 not in the list
08-31 11:03:45.397  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:45.397  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:45.397  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:45.397  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b994236 not in the list
08-31 11:03:45.399  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:03:45.399  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c48dd3 added. We now have 3 listener(s)
08-31 11:03:45.400  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:03:45.403  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:03:45.403  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:45.403  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:03:45.403  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:45.403  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1818dd10 added. We now have 4 listener(s)
08-31 11:03:45.403  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:03:45.408  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:03:45.411  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:45.415  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:03:45.416  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:45.417  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:03:45.421  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:45.423  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:45.424  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:03:45.424  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:03:45.424  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:03:45.424  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:45.424  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:03:45.428  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:03:45.428  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:03:45.435  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:03:45.436  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:03:45.438  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:03:45.438  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:45.442  6558  6663 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-31 11:03:47.812  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-539554716] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-31 11:03:47.815  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-539554713] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:03:47.816  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:03:48.450  6558  6663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:03:48.450  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:03:48.450  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:03:48.460  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:48.461  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.462  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:48.463  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:03:48.463  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c48dd3 removed from the list
08-31 11:03:48.463  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:48.463  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1818dd10 removed from the list
08-31 11:03:48.463  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:48.463  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:48.464  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.464  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:48.465  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:48.465  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:48.466  6558  6663 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:48.466  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:48.466  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:48.466  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1818dd10 not in the list
08-31 11:03:48.466  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.466  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:48.467  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:48.468  6558  6663 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:48.468  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:48.468  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:48.468  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:48.468  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1818dd10 not in the list
08-31 11:03:48.468  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:48.468  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.468  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:48.468  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c48dd3 not in the list
08-31 11:03:48.469  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:03:48.469  655,8  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1416ba3c added. We now have 3 listener(s)
08-31 11:03:48.472  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:03:48.479  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:03:48.480  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:48.480  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:03:48.480  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:48.480  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c3c5 added. We now have 4 listener(s)
08-31 11:03:48.480  6558  6663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:48.481  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:03:48.485  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:48.491  6558  6663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:03:48.493  6558  6663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:48.493  6558  6663 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:03:48.495  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:48.497  6558  6558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:48.499  6558  6663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:03:48.500  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:03:48.500  6558  6663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:03:48.501  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:48.501  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.501  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:48.501  6558  6663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:03:48.501  6558  6663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1416ba3c removed from the list
08-31 11:03:48.501  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:48.501  6558  6663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c3c5 removed from the list
,08-31 11:03:48.501  6558  6663 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:48.502  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:48.503  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.503  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:48.504  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:48.504  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:48.504  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:03:48.504  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c3c5 not in the list
08-31 11:03:48.504  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.504  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:48.505  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:03:48.505  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:03:48.505  6558  6663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:48.505  6558  6663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c3c5 not in the list
08-31 11:03:48.505  6558  6663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:48.505  6558  6663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:48.505  6558  6663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:48.505  6558  6663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1416ba3c not in the list
08-31 11:03:48.506  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:03:48.506  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:03:48.507  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:03:48.507  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:03:48.507  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:03:48.507  6558  6663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:03:50.528  6558  8697 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: My test thread name)
,08-31 11:03:50.842  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-539551686] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-31 11:03:50.845  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-539551683] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-31 11:03:50.845  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 11:03:52.525  6558  6663 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 866
,08-31 11:03:52.525  6558  6663 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 866, name: My test thread name)
,08-31 11:03:52.542  6558  8698 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
08-31 11:03:52.542  6558  8698 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-31 11:03:52.542  6558  8698 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-31 11:03:52.547  6558  6663 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-31 11:03:52.557  6558  8699 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
,08-31 11:03:52.558  6558  8699 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 871, thread name: My test thread name): Test exception.
08-31 11:03:52.558  6558  8699 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-31 11:03:52.561  6558  6663 I jxcore-log: Total number of executed tests:  82
08-31 11:03:52.561  6558  6663 I jxcore-log: 
08-31 11:03:52.562  6558  6663 I jxcore-log: Number of passed tests:  82
08-31 11:03:52.562  6558  6663 I jxcore-log: 
08-31 11:03:52.562  6558  6663 I jxcore-log: Number of failed tests:  0
08-31 11:03:52.562  6558  6663 I jxcore-log: 
08-31 11:03:52.563  6558  6663 I jxcore-log: Number of ignored tests:  0
08-31 11:03:52.563  6558  6663 I jxcore-log: 
08-31 11:03:52.563  6558  6663 I jxcore-log: Total duration:  111912
08-31 11:03:52.563  6558  6663 I jxcore-log: 
08-31 11:03:52.564  6558  6663 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 11:03:52.564  6558  6663 I jxcore-log: 
08-31 11:03:52.565  6558  6663 I jxcore-log: My device name is: LGE-LG-D855
08-31 11:03:52.565  6558  6663 I jxcore-log: 
08-31 11:03:52.574  6558  8697 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,08-31 11:03:52.585  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.585  6558  6663 I jxcore-log: 
08-31 11:03:52.586  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.586  6558  6663 I jxcore-log: 
08-31 11:03:52.587  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.587  6558  6663 I jxcore-log: 
08-31 11:03:52.589  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.589  6558  6663 I jxcore-log: 
08-31 11:03:52.590  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.590  6558  6663 I jxcore-log: 
08-31 11:03:52.599  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:03:52.599  6558  6663 I jxcore-log: 
,08-31 11:03:52.604  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.604  6558  6663 I jxcore-log: 
08-31 11:03:52.606  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.606  6558  6663 I jxcore-log: 
08-31 11:03:52.606  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.606  6558  6663 I jxcore-log: 
08-31 11:03:52.607  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.607  6558  6663 I jxcore-log: 
08-31 11:03:52.609  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.609  6558  6663 I jxcore-log: 
08-31 11:03:52.610  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.610  6558  6663 I jxcore-log: 
08-31 11:03:52.611  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.611  6558  6663 I jxcore-log: 
08-31 11:03:52.613  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.613  6558  6663 I jxcore-log: 
08-31 11:03:52.614  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.614  6558  6663 I jxcore-log: 
08-31 11:03:52.614  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.614  6558  6663 I jxcore-log: 
08-31 11:03:52.615  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.615  6558  6663 I jxcore-log: 
08-31 11:03:52.616  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.616  6558  6663 I jxcore-log: 
08-31 11:03:52.617  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.617  6558  6663 I jxcore-log: 
08-31 11:03:52.618  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.618  6558  6663 I jxcore-log: 
08-31 11:03:52.618  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.618  6558  6663 I jxcore-log: 
08-31 11:03:52.619  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.619  6558  6663 I jxcore-log: 
08-31 11:03:52.620  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.620  6558  6663 I jxcore-log: 
,08-31 11:03:52.625  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.625  6558  6663 I jxcore-log: 
08-31 11:03:52.626  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.626  6558  6663 I jxcore-log: 
08-31 11:03:52.627  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.627  6558  6663 I jxcore-log: 
08-31 11:03:52.627  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.627  6558  6663 I jxcore-log: 
08-31 11:03:52.628  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.628  6558  6663 I jxcore-log: 
08-31 11:03:52.629  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.629  6558  6663 I jxcore-log: 
08-31 11:03:52.630  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.630  6558  6663 I jxcore-log: 
08-31 11:03:52.632  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:03:52.632  6558  6663 I jxcore-log: 
08-31 11:03:52.633  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.633  6558  6663 I jxcore-log: 
08-31 11:03:52.634  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:03:52.634  6558  6663 I jxcore-log: 
08-31 11:03:52.634  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.634  6558  6663 I jxcore-log: 
08-31 11:03:52.635  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.635  6558  6663 I jxcore-log: 
08-31 11:03:52.637  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.637  6558  6663 I jxcore-log: 
08-31 11:03:52.638  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.638  6558  6663 I jxcore-log: 
08-31 11:03:52.638  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.638  6558  6663 I jxcore-log: 
08-31 11:03:52.639  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.639  6558  6663 I jxcore-log: 
08-31 11:03:52.640  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.640  6558  6663 I jxcore-log: 
,08-31 11:03:52.645  6558  6663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:52.645  6558  6663 I jxcore-log: 
08-31 11:03:52.903  8700  8700 D AndroidRuntime: 
08-31 11:03:52.903  8700  8700 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:03:52.907  8700  8700 D AndroidRuntime: CheckJNI is OFF
,08-31 11:03:53.087  8700  8700 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:03:53.100  1036  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-31 11:03:53.100  1036  1114 I ActivityManager: Killing 6558:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-31 11:03:53.144  1036  2032 I WindowState: WIN DEATH: Window{38b659e7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:03:53.144  1036  1474 D WifiService: Client connection lost with reason: 4
,08-31 11:03:53.151  1036  2032 D InputDispatcher: Window went away: Window{38b659e7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:03:53.224  1036  1114 I ActivityManager:   Force finishing activity ActivityRecord{376faca0 u0 com.test.thalitest/.MainActivity t6}
,08-31 11:03:53.259   343   364 E GBMv2   : DFP En is all cleared set to be enabled
08-31 11:03:53.262  1036  1574 W ActivityManager: Spurious death for ProcessRecord{1c987caf 6558:com.test.thalitest/u0a118}, curProc for 6558: null
08-31 11:03:53.262  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-31 11:03:53.267  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{376faca0 u0 com.test.thalitest/.MainActivity t6 f}
08-31 11:03:53.267  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{376faca0 u0 com.test.thalitest/.MainActivity t6 f}
08-31 11:03:53.302  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-31 11:03:53.302  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1eaf89c9 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 11:03:53.303  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 11:03:53.304  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-31 11:03:53.306  1942  2670 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 11:03:53.306  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 11:03:53.306  2034  2123 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-31 11:03:53.307  1942  2670 D SplitWindowPolicy: topRunningActivity=ActivityInfo{272f18ce co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 11:03:53.314  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-31 11:03:53.323  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 11:03:53.323  2725  2725 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-31 11:03:53.326  4603  4603 I art     : Explicit concurrent mark sweep GC freed 15669(894KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 605us total 49.748ms
08-31 11:03:53.328  7869  7869 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 11:03:53.328  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:03:53.342  8124  8124 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 11:03:53.346  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:03:53.363  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:03:53.378  4498  4498 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 11:03:53.378  4498  4498 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 11:03:53.378  4498  4498 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 11:03:53.378  4498  4498 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 11:03:53.378  4498  4498 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:03:53.378  4498  4498 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:03:53.378  4498  4498 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:03:53.378  4498  4498 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:03:53.379  4498  4498 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:03:53.379  4498  4498 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:03:53.379  4498  4498 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:03:53.379  4498  4498 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-31 11:03:53.384  1036  1113 W InputMethodInfo: Duplicated subtype definition found: , voice
08-31 11:03:53.403  2508  2646 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 11:03:53.407  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-31 11:03:53.409  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 11:03:53.410  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-31 11:03:53.410  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 11:03:53.411  1602  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-31 11:03:53.411  1602  1647 D KeyguardModel: createShortcutInfo...
08-31 11:03:53.411  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 11:03:53.411  2725  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 11:03:53.414  1602  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 11:03:53.414  1602  1647 D KeyguardModel: createShortcutInfo...
,08-31 11:03:53.418  2169  2169 I ConfigService: onCreate
08-31 11:03:53.423  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 11:03:53.425  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 11:03:53.426  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 11:03:53.426  1602  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:03:53.427  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 11:03:53.428  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 11:03:53.428  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 11:03:53.430  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:03:53.430  1602  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 11:03:53.435  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 11:03:53.438  2169  2169 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 11:03:53.438  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-31 11:03:53.438  2725  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-31 11:03:53.445  2169  2169 I ConfigService: onBind returning update interface
08-31 11:03:53.445  2725  2784 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:03:53.446  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 11:03:53.446  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 11:03:53.451  1602  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 11:03:53.451  1602  1647 D KeyguardModel: createShortcutInfo...
08-31 11:03:53.452  2169  2169 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 11:03:53.452  2169  2169 I ConfigService: onBind returning config service
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , display: false
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , animation: false }
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , display: false
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , animation: false }
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , display: false
08-31 11:03:53.454  2034  2034 I GBoardWebViewUtils: , animation: false }
,08-31 11:03:53.456  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 11:03:53.456  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:03:53.464  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:03:53.464  1602  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 11:03:53.465  2034  8732 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 11:03:53.465  1036  1732 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:03:53.465  1036  1732 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:03:53.467  1602  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 11:03:53.467  1602  1647 D KeyguardModel: createShortcutInfo...
08-31 11:03:53.471  1602  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:03:53.472  1602  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:03:53.472  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 11:03:53.472  2169  2169 I ConfigService: onDestroy
08-31 11:03:53.472  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:03:53.495  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 11:03:53.496  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 11:03:53.498  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:03:53.498  1602  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 11:03:53.500  1602  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 11:03:53.500  1602  1647 D KeyguardModel: createShortcutInfo...
08-31 11:03:53.501  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-31 11:03:53.501  1869  1869 D SplitUIService: removed split : 
,08-31 11:03:53.507  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-31 11:03:53.507  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 11:03:53.514  1602  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 11:03:53.514  1602  1647 D KeyguardModel: createShortcutInfo...
08-31 11:03:53.516  1602  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 11:03:53.516  1602  1647 D KeyguardModel: createShortcutInfo...
,08-31 11:03:53.521  1816  8734 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 11:03:53.523  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:03:53.523  1602  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 11:03:53.524  1602  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 11:03:53.524  1602  1647 D KeyguardModel: createShortcutInfo...
08-31 11:03:53.525  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:03:53.526  1602  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 11:03:53.542  1602  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 11:03:53.542  1602  1647 D KeyguardModel: createShortcutInfo...
,08-31 11:03:53.544  1036  1960 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:03:53.545  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:03:53.545  1602  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:03:53.545  7869  7869 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:03:53.549  1602  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 11:03:53.549  1602  1647 D KeyguardModel: createShortcutInfo...
08-31 11:03:53.549  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-31 11:03:53.549  1869  1869 I SplitUIService: split app #11
08-31 11:03:53.552  1036  1036 I art     : Explicit concurrent mark sweep GC freed 45604(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 6.157ms total 258.639ms
08-31 11:03:53.559  1036  1124 I art     : WaitForGcToComplete blocked for 114.930ms for cause Explicit
08-31 11:03:53.579  6992  6992 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-31 11:03:53.584  5949  8742 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-31 11:03:53.585  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-31 11:03:53.585  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 11:03:53.591  1816  8743 I PeopleContactsSync: CP2 sync disabled
,08-31 11:03:53.592  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-31 11:03:53.609  1816  4755 I Icing   : doRemovePackageData com.test.thalitest
08-31 11:03:53.611  1036  1922 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:03:53.620  2371  8744 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 11:03:53.620  1036  1036 D administrator: Handling package changes for user 0
08-31 11:03:53.641   330   444 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-31 11:03:53.642  3204  8747 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-31 11:03:53.645  1036  1936 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8748 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-31 11:03:53.662  1816  8741 W GmsApplication: Using Auth Proxy for data requests.
,08-31 11:03:53.672  1816  8741 W GmsApplication: Using Auth Proxy for data requests.
,08-31 11:03:53.701  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-31 11:03:53.703  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:03:53.705  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 11:03:53.706  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 11:03:53.707  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 11:03:53.708  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-31 11:03:53.712  8748  8748 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:03:53.713  8748  8748 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:03:53.713  8748  8748 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:03:53.713  8748  8748 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 11:03:53.722  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{267e31c4 u0 com.lge.launcher2/.Launcher t5} time:229351
08-31 11:03:53.726  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 11:03:53.726  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 11:03:53.726  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 11:03:53.729  1816  8736 I art     : Explicit concurrent mark sweep GC freed 40108(2MB) AllocSpace objects, 29(464KB) LOS objects, 51% free, 30MB/62MB, paused 947us total 30.049ms
08-31 11:03:53.730  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 11:03:53.730  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:03:53.731  1816  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-31 11:03:53.731  1816  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-31 11:03:53.731  1036  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-31 11:03:53.731  2034  2159 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 11:03:53.731  2034  2159 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-31 11:03:53.733  1816  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-31 11:03:53.746  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 11:03:53.747  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 11:03:53.747  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:03:53.758  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 11:03:53.759  2581  2581 D [Concierge]Service: onStartCommand(). Type : 8
08-31 11:03:53.759  2581  2581 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-31 11:03:53.760  2581  2581 D [Concierge]Service: Update widget ID : 11
08-31 11:03:53.761  2034  2034 D [Concierge]WidgetView: change position of spinner
08-31 11:03:53.762  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472634233762
08-31 11:03:53.763  2581  2581 D [Concierge]Service: onStartCommand(). Type : 0
,08-31 11:03:53.788  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 475369355
,08-31 11:03:53.789  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 11:03:53.789  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 11:03:53.791  1036  1124 I art     : Explicit concurrent mark sweep GC freed 10929(658KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.422ms total 228.983ms
08-31 11:03:53.792  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@68cceda
08-31 11:03:53.792  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 11:03:53.795  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 11:03:53.795  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:03:53.800  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 11:03:53.800  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 11:03:53.800  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 11:03:53.800  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472634031939, New one : 1472634233762
08-31 11:03:53.801  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-31 11:03:53.801  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-31 11:03:53.802  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:03:53.803  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 11:03:53.804  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 11:03:53.805  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 11:03:53.806  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 11:03:53.807  8748  8748 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 11:03:53.807  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 11:03:53.812  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:03:53.812  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:03:53.820  8748  8748 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-31 11:03:53.850  8748  8748 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:03:53.856  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 11:03:53.864  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 11:03:53.864  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-31 11:03:53.866  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:03:53.867  8700  8700 D AndroidRuntime: Shutting down VM
,08-31 11:03:53.870  1036  1431 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-539548658] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:03:53.871  1036  1431 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-539548657] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:03:53.871  1036  1431 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:03:53.884  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15e50704 time:229513
,08-31 11:03:53.886  8748  8748 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:03:53.886  8748  8748 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:03:53.911  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:03:53.915  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 11:03:53.920  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 11:03:53.932  8748  8748 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-31 11:03:53.941  1036  1959 I ActivityManager: Killing 8052:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-31 11:03:53.989  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-31 11:03:54.023  2034  2868 I GBoardtInterface: onReloaded()
,08-31 11:03:54.024  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-31 11:03:54.032  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 11:03:54.032  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-31 11:03:54.032  1036  1996 W libprocessgroup: failed to open /acct/uid_10026/pid_8052/cgroup.procs: No such file or directory
08-31 11:03:54.033  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-31 11:03:54.034  2725  2741 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-31 11:03:54.036  2725  2783 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:03:54.036  8124  8124 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 11:03:54.066  1036  1732 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8773 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 11:03:54.072  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-31 11:03:54.074  2725  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 11:03:54.074  2725  4471 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 11:03:54.077  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-31 11:03:54.079  2725  2784 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:03:54.109  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8790 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 11:03:54.111  2725  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 11:03:54.111  2725  4471 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 11:03:54.111  2725  4471 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-31 11:03:54.111  2725  4471 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-31 11:03:54.114  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-31 11:03:54.114  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-31 11:03:54.115  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-31 11:03:54.115  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 11:03:54.117  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-31 11:03:54.117  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-31 11:03:54.152  1036  1960 I ActivityManager: Killing 8313:com.android.chrome/u0a57 (adj 15): empty #17
,08-31 11:03:54.154  8773  8773 W FileUtils: Failed to chmod(/data/data/com.lge.lifetracker/databases/lifetracker2.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-31 11:03:54.221  1036  1995 W libprocessgroup: failed to open /acct/uid_10057/pid_8313/cgroup.procs: No such file or directory

```
